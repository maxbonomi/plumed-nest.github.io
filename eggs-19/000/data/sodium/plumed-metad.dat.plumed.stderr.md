**Project ID:** [plumID:19.000]({{ '/' | absolute_url }}eggs-19/000/)  
Stderr for source:  sodium/plumed-metad.dat   
(download [gzipped raw stdout](plumed-metad.dat.plumed.stdout.txt.gz))  
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
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] *** Process received signal ***
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] Signal: Aborted (6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] Signal code:  (-6)
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fb02542d4b0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fb02542d428]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fb02542f02a]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fb025a6784d]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fb025a656b6]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fb025a65701]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fb025a65919]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 7] plumed[0x40ec95]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 8] plumed[0x40f092]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [ 9] plumed[0x409fe0]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fb025418830]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] [11] plumed[0x40a0a9]
[travis-job-7d693aa1-84e5-4a39-9951-fc14a6acdaad:07367] *** End of error message ***
</pre>
{% endraw %}
