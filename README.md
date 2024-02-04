# Kokoa Clone 2023 Update

Html & CSS are so much fun!

HerosIcons

FontAwesome

link:css (enter!)

shift + 방향키

폰트 찾기 goolgle fonts

기본적으로 적용되는 마진이나 패딩을 지워주기 위해 reset.css를 사용한다

- form은 중요한 2가지 속성(attribute)을 가지고 있다. 하나는 action이고, 다른 하나는 method이다.
  -action은 어떤 페이지로 data를 보낼건지 지정할 수 있다.
- action에 적어 놓은 URL에 해당하는 파일이 반드시 존재해야한다.
- method는 2가지 방식 중 하나를 쓸 수 있다. 하나는 POST이고, 다른 하나는 GET이다.
- POST는 백엔드 서버에 정보를 전송하는 방식이라 이번 강의에서는 사용할 수 없다.
- GET 방식은 보안에 취약하다. username이랑 password를 GET 방식으로 보내선 안된다. URL에 포함되어도 상관없는 정보들을 GET 방식으로 보내는 것이다.

nav>ul>li\*4 tab기능

- CSS에게 200px의 box를 원한다고 하면, CSS는 내가 원한대로 box를 만든다.근데 그 box에 padding을 추가하게 되면 CSS는 기본적으로 내가 원했던 200px을 유지하려고 할 것이다. 따라서, padding을 50px 줬다고 생각한다면 CSS는 box가 150px이 되었다고 생각할 것이다. 하지만 CSS는 이렇게 둘 수 없기 때문에 200px을 유지하기 위해서 box를 더 크게 만들 것이고 오히려 결과적으로 250px이 되는 것이다.
- box-sizing: border-box; → CSS에게 "내가 padding을 줘도 신경쓰지마. 내 box 사이즈를 늘리지 말아줘"라고 말하는 격이다.

.user-componen\_\_column\*2
