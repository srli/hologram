# hologram
Interesting ideas involving holograms

-Image recognition
Some core component of holograms involve projecting a laser across two images. If the images match, the output is a bight dot. If its not, there won't be a bright output dot. Aka interference holography (lol wtf all holograms are interference patterns)

Advantage is that by shining a laser through the two images, its an O(1) operation because light... and then probably just doing an intensity measurement on the result. The analog to this would be finding hamming distances(?) between two images... which would be O(n) at least, because each pixel needs to be diffed. Also, the two images would have to be pre-cropped and rotated... ??? Am thinking this is quite similar to how SIFT/SURF works atm.

-Pose learning
Nikolai Bernstein got some dancers to wear dots and predicted future movements by doing Fourier transforms on the recorded dot patterns. Similar to what they did with the robot arm with AR-tags, we could look at classification algorithms for better robotic responses to human interactions. Interesting concept, read more papers about this because I'm pretty sure that this has been done a million time already. Frequency domain best domain???

-Computer generated holography (CGH)
3 basic elements of holography: the light source, the hologram, and the image. If any of the two are known, the third can be computed. So... could probably write some script that does CGH for the lols
