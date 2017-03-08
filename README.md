#reset css

####charset 선언
<pre><code>@charset "utf-8";</code></pre>

###엘리먼트들의 margin,padding,border 제거, HTML5에서 해당 속성이 있는 엘리먼트만 넣었습니다.
<pre><code>body,h1,h2,h3,h4,h5,h6,p,blockquote,pre,dl,dd,ol,ul,fieldset,legend,figure,menu{margin:0;padding:0;border:0}</code></pre>

###테이블 관련 속성
<pre><code>table,th,td{border-spacing:0;border-collapse:collapse}</code></pre>

###리스트 형식 엘리먼트 스타일 제거.
<pre><code>ol,ul,li{list-style:none}</code></pre>

###h태그들의 속성을 초기화 시켯습니다, 제가 사용하는 방법이니 삭제하셔도 됩니다.
<pre><code>h1,h2,h3,h4,h5,h6{font-size:1em;font-weight:normal}</code></pre>

###폰트 설정입니다, 기본적인 body에 선언하고 나머지는 aria 폰트를 기본적으로 가지고 있어서 재선언 해줫습니다.(pre,code 엘리먼트 의 폰트는 설정하지 않았습니다.)
<pre><code>body,input,textarea,keygen,select,button{font:normal 12px/1.2 'Open Sans','Noto Sans',sans-serif}</code></pre>

###브라우저마다 기본적인 모양들이 들어가 있는 요소들의 모양을 조금 빼줫습니다.
<pre><code>input,textarea,select,button{margin:0;padding:0;border-radius:0;color:#333;outline:0;vertical-align:middle}</code></pre>

###링크 관련 기본 모양을 제거했습니다.
<pre><code>a:link,a:visited,a:hover,a:active{text-decoration:none}</code></pre>

###링크 다음으로 많이 사용하는 유저 인터렉션 버튼의 모양을 제거 했습니다, 주로 컨트롤로 용으로 많이 사용합니다.
<pre><code>a,button,input[type='submit'],input[type='button'],input[type='reset']{border:0;background:transparent;cursor:pointer}</code></pre>

###이미지 정렬 및 링크시 border 제거.
<pre><code>img{border:0;vertical-align:top}</code></pre>

제가 사용하는 방법입니다.<br>
좀더 좋은 방법 및 피드백은 환영이지만 근거없는 피드백 및 방법론은 무시하겟습니다.
