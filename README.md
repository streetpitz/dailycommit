# dailycommit
I try to commit this repository everyday

/2021-08-18
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="UTF-8">
    <title>연습문제 2</title>
    <style>
			#container { 
				width:520px;
				border:1px solid black;
				padding:20px 40px;
				margin:0 auto;
			}
      fieldset { margin-bottom:15px; }
      legend { font-weight:bold; }
			ul {list-style-type: none;}
			li { line-height:30px;}
    </style>
  </head>
  <body>
		<div id="container">
			<h1>프런트엔드 개발자 지원서 </h1>
			<p>HTML, CSS, Javascript에 대한 기술적 이해와 경험이 있는 분을 찾습니다.</p>
			<hr>
			<form>		
				<h3>개인정보</h3>
				<ul>
					<li>
						<label for="r-name">이름</label>
						<input type="text" id="r-name" placeholder="공백 없이 입력하세요">
					</li>
					<li>
						<label for="r-tel">연락처</label>
						<input type="tel" id="r-tel">
					</li>
				</ul>
				<h3>지원 분야</h3>				
				<ul>
					<li>						
						<label><input type="radio" name="분야" value="퍼블리싱">웹	퍼블리싱</label><br>
					</li>
					<li>
						<label><input type="radio" name="분야" value="어플">웹 애플리케이션 개발</label><br>
					</li>
					<li>
						<label><input type="radio" name="분야" value="환경">개발 환경 개선</label><br>
					</li>
				</ul>
				<h3>지원 동기</h3>
				<textarea id="동기" cols="60" rows="5" placeholder="본사 지원 동기를 간략히 써 주세요."></textarea>
				<button type="submit">접수하기</button>
				<button type="reset">다시 쓰기</button>
			</form>
		</div>
  </body>
</html>
