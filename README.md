# Multi-Source Human-in-the-loop Mixed Cloud Control Testbed (MSH-MCCT)

<!--课题组网站链接-->
[![tsinghua-svm-thicv](https://img.shields.io/badge/Tsinghua_University-THICV-brightgreen)](https://www.labxing.com/thicv)

In this project, we present demo videos for our CAVs (Connected and Autonomous Vehicles) testing platform, Multi-Source Human-in-the-loop Mixed Cloud Control Testbed (MSH-MCCT), developed based on a new notion of Mixed Digital Twin (mixedDT). 

A corresponding overview of MSH-MCCT is as follows.

<img src="resources/MSH-framework.jpg" align="center" width="80%"/>

## Demo videos
Two experiments on mixed platooning with the coexistence of HDVs (human-driven vehicles) and CAVs is carried out to validate the effectiveness of MSH-MCCT.

The detailed schematic of the two experiments is illustrated below.

<img src="resources/MSH-snapshot.jpg" align="center" width="80%"/>

The formation of the platoon for experiment A and B is shown below.

<img src="resources/formation.jpg" align="center" width="80%"/>

The detailed mode of operation is presented below.

| ID | Type | Entity | Control input | Field of view |
| :---:| :---: | :---: | :---: | :---: |
| 1 | CAV | Physical vehicle | CACC controller | N/A |
| 2 | HDV | Physical vehicle | Human via G29 simulator | Physical field-of-view from the physical sand table |
| 3 | CAV | Virtual vehicle | CACC controller | N/A |
| 4 | HDV | Physical vehicle | Human via G29 simulator | Virtual field-of-view of the virtual twin vehicle from the Unity virtual environment |
| 5 | HDV | Virtual vehicle | Human via G29 simulator | Virtual field-of-view from the Unity virtual environment |
| 6 | CAV | Virtual vehicle | CACC controller | N/A |
| 7 | CAV | Virtual vehicle | CACC controller | N/A |
| 8 | HDV | Virtual vehicle | Human via InnoSimulation simulator | Virtual field-of-view from the InnoSimulation virtual environment |

**Experiment A:** Head vehicle encounters a half-sinusoidal disturbance.

The video of the experiment process is shown below. The video plays at 1.6x speed. The upper right corner is the visualization of the platoon in the Unity virtual environment. The upper left corner is the image captured by roadside cameras in the physical platform, and the numbers next to the physical vehicles are merely vehicle IDs for identification, not the vehicles' sequential order in the platoon shown above.

<img src="resources/exp_sin_V3.gif" align="center" width="80%"/>

**Experiment B:** Head vehicle encounters a braking disturbance.

The video of the experiment process is shown below. The video plays at 1.6x speed.

<img src="resources/exp_braking_V2.gif" align="center" width="80%"/>

<!--还没放上去，先不放
More longer videos can be found on [![](https://img.shields.io/badge/YouTube-SICity-FF0000?style=logo=youtube&logoColor=white)](https://github.com/cmc623/Formation-control-experiments).
-->

## More experiments on MSH-MCCT
- Multi-vehicle coordinated formation control. [![](https://img.shields.io/badge/GitHub-Formation_control-green?style=logo=github&logoColor=white)](https://github.com/cmc623/Formation-control-experiments)
- Data-Enabled Predictive Leading Cruise Control (DeeP-LCC). [![](https://img.shields.io/badge/GitHub-DeeP_LCC-green?style=logo=github&logoColor=white)](https://github.com/soc-ucsd/DeeP-LCC)

<!--MSH-MCCT放到arxiv上后补充下链接
6.
-->

## Citing MSH-MCCT
If you refer to MSH-MCCT in your research, please cite the [paper](https://arxiv.org/abs/2212.02007). In BibTeX format:

```bibtex
@article{dong2023mixed,
  title={Mixed cloud control testbed: Validating vehicle-road-cloud integration via mixed digital twin},
  author={Dong, Jianghong and Xu, Qing and Wang, Jiawei and Yang, Chunying and Cai, Mengchi and Chen, Chaoyi and Liu, Yu and Wang, Jianqiang and Li, Keqiang},
  journal={IEEE Transactions on Intelligent Vehicles},
  year={2023},
  volume={8},
  number={4},
  pages={2723-2736},
  publisher={IEEE}
}
```

## Contacts
For more details, please contact [Jianghong Dong](https://www.researchgate.net/profile/Jianghong-Dong) and [Jiawei Wang](https://wjiawei.com/).

