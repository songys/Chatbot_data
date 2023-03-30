# Chatbot_data.          
Chatbot_data_for_Korean v1.0             


## Data description.    

인공데이터입니다. 일부 이별과 관련된 질문에서 다음카페 "사랑보다 아름다운 실연( http://cafe116.daum.net/_c21_/home?grpid=1bld )"에서 자주 나오는 이야기들을 참고하여 제작하였습니다. 
가령 "이별한 지 열흘(또는 100일) 되었어요"라는 질문에 챗봇이 위로한다는 취지로 답변을 작성하였습니다. 


1. 챗봇 트레이닝용 문답 페어 11,876개           
2. 일상다반사 0, 이별(부정) 1, 사랑(긍정) 2로 레이블링                
                      
                     
## Quick peek.                
                                     
![quick_peek](./data.png)


## 관련 코드 : [Korean Language Model for Wellness Conversation](https://github.com/nawnoes/WellnessConversationAI?fbclid=IwAR3ZhXYW_DwI2RXP1mbHzvafGXF80QWERa4t6TTz_m2NQug5QwjOwQt6Hvw)
- 이 곳에 저장된 데이터를 만들면서 누군가에게 위로가 되는 모델이 나오면 좋겠다고 생각했었는데 제 생각보다 더 잘 만든 모델이 있어서 링크 걸어 둡니다. 부족한 데이터지만 이곳에 저장된 데이터와 [AI 허브 정신건강 상담 데이터](http://www.aihub.or.kr/keti_data_board/language_intelligence)  를 토대로 만들었다고 합니다. 
- 전창욱 외(2020), 텐서플로2와 머신러닝으로 시작하는 자연어처리, 위키북스( http://cafe116.daum.net/_c21_/home?grpid=1bld )의 챗봇 부분에도 이 데이터가 사용된 것으로 알고 있습니다. 빠르게 챗봇 만들고 싶으신 분들은 참고하셔도 좋을 것 같습니다.
- 데이터 로더를 통한 다운로드는 다음 링크 [Korpora: Korean Corpora Archives](https://github.com/ko-nlp/Korpora)를 참고하시면 편하게 사용하실 수 있을 듯합니다.



#인용

Youngsook Song.(2018). Chatbot_data_for_Korean v1.0)[Online]. Available : https://github.com/songys/Chatbot_data (downloaded 2022. June. 29.)
