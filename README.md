# PRO-C168-Boilerplate
### Download the model from here : https://sketchfab.com/3d-models/pizza-35d8c71791944a6c9f2082a1ad82827d

Hiro markers to display content over that, which is a standard marker.

create our own marker like we created image trackers.

EX: start designing the AR content for the hotel menu card.

What if you can actually see the food ingredients and how the food will look in AR?

To display the food and its ingredients in AR, we are going to use our own markers. These are called pattern markers.
SOLUTION:

Now, to create pattern markers we can take an image and create the pattern marker of that.

There are a few points that we need to keep in mind while creating pattern markers:

● It would be better if we use small size images to create markers.

The markers should be in square shape. ● The black and grey colors are to be used as the background color of the marker. ● It's better to avoid transparent, white and any other colored background.
let's get started. We have the pizza image, and we are going to use it to create the pattern marker.

we are going to use another AR.js marker creating tool. https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html

Once the image is uploaded we can set: ● Pattern ratio: this sets the size of the image with respect to the borders. ● Image size: size of the image. ● Background border color: set to black color. Click on the download marker and download image. The marker will be downloaded in the .patt file format.

And the new marker image will be downloaded which we can use to detect AR content.
