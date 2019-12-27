# Style Transfer

Using the `neural-style`. Usage:

``` bash
python neural_style.py --contents content/fall-leaves.JPG --styles styles/renoir-landscape.jpg --output Output/fall-leaves-renoir.jpg
```

Download imagenet:

``` bash
curl http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-16.mat --output imagenet-vgg-verydeep-19.mat
```