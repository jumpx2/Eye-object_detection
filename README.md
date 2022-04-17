# Eye-tracking-object_detection

### Start 
```python
#for mac osx   
python -m venv tf   
   
source tf/bin/activate
```
   
### mac osx 
```python
brew install pyqt@5
brew install protobuf
brew install qt
brew install wget
brew install openssl@3   
    
    
pip install tf-slim
pip install pycocotools
pip install lxml
pip install lvis
pip install contextlib2
pip install --no-dependencies tf-models-official
pip install avro-python3
pip install pyyaml
pip install gin-config
pip install tensorflow-macos
```

### label Img를 사용해 라벨링하기
```python
https://github.com/tzutalin/labelImg
```

### tensorboard로 학습시킨 데이터 Loss 확인하기
<img width="1242" alt="스크린샷 2022-04-17 13 52 02" src="https://user-images.githubusercontent.com/81940655/163702807-9438a71a-76e2-4e7f-bced-e75155a02362.png">

<img width="375" alt="스크린샷 2022-04-17 14 08 19" src="https://user-images.githubusercontent.com/81940655/163702841-da8224e3-2213-4c4d-9b49-7ee4c4393ac3.png">

#결과를 확인하기 위해 plt.show()로 확인하기
![Apr-17-2022 15-09-00](https://user-images.githubusercontent.com/81940655/163702910-12aa7aa2-1cf6-4875-b5c2-57683de03127.gif)

## 사용한 모델
```python
http://download.tensorflow.org/models/object_detection/tf2/20200711/ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8.tar.gz
제일 작고 빠르기에 사용해봤습니다.   
Tensorflow/model/research/object_detection/g3doc/tf2_detection_zoo.md 에서 많은 모델들 이름과 tar.gz 파일 및 map 존재
```

### https://github.com/nicknochnack/TFODCourse를 보고 window를 mac os에 맞게 수정해서 eye tracking을 해봤습니다.
