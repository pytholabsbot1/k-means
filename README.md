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
![alt text](https://github.com/pytholabsbot1/k-means/raw/master/test_image.png)
![alt text](https://github.com/pytholabsbot1/k-means/raw/master/pallete.png)

```
from color_pallete import ImageFilter

img = ImageFilter('dog.jpg',k=3) 
img.save('new_img.jpg')

```
![alt text](https://github.com/pytholabsbot1/k-means/raw/master/filtered_img.png)
