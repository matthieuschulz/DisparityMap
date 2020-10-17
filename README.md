# Disparity Map Generator

## Stereo Matching

When our eyes view a scene, the left and right eyes see slightly different things. The left and right images are known as a stereo pair. By matching the corresponding points in the two images, we are able to infer the depth of the scene.

<p align="center">
  <img src="Stereo%20Pairs/Pair%202/view1.png" />
  <img src="Stereo%20Pairs/Pair%202/view2.png" />
</p>

<p align="center">
  <img src="Stereo%20Pairs/Pair%202/disp1.png" />
</p>

The paper below proposes using a dynamic programming algorithm to perform stereo matching, which I have implemented in Python.

> Cox, I.J., Hingorani, S., Maggs, B.M. and Rao, S.B. (1992). Stereo Without Disparity Gradient Smoothing: A Bayesian Sensor Fusion Solution. Procedings of the British Machine Vision Conference 1992. [online] Available at: http://www.bmva.org/bmvc/1992/bmvc-92-035.pdf.

