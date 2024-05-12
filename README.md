# Enhancing Knowledge Tracing via Adversarial Training

## Requirements
```sh
PyTorch==1.7.0
Python==3.8.0
```

## Usage

### Cloning the repository
```
git@github.com:Ladyfish030/atkt.git
cd atkt
```

### Running
We evaluate our method on three datasets including **algebra2005**, **bridge2006** and **ASSISTments2015**.

#### Statics2011
```
python main.py --dataset 'algebra2005'
```

#### ASSISTments2009
```
python main.py --dataset 'bridge2006'
```

#### ASSISTments2015
```
python main.py --dataset 'ASSISTments2015'
```

## Acknowledgments
Code and datasets are borrowed from [AKT](https://github.com/arghosh/AKT). Adversarial training implementation is inspired by [adversarial_training](https://github.com/WangJiuniu/adversarial_training). Early stopping implementation is modified from [early-stopping-pytorch](https://github.com/Bjarten/early-stopping-pytorch).
    
### Reference

```  
@inproceedings{guo2021enhancing,
  title={Enhancing Knowledge Tracing via Adversarial Training},
  author={Guo, Xiaopeng and Huang, Zhijie and Gao, Jie and Shang, Mingyu and Shu, Maojing and Sun, Jun},
  booktitle={Proceedings of the 29th ACM International Conference on Multimedia},
  pages={367--375},
  year={2021}
}
``` 

