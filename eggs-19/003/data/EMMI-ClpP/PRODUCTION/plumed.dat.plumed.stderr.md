**Project ID:** [plumID:19.003]({{ '/' | absolute_url }}eggs-19/003/)  
Stderr for source:  EMMI-ClpP/PRODUCTION/plumed.dat   
(download [gzipped raw stdout](plumed.dat.plumed.stdout.txt.gz))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:242, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action EMMI with label emmi : keyword SIGMA_MEAN is compulsory for this action
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] *** Process received signal ***
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] Signal: Aborted (6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] Signal code:  (-6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f13919974b0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f1391997428]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f139199902a]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f1391fd184d]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f1391fcf6b6]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f1391fcf701]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f1391fcf919]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 7] plumed[0x40ec95]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 8] plumed[0x40f092]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [ 9] plumed[0x409fe0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f1391982830]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] [11] plumed[0x40a0a9]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07302] *** End of error message ***
</pre>
{% endraw %}
