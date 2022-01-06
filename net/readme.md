##0、配置

    安装requestments.txt中列出的库

## 1、训练

```shell
python main.py --net='ffa' --crop --crop_size=120 --blocks=9 --gps=3 --bs=2 --lr=0.0001 --trainset='its_train' --testset='its_test' --steps=100 --eval_step=10
```

## 2、测试

```shell
python test.py --task='its' --test_imgs='test'
```

[GitHub](https://github.com/ENMOJY/FAA-NET_GPU)