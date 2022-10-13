## Time-To-Practice-

#### 1. 전체 layout
휴대폰 화면을 기준으로 크게, header, main-song, buttons, song-list 로 나눌 수 있습니다.

#### 2. header
header의 title은 flex와 justify-content를 이용해 가운데 정렬을 구현할 수 있습니다. <br/>
text-align을 사용해도 괜찮습니다. <br/>
header에서 삭제버튼은 absolute를 사용해 구현할 수 있습니다. <br/>
position: absolute 를 위해 header에 position: relative 선언하는 것을 잊지마세요.

#### 3. main-song
main-song 부분은 cover와 song data로 나눌 수 있습니다. <br/>
main-song에 flex 선언과 justify-content로 가로축을 일정 간격 맞춰줍니다.

#### 4. buttons
buttons에는 font awesome에서 제공하는 아이콘들을 적절히 활용해줍니다. <br/>
buttons 역시 flex와 justify-content로 일정 간격 맞춰줍니다. <br/>
button의 입체효과는 border-radius와 border-bottom-width를 이용하면 쉽게 구현할 수 있습니다.

#### 5. song-list
song-list 부분은 ul 태그를 이용해 구현해줍니다. <br/>
세로로 정렬하기위해 flex-direction: column을 선언해줍니다. <br/>
각 song은 main-song 파트와 마찬가지로 cover와 data로 나누어줍니다.
