# Multi-Source Human-in-the-loop Mixed Cloud Control Testbed (MSH-MCCT)

<!--课题组网站链接-->
[![tsinghua-svm-thicv](https://img.shields.io/badge/Tsinghua_University-THICV-brightgreen)](https://www.labxing.com/thicv)

In this project, we present demo videos for our Connected and Autonomous Vehicles (CAVs) testing platform, Multi-Source Human-in-the-loop Mixed Cloud Control Testbed (MSH-MCCT), developed based on a new notion of Mixed Digital Twin (mixedDT). 

## The notion of mixedDT
By introducing Mixed Reality into classical DT, mixedDT bridges the physical and virtual spaces into a unified, integrated one, where physical entities coexist and interact with virtual entities via their digital counterparts. 

The schematic diagram of the classical DT is as follows.

<img src="resources/dt-framework.jpg" align="center" width="80%"/>

The schematic diagram of the proposed mixedDT is as follows.

<img src="resources/mdt-framework.jpg" align="center" width="80%"/>

## Platform structure of MSH-MCCT

Under the framework of mixedDT, MSH-MCCT consists of physical, virtual and mixed platforms, and multi-source control input. 

An corresponding overview of MSH-MCCT is as follows.

<img src="resources/MSH-framework.jpg" align="center" width="80%"/>

The methodological framework diagram for conducting CAVs testing with multi-source human drivers in the loop via various-fidelity driving simulators in MSH-MCCT is as follows.

<img src="resources/MSH-method.jpg" align="center" width="96%"/>

## Demo videos
Two experiments on mixed platooning with the coexistence of HDVs and CAVs is carried out to validate the effectiveness of MSH-MCCT.

The detailed schematic diagram of the two experiments is illustrated below.

Bridged by the mixed platform, human drivers and CAV algorithms could control both physical and virtual vehicles. Therefore, physical and virtual CAVs and human-driven vehicles (HDVs) via multiple driving simulators could coexist and interact simultaneously within the same integrated environment, greatly enhancing the flexibility and scalability of experiments. 

<img src="resources/MSH-snapshot.jpg" align="center" width="80%"/>

The formation of the platoon for experiment A and B is shown below.

<img src="resources/formation.jpg" align="center" width="80%"/>

**Experiment A:** Head vehicle encounters a half-sinusoidal disturbance.

The video of the experiment process is shown below. The video plays at 1.6x speed. The upper right corner is the visualization of the platoon in the Unity virtual environment. The upper left corner is the image captured by roadside cameras in the physical platform, and the numbers next to the physical vehicles are merely vehicle IDs for identification, not the vehicles' sequential order in the platoon shown above.

<img src="resources/exp_sin.gif" align="center" width="80%"/>

**Experiment B:** Head vehicle encounters a braking disturbance.

The video of the experiment process is shown below. The video plays at 1.6x speed.

<img src="resources/exp_brake.gif" align="center" width="80%"/>

<!--还没放上去，先不放
More longer videos can be found on [![](https://img.shields.io/badge/YouTube-SICity-FF0000?style=logo=youtube&logoColor=white)](https://github.com/cmc623/Formation-control-experiments).
-->

## More experiments on MSH-MCCT
- Multi-vehicle coordinated formation control. [![](https://img.shields.io/badge/GitHub-Formation_control-green?style=logo=github&logoColor=white)](https://github.com/cmc623/Formation-control-experiments)
- Data-Enabled Predictive Leading Cruise Control (DeeP-LCC). [![](https://img.shields.io/badge/GitHub-DeeP_LCC-green?style=logo=github&logoColor=white)](https://github.com/soc-ucsd/DeeP-LCC)

## Related publications
1. Yang C, Dong J, Xu Q, et al. Multi-vehicle experiment platform: A Digital Twin Realization Method[C]//2022 IEEE/SICE International Symposium on System Integration (SII). IEEE, 2022: 705-711. [paper link](https://www.researchgate.net/publication/359072029_Multi-vehicle_experiment_platform_A_Digital_Twin_Realization_Method)
2. Dong J, Xu Q, Wang J, et al. Mixed cloud control testbed: Validating vehicle-road-cloud integration via mixed digital twin[J]. IEEE Transactions on Intelligent Vehicles, 2023. [paper link](https://arxiv.org/abs/2212.02007)
3. Wang J, Zheng Y, Dong J, et al. Implementation and experimental validation of data-driven predictive control for dissipating stop-and-go waves in mixed traffic[J]. IEEE Internet of Things Journal, 2023. [paper link](https://arxiv.org/abs/2204.03747)
4. Cai M, Xu Q, Yang C, et al. Experimental Validation of Multi-Lane Formation Control for Connected and Automated Vehicles[C]//2023 IEEE International Conference on Unmanned Systems (ICUS). IEEE, 2023: 1267-1273. [paper link](https://arxiv.org/abs/2112.00312)
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

