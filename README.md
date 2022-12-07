# Dataset Generation with procedural-tracks

Generate an arbitrary number of tracks images to use in Machine Learning or else. <br>
From pure grayscale track to rgb/kerbs/starting grid

## Grayscale

![Grayscale 1](/gen_tracks/track_1_gray.jpg)
![Grayscale 2](/gen_tracks/track_2_gray.jpg) <br>

## RGB 

![RGB 1](/gen_tracks/track_1_rgb.jpg)
![RGB 2](/gen_tracks/track_2_rgb.jpg) <br>

## Full Gamma Sportsback

![Complete Track 1](/gen_tracks/track_1_kerb_startgrid.jpg)
![Complete Track 2](/gen_tracks/track_2_kerb_startgrid.jpg) <br>

# Usage
python main.py --n-tracks 2 --width 512 --height 512 --rgb y --kerb y --starting-grid y <br>

<b>--n-tracks </b> Number of tracks to generate <br>
<b>--width/--height </b> Width/Height of images in pixel <br>
<b>--rgb </b> Rgb or Grayscale <br>
<b>--kerb </b> To draw kerbs <br>
<b>--starting-grid </b> To draw starting-greed <br>



# procedural-tracks (Original Project)
Procedural race track generation with Python.

Blog post with more insights [here](https://bitesofcode.wordpress.com/2020/04/09/procedural-racetrack-generation/).

Following the article found [here](https://www.gamasutra.com/blogs/GustavoMaciel/20131229/207833/Generating_Procedural_Racetracks.php).

The tracks obtained by my implementation are far from ideal, but it might be a good starting point for further work.
