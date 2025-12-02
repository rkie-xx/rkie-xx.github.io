<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>포트폴리오 – 홍길동</title>

    <style>
        body {
            font-family: 'Pretendard', sans-serif;
            margin: 0;
            background: #f4f6fa;
            color: #222;
        }
        header {
            background: #4a6cf7;
            padding: 40px;
            text-align: center;
            color: white;
        }
        nav {
            background: white;
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
        }
        nav a {
            text-decoration: none;
            font-weight: bold;
            color: #4a6cf7;
        }
        section {
            padding: 50px 20px;
            max-width: 900px;
            margin: auto;
        }
        h2 {
            border-left: 6px solid #4a6cf7;
            padding-left: 10px;
        }
        .card {
            background: white;
            padding: 20px;
            margin-top: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <h1>박세웅 포트폴리오</h1>
    <p>“배우고 도전하며 성장하는 사람이 되겠습니다.”</p>
</header>

<nav>
    <a href="#about">소개</a>
    <a href="#study">학습 이력</a>
    <a href="#skills">기술 스택</a>
    <a href="#goals">관심 분야</a>
</nav>

<section id="about">
    <h2>👋 자기소개</h2>
    <div class="card">
        <p><strong>이름:</strong> 박세웅</p>
        <p><strong>학과/학년:</strong> 소프트웨어융합대학/ 1학년</p>
        <p>웹 개발과 Ai 개발 분야에 관심이 있어 GitHub Pages, visual studio code를 통해 나만의 기술 기록 공간을 만들고 있습니다.</p>
    </div>
</section>

<section id="study">
    <h2>📚 학습 이력</h2>
    <div class="card">
        <p><strong>현재 수강 과목</strong></p>
        <ul>
            <li>웹활용및실습</li>
            <li>게임개발입문</li>
            <li>컴퓨터 개론</li>
        </ul>

        <p><strong>이수 완료한 주요 전공</strong></p>
        <ul>
            <li>Python 프로그래밍</li>
            <li>컴퓨터 프로그래밍</li>
        </ul>
    </div>
</section>

<section id="skills">
    <h2>🛠 보유 기술 스택</h2>
    <div class="card">
        <ul>
            <li>언어: C, Python, HTML/CSS, JavaScript</li>
            <li>툴: Git </li>
            <li>관심 분야: Ai개발 , 웹 백엔드 개발</li>
        </ul>
    </div>
</section>

<section id="goals">
    <h2>🎯 관심 분야 및 목표</h2>
    <div class="card">
        <p>희망 직무: 네트워크 엔지니어 & Ai 개발자</p>
        <p>현재는 기초를 다지는 중이며, 점차 어디로 나아가야할지 알아볼 것 같습니다.</p>
    </div>
</section>

<footer>
    © 2025 Hong Portfolio. All Rights Reserved.
</footer>

</body>
</html>
