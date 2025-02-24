# F45boramae
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>F45 보라매 - 최고의 피트니스 경험</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .hero-section {
            background: none; position: relative; overflow: hidden;
            background-size: cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }
        .overlay {
            background: rgba(0, 0, 0, 0.5);
            padding: 50px;
            border-radius: 10px;
        }
    </style>
<style>
        .hero-section video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
    </style>
</head>
<body>
    <header class="hero-section">
        <video autoplay muted loop>
            <source src="https://www.f45training.com/assets/videos/f45_global_video.mp4" type="video/mp4">
        </video>
        <div class="overlay">
            <h1>F45 보라매</h1>
            <p>45분간 최고의 전신 운동! 지금 경험해보세요.</p>
            <a href="#contact" class="btn btn-primary">일주일 체험 신청</a>
        </div>
    </header>

    <section class="container my-5">
        <h2 class="text-center">F45 보라매 소개</h2>
        <p class="text-center">F45는 세계적인 피트니스 브랜드로, 고강도 인터벌 트레이닝을 통해 최상의 결과를 제공합니다.</p>
    </section>

    <section class="container my-5 text-center">
        <div class="ratio ratio-16x9">
            <iframe src="https://www.instagram.com/p/DGJqB2HzWwQ/embed" width="400" height="480" frameborder="0" scrolling="no" allowtransparency="true"></iframe>
            <script async src="https://www.instagram.com/embed.js"></script>
        </div>
    </section>

    <section id="contact" class="container my-5">
        <h2 class="text-center">문의하기</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">이름</label>
                <input type="text" class="form-control" id="name" placeholder="이름을 입력하세요">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">이메일</label>
                <input type="email" class="form-control" id="email" placeholder="이메일을 입력하세요">
            </div>
            <div class="mb-3">
                <label for="phone" class="form-label">연락처</label>
                <input type="tel" class="form-control" id="phone" placeholder="연락처를 입력하세요">
            </div>
                        <button type="submit" class="btn btn-primary">신청하기</button>
        </form>
    </section>

    <footer class="text-center py-4 bg-dark text-light">
        <p>&copy; 2025 F45 보라매. 모든 권리 보유.</p>
    </footer>
    
</body>
</html>
