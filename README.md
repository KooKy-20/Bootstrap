# Bootstrap

<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>나의 첫 Bootstrap 웹사이트</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">내 사이트</a>
    </div>
  </nav>

  <header class="bg-primary text-white text-center py-5">
    <h1>환영합니다!</h1>
    <p>이것은 Bootstrap으로 만든 간단한 웹사이트입니다.</p>
  </header>

  <main class="container my-5">
    <div class="row">
      <div class="col-md-4">
        <h3>소개</h3>
        <p>이 웹사이트는 Bootstrap을 사용해 제작되었습니다. 반응형 디자인으로 어떤 화면에서도 잘 보여요!</p>
      </div>
      <div class="col-md-4">
        <h3>기능</h3>
        <ul>
          <li>반응형 레이아웃</li>
          <li>빠른 스타일링</li>
          <li>직관적인 구성</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h3>연락</h3>
        <button class="btn btn-success">이메일 보내기</button>
      </div>
    </div>
  </main>

  <footer class="bg-dark text-white text-center py-3">
    © 2025 내 웹사이트
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
