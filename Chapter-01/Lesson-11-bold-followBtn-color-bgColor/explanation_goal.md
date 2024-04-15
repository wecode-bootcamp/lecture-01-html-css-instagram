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

<subject> 주제: 사용자 인터페이스의 상호작용적 요소 강화를 위한 CSS 스타일 개선 </subject>
<explanation_goal>

1. 문제 상황: 현재 .instagram-button 클래스는 버튼에 대한 기본적인 스타일링(높이, 모서리 둥글기)만 제공하고 있으나, 특정 버튼('팔로우')을 사용자에게 더욱 눈에 띄게 만들어 상호작용을 유도하려는 추가적인 스타일링이 필요함을 이해시킴
2. instagram-button이라는 클래스를 가진 버튼 두 개 공통적으로는 글씨 두께를 굵게 해주어야 하고, 팔로우 버튼은 따로 글씨 색과 버튼 배경 색도 바꿔주어야 함을 이해 시킴
3. font-weight: bold;: 버튼 내의 글씨를 두껍게 만들어 텍스트를 더 돋보이게 하여, 사용자의 주의를 사로잡고 버튼의 중요성을 강조합니다.
4. .follow-button 클래스를 새로 생성하고 color: white; 및 background-color: rgb(0, 140, 255);를 적용합니다. 이는 '팔로우' 버튼에 대해 흰색 글씨와 밝은 파란색 배경을 설정하여, 시각적으로 대비되고 눈에 띄는 디자인을 제공합니다. 이러한 시각적 차별화는 사용자가 해당 버튼의 기능을 더 명확하게 인식하고, 필요한 액션을 취하도록 유도하는 데 도움을 줍니다.
5. 이처럼 하나의 요소는 2개 이상의 클래스를 가질 수도 있다는 것을 이해시킴.

</explanation_goal>

<script tone>

유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.

</script tone>