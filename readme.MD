### 1. 터미널 npm i 입력
### 2. file_server_list.txt 파일에 작업할 서버들 넣어 두기 (콤마로 split)
### 3. .env 파일 생성해서 app_constants 변수랑 똑같이 채우기
ex)  USER_ID = test
 PW = password
 SERVER_PATH = 서버경로
 PATCH_FILE_NAME = script.sh
 PORT = 1234 

 ### 4. error.txt 에 실패한 서버들 목록 쌓임
 ### 5. success.txt 에 성공한 서버 목록 쌓임
 ### 6. send_error.txt 에 패치 실패한 서버 목록쌓임 (에러서버에도 쌓임)
 ### 7. 터미널에서 npm start 실행
