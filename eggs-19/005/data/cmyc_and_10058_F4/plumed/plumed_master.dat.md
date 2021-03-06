**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs-19/005/)  
Source: cmyc_and_10058_F4/plumed/plumed_master.dat  
Originally used with plumed version: 2.5  
Stable: [raw gzipped stdout](plumed_master.dat.plumed.stdout.txt.gz) - [stderr](plumed_master.dat.plumed.stderr)  
Master: [raw gzipped stdout](plumed_master.dat.plumed_master.stdout.txt.gz) - [stderr](plumed_master.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#this is the master_plumed.dat file for metainference metadynamics simulations</span>

<span style="color:blue"># define groups</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> STRUCTURE=../system/template.pdb
prot: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=1-191
drug: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=192-218
first: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=1-76
second: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=77-119
third: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=120-191
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=prot ENTITY1=drug

<span style="color:blue">#include file with definition of metadynamics CVs</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="meta_cv_plumed.dat.html">meta_cv_plumed.dat</a>

<span style="color:blue">#activate parallel bias metadynamics </span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a> ... <span style="color:blue">#activating start</span>
LABEL=pbmetad <span style="color:blue">#to print out things</span>
ARG=ahelixright,betasheet,ahelixleft,polypro,rgyr,ohbond,fstdr,scddr,trddr
PACE=500 HEIGHT=1.2 BIASFACTOR=10 WALKERS_MPI
SIGMA=1.01,0.89,0.41,0.72,0.05,0.71,0.05,0.05,0.05
FILE=HILLS_ahelixright,HILLS_betasheet,HILLS_ahelixleft,HILLS_polypro,HILLS_rgyr,HILLS_ohbond,HILLS_fstdr,HILLS_scddr,HILLS_trddr
GRID_MIN=-2,-2,-2,-2,0.2,0,0,0,0
GRID_MAX=20,20,20,20,1.4,30,5.2,5.2,5.2
<span style="color:blue">#actual min and max are slightly different, but allowing for gaussian distribution around it</span>
... <a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a>

<span style="color:blue">#include file with definition of experimental CVs</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="exp_cv_plumed.dat.html">exp_cv_plumed.dat</a>

<span style="color:blue"># metainference stuff</span>
mi_cs_ha: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_i_n_f_e_r_e_n_c_e.html">METAINFERENCE</a> ARG=(cs\.ha_.*),pbmetad.bias PARARG=(cs\.expha_.*) REWEIGHT NOISETYPE=GAUSS SIGMA0=1.0 SIGMA_MIN=0.00001 SIGMA_MAX=10.0 DSIGMA=0.5 SIGMA_MEAN0=7.3 
mi_cs_ca: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_i_n_f_e_r_e_n_c_e.html">METAINFERENCE</a> ARG=(cs\.ca_.*),pbmetad.bias PARARG=(cs\.expca_.*) REWEIGHT NOISETYPE=GAUSS SIGMA0=1.0 SIGMA_MIN=0.00001 SIGMA_MAX=10.0 DSIGMA=0.5 SIGMA_MEAN0=7.3 
mi_cs_cb: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_i_n_f_e_r_e_n_c_e.html">METAINFERENCE</a> ARG=(cs\.cb_.*),pbmetad.bias PARARG=(cs\.expcb_.*) REWEIGHT NOISETYPE=GAUSS SIGMA0=1.0 SIGMA_MIN=0.00001 SIGMA_MAX=10.0 DSIGMA=0.5 SIGMA_MEAN0=7.3 

<span style="color:blue">#print out relavant info</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=200 ARG=ahelixright,betasheet,ahelixleft,polypro,rgyr,ohbond,fstdr,scddr,trddr,pbmetad.bias FILE=COLVAR_PBMETAD
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=200 ARG=mi_cs_ha.*,mi_cs_ca.*,mi_cs_cb.* FILE=COLVAR_MI
</pre>{% endraw %}
