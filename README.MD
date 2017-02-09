# Pi-Pirates Raspbian base

The image is created using debootstrap 

If you want to build this image yourself, run the following to generate the compressed chroot.

```
$ rm *.tar.xz
$ ./mkimage.sh
$ ./build-docker-image.sh rasbian jessie
```

build docker images expect the authetication enviroment variables in your bashrc or whatever. 


