# vegans

本リポジトリはvegans のexample リポジトリです。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── 00_univariate-gaussian.ipynb
│   ├── 01_multivariate-gaussian.ipynb
│   ├── 02_mnist.ipynb
│   ├── 03_mnist-conditional.ipynb
│   ├── 03_mnist_conditional.ipynb
│   ├── 04_mnist-image-to-image.ipynb
│   ├── 05_create-your-own-LSGAN.ipynb
│   ├── 06_create-your-own-Pix2PixGAN.ipynb
│   └── 07_create-your-own-LR-GAN.ipynb
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.6

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/vegans）

```
cd Desktop/vegans
```

- Dockerによる環境構築（フォルダをマウント：Desktop/vegans）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## Display notebooks

- [View Jupyter notebooks in nbviewer](https://nbviewer.jupyter.org/github/ykato27/vegans/tree/main/notebooks/)

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
