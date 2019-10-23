<!--
 * @Author: Sauron Wu
 * @GitHub: wutianze
 * @Email: 1369130123qq@gmail.com
 * @Date: 2019-09-03 16:28:15
 * @LastEditors: Sauron Wu
 * @LastEditTime: 2019-10-23 14:29:57
 * @Description: 
 -->
# Build your own autonomous Car
## Introduction
Enjoy your own autonomous driving car with the power of DPU and feel free to try your own AI model and new ideas.

## Material
Download the image we provided [here]() and buy the car [here](). Burn the image to your Pynq-Z2 board. To understand the whole project well, you can read the paper we published in FPT2019 [here](https://easychair.org/publications/preprint/GMvL), be relax to read the paper, it's not complex or hard to understand.

## Preparations
- The host pc should be ubuntu 16.04, you can refer to [this](https://github.com/wutianze/dnndk3.0-pynqz2) to build an environment for DNNDK_v3.0 using tensorflow. If you want to run the simulator, refer to Virtual-Part to set the Unity3d environment.
- Power the Pynq-Z2 in your car and run `nmtui` to connect the car to your switch(make sure your PC connected to the same).
- Read the guides in both `Host-Part/guides`, `Pynq-Part/Car/guides` and `Virtual-Part/guides`(If you want to try the simulator we provided), you can start with `Pynq-Part/Car/guides/collect_guide.md`.


