<div align="center">
  <h2><b> Code for ICLR26 (Oral):</b></h2>
  <h2><b> Decentralized Attention Fails Centralized Signals: Rethink Transformers for Medical Time Series </b></h2>
</div>

## Introduction


## Usage

1. Install requirements.
```
pip install -r requirements.txt
```

2. Prepare data. You can download all datasets from [**Medformer**](https://github.com/DL4mHealth/Medformer). **All the datasets are well pre-processed** *(except for the TDBrain dataset, which requires permission first)* and can be used easily thanks to their efforts. Then, place all datasets under the folder
```
./dataset
```

4. Train the model. We provide the experiment scripts of all benchmarks under the folder
```
./scripts
```
5. For example, you can use the command line  below to get the result of  **APAVA**. The whole training history is under the ***'./logs'*** folder.
```
bash ./scripts/APAVA.sh
```

## Citation
If you find this repo helpful, please cite our paper.

```
@inproceedings{
yu2026tech,
title={Decentralized Attention Fails Centralized Signals: Rethinking Transformers for Medical Time Series},
author={Guoqi Yu and Juncheng Wang and Chen Yang and Jing Qin and Angelica I Aviles-Rivero and Shujun Wang},
booktitle={The Fourteenth International Conference on Learning Representations},
year={2026},
url={https://openreview.net/forum?id=oZJFY2BQt2}
}
```

## Acknowledgement

This project is built on the code in the repo [**Medformer**](https://github.com/DL4mHealth/Medformer).
**Thanks a lot for their amazing work!**

***Please also star their project and cite their paper if you find this repo useful.***
```
@article{wang2024medformer,
  title={Medformer: A multi-granularity patching transformer for medical time-series classification},
  author={Wang, Yihe and Huang, Nan and Li, Taida and Yan, Yujun and Zhang, Xiang},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={36314--36341},
  year={2024}
}
```

