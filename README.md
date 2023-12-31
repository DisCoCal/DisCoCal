# DisCoCal: Unbiased Estimator for Distorted Conics in Camera Calibration
## Entire code will be released after the end of the blind review period.
## Project Insight

![overview](./Figs/overview3.png)

The center of the circle doesn't match up with the distorted ellipse under perspective transformation and distortion! Classic circular pattern-based calibration methods fall short because they ignore the weird shape of the distorted ellipse, leading to bias and less accurate calibration compared to the checkerboard pattern.

### Our Game-Changer: Unbiased Estimator
**Our unbiased estimator completes the missing piece in the conic-based calibration pipeline and outperforms the checkerboard pattern-based calibration!**


## Dependency

- [Ceres-Solver](http://ceres-solver.org/index.html)
- [Eigen3](https://eigen.tuxfamily.org/dox/index.html)
- opencv

<!-- 
## Experiments

### Comparision between existing methods
![results](./Figs/Calresults.png)
Each calibration is conducted with randomly generated 30 images, and the entire process is repeated 30 times to obtain mean and standard deviation values.
Our method shows the best performance and significantly low standard deviation.

### Reprojection error comparison in synthetic images
<img src="./Figs/Rep.png" width="700" height="480"/>
With known intrinsic matrix, we evaluated the reprojection error to verify the projection model is well defined. Unlike other circular pattern methods, our method is unbiased, resulting in near-zero errors regardless of distortion and radius changes.


### Why Circular pattern?

The circular pattern has subpixel-level accuracy to detect the control points and is robust to boundary blur effects. These advantages are maximized in thermal-infrared cameras suffering from boundary blur effect due to thermal conduction.
![boundary_blur](./Figs/boundary_blur.png) -->

