**Project ID:** [plumID:19.000]({{ '/' | absolute_url }}eggs-19/000/)  
Stderr for source:  alanine/plumed-ves.dat   
(download [gzipped raw stdout](plumed-ves.dat.plumed.stdout.txt.gz))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:661, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: VES_DELTA_F LABEL=ves ARG=psi TEMP=300.0 FILE_F0=fesB.data FILE_F1=fesA.data BIASFACTOR=10.0 AV_STRIDE=500 M_STEP=0.05 PRINT_STRIDE=100 ALPHA_FILE=Alpha.data
Maybe a missing space or a typo?
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] *** Process received signal ***
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] Signal: Aborted (6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] Signal code:  (-6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fa493edc4b0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fa493edc428]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fa493ede02a]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fa49451684d]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fa4945146b6]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fa494514701]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fa494514919]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 7] plumed[0x40ec95]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 8] plumed[0x40f092]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [ 9] plumed[0x409fe0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fa493ec7830]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] [11] plumed[0x40a0a9]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07344] *** End of error message ***
</pre>
{% endraw %}
