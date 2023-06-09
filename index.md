---
layout: default
---

BridgeData is a large and diverse dataset of robotic manipulation behaviors designed to facilitate research in scalable robot learning. The dataset is compatible with open-vocabulary, multi-task learning methods conditioned on goal images or natural language instructions. The data consists of human teleoperated demonstrations as well as rollouts from a scripted pick-and-place policy. All the data was collected on a low-cost WidowX 250 6DOF robot arm. 

![bridge-gif-1](assets/images/bridge_gif1.gif)
![bridge-gif-2](assets/images/bridge_gif2.gif)
![bridge-gif-3](assets/images/bridge_gif3.gif)
![bridge-gif-4](assets/images/bridge_gif4.gif)
![bridge-gif-5](assets/images/bridge_gif5.gif)
![bridge-gif-6](assets/images/bridge_gif6.gif)
![bridge-gif-7](assets/images/bridge_gif7.gif)
![bridge-gif-8](assets/images/bridge_gif8.gif)
![bridge-gif-9](assets/images/bridge_gif9.gif)
![bridge-gif-10](assets/images/bridge_gif10.gif)
![bridge-gif-11](assets/images/bridge_gif11.gif)
![bridge-gif-12](assets/images/bridge_gif12.gif)

## Statistics

- 44,165 teleoperated demonstrations
- 9,731 rollouts from a scripted policy
- 24 different environments
- 13 distinct skills

## Usage and Contributing

[This repository](https://github.com/yanlai00/bridge_data_robot_infra) contains 
the robot controller and data collection code. 

Follow the links below to purchase the required equipment:

- [WidowX 250 6DOF robot](https://www.trossenrobotics.com/widowx-250-robot-arm-6dof.aspx)
- [Logitech C920 HD Webcam](https://www.amazon.com/dp/B006JH8T3S)
- [Meta Quest 2 VR Headset](https://www.amazon.com/dp/B099VMT8VZ/) (only needed for data collection)

Please contact [Homer Walke](https://homerwalke.com/) for questions about using the dataset. 

Model training code and a more detailed setup guide will be released soon. 

## Papers

- [Bridge Data: Boosting Generalization of Robotic Skills with Cross-Domain Datasets](https://arxiv.org/abs/2109.13396)
- [Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials](https://arxiv.org/abs/2210.05178)
- [Generalization with Lossy Affordances: Leveraging Broad Offline Data for Learning Visuomotor Tasks](https://arxiv.org/abs/2210.06601)

## Contributors

The following people contributed to the project. 

[Homer Walke](https://homerwalke.com/), [Kevin Black](https://kevinblack.dev/), [Frederik Ebert](https://febert.github.io/), [Aviral Kumar](https://aviralkumar2907.github.io/), [Anikait Singh](https://asap7772.github.io/), [Yanlai Yang](https://yanlai00.github.io/), [Patrick Yin](https://patrickyin.me/), [Gengchen Yan](https://www.linkedin.com/in/gengchen-matt-yan), [Kuan Fang](http://kuanfang.github.io/), [Ashvin Nair](https://ashvin.me/), [Karl Schmeckpeper](https://sites.google.com/view/karlschmeckpeper), [Bernadette Bucher](https://bucherb.github.io/), [Georgios Georgakis](https://ggeorgak11.github.io/), [Kostas Daniilidis](https://www.cis.upenn.edu/~kostas/), [Chelsea Finn](https://ai.stanford.edu/~cbfinn/), [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/)

We also thank Abraham Lee, Mia Galatis, Caroline Johnson, Christian Aviña, Samantha Huang, and Nicholas Lofrese for collecting data. 

All data is provided under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
