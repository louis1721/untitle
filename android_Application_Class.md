# 제목<br>
내용<br>

커스텀 어플리케이션 클래스 사용하는 이유<br>
1. 첫번째 activity 보다 먼저 무언가를 해야할때<br>
2. Global initalization이 필요할때<br>
3. 불변의 static 데이터를 사용하는 static 메소드를 정의하여 사용 (예: 공용 네트워크 클라이언트 object)<br>

주의사항: 가변 데이터는 저장하면 안됨.. 앱이 언제 죽을지 모름<br>

-참조-<br>
https://github.com/codepath/android_guides/wiki/Understanding-the-Android-Application-Class
