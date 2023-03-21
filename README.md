# VAE_PROJECT

>[Author: Xiangyun Rao,520030910366]

## 1. Introduction

This is a project for the course of intelligent perception. The project is to implement a Variational Autoencoder (VAE) and use it to generate new images.

It contains these files:
1. `args.py`: used to make args.
2. `loss.py`: contains the BCEloss and KLDloss.
3. `VAE_model.py`: contains the module I defined.
4. `main.py`: contains the training and testing code.
5. `test.py`: contains the code to generate 2-d gassian distribution graph.

## 2. Run

```bash
python main.py --testing=True --model='./model/best_20.pth'
```

Check results in results folder.