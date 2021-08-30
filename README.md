# MicAugment
Unofficial PyTorch implementation of [MicAugment](https://arxiv.org/abs/2010.09658): One shot microphone style transfer

Note: This is a work in progress. Details will follow in the upcoming commits

#### Todo
- [x] Microphone Model (PyTorch)
- [ ] Data preprocessing pipeline
- [ ] Training pipeline
- [ ] Jupyter notebook with examples
- [ ] Device identification
- [ ] SEANet & evaluation of robustness
- [ ] Pretrained checkpoints

### Requirements

```
conda env create -f environment.yml
conda activate mic_env
```

### Training pipeline

```
cd src
python prepare_data.py
python trainer.py <arguments>
```

### Citation

```
@inproceedings{borsos2021micaugment,
  title={Micaugment: One-Shot Microphone Style Transfer},
  author={Borsos, Zalán and Li, Yunpeng and Gfeller, Beat and Tagliasacchi, Marco},
  booktitle={ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={3400--3404},
  year={2021},
  organization={IEEE}
}
```

