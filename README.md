# Minimal debian package steps

## build package
dpkg-deb --build helloworld

## Install package
dpkg -i helloworld.deb

src/hello.sh -> /usr/local/bin

## Remove package

dpkg -r helloworld.deb

