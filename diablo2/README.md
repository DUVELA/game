싱글 PlugY에서 사용하려고 저장하는 파일들.<br>
runes(origin).txt 는 원본파일.<br>
runes(edit).txt 는 수정파일.<br>

사용하고자 하는 룬워드 파일은 runes 로 이름을 바꾸고 다음의 디아2설치 경로에 runes.txt 파일로 저장.
<ul>
<li>PlugY를 사용할 경우: Diablo II\Mod PlugY\data\Global\Excel</li>
<li>모드 없이 사용할 경우: Diablo II\data\Global\Excel</li>
</ul>

data\Global\Excel는 만들어 주면됨.

<ul>
  <li><a href="http://classic.battle.net/diablo2exp/items/runewords.shtml"><strong>룬워드 규칙(Rune Word Rules)</strong></a></li>
  <li><a href="https://github.com/fabd/diablo2/blob/master/code/d2_113_data/Skills.txt">skills</a></li>
</ul>

<h1>2020-02-26 생각난 김에.</h1><br>
CubeMain(origin).txt 는 원본파일.<br>
CubeMain(edit).txt 는 수정파일.<br>

큐빙 파일도 마찬가지로
사용하고자 하는 큐빙 파일은 CubeMain 로 이름을 바꾸고 다음의 디아2설치 경로에 CubeMain.txt 파일로 저장.


<h1>2020-05-18 개인적으로 원하던 세트아이템 베이스 업글.</h1><br>
처음에 시도 했을 때 set item의 코드를 몰라서 대충 3~4글자로 넣어서 했을 때 적용이 안되서 더 찾아보다가 다음의 영상을 봄.
https://youtu.be/yyQnhknWxHc 를 보고 지난번 룬워드 때 처럼 마지막줄에 넣어서 적용 안된건가 싶어 중간에 넣고 다시 해보니 적용된걸 확인.<br>
https://www.youtube.com/watch?v=i2Tx_6GUi3Y <s>영상에서 확인 할 땐 자수정을 썼는데 아머는 퍼토파, 무기는 퍼루비로</s> CubeMain(edit)에 수정한걸 올림.

<h1>2020-05-30</h1>
POD + PlugY를 하려고 하면서 
<ul>
  <li>첫번째 창모드 에러.</li>
  <li>두번째 인벤토리 에러.</li>
  <li>세번째 문제는 아니고 일반 공유창고를 하코 공유창고로 변경 가능한걸 확인함.</li>
 </ul>

<h1>2020-06-01</h1>
꽃잎 처럼 원소스킬 + 가 될 줄 알았는데 안됨.
그리고 지금 에러나서 싱글 캐릭이 안들어가져서 삭제 후 다시 설치함. - 게임 연 상태에서 룬워드를 수정해서 에러가 난듯.

<h1>2020-06-02</h1><br>
원소스킬 + 그룹 추가.<br>
이름: 'to Cold Skills', ' to Lightning Skills'<br>
-기존 .tbl 파일꺼 그대로 사용.<br>
옵션 추가를 위해 수정, 추가한 파일: Properties, ItemStatCost<br>
설치경로: ..\data\Global\Excel<br>
Skills 파일은 콜드, 라이트닝 마스터리 EType 수정때문에
