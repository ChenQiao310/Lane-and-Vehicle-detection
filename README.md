# Lane-and-Vehicle-detection
Lane detection and vehicle detection are two crucial components of autonomous driving.
They ensure accurate identification of traffic lanes and vehicles, powering autopilot and
reducing driver fatigue. However, many existing models are either too large to fit in self-
driving cars with limited computing power, or lack the capability to generalize to new,
unpredictable road conditions, sometimes known as a domain-shift problem. In this work,
we improved the performance and mobility of several traditional and deep learning based
models, and built a single-pass pipeline combining both detectors.

The input of our pipeline was image/video taken of roads; the output was the same
image/video with lanes and vehicles annotated. We then tried to make the pipeline robust
enough to handle a variety of driving conditions including snow, rain, poor lighting, and 
roads with little or no lane markers. Our final lane detection model was more light weighted
compared to the baseline, with 30% parameter size at only 0.13% sacrificed accuracy. Our 
final vehicle detection model provided better vehicle detection precisoin with reduced noises
from other classes.


<img width="524" alt="Screenshot 2023-04-07 at 7 03 05 PM" src="https://user-images.githubusercontent.com/65835990/230698549-de15a4d9-2695-4a98-8196-75ae31cb732f.png">
