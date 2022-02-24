# CollegeEntrancePassPredictor / 정시 합불 예측기 (2021.01)

CEPP is the program I made for predicting my pass/fail of Korean college entrance. It is based on the data from Jinhaksa, a Korean college application service. Just put some information about the recruitment in, and it will tell if you are likely to be admitted, admitted additionally, or rejected. The images below are screenshots of CEPP and Jinhaksa.

진학사 합격예측 서비스에서 제공하는 정보를 기반으로 정시전형 합불여부를 예측해보기 위해 만든 프로그램. 진학사의 합격예측 서비스는 나보다 점수가 높은 사람들 중 다른 대학에 합격하여 이탈할 사람들을 고려하지 않아 예측에 어려움이 있었다. 내가 지원할 학과의 모집인원, 현재 지원자 수, 내 등수 등을 입력하면 본인이 최초합격권인지, 추가합격권인지, 불합격권인지 표시해준다.
</br></br>
두 번째 사진의 그래프를 보면 최초컷과 최종컷(추가합격컷)을 **표준점수**로 나누고 있다. 표준점수는 당해 시험의 난이도를 반영하고, 수험자의 상대적 위치를 원점수보다 정확히 알 수 있다. 하지만, 표준점수로 합격을 가늠할 경우 학령인구의 지속적인 감소로 인해 매해 커트라인이 하락하는 현상때문에 적중률이 떨어진다. 실제로 내가 입시를 준비할 때, 원서를 넣은 학교에 연락해서 지난 해의 합격컷과 내 표준점수를 비교해달라고 부탁했는데, 입학이 많이 힘들 것 같다는 답변을 받았다. CEPP는 진학사 표본의 **등수**를 이용해 합불여부를 예측할 수 있게 만들었고, CEPP의 예측과 실제 입시 결과는 '합격'이었다.
</br></br>
<img width="1178" alt="스크린샷 2022-02-24 오후 8 01 19" src="https://user-images.githubusercontent.com/98376834/155512139-6c0dcfb5-decb-4735-8763-b96ea9d818d2.png">
</br></br>
![15589673_1563567953660450_46934350204939878_n](https://user-images.githubusercontent.com/98376834/155509120-e380f1b0-a745-4f3a-bcdf-0ffa642a1058.jpeg)
</br></br>
![다운로드 (1)](https://user-images.githubusercontent.com/98376834/153714455-f2811819-86ac-4704-89de-63930eb8696d.jpeg)

<진학사 합격예측 서비스>

