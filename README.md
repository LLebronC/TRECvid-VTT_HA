# TRECvid-VTT_HA
If you use this github please cite:

@InProceedings{lebron2022bertha,
  author    = {Lebron, Luis  and  Graham, Yvette  and  McGuinness, Kevin  and  Kouramas, Konstantinos  and  O'Connor, Noel E.},
  title     = {BERTHA: Video Captioning Evaluation Via Transfer-Learned Human Assessment},
  booktitle      = {Proceedings of the Language Resources and Evaluation Conference},
  month          = {June},
  year           = {2022},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {1566--1575},
  url       = {https://aclanthology.org/2022.lrec-1.168}
  }
## Folder structure
```bash
.
├── multiple-annotator/
│   ├── 2016/
│   │   ├── refernces
│   │   ├── systems
│   │   ├── ad-seg-scores-en-en.csv
│   │   └── urls
│   ├── 2017
│   ├── 2018
│   ├── 2019
│   └── 2020
└── single-annotator/
    ├── 2016/
    │   ├── refernces
    │   ├── systems
    │   ├── ad-seg-scores-en-en.csv
    │   └── urls
    ├── 2017
    ├── 2018
    ├── 2019
    └── 2020
```
## Structure explain
multiple-annotator is refer as MA in the paper.
single-annotator is refer as SA in the paper.
Its subfolder contains the data of each year. References are the human wroten captions per human annotator and systems contains the system generated captions per system.
In ad-seg-scores-en-en.csv you can find the human judments. Column SYS is the name of the system, SID is the line in the sysem refences file and also the id of the video in urls, RAW.SCR is the raw human judment and Z.SCR is the normalize score.
