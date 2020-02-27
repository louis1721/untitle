# 제목<br>
내용<br>
https://stackoverflow.com/questions/14678593/the-application-may-be-doing-too-much-work-on-its-main-thread<br>
Webview에서 canvas에 drawing을 할때 stroke를 for문에서 5000회 정도 호출하면 아래와 같은 인포메이션 로그가 찍힘.<br>
I/Choreographer(1378): Skipped 55 frames!  The application may be doing too much work on its main thread.<br><br>
View를 업데이트 하는 시간이 너무 짧아서 몇 프레임은 그리지 못했다는것 같고, 너무 과도하게 발생하면 앱이 죽어버림<br>
canvas에 선을 모두 그려 놓은 뒤 stroke를 1번 호출하면 


