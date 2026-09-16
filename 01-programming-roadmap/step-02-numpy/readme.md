# STEP 2. NumPy

## 학습 목표

수치 데이터를 배열 형태로 처리할 수 있다. EEG 데이터는 기본적으로 `Channel x Time` 형태이므로 NumPy가 매우 중요하다.

## 공부 내용

- [ ] ndarray
- [ ] shape
- [ ] reshape
- [ ] indexing
- [ ] slicing
- [ ] axis
- [ ] mean
- [ ] std
- [ ] min / max
- [ ] sum
- [ ] matrix 연산
- [ ] broadcasting

## 실습

1. EEG 형태의 가상 데이터 생성
2. Channel = 8, Sampling Rate = 256 Hz, Duration = 10 sec로 NumPy array 만들기
3. 특정 channel 선택하기
4. 평균 / 표준편차 계산하기
5. 원하는 시간 구간 slicing 하기

## 완료 기준

`EEG[channel, time]` 형태의 데이터를 자유롭게 선택하고 계산할 수 있다.

