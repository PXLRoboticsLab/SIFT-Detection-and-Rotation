# SIFT-Detection-and-Rotation

This is a simple python writen program. You will be able to detect objects and rotate the image at the center of the object so that the detected object will end up horizontal.


## Getting Started

Just clone or download the code to your preferable folder.

### Prerequisites

You need to have at least python 2.7 installed on your computer.
To install the needed requirements do:

`$ pip install -r requirements.txt`

### How to use

First remove the images in img and the image train.jpg.
Second choose an image with the object you want to detect. Crop it so you only have your object you want to detect. Then rename the image to train.jpg and put this in the root directory of this project. Then put the images on which you want to detect the object in the img folder.
Then run `$ ./Detect`
It will put the image that have the object in it in the map out.

....................

For example if you want to detect Snickers you crop a Snicker and call the image train.jpg and put this in the root of the project. Next lets say you have 10 images 5 with and 5 without Snickers. Put them in img. Then run the command `$ ./detect` and the 5 images with Snickers will be in the folder out. 

....................

If you have issues executing the file then remind to give it executions rights:

`$ chmod +x ./Detect.py`

For more information on what options you can change:

`$ ./Detect --help`


## Authors

* **Niels Debrier**


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
