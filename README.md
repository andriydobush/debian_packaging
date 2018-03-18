#Minimal debuan package steps

## build package
dpkg-deb --build helloworld

## Install package
dpkg -i helloworld.deb

src/hello.sh will be installed to /usr/local/bin

## Remove package

dpkg -r helloworld.deb

