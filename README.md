# PKLNet
PKLNet: Palm keypoint localization neural network for touchless palmprint recognition. [ [pdf](https://ieeexplore.ieee.org/abstract/document/10049596/) ]

## Requirements
- Anaconda 
- PyThorch 1.7
- Python 3.8

## Test
```shell
cd path/to/PKLNet
# download 'net_params_500.pth' here.
conda activate pklnet # (depends on your python version)
# modify the test folder (`dataset_dir`) path in `test.py`
python test.py
```

```
conda create -n pklnet python=3.8
conda activate pklnet
pip install -r requirements.txt 
```

```
@article{liang2023pklnet,
  title={PKLNet: Keypoint localization neural network for touchless palmprint recognition based on edge-aware regression},
  author={Liang, Xu and Fan, Dandan and Yang, Jinyang and Jia, Wei and Lu, Guangming and Zhang, David},
  journal={IEEE Journal of Selected Topics in Signal Processing},
  volume={17},
  number={3},
  pages={662--676},
  year={2023},
  publisher={IEEE}
}
```

[1] Liang, X., Fan, D., Yang, J., Jia, W., Lu, G., & Zhang, D. (2023). PKLNet: Keypoint localization neural network for touchless palmprint recognition based on edge-aware regression. IEEE Journal of Selected Topics in Signal Processing, 17(3), 662-676.

TODO ...