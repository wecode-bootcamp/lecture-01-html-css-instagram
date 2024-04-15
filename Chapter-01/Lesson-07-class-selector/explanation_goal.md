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
  </style>
</head>

<body>
  <img src="./instagram-profile.jpg" alt="profile-picture" />
  <div>
    >wecode
  </div>
  <button> 팔로우 </button>
  <button> 메시지 보내기</button>
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

<subject> 주제: CSS 클래스 선택자의 기초 </subject>

<explanation goal>
1. 이번 강의의 목표는 CSS에서 중요한 개념 중 하나인 클래스 선택자의 기본을 이해하고, 실제 웹 페이지에서 어떻게 활용되는지 보여주는 것입니다. 클래스 선택자를 통해 특정 그룹의 HTML 요소에 스타일을 적용할 수 있다는 점이 핵심입니다.
2. `<button>` 요소에 `class="instagram-button"` 속성이 추가된 것을 관찰합니다. 이는 해당 버튼들을 하나의 그룹으로 식별하고, 이 그룹 전체에 스타일을 적용할 수 있는 기능을 제공합니다.
3. 이렇게 클래스를 선언하고 나면, 클래스 이름을 이용해서, 같은 태그를 이용하는 요소일지라도 특정한 요소들만 골라서 지칭할 수 있음을 이해함.
4. `<button>` 요소에 instagram-button이라는 클래스를 붙였으니, 이제 이 instagram-button을 선택해서, 색깔을 입히고, 글씨 색을 바꿔볼 예정이라는 것을 이해시킴.
3. `.instagram-button {}` 스타일 정의를 보면 현재는 비어 있는 상태지만, 이 부분은 `instagram-button` 클래스를 가진 모든 요소에 스타일 규칙을 적용하는 곳입니다. 예를 들어, 배경색, 글꼴 색상, 테두리 스타일 등을 여기서 정의할 수 있습니다.
4. 가상의 예로, 만약 `.instagram-button { background-color: blue; color: white; }`라고 스타일을 추가한다면, 모든 'instagram-button' 클래스를 가진 버튼은 파란색 배경과 흰색 글씨로 표시될 것입니다. 이를 통해, 하나의 스타일 규칙으로 여러 요소의 외관을 일관적으로 관리할 수 있음을 보여줍니다.
5. 클래스 선택자의 장점 중 하나는 재사용성입니다. 이는 웹 페이지 내 여러 위치에서 동일한 스타일을 적용해야 하는 요소들에 매우 유용합니다. 따라서, 반복되는 스타일을 줄이고, 코드의 효율성을 높일 수 있습니다.
</explanation goal>
<script tone>
유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.
</script tone>