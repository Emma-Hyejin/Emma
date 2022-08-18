<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  </head>
<body>
  <header class="header">
    <a class="logo" href="#">FastCampus Portfolio</a>
    <nav class="nav">
      <ul>
        <li><a href="#">사진 올리기</a></li>
        <li><a href="#">내 정보</a></li>
        <li><a href="#">팔로우 보기</a></li>
        <li><a href="#">팔로워 보기</a></li>
      </ul>
    </nav>
    <a class="account" href="#">Logout</a>
  </header>
  <main class="main">
    <aside class="aside">
      <div class="option-title">사진 업로드</div>
      <ol>
        <li>양식을 저장한다.</li>
        <li>사진파일을 첨부한다.</li>
        <li>올리기 버튼을 누른다.</li>
      </ol>

    </aside>
    <div class="content">

      <section class="section intro">
        <h1>사진 올리기</h1>
        <p>
            수많은 이용자들이 공유하는 멋진 사진들을 구경하고<br>
            내가 직접 찍은 작품들을 공유하세요!
        </p>
       
      </section>

      <section class="section form">
        <article style="text-align:center">사진 업로드 폼</article>
        <br>
        <div>
            <label>저자정보</label>
            <label for="ip-name">이름</label>
            <input id="ip-name" type="text"/>
            <br>
            <br>

            <input id="id-person" name="type" type="radio" checked/>
            <label for="id-person">일반인</label>
            <input id="id-pro" name="type" type="radio"/>
            <label for="id-pro">전문가</label>
            <br>
            <br>

            <label>사진 정보</label>
            <label for="ip-txt">제목</label>
            <input id="ip-txt" type="text"/>
            <br>
            <br>
            <label for="sel-theme">주제</label>
            <select id="sel-theme">
                <option value="green">자연</option>
                <option vlaue="math">수리</option>
                <option vlaue="org">상경</option>
            </select>
            <br>
            <br>
            <label for="ip-ex">설명</label>
            <textarea id="ipt-ex" placeholder="사진에 담은 생각 등을 자유롭게 적어주세요." rows="10"></textarea>
            <br>
            <Br>
            
            <label for="ip-file">사진 첨부</label>
            <input id="ip-file" type="file"/>
            <br>
            <br>
            <button type="button">올리기</button>
            <button type="button">취소</button>

            

        </div>
        <div>
            <img src="program.jpg" alt="패스트캠퍼스 사진"/>
            <p>
                패스트캠퍼스의 프로그래밍 첫거음 올인원 패키지 강좌로<br>
                여러분의 설레는 첫 코딩을 시작하세요!
            </p>
            <blockquote cite="https://fastcampus.co.kr/?utm_source=google&utm_medium=cpc&utm_campaign=hq^210101^%EC%9E%90%EC%83%81%ED%98%B8&utm_content=%ED%8C%A8%EC%8A%A4%ED%8A%B8%EC%BA%A0%ED%8D%BC%EC%8A%A4&utm_term=&gclid=EAIaIQobChMIl9aTiP3P-QIVRtiWCh2m2gZ-EAAYAiAAEgI4CfD_BwE">

            </blockquote>


        </div>
        
    

   

      </section>

    </div>
  </main>
  <footer class="footer">
    <ul>
      <li><a href="#">회사소개</a></li>
      <li><a href="#">인재채용</a></li>
      <li><a href="#">이용약관</a></li>
      <li><a href="#">개인정보 보호</a></li>
      <li><a href="#">고객센터</a></li>
    </ul>
  </footer>
  
</body>
</html>
