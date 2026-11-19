<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>ATD DESIGN | CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD - atddesign.com</title>
    <meta name="description" content="CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD (ATD DESIGN) - Chuyên thiết kế kiến trúc, thi công xây dựng trọn gói nhà phố, biệt thự, căn hộ, khách sạn, nội thất tại Đà Nẵng. Hotline: 0706.158.686.">
    <meta name="keywords" content="ATD Design, atddesign.com, thiết kế xây dựng Đà Nẵng, xây nhà trọn gói Đà Nẵng, thi công phần thô, thiết kế nội thất Đà Nẵng">

    <!-- Meta Thumbnail Open Graph & Twitter Card sử dụng trực tiếp Logo ATD khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://atddesign.com/">
    <meta property="og:site_name" content="ATD DESIGN - atddesign.com">
    <meta property="og:title" content="CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD | atddesign.com">
    <meta property="og:description" content="ATD DESIGN - Nơi kiến tạo tổ ấm mơ ước cho gia đình bạn. Thiết kế kiến trúc, thi công trọn gói nhà phố, biệt thự, căn hộ tại Đà Nẵng. Hotline: 0706.158.686.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD | atddesign.com">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói uy tín tại Đà Nẵng - 277 Nguyễn Sinh Sắc, P. Hoà Khánh, TP. Đà Nẵng.">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR">

    <!-- Favicon dùng ảnh Logo ATD -->
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR&sz=w256">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        atdPrimary: '#132A42',
                        atdDark: '#0D1E30',
                        atdAccent: '#C58B2A',
                        atdAccentHover: '#A8731E',
                        atdLight: '#F6F7F9',
                    }
                }
            }
        }
    </script>

    <!-- Font Awesome Icons cho biểu tượng giao diện Flatsome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <style>
        /* Biến màu đồng bộ theo nhận diện Logo & Kiến trúc ATD (dễ tùy chỉnh trong Flatsome Theme Options) */
        :root {
            --atd-primary: #132A42;
            --atd-primary-dark: #0D1E30;
            --atd-accent: #C58B2A;
            --atd-accent-hover: #A8731E;
            --atd-text: #222B35;
            --atd-muted: #5A6776;
            --atd-border: #E5E9EF;
        }

        /* Chuẩn hóa box-sizing và chống tràn ngang tuyệt đối trên mọi màn hình */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
        }

        body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: var(--atd-text);
            background-color: #FFFFFF;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung Container chuẩn Flatsome: 95% chiều ngang màn hình trên máy tính, cân giữa hoàn hảo */
        .atd-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 640px) {
            .atd-container {
                padding-left: 18px;
                padding-right: 18px;
            }
        }

        @media (min-width: 1024px) {
            .atd-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu Desktop: tên danh mục viết liền 1 dòng, không bẻ chữ xuống dòng giữa tên */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            row-gap: 4px;
            column-gap: 12px;
        }

        @media (min-width: 1280px) {
            .desktop-nav-list {
                column-gap: 18px;
            }
        }

        .desktop-nav-link {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            letter-spacing: 0.01em;
            color: var(--atd-primary);
            transition: color 0.2s ease;
            padding: 6px 2px;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }

        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 13px;
            }
        }

        .desktop-nav-link:hover,
        .desktop-nav-link.active {
            color: var(--atd-accent);
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown {
            position: relative;
        }

        .nav-dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            background: #FFFFFF;
            border: 1px solid var(--atd-border);
            border-top: 2px solid var(--atd-accent);
            border-radius: 0 0 8px 8px;
            box-shadow: 0 12px 28px rgba(19, 42, 66, 0.12);
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            z-index: 60;
            padding: 6px 0;
        }

        .nav-dropdown:hover .nav-dropdown-menu,
        .nav-dropdown:focus-within .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .nav-dropdown-menu a {
            display: block;
            padding: 8px 16px;
            font-size: 13px;
            color: #2B3642;
            white-space: nowrap;
            transition: background 0.15s ease, color 0.15s ease;
        }

        .nav-dropdown-menu a:hover {
            background-color: #F6F7F9;
            color: var(--atd-accent);
        }

        /* Banner Slider 2 ảnh đồng kích thước tuyệt đối, chữ nằm gọn và cách xa viền */
        .hero-slider-wrapper {
            position: relative;
            width: 100%;
            overflow: hidden;
            background-color: var(--atd-primary-dark);
        }

        .hero-slides-track {
            display: flex;
            width: 100%;
            transition: transform 0.65s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .hero-slide {
            flex: 0 0 100%;
            width: 100%;
            min-width: 100%;
            position: relative;
            /* Kích thước bằng nhau hoàn toàn giữa 2 banner trên mọi thiết bị */
            height: 360px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }

        @media (min-width: 640px) {
            .hero-slide {
                height: 430px;
            }
        }

        @media (min-width: 1024px) {
            .hero-slide {
                height: 500px;
            }
        }

        @media (min-width: 1440px) {
            .hero-slide {
                height: 540px;
            }
        }

        .hero-slide-bg {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
        }

        .hero-slide-overlay {
            position: absolute;
            inset: 0;
            background: linear-gradient(95deg, rgba(13, 30, 48, 0.84) 0%, rgba(19, 42, 66, 0.68) 55%, rgba(13, 30, 48, 0.45) 100%);
        }

        /* Vùng an toàn cho chữ trong banner: cách xa viền trái/phải/trên/dưới để không bao giờ bị cắt chữ */
        .hero-safe-box {
            position: relative;
            z-index: 10;
            width: 100%;
            max-width: 820px;
            margin: 0 auto;
            padding: 28px 44px;
            text-align: center;
        }

        @media (min-width: 640px) {
            .hero-safe-box {
                padding: 40px 72px;
            }
        }

        @media (min-width: 1024px) {
            .hero-safe-box {
                padding: 48px 88px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome có gạch chân nhỏ tinh tế */
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }

        .section-heading::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: var(--atd-accent);
            border-radius: 999px;
        }

        .section-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Tab danh mục trang chủ gọn gàng, không xuống dòng từng nút */
        .cat-tab-btn {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            padding: 7px 14px;
            border-radius: 6px;
            border: 1px solid #D9E0E8;
            background-color: #FFFFFF;
            color: var(--atd-primary);
            transition: all 0.2s ease;
            cursor: pointer;
        }

        @media (min-width: 768px) {
            .cat-tab-btn {
                font-size: 13px;
                padding: 8px 16px;
            }
        }

        .cat-tab-btn:hover {
            border-color: var(--atd-accent);
            color: var(--atd-accent);
        }

        .cat-tab-btn.active {
            background-color: var(--atd-primary);
            border-color: var(--atd-primary);
            color: #FFFFFF;
        }

        /* Card công trình sạch sẽ chuẩn Flatsome, không có nhãn dán đè ảnh */
        .project-card {
            background: #FFFFFF;
            border: 1px solid #EAECEF;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .project-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 24px rgba(19, 42, 66, 0.09);
            border-color: #D5DCE4;
        }

        .project-img-box {
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #ECEFF3;
        }

        .project-img-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
            display: block;
        }

        .project-card:hover .project-img-box img {
            transform: scale(1.05);
        }

        /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(217, 48, 37, 0.45); }
            70% { box-shadow: 0 0 0 11px rgba(217, 48, 37, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 48, 37, 0); }
        }

        .hotline-pulse {
            animation: softPulse 2s infinite;
        }

        .floating-contact-dock {
            position: fixed;
            right: 12px;
            bottom: 16px;
            z-index: 80;
            display: flex;
            flex-direction: column;
            gap: 10px;
            align-items: flex-end;
        }

        @media (min-width: 768px) {
            .floating-contact-dock {
                right: 20px;
                bottom: 24px;
                gap: 12px;
            }
        }

        .contact-pill {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            border-radius: 999px;
            color: #FFFFFF;
            font-weight: 600;
            box-shadow: 0 6px 16px rgba(0, 0, 0, 0.18);
            transition: transform 0.2s ease, opacity 0.2s ease;
            text-decoration: none;
        }

        .contact-pill:hover {
            transform: translateY(-2px) scale(1.03);
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- ===================================================================== -->
    <!-- FLATSOME TOP BAR: Thông tin liên hệ gọn nhẹ, không có thanh UXBuilder -->
    <!-- ===================================================================== -->
    <div class="w-full bg-atdPrimary text-white text-[11px] sm:text-xs py-2 border-b border-white/10">
        <div class="atd-container flex flex-wrap items-center justify-between gap-y-1 gap-x-4">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0706158686" class="inline-flex items-center gap-1.5 hover:text-atdAccent transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-phone text-atdAccent text-[11px]"></i>
                    <span class="font-semibold">0706.158.686</span>
                </a>
                <a href="mailto:thietkexaydungatd.dn@gmail.com" class="hidden sm:inline-flex items-center gap-1.5 hover:text-atdAccent transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-envelope text-atdAccent text-[11px]"></i>
                    <span>thietkexaydungatd.dn@gmail.com</span>
                </a>
                <span class="hidden lg:inline-flex items-center gap-1.5 text-white/85 whitespace-nowrap">
                    <i class="fa-solid fa-location-dot text-atdAccent text-[11px]"></i>
                    <span>277 Nguyễn Sinh Sắc, P. Hoà Khánh, TP. Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 text-white/85">
                <span class="hidden md:inline whitespace-nowrap">Website: <strong class="text-white">atddesign.com</strong></span>
                <a href="https://www.facebook.com/thietkevaxaydungatd?locale=vi_VN" target="_blank" rel="noopener noreferrer" aria-label="Facebook ATD Design" class="hover:text-atdAccent transition-colors">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="https://zalo.me/0706158686" target="_blank" rel="noopener noreferrer" aria-label="Zalo ATD Design" class="hover:text-atdAccent transition-colors font-bold text-[11px]">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- FLATSOME MAIN HEADER: Logo chỉnh gọn nhỏ + Menu 1 hàng, không nút gọi -->
    <!-- ===================================================================== -->
    <header id="mainHeader" class="sticky top-0 z-50 w-full bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="atd-container flex items-center justify-between gap-3 py-2.5 lg:py-3">
            <!-- Logo ATD chỉnh gọn nhỏ, giữ tỷ lệ sắc nét -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 focus:outline-none">
                <img
                    src="https://drive.google.com/thumbnail?id=1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR&sz=w400"
                    data-drive-id="1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR"
                    alt="Logo CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD"
                    class="h-9 sm:h-10 lg:h-11 w-auto max-w-[130px] object-contain rounded"
                    onerror="handleDriveImageError(this, '1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR', 'ATD DESIGN')"
                >
                <div class="leading-tight hidden sm:block">
                    <div class="text-sm lg:text-[15px] font-extrabold tracking-tight text-atdPrimary whitespace-nowrap">ATD DESIGN</div>
                    <div class="text-[10px] font-medium text-slate-500 uppercase tracking-wider whitespace-nowrap">Thiết Kế &amp; Xây Dựng</div>
                </div>
            </a>

            <!-- Menu Desktop chuẩn Flatsome: chữ nhỏ gọn, tên danh mục không bao giờ bị xuống dòng -->
            <nav aria-label="Menu chính" class="hidden lg:block flex-1">
                <ul class="desktop-nav-list list-none m-0 p-0">
                    <li><a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a></li>
                    <li><a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a></li>

                    <!-- Danh mục sản phẩm / Công trình thực tế (từ web mẫu Tín Trường Thịnh) -->
                    <li class="nav-dropdown">
                        <a href="#cong-trinh-thuc-te" class="desktop-nav-link">
                            <span>Công trình thực tế</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('can-ho')">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')">Văn phòng</a>
                        </div>
                    </li>

                    <!-- Lĩnh vực hoạt động -->
                    <li class="nav-dropdown">
                        <a href="#dich-vu" class="desktop-nav-link">
                            <span>Lĩnh vực hoạt động</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#dich-vu">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#dich-vu">Thi công phần thô</a>
                            <a href="#dich-vu">Thi công hoàn thiện</a>
                            <a href="#dich-vu">Thi công nội thất</a>
                        </div>
                    </li>

                    <li><a href="#du-an-da-nang" class="desktop-nav-link">Dự án Đà Nẵng</a></li>

                    <!-- Mẫu thiết kế -->
                    <li class="nav-dropdown">
                        <a href="#du-an-da-nang" class="desktop-nav-link">
                            <span>Mẫu thiết kế</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#du-an-da-nang" onclick="filterDaNang('nha-pho')">Mẫu thiết kế nhà phố</a>
                            <a href="#du-an-da-nang" onclick="filterDaNang('biet-thu')">Mẫu thiết kế biệt thự</a>
                            <a href="#du-an-da-nang" onclick="filterDaNang('noi-that')">Mẫu thiết kế nội thất</a>
                        </div>
                    </li>

                    <!-- Báo giá -->
                    <li class="nav-dropdown">
                        <a href="#bao-gia" class="desktop-nav-link">
                            <span>Báo giá</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia">Báo giá thi công phần thô</a>
                            <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia">Báo giá thi công trọn gói</a>
                        </div>
                    </li>

                    <li><a href="#tin-tuc" class="desktop-nav-link">Tin tức</a></li>
                    <li><a href="#lien-he" class="desktop-nav-link">Liên hệ</a></li>
                </ul>
            </nav>

            <!-- Nút Mở Menu trên Điện thoại / Tablet -->
            <button
                id="mobileMenuBtn"
                type="button"
                aria-label="Mở menu điều hướng"
                aria-expanded="false"
                class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-atdPrimary hover:bg-slate-50 transition-colors shrink-0"
            >
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Mobile Off-canvas Drawer Menu chuẩn Flatsome -->
        <div id="mobileMenuPanel" class="hidden lg:hidden border-t border-slate-200 bg-white shadow-lg">
            <div class="atd-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-medium text-atdPrimary">
                <a href="#trang-chu" class="py-2.5 hover:text-atdAccent mobile-nav-link">Trang chủ</a>
                <a href="#gioi-thieu" class="py-2.5 hover:text-atdAccent mobile-nav-link">Giới thiệu</a>

                <div class="py-2">
                    <button type="button" onclick="toggleSubMenu('mobSub1')" class="w-full flex items-center justify-between py-1 hover:text-atdAccent">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-xs text-slate-400"></i>
                    </button>
                    <div id="mobSub1" class="hidden pl-4 pt-1.5 flex flex-col gap-2 text-xs text-slate-600">
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('can-ho')" class="py-1 mobile-nav-link">Khách sạn – Căn hộ – Phòng trọ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="py-1 mobile-nav-link">Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="py-1 mobile-nav-link">Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="py-1 mobile-nav-link">Văn phòng</a>
                    </div>
                </div>

                <div class="py-2">
                    <button type="button" onclick="toggleSubMenu('mobSub2')" class="w-full flex items-center justify-between py-1 hover:text-atdAccent">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-xs text-slate-400"></i>
                    </button>
                    <div id="mobSub2" class="hidden pl-4 pt-1.5 flex flex-col gap-2 text-xs text-slate-600">
                        <a href="#dich-vu" class="py-1 mobile-nav-link">Thiết kế Kiến trúc – Nội thất</a>
                        <a href="#dich-vu" class="py-1 mobile-nav-link">Thi công phần thô</a>
                        <a href="#dich-vu" class="py-1 mobile-nav-link">Thi công hoàn thiện</a>
                        <a href="#dich-vu" class="py-1 mobile-nav-link">Thi công nội thất</a>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="py-2.5 hover:text-atdAccent mobile-nav-link">Dự án Đà Nẵng</a>
                <a href="#bao-gia" class="py-2.5 hover:text-atdAccent mobile-nav-link">Báo giá &amp; Tư vấn</a>
                <a href="#tin-tuc" class="py-2.5 hover:text-atdAccent mobile-nav-link">Tin tức</a>
                <a href="#doi-tac" class="py-2.5 hover:text-atdAccent mobile-nav-link">Đối tác</a>
                <a href="#lien-he" class="py-2.5 hover:text-atdAccent mobile-nav-link">Liên hệ</a>
            </div>
        </div>
    </header>

    <!-- ===================================================================== -->
    <!-- FLATSOME UX SLIDER: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU        -->
    <!-- Hình ảnh và chữ nằm trọn trong khung an toàn, cách xa viền banner     -->
    <!-- ===================================================================== -->
    <section id="trang-chu" class="w-full overflow-hidden">
        <div id="heroSlider" class="hero-slider-wrapper">
            <div id="heroSlidesTrack" class="hero-slides-track">

                <!-- BANNER 1 -->
                <div class="hero-slide">
                    <img
                        src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                        alt="ATD Design - Thiết kế kiến trúc và thi công xây dựng trọn gói tại Đà Nẵng"
                        class="hero-slide-bg"
                        onerror="handleDriveImageError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'ATD DESIGN - THIẾT KẾ &amp; XÂY DỰNG')"
                    >
                    <div class="hero-slide-overlay"></div>
                    <div class="hero-safe-box">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-amber-300 mb-2 sm:mb-3">
                            ATD DESIGN • XÂY UY TÍN, DỰNG NIỀM TIN
                        </p>
                        <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                            THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                        </h1>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto mb-5 sm:mb-6">
                            Chuyên Nhà phố, Biệt thự Modern Luxury, Căn hộ dịch vụ và Văn phòng. Cam kết chuẩn kỹ thuật, đúng tiến độ và tối ưu ngân sách cho chủ đầu tư.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-2.5 sm:gap-3">
                            <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-atdAccent hover:bg-atdAccentHover text-white text-xs sm:text-sm font-semibold transition-colors shadow-md">
                                Nhận báo giá miễn phí
                            </a>
                            <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 text-xs sm:text-sm font-semibold transition-colors backdrop-blur-sm">
                                Xem công trình thực tế
                            </a>
                        </div>
                    </div>
                </div>

                <!-- BANNER 2 (Đồng bộ cấu trúc & kích thước 100% với Banner 1) -->
                <div class="hero-slide">
                    <img
                        src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1600"
                        alt="ATD Design - Kiến tạo không gian sống đẳng cấp và bền vững"
                        class="hero-slide-bg"
                        onerror="handleDriveImageError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'ATD DESIGN - KHÔNG GIAN SỐNG')"
                    >
                    <div class="hero-slide-overlay"></div>
                    <div class="hero-safe-box">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-amber-300 mb-2 sm:mb-3">
                            CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD
                        </p>
                        <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                            NƠI KIẾN TẠO TỔ ẤM MƠ ƯỚC CHO GIA ĐÌNH BẠN
                        </h2>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto mb-5 sm:mb-6">
                            Chỉn chu từ bản vẽ kiến trúc, thi công phần thô vững chắc đến hoàn thiện nội thất tinh tế. Đồng hành bền vững cùng công trình của bạn theo thời gian.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-2.5 sm:gap-3">
                            <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-atdAccent hover:bg-atdAccentHover text-white text-xs sm:text-sm font-semibold transition-colors shadow-md">
                                Khám phá dự án Đà Nẵng
                            </a>
                            <a href="tel:0706158686" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 text-xs sm:text-sm font-semibold transition-colors backdrop-blur-sm">
                                Tư vấn: 0706.158.686
                            </a>
                        </div>
                    </div>
                </div>

            </div>

            <!-- Nút điều hướng Slider trái / phải -->
            <button
                type="button"
                id="prevSlideBtn"
                aria-label="Banner trước"
                class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-atdAccent text-white flex items-center justify-center transition-colors"
            >
                <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
            </button>
            <button
                type="button"
                id="nextSlideBtn"
                aria-label="Banner tiếp theo"
                class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-atdAccent text-white flex items-center justify-center transition-colors"
            >
                <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
            </button>

            <!-- Chấm chỉ báo 2 banner -->
            <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                <button type="button" onclick="goToSlide(0)" id="dot0" aria-label="Chuyển tới banner 1" class="w-7 h-2 rounded-full bg-atdAccent transition-all"></button>
                <button type="button" onclick="goToSlide(1)" id="dot1" aria-label="Chuyển tới banner 2" class="w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: DỊCH VỤ TIÊU BIỂU (Cấu trúc 4 cột giống web mẫu)    -->
    <!-- ===================================================================== -->
    <section id="dich-vu" class="w-full py-10 sm:py-14 bg-white">
        <div class="atd-container">
            <div class="text-center mb-8 sm:mb-10">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold uppercase text-atdPrimary">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Giải pháp toàn diện từ ý tưởng thiết kế kiến trúc, thi công kết cấu phần thô đến hoàn thiện nội thất chìa khóa trao tay.
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dịch vụ 1 -->
                <div class="bg-atdLight border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center hover:border-atdAccent hover:shadow-md transition-all">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-atdPrimary text-atdAccent flex items-center justify-center text-xl sm:text-2xl">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="text-xs sm:text-base font-bold text-atdPrimary mb-1.5 sm:mb-2 uppercase">Thiết Kế Kiến Trúc</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Thiết kế nhà phố, biệt thự Modern Luxury, căn hộ dịch vụ và khách sạn tối ưu công năng, đón sáng tự nhiên.
                    </p>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-atdLight border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center hover:border-atdAccent hover:shadow-md transition-all">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-atdPrimary text-atdAccent flex items-center justify-center text-xl sm:text-2xl">
                        <i class="fa-solid fa-trowel-bricks"></i>
                    </div>
                    <h3 class="text-xs sm:text-base font-bold text-atdPrimary mb-1.5 sm:mb-2 uppercase">Thi Công Phần Thô</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Quy trình thi công móng, coppha, cốt thép, bê tông dầm sàn nghiêm ngặt theo hồ sơ kỹ thuật và kiểm soát chặt chẽ.
                    </p>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-atdLight border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center hover:border-atdAccent hover:shadow-md transition-all">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-atdPrimary text-atdAccent flex items-center justify-center text-xl sm:text-2xl">
                        <i class="fa-solid fa-house-chimney-crack"></i>
                    </div>
                    <h3 class="text-xs sm:text-base font-bold text-atdPrimary mb-1.5 sm:mb-2 uppercase">Thi Công Trọn Gói</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Xây nhà trọn gói &amp; cải tạo công trình minh bạch vật tư, cam kết tiến độ thi công và bảo hành dài hạn.
                    </p>
                </div>

                <!-- Dịch vụ 4 -->
                <div class="bg-atdLight border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center hover:border-atdAccent hover:shadow-md transition-all">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-atdPrimary text-atdAccent flex items-center justify-center text-xl sm:text-2xl">
                        <i class="fa-solid fa-couch"></i>
                    </div>
                    <h3 class="text-xs sm:text-base font-bold text-atdPrimary mb-1.5 sm:mb-2 uppercase">Thi Công Nội Thất</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Sản xuất và lắp đặt nội thất gỗ tinh tế, không gian tối giản ấm áp, đồng điệu giữa kiến trúc và trải nghiệm sống.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI         -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="w-full py-10 sm:py-14 bg-atdLight border-y border-slate-200/70">
        <div class="atd-container">
            <!-- Hàng 1: Giới thiệu ATD Design -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10 sm:mb-14">
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
                        <img
                            src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1000"
                            alt="CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD tại Đà Nẵng"
                            class="w-full aspect-[4/3] object-cover block"
                            onerror="handleDriveImageError(this, '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz', 'ATD DESIGN ĐÀ NẴNG')"
                        >
                    </div>
                </div>
                <div class="lg:col-span-7">
                    <p class="text-xs font-bold uppercase tracking-widest text-atdAccent mb-2">Về Chúng Tôi</p>
                    <h2 class="section-heading section-heading-left text-lg sm:text-2xl font-extrabold text-atdPrimary mb-4">
                        CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>ATD DESIGN</strong> là đơn vị chuyên nghiệp trong lĩnh vực <strong>Thiết kế kiến trúc – Thi công xây dựng trọn gói – Cải tạo &amp; Hoàn thiện nội thất</strong> các công trình Nhà phố, Biệt thự, Căn hộ dịch vụ, Khách sạn và Văn phòng tại khu vực Đà Nẵng – Quảng Nam.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-5">
                        Với phương châm <strong>“Xây Uy Tín – Dựng Niềm Tin”</strong>, đội ngũ kiến trúc sư và kỹ sư giám sát của ATD DESIGN luôn đặt sự chỉn chu vào từng công đoạn thi công thực tế, từ kết cấu móng, dầm sàn cho đến từng chi tiết hoàn thiện thẩm mỹ, hướng đến những công trình bền vững theo thời gian.
                    </p>
                    <div class="grid grid-cols-3 gap-3 sm:gap-4">
                        <div class="bg-white rounded-lg p-3 sm:p-4 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-atdAccent">100%</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Chuẩn hồ sơ kỹ thuật</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 sm:p-4 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-atdAccent">24/7</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Hỗ trợ &amp; Báo cáo tiến độ</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 sm:p-4 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-atdAccent">5+ Năm</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Hàng 2: 6 Thế mạnh của chúng tôi (chuẩn cấu trúc Tín Trường Thịnh) -->
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold uppercase text-atdPrimary">
                    Thế Mạnh Của Chúng Tôi
                </h2>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-atdPrimary/10 text-atdPrimary flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-helmet-safety text-atdAccent"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-bold text-atdPrimary mb-1">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giám sát công trường giàu kinh nghiệm và thợ thi công lành nghề.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-atdPrimary/10 text-atdPrimary flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-layer-group text-atdAccent"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-bold text-atdPrimary mb-1">Cập nhật xu hướng kiến trúc hiện đại</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">Mang đến những không gian sống hài hòa thiên nhiên, phong cách Modern Luxury và giải pháp vật liệu mới tối ưu.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-atdPrimary/10 text-atdPrimary flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-clipboard-check text-atdAccent"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-bold text-atdPrimary mb-1">Giám sát tiến độ chuẩn xác</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">Báo cáo nhật ký công trình hằng ngày bằng hình ảnh thực tế giúp chủ đầu tư dễ dàng theo dõi ở bất cứ đâu.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-atdPrimary/10 text-atdPrimary flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-shield-halved text-atdAccent"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-bold text-atdPrimary mb-1">Bảo hành công trình lâu dài</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi rõ ràng, hỗ trợ nhanh chóng sau bàn giao để gia chủ hoàn toàn an tâm khi đưa vào sử dụng.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-atdPrimary/10 text-atdPrimary flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-file-invoice-dollar text-atdAccent"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-bold text-atdPrimary mb-1">Chi phí minh bạch, hợp lý</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">Dự toán bóc tách khối lượng chi tiết từng hạng mục, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-atdPrimary/10 text-atdPrimary flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-headset text-atdAccent"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-bold text-atdPrimary mb-1">Hỗ trợ tư vấn miễn phí 24/7</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">Đội ngũ ATD DESIGN luôn sẵn sàng khảo sát thực tế, tư vấn phương án thiết kế và báo giá phù hợp ngân sách.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: CÔNG TRÌNH THỰC TẾ (9 ẢNH THI CÔNG TỪ GOOGLE DRIVE) -->
    <!-- Danh mục sản phẩm lấy chuẩn từ web mẫu tintruongthinh.com             -->
    <!-- Chia 2 cột trên điện thoại, tên đầy đủ không tràn, không nhãn dán     -->
    <!-- ===================================================================== -->
    <section id="cong-trinh-thuc-te" class="w-full py-10 sm:py-14 bg-white">
        <div class="atd-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold uppercase text-atdPrimary">
                    Công Trình Thi Công Thực Tế
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Hình ảnh nhật ký thi công thực tế tại công trường do đội ngũ kỹ sư ATD DESIGN trực tiếp triển khai và giám sát.
                </p>
            </div>

            <!-- Thanh danh mục lọc gọn gàng, tối ưu đẹp trên máy tính và điện thoại -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8" id="constructionTabs">
                <button type="button" onclick="filterConstruction('all')" data-cat="all" class="cat-tab-btn active">Tất cả</button>
                <button type="button" onclick="filterConstruction('can-ho')" data-cat="can-ho" class="cat-tab-btn">Khách sạn - Căn hộ - Phòng trọ</button>
                <button type="button" onclick="filterConstruction('biet-thu')" data-cat="biet-thu" class="cat-tab-btn">Biệt thự</button>
                <button type="button" onclick="filterConstruction('nha-pho')" data-cat="nha-pho" class="cat-tab-btn">Nhà phố</button>
                <button type="button" onclick="filterConstruction('van-phong')" data-cat="van-phong" class="cat-tab-btn">Văn phòng</button>
            </div>

            <!-- Lưới sản phẩm / công trình: 2 cột trên điện thoại, 3 cột tablet, 3-4 cột máy tính -->
            <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dữ liệu được render tự động từ mảng 9 ảnh thực tế Google Drive -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DỰ ÁN TỪ GOOGLE DRIVE)  -->
    <!-- Chia 2 cột trên điện thoại, không nhãn dán, chữ rõ ràng không bị cắt  -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="w-full py-10 sm:py-14 bg-atdLight border-y border-slate-200/70">
        <div class="atd-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold uppercase text-atdPrimary">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Tuyển chọn các dự án thiết kế kiến trúc, thi công trọn gói và hoàn thiện nội thất do ATD DESIGN thực hiện tại TP. Đà Nẵng.
                </p>
            </div>

            <!-- Thanh danh mục dự án Đà Nẵng gọn gàng -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8" id="danangTabs">
                <button type="button" onclick="filterDaNang('all')" data-cat="all" class="cat-tab-btn active">Tất cả dự án</button>
                <button type="button" onclick="filterDaNang('nha-pho')" data-cat="nha-pho" class="cat-tab-btn">Nhà phố Đà Nẵng</button>
                <button type="button" onclick="filterDaNang('biet-thu')" data-cat="biet-thu" class="cat-tab-btn">Biệt thự &amp; Villa</button>
                <button type="button" onclick="filterDaNang('can-ho')" data-cat="can-ho" class="cat-tab-btn">Căn hộ dịch vụ</button>
                <button type="button" onclick="filterDaNang('noi-that')" data-cat="noi-that" class="cat-tab-btn">Nội thất hoàn thiện</button>
            </div>

            <!-- Lưới 10 dự án Đà Nẵng: 2 cột điện thoại, 3 cột tablet, 5 cột trên màn hình lớn hoặc 4 cột cân đối -->
            <div id="danangGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-5">
                <!-- Dữ liệu được render tự động từ mảng 10 ảnh dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (Giống Tín Trường Thịnh) -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="w-full py-10 sm:py-14 bg-atdPrimary text-white">
        <div class="atd-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Cột thông tin bảng báo giá tham khảo -->
                <div class="lg:col-span-5">
                    <p class="text-xs font-bold uppercase tracking-widest text-atdAccent mb-2">Miễn Phí Tư Vấn &amp; Khảo Sát</p>
                    <h2 class="section-heading section-heading-left text-lg sm:text-2xl font-extrabold text-white mb-4">
                        ĐĂNG KÝ YÊU CẦU BÁO GIÁ XÂY DỰNG
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-300 leading-relaxed mb-5">
                        Để lại thông tin công trình dự kiến của bạn, kiến trúc sư và kỹ sư dự toán của <strong>ATD DESIGN</strong> sẽ liên hệ tư vấn giải pháp tối ưu và gửi bảng báo giá chi tiết trong vòng 24 giờ.
                    </p>

                    <div class="space-y-3 text-xs sm:text-sm">
                        <div class="flex items-center justify-between py-2.5 px-4 rounded-lg bg-white/10 border border-white/15">
                            <span class="font-medium text-slate-200">Thiết kế kiến trúc – Nội thất</span>
                            <span class="font-bold text-amber-300 whitespace-nowrap">Liên hệ báo giá</span>
                        </div>
                        <div class="flex items-center justify-between py-2.5 px-4 rounded-lg bg-white/10 border border-white/15">
                            <span class="font-medium text-slate-200">Thi công phần thô &amp; nhân công</span>
                            <span class="font-bold text-amber-300 whitespace-nowrap">Từ 3.600.000đ/m²</span>
                        </div>
                        <div class="flex items-center justify-between py-2.5 px-4 rounded-lg bg-white/10 border border-white/15">
                            <span class="font-medium text-slate-200">Thi công trọn gói chìa khóa trao tay</span>
                            <span class="font-bold text-amber-300 whitespace-nowrap">Từ 5.800.000đ/m²</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Form gửi yêu cầu -->
                <div class="lg:col-span-7">
                    <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-atdPrimary mb-1.5">Họ và tên <span class="text-red-500">*</span></label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-atdAccent focus:ring-2 focus:ring-atdAccent/20 outline-none">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-semibold text-atdPrimary mb-1.5">Số điện thoại <span class="text-red-500">*</span></label>
                                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0706 158 686" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-atdAccent focus:ring-2 focus:ring-atdAccent/20 outline-none">
                            </div>
                            <div>
                                <label for="qEmail" class="block text-xs font-semibold text-atdPrimary mb-1.5">Email</label>
                                <input id="qEmail" type="email" placeholder="email@domain.com" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-atdAccent focus:ring-2 focus:ring-atdAccent/20 outline-none">
                            </div>
                            <div>
                                <label for="qType" class="block text-xs font-semibold text-atdPrimary mb-1.5">Loại công trình</label>
                                <select id="qType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-atdAccent focus:ring-2 focus:ring-atdAccent/20 outline-none">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    <option value="Thiết kế &amp; Thi công nội thất">Thiết kế &amp; Thi công nội thất</option>
                                </select>
                            </div>
                            <div>
                                <label for="qBudget" class="block text-xs font-semibold text-atdPrimary mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-atdAccent focus:ring-2 focus:ring-atdAccent/20 outline-none">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ - 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div>
                                <label for="qArea" class="block text-xs font-semibold text-atdPrimary mb-1.5">Khu vực xây dựng</label>
                                <input id="qArea" type="text" placeholder="VD: Hòa Khánh, Hải Châu, Hòa Xuân..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-atdAccent focus:ring-2 focus:ring-atdAccent/20 outline-none">
                            </div>
                            <div class="sm:col-span-2">
                                <label for="qNote" class="block text-xs font-semibold text-atdPrimary mb-1.5">Nội dung yêu cầu chi tiết</label>
                                <textarea id="qNote" rows="3" placeholder="Mô tả diện tích đất, số tầng mong muốn hoặc hạng mục cần báo giá..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-atdAccent focus:ring-2 focus:ring-atdAccent/20 outline-none resize-none"></textarea>
                            </div>
                        </div>

                        <!-- Thông báo trạng thái gửi form (không dùng alert()) -->
                        <div id="quoteFeedback" class="hidden mt-4 p-3.5 rounded-lg text-xs sm:text-sm font-medium"></div>

                        <div class="mt-5 flex flex-col sm:flex-row items-center justify-between gap-3">
                            <p class="text-[11px] text-slate-500">
                                Hoặc liên hệ trực tiếp Hotline/Zalo: <a href="tel:0706158686" class="font-bold text-atdPrimary">0706.158.686</a>
                            </p>
                            <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-atdAccent hover:bg-atdAccentHover text-white text-sm font-bold transition-colors shadow-md">
                                Gửi yêu cầu báo giá
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ           -->
    <!-- ===================================================================== -->
    <section id="tin-tuc" class="w-full py-10 sm:py-14 bg-white">
        <div class="atd-container">
            <div class="text-center mb-8 sm:mb-10">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold uppercase text-atdPrimary">
                    Tin Tức &amp; Cẩm Nang Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Cập nhật kiến thức thi công, xu hướng thiết kế kiến trúc – nội thất và nhật ký công trình mới nhất từ ATD DESIGN.
                </p>
            </div>

            <div id="blogGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Danh sách bài viết được render từ dữ liệu nội dung Fanpage ATD & Cẩm nang -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: DANH MỤC CÁC ĐỐI TÁC                                -->
    <!-- ===================================================================== -->
    <section id="doi-tac" class="w-full py-10 sm:py-12 bg-atdLight border-y border-slate-200/70">
        <div class="atd-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold uppercase text-atdPrimary">
                    Đối Tác Đồng Hành
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    ATD DESIGN hợp tác cùng các thương hiệu vật liệu xây dựng và thiết bị nội thất uy tín hàng đầu nhằm đảm bảo chất lượng bền vững cho mọi công trình.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-3 sm:gap-4">
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#00529B]">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#C4161C]">VIỆT NHẬT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Vina Kyoei Steel</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#006838]">SÔNG GIANH</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Xi măng cao cấp</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#1D3C85]">DULUX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn kiến trúc</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#003366]">JOTUN</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#8B1A1A]">AN CƯỜNG</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gỗ công nghiệp nội thất</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#0072BC]">TIỀN PHONG</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Hệ thống cấp thoát nước</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#D71920]">CADIVI</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Dây cáp điện dân dụng</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#003B73]">TOTO</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg px-4 py-4 flex flex-col items-center justify-center text-center hover:border-atdAccent transition-colors">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#132A42]">ĐỒNG TÂM</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch ốp lát cao cấp</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION: GOOGLE MAPS & FANPAGE FACEBOOK NGAY TRANG CHỦ       -->
    <!-- ===================================================================== -->
    <section id="lien-he" class="w-full py-10 sm:py-14 bg-white">
        <div class="atd-container">
            <div class="text-center mb-8 sm:mb-10">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold uppercase text-atdPrimary">
                    Kết Nối &amp; Bản Đồ Chỉ Đường
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Ghé thăm văn phòng ATD DESIGN tại 277 Nguyễn Sinh Sắc, P. Hoà Khánh, TP. Đà Nẵng hoặc theo dõi Fanpage chính thức để cập nhật công trình mỗi ngày.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột Google Map (chiếm 7 cột trên desktop) -->
                <div class="lg:col-span-7 flex flex-col bg-atdLight border border-slate-200 rounded-xl overflow-hidden">
                    <div class="px-4 py-3 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-atdPrimary">
                            <i class="fa-solid fa-map-location-dot text-atdAccent"></i>
                            <span>Bản đồ văn phòng ATD DESIGN Đà Nẵng</span>
                        </div>
                        <a
                            href="https://www.google.com/maps/search/?api=1&query=277+Nguy%E1%BB%85n+Sinh+S%E1%BA%AFc,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="text-xs font-semibold text-atdAccent hover:underline"
                        >
                            Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px] ml-0.5"></i>
                        </a>
                    </div>
                    <div class="w-full flex-1 min-h-[320px] sm:min-h-[380px] relative">
                        <iframe
                            title="Bản đồ 277 Nguyễn Sinh Sắc, P. Hoà Khánh, TP. Đà Nẵng"
                            src="https://maps.google.com/maps?q=277%20Nguy%E1%BB%85n%20Sinh%20S%E1%BA%AFc,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[320px] sm:min-h-[380px] border-0 block"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen
                        ></iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook ATD DESIGN (chiếm 5 cột trên desktop) -->
                <div class="lg:col-span-5 flex flex-col bg-atdLight border border-slate-200 rounded-xl overflow-hidden">
                    <div class="px-4 py-3 bg-white border-b border-slate-200 flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-atdPrimary">
                            <i class="fa-brands fa-facebook text-[#1877F2]"></i>
                            <span>Fanpage Thiết Kế &amp; Xây Dựng ATD</span>
                        </div>
                        <a
                            href="https://www.facebook.com/thietkevaxaydungatd?locale=vi_VN"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="text-xs font-semibold text-[#1877F2] hover:underline"
                        >
                            Xem trang <i class="fa-solid fa-arrow-up-right-from-square text-[10px] ml-0.5"></i>
                        </a>
                    </div>

                    <!-- Thẻ tóm tắt Fanpage luôn hiển thị đẹp kể cả khi trình duyệt chặn iframe bên thứ 3 -->
                    <div class="p-4 bg-white border-b border-slate-100 flex items-center gap-3">
                        <img
                            src="https://drive.google.com/thumbnail?id=1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR&sz=w200"
                            alt="Avatar Fanpage Thiết Kế & Xây Dựng ATD"
                            class="w-12 h-12 rounded-full object-contain border border-slate-200 bg-white p-1 shrink-0"
                            onerror="handleDriveImageError(this, '1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR', 'ATD')"
                        >
                        <div class="min-w-0 flex-1">
                            <a href="https://www.facebook.com/thietkevaxaydungatd?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="text-sm font-bold text-atdPrimary hover:text-[#1877F2] block truncate">
                                Thiết Kế &amp; Xây Dựng ATD
                            </a>
                            <p class="text-[11px] text-slate-500">ATD DESIGN - Nơi kiến tạo tổ ấm mơ ước</p>
                        </div>
                        <a
                            href="https://www.facebook.com/thietkevaxaydungatd?locale=vi_VN"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="px-3 py-1.5 rounded-md bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold shrink-0 transition-colors"
                        >
                            Theo dõi
                        </a>
                    </div>

                    <!-- Nhúng Facebook Page Plugin chính thức -->
                    <div class="w-full flex-1 flex justify-center bg-white p-2 overflow-hidden">
                        <iframe
                            title="Fanpage Facebook Thiết Kế & Xây Dựng ATD"
                            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fthietkevaxaydungatd&tabs=timeline&width=440&height=300&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                            class="w-full max-w-[440px] h-[300px] border-0 overflow-hidden"
                            scrolling="no"
                            frameborder="0"
                            allowfullscreen="true"
                            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                        ></iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME FOOTER: Thông tin công ty & Danh mục chuẩn Flatsome          -->
    <!-- ===================================================================== -->
    <footer class="w-full bg-atdDark text-slate-300 pt-10 pb-6 border-t-4 border-atdAccent">
        <div class="atd-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-2">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="bg-white rounded-lg p-1.5 shrink-0">
                            <img
                                src="https://drive.google.com/thumbnail?id=1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR&sz=w300"
                                alt="Logo ATD DESIGN"
                                class="h-9 w-auto object-contain"
                                onerror="handleDriveImageError(this, '1yVV_IiGCz06R_uNxJ7fC4b92XTLZPNbR', 'ATD')"
                            >
                        </div>
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-white">CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD</h3>
                            <p class="text-[11px] text-amber-300 font-medium">ATD DESIGN • Xây Uy Tín – Dựng Niềm Tin</p>
                        </div>
                    </div>
                    <ul class="space-y-2.5 text-xs sm:text-sm list-none p-0 m-0">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-atdAccent mt-1 shrink-0"></i>
                            <span>Địa chỉ: 277 Nguyễn Sinh Sắc, P. Hoà Khánh, TP. Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-atdAccent shrink-0"></i>
                            <span>Hotline / Zalo: <a href="tel:0706158686" class="text-white font-semibold hover:text-atdAccent">0706.158.686</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-envelope text-atdAccent shrink-0"></i>
                            <span>Email: <a href="mailto:thietkexaydungatd.dn@gmail.com" class="hover:text-atdAccent">thietkexaydungatd.dn@gmail.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-atdAccent shrink-0"></i>
                            <span>Website: <strong class="text-white">atddesign.com</strong></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-building text-atdAccent shrink-0"></i>
                            <span>Mã số thuế: 0317744872-001</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div>
                    <h4 class="text-sm font-bold uppercase text-white mb-4 pb-2 border-b border-white/15">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs sm:text-sm list-none p-0 m-0">
                        <li><a href="#dich-vu" class="hover:text-atdAccent transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#dich-vu" class="hover:text-atdAccent transition-colors">Thi công phần thô</a></li>
                        <li><a href="#dich-vu" class="hover:text-atdAccent transition-colors">Thi công hoàn thiện</a></li>
                        <li><a href="#dich-vu" class="hover:text-atdAccent transition-colors">Thi công nội thất trọn gói</a></li>
                        <li><a href="#bao-gia" class="hover:text-atdAccent transition-colors">Cải tạo &amp; Sửa chữa công trình</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình & Giờ làm việc -->
                <div>
                    <h4 class="text-sm font-bold uppercase text-white mb-4 pb-2 border-b border-white/15">Danh Mục Công Trình</h4>
                    <ul class="space-y-2 text-xs sm:text-sm list-none p-0 m-0 mb-5">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('can-ho')" class="hover:text-atdAccent transition-colors">Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="hover:text-atdAccent transition-colors">Biệt thự &amp; Villa</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="hover:text-atdAccent transition-colors">Nhà phố hiện đại</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="hover:text-atdAccent transition-colors">Văn phòng làm việc</a></li>
                    </ul>
                    <div class="text-xs text-slate-400 leading-relaxed">
                        <strong class="text-white block mb-1">Giờ làm việc:</strong>
                        Thứ 2 – Thứ 7: 07h30 – 11h30 | 13h00 – 17h00
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <p>Copyright 2026 © CÔNG TY TNHH TMDV THIẾT KẾ XÂY DỰNG ATD. All rights reserved.</p>
                <p>Thiết kế chuẩn giao diện Flatsome • <span class="text-white font-medium">atddesign.com</span></p>
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (Tương thích PC & Mobile)-->
    <!-- ===================================================================== -->
    <div class="floating-contact-dock" aria-label="Liên hệ nhanh">
        <!-- Nút Facebook Messenger / Fanpage -->
        <a
            href="https://www.facebook.com/thietkevaxaydungatd?locale=vi_VN"
            target="_blank"
            rel="noopener noreferrer"
            class="contact-pill bg-[#1877F2] w-11 h-11 md:w-auto md:px-4 md:py-2.5 text-xs sm:text-sm"
            title="Fanpage Facebook ATD Design"
        >
            <i class="fa-brands fa-facebook-f text-base"></i>
            <span class="hidden md:inline">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a
            href="https://zalo.me/0706158686"
            target="_blank"
            rel="noopener noreferrer"
            class="contact-pill bg-[#0068FF] w-11 h-11 md:w-auto md:px-4 md:py-2.5 text-xs sm:text-sm"
            title="Chat Zalo 0706.158.686"
        >
            <span class="font-extrabold text-xs tracking-tight border border-white/80 rounded px-1 leading-tight">Zalo</span>
            <span class="hidden md:inline">Chat Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a
            href="tel:0706158686"
            class="contact-pill bg-[#D93025] hotline-pulse w-11 h-11 md:w-auto md:px-4 md:py-2.5 text-xs sm:text-sm"
            title="Gọi Hotline 0706.158.686"
        >
            <i class="fa-solid fa-phone-volume text-base"></i>
            <span class="hidden md:inline">0706.158.686</span>
        </a>
    </div>

    <!-- ===================================================================== -->
    <!-- MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH / BÀI VIẾT (Thay cho chuyển trang)  -->
    <!-- ===================================================================== -->
    <div id="detailModal" class="fixed inset-0 z-[100] hidden items-center justify-center bg-black/75 p-3 sm:p-6">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button
                type="button"
                onclick="closeModal()"
                aria-label="Đóng cửa sổ"
                class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-black/60 hover:bg-atdAccent text-white flex items-center justify-center transition-colors"
            >
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modalImageWrap" class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                <img id="modalImg" src="" alt="" class="w-full h-full object-cover">
            </div>
            <div class="p-5 sm:p-6">
                <div id="modalMeta" class="text-xs font-semibold text-atdAccent uppercase tracking-wider mb-1.5"></div>
                <h3 id="modalTitle" class="text-base sm:text-xl font-extrabold text-atdPrimary mb-3 leading-snug"></h3>
                <p id="modalDesc" class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-5"></p>
                <div class="flex flex-wrap items-center justify-between gap-3 pt-4 border-t border-slate-200">
                    <span class="text-xs text-slate-500">Đơn vị thực hiện: <strong class="text-atdPrimary">ATD DESIGN</strong></span>
                    <a href="#bao-gia" onclick="closeModal()" class="px-4 py-2 rounded-lg bg-atdPrimary hover:bg-atdAccent text-white text-xs font-semibold transition-colors">
                        Yêu cầu tư vấn công trình tương tự
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC & TƯƠNG TÁC      -->
    <!-- ===================================================================== -->
    <script>
        /**
         * Hàm tạo URL ảnh từ Google Drive ID để hiển thị trực tiếp sắc nét
         */
        function getDriveThumb(id, size = 'w1000') {
            return `https://drive.google.com/thumbnail?id=${id}&sz=${size}`;
        }

        /**
         * Cơ chế dự phòng đa tầng khi tải ảnh từ Google Drive:
         * Lần 1 lỗi -> chuyển sang endpoint lh3.googleusercontent.com
         * Lần 2 lỗi -> hiển thị ảnh placeholder sạch theo tên công trình
         */
        function handleDriveImageError(imgEl, driveId, labelText) {
            const step = imgEl.getAttribute('data-fallback-step') || '0';
            if (step === '0' && driveId) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = `https://lh3.googleusercontent.com/d/${driveId}=w1000`;
            } else {
                imgEl.onerror = null;
                const safeText = encodeURIComponent(labelText || 'ATD DESIGN');
                imgEl.src = `https://placehold.co/800x600/132A42/FFFFFF?text=${safeText}`;
            }
        }

        /**
         * 1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE
         * Phân loại theo đúng danh mục sản phẩm mẫu tintruongthinh.com
         */
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi công bê tông dầm sàn tầng 2 – Công trình Nguyễn Đôn Tiết, Hải Châu',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Công tác lắp dựng coppha, kiểm tra cốt thép và đổ bê tông dầm sàn tầng 2 hạng mục cải tạo nhà phố Nguyễn Đôn Tiết do đội ngũ kỹ sư ATD DESIGN trực tiếp giám sát.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi công coppha kết cấu sàn tầng 1 – Dự án Mermaid House',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Lắp dựng hệ coppha, căn chỉnh cao độ và độ ổn định hệ chống đỡ sàn tầng 1 tại công trình Mermaid House, đảm bảo độ chính xác tuyệt đối theo hồ sơ kỹ thuật.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Nhật ký thi công đổ bê tông móng – Công trình Hồ Xuân Hương',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Đường Hồ Xuân Hương, Đà Nẵng',
                desc: 'Hoàn thành hạng mục đổ bê tông móng chắc chắn, tuân thủ nghiêm ngặt quy trình kỹ thuật kết cấu nền móng cho ngôi nhà bền vững theo thời gian.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi công phần thô khung cột & tường bao – Olive Apartment',
                category: 'can-ho',
                categoryLabel: 'Khách sạn - Căn hộ - Phòng trọ',
                location: 'Trung tâm TP. Đà Nẵng',
                desc: 'Triển khai thi công phần thô hệ khung cột bê tông cốt thép và tường xây căn hộ dịch vụ Olive Apartment đúng tiến độ cam kết với chủ đầu tư.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi công xây tô hoàn thiện mặt tiền – Biệt thự Modern Luxury',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Khu đô thị Hòa Xuân, Đà Nẵng',
                desc: 'Giai đoạn hoàn thiện mặt tiền kiến trúc hiện đại với đường nét mảng khối sắc sảo, xử lý chống thấm và sơn bả ngoại thất cao cấp.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi công hoàn thiện nội thất căn hộ cho thuê cao cấp',
                category: 'can-ho',
                categoryLabel: 'Khách sạn - Căn hộ - Phòng trọ',
                location: 'Quận Sơn Trà, Đà Nẵng',
                desc: 'Thi công hoàn thiện hệ trần thạch cao, chiếu sáng, ốp lát và lắp đặt nội thất gỗ công nghiệp đồng bộ tối ưu công năng khai thác cho thuê.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi công xây nhà trọn gói 3 tầng hiện đại – Hòa Xuân',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Quận Cẩm Lệ, Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng được ATD DESIGN thiết kế và thi công trọn gói chìa khóa trao tay, kiểm soát vật tư rõ ràng từng giai đoạn.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi công cải tạo & hoàn thiện không gian văn phòng làm việc',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                location: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Cải tạo kết cấu, hệ thống điện nước M&E, vách kính khung nhôm và bố trí không gian làm việc hiện đại, thoáng sáng cho doanh nghiệp.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Nghiệm thu hoàn thiện & bàn giao nhà phố tại Hòa Khánh',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Phường Hòa Khánh, Đà Nẵng',
                desc: 'Kiểm tra chất lượng hoàn thiện từng hạng mục kỹ thuật, vệ sinh công nghiệp và bàn giao tổ ấm trọn vẹn đúng thời hạn cho gia chủ.'
            }
        ];

        /**
         * 2. DỮ LIỆU 10 ẢNH DỰ ÁN Ở ĐÀ NẴNG TỪ GOOGLE DRIVE
         */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Olive Apartment – Căn hộ dịch vụ xanh giữa lòng phố Đà Nẵng',
                category: 'can-ho',
                location: 'TP. Đà Nẵng',
                desc: 'Nổi bật với hệ ban công vòm cong xếp tầng kết hợp mảng tường trắng kem và sắc xanh Olive đặc trưng, hài hòa giữa thẩm mỹ và công năng.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Mermaid House – Biệt thự hiện đại tại Ngũ Hành Sơn',
                category: 'biet-thu',
                location: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Dự án thi công bởi ATD DESIGN, mang dấu ấn kiến trúc đương đại tinh tế, không gian sống thoáng mở và kết cấu bền vững.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Villa Phong Cách Modern Luxury – Khu đô thị Hòa Xuân',
                category: 'biet-thu',
                location: 'Hòa Xuân, Đà Nẵng',
                desc: 'Căn villa được chăm chút từ đường nét kiến trúc mạnh mẽ, mảng khối hài hòa đến cảnh quan xanh mát và tiện nghi đẳng cấp.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà phố cải tạo kết hợp ở – Nguyễn Đôn Tiết, Hải Châu',
                category: 'nha-pho',
                location: 'Hải Châu, Đà Nẵng',
                desc: 'Giải pháp cải tạo toàn diện kết cấu và diện mạo kiến trúc, nâng tầm không gian sống tiện nghi ngay khu vực trung tâm.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Nhà ở gia đình trọn gói – Khu vực Hồ Xuân Hương',
                category: 'nha-pho',
                location: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Thiết kế và thi công trọn gói tối ưu thông gió, ánh sáng tự nhiên và công năng sinh hoạt cho gia đình trẻ tại Đà Nẵng.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Căn hộ cho thuê cao cấp ven biển – Quận Sơn Trà',
                category: 'can-ho',
                location: 'Sơn Trà, Đà Nẵng',
                desc: 'Mô hình căn hộ lưu trú hiện đại tối ưu số lượng phòng và trải nghiệm nghỉ dưỡng, gia tăng hiệu quả đầu tư lâu dài.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Nhà phố 3 tầng hiện đại – Khu vực Nguyễn Sinh Sắc, Hòa Khánh',
                category: 'nha-pho',
                location: 'Hòa Khánh, Đà Nẵng',
                desc: 'Kiến trúc mặt tiền thanh lịch, bố trí không gian sinh hoạt chung rộng rãi kết hợp khoảng xanh thư giãn tại các tầng.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Hoàn thiện nội thất căn hộ tối giản ấm áp – Thanh Khê',
                category: 'noi-that',
                location: 'Thanh Khê, Đà Nẵng',
                desc: 'Sử dụng gam màu trắng kem, be và vân gỗ nâu xuyên suốt cùng hệ tủ kịch trần bo cong tinh tế, tối ưu không gian lưu trữ.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Nhà phố 2 mặt tiền hiện đại – Khu vực Liên Chiểu, Đà Nẵng',
                category: 'nha-pho',
                location: 'Liên Chiểu, Đà Nẵng',
                desc: 'Tận dụng lợi thế hai mặt thoáng với hệ cửa kính lớn và ban công cây xanh tạo nhịp điệu kiến trúc nổi bật.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Không gian nội thất phòng khách & bếp – Khu Nam Việt Á',
                category: 'noi-that',
                location: 'Nam Việt Á, Đà Nẵng',
                desc: 'Thiết kế thi công nội thất trọn gói đồng bộ vật liệu đá, gỗ và ánh sáng tạo nên không gian sinh hoạt ấm cúng, sang trọng.'
            }
        ];

        /**
         * 3. DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ
         */
        const blogPosts = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                date: 'Cập nhật mới nhất',
                title: 'Olive Apartment | Nét Xanh An Yên Giữa Lòng Phố Đà Nẵng',
                excerpt: 'Khám phá giải pháp kiến trúc ban công vòm cong kết hợp nội thất tối giản gam màu trung tính ấm áp do ATD DESIGN thiết kế.',
                fullText: 'Lấy cảm hứng từ sự kết hợp giữa kiến trúc hiện đại và thiên nhiên, Olive Apartment được ATD DESIGN định hình với đường nét mềm mại, bảng màu trắng kem – be – nâu gỗ kết hợp điểm nhấn gạch xanh Olive tinh tế. Không gian sinh hoạt chung được bố trí gọn gàng cùng hệ vách kính khung đen giúp căn hộ luôn thông thoáng và giàu cảm xúc.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                date: 'Kỹ thuật thi công',
                title: 'Quy Trình Đổ Bê Tông Móng & Bảo Dưỡng Đúng Kỹ Thuật',
                excerpt: 'Những tiêu chuẩn kiểm tra cốt thép, cao độ coppha và bảo dưỡng bê tông móng giúp công trình vững chắc bền bỉ hàng chục năm.',
                fullText: 'Công tác thi công móng là bước nền tảng quyết định sự bền vững của toàn bộ công trình. Tại ATD DESIGN, trước khi đổ bê tông, kỹ sư giám sát luôn kiểm tra kỹ lớp bê tông lót, khoảng cách thép, con kê bảo vệ và độ vững chắc của hệ coppha, sau đó thực hiện bảo dưỡng giữ ẩm đúng chu kỳ để đạt cường độ tối ưu.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                date: 'Xu hướng thiết kế',
                title: 'Villa Phong Cách Modern Luxury – Sang Trọng & Bền Vững',
                excerpt: 'Sự giao thoa giữa đường nét kiến trúc mạnh mẽ, không gian mở đón sáng tự nhiên và cảnh quan xanh mát cho gia đình hiện đại.',
                fullText: 'Phong cách Modern Luxury đề cao sự tinh giản trong hình khối nhưng chăm chút tỉ mỉ ở vật liệu hoàn thiện và tỷ lệ ánh sáng. ATD DESIGN thiết kế từng không gian chức năng gắn kết liền mạch với sân vườn xanh mát, mang lại trải nghiệm nghỉ dưỡng ngay trong chính tổ ấm của gia chủ.'
            },
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: 'Cẩm nang xây nhà',
                title: '03 Lưu Ý Quan Trọng Khi Cải Tạo Nhà Phố & Kết Cấu Dầm Sàn',
                excerpt: 'Đánh giá hiện trạng kết cấu, tính toán tải trọng và lập dự toán minh bạch là chìa khóa giúp cải tạo nhà an toàn, tiết kiệm chi phí.',
                fullText: 'Đối với công trình cải tạo như dự án Nguyễn Đôn Tiết, mỗi phần kết cấu đều cần khảo sát hiện trạng kỹ lưỡng trước khi lên phương án gia cố dầm sàn. Việc phối hợp chặt chẽ giữa thiết kế và đội ngũ thi công trực tiếp giúp kiểm soát chất lượng, đảm bảo an toàn lao động và tránh phát sinh ngân sách.'
            }
        ];

        /**
         * Render danh sách Công trình thực tế (2 cột mobile, không nhãn dán, không cắt chữ)
         */
        function renderConstruction(filterCat = 'all') {
            const grid = document.getElementById('constructionGrid');
            if (!grid) return;

            const filtered = filterCat === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.category === filterCat);

            grid.innerHTML = filtered.map((item, idx) => `
                <article
                    class="project-card cursor-pointer"
                    onclick="openDetailModal('construction', '${item.id}')"
                >
                    <div class="project-img-box">
                        <img
                            src="${getDriveThumb(item.id, 'w900')}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, '${item.id}', 'ATD THI CÔNG')"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-atdPrimary leading-snug break-words whitespace-normal mb-1.5 hover:text-atdAccent transition-colors">
                                ${item.title}
                            </h3>
                        </div>
                        <div class="pt-2 mt-1 border-t border-slate-100 flex flex-wrap items-center justify-between gap-1 text-[11px] text-slate-500">
                            <span>${item.categoryLabel}</span>
                            <span class="text-atdAccent font-semibold">Chi tiết</span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterConstruction(cat) {
            document.querySelectorAll('#constructionTabs .cat-tab-btn').forEach(btn => {
                btn.classList.toggle('active', btn.getAttribute('data-cat') === cat);
            });
            renderConstruction(cat);
        }

        /**
         * Render danh sách 10 Dự án tại Đà Nẵng (2 cột mobile, không nhãn dán, chữ đầy đủ)
         */
        function renderDaNang(filterCat = 'all') {
            const grid = document.getElementById('danangGrid');
            if (!grid) return;

            const filtered = filterCat === 'all'
                ? danangProjects
                : danangProjects.filter(item => item.category === filterCat);

            grid.innerHTML = filtered.map(item => `
                <article
                    class="project-card cursor-pointer"
                    onclick="openDetailModal('danang', '${item.id}')"
                >
                    <div class="project-img-box">
                        <img
                            src="${getDriveThumb(item.id, 'w900')}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, '${item.id}', 'DỰ ÁN ĐÀ NẴNG')"
                        >
                    </div>
                    <div class="p-3 sm:p-3.5 flex flex-col flex-1 justify-between">
                        <h3 class="text-xs sm:text-[13px] font-bold text-atdPrimary leading-snug break-words whitespace-normal mb-2 hover:text-atdAccent transition-colors">
                            ${item.title}
                        </h3>
                        <div class="text-[11px] text-slate-500 flex items-center gap-1">
                            <i class="fa-solid fa-location-dot text-atdAccent text-[10px] shrink-0"></i>
                            <span class="break-words">${item.location}</span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterDaNang(cat) {
            document.querySelectorAll('#danangTabs .cat-tab-btn').forEach(btn => {
                btn.classList.toggle('active', btn.getAttribute('data-cat') === cat);
            });
            renderDaNang(cat);
        }

        /**
         * Render danh mục Bài viết trang chủ
         */
        function renderBlogs() {
            const grid = document.getElementById('blogGrid');
            if (!grid) return;

            grid.innerHTML = blogPosts.map((post, index) => `
                <article
                    class="project-card cursor-pointer"
                    onclick="openBlogModal(${index})"
                >
                    <div class="project-img-box">
                        <img
                            src="${getDriveThumb(post.id, 'w800')}"
                            alt="${post.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, '${post.id}', 'TIN TỨC ATD')"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1">
                        <div class="text-[11px] font-medium text-atdAccent mb-1">${post.date}</div>
                        <h3 class="text-xs sm:text-sm font-bold text-atdPrimary leading-snug break-words whitespace-normal mb-2 hover:text-atdAccent transition-colors">
                            ${post.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed break-words mt-auto">
                            ${post.excerpt}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /**
         * Điều khiển Modal xem chi tiết công trình / bài viết
         */
        function openDetailModal(type, driveId) {
            const source = type === 'construction' ? constructionProjects : danangProjects;
            const item = source.find(p => p.id === driveId);
            if (!item) return;

            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImg');
            img.setAttribute('data-fallback-step', '0');
            img.src = getDriveThumb(item.id, 'w1200');
            img.alt = item.title;
            img.onerror = function () { handleDriveImageError(img, item.id, 'ATD DESIGN'); };

            document.getElementById('modalMeta').textContent = item.location || item.categoryLabel || 'ATD DESIGN';
            document.getElementById('modalTitle').textContent = item.title;
            document.getElementById('modalDesc').textContent = item.desc;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function openBlogModal(index) {
            const post = blogPosts[index];
            if (!post) return;

            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImg');
            img.setAttribute('data-fallback-step', '0');
            img.src = getDriveThumb(post.id, 'w1200');
            img.alt = post.title;
            img.onerror = function () { handleDriveImageError(img, post.id, 'ATD DESIGN'); };

            document.getElementById('modalMeta').textContent = post.date;
            document.getElementById('modalTitle').textContent = post.title;
            document.getElementById('modalDesc').textContent = post.fullText;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function closeModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        /**
         * Logic Slider 2 Banner tự trượt chuyên nghiệp + hỗ trợ vuốt cảm ứng trên điện thoại
         */
        let currentSlide = 0;
        const totalSlides = 2;
        let slideTimer = null;

        function updateSliderUI() {
            const track = document.getElementById('heroSlidesTrack');
            if (track) {
                track.style.transform = `translateX(-${currentSlide * 100}%)`;
            }
            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById(`dot${i}`);
                if (!dot) continue;
                if (i === currentSlide) {
                    dot.className = 'w-7 h-2 rounded-full bg-atdAccent transition-all';
                } else {
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all';
                }
            }
        }

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            updateSliderUI();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSliderUI();
            }, 5000);
        }

        /**
         * Toggle Mobile Menu & Submenu
         */
        function toggleSubMenu(id) {
            const el = document.getElementById(id);
            if (el) el.classList.toggle('hidden');
        }

        /**
         * Khởi tạo toàn bộ sự kiện khi tải trang
         */
        document.addEventListener('DOMContentLoaded', () => {
            try {
                // Render các danh mục sản phẩm, dự án Đà Nẵng & tin tức
                renderConstruction('all');
                renderDaNang('all');
                renderBlogs();

                // Khởi chạy tự trượt 2 banner
                updateSliderUI();
                resetAutoSlide();

                document.getElementById('prevSlideBtn')?.addEventListener('click', () => goToSlide(currentSlide - 1));
                document.getElementById('nextSlideBtn')?.addEventListener('click', () => goToSlide(currentSlide + 1));

                // Hỗ trợ vuốt trái/phải banner trên điện thoại
                const sliderEl = document.getElementById('heroSlider');
                let touchStartX = 0;
                if (sliderEl) {
                    sliderEl.addEventListener('touchstart', (e) => {
                        touchStartX = e.changedTouches[0].screenX;
                    }, { passive: true });
                    sliderEl.addEventListener('touchend', (e) => {
                        const diff = e.changedTouches[0].screenX - touchStartX;
                        if (Math.abs(diff) > 45) {
                            goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                        }
                    }, { passive: true });
                }

                // Menu điện thoại
                const mobileBtn = document.getElementById('mobileMenuBtn');
                const mobilePanel = document.getElementById('mobileMenuPanel');
                if (mobileBtn && mobilePanel) {
                    mobileBtn.addEventListener('click', () => {
                        const isHidden = mobilePanel.classList.toggle('hidden');
                        mobileBtn.setAttribute('aria-expanded', String(!isHidden));
                    });
                    mobilePanel.querySelectorAll('.mobile-nav-link').forEach(link => {
                        link.addEventListener('click', () => {
                            mobilePanel.classList.add('hidden');
                            mobileBtn.setAttribute('aria-expanded', 'false');
                        });
                    });
                }

                // Đóng modal khi bấm nền tối hoặc phím ESC
                const modal = document.getElementById('detailModal');
                if (modal) {
                    modal.addEventListener('click', (e) => {
                        if (e.target === modal) closeModal();
                    });
                }
                document.addEventListener('keydown', (e) => {
                    if (e.key === 'Escape') closeModal();
                });

                // Xử lý Form đăng ký tư vấn & báo giá (không dùng alert)
                const quoteForm = document.getElementById('quoteForm');
                const feedback = document.getElementById('quoteFeedback');
                if (quoteForm && feedback) {
                    quoteForm.addEventListener('submit', (e) => {
                        e.preventDefault();
                        const name = document.getElementById('qName').value.trim();
                        const phone = document.getElementById('qPhone').value.trim();
                        const type = document.getElementById('qType').value;

                        if (!name || !phone) {
                            feedback.className = 'mt-4 p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                            feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để ATD DESIGN liên hệ báo giá.';
                            return;
                        }

                        feedback.className = 'mt-4 p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
                        feedback.innerHTML = `Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${type}</strong> đã được ghi nhận. Kỹ sư ATD DESIGN sẽ liên hệ số <strong>${phone}</strong> trong thời gian sớm nhất.`;
                        quoteForm.reset();
                    });
                }
            } catch (err) {
                console.error('Lỗi khởi tạo giao diện ATD DESIGN:', err);
            }
        });
    </script>
</body>
</html>
