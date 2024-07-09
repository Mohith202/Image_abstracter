To commence, you must install the Remove library. To do this, enter the following command: **"!pip install remove."** Once the library is installed, you can use it to remove objects from an image.

we simply pass the image to remove library abd gives a updated image and we store it.

It is a simple way but we can do it in more professional way by argumented the image and then train it on U-Net architecture of segmentation method.
the code is in U-Net arch file.

We took a single image and derived multiple images from it. We accomplished this by rotating, moving, cropping, and mirroring the original image.

Then encode the image from 64 to 1024 and make adjustment in kernal neural networks.

Then train the module based on that data and epoch it and use it to predit it.
