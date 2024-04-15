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

    .instagram-button {
      height: 30px;
      border-radius: 8px;
      border: none;
      font-weight: bold;
    }

    .follow-button {
      color: white;
      background-color: rgb(0, 140, 255);
    }
  </style>
</head>

<body>
  <img src="./instagram-profile.jpg" alt="profile-picture" />
  <div>
    >wecode
  </div>
  <button class="instagram-button follow-button"> 팔로우 </button>
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
  <img src="./instagram-profile.jpg" alt="profile-picture" />
  <div class="user-name">
    >wecode
  </div>
  <button class="instagram-button follow-button"> 팔로우 </button>
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

<subject> 주제: margin과 padding에대해 배우며 요소간 간격, 요소 내 간격 이해하기 </subject>
<explanation_goal>

1. 문제 상황: 기존의 스타일링에는 사용자가 주의를 기울여야 할 중요한 '팔로우' 버튼이 다른 요소들과 시각적으로 평이하게 묻힐 위험이 있었습니다.
2. 버튼끼리 너무 붙어있어서 간격을 설정해주어야 할 필요가 있음을 이해시킴.
3. 여백을 주는 방법에는 margin과 padding 두가지 방법이 있음을 이해시킴.
4. 요소를 기준으로, margin은 요소와 요소 사이에 간격을 만들어서, 서로 멀어지게 만들 수 있음을 이해시킴.
5. padding은 요소 끼리의 간격이 아니라, 요소 내부에 간격을 만들어 주는 것임을 이해시킴.
6. 시각적으로 보면 이해가 쉬우므로, 먼저 버튼에 공백을 만들어 주겠다고 계획을 알려줌.
7. margin-top: 24px; margin-right: 4px;: 버튼 주위에 여백을 추가하여, 버튼이 페이지 내에서 차지하는 공간을 더 명확하게 하고, 인접 요소들과의 구분을 명확히 합니다. 이는 눈에 잘 띄는 위치에 버튼을 배치하는 데 도움이 됩니다.
8. padding: 4px 20px;: 버튼 내부에 패딩을 추가하여 텍스트와 버튼 경계 사이의 공간을 넓혀줌으로써, 버튼의 클릭 가능 영역을 확대하고 사용자의 클릭 경험을 개선합니다. 좌/우 여백과 위/아래 여백을 따로 줄 수 있다는 것을 이해시킴.
9. 이를 통틀어 Box Model이라고 표현하며, 더 자세한 내용은 다른 요소들의 간격을 설정하면서 더 자세히 이해할 수 있다고 얘기하며, 어려운 개념에 대한 불안함을 해소시킴.

</explanation goal>

<script tone>

유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.

</script tone>