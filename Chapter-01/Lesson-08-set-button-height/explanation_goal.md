explanation_script를 작성해줘. 아래에 내가 'previous_code_snapshot', 'current_code_snapshot',
'future_target_snapshot', 'subject', 'explanation goal' 을 제공할게.

<previous_code_snapshot>
<!DOCTYPE html>
<html lang="en">

<head>
  <title> My First Instagram </title>
  <style>
    img {
      width: 77px;
      height: 77px;
      border-radius: 50%;
    }

    div {
      font-family: Arial;
      font-size: 20px;
    }

    .instagram-button {}
  </style>
</head>

<body>
  <img src="./instagram-profile.jpg" alt="profile-picture" />
  <div>
    >wecode
  </div>
  <button class="instagram-button"> 팔로우 </button>
  <button class="instagram-button"> 메시지 보내기</button>
</body>

</html>
</previous_code_snapshot>

<current_code_snapshot>
<!DOCTYPE html>
<html lang="en">

<head>
  <title> My First Instagram </title>
  <style>
    img {
      width: 77px;
      height: 77px;
      border-radius: 50%;
    }

    div {
      font-family: Arial;
      font-size: 20px;
    }

    .instagram-button {
      height: 40px;
    }
  </style>
</head>

<body>
  <img src="./instagram-profile.jpg" alt="profile-picture" />
  <div>
    >wecode
  </div>
  <button class="instagram-button"> 팔로우 </button>
  <button class="instagram-button"> 메시지 보내기</button>
</body>

</html>

</current_code_snapshot>

<future_target_snapshot>
<!DOCTYPE html>
<html lang="en">

<head>
  <title> My First Instagram </title>
  <style>
    .profile-image {
      width: 77px;
      height: 77px;
      border-radius: 50%;
      display: inline-block;
    }

    .user-info {
      display: inline-block;
      padding-left: 28px;
    }

    .user-name {
      font-family: Arial;
      font-size: 20px;
    }

    .instagram-button {
      height: 30px;
      border-radius: 8px;
      border: none;
      font-weight: bold;
      margin-top: 24px;
      margin-right: 4px;
      padding: 4px 20px;
    }

    .follow-button {
      color: white;
      background-color: rgb(0, 140, 255);
    }
  </style>
</head>

<body>
  <header class="profile-wrapper">
    <img class="profile-image" src="./instagram-profile.jpg" alt="profile-picture" />
    <section class="user-info">
      <div class="user-name">
        >wecode
      </div>
      <button class="instagram-button follow-button"> 팔로우 </button>
      <button class="instagram-button"> 메시지 보내기</button>
    </section>
  </header>
</body>

</html>
</future_target_snapshot>

<subject> 주제: CSS 스타일 규칙의 상세화와 클래스 선택자의 활용 </subject>

<explanation goal>
1. 이번 강의에서는 CSS에서 클래스 선택자를 이용하여 스타일을 더 세밀하게 조정하는 방법을 배웁니다. 클래스 선택자를 활용함으로써, 스타일 시트를 통해 HTML 요소의 시각적 표현을 어떻게 개선할 수 있는지 보여줄 것입니다.
2. `.instagram-button` 클래스에 `height: 40px;` 스타일 규칙을 추가한 것을 볼 수 있습니다. 이는 해당 클래스가 적용된 모든 버튼의 높이를 40픽셀로 설정하여, 사이트의 일관성을 유지하며 사용자 경험을 향상시키는 데 기여합니다.
3. 기존에 비어 있던 `.instagram-button` 클래스에 스타일 규칙을 추가함으로써, HTML 요소에 클래스 기반 스타일링의 도입이 프로젝트의 가독성과 관리 용이성에 어떤 영향을 미치는지 이해합니다.
4. 원래 우리가 만드려고 하는 버튼과 비교했을 때, 40px로 설정한 버튼 높이가 다소 너무 값이 크다는 것을 이해함.
5. 걱정말고 숫자를 변경해가면서, 적절한 높이로 설정하면 된다는 것을 이해함.
</explanation goal>

<script tone>

유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.

</script tone>