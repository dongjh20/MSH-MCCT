# Multi Source Human-in-the-loop Mixed Cloud Control Testbed (MSH-MCCT)

<!--课题组网站链接-->
[![tsinghua-svm-thicv](https://img.shields.io/badge/Tsinghua_University-THICV-brightgreen)](https://www.labxing.com/thicv)

<!---用到的系统-->
<a><img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>
<a><img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"></a>


In this project, we present demo videos for our Connected and Autonomous Vehicles (CAVs) testing platform, Multi Source Human-in-the-loop Mixed Cloud Control Testbed (MSH-MCCT), developed based on a new notion of Mixed Digital Twin (mixedDT). 

## The notion of mixedDT
By introducing Mixed Reality into classical DT, mixedDT bridges the physical and virtual spaces into an unified, integrated one, where physical entities coexist and interact with virtual entities via their digital counterparts. 

The schematic diagram of the classical DT is as follows.

<img src="resources/dt-framework.jpg" align="center" width="70%"/>

The schematic diagram of the proposed mixedDT is as follows.

<img src="resources/mdt-framework.jpg" align="center" width="70%"/>

## The structure of the MSH-MCCT

Under the framework of mixedDT, MCCT contains three major experimental platforms in the physical, virtual and mixed spaces respectively, and provides a unified access for various human-machine interfaces and external devices such as driving simulators.

<img src="resources/MCCT-architecture.jpg" align="center" width="50%"/>

An corresponding overview of the MCCT is as follows.

<img src="resources/MCCT-overview.png" align="center" width="50%"/>

The detailed physical architecture of the MCCT is as follows, which is not presented in paper due to space limitations.

<img src="resources/MCCT-framework.png" align="center" width="80%"/>

## Demo videos
Cross-platform experiments are carried out on vehicle platooning, which is composed of different types of vehicles from different platforms in MCCT.

**Experiment A:** Mixing physical miniature vehicles and virtual vehicles

The formation of the platoon for experiment A is shown below.

<img src="resources/formation-experiment-A.jpg" align="center" width="50%"/>

The video of the experiment process is shown below.

<img src="resources/experiment-A-V2.gif" align="center" width="100%"/>

**Experiment B:** Mixing physical miniature vehicles, virtual vehicles and a human-driven vehicle via a driving simulator

The formation of the platoon for experiment B is shown below. SCANeR Studio is the supporting software of the driving simulator. 

<img src="resources/formation-experiment-B.jpg" align="center" width="50%"/>

The video of the experiment process is shown below.

<img src="resources/experiment-B.gif" align="center" width="100%"/>

<!--还没放上去，先不放
More longer videos can be found on [![](https://img.shields.io/badge/YouTube-SICity-FF0000?style=logo=youtube&logoColor=white)](https://github.com/cmc623/Formation-control-experiments).
-->

## More experiments on MCCT
- Multi-vehicle coordinated formation control. [![](https://img.shields.io/badge/GitHub-Formation_control-green?style=logo=github&logoColor=white)](https://github.com/cmc623/Formation-control-experiments)
- Data-Enabled Predictive Leading Cruise Control (DeeP-LCC). [![](https://img.shields.io/badge/GitHub-DeeP_LCC-green?style=logo=github&logoColor=white)](https://github.com/soc-ucsd/DeeP-LCC)

## Related publications
1. Yang C, Dong J, Xu Q, et al. Multi-vehicle experiment platform: A Digital Twin Realization Method[C]//2022 IEEE/SICE International Symposium on System Integration (SII). IEEE, 2022: 705-711. [paper link](https://www.researchgate.net/publication/359072029_Multi-vehicle_experiment_platform_A_Digital_Twin_Realization_Method)
2. Cai M, Xu Q, Yang C, et al. Experimental Validation of Multi-lane Formation Control for Connected and Automated Vehicles in Multiple Scenarios[J]. arXiv preprint arXiv:2112.00312, 2021. [paper link](https://www.researchgate.net/publication/356711150_Experimental_Validation_of_Multi-lane_Formation_Control_for_Connected_and_Automated_Vehicles_in_Multiple_Scenarios)
3. Wang J, Zheng Y, Dong J, et al. Experimental Validation of DeeP-LCC for Dissipating Stop-and-Go Waves in Mixed Traffic[J]. arXiv preprint arXiv:2204.03747, 2022. [paper link](https://arxiv.org/abs/2204.03747)
4. Dong J, Xu Q, Wang J, et al. Mixed cloud control testbed: Validating vehicle-road-cloud integration via mixed digital twin[J]. IEEE Transactions on Intelligent Vehicles, 2023. [paper link](https://arxiv.org/abs/2212.02007)
5. Wang J, Zheng Y, Dong J, et al. Implementation and experimental validation of data-driven predictive control for dissipating stop-and-go waves in mixed traffic[J]. IEEE Internet of Things Journal, 2023. [paper link](https://arxiv.org/abs/2204.03747)
## Citing MCCT
If you refer to MCCT in your research, please cite the [paper](https://arxiv.org/abs/2212.02007). In BibTeX format:

```bibtex
@article{dong2023mixed,
  title={Mixed cloud control testbed: Validating vehicle-road-cloud integration via mixed digital twin},
  author={Dong, Jianghong and Xu, Qing and Wang, Jiawei and Yang, Chunying and Cai, Mengchi and Chen, Chaoyi and Liu, Yu and Wang, Jianqiang and Li, Keqiang},
  journal={IEEE Transactions on Intelligent Vehicles},
  year={2023},
  publisher={IEEE}
}
```

## Contacts
For more details, please contact [Jianghong Dong](https://www.researchgate.net/profile/Jianghong-Dong) and [Jiawei Wang](https://wangjw18.github.io/).

