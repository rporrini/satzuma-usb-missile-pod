### Docker image for controlling the Satzuma USB missile pod

![The satzuma usb missile pod](http://ecx.images-amazon.com/images/I/41mOLPwwQpL._SY300_QL70_.jpg)

### Run
```
docker run -it --privileged -v /dev/bus/usb:/dev/bus/usb rporrini/satzuma-usb-missile-pod
```

### Credits

* Thanks to https://github.com/momentofgeekiness/pymissile-ng
