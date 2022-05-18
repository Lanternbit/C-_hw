# C++프로그래밍 11팀 과제 계획서

>과제명 : 

>팀명 : 11팀
<br/>

업무 분담   
|직책|이름|학과|학년|담당업무|
|----|----|---|----|-------|
|팀장|서경호|컴퓨터공학과|4학년|구현, 보고서 작성, 동영상 제작|
|팀원|김병현|컴퓨터공학과|3학년|구현, 보고서 작성, 리플릿 작성|
|팀원|안보경|컴퓨터공학과|3학년|구현, 보고서 작성, 리플릿 작성|
|팀원|김선희|컴퓨터공학과|3학년|구현, 보고서 작성, 리플릿 작성|


## 1. 요약

### 1.1 과제 요약

#### p5js와 ml5라이브러리를 활용하여 사람의 윤곽선을 따서 뒷 배경과 합성하는 javascript기반의 프로그램을 만든다.
<br/>

## 2. 개요

### 2.1 배경

#### 인공지능과 그래픽스의 발달에 따라 이미지의 가공이 쉬워지고 있다. 이미 필요한 사람들이 쉽게 이용할 수 있는 관련 툴들이 많지만 ML5.js를 이용해 직접 이미지 합성을 시도해보고자 하였다.

### 2.2 필요성

#### 사진 필터는 여러 곳에 사용된지 꽤 오래된 기능이다. SNS에 업로드하기 위해 많은 사람들이 빈번하게 사용하고 있는 것이 대표적인 쓰임새로, 사람들의 사랑을 받으며 단지 사진의 색감을 조절하는 것이 아니라 취향에 따라 여러 배경을 합성하고 다양한 그림체로 변환하는 등 여러 기능이 추가되어왔다. 하지만 너무 다양한 기능은 사용에 장애를 초래할 수 있다. 그리고 그 장애물을 넘기위한 도구로 AI는 좋은 선택이 될 수 있기에 여러 이용자 및 개발자들은 점점 이를 도입해 갈 것이라 예상한다.

### 2.3 선택 동기

#### 회의결과 이 주제가 여러 의견들 가운데 결과물이 제일 직관적이고, 불특정 다수의 이용자가 평상시에 필요로 한다고 판단하여 선택하게 되었다.
<br/>

## 3. 목표 및 내용

### 3.1 정량적/정성적 목표

>1) 인물의 외곽을 따서 인물과 배경을 분리시킬 수 있는가?

>2) 한 인물사진에 다양한 배경사진을 설정에 따라 바꿔 적용시킬 수 있는가?

>3) BodyPix를 제대로 이용하여 인물의 특정 신체 부위만 적용시킬 수 있는가?

### 3.2 세부 내용

#### 1) 사진을 업로드한다.
![original image](https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/Harriet_Tubman_c1868-69_%28cropped%29.jpg/220px-Harriet_Tubman_c1868-69_%28cropped%29.jpg)  

#### 2) 프로그램을 실행시키면 인물이 있는 부분만 분리시킨다.
![processed image](https://user-images.githubusercontent.com/50915637/168789131-62db32e8-6ac6-4748-96b7-7181ba453123.PNG)

#### 3) 분리시킨 사진을 원하는 배경에 합성한다.
![processed image2](https://user-images.githubusercontent.com/50915637/168790405-71876bb7-dd02-4fe6-ba14-d1d46aaad387.png)
<br/>

## 4. 결과물

### 4.1 예상 결과물

#### 지정된 곳에 배경을 넣고 합성할 인물의 사진을 그 뒤에 넣으면 ml5 라이브러리를 활용하여 사진안에 인물의 배경을 제거하고 윤곽선을 따서 합성하고 싶은 사진과 합성하는 결과물을 예상하고 있다.

![expected result](https://blog.kakaocdn.net/dn/cAvoaZ/btqugEtGcEE/XW6qr2etS6zM0fni9xHcA1/img.png)
> 위의 사진은 포토샵을 이용하여 사람과 배경을 합성한 예시이나 ml5.js와 그래픽스를 이용하여 같은 작업을 간편하게 수행할 수 있게 구현할 계획이다.

### 4.2 기도효과 및 활용방안

#### 기존의 방식은 포토샵과 같은 프로그램을 숙련자가 이용하여 누끼를 따고 합성하는 귀찮은 방식을 사용하였다면 위의 결과물로 누구나 쉽게 웹에서도 인물의 윤곽선만 포함하고 뒷배경은 제거하여 원하는 사진과의 합성이 가능해진다. 현재로서는 인물만 추출할 수 있으며 사진만 적용 가능하지만 움직이는 영상에도 코드 수정을 통해 쉽게 적용할 수 있을 것이다.
<br/>

## 5. 수행일정

|                              |1주차|2주차|3주차|비고|
|------------------------------|-----|----|-----|----|
|1. 주제 선택                   |  O  |    |     |    |
|2. 업무 분담                   |  O  |    |     |    |
|3. 계획서 작성                 |  O  |    |     |    |
|4. ml5.js를 이용한 BodyPix 학습|     |  O  |    |    |
|5. 1차 구현, 시험              |     |  O  |    |    |
|6. 결과물 수정 및 완성          |    |  O  |     |    |
|7. 보고서 작성                 |     |     | O  |    |
|8. 발표PPT 및 리플릿 작성       |     |    |  O  |    |
|9. 동영상 제작                 |     |     |  O  |    |
<br/>

## 6. 참고문헌 및 자료

> [1] bodyfix(2020). https://learn.ml5js.org/#/reference/bodypix?id=bodypix (accessed may 18,2022).

> [2]  p5.js ml5.js(2020). https://wikidocs.net/book/5373 (accessed may 18,2022).

> [3] Image drag&drop(2020). https://wikidocs.net/102807 (accessed may 18,2022).
