# F_API
g++ -o main *.o -l:thostmduserapi.so -l:thosttraderapi.so -L/usr/local/include/


exec:
luit -encoding gbk ./main



#IB_API

https://github.com/rudimeier/twsapi


1 PosixSocketClient/Makefile.am:8: but option 'subdir-objects' is disabled
autoreconf: automake failed with exit status: 1

  in file PosixSocketClient/Makefile.am 
  AUTOMAKE_OPTIONS = subdir-objects 


2 PosixSocketClient/Makefile.am:7: error: Libtool library used but 'LIBTOOL' is undefined
PosixSocketClient/Makefile.am:7:   The usual way to define 'LIBTOOL' is to add 'LT_INIT'
PosixSocketClient/Makefile.am:7:   to 'configure.ac' and run 'aclocal' and 'autoconf' again.
PosixSocketClient/Makefile.am:7:   If 'LT_INIT' is in 'configure.ac', make sure
PosixSocketClient/Makefile.am:7:   its definition is in aclocal's search path.
autoreconf: automake failed with exit status: 1


  sudo apt-get install libtool
