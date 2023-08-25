# Cat Dog image YOLO-Practice
### coco데이터셋을 사용 강아지/고양이를 찾는 프로그램을 작성하기

📑 [coco dataset](https://cocodataset.org/#download)
먼저 위의 링크에서 파일을 다운 받은 후 사용할 파일들만 따로 빼서 정리를 해줬습니다
😺🐶클래스들 중에서 cat과  dog가 들어있는 17, 18 클래스만 사용하기로 하고 cat클래스는 0, dog클래스는 1로 다시 변경해주었습니다

#### 💻학습에 사용한 모델: YOLOv8n
![F1_curve](https://github.com/sennycho/CatDog-YOLOv8-practice/assets/131944345/af9968a2-ad9d-41bd-b6c8-39f709bcd4d5)

- 라벨과 예측 
<img width="824" alt="image" src="https://github.com/sennycho/CatDog-YOLOv8-practice/assets/131944345/f5f20bcd-b01b-4227-b8b0-1f8126e3f98c">


#### ✏️학습 완료 후 확인
- 강아지와 춘식이 인형이 있는 이미지를 사용해봤는데 강아지를 잘 잡아주는 모습을 볼 수 있습니다 
  ![image](https://github.com/sennycho/CatDog-YOLOv8-practice/assets/131944345/cf14f182-cc59-4645-bb81-d17a590d0bef)
