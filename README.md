<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Nhôm Kính Nam Long | Cửa Nhôm Xingfa & Cửa Kính Cường Lực Đà Nẵng</title>
    <meta name="description" content="Nhôm Kính Nam Long (nhomkinhnamlong.com) - Chuyên sản xuất, thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0905.160.887.">

    <!-- Meta Thumbnail (Ảnh Logo Trang Web Khi Chia Sẻ Link Qua Zalo, Facebook, Messenger) -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Nhôm Kính Nam Long">
    <meta property="og:url" content="https://nhomkinhnamlong.com">
    <meta property="og:title" content="Nhôm Kính Nam Long - Cửa Nhôm Xingfa & Kính Cường Lực Chính Hãng Đà Nẵng">
    <meta property="og:description" content="Thi công trọn gói Cửa Nhôm Xingfa, Cửa Kính Cường Lực, Kính Ốp Bếp, Phòng Tắm Kính tại Đà Nẵng. Địa chỉ: 123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng. Hotline: 0905.160.887.">
    <meta property="og:image" content="https://nhomkinhnamlong.com/assets/logo-nhom-kinh-nam-long-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nhôm Kính Nam Long - nhomkinhnamlong.com">
    <meta name="twitter:description" content="Chuyên cửa nhôm Xingfa, cửa kính cường lực chính hãng giá tốt tại Đà Nẵng.">
    <meta name="twitter:image" content="https://nhomkinhnamlong.com/assets/logo-nhom-kinh-nam-long-thumbnail.png">

    <!-- Font Inter & Tailwind CSS CDN -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình bảng màu theo Logo Nhôm Kính Nam Long -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            primary: '#0B3B66',     /* Xanh Navy Kiến Trúc (Màu chính logo) */
                            dark: '#072744',        /* Xanh đậm footer / hover */
                            light: '#EBF4FC',       /* Nền xanh nhạt tinh tế */
                            accent: '#D97706',      /* Vàng Hổ Phách Kim Loại (Điểm nhấn logo) */
                            accentHover: '#B45309', /* Vàng đậm khi hover */
                            surface: '#F8FAFC',     /* Nền sáng hiện đại */
                        }
                    }
                }
            }
        }
    </script>

    <!-- Custom CSS tối giản chuẩn Flatsome & chống tràn viền tuyệt đối -->
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            scroll-behavior: smooth;
            font-family: 'Inter', sans-serif;
            background-color: #ffffff;
            color: #1e293b;
        }

        /* Chiều ngang giao diện trên máy tính = 95% kích thước màn hình */
        .nl-container {
            width: 94%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .nl-container {
                width: 95%;
                max-width: 95%;
            }
        }

        /* Dropdown Menu chuẩn Flatsome */
        .nav-item-dropdown {
            position: relative;
        }
        .nav-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            z-index: 60;
        }
        .nav-item-dropdown:hover .nav-dropdown-menu,
        .nav-item-dropdown:focus-within .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Tiêu đề Section phong cách Flatsome gọn gàng */
        .flatsome-heading {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
        }
        .flatsome-heading::before,
        .flatsome-heading::after {
            content: "";
            height: 2px;
            flex: 1;
            max-width: 90px;
            background: linear-gradient(90deg, transparent, #cbd5e1);
        }
        .flatsome-heading::after {
            background: linear-gradient(90deg, #cbd5e1, transparent);
        }

        /* Banner Slider mượt mà & bằng kích thước */
        .banner-track {
            display: flex;
            transition: transform 0.6s cubic-bezier(0.25, 0.8, 0.25, 1);
            width: 100%;
        }
        .banner-slide {
            min-width: 100%;
            width: 100%;
            flex-shrink: 0;
        }

        /* Hiệu ứng nhịp nhẹ cho nút liên hệ nổi bật */
        @keyframes softPulse {
            0%, 100% { box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.45); }
            50% { box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
        }
        .btn-pulse-hotline {
            animation: softPulse 2.2s infinite;
        }

        /* Ẩn thanh cuộn ngang cho thanh filter trên mobile nhưng vẫn vuốt mượt */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="antialiased text-slate-800 bg-white">

    <!-- ====================================================================== -->
    <!-- TOP BAR: THÔNG TIN NHANH (CHUẨN FLATSOME HEADER TOP - KHÔNG CHỈNH SỬA) -->
    <!-- ====================================================================== -->
    <div class="bg-brand-dark text-slate-200 text-xs py-2 border-b border-white/10">
        <div class="nl-container flex flex-wrap items-center justify-between gap-y-1 gap-x-4">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-accent shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    <span>123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-300">
                    <svg class="w-3.5 h-3.5 text-brand-accent shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                    <span>Làm việc: 07:30 - 20:00 (T2 - CN)</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-slate-300">
                <span>Website: <strong class="text-white font-medium">nhomkinhnamlong.com</strong></span>
                <span class="text-white/25">|</span>
                <span>Tư vấn &amp; Báo giá: <a href="tel:0905160887" class="text-amber-400 font-semibold hover:underline">0905.160.887</a></span>
            </div>
        </div>
    </div>

    <!-- ====================================================================== -->
    <!-- MAIN HEADER: LOGO CHUYÊN NGHIỆP GỌN NHỎ + TÌM KIẾM (KHÔNG NÚT GỌI NGAY) -->
    <!-- ====================================================================== -->
    <header id="site-header" class="sticky top-0 z-50 bg-white shadow-sm border-b border-slate-200/80">
        <!-- Header Main Row -->
        <div class="nl-container py-2.5 flex items-center justify-between gap-3">
            <!-- Nút Mở Menu Trên Điện Thoại -->
            <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục trang web" class="lg:hidden inline-flex items-center justify-center p-2 rounded-lg text-brand-primary hover:bg-brand-light transition">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/></svg>
            </button>

            <!-- LOGO CHUYÊN NGHIỆP GỌN NHỎ (SVG VECTOR SẮC NÉT) -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Trang chủ Nhôm Kính Nam Long">
                <!-- Biểu tượng kiến trúc khung cửa nhôm kính + chữ NL cách điệu gọn nhỏ -->
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect x="2" y="2" width="44" height="44" rx="10" fill="#0B3B66"/>
                    <!-- Khung cửa kiến trúc ngoài -->
                    <rect x="7" y="7" width="34" height="34" rx="6" stroke="#D97706" stroke-width="2"/>
                    <!-- Đường cắt kính hiện đại -->
                    <path d="M13 33V15L23 28V15" stroke="#FFFFFF" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M27.5 15V33H35.5" stroke="#F59E0B" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
                    <!-- Ánh phản chiếu kính -->
                    <path d="M31 12L36 17" stroke="#93C5FD" stroke-width="1.6" stroke-linecap="round" opacity="0.8"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary group-hover:text-brand-accent transition-colors">
                        NHÔM KÍNH <span class="text-brand-accent">NAM LONG</span>
                    </div>
                    <div class="text-[10px] sm:text-[11px] font-medium text-slate-500 tracking-wide">
                        nhomkinhnamlong.com
                    </div>
                </div>
            </a>

            <!-- Thanh Tìm Kiếm Sản Phẩm (Kiểu Flatsome / Ngochanwindow) -->
            <form id="header-search-form" class="hidden md:flex flex-1 max-w-xl items-center bg-slate-50 border border-slate-300 rounded-lg overflow-hidden focus-within:border-brand-primary focus-within:ring-2 focus-within:ring-brand-primary/15 transition">
                <select id="search-category" aria-label="Chọn danh mục tìm kiếm" class="bg-slate-100 text-slate-700 text-xs font-medium px-3 py-2.5 border-r border-slate-200 focus:outline-none cursor-pointer">
                    <option value="all">Tất cả danh mục</option>
                    <option value="xingfa">Cửa nhôm Xingfa</option>
                    <option value="kinh-cuong-luc">Cửa kính cường lực</option>
                    <option value="nhua-loi-thep">Cửa nhựa lõi thép</option>
                    <option value="cua-tu-dong">Cửa kính tự động</option>
                    <option value="cau-thang-kinh">Cầu thang kính</option>
                    <option value="kinh-op-bep">Kính ốp bếp</option>
                    <option value="phong-tam-kinh">Phòng tắm kính</option>
                </select>
                <input id="search-input" type="text" placeholder="Tìm cửa nhôm Xingfa, cửa kính, báo giá..." class="flex-1 bg-transparent px-3.5 py-2 text-xs sm:text-sm text-slate-700 placeholder-slate-400 focus:outline-none">
                <button type="submit" aria-label="Tìm kiếm" class="bg-brand-primary hover:bg-brand-dark text-white px-4 py-2.5 transition flex items-center justify-center">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
                </button>
            </form>

            <!-- Nút Tìm kiếm nhanh trên mobile (Thay vì nút gọi ngay để tránh tràn viền header) -->
            <div class="flex items-center gap-2">
                <button id="mobile-search-toggle" type="button" aria-label="Tìm kiếm sản phẩm" class="md:hidden p-2 rounded-lg text-brand-primary hover:bg-brand-light transition">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
                </button>
                <a href="#form-bao-gia" class="hidden sm:inline-flex items-center gap-1.5 text-xs font-semibold text-brand-primary bg-brand-light hover:bg-brand-primary hover:text-white px-3.5 py-2 rounded-lg transition whitespace-nowrap">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
                    <span>Nhận báo giá</span>
                </a>
            </div>
        </div>

        <!-- Thanh tìm kiếm ẩn cho Mobile -->
        <div id="mobile-search-bar" class="hidden md:hidden border-t border-slate-100 bg-slate-50 px-3 py-2">
            <form id="mobile-search-form" class="flex items-center bg-white border border-slate-300 rounded-lg overflow-hidden">
                <input id="mobile-search-input" type="text" placeholder="Tìm sản phẩm nhôm kính..." class="flex-1 px-3 py-2 text-xs text-slate-700 focus:outline-none">
                <button type="submit" class="bg-brand-primary text-white px-3.5 py-2 text-xs font-medium">Tìm</button>
            </form>
        </div>

        <!-- ====================================================================== -->
        <!-- THANH DANH MỤC CHÍNH (DESKTOP: VIẾT LIỀN 1 HÀNG NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN) -->
        <!-- ====================================================================== -->
        <nav aria-label="Danh mục chính" class="hidden lg:block bg-brand-primary text-white border-t border-white/10">
            <div class="nl-container">
                <ul class="flex flex-wrap items-center justify-between xl:justify-start gap-x-1 xl:gap-x-2 py-0.5 text-[12.5px] xl:text-[13px] font-semibold tracking-tight">
                    <!-- 1. Trang chủ -->
                    <li>
                        <a href="#trang-chu" class="block px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            Trang chủ
                        </a>
                    </li>
                    <!-- 2. Giới thiệu -->
                    <li>
                        <a href="#gioi-thieu" class="block px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            Giới thiệu
                        </a>
                    </li>
                    <!-- 3. Cửa nhôm xingfa (Có menu con 1 - 5 cánh) -->
                    <li class="nav-item-dropdown">
                        <a href="#san-pham-xingfa" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            <span>Cửa nhôm xingfa</span>
                            <svg class="w-3.5 h-3.5 opacity-80" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <ul class="nav-dropdown-menu bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-200 py-1.5 text-[13px] font-medium">
                            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('1 cánh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa nhôm xingfa 1 cánh</a></li>
                            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('2 cánh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa nhôm xingfa 2 cánh</a></li>
                            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('3 cánh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa nhôm xingfa 3 cánh</a></li>
                            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('4 cánh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa nhôm xingfa 4 cánh</a></li>
                            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('xếp trượt')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a></li>
                        </ul>
                    </li>
                    <!-- 4. Cửa kính cường lực -->
                    <li>
                        <a href="#danh-muc-san-pham" class="block px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            Cửa kính cường lực
                        </a>
                    </li>
                    <!-- 5. Sản phẩm (Có menu con 6 hạng mục) -->
                    <li class="nav-item-dropdown">
                        <a href="#danh-muc-san-pham" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            <span>Sản phẩm</span>
                            <svg class="w-3.5 h-3.5 opacity-80" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <ul class="nav-dropdown-menu bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-200 py-1.5 text-[13px] font-medium">
                            <li><a href="#san-pham-xingfa" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa nhôm xingfa</a></li>
                            <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa nhựa lõi thép</a></li>
                            <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cửa kính tự động</a></li>
                            <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Cầu thang kính</a></li>
                            <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Kính ốp bếp</a></li>
                            <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition whitespace-nowrap">Phòng tắm kính</a></li>
                        </ul>
                    </li>
                    <!-- 6. Công trình -->
                    <li>
                        <a href="#cong-trinh" class="block px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            Công trình
                        </a>
                    </li>
                    <!-- 7. Báo giá -->
                    <li>
                        <a href="#bao-gia" class="block px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            Báo giá
                        </a>
                    </li>
                    <!-- 8. Tin tức -->
                    <li>
                        <a href="#tin-tuc" class="block px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            Tin tức
                        </a>
                    </li>
                    <!-- 9. Liên hệ -->
                    <li>
                        <a href="#lien-he" class="block px-2.5 xl:px-3.5 py-2.5 rounded-md hover:bg-white/10 transition whitespace-nowrap">
                            Liên hệ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Thanh Danh Mục Lướt Ngang Gọn Đẹp Trên Điện Thoại -->
        <div class="lg:hidden bg-brand-primary text-white border-t border-white/10">
            <div class="flex items-center gap-1 overflow-x-auto no-scrollbar px-3 py-1.5 text-[11.5px] font-semibold">
                <a href="#trang-chu" class="px-2.5 py-1 rounded bg-white/10 whitespace-nowrap shrink-0">Trang chủ</a>
                <a href="#san-pham-xingfa" class="px-2.5 py-1 rounded hover:bg-white/10 whitespace-nowrap shrink-0">Cửa nhôm xingfa</a>
                <a href="#danh-muc-san-pham" class="px-2.5 py-1 rounded hover:bg-white/10 whitespace-nowrap shrink-0">Cửa kính cường lực</a>
                <a href="#danh-muc-san-pham" class="px-2.5 py-1 rounded hover:bg-white/10 whitespace-nowrap shrink-0">Sản phẩm</a>
                <a href="#cong-trinh" class="px-2.5 py-1 rounded hover:bg-white/10 whitespace-nowrap shrink-0">Công trình</a>
                <a href="#bao-gia" class="px-2.5 py-1 rounded hover:bg-white/10 whitespace-nowrap shrink-0">Báo giá</a>
                <a href="#tin-tuc" class="px-2.5 py-1 rounded hover:bg-white/10 whitespace-nowrap shrink-0">Tin tức</a>
                <a href="#lien-he" class="px-2.5 py-1 rounded hover:bg-white/10 whitespace-nowrap shrink-0">Liên hệ</a>
            </div>
        </div>
    </header>

    <!-- ====================================================================== -->
    <!-- MOBILE DRAWER MENU (CHUẨN FLATSOME OFF-CANVAS CHO ĐIỆN THOẠI)           -->
    <!-- ====================================================================== -->
    <div id="mobile-drawer-overlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
    <aside id="mobile-drawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between px-4 py-3.5 bg-brand-primary text-white">
            <span class="font-bold text-sm tracking-wide">DANH MỤC NAM LONG</span>
            <button id="mobile-drawer-close" type="button" aria-label="Đóng menu" class="p-1.5 rounded-lg hover:bg-white/15">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-sm font-medium text-slate-700">
            <a href="#trang-chu" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Trang chủ</a>
            <a href="#gioi-thieu" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Giới thiệu</a>

            <!-- Accordion: Cửa nhôm xingfa -->
            <div>
                <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-4 py-3 hover:bg-brand-light hover:text-brand-primary text-left">
                    <span>Cửa nhôm xingfa</span>
                    <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                </button>
                <div class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-xs text-slate-600">
                    <a href="#san-pham-xingfa" onclick="filterProductsByKeyword('1 cánh')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 1 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProductsByKeyword('2 cánh')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 2 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProductsByKeyword('3 cánh')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 3 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProductsByKeyword('4 cánh')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 4 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProductsByKeyword('xếp trượt')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 5 cánh</a>
                </div>
            </div>

            <a href="#danh-muc-san-pham" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Cửa kính cường lực</a>

            <!-- Accordion: Sản phẩm -->
            <div>
                <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-4 py-3 hover:bg-brand-light hover:text-brand-primary text-left">
                    <span>Sản phẩm</span>
                    <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                </button>
                <div class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-xs text-slate-600">
                    <a href="#san-pham-xingfa" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa</a>
                    <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa nhựa lõi thép</a>
                    <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cửa kính tự động</a>
                    <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Cầu thang kính</a>
                    <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Kính ốp bếp</a>
                    <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="mobile-nav-link block py-2 hover:text-brand-primary">+ Phòng tắm kính</a>
                </div>
            </div>

            <a href="#cong-trinh" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Công trình</a>
            <a href="#bao-gia" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Báo giá</a>
            <a href="#tin-tuc" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Tin tức</a>
            <a href="#lien-he" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Liên hệ</a>
        </div>
        <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
            <div class="font-bold text-brand-primary">NHÔM KÍNH NAM LONG</div>
            <div>123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng</div>
            <div>Hotline: <a href="tel:0905160887" class="font-bold text-brand-accent">0905.160.887</a></div>
        </div>
    </aside>

    <!-- ====================================================================== -->
    <!-- MAIN CONTENT (UX BUILDER FLATSOME SECTIONS)                            -->
    <!-- ====================================================================== -->
    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- ================================================================== -->
        <!-- SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU) -->
        <!-- Thiết kế hình ảnh & chữ nằm trọn bên trong, cách xa viền, không mất chữ -->
        <!-- ================================================================== -->
        <section aria-label="Banner nổi bật" class="bg-slate-100 py-3 sm:py-4">
            <div class="nl-container">
                <div id="hero-slider" class="relative overflow-hidden rounded-2xl shadow-md bg-brand-dark">
                    <div id="banner-track" class="banner-track">

                        <!-- SLIDE 1 -->
                        <div class="banner-slide">
                            <div class="w-full min-h-[340px] sm:min-h-[390px] lg:min-h-[430px] bg-gradient-to-br from-[#072744] via-[#0B3B66] to-[#12538B] px-7 py-8 sm:px-14 sm:py-10 lg:px-20 lg:py-12 flex items-center">
                                <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                                    <!-- Nội dung chữ cách xa viền ảnh -->
                                    <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-[0.18em] text-amber-400">
                                            Nhôm Kính Nam Long • Đà Nẵng
                                        </p>
                                        <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight">
                                            CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG
                                        </h1>
                                        <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                                            Gia công chuẩn kỹ thuật, phụ kiện Kinlong đồng bộ, cách âm cách nhiệt vượt trội. Khảo sát &amp; báo giá miễn phí tận nơi tại Đà Nẵng.
                                        </p>
                                        <div class="pt-1 flex flex-wrap items-center gap-3">
                                            <a href="#san-pham-xingfa" class="inline-flex items-center justify-center bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-lg shadow transition">
                                                Xem Mẫu Cửa Xingfa
                                            </a>
                                            <a href="#form-bao-gia" class="inline-flex items-center justify-center bg-white/10 hover:bg-white/20 border border-white/30 text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition">
                                                Nhận Báo Giá Ngay
                                            </a>
                                        </div>
                                    </div>
                                    <!-- Hình ảnh sản phẩm nằm gọn bên trong banner -->
                                    <div class="md:col-span-5 flex justify-center md:justify-end">
                                        <div class="w-full max-w-[360px] bg-white/10 p-2 sm:p-2.5 rounded-xl border border-white/20 backdrop-blur-sm">
                                            <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-slate-800">
                                                <img
                                                    src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w1000"
                                                    data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                                    alt="Cửa nhôm Xingfa nhập khẩu Nhôm Kính Nam Long"
                                                    class="w-full h-full object-cover"
                                                    onerror="handleDriveFallback(this, 'Cửa Nhôm Xingfa')"
                                                >
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- SLIDE 2 (Kích thước & padding đồng nhất tuyệt đối với Slide 1) -->
                        <div class="banner-slide">
                            <div class="w-full min-h-[340px] sm:min-h-[390px] lg:min-h-[430px] bg-gradient-to-br from-[#0F2942] via-[#13426B] to-[#0B3B66] px-7 py-8 sm:px-14 sm:py-10 lg:px-20 lg:py-12 flex items-center">
                                <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                                    <!-- Nội dung chữ cách xa viền ảnh -->
                                    <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-[0.18em] text-amber-400">
                                            Giải Pháp Kiến Trúc Toàn Diện
                                        </p>
                                        <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight">
                                            THI CÔNG CỬA KÍNH CƯỜNG LỰC &amp; PHÒNG TẮM KÍNH
                                        </h2>
                                        <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                                            Chuyên thi công cầu thang kính, kính ốp bếp, cửa kính tự động cho nhà phố, biệt thự, khách sạn tại Đà Nẵng với chế độ bảo hành dài hạn.
                                        </p>
                                        <div class="pt-1 flex flex-wrap items-center gap-3">
                                            <a href="#cong-trinh" class="inline-flex items-center justify-center bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-lg shadow transition">
                                                Xem Dự Án Đã Làm
                                            </a>
                                            <a href="tel:0905160887" class="inline-flex items-center justify-center bg-white/10 hover:bg-white/20 border border-white/30 text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition">
                                                Hotline: 0905.160.887
                                            </a>
                                        </div>
                                    </div>
                                    <!-- Hình ảnh dự án thực tế nằm gọn bên trong banner -->
                                    <div class="md:col-span-5 flex justify-center md:justify-end">
                                        <div class="w-full max-w-[360px] bg-white/10 p-2 sm:p-2.5 rounded-xl border border-white/20 backdrop-blur-sm">
                                            <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-slate-800">
                                                <img
                                                    src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000"
                                                    data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                                    alt="Dự án thi công Nhôm Kính Nam Long Đà Nẵng"
                                                    class="w-full h-full object-cover"
                                                    onerror="handleDriveFallback(this, 'Dự Án Nhôm Kính')"
                                                >
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút Điều Hướng Trái / Phải Nằm Gọn Viền Trong -->
                    <button id="banner-prev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3.5 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition z-10">
                        <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                    </button>
                    <button id="banner-next" type="button" aria-label="Banner sau" class="absolute right-2 sm:right-3.5 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition z-10">
                        <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                    </button>

                    <!-- Chấm Chỉ Báo Slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                        <button type="button" class="banner-dot w-6 h-2 rounded-full bg-brand-accent transition-all" data-slide="0" aria-label="Chuyển tới banner 1"></button>
                        <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" data-slide="1" aria-label="Chuyển tới banner 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 2: GIỚI THIỆU NHÔM KÍNH NAM LONG (THEO MẪU FLATSOME 2 CỘT) -->
        <!-- ================================================================== -->
        <section id="gioi-thieu" class="py-10 sm:py-12 bg-white border-b border-slate-100">
            <div class="nl-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-7 space-y-3.5">
                        <div class="text-xs font-bold uppercase tracking-wider text-brand-accent">
                            Về chúng tôi
                        </div>
                        <h2 class="text-xl sm:text-2xl font-extrabold text-brand-primary leading-snug">
                            CÔNG TY CỬA NHÔM XINGFA ĐÀ NẴNG – NHÔM KÍNH NAM LONG
                        </h2>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            <strong>Nhôm Kính Nam Long</strong> là đơn vị chuyên thiết kế, gia công và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Các dòng sản phẩm chủ lực bao gồm: <em>Cửa nhôm Xingfa nhập khẩu tem đỏ, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính</em>.
                        </p>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Với phương châm <strong>“Cửa đẹp cho mọi công trình”</strong>, Nam Long cam kết sử dụng vật tư chính hãng, kỹ thuật lắp đặt chuẩn xác, thẩm mỹ tinh tế cùng chính sách bảo hành minh bạch và giá thành tối ưu trực tiếp tại xưởng.
                        </p>
                    </div>

                    <!-- 4 Thông Số Uy Tín (Flatsome 2x2 Counter Grid) -->
                    <div class="lg:col-span-5 grid grid-cols-2 gap-3.5 sm:gap-4">
                        <div class="bg-brand-surface border border-slate-200/80 rounded-xl p-4 sm:p-5 text-center">
                            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">150+</div>
                            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Dự án hoàn thành</div>
                        </div>
                        <div class="bg-brand-surface border border-slate-200/80 rounded-xl p-4 sm:p-5 text-center">
                            <div class="text-2xl sm:text-3xl font-extrabold text-brand-accent">50+</div>
                            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Kỹ thuật viên lành nghề</div>
                        </div>
                        <div class="bg-brand-surface border border-slate-200/80 rounded-xl p-4 sm:p-5 text-center">
                            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100+</div>
                            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Mẫu cửa chính hãng</div>
                        </div>
                        <div class="bg-brand-surface border border-slate-200/80 rounded-xl p-4 sm:p-5 text-center">
                            <div class="text-2xl sm:text-3xl font-extrabold text-brand-accent">100%</div>
                            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Khách hàng hài lòng</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 3: DANH MỤC SẢN PHẨM NỔI BẬT (6 DANH MỤC - CHỮ NHỎ GỌN)    -->
        <!-- ================================================================== -->
        <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-brand-surface">
            <div class="nl-container">
                <div class="text-center mb-7">
                    <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold text-brand-primary uppercase">
                        DANH MỤC SẢN PHẨM NỔI BẬT
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-1.5">
                        Đa dạng hệ cửa nhôm kính chất lượng cao phù hợp nhà phố, biệt thự và khách sạn
                    </p>
                </div>

                <!-- 6 Danh mục sản phẩm chính: 2 cột trên mobile, 3 cột tablet, 6 cột desktop -->
                <div id="category-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                    <!-- Được render từ dữ liệu danh mục chuẩn ở phần script -->
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 4: BÁO GIÁ & SẢN PHẨM CỬA NHÔM XINGFA (2 CỘT TRÊN MOBILE)   -->
        <!-- Có Giá & Giảm Giá % Góc Trên Bên Trái Sản Phẩm, Không Tràn Chữ     -->
        <!-- ================================================================== -->
        <section id="san-pham-xingfa" class="py-10 sm:py-14 bg-white">
            <div class="nl-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold text-brand-primary uppercase">
                        BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-1.5">
                        Thanh nhôm Xingfa nhập khẩu chính hãng hệ 55/93 – Giá ưu đãi trực tiếp từ xưởng
                    </p>
                </div>

                <!-- Thanh Lọc Nhanh Gọn Đẹp -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
                    <button type="button" data-filter="all" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition">
                        Tất cả sản phẩm
                    </button>
                    <button type="button" data-filter="mo-quay" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">
                        Cửa đi mở quay
                    </button>
                    <button type="button" data-filter="xep-truot" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">
                        Cửa đi xếp trượt
                    </button>
                    <button type="button" data-filter="cua-so" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">
                        Cửa sổ mở hất
                    </button>
                </div>

                <!-- Lưới Sản Phẩm: 2 cột trên điện thoại, 3 cột trên máy tính -->
                <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
                    <!-- Được render đầy đủ 6 sản phẩm kèm giá & badge -% góc trên trái -->
                </div>

                <!-- Bảng Giá Tham Khảo Nhanh (Mục Báo Giá Chuẩn Web Mẫu) -->
                <div id="bao-gia" class="mt-10 bg-brand-surface border border-slate-200 rounded-2xl p-4 sm:p-6">
                    <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-4">
                        <div>
                            <h3 class="text-base sm:text-lg font-bold text-brand-primary">
                                Bảng Báo Giá Tham Khảo Nhôm Xingfa Quảng Đông Tem Đỏ
                            </h3>
                            <p class="text-xs text-slate-500">Đơn giá tính theo m², đã bao gồm kính an toàn 6.38mm &amp; công lắp đặt tại Đà Nẵng.</p>
                        </div>
                        <a href="#form-bao-gia" class="inline-flex items-center justify-center bg-brand-accent hover:bg-brand-accentHover text-white text-xs font-bold px-4 py-2 rounded-lg transition self-start sm:self-auto">
                            Yêu cầu báo giá chi tiết
                        </a>
                    </div>
                    <div class="overflow-x-auto rounded-xl border border-slate-200 bg-white">
                        <table class="w-full text-left border-collapse text-xs sm:text-sm">
                            <thead>
                                <tr class="bg-brand-primary text-white">
                                    <th class="py-2.5 px-3 sm:px-4 font-semibold">Hạng mục hệ cửa</th>
                                    <th class="py-2.5 px-3 sm:px-4 font-semibold">Hệ nhôm / Độ dày</th>
                                    <th class="py-2.5 px-3 sm:px-4 font-semibold text-right">Đơn giá (VNĐ/m²)</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-slate-100 text-slate-700">
                                <tr class="hover:bg-slate-50">
                                    <td class="py-2.5 px-3 sm:px-4 font-medium">Cửa sổ mở quay / mở hất nhôm Xingfa</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-slate-500">Hệ 55 – Dày 1.4mm</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-brand-accent">1.690.000 ₫</td>
                                </tr>
                                <tr class="hover:bg-slate-50">
                                    <td class="py-2.5 px-3 sm:px-4 font-medium">Cửa đi mở quay 1, 2, 3, 4 cánh nhôm Xingfa</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-slate-500">Hệ 55 – Dày 2.0mm</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-brand-accent">1.800.000 – 2.100.000 ₫</td>
                                </tr>
                                <tr class="hover:bg-slate-50">
                                    <td class="py-2.5 px-3 sm:px-4 font-medium">Cửa đi mở xếp trượt nhôm Xingfa 4 – 6 cánh</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-slate-500">Hệ 63 – Dày 2.0mm</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-brand-accent">2.100.000 ₫</td>
                                </tr>
                                <tr class="hover:bg-slate-50">
                                    <td class="py-2.5 px-3 sm:px-4 font-medium">Cửa kính cường lực, phòng tắm kính, cầu thang kính</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-slate-500">Kính tôi 10mm – 12mm</td>
                                    <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-brand-primary">Liên hệ khảo sát</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 5: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 CÔNG TRÌNH THỰC TẾ)  -->
        <!-- ================================================================== -->
        <section id="cong-trinh" class="py-10 sm:py-14 bg-brand-surface border-t border-slate-200/70">
            <div class="nl-container">
                <div class="text-center mb-7">
                    <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold text-brand-primary uppercase">
                        CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-1.5">
                        Những công trình khách sạn, resort và nhà phố tiêu biểu do Nhôm Kính Nam Long thi công
                    </p>
                </div>

                <!-- 6 Dự án tại Đà Nẵng: 1 cột mobile nhỏ / 2 cột mobile ngang / 3 cột desktop -->
                <div id="project-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6">
                    <!-- Render 6 dự án Đà Nẵng từ danh sách Google Drive -->
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 6: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY TRÊN TRANG CHỦ       -->
        <!-- ================================================================== -->
        <section id="form-bao-gia" class="py-10 sm:py-14 bg-brand-primary text-white">
            <div class="nl-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <!-- Cột Trái: Thông tin cam kết -->
                    <div class="lg:col-span-5 space-y-4">
                        <p class="text-xs font-bold uppercase tracking-widest text-amber-400">
                            Đăng ký nhận báo giá miễn phí
                        </p>
                        <h2 class="text-xl sm:text-3xl font-extrabold leading-snug">
                            YÊU CẦU TƯ VẤN &amp; BÁO GIÁ TRỌN GÓI TẠI CÔNG TRÌNH
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                            Để lại thông tin hạng mục cửa cần thi công. Kỹ thuật viên Nhôm Kính Nam Long sẽ liên hệ tư vấn mẫu mã, đo đạc miễn phí và gửi bảng dự toán chi tiết trong vòng 15 phút.
                        </p>
                        <ul class="space-y-2.5 text-xs sm:text-sm text-slate-100 pt-1">
                            <li class="flex items-start gap-2.5">
                                <svg class="w-4 h-4 text-amber-400 mt-0.5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
                                <span>Khảo sát thực tế, đo đạc kích thước chuẩn xác hoàn toàn miễn phí</span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <svg class="w-4 h-4 text-amber-400 mt-0.5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
                                <span>Sản phẩm nhôm Xingfa &amp; phụ kiện chính hãng, bảo hành dài hạn</span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <svg class="w-4 h-4 text-amber-400 mt-0.5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
                                <span>Hotline hỗ trợ trực tiếp: <a href="tel:0905160887" class="font-bold text-amber-400 hover:underline">0905.160.887</a></span>
                            </li>
                        </ul>
                    </div>

                    <!-- Cột Phải: Form Nhập Liệu Gọn Đẹp -->
                    <div class="lg:col-span-7">
                        <form id="quote-form" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                    <input id="q-name" type="text" required placeholder="Nhập họ tên của anh/chị" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                </div>
                                <div>
                                    <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                                    <input id="q-phone" type="tel" required placeholder="Ví dụ: 0905.xxx.xxx" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                </div>
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="q-category" class="block text-xs font-semibold text-slate-700 mb-1.5">Hạng mục cần báo giá</label>
                                    <select id="q-category" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                        <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                                        <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                        <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                        <option value="Cửa kính tự động">Cửa kính tự động</option>
                                        <option value="Cầu thang kính">Cầu thang kính</option>
                                        <option value="Kính ốp bếp">Kính ốp bếp</option>
                                        <option value="Phòng tắm kính">Phòng tắm kính</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-address" class="block text-xs font-semibold text-slate-700 mb-1.5">Khu vực công trình</label>
                                    <input id="q-address" type="text" placeholder="Quận/Huyện tại Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                                </div>
                            </div>
                            <div>
                                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1.5">Ghi chú kích thước / Yêu cầu thêm</label>
                                <textarea id="q-note" rows="3" placeholder="Ví dụ: Cần báo giá bộ cửa đi 4 cánh Xingfa màu xám ghi, diện tích khoảng 12m2..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm py-3 rounded-lg shadow transition flex items-center justify-center gap-2">
                                <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3"/></svg>
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 7: DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ       -->
        <!-- ================================================================== -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
            <div class="nl-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold text-brand-primary uppercase">
                        TIN TỨC &amp; KINH NGHIỆM CHỌN CỬA
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-1.5">
                        Kiến thức hữu ích về cửa nhôm Xingfa, kính cường lực và bảo quản nội thất nhôm kính
                    </p>
                </div>

                <!-- Danh mục bài viết gọn đẹp -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
                    <button type="button" data-article-cat="all" class="article-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition">Tất cả bài viết</button>
                    <button type="button" data-article-cat="tu-van" class="article-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Tư vấn chọn cửa</button>
                    <button type="button" data-article-cat="bao-gia" class="article-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Báo giá &amp; Vật tư</button>
                    <button type="button" data-article-cat="kinh-nghiem" class="article-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Kinh nghiệm thi công</button>
                </div>

                <div id="article-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                    <!-- Render danh sách bài viết -->
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 8: ĐỐI TÁC CỦA CHÚNG TÔI (6 LOGO ĐỐI TÁC CHÍNH HÃNG)       -->
        <!-- ================================================================== -->
        <section aria-label="Đối tác của chúng tôi" class="py-10 bg-brand-surface border-t border-slate-200/70">
            <div class="nl-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-heading text-base sm:text-xl font-extrabold text-brand-primary uppercase">
                        ĐỐI TÁC CỦA CHÚNG TÔI
                    </h2>
                </div>
                <div id="partner-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
                    <!-- Render 6 logo đối tác từ Google Drive -->
                </div>
            </div>
        </section>

        <!-- ================================================================== -->
        <!-- SECTION 9: BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ    -->
        <!-- ================================================================== -->
        <section id="lien-he" class="py-10 sm:py-14 bg-white border-t border-slate-200/70">
            <div class="nl-container">
                <div class="text-center mb-7">
                    <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold text-brand-primary uppercase">
                        BẢN ĐỒ CHỈ ĐƯỜNG &amp; FANPAGE NAM LONG
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-1.5">
                        Ghé xưởng sản xuất &amp; showroom tại 123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- CỘT TRÁI: GOOGLE MAPS NHÚNG TRỰC TIẾP RA NGOÀI TRANG CHỦ -->
                    <div class="lg:col-span-7 bg-brand-surface rounded-2xl border border-slate-200 overflow-hidden flex flex-col">
                        <div class="px-4 py-3 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-brand-primary">
                                <svg class="w-4 h-4 text-brand-accent shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                                <span>123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng</span>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=123+%C3%94ng+%C3%8Dch+%C4%90%C6%B0%E1%BB%9Dng,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-accent hover:underline">
                                Mở Google Maps &rarr;
                            </a>
                        </div>
                        <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-200">
                            <iframe
                                title="Bản đồ Nhôm Kính Nam Long - 123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng"
                                src="https://maps.google.com/maps?q=123%20%C3%94ng%20%C3%8Dch%20%C4%90%C6%B0%E1%BB%9Dng,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>

                    <!-- CỘT PHẢI: FANPAGE FACEBOOK NGOÀI TRANG CHỦ -->
                    <div class="lg:col-span-5 bg-brand-surface rounded-2xl border border-slate-200 overflow-hidden flex flex-col">
                        <div class="px-4 py-3 bg-white border-b border-slate-200 flex items-center justify-between">
                            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-[#1877F2]">
                                <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
                                <span>Fanpage Facebook Chính Thức</span>
                            </div>
                            <span class="text-[11px] font-medium text-emerald-600">Đang hoạt động</span>
                        </div>

                        <!-- Khung Fanpage Facebook trực quan (Tương thích tốt không bị chặn trình duyệt) -->
                        <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                            <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                                <!-- Ảnh bìa Fanpage -->
                                <div class="relative h-32 bg-gradient-to-r from-brand-dark via-brand-primary to-sky-800 overflow-hidden">
                                    <img
                                        src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w800"
                                        data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                                        alt="Ảnh bìa Fanpage Nhôm Kính Nam Long"
                                        class="w-full h-full object-cover opacity-55"
                                        onerror="handleDriveFallback(this, 'Nhôm Kính Nam Long')"
                                    >
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <!-- Logo Avatar nhỏ gọn -->
                                        <div class="w-12 h-12 rounded-xl bg-white p-1 shadow shrink-0 flex items-center justify-center">
                                            <svg class="w-10 h-10" viewBox="0 0 48 48" fill="none">
                                                <rect x="2" y="2" width="44" height="44" rx="10" fill="#0B3B66"/>
                                                <rect x="7" y="7" width="34" height="34" rx="6" stroke="#D97706" stroke-width="2"/>
                                                <path d="M13 33V15L23 28V15" stroke="#FFFFFF" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
                                                <path d="M27.5 15V33H35.5" stroke="#F59E0B" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
                                            </svg>
                                        </div>
                                        <div class="text-white min-w-0">
                                            <div class="font-bold text-sm leading-tight truncate">Nhôm Kính Nam Long - Đà Nẵng</div>
                                            <div class="text-[11px] text-slate-200 mt-0.5">4.850 lượt thích • 5.120 người theo dõi</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Thanh thao tác Fanpage -->
                                <div class="p-3.5 space-y-3">
                                    <p class="text-xs text-slate-600 leading-relaxed">
                                        Cập nhật liên tục hình ảnh thi công thực tế cửa nhôm Xingfa, cầu thang kính, phòng tắm kính và các chương trình ưu đãi tại Đà Nẵng.
                                    </p>
                                    <div class="grid grid-cols-2 gap-2.5">
                                        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 bg-[#1877F2] hover:bg-[#1664cc] text-white text-xs font-bold py-2 px-3 rounded-lg transition">
                                            <svg class="w-3.5 h-3.5 fill-current" viewBox="0 0 24 24"><path d="M14 9V5a3 3 0 00-3-3l-4 9v11h11.28a2 2 0 002-1.7l1.38-9a2 2 0 00-2-2.3H14zM7 22H4a2 2 0 01-2-2v-7a2 2 0 012-2h3"/></svg>
                                            <span>Thích Trang</span>
                                        </a>
                                        <a href="https://zalo.me/0905160887" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 bg-slate-100 hover:bg-slate-200 text-slate-800 text-xs font-bold py-2 px-3 rounded-lg transition">
                                            <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"/></svg>
                                            <span>Nhắn Tin Tư Vấn</span>
                                        </a>
                                    </div>
                                </div>
                            </div>

                            <!-- Bài đăng mới nhất mini trên Fanpage -->
                            <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center gap-3">
                                <img
                                    src="https://drive.google.com/thumbnail?id=1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-&sz=w400"
                                    data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                                    alt="Công trình bàn giao cửa nhôm Xingfa"
                                    class="w-16 h-14 object-cover rounded-lg shrink-0 bg-slate-100"
                                    onerror="handleDriveFallback(this, 'Xingfa')"
                                >
                                <div class="min-w-0 text-xs">
                                    <div class="font-bold text-slate-800 leading-snug">Bàn giao trọn bộ cửa đi mở quay 4 cánh Xingfa tại Cẩm Lệ</div>
                                    <div class="text-[11px] text-slate-500 mt-0.5">Nhôm Kính Nam Long • 0905.160.887</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ====================================================================== -->
    <!-- FOOTER CHUẨN FLATSOME 4 CỘT (MÀU THEO LOGO)                            -->
    <!-- ====================================================================== -->
    <footer class="bg-brand-dark text-slate-300 pt-10 pb-6 border-t-4 border-brand-accent">
        <div class="nl-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2">
                        <svg class="w-8 h-8 shrink-0" viewBox="0 0 48 48" fill="none">
                            <rect x="2" y="2" width="44" height="44" rx="10" fill="#0B3B66"/>
                            <rect x="7" y="7" width="34" height="34" rx="6" stroke="#D97706" stroke-width="2"/>
                            <path d="M13 33V15L23 28V15" stroke="#FFFFFF" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M27.5 15V33H35.5" stroke="#F59E0B" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <div class="font-extrabold text-white text-sm tracking-tight">NHÔM KÍNH NAM LONG</div>
                    </div>
                    <p class="text-xs leading-relaxed text-slate-300">
                        Chuyên sản xuất, gia công và lắp đặt cửa nhôm Xingfa chính hãng, cửa kính cường lực, cầu thang kính, phòng tắm kính uy tín hàng đầu tại Đà Nẵng.
                    </p>
                    <ul class="text-xs space-y-1.5 text-slate-200">
                        <li><strong>Địa chỉ:</strong> 123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng</li>
                        <li><strong>Hotline:</strong> <a href="tel:0905160887" class="text-amber-400 font-bold hover:underline">0905.160.887</a></li>
                        <li><strong>Website:</strong> nhomkinhnamlong.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h3 class="text-xs font-bold uppercase tracking-wider text-white mb-3.5 pb-1.5 border-b border-white/15 inline-block">
                        Cửa Nhôm Xingfa
                    </h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('1 cánh')" class="hover:text-amber-400 transition">Cửa nhôm xingfa 1 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('2 cánh')" class="hover:text-amber-400 transition">Cửa nhôm xingfa 2 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('3 cánh')" class="hover:text-amber-400 transition">Cửa nhôm xingfa 3 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('4 cánh')" class="hover:text-amber-400 transition">Cửa nhôm xingfa 4 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('xếp trượt')" class="hover:text-amber-400 transition">Cửa nhôm xingfa 5 cánh / Xếp trượt</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h3 class="text-xs font-bold uppercase tracking-wider text-white mb-3.5 pb-1.5 border-b border-white/15 inline-block">
                        Danh Mục Sản Phẩm
                    </h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-xingfa" class="hover:text-amber-400 transition">Cửa nhôm Xingfa Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-400 transition">Cửa kính cường lực Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-400 transition">Cửa nhựa lõi thép</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-400 transition">Cửa kính tự động</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-400 transition">Cầu thang kính &amp; Kính ốp bếp</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-400 transition">Phòng tắm kính cao cấp</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh -->
                <div>
                    <h3 class="text-xs font-bold uppercase tracking-wider text-white mb-3.5 pb-1.5 border-b border-white/15 inline-block">
                        Hỗ Trợ Khách Hàng
                    </h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition">Bảng báo giá cửa nhôm Xingfa</a></li>
                        <li><a href="#cong-trinh" class="hover:text-amber-400 transition">Dự án thi công tại Đà Nẵng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-400 transition">Tin tức &amp; Tư vấn kỹ thuật</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-400 transition">Đăng ký khảo sát miễn phí</a></li>
                        <li><a href="#lien-he" class="hover:text-amber-400 transition">Bản đồ &amp; Fanpage chính thức</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <div>Copyright 2026 © Bản quyền thuộc về <strong class="text-white">Nhôm Kính Nam Long</strong> (nhomkinhnamlong.com)</div>
                <div>Địa chỉ: 123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng</div>
            </div>
        </div>
    </footer>

    <!-- ====================================================================== -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (PC & MOBILE)         -->
    <!-- ====================================================================== -->
    <div class="fixed right-3 bottom-4 sm:right-5 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Lên đầu trang (Hiện khi cuộn xuống) -->
        <button id="scroll-top-btn" type="button" aria-label="Lên đầu trang" class="hidden w-10 h-10 rounded-full bg-slate-700/90 hover:bg-brand-primary text-white shadow-lg items-center justify-center transition">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 15l7-7 7 7"/></svg>
        </button>

        <!-- Nút Facebook Nổi Bật -->
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook Nhôm Kính Nam Long" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1464cc] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
            <span class="hidden sm:inline text-xs font-bold pr-0.5">Facebook</span>
        </a>

        <!-- Nút Zalo Nổi Bật -->
        <a href="https://zalo.me/0905160887" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo Nhôm Kính Nam Long" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055d4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-0.5">Chat Zalo</span>
        </a>

        <!-- Nút Hotline Nổi Bật -->
        <a href="tel:0905160887" aria-label="Gọi Hotline 0905.160.887" class="btn-pulse-hotline flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white rounded-full shadow-xl px-3.5 py-2.5 transition">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span class="text-xs sm:text-sm font-extrabold tracking-tight">0905.160.887</span>
        </a>
    </div>

    <!-- ====================================================================== -->
    <!-- MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT & HỘP THÔNG BÁO (KHÔNG ALERT)   -->
    <!-- ====================================================================== -->
    <div id="info-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/60 p-4">
        <div class="bg-white rounded-2xl max-w-lg w-full max-h-[88vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-100 sticky top-0 bg-white">
                <h3 id="modal-title" class="text-sm sm:text-base font-bold text-brand-primary pr-3">Chi tiết</h3>
                <button id="modal-close" type="button" aria-label="Đóng cửa sổ" class="p-1.5 rounded-lg text-slate-400 hover:text-slate-700 hover:bg-slate-100 transition">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div id="modal-body" class="p-5 text-sm text-slate-600 space-y-4"></div>
        </div>
    </div>

    <!-- Thông báo nổi Toast -->
    <div id="toast-box" class="fixed top-5 right-4 z-50 hidden max-w-xs sm:max-w-sm bg-emerald-600 text-white text-xs sm:text-sm font-medium px-4 py-3 rounded-xl shadow-xl"></div>

    <!-- ====================================================================== -->
    <!-- JAVASCRIPT: DỮ LIỆU THỰC TẾ, SLIDER, BỘ LỌC & TƯƠNG TÁC                -->
    <!-- ====================================================================== -->
    <script>
        /**
         * Hàm tạo URL ảnh Google Drive tối ưu độ ổn định cao
         * Tự động fallback qua lh3.googleusercontent.com và ảnh thay thế placehold.co nếu Drive giới hạn băng thông
         */
        function getDriveImgUrl(id, size = 1000) {
            return `https://drive.google.com/thumbnail?id=${id}&sz=w${size}`;
        }

        function handleDriveFallback(imgEl, label) {
            try {
                const attempt = parseInt(imgEl.dataset.retry || '0', 10);
                const driveId = imgEl.dataset.driveId;
                if (attempt === 0 && driveId) {
                    imgEl.dataset.retry = '1';
                    imgEl.src = `https://lh3.googleusercontent.com/d/${driveId}=w1000`;
                } else {
                    imgEl.onerror = null;
                    const text = encodeURIComponent(label || 'Nhôm Kính Nam Long');
                    imgEl.src = `https://placehold.co/600x450/0B3B66/FFFFFF?text=${text}`;
                }
            } catch (e) {
                imgEl.onerror = null;
            }
        }

        /* ------------------------------------------------------------------ */
        /* 1. DỮ LIỆU 6 DANH MỤC SẢN PHẨM (KHỚP 100% ẢNH DRIVE & WEB MẪU)     */
        /* ------------------------------------------------------------------ */
        const categoriesData = [
            { name: 'Cửa nhôm Xingfa', driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', target: '#san-pham-xingfa' },
            { name: 'Cửa nhựa lõi thép', driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA', target: '#form-bao-gia' },
            { name: 'Cửa tự động', driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ', target: '#form-bao-gia' },
            { name: 'Cầu thang kính', driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul', target: '#form-bao-gia' },
            { name: 'Kính ốp bếp', driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb', target: '#form-bao-gia' },
            { name: 'Phòng tắm kính', driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH', target: '#form-bao-gia' }
        ];

        /* ------------------------------------------------------------------ */
        /* 2. DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA KÈM GIÁ & GIẢM GIÁ %         */
        /* ------------------------------------------------------------------ */
        const productsData = [
            {
                id: 1,
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                category: 'mo-quay',
                driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                originalPrice: '2.450.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-14%',
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm nhập khẩu, kính an toàn 6.38mm, phụ kiện Kinlong đồng bộ, gioăng kép EPDM kín khít.'
            },
            {
                id: 2,
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                category: 'mo-quay',
                driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                originalPrice: '2.500.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-16%',
                specs: 'Thiết kế 2 cánh mở quay sang trọng cho cửa mặt tiền hoặc ban công. Nhôm hệ 55 sơn tĩnh điện bền màu ngoài trời.'
            },
            {
                id: 3,
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                category: 'mo-quay',
                driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                originalPrice: '2.480.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-15%',
                specs: 'Giải pháp tối ưu cho nhà phố có mặt tiền vừa phải, mở rộng không gian tối đa, khóa đa điểm chống trộm an toàn.'
            },
            {
                id: 4,
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                category: 'mo-quay',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                originalPrice: '2.550.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-18%',
                specs: 'Cửa chính 4 cánh mặt tiền đẳng cấp, chịu áp lực gió bão lên đến 1600 Pascal, ép góc CNC kín khít tuyệt đối.'
            },
            {
                id: 5,
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                category: 'xep-truot',
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                originalPrice: '2.600.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-19%',
                specs: 'Hệ cửa xếp trượt gấp gọn (4, 5, 6 cánh) giúp mở rộng 100% lối đi cho biệt thự, sân vườn, showroom và resort.'
            },
            {
                id: 6,
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                category: 'cua-so',
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                originalPrice: '2.400.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-12%',
                specs: 'Cửa sổ mở hất góc 45 độ chắn mưa hắt cực tốt, thanh chống gió inox 304 chắc chắn, phù hợp khí hậu miền Trung.'
            }
        ];

        /* ------------------------------------------------------------------ */
        /* 3. DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG                           */
        /* ------------------------------------------------------------------ */
        const projectsData = [
            {
                title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
                location: 'Quảng Nam – Đà Nẵng',
                driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
                desc: 'Thi công toàn bộ hệ cửa nhôm Xingfa vân gỗ & vách kính cường lực chịu lực cho khu nghỉ dưỡng 4 sao.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
                location: 'Đà Nẵng',
                driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
                desc: 'Lắp đặt mặt dựng kính, cửa đi ban công nhôm Xingfa cách âm chuẩn khách sạn biển.'
            },
            {
                title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
                location: 'Đà Nẵng',
                driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
                desc: 'Cung cấp và lắp đặt đồng bộ cửa nhôm Xingfa, phòng tắm kính cường lực 10mm cho toàn bộ phòng lưu trú.'
            },
            {
                title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
                location: 'Sơn Trà, Đà Nẵng',
                driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
                desc: 'Hạng mục cửa kính tự động sảnh chính, hệ cửa sổ chống gió bão ven biển Mỹ Khê.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
                location: 'Đà Nẵng',
                driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
                desc: 'Thi công hoàn thiện hệ vách kính mặt tiền, cửa đi nhôm Xingfa hệ 55 và lan can kính cường lực.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
                location: 'Đà Nẵng',
                driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
                desc: 'Giải pháp nhôm kính kiến trúc hiện đại, cách âm tối ưu cho không gian nghỉ dưỡng cao cấp.'
            }
        ];

        /* ------------------------------------------------------------------ */
        /* 4. DỮ LIỆU 6 LOGO ĐỐI TÁC                                          */
        /* ------------------------------------------------------------------ */
        const partnersData = [
            { name: 'Đối tác Nhôm Xingfa', driveId: '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk' },
            { name: 'Đối tác Phụ kiện Kinlong', driveId: '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq' },
            { name: 'Đối tác Kính an toàn', driveId: '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn' },
            { name: 'Đối tác Bản lề VVP', driveId: '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT' },
            { name: 'Đối tác Cửa tự động', driveId: '1SDcarhnX0yypmqdbawICjYBRtFnKngn-' },
            { name: 'Đối tác Phụ kiện cao cấp', driveId: '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg' }
        ];

        /* ------------------------------------------------------------------ */
        /* 5. DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ                            */
        /* ------------------------------------------------------------------ */
        const articlesData = [
            {
                id: 1,
                cat: 'tu-van',
                catLabel: 'Tư vấn chọn cửa',
                date: '18/11/2026',
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu miền Trung không?',
                driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                excerpt: 'Với kết cấu khoang rỗng gân tăng cứng và sơn tĩnh điện chống ăn mòn muối biển, cửa nhôm Xingfa là lựa chọn bền bỉ hàng đầu tại Đà Nẵng.',
                content: 'Đà Nẵng và khu vực miền Trung có khí hậu nắng nóng gay gắt kèm gió bão ven biển. Cửa nhôm Xingfa nhập khẩu chính hãng có độ dày 1.4mm - 2.0mm, bề mặt sơn tĩnh điện cao cấp chống oxy hóa, kết hợp gioăng EPDM kép giúp ngăn nước mưa tuyệt đối và chịu áp lực gió lên đến 1600 Pascal.'
            },
            {
                id: 2,
                cat: 'bao-gia',
                catLabel: 'Báo giá & Vật tư',
                date: '14/11/2026',
                title: 'Cách phân biệt nhôm Xingfa nhập khẩu tem đỏ và hàng gia công',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                excerpt: 'Hướng dẫn kiểm tra tem mã QR, độ dày mặt cắt thanh profile nhôm và ánh kim lớp mạ Crom bên trong để chọn đúng hàng chính hãng.',
                content: 'Nhôm Xingfa Quảng Đông tem đỏ chính hãng có màu chữ tem sắc nét, mã QR quét ra thông tin nhà máy, lõi bên trong có ánh cầu vồng của lớp mạ Crom chống oxy hóa. Khi lắp đặt cùng phụ kiện Kinlong đồng bộ và keo silicon trung tính, cửa vận hành cực kỳ êm ái và bền trên 20 năm.'
            },
            {
                id: 3,
                cat: 'kinh-nghiem',
                catLabel: 'Kinh nghiệm thi công',
                date: '09/11/2026',
                title: 'Nên chọn cửa mở quay hay cửa xếp trượt cho mặt tiền nhà phố?',
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                excerpt: 'So sánh ưu nhược điểm về độ kín khít, diện tích thông thủy và chi phí giữa hệ cửa đi mở quay 4 cánh và cửa xếp trượt.',
                content: 'Cửa đi mở quay 4 cánh hệ 55 có độ kín khít cao, dễ sử dụng hằng ngày và giá thành tối ưu. Trong khi đó, cửa xếp trượt hệ 63 phù hợp các mặt tiền rộng từ 3.5m trở lên cần mở trọn 100% không gian cho xe ô tô ra vào hoặc kết nối sân vườn.'
            },
            {
                id: 4,
                cat: 'tu-van',
                catLabel: 'Tư vấn chọn cửa',
                date: '02/11/2026',
                title: 'Kinh nghiệm làm phòng tắm kính & cầu thang kính an toàn, sang trọng',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                excerpt: 'Lựa chọn độ dày kính cường lực 10mm - 12mm cùng bộ phụ kiện inox 304 chống gỉ giúp không gian luôn sáng bóng như mới.',
                content: 'Đối với phòng tắm kính, nên sử dụng kính cường lực 10mm kết hợp bản lề và tay nắm Inox 304 chuẩn để tránh hoen gỉ trong môi trường ẩm ướt. Đối với cầu thang kính, kính 10mm - 12mm cùng trụ kẹp chắc chắn giúp ngôi nhà thoáng rộng và hiện đại hơn.'
            }
        ];

        /* ------------------------------------------------------------------ */
        /* RENDER DANH MỤC SẢN PHẨM                                           */
        /* ------------------------------------------------------------------ */
        function renderCategories() {
            const container = document.getElementById('category-grid');
            container.innerHTML = categoriesData.map(cat => `
                <a href="${cat.target}" onclick="selectCategoryQuote('${cat.name}')" class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary/40 transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImgUrl(cat.driveId, 700)}"
                            data-drive-id="${cat.driveId}"
                            alt="${cat.name}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                            onerror="handleDriveFallback(this, '${cat.name}')"
                        >
                    </div>
                    <div class="px-2.5 py-2.5 text-center flex-1 flex items-center justify-center">
                        <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-primary group-hover:text-brand-accent transition leading-snug">
                            ${cat.name}
                        </h3>
                    </div>
                </a>
            `).join('');
        }

        /* ------------------------------------------------------------------ */
        /* RENDER SẢN PHẨM (2 CỘT TRÊN MOBILE, GIÁ & -% GÓC TRÊN TRÁI)        */
        /* ------------------------------------------------------------------ */
        function renderProducts(list) {
            const container = document.getElementById('product-grid');
            if (!list.length) {
                container.innerHTML = `
                    <div class="col-span-full text-center py-8 text-sm text-slate-500 bg-slate-50 rounded-xl border border-slate-200">
                        Không tìm thấy sản phẩm phù hợp. <button type="button" onclick="resetProductFilter()" class="text-brand-primary font-bold underline ml-1">Xem tất cả sản phẩm</button>
                    </div>
                `;
                return;
            }
            container.innerHTML = list.map(p => `
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary/35 transition flex flex-col">
                    <!-- Ảnh Sản Phẩm + Nhãn Giảm Giá % Góc Trên Bên Trái -->
                    <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <span class="absolute top-2 left-2 z-10 bg-red-600 text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded-md shadow">
                            ${p.discount}
                        </span>
                        <img
                            src="${getDriveImgUrl(p.driveId, 800)}"
                            data-drive-id="${p.driveId}"
                            alt="${p.name}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300 cursor-pointer"
                            onclick="openProductModal(${p.id})"
                            onerror="handleDriveFallback(this, '${p.name}')"
                        >
                    </div>

                    <!-- Thông tin sản phẩm: Tên đầy đủ, không cắt chữ, không tràn viền -->
                    <div class="p-2.5 sm:p-4 flex flex-col flex-1 justify-between gap-2.5">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary transition leading-snug break-words cursor-pointer" onclick="openProductModal(${p.id})">
                            ${p.name}
                        </h3>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2.5">
                                <span class="text-xs sm:text-base font-extrabold text-brand-accent">${p.salePrice}</span>
                                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.originalPrice}</span>
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 sm:gap-2">
                                <button type="button" onclick="openProductModal(${p.id})" class="w-full py-1.5 px-2 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-light text-[11.5px] sm:text-xs font-semibold transition">
                                    Xem chi tiết
                                </button>
                                <button type="button" onclick="orderProductQuote('${p.name}')" class="w-full py-1.5 px-2 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-[11.5px] sm:text-xs font-semibold transition">
                                    Báo giá ngay
                                </button>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* ------------------------------------------------------------------ */
        /* RENDER 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG                               */
        /* ------------------------------------------------------------------ */
        function renderProjects() {
            const container = document.getElementById('project-grid');
            container.innerHTML = projectsData.map(proj => `
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImgUrl(proj.driveId, 900)}"
                            data-drive-id="${proj.driveId}"
                            alt="${proj.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                            onerror="handleDriveFallback(this, '${proj.title}')"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-brand-accent uppercase tracking-wide mb-1">${proj.location}</div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-primary leading-snug">
                                ${proj.title}
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">${proj.desc}</p>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* ------------------------------------------------------------------ */
        /* RENDER 6 LOGO ĐỐI TÁC                                              */
        /* ------------------------------------------------------------------ */
        function renderPartners() {
            const container = document.getElementById('partner-grid');
            container.innerHTML = partnersData.map(pt => `
                <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-primary/30 transition">
                    <img
                        src="${getDriveImgUrl(pt.driveId, 500)}"
                        data-drive-id="${pt.driveId}"
                        alt="${pt.name}"
                        loading="lazy"
                        class="max-h-full max-w-full object-contain"
                        onerror="handleDriveFallback(this, '${pt.name}')"
                    >
                </div>
            `).join('');
        }

        /* ------------------------------------------------------------------ */
        /* RENDER BÀI VIẾT / TIN TỨC TRANG CHỦ                                */
        /* ------------------------------------------------------------------ */
        function renderArticles(cat = 'all') {
            const container = document.getElementById('article-grid');
            const filtered = cat === 'all' ? articlesData : articlesData.filter(a => a.cat === cat);
            container.innerHTML = filtered.map(art => `
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openArticleModal(${art.id})">
                        <img
                            src="${getDriveImgUrl(art.driveId, 700)}"
                            data-drive-id="${art.driveId}"
                            alt="${art.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                            onerror="handleDriveFallback(this, 'Tin tức Nam Long')"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between gap-2.5">
                        <div>
                            <div class="flex items-center justify-between text-[11px] text-slate-500 mb-1.5">
                                <span class="font-semibold text-brand-accent">${art.catLabel}</span>
                                <span>${art.date}</span>
                            </div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug cursor-pointer" onclick="openArticleModal(${art.id})">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">${art.excerpt}</p>
                        </div>
                        <button type="button" onclick="openArticleModal(${art.id})" class="text-xs font-bold text-brand-primary hover:text-brand-accent inline-flex items-center gap-1 self-start transition">
                            <span>Đọc bài viết</span>
                            <span>&rarr;</span>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        /* ------------------------------------------------------------------ */
        /* TƯƠNG TÁC LỌC SẢN PHẨM, TÌM KIẾM & FORM BÁO GIÁ                    */
        /* ------------------------------------------------------------------ */
        function setActiveFilterBtn(filterKey) {
            document.querySelectorAll('.product-filter-btn').forEach(btn => {
                const isActive = btn.dataset.filter === filterKey;
                btn.classList.toggle('bg-brand-primary', isActive);
                btn.classList.toggle('text-white', isActive);
                btn.classList.toggle('bg-slate-100', !isActive);
                btn.classList.toggle('text-slate-700', !isActive);
            });
        }

        function resetProductFilter() {
            setActiveFilterBtn('all');
            renderProducts(productsData);
        }

        function filterProductsByKeyword(keyword) {
            const q = keyword.toLowerCase().trim();
            const matched = productsData.filter(p => p.name.toLowerCase().includes(q) || p.specs.toLowerCase().includes(q));
            setActiveFilterBtn('all');
            renderProducts(matched.length ? matched : productsData);
            if (!matched.length) {
                showToast(`Đang hiển thị các mẫu Cửa nhôm Xingfa liên quan đến "${keyword}".`);
            }
        }

        function selectCategoryQuote(categoryName) {
            const selectEl = document.getElementById('q-category');
            if (!selectEl) return;
            for (const opt of selectEl.options) {
                if (opt.value.toLowerCase().includes(categoryName.toLowerCase()) || categoryName.toLowerCase().includes(opt.value.toLowerCase())) {
                    selectEl.value = opt.value;
                    break;
                }
            }
        }

        function orderProductQuote(productName) {
            const noteEl = document.getElementById('q-note');
            if (noteEl) {
                noteEl.value = `Tôi cần tư vấn và báo giá chi tiết sản phẩm: ${productName}.`;
            }
            const formSection = document.getElementById('form-bao-gia');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
            closeModal();
        }

        /* ------------------------------------------------------------------ */
        /* MODAL CHI TIẾT SẢN PHẨM & BÀI VIẾT                                 */
        /* ------------------------------------------------------------------ */
        function openProductModal(id) {
            const p = productsData.find(item => item.id === id);
            if (!p) return;
            document.getElementById('modal-title').textContent = p.name;
            document.getElementById('modal-body').innerHTML = `
                <div class="relative rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <span class="absolute top-2.5 left-2.5 bg-red-600 text-white text-xs font-extrabold px-2.5 py-1 rounded-md shadow">${p.discount}</span>
                    <img src="${getDriveImgUrl(p.driveId, 900)}" data-drive-id="${p.driveId}" alt="${p.name}" class="w-full h-full object-cover" onerror="handleDriveFallback(this, '${p.name}')">
                </div>
                <div class="flex items-baseline gap-3">
                    <span class="text-xl font-extrabold text-brand-accent">${p.salePrice} / m²</span>
                    <span class="text-sm text-slate-400 line-through">${p.originalPrice}</span>
                </div>
                <p class="text-sm text-slate-600 leading-relaxed">${p.specs}</p>
                <div class="bg-brand-surface rounded-xl p-3.5 text-xs text-slate-700 space-y-1 border border-slate-200">
                    <div><strong>Đơn vị thi công:</strong> Nhôm Kính Nam Long – 123 Ông Ích Đường, Cẩm Lệ, Đà Nẵng</div>
                    <div><strong>Tư vấn nhanh:</strong> <a href="tel:0905160887" class="font-bold text-brand-primary">0905.160.887</a> (Zalo / Điện thoại)</div>
                </div>
                <div class="flex flex-wrap gap-2.5 pt-1">
                    <button type="button" onclick="orderProductQuote('${p.name}')" class="flex-1 bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-bold py-2.5 px-4 rounded-lg transition">
                        Nhận Báo Giá Chi Tiết
                    </button>
                    <a href="tel:0905160887" class="flex-1 text-center bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold py-2.5 px-4 rounded-lg transition">
                        Gọi 0905.160.887
                    </a>
                </div>
            `;
            openModal();
        }

        function openArticleModal(id) {
            const art = articlesData.find(item => item.id === id);
            if (!art) return;
            document.getElementById('modal-title').textContent = art.title;
            document.getElementById('modal-body').innerHTML = `
                <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img src="${getDriveImgUrl(art.driveId, 900)}" data-drive-id="${art.driveId}" alt="${art.title}" class="w-full h-full object-cover" onerror="handleDriveFallback(this, 'Tin tức Nam Long')">
                </div>
                <div class="flex items-center justify-between text-xs text-slate-500">
                    <span class="font-semibold text-brand-accent">${art.catLabel}</span>
                    <span>Ngày đăng: ${art.date}</span>
                </div>
                <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
                <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-2">
                    <span class="text-xs text-slate-500">Cần tư vấn kỹ thuật trực tiếp?</span>
                    <a href="#form-bao-gia" onclick="closeModal()" class="bg-brand-primary text-white text-xs font-bold px-4 py-2 rounded-lg hover:bg-brand-dark transition">Liên hệ Nam Long</a>
                </div>
            `;
            openModal();
        }

        function openModal() {
            const modal = document.getElementById('info-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeModal() {
            const modal = document.getElementById('info-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function showToast(message) {
            const toast = document.getElementById('toast-box');
            toast.textContent = message;
            toast.classList.remove('hidden');
            clearTimeout(window.__toastTimer);
            window.__toastTimer = setTimeout(() => {
                toast.classList.add('hidden');
            }, 4000);
        }

        /* ------------------------------------------------------------------ */
        /* BANNER AUTO-SLIDER (2 SLIDES KÍCH THƯỚC BẰNG NHAU + VUỐT MOBILE)   */
        /* ------------------------------------------------------------------ */
        let currentSlide = 0;
        const totalSlides = 2;
        let sliderTimer = null;

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            const track = document.getElementById('banner-track');
            if (track) {
                track.style.transform = `translateX(-${currentSlide * 100}%)`;
            }
            document.querySelectorAll('.banner-dot').forEach((dot, idx) => {
                if (idx === currentSlide) {
                    dot.classList.add('w-6', 'bg-brand-accent');
                    dot.classList.remove('w-2.5', 'bg-white/50');
                } else {
                    dot.classList.remove('w-6', 'bg-brand-accent');
                    dot.classList.add('w-2.5', 'bg-white/50');
                }
            });
        }

        function startAutoSlide() {
            clearInterval(sliderTimer);
            sliderTimer = setInterval(() => goToSlide(currentSlide + 1), 5000);
        }

        /* ------------------------------------------------------------------ */
        /* KHỞI TẠO TOÀN BỘ SỰ KIỆN KHI TRANG TẢI XONG                        */
        /* ------------------------------------------------------------------ */
        window.addEventListener('DOMContentLoaded', () => {
            renderCategories();
            renderProducts(productsData);
            renderProjects();
            renderPartners();
            renderArticles('all');
            startAutoSlide();

            // Điều khiển Banner Slider
            document.getElementById('banner-prev').addEventListener('click', () => {
                goToSlide(currentSlide - 1);
                startAutoSlide();
            });
            document.getElementById('banner-next').addEventListener('click', () => {
                goToSlide(currentSlide + 1);
                startAutoSlide();
            });
            document.querySelectorAll('.banner-dot').forEach(dot => {
                dot.addEventListener('click', () => {
                    goToSlide(parseInt(dot.dataset.slide, 10));
                    startAutoSlide();
                });
            });

            // Hỗ trợ vuốt cảm ứng (Swipe) cho Banner trên điện thoại
            const sliderEl = document.getElementById('hero-slider');
            let touchStartX = 0;
            sliderEl.addEventListener('touchstart', e => {
                touchStartX = e.changedTouches[0].screenX;
                clearInterval(sliderTimer);
            }, { passive: true });
            sliderEl.addEventListener('touchend', e => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                }
                startAutoSlide();
            }, { passive: true });
            sliderEl.addEventListener('mouseenter', () => clearInterval(sliderTimer));
            sliderEl.addEventListener('mouseleave', startAutoSlide);

            // Bộ lọc sản phẩm
            document.querySelectorAll('.product-filter-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    const key = btn.dataset.filter;
                    setActiveFilterBtn(key);
                    const filtered = key === 'all' ? productsData : productsData.filter(p => p.category === key);
                    renderProducts(filtered);
                });
            });

            // Bộ lọc danh mục bài viết
            document.querySelectorAll('.article-filter-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    const cat = btn.dataset.articleCat;
                    document.querySelectorAll('.article-filter-btn').forEach(b => {
                        const active = b.dataset.articleCat === cat;
                        b.classList.toggle('bg-brand-primary', active);
                        b.classList.toggle('text-white', active);
                        b.classList.toggle('bg-slate-100', !active);
                        b.classList.toggle('text-slate-700', !active);
                    });
                    renderArticles(cat);
                });
            });

            // Tìm kiếm Header (Desktop & Mobile)
            function handleSearchSubmit(e, inputId) {
                e.preventDefault();
                const val = document.getElementById(inputId).value.trim();
                const section = document.getElementById('san-pham-xingfa');
                if (section) section.scrollIntoView({ behavior: 'smooth' });
                if (!val) {
                    resetProductFilter();
                } else {
                    filterProductsByKeyword(val);
                }
            }
            document.getElementById('header-search-form').addEventListener('submit', e => handleSearchSubmit(e, 'search-input'));
            document.getElementById('mobile-search-form').addEventListener('submit', e => handleSearchSubmit(e, 'mobile-search-input'));
            document.getElementById('mobile-search-toggle').addEventListener('click', () => {
                document.getElementById('mobile-search-bar').classList.toggle('hidden');
            });

            // Mobile Drawer Menu
            const drawer = document.getElementById('mobile-drawer');
            const overlay = document.getElementById('mobile-drawer-overlay');
            function toggleDrawer(open) {
                if (open) {
                    overlay.classList.remove('hidden');
                    drawer.classList.remove('-translate-x-full');
                } else {
                    overlay.classList.add('hidden');
                    drawer.classList.add('-translate-x-full');
                }
            }
            document.getElementById('mobile-menu-btn').addEventListener('click', () => toggleDrawer(true));
            document.getElementById('mobile-drawer-close').addEventListener('click', () => toggleDrawer(false));
            overlay.addEventListener('click', () => toggleDrawer(false));
            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', () => toggleDrawer(false));
            });
            document.querySelectorAll('.mobile-accordion-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    const submenu = btn.nextElementSibling;
                    const icon = btn.querySelector('svg');
                    submenu.classList.toggle('hidden');
                    icon.classList.toggle('rotate-180');
                });
            });

            // Xử lý Form Yêu Cầu Báo Giá (Không dùng alert)
            document.getElementById('quote-form').addEventListener('submit', e => {
                e.preventDefault();
                const name = document.getElementById('q-name').value.trim();
                const phone = document.getElementById('q-phone').value.trim();
                if (!name || !phone) {
                    showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại.');
                    return;
                }
                showToast(`Cảm ơn ${name}! Nhôm Kính Nam Long đã nhận yêu cầu và sẽ gọi lại số ${phone} sớm nhất.`);
                e.target.reset();
            });

            // Đóng Modal khi click nền ngoài hoặc nút đóng
            document.getElementById('modal-close').addEventListener('click', closeModal);
            document.getElementById('info-modal').addEventListener('click', e => {
                if (e.target.id === 'info-modal') closeModal();
            });

            // Nút Lên Đầu Trang
            const scrollTopBtn = document.getElementById('scroll-top-btn');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 360) {
                    scrollTopBtn.classList.remove('hidden');
                    scrollTopBtn.classList.add('flex');
                } else {
                    scrollTopBtn.classList.add('hidden');
                    scrollTopBtn.classList.remove('flex');
                }
            }, { passive: true });
            scrollTopBtn.addEventListener('click', () => window.scrollTo({ top: 0, behavior: 'smooth' }));
        });
    </script>
</body>
</html>
