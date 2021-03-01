# 新しく始めたネトゲとその攻略１

## 新しいネトゲ

Kaggle
賞金が出る。

お酒を飲みながら軽い気持ちでできる。
たまに大会があるのでその時だけシラフ。

## エミュレータ環境

## Google Colaboratory

* n1-highmem-2 instance
* Ubuntu 18.04
* 2vCPU @ 2.2GHz
* GPU NVIDIA Tesla T4 16GB または Tesla K80 12GB

連続12時間使用可能！（実質無限！…ではない…？）

``` shell:
# 起動時間を確認する。
cat /proc/uptime | awk '{print $1 /60 /60 /24 "days (" $1 "sec)"}'
```
