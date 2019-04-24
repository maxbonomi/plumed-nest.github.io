**Project ID:** [plumID:19.007]({{ '/' | absolute_url }}eggs-19/007/)  
Stderr for source:  EMMI-MT/plumed.dat   
(download [gzipped raw stdout](plumed.dat.plumed.stdout.txt.gz))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:242, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action WHOLEMOLECULES with label @4 : cannot understand the following words from the input line : ADDREFERENCE, REF0=3.217,4.340,6.195
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] *** Process received signal ***
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] Signal: Aborted (6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] Signal code:  (-6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f83ac1584b0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f83ac158428]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f83ac15a02a]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f83ac79284d]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f83ac7906b6]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f83ac790701]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f83ac790919]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 7] plumed[0x40ec95]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 8] plumed[0x40f092]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [ 9] plumed[0x409fe0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f83ac143830]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] [11] plumed[0x40a0a9]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07215] *** End of error message ***
</pre>
{% endraw %}
