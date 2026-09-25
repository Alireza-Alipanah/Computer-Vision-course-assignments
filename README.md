# Assignment 5
## Part one
For the first part, Mean Curvature Motion was implemented.
| Image | MCM final | MCM animation |
|:---------:|:---------:|:---------:|
| <img src="./assets/head.png" alt="head original" width="100"> | <img src="./assets/head_mcm_final.png" alt="head MCM final" width="100"> | <img src="./assets/head_mcm.gif" alt="head MCM animation" width="100"> |
## Part two
Fro the second part, Chan Vese segmentation was implemented.
| Image | CV overlay | CV animation |
|:---------:|:---------:|:---------:|
| <img src="./assets/head.png" alt="head original" width="100"> | <img src="./assets/head_cv_overlay.png" alt="head cv overlay" width="100"> | <img src="./assets/head_cv_animation.gif" alt="head cv overlay" width="100">

# Assignment 4
## Part one
For the first part, Coherence-enhancing anisotropic diffusion (CED) was applied to images.
| Image | CED |
|:---------:|:---------:|
| <img src="./assets/finger.png" alt="finger original" width="100"> | <img src="./assets/finger_ced.png" alt="finger ced" width="100"> |
| <img src="./assets/sbrain.png" alt="sbrain original" width="100"> | <img src="./assets/sbrain_ced.png" alt="sbrain ced" width="100"> |
| <img src="./assets/xmas.png" alt="xmas original" width="100"> | <img src="./assets/xmas_ced.png" alt="xmas ced" width="100"> |
<!-- -->
| Image | CED 20 iterations | CED 200 iterations |
|:---------:|:---------:|:---------:|
| <img src="./assets/fabric.png" alt="fabric original" width="100"> | <img src="./assets/fabric_ced_itr20.png" alt="fabric ced 20 iterations" width="100"> | <img src="./assets/fabric_ced_itr200.png" alt="fabric ced 200 iterations" width="100"> |
## Part two
For the second part, dilation and erosion operations on grascale images were implemented.
| Image | Dilation | Erosion |
|:---------:|:---------:|:---------:|
| <img src="./assets/bank.png" alt="bank original" width="100"> | <img src="./assets/bank_dilation.png" alt="bank dilation" width="100"> | <img src="./assets/bank_erosion.png" alt="bank erosion" width="100"> |
| <img src="./assets/head.png" alt="head original" width="100"> | <img src="./assets/head_dilation.png" alt="head dilation" width="100"> | <img src="./assets/head_erosion.png" alt="head erosion" width="100"> |
##
For the third part, shock filtering was implemented for grayscale and color images
| Image | Shock filter |
|:---------:|:---------:|
| <img src="./assets/baboon.png" alt="baboon original" width="100"> | <img src="./assets/baboon_shock.png" alt="baboon shock filter" width="100"> |
| <img src="./assets/bank.png" alt="bank original" width="100"> | <img src="./assets/bank_shock.png" alt="bank shock filter" width="100"> |
| <img src="./assets/head.png" alt="head original" width="100"> | <img src="./assets/head_shock.png" alt="head shock filter" width="100"> |
| <img src="./assets/finger.png" alt="finger original" width="100"> | <img src="./assets/finger_shock.png" alt="finger shock filter" width="100"> |assets/head_cv_animation.gif" alt="head cv animation" width="100"> |

# Assignment 3
For this assignment, Horn and Schunck method was used for Optical Flow Estimation between two frames.
| Frame 1 | Frame 2 |
|:---------:|:---------:|
| <img src="./assets/pig1.png" alt="pig frame 1" width="100"> | <img src="./assets/pig2.png" alt="pig frame 2" width="100"> |
| Flow magnitude |
| <img src="./assets/hornschunck_flow_magnitude.png" alt="horn and schunck flow magnitude" width="100"> |

# Assignment 2
In this assignment, Optical Flow Estimation between two frames using the Lucas–Kanade method was performed.
| Frame 1 | Frame 2 |
|:---------:|:---------:|
| <img src="./assets/sphere1.png" alt="sphere frame 1" width="100"> | <img src="./assets/sphere2.png" alt="sphere frame 2" width="100"> |
| Flow magnitude | Flow classification |
| <img src="./assets/sphere_flow_magnitude.png" alt="flow magnitude" width="100"> | <img src="./assets/sphere_flow_classification.png" alt="flow classification" width="100"> |

# Assignment 1
## Part one
In the first part of this assignment, gradient map of an image containing coins is approximated using finite differences:
| Original | Gradient map |
|:---------:|:---------:|
| <img src="./assets/coins.png" alt="Original" width="100"> | <img src="./assets/gradient_map_output.png" alt="gradinet map output" width="100"> |
## Part two
In this part, the shapes of the coins are deteced using hough transfrom and the gradient map from the previous part.
| Detected shapes | Boundaries |
|:---------:|:---------:|
| <img src="./assets/hough_transform_output_2.png" alt="Detected shapes" width="100"> | <img src="./assets/hough_transform_output1.png" alt="Coins with Boundaries" width="100"> |