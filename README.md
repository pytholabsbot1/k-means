# k-means

Creates color pallete of provided input image 

Installation:
```
$ pip install color-pallete 
```


Usage :

```
from color_pallete import ColorPallete as cp

c = cp(r'path\to\img.jpg') ##image path any extension

c.process() ## fit kmeans to image array

c.save('out.jpg') ## save pallete as image
```
