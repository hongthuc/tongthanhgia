<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG VÀ THƯƠNG MẠI TỐNG THÀNH GIA - tongthanhgia.com</title>
  <meta name="description" content="CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG VÀ THƯƠNG MẠI TỐNG THÀNH GIA chuyên Thiết kế Kiến trúc - Thi công phần thô - Thi công xây dựng trọn gói - Thi công nội thất uy tín tại Đà Nẵng. Hotline: 0934.484.843">

  <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://tongthanhgia.com/">
  <meta property="og:title" content="CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG VÀ THƯƠNG MẠI TỐNG THÀNH GIA">
  <meta property="og:description" content="Chuyên Thiết kế & Thi công Xây dựng Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng uy tín tại Đà Nẵng. Địa chỉ: 157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng. ĐT: 0934.484.843">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ&sz=w1200">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ&sz=w1200">
  <link rel="icon" href="https://drive.google.com/thumbnail?id=1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ&sz=w200">

  <!-- Tailwind CSS & Font Awesome & Google Fonts -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              DEFAULT: '#0f3b68',
              dark: '#092646',
              light: '#1d5691',
              accent: '#d97706',
              accentHover: '#b45309',
              bg: '#f5f7fa'
            }
          },
          fontFamily: {
            sans: ['Roboto', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Reset chống tràn viền và chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Logo chỉnh gọn nhỏ lại */
    .site-logo-img {
      height: 38px;
      width: auto;
      max-width: 120px;
      object-fit: contain;
      display: block;
    }
    @media (min-width: 1024px) {
      .site-logo-img {
        height: 46px;
        max-width: 145px;
      }
    }

    /* Menu danh mục trên máy tính: viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng tên danh mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: flex-end;
      gap: 2px;
      margin: 0;
      padding: 0;
      list-style: none;
    }
    @media (min-width: 1200px) {
      .desktop-nav-list {
        flex-wrap: nowrap;
        gap: 4px;
      }
    }
    .desktop-nav-item {
      position: relative;
      white-space: nowrap;
    }
    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 3px;
      padding: 7px 8px;
      font-size: 12px;
      font-weight: 700;
      color: #0f3b68;
      text-transform: uppercase;
      white-space: nowrap;
      border-radius: 4px;
      transition: all 0.2s ease;
      letter-spacing: -0.1px;
    }
    @media (min-width: 1366px) {
      .desktop-nav-link {
        font-size: 12.5px;
        padding: 8px 10px;
      }
    }
    .desktop-nav-link:hover,
    .desktop-nav-link.active {
      color: #d97706;
      background-color: rgba(15, 59, 104, 0.05);
    }

    /* Dropdown menu chuẩn Flatsome */
    .nav-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 220px;
      background: #ffffff;
      border-top: 3px solid #d97706;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.12);
      border-radius: 0 0 6px 6px;
      padding: 6px 0;
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      z-index: 100;
    }
    .desktop-nav-item:hover .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }
    .nav-dropdown a {
      display: block;
      padding: 8px 14px;
      font-size: 12.5px;
      font-weight: 500;
      color: #334155;
      white-space: nowrap;
      border-bottom: 1px solid #f1f5f9;
      transition: all 0.15s ease;
    }
    .nav-dropdown a:last-child {
      border-bottom: none;
    }
    .nav-dropdown a:hover {
      background-color: #f8fafc;
      color: #d97706;
      padding-left: 18px;
    }

    /* Danh mục lọc ở trang chủ: chữ nhỏ gọn, viết liền trên 1 hàng không bị gãy chữ */
    .cat-pills-wrap {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 6px;
    }
    .cat-pill-btn {
      white-space: nowrap;
      font-size: 11.5px;
      font-weight: 600;
      padding: 6px 11px;
      border-radius: 4px;
      border: 1px solid #cbd5e1;
      background-color: #ffffff;
      color: #1e293b;
      transition: all 0.2s ease;
      cursor: pointer;
    }
    @media (min-width: 1024px) {
      .cat-pill-btn {
        font-size: 12px;
        padding: 6px 13px;
      }
    }
    .cat-pill-btn:hover,
    .cat-pill-btn.active {
      background-color: #0f3b68;
      border-color: #0f3b68;
      color: #ffffff;
    }

    /* Tiêu đề Section kiểu Flatsome */
    .section-title-container {
      margin-bottom: 20px;
      text-align: center;
    }
    .section-title-main {
      display: inline-block;
      position: relative;
      font-size: 18px;
      font-weight: 800;
      color: #0f3b68;
      text-transform: uppercase;
      padding-bottom: 8px;
      margin: 0;
    }
    @media (min-width: 768px) {
      .section-title-main {
        font-size: 22px;
      }
    }
    .section-title-main::after {
      content: "";
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 60px;
      height: 3px;
      background-color: #d97706;
      border-radius: 2px;
    }

    /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối, chữ nằm gọn bên trong cách xa viền */
    .hero-slider-box {
      position: relative;
      width: 100%;
      height: 290px;
      overflow: hidden;
      border-radius: 8px;
      background-color: #092646;
    }
    @media (min-width: 640px) {
      .hero-slider-box {
        height: 350px;
      }
    }
    @media (min-width: 1024px) {
      .hero-slider-box {
        height: 440px;
      }
    }
    .hero-slide-item {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
    }
    .hero-slide-item.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Tên sản phẩm / công trình trên điện thoại & máy tính không bị tràn hoặc thiếu chữ */
    .product-title-full {
      font-size: 12.5px;
      line-height: 1.4;
      font-weight: 700;
      color: #0f3b68;
      word-wrap: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      overflow: visible;
      text-overflow: clip;
      display: block;
    }
    @media (min-width: 768px) {
      .product-title-full {
        font-size: 14px;
      }
    }

    /* Hiệu ứng rung nhẹ cho nút nổi bật */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
    }
    .floating-pulse {
      animation: pulse-ring 2s infinite;
    }
  </style>
</head>
<body>

  <!-- WRAPPER CHUẨN FLATSOME -->
  <div id="wrapper" class="w-full overflow-x-hidden">

    <!-- HEADER (Không có thanh UX Builder ở trên, không có nút Gọi ngay trên Header để tránh tràn viền) -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-50">
      <!-- Top Bar -->
      <div class="header-top bg-brand text-white py-1.5 text-xs border-b border-brand-light">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
          <div class="flex items-center gap-3 overflow-hidden">
            <span class="inline-flex items-center gap-1.5 font-medium truncate">
              <i class="fa-solid fa-building text-amber-400"></i>
              <span>CÔNG TY TNHH ĐTXD & TM TỐNG THÀNH GIA</span>
            </span>
            <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
              <i class="fa-solid fa-location-dot text-amber-400"></i>
              <span>157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng</span>
            </span>
          </div>
          <div class="flex items-center gap-3 ml-auto text-[11.5px]">
            <a href="tel:0934484843" class="inline-flex items-center gap-1 text-amber-300 font-bold hover:text-white">
              <i class="fa-solid fa-phone-volume"></i>
              <span>0934.484.843</span>
            </a>
            <span class="text-slate-400">|</span>
            <a href="https://www.facebook.com/tongthanhgia/" target="_blank" rel="noopener" class="inline-flex items-center gap-1 text-white hover:text-amber-300">
              <i class="fa-brands fa-facebook"></i>
              <span>Fanpage</span>
            </a>
          </div>
        </div>
      </div>

      <!-- Header Main: Logo nhỏ gọn + Menu danh mục viết liền trên 1 hàng chữ nhỏ gọn (Không để nút gọi ngay) -->
      <div class="header-main py-2 bg-white border-b border-slate-100">
        <div class="flatsome-container flex items-center justify-between gap-2">
          <!-- Logo chỉnh gọn nhỏ lại -->
          <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group">
            <img
              src="https://drive.google.com/thumbnail?id=1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ&sz=w400"
              onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ=w400';"
              alt="Logo Tống Thành Gia"
              class="site-logo-img rounded border border-slate-200 p-0.5 bg-white"
            >
            <div class="leading-tight">
              <span class="block text-xs sm:text-sm font-black text-brand tracking-tight uppercase">TỐNG THÀNH GIA</span>
              <span class="block text-[10px] text-amber-600 font-semibold">XÂY DỰNG & THƯƠNG MẠI</span>
            </div>
          </a>

          <!-- Danh mục trên máy tính: viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng từng mục -->
          <nav class="hidden lg:block flex-1">
            <ul class="desktop-nav-list">
              <li class="desktop-nav-item">
                <a href="#trang-chu" class="desktop-nav-link active">TRANG CHỦ</a>
              </li>
              <li class="desktop-nav-item">
                <a href="#gioi-thieu" class="desktop-nav-link">GIỚI THIỆU</a>
              </li>
              <li class="desktop-nav-item">
                <a href="#cong-trinh-thuc-te" class="desktop-nav-link">
                  <span>CÔNG TRÌNH THỰC TẾ</span>
                  <i class="fa-solid fa-angle-down text-[10px]"></i>
                </a>
                <div class="nav-dropdown">
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('all')">Tất cả công trình thực tế</a>
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Khách sạn - Căn hộ')">Khách sạn – Căn hộ – Phòng trọ</a>
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Biệt thự')">Biệt thự</a>
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Nhà phố')">Nhà phố</a>
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Văn phòng')">Văn phòng</a>
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Thi công phần thô')">Thi công phần thô & Móng</a>
                </div>
              </li>
              <li class="desktop-nav-item">
                <a href="#linh-vuc-hoat-dong" class="desktop-nav-link">
                  <span>LĨNH VỰC HOẠT ĐỘNG</span>
                  <i class="fa-solid fa-angle-down text-[10px]"></i>
                </a>
                <div class="nav-dropdown">
                  <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                  <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                  <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                  <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
                  <a href="#linh-vuc-hoat-dong">Cải tạo – Sửa chữa</a>
                </div>
              </li>
              <li class="desktop-nav-item">
                <a href="#du-an-da-nang" class="desktop-nav-link">
                  <span>DỰ ÁN ĐÀ NẴNG</span>
                  <i class="fa-solid fa-angle-down text-[10px]"></i>
                </a>
                <div class="nav-dropdown">
                  <a href="#du-an-da-nang" onclick="filterDanang('all')">Tất cả dự án tại Đà Nẵng</a>
                  <a href="#du-an-da-nang" onclick="filterDanang('Nhà phố Đà Nẵng')">Dự án Nhà phố Đà Nẵng</a>
                  <a href="#du-an-da-nang" onclick="filterDanang('Biệt thự Đà Nẵng')">Dự án Biệt thự Đà Nẵng</a>
                  <a href="#du-an-da-nang" onclick="filterDanang('Căn hộ - Khách sạn')">Dự án Căn hộ – Khách sạn</a>
                </div>
              </li>
              <li class="desktop-nav-item">
                <a href="#mau-thiet-ke" class="desktop-nav-link">
                  <span>MẪU THIẾT KẾ</span>
                  <i class="fa-solid fa-angle-down text-[10px]"></i>
                </a>
                <div class="nav-dropdown">
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Nhà phố')">Mẫu thiết kế nhà phố</a>
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Biệt thự')">Mẫu thiết kế biệt thự</a>
                  <a href="#cong-trinh-thuc-te" onclick="filterConstruction('Văn phòng')">Mẫu thiết kế nội thất</a>
                </div>
              </li>
              <li class="desktop-nav-item">
                <a href="#bao-gia" class="desktop-nav-link">
                  <span>BÁO GIÁ</span>
                  <i class="fa-solid fa-angle-down text-[10px]"></i>
                </a>
                <div class="nav-dropdown">
                  <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                  <a href="#bao-gia">Báo giá thi công phần thô</a>
                  <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                  <a href="#bao-gia">Báo giá thi công trọn gói</a>
                </div>
              </li>
              <li class="desktop-nav-item">
                <a href="#doi-tac" class="desktop-nav-link">ĐỐI TÁC</a>
              </li>
              <li class="desktop-nav-item">
                <a href="#tin-tuc" class="desktop-nav-link">TIN TỨC</a>
              </li>
              <li class="desktop-nav-item">
                <a href="#lien-he" class="desktop-nav-link">LIÊN HỆ</a>
              </li>
            </ul>
          </nav>

          <!-- Nút mở menu trên Điện thoại -->
          <button
            type="button"
            onclick="toggleMobileMenu()"
            aria-label="Mở danh mục"
            class="lg:hidden inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded bg-brand text-white text-xs font-bold"
          >
            <i id="mobile-menu-icon" class="fa-solid fa-bars text-sm"></i>
            <span>DANH MỤC</span>
          </button>
        </div>

        <!-- Thanh danh mục cuộn ngang nhanh trên Điện thoại (Tối ưu hiển thị đẹp trên mobile) -->
        <div class="lg:hidden border-t border-slate-100 mt-2 pt-1.5">
          <div class="flatsome-container flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1">
            <a href="#trang-chu" class="shrink-0 px-2.5 py-1 rounded bg-brand text-white text-[11px] font-bold whitespace-nowrap">Trang chủ</a>
            <a href="#cong-trinh-thuc-te" class="shrink-0 px-2.5 py-1 rounded bg-slate-100 text-brand text-[11px] font-semibold whitespace-nowrap">Công trình thực tế</a>
            <a href="#du-an-da-nang" class="shrink-0 px-2.5 py-1 rounded bg-slate-100 text-brand text-[11px] font-semibold whitespace-nowrap">Dự án Đà Nẵng</a>
            <a href="#linh-vuc-hoat-dong" class="shrink-0 px-2.5 py-1 rounded bg-slate-100 text-brand text-[11px] font-semibold whitespace-nowrap">Lĩnh vực hoạt động</a>
            <a href="#bao-gia" class="shrink-0 px-2.5 py-1 rounded bg-slate-100 text-brand text-[11px] font-semibold whitespace-nowrap">Báo giá</a>
            <a href="#doi-tac" class="shrink-0 px-2.5 py-1 rounded bg-slate-100 text-brand text-[11px] font-semibold whitespace-nowrap">Đối tác</a>
            <a href="#tin-tuc" class="shrink-0 px-2.5 py-1 rounded bg-slate-100 text-brand text-[11px] font-semibold whitespace-nowrap">Tin tức</a>
            <a href="#lien-he" class="shrink-0 px-2.5 py-1 rounded bg-slate-100 text-brand text-[11px] font-semibold whitespace-nowrap">Liên hệ</a>
          </div>
        </div>
      </div>

      <!-- Menu sổ xuống đầy đủ trên Điện thoại -->
      <div id="mobile-drawer" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-lg">
        <div class="flatsome-container py-3 grid grid-cols-2 gap-2 text-xs">
          <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-house text-amber-600"></i> Trang chủ
          </a>
          <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-circle-info text-amber-600"></i> Giới thiệu
          </a>
          <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-helmet-safety text-amber-600"></i> Công trình thực tế
          </a>
          <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-city text-amber-600"></i> Dự án Đà Nẵng
          </a>
          <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-compass-drafting text-amber-600"></i> Lĩnh vực hoạt động
          </a>
          <a href="#bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-file-invoice-dollar text-amber-600"></i> Báo giá xây dựng
          </a>
          <a href="#doi-tac" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-handshake text-amber-600"></i> Đối tác uy tín
          </a>
          <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-bold text-brand flex items-center gap-2">
            <i class="fa-solid fa-newspaper text-amber-600"></i> Tin tức xây dựng
          </a>
          <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="col-span-2 p-2.5 rounded bg-amber-600 text-white font-bold text-center">
            <i class="fa-solid fa-paper-plane mr-1"></i> GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ
          </a>
        </div>
      </div>
    </header>

    <!-- MAIN CONTENT CHUẨN UX BUILDER FLATSOME -->
    <main id="main" class="w-full">

      <!-- SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU -->
      <!-- Chữ và hình ảnh nằm gọn bên trong banner, cách xa viền, không bị thiếu chữ trên cả điện thoại và máy tính -->
      <section id="trang-chu" class="section py-3 md:py-4">
        <div class="flatsome-container">
          <div class="hero-slider-box shadow-md">

            <!-- SLIDE 1 -->
            <div class="hero-slide-item active" data-slide="0">
              <img
                src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600';"
                alt="Banner Tống Thành Gia 1"
                class="w-full h-full object-cover"
              >
              <div class="absolute inset-0 bg-gradient-to-r from-[#092646]/95 via-[#0f3b68]/85 to-[#092646]/70"></div>

              <!-- Khung nội dung cách xa viền ảnh banner (px-8 sm:px-14 lg:px-20 py-6) -->
              <div class="absolute inset-0 flex items-center justify-between px-8 sm:px-14 lg:px-20 py-6">
                <div class="w-full lg:w-7/12 text-white space-y-2 sm:space-y-3">
                  <p class="text-[11px] sm:text-xs font-bold uppercase tracking-wider text-amber-400">
                    WEBSITE CHÍNH THỨC: TONGTHANHGIA.COM
                  </p>
                  <h1 class="text-sm sm:text-xl lg:text-2xl font-black leading-snug uppercase text-white">
                    CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG VÀ THƯƠNG MẠI TỐNG THÀNH GIA
                  </h1>
                  <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                    Chuyên Thiết Kế Kiến Trúc – Thi Công Phần Thô – Xây Nhà Trọn Gói – Thi Công Nội Thất Nhà Phố, Biệt Thự, Căn Hộ, Văn Phòng tại TP Đà Nẵng.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-2 text-[11px] sm:text-xs text-amber-300 font-semibold">
                    <span><i class="fa-solid fa-location-dot mr-1"></i>157 Nguyễn Đình Tứ, P. Cẩm Lệ, TP Đà Nẵng</span>
                    <span class="hidden sm:inline">|</span>
                    <span><i class="fa-solid fa-phone mr-1"></i>Hotline: 0934.484.843</span>
                  </div>
                  <div class="pt-2 flex flex-wrap gap-2">
                    <a href="#form-bao-gia" class="px-3.5 py-2 rounded bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold uppercase transition">
                      Nhận báo giá miễn phí
                    </a>
                    <a href="#cong-trinh-thuc-te" class="px-3.5 py-2 rounded bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs font-bold uppercase transition">
                      Xem công trình thực tế
                    </a>
                  </div>
                </div>

                <!-- Khung ảnh thực tế nằm gọn trong banner trên máy tính -->
                <div class="hidden lg:grid lg:w-4/12 grid-cols-2 gap-2.5 p-2.5 bg-white/10 rounded-lg border border-white/20">
                  <img
                    src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w600';"
                    alt="Thi công thực tế 1"
                    class="w-full h-28 object-cover rounded"
                  >
                  <img
                    src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w600';"
                    alt="Dự án Đà Nẵng 1"
                    class="w-full h-28 object-cover rounded"
                  >
                  <img
                    src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w600';"
                    alt="Thi công thực tế 2"
                    class="w-full h-28 object-cover rounded"
                  >
                  <img
                    src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w600';"
                    alt="Dự án Đà Nẵng 2"
                    class="w-full h-28 object-cover rounded"
                  >
                </div>
              </div>
            </div>

            <!-- SLIDE 2 (Kích thước bằng nhau 100%) -->
            <div class="hero-slide-item" data-slide="1">
              <img
                src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w1600"
                onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w1600';"
                alt="Banner Tống Thành Gia 2"
                class="w-full h-full object-cover"
              >
              <div class="absolute inset-0 bg-gradient-to-r from-[#092646]/95 via-[#0f3b68]/85 to-[#092646]/70"></div>

              <!-- Khung nội dung cách xa viền ảnh banner (px-8 sm:px-14 lg:px-20 py-6) -->
              <div class="absolute inset-0 flex items-center justify-between px-8 sm:px-14 lg:px-20 py-6">
                <div class="w-full lg:w-7/12 text-white space-y-2 sm:space-y-3">
                  <p class="text-[11px] sm:text-xs font-bold uppercase tracking-wider text-amber-400">
                    AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ – TỐI ƯU CHI PHÍ
                  </p>
                  <h2 class="text-sm sm:text-xl lg:text-2xl font-black leading-snug uppercase text-white">
                    GIẢI PHÁP THIẾT KẾ & THI CÔNG XÂY DỰNG TRỌN GÓI UY TÍN TẠI ĐÀ NẴNG
                  </h2>
                  <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                    Miễn phí 100% chi phí hồ sơ thiết kế khi ký hợp đồng thi công trọn gói. Đội ngũ Kiến trúc sư, Kỹ sư giàu kinh nghiệm trực tiếp giám sát từng hạng mục.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-2 text-[11px] sm:text-xs text-amber-300 font-semibold">
                    <span><i class="fa-solid fa-shield-halved mr-1"></i>Bảo hành kết cấu dài hạn</span>
                    <span class="hidden sm:inline">|</span>
                    <span><i class="fa-solid fa-phone mr-1"></i>Tư vấn 24/7: 0934.484.843</span>
                  </div>
                  <div class="pt-2 flex flex-wrap gap-2">
                    <a href="#du-an-da-nang" class="px-3.5 py-2 rounded bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold uppercase transition">
                      Dự án tại Đà Nẵng
                    </a>
                    <a href="#bao-gia" class="px-3.5 py-2 rounded bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs font-bold uppercase transition">
                      Xem bảng báo giá
                    </a>
                  </div>
                </div>

                <!-- Khung ảnh dự án nằm gọn trong banner trên máy tính -->
                <div class="hidden lg:grid lg:w-4/12 grid-cols-2 gap-2.5 p-2.5 bg-white/10 rounded-lg border border-white/20">
                  <img
                    src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N=w600';"
                    alt="Dự án Đà Nẵng 3"
                    class="w-full h-28 object-cover rounded"
                  >
                  <img
                    src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML=w600';"
                    alt="Dự án Đà Nẵng 4"
                    class="w-full h-28 object-cover rounded"
                  >
                  <img
                    src="https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF=w600';"
                    alt="Dự án Đà Nẵng 5"
                    class="w-full h-28 object-cover rounded"
                  >
                  <img
                    src="https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A=w600';"
                    alt="Dự án Đà Nẵng 6"
                    class="w-full h-28 object-cover rounded"
                  >
                </div>
              </div>
            </div>

            <!-- Nút điều hướng 좌/우 nằm sát mép ngoài, không che chữ -->
            <button
              type="button"
              onclick="changeHeroSlide(-1)"
              aria-label="Slide trước"
              class="absolute left-1.5 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/40 hover:bg-amber-600 text-white flex items-center justify-center transition"
            >
              <i class="fa-solid fa-chevron-left text-xs"></i>
            </button>
            <button
              type="button"
              onclick="changeHeroSlide(1)"
              aria-label="Slide tiếp"
              class="absolute right-1.5 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/40 hover:bg-amber-600 text-white flex items-center justify-center transition"
            >
              <i class="fa-solid fa-chevron-right text-xs"></i>
            </button>

            <!-- Chấm chỉ báo 2 banner -->
            <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
              <button type="button" onclick="goToHeroSlide(0)" class="hero-dot w-6 h-2 rounded-full bg-amber-500 transition"></button>
              <button type="button" onclick="goToHeroSlide(1)" class="hero-dot w-2.5 h-2 rounded-full bg-white/60 transition"></button>
            </div>

          </div>
        </div>
      </section>

      <!-- SECTION 2: DỊCH VỤ TIÊU BIỂU & LĨNH VỰC HOẠT ĐỘNG (Theo mẫu tintruongthinh.com) -->
      <section id="linh-vuc-hoat-dong" class="section py-6 bg-white border-y border-slate-100">
        <div class="flatsome-container">
          <div class="section-title-container">
            <h2 class="section-title-main">DỊCH VỤ TIÊU BIỂU & LĨNH VỰC HOẠT ĐỘNG</h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
              Danh mục dịch vụ trọng tâm của Công ty TNHH Đầu tư Xây dựng và Thương mại Tống Thành Gia
            </p>
          </div>

          <!-- 4 Lĩnh vực hoạt động chính giống web mẫu (Chia 2 cột trên điện thoại, 4 cột trên máy tính) -->
          <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
            <div class="box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition">
              <div class="box-image h-32 sm:h-44 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w600"
                  onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w600';"
                  alt="Thiết kế Kiến trúc – Nội thất"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                >
              </div>
              <div class="box-text p-3 text-center">
                <h3 class="product-title-full uppercase">THIẾT KẾ KIẾN TRÚC – NỘI THẤT</h3>
                <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                  Thiết kế bản vẽ kiến trúc, kết cấu, điện nước và phối cảnh 3D nhà phố, biệt thự, khách sạn, căn hộ.
                </p>
              </div>
            </div>

            <div class="box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition">
              <div class="box-image h-32 sm:h-44 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w600"
                  onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w600';"
                  alt="Thi công phần thô"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                >
              </div>
              <div class="box-text p-3 text-center">
                <h3 class="product-title-full uppercase">THI CÔNG PHẦN THÔ</h3>
                <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                  Thi công móng, cốt pha, cốt thép, đổ bê tông sàn, xây tô tường đúng tiêu chuẩn kỹ thuật xây dựng.
                </p>
              </div>
            </div>

            <div class="box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition">
              <div class="box-image h-32 sm:h-44 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w600"
                  onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w600';"
                  alt="Thi công hoàn thiện trọn gói"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                >
              </div>
              <div class="box-text p-3 text-center">
                <h3 class="product-title-full uppercase">THI CÔNG HOÀN THIỆN TRỌN GÓI</h3>
                <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                  Xây nhà trọn gói chìa khóa trao tay, ốp lát, sơn bả, lắp đặt hệ thống điện nước, cửa và thiết bị.
                </p>
              </div>
            </div>

            <div class="box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition">
              <div class="box-image h-32 sm:h-44 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w600"
                  onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w600';"
                  alt="Thi công nội thất & Cải tạo"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                >
              </div>
              <div class="box-text p-3 text-center">
                <h3 class="product-title-full uppercase">THI CÔNG NỘI THẤT & CẢI TẠO</h3>
                <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                  Sản xuất, lắp đặt nội thất hiện đại và cải tạo, nâng tầng, sửa chữa nhà ở, văn phòng, khách sạn.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 3: GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH CỦA CHÚNG TÔI (Theo mẫu tintruongthinh.com) -->
      <section id="gioi-thieu" class="section py-7 bg-slate-50">
        <div class="flatsome-container">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-white p-4 sm:p-6 rounded-lg border border-slate-200 shadow-sm">
            <div class="lg:col-span-7 space-y-3">
              <div class="flex items-center gap-3">
                <img
                  src="https://drive.google.com/thumbnail?id=1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ&sz=w200"
                  onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ=w200';"
                  alt="Logo Tống Thành Gia"
                  class="w-12 h-12 object-contain rounded border border-slate-200 p-1"
                >
                <div>
                  <span class="text-xs font-bold text-amber-600 uppercase">VỀ CHÚNG TÔI</span>
                  <h2 class="text-base sm:text-xl font-black text-brand uppercase">
                    CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG VÀ THƯƠNG MẠI TỐNG THÀNH GIA
                  </h2>
                </div>
              </div>
              <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                <strong>TỐNG THÀNH GIA</strong> chuyên <strong>Thiết kế – Xây dựng – Thi công Nội thất</strong> các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại TP Đà Nẵng và khu vực miền Trung. Với phương châm đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu, mỗi công trình do Tống Thành Gia thực hiện luôn đảm bảo tiêu chí: <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>.
              </p>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs text-slate-700 bg-slate-50 p-3 rounded border border-slate-200">
                <div><i class="fa-solid fa-check text-amber-600 mr-1.5"></i><strong>Mã số thuế:</strong> 0401765197</div>
                <div><i class="fa-solid fa-check text-amber-600 mr-1.5"></i><strong>Hotline/Zalo:</strong> 0934.484.843</div>
                <div class="sm:col-span-2"><i class="fa-solid fa-check text-amber-600 mr-1.5"></i><strong>Địa chỉ:</strong> 157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng</div>
                <div class="sm:col-span-2"><i class="fa-solid fa-check text-amber-600 mr-1.5"></i><strong>Website:</strong> tongthanhgia.com | <strong>Fanpage:</strong> facebook.com/tongthanhgia</div>
              </div>
            </div>

            <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
              <img
                src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w600"
                onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w600';"
                alt="Hình ảnh thi công thực tế Tống Thành Gia"
                class="w-full h-36 sm:h-44 object-cover rounded border border-slate-200"
              >
              <img
                src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w600"
                onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w600';"
                alt="Hình ảnh công trình Tống Thành Gia"
                class="w-full h-36 sm:h-44 object-cover rounded border border-slate-200"
              >
            </div>
          </div>

          <!-- 6 Thế mạnh của chúng tôi (Giống mẫu tintruongthinh.com) -->
          <div class="mt-6">
            <div class="section-title-container">
              <h3 class="section-title-main">THẾ MẠNH CỦA CHÚNG TÔI</h3>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 md:gap-4">
              <div class="bg-white p-3.5 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                <div class="w-10 h-10 rounded-lg bg-brand text-amber-400 flex items-center justify-center shrink-0 text-base">
                  <i class="fa-solid fa-user-tie"></i>
                </div>
                <div>
                  <h4 class="product-title-full">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
                  <p class="text-[11.5px] text-slate-600 mt-1">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giám sát giàu kinh nghiệm và thợ lành nghề.</p>
                </div>
              </div>

              <div class="bg-white p-3.5 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                <div class="w-10 h-10 rounded-lg bg-brand text-amber-400 flex items-center justify-center shrink-0 text-base">
                  <i class="fa-solid fa-compass-drafting"></i>
                </div>
                <div>
                  <h4 class="product-title-full">Cập nhật xu hướng thiết kế hiện đại</h4>
                  <p class="text-[11.5px] text-slate-600 mt-1">Ứng dụng giải pháp không gian xanh, thông thoáng, vật liệu và biện pháp thi công mới nhất.</p>
                </div>
              </div>

              <div class="bg-white p-3.5 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                <div class="w-10 h-10 rounded-lg bg-brand text-amber-400 flex items-center justify-center shrink-0 text-base">
                  <i class="fa-solid fa-clipboard-check"></i>
                </div>
                <div>
                  <h4 class="product-title-full">Giám sát tiến độ chuẩn xác</h4>
                  <p class="text-[11.5px] text-slate-600 mt-1">Báo cáo hình ảnh nhật ký công trình thường xuyên, cam kết bàn giao đúng tiến độ hợp đồng.</p>
                </div>
              </div>

              <div class="bg-white p-3.5 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                <div class="w-10 h-10 rounded-lg bg-brand text-amber-400 flex items-center justify-center shrink-0 text-base">
                  <i class="fa-solid fa-shield-heart"></i>
                </div>
                <div>
                  <h4 class="product-title-full">Bảo hành công trình lâu dài</h4>
                  <p class="text-[11.5px] text-slate-600 mt-1">Chế độ hậu mãi tận tâm, bảo hành kết cấu và chống thấm dài hạn giúp gia chủ an tâm tuyệt đối.</p>
                </div>
              </div>

              <div class="bg-white p-3.5 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                <div class="w-10 h-10 rounded-lg bg-brand text-amber-400 flex items-center justify-center shrink-0 text-base">
                  <i class="fa-solid fa-coins"></i>
                </div>
                <div>
                  <h4 class="product-title-full">Giá cả hợp lý, minh bạch vật tư</h4>
                  <p class="text-[11.5px] text-slate-600 mt-1">Dự toán chi tiết từng hạng mục, cam kết đúng chủng loại vật tư, không phát sinh chi phí.</p>
                </div>
              </div>

              <div class="bg-white p-3.5 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                <div class="w-10 h-10 rounded-lg bg-brand text-amber-400 flex items-center justify-center shrink-0 text-base">
                  <i class="fa-solid fa-headset"></i>
                </div>
                <div>
                  <h4 class="product-title-full">Hỗ trợ tư vấn miễn phí 24/7</h4>
                  <p class="text-[11.5px] text-slate-600 mt-1">Khảo sát thực tế tận nơi tại Đà Nẵng, tư vấn phong thủy và xin phép xây dựng nhanh chóng.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 4: 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG & DANH MỤC SẢN PHẨM (Không nhãn dán, chia 2 cột trên điện thoại, tên đầy đủ không tràn) -->
      <section id="cong-trinh-thuc-te" class="section py-7 bg-white">
        <div class="flatsome-container">
          <div class="section-title-container">
            <h2 class="section-title-main">HÌNH ẢNH THỰC TẾ THI CÔNG XÂY DỰNG & SẢN PHẨM DỊCH VỤ</h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
              Thực tế thi công phần thô, móng, khung kết cấu và hoàn thiện công trình của Tống Thành Gia
            </p>
          </div>

          <!-- Bộ lọc danh mục nhỏ gọn, chữ nằm trên 1 hàng không gãy dòng -->
          <div class="cat-pills-wrap mb-5" id="construction-filter-bar">
            <button type="button" onclick="filterConstruction('all')" class="cat-pill-btn active" data-cat="all">Tất cả hạng mục</button>
            <button type="button" onclick="filterConstruction('Thi công phần thô')" class="cat-pill-btn" data-cat="Thi công phần thô">Thi công phần thô</button>
            <button type="button" onclick="filterConstruction('Nhà phố')" class="cat-pill-btn" data-cat="Nhà phố">Nhà phố</button>
            <button type="button" onclick="filterConstruction('Biệt thự')" class="cat-pill-btn" data-cat="Biệt thự">Biệt thự</button>
            <button type="button" onclick="filterConstruction('Khách sạn - Căn hộ')" class="cat-pill-btn" data-cat="Khách sạn - Căn hộ">Khách sạn – Căn hộ – Phòng trọ</button>
            <button type="button" onclick="filterConstruction('Văn phòng')" class="cat-pill-btn" data-cat="Văn phòng">Văn phòng – Cải tạo</button>
          </div>

          <!-- Lưới 9 sản phẩm/hạng mục thi công thực tế: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (lg:grid-cols-3) -->
          <!-- KHÔNG để các nhãn dán (stickers/badges) trên ảnh theo đúng yêu cầu -->
          <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 md:gap-4"></div>
        </div>
      </section>

      <!-- SECTION 5: DANH MỤC 10 DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ (Chia 2 cột trên điện thoại, không nhãn dán, tên đầy đủ) -->
      <section id="du-an-da-nang" class="section py-7 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
          <div class="section-title-container">
            <h2 class="section-title-main">CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
              Tổng hợp các dự án Thiết kế & Thi công xây dựng thực tế tại Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn, Hòa Xuân – TP Đà Nẵng
            </p>
          </div>

          <!-- Bộ lọc danh mục dự án Đà Nẵng nhỏ gọn -->
          <div class="cat-pills-wrap mb-5" id="danang-filter-bar">
            <button type="button" onclick="filterDanang('all')" class="cat-pill-btn active" data-dncat="all">Tất cả dự án Đà Nẵng</button>
            <button type="button" onclick="filterDanang('Nhà phố Đà Nẵng')" class="cat-pill-btn" data-dncat="Nhà phố Đà Nẵng">Nhà phố Đà Nẵng</button>
            <button type="button" onclick="filterDanang('Biệt thự Đà Nẵng')" class="cat-pill-btn" data-dncat="Biệt thự Đà Nẵng">Biệt thự Đà Nẵng</button>
            <button type="button" onclick="filterDanang('Căn hộ - Khách sạn')" class="cat-pill-btn" data-dncat="Căn hộ - Khách sạn">Khách sạn – Căn hộ Đà Nẵng</button>
          </div>

          <!-- Lưới 10 dự án ở Đà Nẵng: 2 cột trên điện thoại (grid-cols-2), 5 cột trên máy tính (lg:grid-cols-5) -->
          <div id="danang-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 md:gap-4"></div>
        </div>
      </section>

      <!-- SECTION 6: BÁO GIÁ THIẾT KẾ & THI CÔNG XÂY DỰNG (Theo mẫu tintruongthinh.com) -->
      <section id="bao-gia" class="section py-7 bg-white border-t border-slate-200">
        <div class="flatsome-container">
          <div class="section-title-container">
            <h2 class="section-title-main">BẢNG BÁO GIÁ THIẾT KẾ & THI CÔNG XÂY DỰNG</h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
              Hoàn trả ngay 100% chi phí thiết kế kiến trúc khi Quý khách hàng ký hợp đồng thi công xây dựng trọn gói
            </p>
          </div>

          <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
          <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
            <div class="rounded-lg border border-slate-200 bg-slate-50 p-3.5 flex flex-col justify-between">
              <div>
                <h3 class="product-title-full uppercase text-center border-b border-slate-200 pb-2">BÁO GIÁ THIẾT KẾ KIẾN TRÚC</h3>
                <p class="text-center text-base sm:text-lg font-black text-amber-600 my-2">99.000đ – 150.000đ/m²</p>
                <ul class="text-[11.5px] text-slate-700 space-y-1.5">
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Hồ sơ thiết kế chi tiết Kiến trúc</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Hồ sơ thiết kế chi tiết Kết cấu</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Hồ sơ thiết kế Điện nước (M&E)</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Phối cảnh 3D mặt tiền ngoại thất</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded bg-brand hover:bg-brand-dark text-white text-xs font-bold">
                Đăng ký tư vấn
              </a>
            </div>

            <div class="rounded-lg border border-slate-200 bg-slate-50 p-3.5 flex flex-col justify-between">
              <div>
                <h3 class="product-title-full uppercase text-center border-b border-slate-200 pb-2">THIẾT KẾ TRỌN GÓI ĐẶC BIỆT</h3>
                <p class="text-center text-base sm:text-lg font-black text-amber-600 my-2">180.000đ – 250.000đ/m²</p>
                <ul class="text-[11.5px] text-slate-700 space-y-1.5">
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Đầy đủ hồ sơ Kiến trúc, Kết cấu, Điện nước</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Phối cảnh 3D Ngoại thất & Nội thất</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Hồ sơ xin cấp giấy phép xây dựng</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Bảng dự toán chi tiết khối lượng</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded bg-brand hover:bg-brand-dark text-white text-xs font-bold">
                Đăng ký tư vấn
              </a>
            </div>

            <div class="rounded-lg border border-slate-200 bg-slate-50 p-3.5 flex flex-col justify-between">
              <div>
                <h3 class="product-title-full uppercase text-center border-b border-slate-200 pb-2">BÁO GIÁ THI CÔNG PHẦN THÔ</h3>
                <p class="text-center text-base sm:text-lg font-black text-amber-600 my-2">3.500.000đ – 3.900.000đ/m²</p>
                <ul class="text-[11.5px] text-slate-700 space-y-1.5">
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Vật tư chuẩn: Thép Hòa Phát, Xi măng Sông Gianh</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Nhân công xây tô, cốt pha, bê tông chuẩn</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Lắp đặt hệ thống điện nước âm tường</li>
                  <li><i class="fa-solid fa-check text-brand mr-1"></i>Kỹ sư giám sát trực tiếp tại công trình</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded bg-brand hover:bg-brand-dark text-white text-xs font-bold">
                Nhận dự toán
              </a>
            </div>

            <div class="rounded-lg border border-amber-500 bg-amber-50/40 p-3.5 flex flex-col justify-between">
              <div>
                <h3 class="product-title-full uppercase text-center border-b border-amber-200 pb-2">THI CÔNG TRỌN GÓI (CHÌA KHÓA TRAO TAY)</h3>
                <p class="text-center text-base sm:text-lg font-black text-amber-600 my-2">5.500.000đ – 6.800.000đ/m²</p>
                <ul class="text-[11.5px] text-slate-700 space-y-1.5">
                  <li><i class="fa-solid fa-check text-amber-600 mr-1"></i>Miễn phí 100% thiết kế & xin phép xây dựng</li>
                  <li><i class="fa-solid fa-check text-amber-600 mr-1"></i>Thi công trọn gói từ phần thô đến hoàn thiện</li>
                  <li><i class="fa-solid fa-check text-amber-600 mr-1"></i>Cam kết không phát sinh chi phí</li>
                  <li><i class="fa-solid fa-check text-amber-600 mr-1"></i>Bảo hành kết cấu công trình lên đến 5 năm</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded bg-amber-600 hover:bg-amber-700 text-white text-xs font-bold">
                Nhận báo giá ngay
              </a>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 7: FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ (Theo mẫu tintruongthinh.com) -->
      <section id="form-bao-gia" class="section py-8 bg-brand text-white">
        <div class="flatsome-container">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
            <div class="lg:col-span-5 space-y-3">
              <span class="text-xs font-bold uppercase text-amber-400">KẾT NỐI VỚI TỐNG THÀNH GIA</span>
              <h2 class="text-lg sm:text-2xl font-black uppercase leading-snug">
                ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ XÂY DỰNG MIỄN PHÍ
              </h2>
              <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                Quý khách hàng đang có kế hoạch xây dựng Nhà phố, Biệt thự, Căn hộ cho thuê, Khách sạn hay Văn phòng tại Đà Nẵng? Hãy để lại thông tin, Kỹ sư trưởng của <strong>TỐNG THÀNH GIA</strong> sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết ngay!
              </p>
              <div class="space-y-2 pt-1 text-xs sm:text-sm">
                <div class="flex items-center gap-2.5">
                  <i class="fa-solid fa-phone-volume text-amber-400 w-5"></i>
                  <span>Hotline tư vấn trực tiếp: <strong class="text-amber-300">0934.484.843</strong></span>
                </div>
                <div class="flex items-center gap-2.5">
                  <i class="fa-solid fa-location-dot text-amber-400 w-5"></i>
                  <span>Địa chỉ: <strong>157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng</strong></span>
                </div>
                <div class="flex items-center gap-2.5">
                  <i class="fa-solid fa-globe text-amber-400 w-5"></i>
                  <span>Website: <strong>tongthanhgia.com</strong></span>
                </div>
              </div>
            </div>

            <div class="lg:col-span-7">
              <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 p-4 sm:p-6 rounded-lg shadow-lg">
                <h3 class="text-sm sm:text-base font-black text-brand uppercase mb-3 border-b border-slate-200 pb-2">
                  FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ
                </h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs">
                  <div>
                    <label class="block font-bold text-slate-700 mb-1">Họ và tên *</label>
                    <input type="text" id="q_name" required placeholder="Nhập họ và tên của Quý khách" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand">
                  </div>
                  <div>
                    <label class="block font-bold text-slate-700 mb-1">Số điện thoại *</label>
                    <input type="tel" id="q_phone" required placeholder="Ví dụ: 0934.484.843" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand">
                  </div>
                  <div>
                    <label class="block font-bold text-slate-700 mb-1">Loại công trình</label>
                    <select id="q_type" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                      <option value="Nhà phố">Nhà phố</option>
                      <option value="Biệt thự">Biệt thự</option>
                      <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                      <option value="Văn phòng">Văn phòng</option>
                      <option value="Thi công phần thô">Thi công phần thô</option>
                      <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                    </select>
                  </div>
                  <div>
                    <label class="block font-bold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                    <select id="q_budget" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                      <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                      <option value="Từ 1 - 2 tỷ">Từ 1 - 2 tỷ</option>
                      <option value="Từ 2 - 3 tỷ">Từ 2 - 3 tỷ</option>
                      <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                      <option value="Cần tư vấn dự toán chi tiết">Cần tư vấn dự toán chi tiết</option>
                    </select>
                  </div>
                  <div class="sm:col-span-2">
                    <label class="block font-bold text-slate-700 mb-1">Địa điểm xây dựng & Yêu cầu chi tiết (Diện tích, số tầng...)</label>
                    <textarea id="q_note" rows="2" placeholder="Ví dụ: Xây nhà phố 3 tầng diện tích 5x20m tại Cẩm Lệ, Đà Nẵng..." class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-brand"></textarea>
                  </div>
                </div>
                <button type="submit" class="mt-3 w-full py-2.5 px-4 rounded bg-amber-600 hover:bg-amber-700 text-white font-bold text-xs sm:text-sm uppercase transition">
                  <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                </button>
                <div id="quoteSuccessMsg" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
              </form>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 8: DANH MỤC CÁC ĐỐI TÁC UY TÍN -->
      <section id="doi-tac" class="section py-7 bg-white border-b border-slate-200">
        <div class="flatsome-container">
          <div class="section-title-container">
            <h2 class="section-title-main">ĐỐI TÁC CUNG ỨNG VẬT TƯ & THƯƠNG HIỆU ĐỒNG HÀNH</h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
              Tống Thành Gia hợp tác cùng các thương hiệu vật liệu xây dựng và nội thất hàng đầu Việt Nam
            </p>
          </div>

          <!-- Chia 2 cột trên điện thoại, 5 cột trên máy tính -->
          <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3">
            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">HP</div>
              <h3 class="product-title-full">THÉP HÒA PHÁT</h3>
              <p class="text-[11px] text-slate-500">Thép xây dựng kết cấu chuẩn</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">SG</div>
              <h3 class="product-title-full">XI MĂNG KIM ĐỈNH – SÔNG GIANH</h3>
              <p class="text-[11px] text-slate-500">Xi măng bê tông & xây tô</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">DL</div>
              <h3 class="product-title-full">SƠN DULUX & JOTUN</h3>
              <p class="text-[11px] text-slate-500">Sơn nội ngoại thất cao cấp</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">IN</div>
              <h3 class="product-title-full">THIẾT BỊ VỆ SINH INAX & TOTO</h3>
              <p class="text-[11px] text-slate-500">Thiết bị phòng tắm chính hãng</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">PA</div>
              <h3 class="product-title-full">ĐIỆN PANASONIC & CADIVI</h3>
              <p class="text-[11px] text-slate-500">Hệ thống cáp & thiết bị điện</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">XF</div>
              <h3 class="product-title-full">NHÔM KÍNH XINGFA</h3>
              <p class="text-[11px] text-slate-500">Hệ cửa nhôm kính cao cấp</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">AC</div>
              <h3 class="product-title-full">GỖ CÔNG NGHIỆP AN CƯỜNG</h3>
              <p class="text-[11px] text-slate-500">Vật liệu nội thất hiện đại</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">BM</div>
              <h3 class="product-title-full">ỐNG NƯỚC BÌNH MINH & TIỀN PHONG</h3>
              <p class="text-[11px] text-slate-500">Hệ thống cấp thoát nước</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">SK</div>
              <h3 class="product-title-full">CHỐNG THẤM SIKA</h3>
              <p class="text-[11px] text-slate-500">Phụ gia & hóa chất chống thấm</p>
            </div>

            <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand transition">
              <div class="w-10 h-10 mx-auto mb-1.5 rounded-full bg-brand/10 text-brand flex items-center justify-center font-black text-sm">ĐN</div>
              <h3 class="product-title-full">BÊ TÔNG THƯƠNG PHẨM ĐÀ NẴNG</h3>
              <p class="text-[11px] text-slate-500">Bê tông tươi đúng mác thiết kế</p>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 9: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ (Theo mẫu tintruongthinh.com) -->
      <section id="tin-tuc" class="section py-7 bg-slate-50">
        <div class="flatsome-container">
          <div class="section-title-container">
            <h2 class="section-title-main">TIN TỨC & KINH NGHIỆM XÂY DỰNG</h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
              Cập nhật kiến thức thi công phần thô, bảo dưỡng bê tông và kinh nghiệm xây nhà trọn gói tại Đà Nẵng
            </p>
          </div>

          <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
          <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
            <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
              <div>
                <div class="h-32 sm:h-40 overflow-hidden">
                  <img
                    src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w600';"
                    alt="Hướng dẫn bảo dưỡng bê tông móng đúng cách"
                    class="w-full h-full object-cover"
                  >
                </div>
                <div class="p-3">
                  <h3 class="product-title-full">Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật xây dựng</h3>
                  <p class="text-[11.5px] text-slate-600 mt-1.5">
                    Trong quá trình thi công phần thô, bảo dưỡng bê tông móng và sàn đóng vai trò quyết định đến cường độ chịu lực và chống nứt công trình.
                  </p>
                </div>
              </div>
              <div class="px-3 pb-3">
                <button type="button" onclick="openArticleModal(0)" class="text-xs font-bold text-amber-600 hover:text-brand">
                  Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                </button>
              </div>
            </article>

            <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
              <div>
                <div class="h-32 sm:h-40 overflow-hidden">
                  <img
                    src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w600';"
                    alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư đều gặp phải"
                    class="w-full h-full object-cover"
                  >
                </div>
                <div class="p-3">
                  <h3 class="product-title-full">03 Nỗi lo lớn nhất khi xây nhà tại Đà Nẵng và giải pháp tối ưu</h3>
                  <p class="text-[11.5px] text-slate-600 mt-1.5">
                    Giải quyết triệt để nỗi lo phát sinh chi phí, chậm tiến độ và chất lượng vật tư khi lựa chọn nhà thầu xây nhà trọn gói uy tín.
                  </p>
                </div>
              </div>
              <div class="px-3 pb-3">
                <button type="button" onclick="openArticleModal(1)" class="text-xs font-bold text-amber-600 hover:text-brand">
                  Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                </button>
              </div>
            </article>

            <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
              <div>
                <div class="h-32 sm:h-40 overflow-hidden">
                  <img
                    src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w600';"
                    alt="Tâm lý học không gian nội thất"
                    class="w-full h-full object-cover"
                  >
                </div>
                <div class="p-3">
                  <h3 class="product-title-full">Tâm lý học không gian: Thiết kế kiến trúc & nội thất tác động thế nào?</h3>
                  <p class="text-[11.5px] text-slate-600 mt-1.5">
                    Cách bố trí ánh sáng tự nhiên, thông gió và cây xanh giúp ngôi nhà phố tại Đà Nẵng luôn tràn đầy năng lượng tích cực.
                  </p>
                </div>
              </div>
              <div class="px-3 pb-3">
                <button type="button" onclick="openArticleModal(2)" class="text-xs font-bold text-amber-600 hover:text-brand">
                  Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                </button>
              </div>
            </article>

            <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
              <div>
                <div class="h-32 sm:h-40 overflow-hidden">
                  <img
                    src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w600"
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w600';"
                    alt="Quy trình nghiệm thu sắt thép và cốt pha"
                    class="w-full h-full object-cover"
                  >
                </div>
                <div class="p-3">
                  <h3 class="product-title-full">Quy trình kiểm tra nghiệm thu cốt thép và cốt pha trước khi đổ bê tông</h3>
                  <p class="text-[11.5px] text-slate-600 mt-1.5">
                    Tiêu chuẩn nghiệm thu kỹ thuật nghiêm ngặt của đội ngũ kỹ sư Tống Thành Gia nhằm đảm bảo kết cấu bền vững vĩnh cửu.
                  </p>
                </div>
              </div>
              <div class="px-3 pb-3">
                <button type="button" onclick="openArticleModal(3)" class="text-xs font-bold text-amber-600 hover:text-brand">
                  Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                </button>
              </div>
            </article>
          </div>
        </div>
      </section>

      <!-- SECTION 10: ĐƯA FANPAGE VÀ BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
      <section id="lien-he" class="section py-7 bg-white border-t border-slate-200">
        <div class="flatsome-container">
          <div class="section-title-container">
            <h2 class="section-title-main">KẾT NỐI FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG TỐNG THÀNH GIA</h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
              Địa chỉ trụ sở: 157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng – Hotline: 0934.484.843
            </p>
          </div>

          <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
            <!-- Cột Fanpage chính thức ngoài trang chủ -->
            <div class="lg:col-span-5 bg-slate-50 rounded-lg border border-slate-200 p-4 flex flex-col justify-between">
              <div>
                <h3 class="text-sm sm:text-base font-black text-brand uppercase mb-3 flex items-center gap-2">
                  <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                  <span>FANPAGE FACEBOOK CHÍNH THỨC</span>
                </h3>

                <!-- Khung giao diện Fanpage trực quan + Plugin nhúng Facebook -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                  <div class="relative h-32 bg-brand">
                    <img
                      src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                      onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800';"
                      alt="Ảnh bìa Fanpage Tống Thành Gia"
                      class="w-full h-full object-cover opacity-65"
                    >
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                      <img
                        src="https://drive.google.com/thumbnail?id=1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ&sz=w200"
                        onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ=w200';"
                        alt="Logo Fanpage Tống Thành Gia"
                        class="w-12 h-12 rounded-lg bg-white p-1 object-contain border border-white shrink-0"
                      >
                      <div class="text-white">
                        <a href="https://www.facebook.com/tongthanhgia/" target="_blank" rel="noopener" class="font-bold text-xs sm:text-sm hover:underline block">
                          CÔNG TY TNHH ĐTXD & TM TỐNG THÀNH GIA
                        </a>
                        <span class="text-[11px] text-slate-200 block">@tongthanhgia • Công ty Xây dựng Đà Nẵng</span>
                      </div>
                    </div>
                  </div>

                  <div class="p-3 space-y-2 text-xs text-slate-700">
                    <p>
                      Cập nhật hình ảnh nhật ký công trình thi công thực tế hàng ngày, các mẫu thiết kế nhà phố, biệt thự mới nhất trên Fanpage chính thức của công ty.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-1">
                      <a
                        href="https://www.facebook.com/tongthanhgia/"
                        target="_blank"
                        rel="noopener"
                        class="inline-flex items-center gap-1.5 px-3 py-2 rounded bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs"
                      >
                        <i class="fa-brands fa-facebook-f"></i> Truy cập Fanpage Facebook
                      </a>
                      <a
                        href="https://zalo.me/0934484843"
                        target="_blank"
                        rel="noopener"
                        class="inline-flex items-center gap-1.5 px-3 py-2 rounded bg-sky-600 hover:bg-sky-700 text-white font-bold text-xs"
                      >
                        <i class="fa-solid fa-comment-dots"></i> Nhắn tin Zalo: 0934.484.843
                      </a>
                    </div>
                  </div>
                </div>
              </div>

              <div class="mt-3 p-3 rounded bg-white border border-slate-200 text-xs space-y-1">
                <div class="font-bold text-brand uppercase">THÔNG TIN LIÊN HỆ TRỰC TIẾP:</div>
                <div><strong>Địa chỉ:</strong> 157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng</div>
                <div><strong>Điện thoại:</strong> <a href="tel:0934484843" class="text-amber-600 font-bold">0934.484.843</a></div>
                <div><strong>Website:</strong> <a href="https://tongthanhgia.com" class="text-brand font-medium">https://tongthanhgia.com</a></div>
              </div>
            </div>

            <!-- Cột Bản đồ Google Maps ngoài trang chủ -->
            <div class="lg:col-span-7 bg-slate-50 rounded-lg border border-slate-200 p-4 flex flex-col justify-between">
              <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                <h3 class="text-sm sm:text-base font-black text-brand uppercase flex items-center gap-2">
                  <i class="fa-solid fa-map-location-dot text-amber-600 text-lg"></i>
                  <span>BẢN ĐỒ GOOGLE MAPS: 157 NGUYỄN ĐÌNH TỨ, CẨM LỆ, ĐÀ NẴNG</span>
                </h3>
                <a
                  href="https://www.google.com/maps/search/?api=1&query=157+Nguy%E1%BB%85n+%C4%90%C3%ACnh+T%E1%BB%A9,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng"
                  target="_blank"
                  rel="noopener"
                  class="text-xs font-bold text-amber-600 hover:underline"
                >
                  <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Google Maps lớn
                </a>
              </div>

              <div class="w-full h-64 sm:h-80 rounded-lg overflow-hidden border border-slate-300 bg-slate-200">
                <iframe
                  title="Bản đồ 157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng"
                  src="https://maps.google.com/maps?q=157%20Nguy%E1%BB%85n%20%C4%90%C3%ACnh%20T%E1%BB%A9,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                  class="w-full h-full border-0"
                  loading="lazy"
                  referrerpolicy="no-referrer-when-downgrade"
                ></iframe>
              </div>
            </div>
          </div>
        </div>
      </section>

    </main>

    <!-- FOOTER CHUẨN FLATSOME -->
    <footer id="footer" class="bg-brand-dark text-slate-200 pt-8 pb-6 border-t-4 border-amber-500">
      <div class="flatsome-container">
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
          <!-- Cột 1: Thông tin công ty -->
          <div class="lg:col-span-5 space-y-2.5 text-xs">
            <div class="flex items-center gap-2.5">
              <img
                src="https://drive.google.com/thumbnail?id=1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ&sz=w200"
                onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1r2WS8pzEcYNhrq5J15v8EaABLwFuvaXZ=w200';"
                alt="Logo Tống Thành Gia"
                class="w-10 h-10 rounded bg-white p-0.5 object-contain shrink-0"
              >
              <h3 class="text-sm font-black text-white uppercase leading-snug">
                CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG VÀ THƯƠNG MẠI TỐNG THÀNH GIA
              </h3>
            </div>
            <p class="text-slate-300 leading-relaxed">
              Đơn vị uy tín hàng đầu tại Đà Nẵng chuyên Thiết kế kiến trúc, Thi công phần thô, Xây nhà trọn gói và Thi công nội thất Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng.
            </p>
            <ul class="space-y-1.5 text-slate-200">
              <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Trụ sở:</strong> 157 Nguyễn Đình Tứ, Phường Cẩm Lệ, TP Đà Nẵng</li>
              <li><i class="fa-solid fa-phone text-amber-400 w-5"></i><strong>Hotline / Zalo:</strong> <a href="tel:0934484843" class="text-amber-300 font-bold">0934.484.843</a></li>
              <li><i class="fa-solid fa-id-card text-amber-400 w-5"></i><strong>Mã số thuế:</strong> 0401765197</li>
              <li><i class="fa-solid fa-globe text-amber-400 w-5"></i><strong>Website:</strong> tongthanhgia.com</li>
              <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/tongthanhgia/" target="_blank" rel="noopener" class="hover:text-amber-300">facebook.com/tongthanhgia</a></li>
            </ul>
          </div>

          <!-- Cột 2: Lĩnh vực hoạt động -->
          <div class="lg:col-span-3 space-y-2 text-xs">
            <h4 class="text-sm font-black text-white uppercase border-b border-white/15 pb-2">LĨNH VỰC HOẠT ĐỘNG</h4>
            <ul class="space-y-1.5">
              <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thiết kế Kiến trúc – Nội thất</a></li>
              <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thi công xây dựng phần thô</a></li>
              <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thi công xây nhà trọn gói</a></li>
              <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thi công hoàn thiện nội thất</a></li>
              <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Cải tạo – Sửa chữa công trình</a></li>
            </ul>
          </div>

          <!-- Cột 3: Danh mục công trình & báo giá -->
          <div class="lg:col-span-4 space-y-2 text-xs">
            <h4 class="text-sm font-black text-white uppercase border-b border-white/15 pb-2">DANH MỤC CÔNG TRÌNH & BÁO GIÁ</h4>
            <div class="grid grid-cols-2 gap-1.5">
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Nhà phố hiện đại</a>
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Biệt thự sang trọng</a>
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Khách sạn – Căn hộ</a>
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Văn phòng công ty</a>
              <a href="#bao-gia" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Báo giá thiết kế</a>
              <a href="#bao-gia" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Báo giá phần thô</a>
              <a href="#bao-gia" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Báo giá trọn gói</a>
              <a href="#du-an-da-nang" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i>Dự án Đà Nẵng</a>
            </div>
          </div>
        </div>

        <div class="pt-4 text-center text-[11.5px] text-slate-400">
          Copyright © CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG VÀ THƯƠNG MẠI TỐNG THÀNH GIA (tongthanhgia.com). All rights reserved.
        </div>
      </div>
    </footer>

  </div>

  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE TƯƠNG THÍCH TRÊN MÁY TÍNH VÀ ĐIỆN THOẠI -->
  <div class="fixed bottom-4 left-3 z-50 flex flex-col gap-2.5">
    <!-- Nút Facebook Fanpage -->
    <a
      href="https://www.facebook.com/tongthanhgia/"
      target="_blank"
      rel="noopener"
      aria-label="Facebook Fanpage Tống Thành Gia"
      class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-blue-600 flex items-center justify-center text-xs font-bold shrink-0">
        <i class="fa-brands fa-facebook-f"></i>
      </span>
      <span class="text-xs font-bold pr-1">Fanpage</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a
      href="https://zalo.me/0934484843"
      target="_blank"
      rel="noopener"
      aria-label="Zalo 0934.484.843"
      class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-sky-600 flex items-center justify-center text-[10px] font-black shrink-0">
        Zalo
      </span>
      <span class="text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Gọi Hotline nổi bật -->
    <a
      href="tel:0934484843"
      aria-label="Gọi Hotline 0934.484.843"
      class="floating-pulse flex items-center gap-2 bg-amber-600 hover:bg-amber-700 text-white px-3.5 py-2 rounded-full shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-amber-600 flex items-center justify-center text-xs font-bold shrink-0">
        <i class="fa-solid fa-phone-volume"></i>
      </span>
      <span class="text-xs font-black pr-1">0934.484.843</span>
    </a>
  </div>

  <!-- MODAL XEM CHI TIẾT HÌNH ẢNH CÔNG TRÌNH / BÀI VIẾT -->
  <div id="detailModal" class="fixed inset-0 bg-black/75 z-50 hidden items-center justify-center p-3" onclick="closeDetailModal(event)">
    <div class="bg-white rounded-lg max-w-2xl w-full overflow-hidden shadow-2xl" onclick="event.stopPropagation()">
      <div class="flex items-center justify-between px-4 py-3 bg-brand text-white">
        <h3 id="modalTitle" class="text-xs sm:text-sm font-bold uppercase pr-4">Chi tiết hạng mục</h3>
        <button type="button" onclick="closeDetailModal()" class="text-white hover:text-amber-300 text-lg leading-none">&times;</button>
      </div>
      <div class="p-4 space-y-3 max-h-[80vh] overflow-y-auto">
        <img id="modalImage" src="" alt="" class="w-full h-56 sm:h-72 object-cover rounded border border-slate-200">
        <p id="modalCategory" class="text-xs font-bold text-amber-600 uppercase"></p>
        <p id="modalDesc" class="text-xs sm:text-sm text-slate-700 leading-relaxed"></p>
        <div class="pt-2 flex flex-wrap gap-2 border-t border-slate-200">
          <a href="tel:0934484843" class="px-3.5 py-2 rounded bg-amber-600 text-white text-xs font-bold">
            <i class="fa-solid fa-phone mr-1"></i> Gọi tư vấn: 0934.484.843
          </a>
          <a href="#form-bao-gia" onclick="closeDetailModal()" class="px-3.5 py-2 rounded bg-brand text-white text-xs font-bold">
            <i class="fa-solid fa-calculator mr-1"></i> Nhận báo giá hạng mục này
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- JAVASCRIPT XỬ LÝ DỮ LIỆU 9 ẢNH THI CÔNG THỰC TẾ, 10 ẢNH DỰ ÁN ĐÀ NẴNG, SLIDER BANNER VÀ FORM -->
  <script>
    // Danh sách 9 ảnh thực tế thi công xây dựng từ Google Drive của khách hàng, phân loại chuẩn theo danh mục mẫu tintruongthinh.com
    const constructionItems = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi Công Phần Thô & Đổ Bê Tông Sàn Nhà Phố Hiện Đại',
        category: 'Thi công phần thô',
        desc: 'Thực tế công tác lắp dựng cốt pha, nghiệm thu cốt thép sàn và đổ bê tông phần thô nhà phố do đội ngũ kỹ sư Tống Thành Gia trực tiếp giám sát.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi Công Kết Cấu Khung Bê Tông Cốt Thép Nhà Phố 3 Tầng',
        category: 'Nhà phố',
        desc: 'Thi công phần khung bê tông cốt thép và xây tường bao nhà phố 3 tầng đảm bảo đúng tiêu chuẩn kỹ thuật, an toàn lao động và tiến độ cam kết.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi Công Cốt Thép Dầm Sàn & Hệ Thống Móng Công Trình',
        category: 'Thi công phần thô',
        desc: 'Gia công, lắp đặt cốt thép dầm sàn sử dụng thép Hòa Phát chính hãng, buộc sắt đúng khoảng cách thiết kế kết cấu.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi Công Xây Dựng Biệt Thự Gia Đình Trọn Gói',
        category: 'Biệt thự',
        desc: 'Hình ảnh thực tế thi công xây dựng công trình biệtự hiện đại với kết cấu vững chắc, không gian thông thoáng và thẩm mỹ cao.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Nghiệm Thu Cốt Pha & Sắt Thép Sàn Trước Khi Đổ Bê Tông',
        category: 'Thi công phần thô',
        desc: 'Kỹ sư Tống Thành Gia kiểm tra độ kín khít của cốt pha và cao độ sàn trước khi tiến hành đổ bê tông thương phẩm.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi Công Căn Hộ Cho Thuê & Khách Sạn Cao Tầng',
        category: 'Khách sạn - Căn hộ',
        desc: 'Thi công kết cấu và hoàn thiện công trình căn hộ dịch vụ cho thuê kết hợp kinh doanh tối ưu diện tích và công năng sử dụng.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi Công Xây Tô Tường & Lắp Đặt Điện Nước Âm Tường Nhà Phố',
        category: 'Nhà phố',
        desc: 'Giai đoạn xây tô tường phẳng thẳng và đi hệ thống ống điện nước âm tường chuẩn kỹ thuật tại công trình nhà phố.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi Công Hoàn Thiện Mặt Tiền Biệt Thự & Nhà Phố Liền Kề',
        category: 'Biệt thự',
        desc: 'Hoàn thiện mặt tiền kiến trúc, chống thấm ngoài trời và ốp lát trang trí mang lại vẻ đẹp sang trọng, bền vững theo thời gian.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thi Công Văn Phòng Công Ty & Cải Tạo Nâng Tầng Trọn Gói',
        category: 'Văn phòng',
        desc: 'Giải pháp thi công xây mới và cải tạo không gian văn phòng làm việc kết hợp nhà ở gia đình tại Đà Nẵng.'
      }
    ];

    // Danh sách 10 ảnh Các dự án ở Đà Nẵng từ Google Drive của khách hàng
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự Án Thiết Kế & Thi Công Nhà Phố Hiện Đại Quận Cẩm Lệ – Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        desc: 'Công trình nhà phố hiện đại tại Phường Cẩm Lệ, TP Đà Nẵng do Công ty Tống Thành Gia thiết kế và thi công trọn gói.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự Án Nhà Phố 3 Tầng Khu Đô Thị Hòa Xuân – Cẩm Lệ, Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        desc: 'Mẫu nhà phố 3 tầng phong cách hiện đại, mặt tiền thoáng rộng đón gió tự nhiên tại Khu đô thị sinh thái Hòa Xuân, Đà Nẵng.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự Án Biệt Thự Nghỉ Dưỡng Cao Cấp Quận Sơn Trà – Đà Nẵng',
        category: 'Biệt thự Đà Nẵng',
        desc: 'Thiết kế và thi công hoàn thiện biệt thự hiện đại không gian mở kết hợp sân vườn xanh mát tại Quận Sơn Trà, TP Đà Nẵng.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự Án Căn Hộ Dịch Vụ & Khách Sạn Quận Ngũ Hành Sơn – Đà Nẵng',
        category: 'Căn hộ - Khách sạn',
        desc: 'Công trình tòa nhà căn hộ cho thuê và lưu trú du lịch thiết kế tối ưu hiệu suất đầu tư tại Ngũ Hành Sơn, Đà Nẵng.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự Án Nhà Phố Kết Hợp Kinh Doanh Quận Hải Châu – Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        desc: 'Thi công trọn gói nhà phố vừa ở vừa kết hợp văn phòng kinh doanh tại trung tâm Quận Hải Châu, TP Đà Nẵng.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự Án Biệt Thự 2 Mặt Tiền Khu Nam Việt Á – Đà Nẵng',
        category: 'Biệt thự Đà Nẵng',
        desc: 'Công trình biệt thự 2 mặt tiền sang trọng với kiến trúc hình khối mạnh mẽ, vật liệu hoàn thiện cao cấp tại Khu Nam Việt Á, Đà Nẵng.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự Án Nhà Phố 3 Tầng 1 Tum Quận Liên Chiểu – Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        desc: 'Thiết kế kiến trúc và thi công trọn gói nhà phố 3 tầng 1 tum đầy đủ công năng cho gia đình đa thế hệ tại Đà Nẵng.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự Án Căn Hộ Cho Thuê Cao Cấp View Sông Hàn – Đà Nẵng',
        category: 'Căn hộ - Khách sạn',
        desc: 'Thi công xây dựng và hoàn thiện nội thất tòa căn hộ dịch vụ cao cấp tại TP Đà Nẵng.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự Án Biệt Thự Phố Hiện Đại Quận Thanh Khê – Đà Nẵng',
        category: 'Biệt thự Đà Nẵng',
        desc: 'Công trình biệt thự phố thiết kế thông tầng lấy sáng tự nhiên, thi công chuẩn chất lượng bởi Tống Thành Gia.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự Án Nhà Phố Trọn Gói Nguyễn Đình Tứ – Cẩm Lệ, Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        desc: 'Dự án tiêu biểu ngay tại khu vực Cẩm Lệ, TP Đà Nẵng khẳng định uy tín và năng lực thi công của Tống Thành Gia.'
      }
    ];

    // Nội dung chi tiết 4 bài viết tin tức
    const articlesData = [
      {
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật xây dựng',
        category: 'Kinh nghiệm thi công phần thô',
        img: 'https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1000',
        desc: 'Sau khi đổ bê tông móng hoặc sàn, việc giữ ẩm liên tục trong 7 đến 14 ngày đầu tiên giúp quá trình thủy hóa xi măng diễn ra hoàn toàn, ngăn ngừa hiện tượng rạn nứt chân chim và giúp bê tông đạt 100% mác thiết kế. Tại Tống Thành Gia, đội ngũ kỹ thuật luôn thực hiện tưới nước bảo dưỡng định kỳ và che phủ bề mặt đúng quy chuẩn.'
      },
      {
        title: '03 Nỗi lo lớn nhất khi xây nhà tại Đà Nẵng và giải pháp tối ưu',
        category: 'Tư vấn xây nhà trọn gói',
        img: 'https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1000',
        desc: '3 nỗi lo lớn nhất của Chủ đầu tư là: Phát sinh chi phí ngoài dự kiến, Vật tư không đúng cam kết và Chậm trễ tiến độ bàn giao. Khi hợp tác cùng Công ty TNHH ĐTXD & TM Tống Thành Gia, mọi hạng mục vật tư đều được quy định rõ trong hợp đồng kèm bảng dự toán minh bạch 100%.'
      },
      {
        title: 'Tâm lý học không gian: Thiết kế kiến trúc & nội thất tác động thế nào?',
        category: 'Thiết kế Kiến trúc – Nội thất',
        img: 'https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1000',
        desc: 'Không gian sống có ảnh hưởng trực tiếp đến cảm xúc và sức khỏe của các thành viên trong gia đình. Các thiết kế của Tống Thành Gia luôn ưu tiên giếng trời, đối lưu không khí tự nhiên và bố trí ánh sáng hài hòa theo phong thủy.'
      },
      {
        title: 'Quy trình kiểm tra nghiệm thu cốt thép và cốt pha trước khi đổ bê tông',
        category: 'Tiêu chuẩn kỹ thuật',
        img: 'https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1000',
        desc: 'Trước mỗi mẻ đổ bê tông, kỹ sư giám sát của Tống Thành Gia cùng Chủ đầu tư kiểm tra kỹ lưỡng chủng loại thép, khoảng cách đai cột, dầm, con kê bê tông bảo vệ lớp thép và độ chắc chắn của hệ giáo chống cốt pha.'
      }
    ];

    // Hàm hiển thị 9 ảnh thực tế thi công xây dựng (Không có nhãn dán trên ảnh, chia 2 cột trên điện thoại, tên đầy đủ)
    function renderConstruction(filterCat = 'all') {
      const grid = document.getElementById('construction-grid');
      const filtered = filterCat === 'all'
        ? constructionItems
        : constructionItems.filter(item => item.category === filterCat);

      grid.innerHTML = filtered.map((item, idx) => `
        <div class="box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition cursor-pointer" onclick="openItemModal('construction', ${idx}, '${filterCat}')">
          <div>
            <div class="box-image h-36 sm:h-52 overflow-hidden bg-slate-200">
              <img
                src="https://drive.google.com/thumbnail?id=${item.id}&sz=w800"
                onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/${item.id}=w800';"
                alt="${item.title}"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                loading="lazy"
              >
            </div>
            <div class="box-text p-2.5 sm:p-3.5">
              <h3 class="product-title-full">${item.title}</h3>
              <p class="text-[11px] sm:text-xs text-slate-600 mt-1 leading-relaxed">${item.desc}</p>
            </div>
          </div>
          <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
            <span class="text-[11px] font-semibold text-amber-600">${item.category}</span>
            <span class="text-[11px] font-bold text-brand hover:underline">Xem ảnh lớn <i class="fa-solid fa-expand ml-0.5"></i></span>
          </div>
        </div>
      `).join('');
    }

    function filterConstruction(cat) {
      document.querySelectorAll('#construction-filter-bar .cat-pill-btn').forEach(btn => {
        btn.classList.toggle('active', btn.getAttribute('data-cat') === cat);
      });
      renderConstruction(cat);
    }

    // Hàm hiển thị 10 dự án ở Đà Nẵng (Không có nhãn dán trên ảnh, chia 2 cột trên điện thoại, tên đầy đủ)
    function renderDanang(filterCat = 'all') {
      const grid = document.getElementById('danang-grid');
      const filtered = filterCat === 'all'
        ? danangProjects
        : danangProjects.filter(item => item.category === filterCat);

      grid.innerHTML = filtered.map((item, idx) => `
        <div class="box bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition cursor-pointer" onclick="openItemModal('danang', ${idx}, '${filterCat}')">
          <div>
            <div class="box-image h-36 sm:h-44 overflow-hidden bg-slate-200">
              <img
                src="https://drive.google.com/thumbnail?id=${item.id}&sz=w800"
                onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/${item.id}=w800';"
                alt="${item.title}"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                loading="lazy"
              >
            </div>
            <div class="box-text p-2.5 sm:p-3">
              <h3 class="product-title-full">${item.title}</h3>
              <p class="text-[11px] text-slate-600 mt-1 leading-relaxed">${item.desc}</p>
            </div>
          </div>
          <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
            <span class="text-[10.5px] font-semibold text-amber-600">${item.category}</span>
            <span class="text-[11px] font-bold text-brand">Chi tiết</span>
          </div>
        </div>
      `).join('');
    }

    function filterDanang(cat) {
      document.querySelectorAll('#danang-filter-bar .cat-pill-btn').forEach(btn => {
        btn.classList.toggle('active', btn.getAttribute('data-dncat') === cat);
      });
      renderDanang(cat);
    }

    // Modal xem chi tiết công trình / dự án
    function openItemModal(type, idx, currentFilter) {
      const sourceList = type === 'construction' ? constructionItems : danangProjects;
      const filtered = currentFilter === 'all'
        ? sourceList
        : sourceList.filter(i => i.category === currentFilter);
      const item = filtered[idx];
      if (!item) return;

      document.getElementById('modalTitle').textContent = item.title;
      document.getElementById('modalImage').src = `https://drive.google.com/thumbnail?id=${item.id}&sz=w1200`;
      document.getElementById('modalCategory').textContent = `Danh mục: ${item.category} | Đơn vị thực hiện: TỐNG THÀNH GIA`;
      document.getElementById('modalDesc').textContent = item.desc;

      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function openArticleModal(idx) {
      const item = articlesData[idx];
      if (!item) return;
      document.getElementById('modalTitle').textContent = item.title;
      document.getElementById('modalImage').src = item.img;
      document.getElementById('modalCategory').textContent = item.category;
      document.getElementById('modalDesc').textContent = item.desc;

      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    // Xử lý 2 Banner tự trượt chuyên nghiệp
    let currentSlide = 0;
    const totalSlides = 2;
    let slideTimer = null;

    function showHeroSlide(index) {
      currentSlide = (index + totalSlides) % totalSlides;
      const slides = document.querySelectorAll('.hero-slide-item');
      const dots = document.querySelectorAll('.hero-dot');

      slides.forEach((s, i) => {
        s.classList.toggle('active', i === currentSlide);
      });
      dots.forEach((d, i) => {
        if (i === currentSlide) {
          d.className = 'hero-dot w-6 h-2 rounded-full bg-amber-500 transition';
        } else {
          d.className = 'hero-dot w-2.5 h-2 rounded-full bg-white/60 transition';
        }
      });
    }

    function changeHeroSlide(step) {
      showHeroSlide(currentSlide + step);
      resetSlideTimer();
    }

    function goToHeroSlide(index) {
      showHeroSlide(index);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideTimer) clearInterval(slideTimer);
      slideTimer = setInterval(() => {
        showHeroSlide(currentSlide + 1);
      }, 5000);
    }

    // Menu điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobile-drawer');
      const icon = document.getElementById('mobile-menu-icon');
      const isHidden = drawer.classList.contains('hidden');
      drawer.classList.toggle('hidden', !isHidden);
      icon.className = isHidden ? 'fa-solid fa-xmark text-sm' : 'fa-solid fa-bars text-sm';
    }

    // Xử lý gửi Form Yêu cầu và Báo giá trang chủ
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('q_name').value.trim();
      const phone = document.getElementById('q_phone').value.trim();
      const type = document.getElementById('q_type').value;
      const budget = document.getElementById('q_budget').value;
      const msgBox = document.getElementById('quoteSuccessMsg');

      msgBox.innerHTML = `Cảm ơn Quý khách <strong>${name}</strong> (${phone})! Yêu cầu báo giá hạng mục <strong>${type}</strong> (Mức đầu tư: ${budget}) đã được gửi tới <strong>CÔNG TY TNHH ĐTXD & TM TỐNG THÀNH GIA</strong>. Hotline <strong>0934.484.843</strong> sẽ liên hệ tư vấn Quý khách trong thời gian sớm nhất!`;
      msgBox.classList.remove('hidden');
      document.getElementById('quoteRequestForm').reset();
    }

    // Khởi chạy khi tải trang
    window.addEventListener('DOMContentLoaded', () => {
      renderConstruction('all');
      renderDanang('all');
      resetSlideTimer();
    });
  </script>
</body>
</html>
