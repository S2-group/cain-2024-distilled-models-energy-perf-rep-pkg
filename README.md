# The Impact of Knowledge Distillation on the Energy Consumption and Runtime Efficiency of NLP Models
This repository is a companion page for the following publication:
> Ye Yuan, Jingzhi Zhang, Zongyao Zhang, Kaiwei Chen, Jiacheng Shi, Vincenzo Stoico, Ivano Malavolta. The Impact of Knowledge Distillation on the Energy Consumption and Runtime Efficiency of NLP Models. Proceedings of the IEEE/ACM 3rd International Conference on AI Engineering--Software Engineering for AI (CAIN), 2024.

## Structure of the replication package
This replication package is organized according to the following structure:
```
├── README.md: The file you are reading right now.
├── LICENSE: File describing under which license the repository's content is being made available.
├── data                        Data used in the paper 
│   ├── experiment_data         Dataset generated from the experiment
│   ├── script                  Script for generating and visualizing the graphs from the dataset
│   └── plot                    Graphical representation of the results
├── documentation               Our paper detailing the experiment settings and results
└── src                         Source code and dependencies used in the paper
    └──script                   Code for executing the experiment
```

## Quick started

- To get started:

  ```
  git clone https://github.com/Ckkk112138/GoGreen2-replication-package.git
  cd GoGreen2-replication-package/
  pip install -r requirements.txt
  ```

- To execute the experiment and generate the dataset in `data/experiment_data`:

  `python src/experiment-runner src/script/linux-powerjoular-profiling/RunnerConfig.py`

- To reproduce the results from the dataset:

  `python data/script/<example_test>`
  Replace `<example_test>` with the actual name of your test file under `data/script` folder.

## How to cite us
If this study is helping your research, consider to cite it is as follows, thanks!

```
@inproceedings{cain_2024,
  title={{The Impact of Knowledge Distillation on the Energy Consumption and Runtime Efficiency of NLP Models}},
  author={Ye Yuan and Jingzhi Zhang and Zongyao Zhang and Kaiwei Chen and Jiacheng Shi and Vincenzo Stoico and Ivano Malavolta},
  booktitle={IEEE/ACM 3rd International Conference on AI Engineering--Software Engineering for AI (CAIN)},
  pages={To appear},
  year={2024},
  organization={IEEE}
}
```
