# Awesome-DL-Scheduling-Papers
🔥 A curated list of DL cluster scheduling papers.

Please feel free to pull requests or open an issue to add papers.


## Table of Content

- [Awesome-DL-Scheduling-Papers](#Awesome-DL-Scheduling-Papers)
  <!-- - [Industrial Traces](#milestone-papers) -->
  - [Schedulers for DL Training](#Schedulers-for-DL-Training)
  - [Schedulers for DL Inference](#Schedulers-for-DL-Inference)
  - [Glossary of Terms](#Glossary-of-Terms)

<!-- ## Industrial Traces -->



## Schedulers for DL Training
| **Scheduler** | **Year** | **Series** | **Paper** | **Objective** | **Heter.** | **Elastic** | **AutoML** | **Code** |  **Citations** |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Acme | 2024 | NSDI | [Paper](https://www.usenix.org/conference/nsdi24/presentation/hu) | ♣ | - | - | - | [Code](https://github.com/InternLM/AcmeTrace) | 
| Cassini | 2024 | NSDI | [Paper](https://arxiv.org/abs/2308.00852) | ♠♣♥ | - | ✔ | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/c095361942179c96cae0c30248fb6ff80b0bc390?fields=citationCount)](https://www.semanticscholar.org/paper/c095361942179c96cae0c30248fb6ff80b0bc390)
| Sia | 2023 | SOSP | [Paper](https://dl.acm.org/doi/10.1145/3600006.3613175) | ♠♣♥ | ✔ | ✔ | ✔ | [Code](https://github.com/siasosp23/artifacts) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/71de9b9cb83dcf53a86c7a3cb3ff7b36b3917978?fields=citationCount)](https://www.semanticscholar.org/paper/71de9b9cb83dcf53a86c7a3cb3ff7b36b3917978) |
| EasyScale | 2023 | SC | [Paper](https://dl.acm.org/doi/abs/10.1145/3581784.3607054) | ♠♣  | ✔ | ✔ | - | [Code](https://github.com/sUntvoOk/EasyScale_info_for_SC23) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/9a85cd8a2cc809e740485e1904dd5f6b15fcc371?fields=citationCount)](https://www.semanticscholar.org/paper/9a85cd8a2cc809e740485e1904dd5f6b15fcc371)
| Hydro | 2023 | OSDI | [Paper](https://www.usenix.org/conference/osdi23/presentation/hu) | ♠▲ | ✔ | ✔ | ✔ | [Code](https://github.com/S-Lab-System-Group/Hydro) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/6597b53ea7f7c1909870c9be6ed54695ec36d3b6?fields=citationCount)](https://www.semanticscholar.org/paper/6597b53ea7f7c1909870c9be6ed54695ec36d3b6)
|  Shockwave | 2023 | NSDI | [Paper](https://www.usenix.org/conference/nsdi23/presentation/zheng) | ♠♣♥ | - | ✔ | - | [Code](https://github.com/uw-mad-dash/shockwave) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/b5ab21eb46f4619cd22cb0691d6850c9802a705e?fields=citationCount)](https://www.semanticscholar.org/paper/b5ab21eb46f4619cd22cb0691d6850c9802a705e)
| ModelKeeper | 2023 | NSDI | [Paper](https://www.usenix.org/conference/nsdi23/presentation/lai-fan) | ♦♣ | - | - | ✔ | [Code](https://github.com/SymbioticLab/ModelKeeper) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/f6de443b1c6f49625575735ee01d714e1d63cde6?fields=citationCount)](https://www.semanticscholar.org/paper/f6de443b1c6f49625575735ee01d714e1d63cde6)
| Lyra | 2023 | EuroSys | [Paper](https://dl.acm.org/doi/10.1145/3552326.3587445) | ♠♣  | ✔ | ✔ | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/15822ae7035dec57b3126dac84386a415cb4d59e?fields=citationCount)](https://www.semanticscholar.org/paper/15822ae7035dec57b3126dac84386a415cb4d59e)
| SiloD | 2023 | EuroSys | [Paper](https://dl.acm.org/doi/abs/10.1145/3552326.3567499) | ♠♣♥ | ✔* | - | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/6ad2d6ea4a970974033b4742c376fb1c3dac86ed?fields=citationCount)](https://www.semanticscholar.org/paper/6ad2d6ea4a970974033b4742c376fb1c3dac86ed)
| FGD | 2023 | ATC | [Paper](https://www.usenix.org/conference/atc23/presentation/weng) | ♠♣  | - | - | - | [Code](https://github.com/hkust-adsl/kubernetes-scheduler-simulator) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/8f4e626c2783b0fada28d206c3584ed6674ba53f?fields=citationCount)](https://www.semanticscholar.org/paper/8f4e626c2783b0fada28d206c3584ed6674ba53f)
| ElasticFlow | 2023 | ASPLOS | [Paper](https://dl.acm.org/doi/10.1145/3575693.3575721) | ♣✿ | - | ✔ | - | [Code](https://github.com/pkusys/ElasticFlow) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/3995c7a3704db252cfcce18ef56562a89f4cf693?fields=citationCount)](https://www.semanticscholar.org/paper/3995c7a3704db252cfcce18ef56562a89f4cf693)
| Lucid | 2023 | ASPLOS | [Paper](https://dl.acm.org/doi/10.1145/3575693.3575705) | ♠♣  | - | - | - | [Code](https://github.com/S-Lab-System-Group/Lucid) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/d5fe97309afdf0da633e04b5da4212a054661ecf?fields=citationCount)](https://www.semanticscholar.org/paper/d5fe97309afdf0da633e04b5da4212a054661ecf)
| PowerFlow | 2023 | arxiv | [Paper](https://arxiv.org/abs/2304.06381) | ♦♣ | - | ✔ | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/d75dab1a203123b3319a65c107d08a4a8f0d4af3?fields=citationCount)](https://www.semanticscholar.org/paper/d75dab1a203123b3319a65c107d08a4a8f0d4af3)
| EDL | 2022 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9373916) | ♠♣ | - | ✔ | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/cda4c055b9f919fad1699a66c315a9b2e1031ec3?fields=citationCount)](https://www.semanticscholar.org/paper/cda4c055b9f919fad1699a66c315a9b2e1031ec3)
| AOnline | 2022 | TCC | [Paper](https://ieeexplore.ieee.org/document/9682563) | ♠♣ | - | ✔ | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/3445ed8d5a8df735f25fe7b6c18781176d7e990e?fields=citationCount)](https://www.semanticscholar.org/paper/3445ed8d5a8df735f25fe7b6c18781176d7e990e)
| Titan | 2022 | SoCC | [Paper](https://dl.acm.org/doi/abs/10.1145/3542929.3563460) | ♠♣  | - | - | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/22bc6d8c6fe96758ccf7099fcf482fce5525889f?fields=citationCount)](https://www.semanticscholar.org/paper/22bc6d8c6fe96758ccf7099fcf482fce5525889f)
| Muri | 2022 | SIGCOMM | [Paper](https://dl.acm.org/doi/10.1145/3544216.3544224) | ♠♣  | ✔* | - | - | [Code](https://github.com/Rivendile/Muri) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/106208a4a411a4788f455bcc1afaebe25dd04316?fields=citationCount)](https://www.semanticscholar.org/paper/106208a4a411a4788f455bcc1afaebe25dd04316)
| Synergy | 2022 | OSDI | [Paper](https://www.usenix.org/conference/osdi22/presentation/mohan) | ♣  | - | - | - | [Code](https://github.com/msr-fiddle/synergy) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/5af975364d0a228e316278575cadbe41f03b48e4?fields=citationCount)](https://www.semanticscholar.org/paper/5af975364d0a228e316278575cadbe41f03b48e4)
| Ali-MLaaS | 2022 | NSDI | [Paper](https://www.usenix.org/conference/nsdi22/presentation/weng) | ♠♣ | - | - | - | [Code](https://github.com/alibaba/clusterdata/tree/master/cluster-trace-gpu-v2020) | `136` (FEB 24)
| GADGET | 2022 | INFOCOM | [Paper](https://arxiv.org/abs/2202.01158) | ♠♣ | - | ✔ | - | [Code](https://zenodo.org/record/5847644#.YishWH8zZhE) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/578f04926177f2f63f1560aced52757678655344?fields=citationCount)](https://www.semanticscholar.org/paper/578f04926177f2f63f1560aced52757678655344)
| CloudBrain | 2022 | ICCD | [Paper](https://ieeexplore.ieee.org/abstract/document/9978490) | ♠ | - | - | - | [Code](https://openi.pcl.ac.cn/potato/CloudBrain-datasets) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/dd6c0726a2a0ad2459de0e4024ed134cd59382b8?fields=citationCount)](https://www.semanticscholar.org/paper/dd6c0726a2a0ad2459de0e4024ed134cd59382b8)
| Aryl | 2022 | arxiv | [Paper](https://arxiv.org/abs/2202.07896) | ♠♣ | - | ✔ | ✔ | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/dfe6da89a515bc8219a811baa289d2afb6fa660e?fields=citationCount)](https://www.semanticscholar.org/paper/dfe6da89a515bc8219a811baa289d2afb6fa660e)
| Singularity | 2022 | arxiv | [Paper](https://arxiv.org/abs/2202.07848) | ♠♣♦ | - | ✔ | - | - | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/0ab45561e83fbcca3397d2286e39ba1855cfd169?fields=citationCount)](https://www.semanticscholar.org/paper/0ab45561e83fbcca3397d2286e39ba1855cfd169)
| $DL^2$ | 2021 | TPDS | [Paper](https://arxiv.org/abs/1909.06040) | ♣ | - | ✔ | - | [Code](https://github.com/pengyanghua/DL2) |
| Astraea | 2021 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9655467/) | ♥ | - | - | - | [Code](https://github.com/yzs981130/Astraea_Artifacts) |
| Horus | 2021 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9428512) | ♠♣ | - | - | - | - |
| Liquid | 2021 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9664375) | ♣  | - | - | - | [Code](https://github.com/PasaLab/Liquid) |
| POP | 2021 | SOSP | [Paper](https://dl.acm.org/doi/10.1145/3477132.3483588) | ♥♣ | ✔ | - | - | [Code](https://github.com/stanford-futuredata/POP) |
| Chronus | 2021 | SoCC | [Paper](https://dl.acm.org/doi/abs/10.1145/3472883.3486978) | ✿ | - | - | - | [Code](https://github.com/S-Lab-System-Group/ChronusArtifact/) |
| SEER | 2021 | SoCC | [Paper](https://dl.acm.org/doi/pdf/10.1145/3472883.3486989) | ▲ | - | ✔ | ✔ | - |
| Helios | 2021 | SC | [Paper](https://dl.acm.org/doi/abs/10.1145/3458817.3476223) | ♣♦ | - | - | - | [Code](https://github.com/S-Lab-System-Group/HeliosArtifact) |
| ONES | 2021 | SC | [Paper](https://dl.acm.org/doi/10.1145/3458817.3480859) | ♠♣ | - | ✔ | - | [Code](https://github.com/kurisusnowdeng/ones_sc21) |
| Pollux | 2021 | OSDI | [Paper](https://www.usenix.org/conference/osdi21/presentation/qiao) | ♠♣♥ | - | ✔ | ✔ | [Code](https://github.com/petuum/adaptdl) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/2adcdc9e9e81147499e1372f992d25ac6265fb29?fields=citationCount)](https://www.semanticscholar.org/paper/2adcdc9e9e81147499e1372f992d25ac6265fb29)
| AFS | 2021 | NSDI | [Paper](https://www.usenix.org/conference/nsdi21/presentation/hwang) | ♠♣ | - | ✔ | - | - |
| SMD | 2021 | INFOCOM | [Paper](https://arxiv.org/abs/2105.13855) | ♣ | - | - | - | - |
| ANDREAS | 2021 | FCloud | [Paper](https://arxiv.org/abs/2105.05080) | ♦ | - | - | - | - |
| RubberBand | 2021 | EuroSys | [Paper](https://dl.acm.org/doi/10.1145/3447786.3456245) |  ♦ | - | ✔ | ✔ | - |
| Hermes | 2021 | Electronics | [Paper](https://www.mdpi.com/2079-9292/10/3/350) | ♣ | - | - | ✔ | - |
| Jigsaw | 2021 | DistributedML | [Paper](https://dl.acm.org/doi/10.1145/3488659.3493778) | ♣ | - | - | - | - |
| DynamoML | 2021 | CLOSER | [Paper](https://www.scitepress.org/Papers/2021/104834/104834.pdf) | ♠♣ | - | ✔ | - | - |
| GENIE | 2020 | TPDS | [Paper](https://ieeexplore.ieee.org/document/8778770) | ✿ | - | ✔ | - | - |
| Parrot | 2020 | TCC | [Paper](https://ieeexplore.ieee.org/document/9269382) | ♣ | - | - | - | - |
| Non-Intrusive | 2020 | SC | [Paper](https://dl.acm.org/doi/abs/10.5555/3433701.3433820) | ♠♣ | - | ✔ | - | - |
| Antman | 2020 | OSDI | [Paper](https://www.usenix.org/system/files/osdi20-xiao.pdf) | ♠♣ | - | ✔ | - | [Code](https://github.com/alibaba/GPU-scheduler-for-deep-learning) |
| Gavel | 2020 | OSDI | [Paper](https://www.usenix.org/conference/osdi20/presentation/narayanan-deepak) | ♣♥ | ✔ | - | - | [Code](https://github.com/stanford-futuredata/gavel) | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https://api.semanticscholar.org/graph/v1/paper/2f4d6d3748ac6822711fe0bbd4cf6d2e66fa6613?fields=citationCount)](https://www.semanticscholar.org/paper/2f4d6d3748ac6822711fe0bbd4cf6d2e66fa6613)
| HiveD | 2020 | OSDI | [Paper](https://www.usenix.org/conference/osdi20/presentation/zhao-hanyu) | ♣ | - | - | - | [Code](https://github.com/microsoft/hivedscheduler) |
| Themis | 2020 | NSDI | [Paper](https://www.usenix.org/conference/nsdi20/presentation/mahajan) | ♥ | - | - | - | - |
| Salus | 2020 | MLSys | [Paper](https://proceedings.mlsys.org/paper/2020/hash/f7177163c833dff4b38fc8d2872f1ec6-Abstract.html) | ♠♣ | - | - | - | [Code](https://github.com/SymbioticLab/Salus) |
| Vaibhav et al. | 2020 | MASCOTS | [Paper](https://ieeexplore.ieee.org/abstract/document/9285954) | ♠♣ | - | ✔ | - | - |
| SPIN | 2020 | INFOCOM | [Paper](https://ieeexplore.ieee.org/document/9155445/) | ♣ | - | - | - | - |
| E-LAS | 2020 | ICPP | [Paper](https://dl.acm.org/doi/fullHtml/10.1145/3404397.3404415) | ♣ | - | - | - | - |
| CODA | 2020 | ICDCS | [Paper](https://ieeexplore.ieee.org/document/9355823) | ♣ | ✔* | - | - | - |
| Elan | 2020 | ICDCS | [Paper](https://ieeexplore.ieee.org/document/9355755) | ♠♣ | - | ✔ | - | - |
| Yeung | 2020 | HotCloud | [Paper](https://www.usenix.org/conference/hotcloud20/presentation/yeung) | ♠ | - | - | - | - |
| $Gandiva_{fair}$ | 2020 | EuroSys | [Paper](https://dl.acm.org/doi/abs/10.1145/3342195.3387555) | ♥♣ | ✔ | - | - | - |
| MLCloudPrice | 2020 | DISPA | [Paper](https://cs.stanford.edu/~matei/papers/2020/dispa_cloud_ml.pdf) |  ♣♦ | - | - | - | [Code](https://github.com/stanford-futuredata/training_on_a_dime) |
| MLFS | 2020 | CoNext | [Paper](https://dl.acm.org/doi/10.1145/3386367.3432588) | ♣✿ | - | - | - | [Code](https://github.com/hiddenlayer2020/ML-Job-Scheduler-MLFS) |
| MARBLE | 2020 | CCGRID | [Paper](https://ieeexplore.ieee.org/document/9407835) | ♠♣ | - | ✔ | - | - |
| Ada-SRSF | 2020 | arxiv | [Paper](https://arxiv.org/abs/2002.10105) | ♣ | ✔* | - | - | - |
| Co-scheML | 2020 | ACSOS | [Paper](https://ieeexplore.ieee.org/document/9196380) | ♣ | - | - | - | - |
| HyperSched | 2019 | SoCC | [Paper](https://dl.acm.org/doi/10.1145/3357223.3362719) | ✿ ▲ | - | ✔ | ✔ | - |
| Tiresias | 2019 | NSDI | [Paper](https://www.usenix.org/conference/nsdi19/presentation/gu) | ♣ | - | - | - | [Code](https://github.com/SymbioticLab/Tiresias) |
| FfDL | 2019 | Middleware | [Paper](https://dl.acm.org/doi/10.1145/3361525.3361538) | ♣ | - | - | - | [Code](https://github.com/IBM/FfDL) |
| JPAS | 2019 | JNCA | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1084804520300643) | ♣▲ | - | - | ✔ | - |
| Harmony | 2019 | INFOCOM | [Paper](https://ieeexplore.ieee.org/document/8737460) | ♣ | - | - | - | - |
| Cynthia | 2019 | ICPP | [Paper](https://dl.acm.org/doi/10.1145/3337821.3337873) | ♦ | - | ✔ | - | - |
| Jahani | 2019 | ICCCS | [Paper](https://ieeexplore.ieee.org/document/8888151) | ♦ | ✔ | ✔ | - | - |
| $Sched^2$ | 2019 | GLOBECOM | [Paper](https://ieeexplore.ieee.org/document/9014110) | ♣ | - | - | - | - |
| Dragon | 2019 | CLOSER | [Paper](https://pdfs.semanticscholar.org/3075/cf85b9a70092bcafa10757c6ee6f73b75c2e.pdf) | ♠♣ | - | ✔ | - | - |
| $FC^2$ | 2019 | CC | [Paper](https://link.springer.com/article/10.1007/s10586-019-02912-6) |  ♦ | ✔* | ✔ | - | - |
| Philly | 2019 | ATC | [Paper](https://www.usenix.org/conference/atc19/presentation/jeon) | ♣ | - | - | - | [Code](https://github.com/msr-fiddle/philly-traces) |
| Gandiva | 2018 | OSDI | [Paper](https://www.usenix.org/conference/osdi18/presentation/xiao) | ♠♣ | - | ✔ | ✔ | - |
| OASiS | 2018 | INFOCOM | [Paper](https://ieeexplore.ieee.org/abstract/document/8486422) | ♠♣ | - | ✔ | - | - |
| Optimus | 2018 | EuroSys | [Paper](https://i.cs.hku.hk/~cwu/papers/yhpeng-eurosys18.pdf) | ♣  | - | ✔ | - | [Code](https://github.com/pengyanghua/optimus) |
| Dorm | 2017 | SMARTCOMP | [Paper](https://www.computer.org/csdl/proceedings-article/smartcomp/2017/07947053/12OmNAlvHZ3) | ♥ | - | - | - | - |
| Topology-Aware | 2017 | SC | [Paper](https://dl.acm.org/doi/10.1145/3126908.3126933) | ♣ | - | - | - | [Code](https://github.com/HiEST/gpu-topo-aware) |
| HyperDrive | 2017 | Middleware | [Paper](https://dl.acm.org/doi/10.1145/3135974.3135994) | ♣▲ | - | - | ✔ | - |

`Symbols of Training Schedulers`:
| JCT | Utilization | Cost | Fairness | DDL | Accuracy |
|:---:|:---:|:---:|:---:|:---:|:---:|
| ♣ | ♠ | ♦ | ♥ | ✿ | ▲ |

<!-- JCT: ♣ Utilization: ♠ Cost: ♦ Fairness: ♥ DDL: ✿ Accuracy: ▲  -->

## Schedulers for DL Inference
| **Scheduler** | **Year** | **Series** | **Paper** | **Objective** | **Batch** | **Share** | **Cloud** | **Source Code** |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| SpotServe | 2024 | ASPLOS | [Paper](https://arxiv.org/abs/2311.15566) | ♦♥ | ✔ | - | ✔ | [Code](https://github.com/Hsword/SpotServe) |
| DeltaZip | 2023 | arxiv | [Paper](https://arxiv.org/abs/2312.05215) | ♥♠ | ✔ | - | - | [Code](https://github.com/eth-easl/deltazip) |
| MOSEL | 2023 | arxiv | [Paper](https://arxiv.org/abs/2310.18481) | ♦♠ | ✔ | - | - | - |
| Punica | 2023 | arxiv | [Paper](https://arxiv.org/abs/2310.18547) | ♥♠ | - | ✔* | - | [Code](https://github.com/punica-ai/punica) |
| S-LoRA | 2023 | arxiv | [Paper](https://arxiv.org/abs/2311.03285) | ♥♠ | - | ✔* | - | [Code](https://github.com/S-LoRA/S-LoRA) |
| Symphony | 2023 | arxiv | [Paper](https://arxiv.org/abs/2308.07470) | ✿♠♦ | ✔ | - | - | - |
| DeepPlan | 2023 | EuroSys | [Paper](https://dl.acm.org/doi/abs/10.1145/3552326.3567508) | ♦♠ | ✔ | - | - | [Code](https://github.com/csl-ajou/DeepPlan) |
| Tabi | 2023 | EuroSys | [Paper](https://dl.acm.org/doi/abs/10.1145/3552326.3587438) | ♦♣ | - | - | ✔ | - |
| Kairos | 2023 | HPDC | [Paper](https://dl.acm.org/doi/abs/10.1145/3588195.3592997) | ♦♥♠ | ✔ | - | ✔ | [Code](https://zenodo.org/records/7888058) |
| Shepherd | 2023 | NSDI | [Paper](https://www.usenix.org/conference/nsdi23/presentation/zhang-hong) | ✿♠♦ | ✔ | - | - | - |
| AlpaServe | 2023 | OSDI | [Paper](https://www.usenix.org/conference/osdi23/presentation/li-zhouhan) | ♦♠ | ✔ | ✔ | - | [Code](https://github.com/alpa-projects/mms) |
| Clover | 2023 | SC | [Paper](https://dl.acm.org/doi/abs/10.1145/3581784.3607034) | ♥ | ✔ | ✔ | - | [Code](https://zenodo.org/records/8084800) |
| iGniter | 2023 | TPDS | [Paper](https://ieeexplore.ieee.org/document/10002315) | ✿♥ | ✔ | ✔ | ✔ | [Code](https://github.com/icloud-ecnu/igniter) |
| Gpulet | 2022 | ATC | [Paper](https://www.usenix.org/conference/atc22/presentation/choi-seungbeom) | ✿♠♥ | ✔ | ✔ | - | [Code](https://github.com/casys-kaist/glet) |
| Cocktail | 2022 | NSDI | [Paper](https://www.usenix.org/conference/nsdi22/presentation/gunasekaran) | ♣♦♥ | - | - | ✔ | [Code](https://github.com/jashwantraj92/cocktail) |
| INFaaS | 2021 | ATC | [Paper](https://www.usenix.org/system/files/atc21-romero.pdf) | ♦♥♠ | - | ✔ | ✔ | [Code](https://github.com/stanford-mast/INFaaS) |
| MIG-SERVING | 2021 | CoRR | [Paper](http://arxiv.org/abs/2109.11067) | ♦♥ | ✔ | ✔ | - | - |
| Mendoza et al. | 2021 | EuroMLSys | [Paper](https://dl.acm.org/doi/10.1145/3437984.3458837) | ♦ | - | ✔ | - | - |
| Abacus | 2021 | SC | [Paper](https://dl.acm.org/doi/10.1145/3458817.3476143) |  ♦♠ | - | ✔ | - | [Code](https://github.com/Raphael-Hao/Abacus) |
| Morphling | 2021 | SoCC | [Paper](https://dl.acm.org/doi/10.1145/3472883.3486987) | ♥♠ | ✔ | ✔ | ✔ | [Code](https://github.com/kubedl-io/morphling) |
| Irina | 2020 | APNet | [Paper](https://dl.acm.org/doi/10.1145/3411029.3411035) | ♦♠✿ | ✔ | ✔ | - | - |
| DyBatch | 2020 | CCGrid | [Paper](https://ieeexplore.ieee.org/document/9139602) | ♦♠ | ✔ | ✔ | - | - |
| CMS | 2020 | Future Internet | [Paper](https://www.mdpi.com/1999-5903/12/6/102) | ♣✿ | - | - | - | - |
| PERSEUS | 2020 | IC2E | [Paper](https://ieeexplore.ieee.org/document/9096261/) | ♦♥♠ | ✔ | - | ✔ | [Code](https://github.com/cake-lab/perseus) |
| AutoDeep | 2020 | Infocom | [Paper](https://ieeexplore.ieee.org/document/9155267) | ♦♥♠ | - | ✔ | ✔ | - |
| Clockwork | 2020 | OSDI | [Paper](https://www.usenix.org/conference/osdi20/presentation/gujarati) | ♦♠ | ✔ | - | - | [Code](https://gitlab.mpi-sws.org/cld/ml/clockwork) |
| GSLICE | 2020 | SoCC | [Paper](https://dl.acm.org/doi/10.1145/3419111.3421284) | ♠✿ | ✔ | ✔ | - | - |
| Inferline | 2020 | SoCC | [Paper](https://dl.acm.org/doi/10.1145/3419111.3421285) | ♦♥ | ✔ | - | ✔ | [Code](https://github.com/simon-mo/inferline-models) |
| MArk | 2019 | ATC | [Paper](https://www.usenix.org/conference/atc19/presentation/zhang-chengliang) | ♦♥ | ✔ | - | ✔ | [Code](https://github.com/marcoszh/MArk-Project) |
| TrIMS | 2019 | CLOUD | [Paper](https://ieeexplore.ieee.org/document/8814494) | ♦♠✿ | ✔ | ✔ | ✔ | [Code](https://github.com/rai-project/trims_mxnet) |
| Kube-Knots | 2019 | CLUSTER | [Paper](https://ieeexplore.ieee.org/document/8891040) | ♦✿ | ✔ | ✔ | - | - |
| Gilman et al. | 2019 | DIDL | [Paper](https://dl.acm.org/doi/10.1145/3366622.3368147) | ♦♠ | - | ✔ | - | - |
| Nanily | 2019 | HPCC | [Paper](https://ieeexplore.ieee.org/document/8855453) |  ♦♠ | ✔ | - | - | - |
| Ebird | 2019 | ICCD | [Paper](https://ieeexplore.ieee.org/abstract/document/8988602/) |  ♦♠✿ | ✔ | ✔ | - | [Code](https://github.com/sjtu-epcc/Ebird) |
| Tolerance Tiers | 2019 | ISPASS | [Paper](https://ieeexplore.ieee.org/abstract/document/8695638/) | ♣♦♥ | - | - | ✔ | - |
| RRL | 2019 | SC | [Paper](https://dl.acm.org/doi/10.1145/3295500.3356164) | ♦ | ✔ | ✔ | - | [Code](https://github.com/HeyangQin/RRL) |
| ParM | 2019 | SOSP | [Paper](https://dl.acm.org/doi/10.1145/3341301.3359654) | ♦ | ✔ | - | - | [Code](https://github.com/thesys-lab/parity-models) |
| HiveMind | 2018 | NIPS | [Paper](https://www.microsoft.com/en-us/research/publication/accelerating-deep-learning-workloads-through-efficient-multi-model-execution/) | ♠ | ✔ | ✔ | - | - |
| Space-Time | 2018 | NIPS | [Paper](http://learningsys.org/nips18/assets/papers/102CameraReadySubmissionGPU_Virtualization%20(8).pdf) | ♠✿ | ✔ | ✔ | - | - |
| Ease.ml | 2018 | VLDB | [Paper](https://dl.acm.org/doi/10.1145/3187009.3177737) | ♣ | - | - | - | [Code](https://github.com/easeml/automl) |
| Rafiki | 2018 | VLDB | [Paper](https://dl.acm.org/doi/10.14778/3282495.3282499) | ♣♦ | ✔ | - | - | [Code](https://github.com/nginyc/rafiki) |
| Clipper | 2017 | NSDI | [Paper](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/crankshaw) | ♣♦♠ | ✔ | - | - | [Code](https://github.com/ucbrise/clipper) |


`Symbols of Inference Schedulers`:
| Accuracy | Throughput | Latency| Cost | Utilization |
|:---:|:---:|:---:|:---:|:---:|
| ♣ | ♠ | ♦ | ♥ | ✿ |


## Glossary of Terms

| Terminology | Definition                                                  |
|-------------|-------------------------------------------------------------|
| JCT         | Job Completion Time (Job Finish Time - Job Submission Time) |
| Fairness    | a metric to assess whether resources are fairly shared among users or jobs                  |
| QoS         | Quality of Service                                          |
| DDL         | Deadline, a time point where DL job must be completed                                                   |
| SLO         | Service Level Objective                                     |
