# neural-style-gradient

This bash scripts creates a gradient of style transfer images using [jcjohnson's neural-style](https://github.com/jcjohnson/neural-style) script. This is intended to help anyone who wants to use the NIN model and figure out the best parameters. The .sh file is well commented so you should have an easy time making edits to whatever you like. This was written for bash on OS X, but you may easily modify it to work with Ubuntu or other Linux platforms. (untested, but it may verbatim to the contents of the .sh file)

Dependencies for the script are exactly the same as neural-style because it is totally reliant on that script. You simply place the neural-style-gradient.sh file in your neural-style directory and run from there. You will need the NIN model installed in your models directory if you have not already done so: You can get the details on the model from [BVLC Caffe ModelZoo](https://github.com/BVLC/caffe/wiki/Model-Zoo) and can download the files from [NIN-Imagenet Download Link](https://drive.google.com/folderview?id=0B0IedYUunOQINEFtUi1QNWVhVVU&usp=drive_web)



<br>
<a href="http://imgur.com/vFiTXEn"><img src="http://i.imgur.com/vFiTXEn.gif" title="source: imgur.com" /></a>
<a href="http://imgur.com/h0Hse0r"><img src="http://i.imgur.com/h0Hse0r.gif" title="source: imgur.com" /></a>
<br>
*Note that this script does not create animated .gifs for you, this is just a visual of the sequence of images that can be easily created using the script.

<a href="http://imgur.com/M4uMqfO"><img src="http://i.imgur.com/M4uMqfO.png" title="source: imgur.com" /></a>

The idea is to find the settings you would like to use and keep track of them by naming the files with the actual parameters used in that image. This is especially useful for finding the right set of parameters before creating a video sequence.

*If you want to use this to create with the VGG 19 model, just edit out the parts that refer to the NIN Model, I may add a seperate .sh file in the future, but for now this is an easy edit if you read the command and edit out those flags.
