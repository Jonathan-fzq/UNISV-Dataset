# UNISV-Dataset
Introducing a nighttime infrared surveillance video behavior recognition dataset comprising 1,200 samples. This dataset utilizes recorded, unedited raw video data as samples, encompassing 10 distinct behavioral actions. Each action category comprises 120 samples.

The UNISV dataset consists of unedited or randomly edited video samples, with a significant portion of the videos not containing individuals. During the dataset construction process, various factors such as sample types and scene complexity were considered. Additionally, given the fixed camera positions and backgrounds in nighttime surveillance data, the dataset reflects scene variations and diverse behavioral categories across different scenarios. The naming convention for video samples in this dataset follows the format used in the UCF-101 dataset, for example, a video sample name could be "v_DoubleWave_g01_c01," where "v_DoubleWave" indicates the behavior category of double waving, "g01" signifies that the video sample was recorded in location 01, and "c01" denotes the first video sample of the double waving behavior category in location 01. All video samples in this dataset were recorded in outdoor settings, with scene selections based on key locations for real-life surveillance cameras, such as parking lots, gardens, alleys, etc. The recording time for all video samples is during the nighttime, and the dataset compilation involved 15 experiment participants with varying heights and body types.

![UNISV-Dataset](https://github.com/Jonathan-fzq/UNISV-Dataset/assets/68420717/bd2fdbfb-26d7-47ad-8c9d-fba46e7b844e)

The UNISV dataset consists of 10 action categories, as shown in Figure 1, namely: "Double Wave," "Wave Hand," "Walk," "Jump," "Squat," "Jogging," "Push People," "Shake Hands," "Embrace," and "Fight." The dataset includes both individual actions and interactive actions involving two individuals. Each action category involves the participation of 6 individuals, totaling 15 participants in video enactment. There are 120 video samples for each of the 10 behavior categories, resulting in a total of 1200 video samples. The videos have a frame rate of 10 frames per second and a resolution of 480 x 248 pixels.

If you use this dataset for your research, please cite:

Feng Z, Wang X, Zhou J, et al. MDJ: A Multi-Scale Difference Joint Keyframe Extraction Algorithm for Infrared Surveillance Video Action Recognition[J]. Digital Signal Processing, 2024: 104469. https://doi.org/10.1016/j.dsp.2024.104469.

```
@article{feng2024mdj,
  title={MDJ: A Multi-Scale Difference Joint Keyframe Extraction Algorithm for Infrared Surveillance Video Action Recognition},
  author={Feng, Zhiqiang and Wang, Xiaogang and Zhou, Jiayi and Du, Xin},
  journal={Digital Signal Processing},
  pages={104469},
  year={2024},
  publisher={Elsevier}
}
