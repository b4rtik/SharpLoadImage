# SharpLoadImage

Hide assembly into png images

SharpImage small tool to embed .Net assembly on it, useful to hide traffic of an implant.

The main code is a porting of [Invoke-PSImage](https://github.com/peewpw/Invoke-PSImage) .

```
usage: SharpLoadImage -a [path to assembly] -i [path to image source] -o [path to output file]
```

Image source can be most image types but output will be allways png.

The tool generare the image with assembly embedded and test it's execution

