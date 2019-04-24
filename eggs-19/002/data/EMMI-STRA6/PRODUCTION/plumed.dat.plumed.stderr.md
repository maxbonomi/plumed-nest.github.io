**Project ID:** [plumID:19.002]({{ '/' | absolute_url }}eggs-19/002/)  
Stderr for source:  EMMI-STRA6/PRODUCTION/plumed.dat   
(download [gzipped raw stdout](plumed.dat.plumed.stdout.txt.gz))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:242, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action EMMI with label emmi : keyword SIGMA_MEAN is compulsory for this action
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] *** Process received signal ***
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] Signal: Aborted (6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] Signal code:  (-6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fc6740674b0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fc674067428]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fc67406902a]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fc6746a184d]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fc67469f6b6]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fc67469f701]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fc67469f919]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 7] plumed[0x40ec95]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 8] plumed[0x40f092]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [ 9] plumed[0x409fe0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fc674052830]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] [11] plumed[0x40a0a9]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07314] *** End of error message ***
</pre>
{% endraw %}
