**Project ID:** [plumID:19.000]({{ '/' | absolute_url }}eggs-19/000/)  
Stderr for source:  model/plumed-ves.dat   
(download [gzipped raw stdout](plumed-ves.dat.plumed.stdout.txt.gz))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:661, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: VES_DELTA_F LABEL=ves ARG=p.x TEMP=1 FILE_F0=fesA.data FILE_F1=fesB.data BIASFACTOR=10.0 AV_STRIDE=500 M_STEP=0.05 PRINT_STRIDE=100 ALPHA_FILE=Alpha.data
Maybe a missing space or a typo?
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] *** Process received signal ***
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] Signal: Aborted (6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] Signal code:  (-6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f788aa454b0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f788aa45428]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f788aa4702a]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f788b07f84d]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f788b07d6b6]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f788b07d701]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f788b07d919]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 7] plumed[0x40ec95]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 8] plumed[0x40f092]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [ 9] plumed[0x409fe0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f788aa30830]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] [11] plumed[0x40a0a9]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07359] *** End of error message ***
</pre>
{% endraw %}
