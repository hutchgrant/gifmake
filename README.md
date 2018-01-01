# gifmake

## Dependencies:

* mplayer
* ImageMagick
* gifsicle

## Install Dependencies

sudo apt-get install mplayer gifsicle

## Install gifmake

move gifmake to /usr/bin/ :

```
 sudo cp ./gifmake /usr/bin/gifmake
```

add execute permissions.

```
sudo chmod +x /usr/bin/gifmake
```

finally you can now launch it with :

```
gifmake
```

## Usage

Go through the list of options one at a time following the onscreen instructions.

1. For the location of the video you want to make a gif from make sure you enter the absolute path to the folder location. When you hit enter you will be asked for the filename e.g. /home/user/videos

2. Set the seek to the time at which you want the gif to begin e.g. 12:42
   Set the gif length in seconds. e.g. 5
   Set the output folder e.g. gif_export (no path necessary)

3. Set the image type to: png.
   Set the image size: 1000x500.
   Set the image crop: 250+40.
4. Set the Fuzz amount: 1.6 .
   Set the animated speed (frame delay): 8 .
   Set Loop Forever: y .
   Set the output gif name (no extension): Example
5. Create the gif. Look for the output folder in your home directory aswell as your new gif with the output name.

6. Compress the gif. New gif should be found in home directory called complete.gif
