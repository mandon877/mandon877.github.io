<html>
<meta charset="UTF-8">
  <meta http-equiv="CACHE-CONTROL" content="NO-CACHE">
  <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/milligram/1.2.3/milligram.min.css">
  <title>Simple Storage Dapp 예제 [mandon877]</title>
  <style>
    body {margin-left:50px;}
    #storedData {font-size:300%; margin-right:10px;}
    #newValue {width: 200px; margin-right:10px; text-align:right;}
  </style>
<body>
<h3>Simple Storage dApp 예제 [mandon877]</h3>
<ul>
  <li>
    컨트랙트 주소: <span id="contractAddr"></span>
  </li>
  <li>
    내 어카운트 주소: <span id="accountAddr"></span>
  </li>
  <li>
    컨트랙트에 저장된 값: <span id="storedData"></span> <button onclick="getValue()">새로고침</button> (현재블록: <span id="lastBlock"></span>)
  </li>
  <li><input id="newValue" type="text">
      <button onclick="setValue()">새 값으로 저장하기</button>
      <div id="result"></div>
  </li>
  <li>새 값을 저장한 후 팬딩 트랜잭션이 블록에 포함되면 자동으로 페이지가 업데이트될 것입니다.   %%%% </li>
</ul>
</body>
</html>
[블록체인 PROJECT](mandon877.github.io/jjhSimpleStorage.html)
