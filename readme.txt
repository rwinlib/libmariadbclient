Build with Rtools gcc 4.9.3.

Hack: library seems to redefine pthread stuff on windows. 
In libmariadb sources: my_pthread.c: remove pthread stuff in #ifdef WIN32.
