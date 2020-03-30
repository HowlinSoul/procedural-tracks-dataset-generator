# procedural-tracks
Procedural race track generation with Python.

Following the article found [here](https://www.gamasutra.com/blogs/GustavoMaciel/20131229/207833/Generating_Procedural_Racetracks.php)

## Process

As explained in the post mentioned above, which I strongly recommend you to read, below you can find the steps taken to generate a track. Note that there are some restrictions and parameters used in the code which are not explained in the summary presented below. You can dive in the code to learn more about them.

The outline of the algorithm is:
1. Generate a set of random points (white points)
2. Compute the points that, from the set of all points generated in step 1, form the convex Hull (red lines)
3. For each pair of consecutive points in the convex hull, compute the midpoint and displace it by a random bounded amount
4. Push points whose distance is less than a predefined threshold apart an limit the max angle between them.
5. From the final set of points, compute a spline that passess through all of them.

## Example tracks

![Example Track 1](/img/track_1.png)
![Example Track 2](/img/track_2.png)
![Example Track 3](/img/track_3.png)
![Example Track 4](/img/track_4.png)