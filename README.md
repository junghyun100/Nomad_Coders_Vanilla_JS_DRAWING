# Vanilla_JS를 이용한 Paint사이트

### 초기 설정
* Canvas는 500x500 사이즈
* Background는 White 색상.
* Brush는 2.5 사이즈
* Brush Color는 Black 색상

### 기능 구현
* Fill 기능 활성화 시 Canvas를 Click했을 시 이벤트 발생
> 이 후 Canvas는 현재 설정되어있는 Color로 채워지게 됨
 
* Paint 기능 활성화 시 Canvas를 Click했을 시 이벤트 발생
> 이 후 Canvas에 현재 설정되어있는 Color로 Brush를 따라 그려지게 됨

* Save 버튼 클릭 시 현재의 Canvas 그림이 PNG파일 형태로 저장됨

* Erase 버튼 클릭 시 현재의 Canvas 그림 위에 White 색상으로 Fill 버튼 했을 시 처럼 덮이게 됨.
> 현재 색상과는 연관 없음.