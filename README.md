<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | 오윤투르</title>
    <style>
        /* CSS Reset & Base Styles */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif; 
            line-height: 1.6; 
            color: #333; 
            background-color: #f8f9fa; 
        }

        /* 1. Header Section (Deep Navy) */
        header {
            background-color: #0a192f; 
            color: #e6f1ff;
            padding: 100px 20px;
            text-align: center;
        }
        .header-emoji { font-size: 4.5rem; margin-bottom: 15px; display: block; filter: drop-shadow(0 5px 15px rgba(0,0,0,0.3)); }
        header h1 { font-size: 3rem; margin-bottom: 10px; letter-spacing: -1.5px; }
        header p { font-size: 1.2rem; opacity: 0.8; font-weight: 300; }

        /* 2. Main Content Section */
        main {
            max-width: 850px;
            margin: -50px auto 80px;
            padding: 0 20px;
        }
        .card {
            background: white;
            padding: 50px;
            border-radius: 24px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.08);
        }

        /* Content Styling */
        section { margin-bottom: 45px; }
        section:last-child { margin-bottom: 0; }
        h2 { 
            font-size: 1.5rem; 
            color: #0a192f; 
            border-bottom: 2px solid #e6f1ff; 
            padding-bottom: 10px; 
            margin-bottom: 25px;
            display: flex;
            align-items: center;
        }
        h2 span { margin-right: 12px; }

        .info-list { list-style: none; }
        .info-list li { 
            margin-bottom: 15px; 
            display: flex; 
            align-items: center;
            font-size: 1.1rem;
        }
        .label { 
            font-weight: 700; 
            width: 120px; 
            color: #555; 
            flex-shrink: 0;
        }

        .interest-tags { display: flex; gap: 12px; flex-wrap: wrap; }
        .tag { 
            background: #e6f1ff; 
            color: #0a192f; 
            padding: 8px 18px; 
            border-radius: 30px; 
            font-size: 0.95rem; 
            font-weight: 600;
        }

        .goal-box {
            background: #f0f4f8;
            padding: 25px;
            border-radius: 12px;
            border-left: 5px solid #0a192f;
            font-style: italic;
            font-size: 1.15rem;
            color: #2c3e50;
            line-height: 1.7;
        }

        /* 3. Responsive Design (Mobile) */
        @media (max-width: 600px) {
            header { padding: 70px 20px; }
            header h1 { font-size: 2.3rem; }
            .card { padding: 35px 25px; }
            .label { width: 100px; }
            .info-list li { flex-direction: column; align-items: flex-start; }
            .label { margin-bottom: 4px; }
        }
    </style>
</head>
<body>

    <header>
        <span class="header-emoji">👨‍💻</span>
        <h1>오윤투르</h1>
        <p>청주대학교 | 경영학과 3학년</p>
    </header>

    <main>
        <div class="card">
            <!-- 관심 분야 / Сонирхол -->
            <section>
                <h2><span>🔍</span> 관심 분야</h2>
                <div class="interest-tags">
                    <span class="tag">프론트엔드 개발</span>
                    <span class="tag">비즈니스 전략</span>
                    <span class="tag">시장 분석</span>
                    <span class="tag">UX/UI 디자인</span>
                </div>
            </section>

            <!-- 개인 정보 / Миний тухай -->
            <section>
                <h2><span>✨</span> 프로필</h2>
                <ul class="info-list">
                    <li><span class="label">나이</span> 20세</li>
                    <li><span class="label">언어</span> 몽골어, 한국어</li>
                    <li><span class="label">기술 스택</span> HTML, CSS, JavaScript</li>
                    <li><span class="label">관심사</span> 새로운 기술 습득, 비즈니스와 기술의 융합</li>
                </ul>
            </section>

            <!-- 목표 / Зорилго -->
            <section>
                <h2><span>🎯</span> 목표</h2>
                <div class="goal-box">
                    "경영학적 통찰력과 프론트엔드 개발 역량을 결합하여, 사용자에게 최적의 가치를 제공하는 디지털 솔루션을 만드는 것이 목표입니다."
                </div>
            </section>
        </div>
    </main>

</body>
</html>
