# OLED Face Simulator

128x64 SSD1306 OLED 표정 시뮬레이터. 텍스트 또는 마이크(크롬 음성 인식, ko-KR)로 말하면 키워드 규칙으로 감정을 판별해 표정을 바꾼다.

열기: https://rectuson849.github.io/oled-face/

## 대답 데이터
소리 내어 대답할 때 `chat_data.json`에서 들은 말과 가장 비슷한 질문을 찾아(글자 2개 묶음 TF-IDF 코사인 유사도 0.6 이상) 그 대답을 쓴다.
출처: [songys/Chatbot_data](https://github.com/songys/Chatbot_data) (MIT License, `chat_data_LICENSE.txt`).
