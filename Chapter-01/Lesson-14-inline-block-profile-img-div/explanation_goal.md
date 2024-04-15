explanation_script를 작성해줘. 아래에 내가 'previous_code_snapshot', 'current_code_snapshot',
'future_target_snapshot', 'subject', 'explanation goal' 을 제공할게.

<previous_code_snapshot>
<!DOCTYPE html>
<html lang="en">

<head>
  <title> My First Instagram </title>
  <style>
    .profile-image {
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
  <img class="profile-image" src="./instagram-profile.jpg" alt="profile-picture" />
  <section class="user-info">
    <div class="user-name">
      >wecode
    </div>
    <button class="instagram-button follow-button"> 팔로우 </button>
    <button class="instagram-button"> 메시지 보내기</button>
  </section>
</body>

</html>
</previous_code_snapshot>

<current_code_snapshot>
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
  <img class="profile-image" src="./instagram-profile.jpg" alt="profile-picture" />
  <section class="user-info">
    <div class="user-name">
      >wecode
    </div>
    <button class="instagram-button follow-button"> 팔로우 </button>
    <button class="instagram-button"> 메시지 보내기</button>
  </section>
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

<subject> 주제: display: block과 display: inline-block  </subject>

<explanation goal> 
1. profile-image와 user-info가 좌우로 배치되어 한 줄에서 볼 수 있어야 하는데, 현재는 위 아래로 분리되어 있음을 확인함.
2. 이는 <div>태그와 <section>태그가 각각 한 줄의 넓이를 모두 차지 하는 속성을 가지고 있기 때문임을 이해함.
3. block 레벨 요소라는 단어를 소개하며, display 속성을 소개함.
4. 이를 block 레벨이 아닌 inline-block으로 변경하면, 같은 div태그, section 태그일지라도 같은 줄에 수평 배열 시킬 수 있음을 이해시킴.
5. 이러한 배치는 영역별 구분을 명확히 하고, 페이지 레이아웃의 전반적인 조화와 가독성을 개선합니다. 코드를 소개해줌.
6. 필요에 따라 display 속서을 자주 바꾸어 사용할 수 있음을 안내함.

</explanation goal>

<script tone>

유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.

</script tone>