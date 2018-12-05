# Google Image Downloader

By __[Jeff Ocampo](http://www.JOcampo.com)__

__Purpose:__ Automate the download of images from Google to support other analyses. 

__Background:__ Had originally used this method to support some image recognition work I was doing with CNN's. Decided to formalize this part more to make it a bit easier to get pics for working with. 

__Parameters:__ (1) Search term (2) number of images to retrieve (3) base directory

__Returns:__ A folder in the base directory that has (1) an Excel with a list of files (2) another folder with the images

__Other things of note:__ (1) Only works for .jpgs (2) Sometimes query returns extra files that aren't jpgs, so the process ignores files it can't work with. 
