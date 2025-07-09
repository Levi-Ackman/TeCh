<div align="center">
  <h2><b> Code for Paper:</b></h2>
  <h2><b> Decentralized Attention Fails Centralized Signals: Rethink Transformers for Medical Time Series </b></h2>
</div>

## Get Started

1. Install requirements. ```pip install -r requirements.txt```
2. Download data. You can download all datasets from **Medformer**: [datasets](https://github.com/DL4mHealth/Medformer). **All the datasets are well pre-processed** *(except for the TDBrain dataset, which requires permission first)* and can be used easily thanks to their efforts. Then, place all datasets under a folder ```./dataset```
3. Train the model. We provide the experiment scripts of all benchmarks under the folder `./scripts`. 
4. You can use bash commands to individually run scripts in the 'scripts' folder from the command line to obtain results for individual datasets. For example, you can use the below command line to get the result of  **APAVA**: ```bash ./scripts/APAVA.sh ``` You can find the training history and results under the './logs' folder.

## Acknowledgement

This project is constructed based on the code in repo [**Medformer**](https://github.com/DL4mHealth/Medformer).
Thanks a lot for their amazing work!

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

