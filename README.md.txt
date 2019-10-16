### REAME.md

- 월, 일, 시간, 기온, 지면온도, 일조시간, 습도, 풍속을 입력 데이터로 한 DNN 모델 입니다.

- 2017년 07월 01일부터 2019년 06월 30일 데이터를 입력 데이터로 하였습니다.

- http://www.weather.go.kr/weather/main.jsp#dong-forecast
  http://www.weather.go.kr/weather/forecast/timeseries.jsp
  위의 사이트에서 전라남도 해남군 황산면의 내일 기온, 풍속, 습도 데이터를 얻었습니다.

- 위에서 얻은 기온, 풍속, 습도 데이터를 바탕으로 내일의 일조시간 및 지면온도를 예측하였고 예측한 일조시간 및 지면온도를 추가로 입력데이터로 넣어 내일의 태양광 발전량을 예측했습니다.
 