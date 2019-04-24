**Project ID:** [plumID:19.000]({{ '/' | absolute_url }}eggs-19/000/)  
Stderr for source:  sodium/plumed-metad.dat   
(download [gzipped raw stdout](plumed-metad.dat.plumed_master.stdout.txt.gz))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:661, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: DEBYE_STRUCTURE_FACTOR LABEL=cv CUTOFF=10.5 ACTIVE_Q=2.070595
Maybe a missing space or a typo?
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] *** Process received signal ***
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] Signal: Aborted (6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] Signal code:  (-6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fe5a087c4b0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fe5a087c428]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fe5a087e02a]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fe5a0eb684d]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fe5a0eb46b6]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fe5a0eb4701]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fe5a0eb4919]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 7] plumed_master[0x40eca5]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 8] plumed_master[0x40f0a2]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [ 9] plumed_master[0x409ff0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fe5a0867830]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] [11] plumed_master[0x40a0b9]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07370] *** End of error message ***
</pre>
{% endraw %}
