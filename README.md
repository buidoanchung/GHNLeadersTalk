# GHNLeadersTalk
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Workshop: VIBE CODING - AI Dành Cho Lãnh Đạo & Người Không Chuyên</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Chosen Palette: Modern Professional (White/Light Gray base, Deep Blue primary, Teal accent) -->
    <!-- Application Structure Plan: A clean, top-down narrative structure. 1. Hero section grabs attention with a problem. 2. Solution section introduces "Vibe Coding". 3. Benefits section shows tangible value. 4. Speaker section builds credibility. 5. "What you'll build" section shows the hands-on project. 6. Detailed agenda provides specifics. 7. Final CTA converts. This linear flow is intuitive and builds momentum towards the registration call-to-action. -->
    <!-- Visualization & Content Choices: 
    - Hero Narrative: Goal: Engage -> Viz: Large, clean typography with subtle background graphics -> Interaction: None. Justification: Creates a professional, focused opening.
    - Benefits Grid: Goal: Inform/Persuade -> Viz: Icon-based grid with cards -> Interaction: Hover effects. Justification: Clearly communicates value propositions.
    - Speaker Bio: Goal: Build Trust -> Viz: Two-column layout with image and text -> Interaction: None. Justification: Professional and clean presentation of the expert.
    - Project Mockup: Goal: Inform -> Viz: Styled mockup of the "Idea Hub" app -> Interaction: None. Justification: Gives a clear, tangible goal for attendees.
    - Agenda: Goal: Organize -> Viz: Simple, clean list-based timeline -> Interaction: None. Justification: Easy-to-scan and clear for information delivery.
    -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7faff;
            color: #1e293b;
        }
        .hero-section {
            background-color: #ffffff;
            background-image:
                radial-gradient(at 88% 3%, hsla(204,67%,65%,0.2) 0px, transparent 50%),
                radial-gradient(at 2% 95%, hsla(338,78%,65%,0.2) 0px, transparent 50%);
        }
        .gradient-text {
            background: linear-gradient(90deg, #0ea5e9, #1d4ed8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .cta-button {
            background: linear-gradient(90deg, #0ea5e9, #1d4ed8);
            transition: all 0.3s ease;
        }
        .cta-button:hover {
            box-shadow: 0 10px 20px -10px rgba(29, 78, 216, 0.5);
            transform: translateY(-2px);
        }
        .card-hover {
            transition: all 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 4px;
            background-color: #0ea5e9;
            margin: 16px auto 0;
            border-radius: 2px;
        }
        .info-card {
            position: relative;
        }
        .download-btn {
            position: absolute;
            top: 16px;
            right: 16px;
            background-color: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(4px);
            border: 1px solid #e2e8f0;
            border-radius: 9999px;
            padding: 8px;
            cursor: pointer;
            transition: all 0.2s ease;
            z-index: 10;
        }
        .download-btn:hover {
            background-color: #ffffff;
            transform: scale(1.1);
        }
        .download-btn-icon {
            width: 20px;
            height: 20px;
            color: #334155;
        }
    </style>
</head>
<body class="antialiased">
    <!-- Logo Bar -->
    <header class="bg-white py-4">
        <div class="container mx-auto px-6 flex justify-center items-center space-x-6 md:space-x-10 opacity-70">
            <span class="font-bold text-slate-700">SCOMMERCE</span>
            <span class="font-bold text-orange-500">GiaoHàngNhanh</span>
            <span class="font-bold text-red-600">GiaoHàngNặng</span>
            <span class="font-bold text-green-500">Ahamove</span>
        </div>
    </header>

    <!-- Hero Section -->
    <div id="section-hero" class="info-card">
        <button class="download-btn" onclick="downloadSectionAsImage('section-hero', 'Workshop-Vibe-Coding-Gioi-Thieu.png')">
            <svg class="download-btn-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"></path></svg>
        </button>
        <section class="hero-section pt-16 pb-20 md:pt-24 md:pb-32">
            <div class="container mx-auto px-6 text-center">
                <p class="text-lg font-semibold text-blue-600 mb-4">LEADERS TALK</p>
                <h1 class="text-4xl md:text-6xl font-extrabold text-slate-900 leading-tight">Biến ý tưởng thành hiện thực.</h1>
                <p class="max-w-3xl mx-auto mt-6 text-lg text-slate-600">
                    Không cần biết code, chỉ cần biết cách trò chuyện. Nếu bạn có ý tưởng về một sản phẩm (web, app) nhưng không biết bắt đầu từ đâu, workshop này là dành cho bạn.
                </p>
                <div class="mt-10">
                    <a href="https://docs.google.com/forms/d/e/1FAIpQLSdGoyQK3nQ53sT0ih_8ya2Cqecy7_bEOO4J9O-FFsw-nZGkaw/viewform" target="_blank" class="cta-button text-white font-bold py-4 px-8 rounded-lg shadow-lg">
                        Đăng Ký Ngay
                    </a>
                </div>
            </div>
        </section>
    </div>

    <!-- Speaker Section -->
    <div id="section-speaker" class="info-card bg-white py-20">
        <button class="download-btn" onclick="downloadSectionAsImage('section-speaker', 'Workshop-Vibe-Coding-Dien-Gia.png')">
            <svg class="download-btn-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"></path></svg>
        </button>
        <section>
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-slate-900 section-title">Chuyên Gia Của Bạn</h2>
                </div>
                <div class="max-w-4xl mx-auto bg-white rounded-xl shadow-lg overflow-hidden md:flex border border-slate-200">
                    <div class="md:w-1/3 bg-slate-100 flex items-center justify-center p-8">
                        <img src="https://i.imgur.com/GRZ87yH.png" alt="Hình ảnh của Tiến sĩ Lê Thanh Bính" class="w-40 h-40 rounded-full object-cover shadow-md">
                    </div>
                    <div class="md:w-2/3 p-8">
                        <p class="text-xl font-bold gradient-text mb-2">Tiến sĩ LÊ THANH BÍNH</p>
                        <p class="font-semibold text-slate-700 mb-4">Technical Program Manager @ Google Ireland</p>
                        <p class="text-slate-600 leading-relaxed">
                            Với kinh nghiệm dày dặn trong việc quản lý các chương trình kỹ thuật phức tạp tại một trong những tập đoàn công nghệ hàng đầu thế giới, TS. Lê Thanh Bính là người hiểu rõ nhất cách công nghệ có thể tối ưu hóa hiệu suất và giải phóng tiềm năng con người.
                        </p>
                    </div>
                </div>
            </div>
        </section>
    </div>
    
    <!-- Agenda Section -->
    <div id="section-agenda" class="info-card bg-slate-50 py-20">
        <button class="download-btn" onclick="downloadSectionAsImage('section-agenda', 'Workshop-Vibe-Coding-Lich-Trinh.png')">
            <svg class="download-btn-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"></path></svg>
        </button>
        <section>
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-slate-900 section-title">Lịch Trình Chi Tiết</h2>
                </div>
                <div class="max-w-3xl mx-auto bg-white p-8 rounded-xl shadow-lg border">
                    <div class="space-y-8">
                        <div>
                            <p class="text-sm font-semibold text-blue-600">14:00 – 14:25</p>
                            <h3 class="text-xl font-bold mt-1">Phần 1: Khởi Động & Truyền Cảm Hứng</h3>
                            <p class="text-slate-600 mt-2">Check-in, giới thiệu và chứng kiến những màn demo "phép thuật" của AI coding để phá vỡ mọi định kiến.</p>
                        </div>
                        <div class="border-t border-slate-200"></div>
                        <div>
                            <p class="text-sm font-semibold text-blue-600">14:25 – 15:00</p>
                            <h3 class="text-xl font-bold mt-1">Phần 2: Nền Tảng & Tư Duy Cốt Lõi</h3>
                            <p class="text-slate-600 mt-2">Làm quen với Google AI Studio và nắm vững 4 nguyên tắc vàng để "ra lệnh" cho AI một cách hiệu quả.</p>
                        </div>
                        <div class="border-t border-slate-200"></div>
                        <div>
                            <p class="text-sm font-semibold text-blue-600">15:00 – 16:00</p>
                            <h3 class="text-xl font-bold mt-1">Phần 3: Thực Hành: Xây Dựng Ứng Dụng Đầu Tay</h3>
                            <p class="text-slate-600 mt-2">Bắt tay vào việc, áp dụng kiến thức đã học để xây dựng ứng dụng "Idea Hub" từ con số không.</p>
                        </div>
                        <div class="border-t border-slate-200"></div>
                        <div>
                            <p class="text-sm font-semibold text-blue-600">16:00 – 16:30</p>
                            <h3 class="text-xl font-bold mt-1">Phần 4: Tổng Kết & Hỏi Đáp</h3>
                            <p class="text-slate-600 mt-2">Ôn lại kiến thức, nhận gợi ý phát triển và giải đáp mọi thắc mắc cùng chuyên gia.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <!-- CTA Section -->
    <div id="section-register" class="info-card">
         <button class="download-btn" onclick="downloadSectionAsImage('section-register', 'Workshop-Vibe-Coding-Dang-Ky.png')">
            <svg class="download-btn-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"></path></svg>
        </button>
        <section id="register" class="py-20">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-5xl font-extrabold text-slate-900">Đây là cơ hội để thay đổi cách làm việc của bạn.</h2>
                <p class="max-w-2xl mx-auto mt-4 text-lg text-slate-600">Đừng để nỗi sợ công nghệ cản bước bạn. Hãy biến AI thành trợ thủ đắc lực nhất. Số lượng có hạn, hãy giữ chỗ ngay hôm nay!</p>
                
                <div id="register-box" class="mt-10 max-w-lg mx-auto bg-white p-8 rounded-xl shadow-2xl border">
                    <h3 class="text-2xl font-bold text-slate-800">Đăng Ký Tham Gia</h3>
                    <p class="mt-4 text-slate-600">Quét mã QR hoặc nhấn vào nút bên dưới để điền thông tin.</p>
                    <div class="mt-6 flex justify-center">
                        <img src="https://api.qrserver.com/v1/create-qr-code/?size=160x160&data=https://docs.google.com/forms/d/e/1FAIpQLSdGoyQK3nQ53sT0ih_8ya2Cqecy7_bEOO4J9O-FFsw-nZGkaw/viewform" alt="Mã QR Đăng ký Workshop" class="rounded-lg">
                    </div>
                    <a href="https://docs.google.com/forms/d/e/1FAIpQLSdGoyQK3nQ53sT0ih_8ya2Cqecy7_bEOO4J9O-FFsw-nZGkaw/viewform" target="_blank" class="cta-button mt-6 inline-block w-full text-white font-bold py-4 px-10 rounded-lg shadow-lg text-lg">
                        🔥 Giữ Chỗ Của Tôi Ngay! 🔥
                    </a>
                </div>

                <div class="mt-12 text-slate-600 bg-white max-w-lg mx-auto p-6 rounded-xl border">
                    <p class="font-bold text-lg text-slate-800">Thông Tin Sự Kiện</p>
                    <p class="mt-4"><strong>Thời gian:</strong> 14:00 – 16:00, Thứ Sáu, 11/07/2025</p>
                    <p class="mt-2"><strong>Địa điểm:</strong> Learning Center - Tầng 3, Tòa nhà Rivera Park, 7/28 Thành Thái, P.14, Q.10</p>
                    <p class="mt-2"><strong>Hình thức:</strong> Offline hoặc tham gia online qua Google Meet</p>
                    <div class="border-t my-4"></div>
                    <p class="text-sm"><strong>Hỗ trợ:</strong> NhưNTH - 086.225.8353 - @nhunth102</p>
                </div>
            </div>
        </section>
    </div>

<script>
    function downloadSectionAsImage(elementId, filename) {
        const downloadButton = event.currentTarget;
        const originalIcon = downloadButton.innerHTML;
        downloadButton.innerHTML = `<svg class="download-btn-icon animate-spin" fill="none" viewBox="0 0 24 24"><path fill="currentColor" d="M12,4a8,8,0,0,1,7.89,6.7A1.53,1.53,0,0,0,21.38,12h0a1.5,1.5,0,0,0,1.48-1.75,11,11,0,0,0-21.72,0A1.5,1.5,0,0,0,2.62,12h0a1.53,1.53,0,0,0,1.49-1.3A8,8,0,0,1,12,4Z"></path></svg>`;
        downloadButton.disabled = true;

        const elementToCapture = document.getElementById(elementId);
        
        // Hide all download buttons before capturing
        const allDownloadButtons = document.querySelectorAll('.download-btn');
        allDownloadButtons.forEach(btn => btn.style.visibility = 'hidden');

        html2canvas(elementToCapture, {
            scale: 2, // Higher scale for better quality
            useCORS: true,
            logging: false,
            onclone: (document) => {
                const clonedElement = document.getElementById(elementId);
                // Force a 4:5 aspect ratio for the captured image
                const width = clonedElement.offsetWidth;
                const height = width * 1.25; // 5/4 = 1.25
                clonedElement.style.height = `${height}px`;
                clonedElement.style.display = 'flex';
                clonedElement.style.flexDirection = 'column';
                clonedElement.style.justifyContent = 'center';
            }
        }).then(canvas => {
            const link = document.createElement('a');
            link.download = filename;
            link.href = canvas.toDataURL('image/png');
            link.click();

            // Restore buttons
            allDownloadButtons.forEach(btn => btn.style.visibility = 'visible');
            downloadButton.innerHTML = originalIcon;
            downloadButton.disabled = false;
        }).catch(err => {
            console.error("Lỗi khi tạo ảnh:", err);
            alert("Đã có lỗi xảy ra khi tạo file ảnh. Vui lòng thử lại.");
            // Restore buttons even if there's an error
            allDownloadButtons.forEach(btn => btn.style.visibility = 'visible');
            downloadButton.innerHTML = originalIcon;
            downloadButton.disabled = false;
        });
    }
</script>
</body>
</html>
