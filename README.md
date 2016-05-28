# neural-style-gradient

This bash scripts creates a gradient of style transfer images using jcjohnson's neural-style script. Dependencies for the script are exactly the same as neural-style, with the addition of the NIN model. You will need to download the NIN model and proto files to use this example. 
<br>
<a href="http://imgur.com/vFiTXEn"><img src="http://i.imgur.com/vFiTXEn.gif" title="source: imgur.com" /></a>

*Note that this script does not create animated .gifs for you, this is just a visual of the sequence of images that can be easily created using the script.

<a href="http://imgur.com/M4uMqfO"><img src="http://i.imgur.com/M4uMqfO.png" title="source: imgur.com" /></a>

The idea is to find the settings you would like to use and actually keep track of them by naming the files with the actual parameters used in that file

*tip If you want to use this to create with the VGG 19 model, just edit out the parts that refer to the NIN Model, I may add that in the future, but for now this is an easy edit if you read the script.
