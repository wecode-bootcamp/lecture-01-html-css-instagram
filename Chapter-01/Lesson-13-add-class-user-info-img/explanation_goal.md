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

<subject> img 태그에 클래스 부여하기 및 section 태그로 user-info 영역 구분하기 </subject>
<explanation_goal>

1. <img class="profile-image">를 사용하여 프로필 이미지에 대한 스타일링을 별도로 관리합니다. 이렇게 클래스를 분리함으로써, 이미지와 텍스트 간의 적절한 간격과 정렬을 조율할 수 있어, 전반적인 페이지의 통일감과 가독성이 향상됩니다.

2. 웹 페이지의 주요 요소인 사용자 정보, 프로필 이미지, 액션 버튼을 명확하게 구분하여 사용자가 각 기능과 정보를 쉽게 식별할 수 있도록 하는 것입니다.

3. <section class="user-info">를 도입하여 사용자 정보 관련 요소들을 하나의 논리적 단위로 그룹화합니다. 이 구조는 CSS 스타일링을 통해 해당 섹션의 시각적 표현을 직관적으로 관리할 수 있게 해줍니다.

4. <section>태그의 의미와 사용하는 이유를 이해시킴.

5. <div>태그와 <section> 태그의 차이점과 공통점을 설명하고, 사용 용도를 각각 추천함.

</explanation_goal>
<script tone>

유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.

</script tone>