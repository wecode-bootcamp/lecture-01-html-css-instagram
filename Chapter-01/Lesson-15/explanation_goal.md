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

<subject> 주제: CSS 스타일링을 통한 웹 페이지 레이아웃 개선 </subject>
<explanation_goal>

문제 상황: 초기 디자인에서는 .profile-image와 .user-info 섹션이 시각적으로 분리되지 않아, 사용자 정보와 프로필 이미지 간의 구분이 뚜렷하지 않았습니다. 이로 인해 유저의 주의 분산과 정보 인식 효율성 저하가 우려되었습니다.

필요한 조치: 프로필 이미지와 사용자 정보 섹션 사이에 적절한 시각적 여백을 추가하여, 각 요소의 인식을 분명하게 하고 전체 레이아웃의 조화를 개선할 필요가 있었습니다.

적용된 변경 사항: .user-info 섹션에 padding-left: 28px; 속성을 추가하여, 프로필 이미지와 사용자 정보 사이에 충분한 간격을 배치함으로써 이 두 요소 사이의 시각적 분리와 구분을 강화했습니다.

개선 효과:

이러한 조정을 통해 유저의 시선이 자연스럽게 정보를 쫓을 수 있도록 유도되며, 페이지의 정보 제공이 보다 명확해집니다.
사용자 정보와 인터랙션이 중요한 버튼 사이의 시각적 관계가 개선되어 사용자 경험(UX)이 향상됩니다. 유저는 각 기능과 정보를 쉽게 구별하고, 원하는 액션을 더욱 직관적으로 수행할 수 있게 됩니다.
중요성: 이번 CSS 스타일링의 간단한 조정 사례를 통해, 웹 페이지의 레이아웃과 디자인을 세심하게 조율하는 것이 사용자 인터페이스(UI) 디자인에 얼마나 큰 영향을 끼치는지 학습합니다. 레이아웃의 각 요소는 정보 전달의 효율성뿐만 아니라, 사용자의 상호작용 경험을 향상시키는 데 중요한 역할을 수행합니다.

</explanation_goal>

<script tone>

유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.

</script tone>