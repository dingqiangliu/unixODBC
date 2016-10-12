

bugs fixed
==========

"General error: fseek fails" issue when BIEE getting huge dataset from Vertica
----------
Note: should add "CFLAGS=-D_FILE_OFFSET_BITS=64" when configure, eg.
<code><pre>
  CFLAGS=-D_FILE_OFFSET_BITS=64 ./configure --disable-gui --enable-threads --disable-drivers --prefix=/usr/local/unixODBC
  make && make install
</code></pre>






