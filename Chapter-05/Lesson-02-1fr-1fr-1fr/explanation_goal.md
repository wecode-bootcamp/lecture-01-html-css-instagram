explanation_script를 작성해줘. 아래에 내가 'previous_code_snapshot', 'current_code_snapshot',
'future_target_snapshot', 'subject', 'explanation goal' 을 제공할게.

<previous_code_snapshot>
<file_name:index.html>
  <div class="postings">
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
  </div>
</file_name:index.html>
<file_name:style.css>
</file_name:style.css>

</previous_code_snapshot>

<current_code_snapshot>
<file_name:index.html>
  <div class="postings">
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
  </div>
</file_name:index.html>
<file_name:style.css>

.postings {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}
</file_name:style.css>

</current_code_snapshot>

<future_target_snapshot>
<file_name:index.html>
  <div class="postings">
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
    <img src="./01.jpg" class="posting-image" />
  </div>
</file_name:index.html>

<file_name:style.css>

.postings {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 4px;
}

.posting-image {
  width: 100%;
}
</file_name:style.css>

</future_target_snapshot>

<subject>  </subject>

<explanation goal> 

</explanation goal>

<script tone>

유치원 선생님처럼 친절하고 따뜻한 말투, 초보자에게 수업을 하기 위해 기초적인 내용까지 꼼꼼히 설명하고 넘어가는 선생님같은 말투. 하나라도 더 알려주고 싶어하는 멘토의 마음가짐을 가지고 있어요. "~합니다"체가 아니라 "~해요"체를 전체 문단의 70%이상 으로 구성하는 것이 좋아요.

</script tone>