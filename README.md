# EasyPR-python
EasyPR-python by fh
## Requirements
* python 3.5
* opencv 3.1
* tensorflow 1.0

## Compare
### easypr-1.4
![performance](pic/easypr_1.4.png)
### easy-python
![cnn_performance](pic/cnn_res_loss.png)
![cnn_performance](pic/cnn_res_acc.png)
## TODO
- [ ] plate judge

## Done
- [x] plate locate ( need test )
- [x] plate segment
- [x] char identify ( cnn 98.86%)

## How to train cnn
unzip `resources/train_data/chars.7z`

`python demo.py`
## Demo
`python demo.py`