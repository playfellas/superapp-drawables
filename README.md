### Generate grayscale concrete images

```
$ cd concrete
$ for f in `ls`; do convert $f -colorspace Gray grayscale/"${f%_*_*_*_*.png}"_grayscale.png; done
```
