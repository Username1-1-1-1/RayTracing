# 1. 렌더링 기본 개념

## 1.1 픽셀 색상 나타내기

먼저 r, g, b값을 0~1 사이의 값으로 정규화.
다음 이 값들에 255.999를 곱해서 양자화.

## 1.2 이미지 생성하기

P3 : PPM(Portable Pixmap) 이미지 파일 형식을 나타내는 매직 넘버.
실행파일 > image.ppm 명령어로 이미지 파일 생성.
리다이렉션 연산자(>): stdout을 지정된 파일로 보내 기록하는 역할.

## 1.3 광선
선형보간(Linear Interpolation, Lerp): 두 알려진 값 사이의 중간 지점 값을 선형적으로 추정하는 수학적 방법.

$$V_{\text{lerp}} = (1-a) \cdot V_{\text{start}}+a\cdot V_{\text{end}}$$
​
