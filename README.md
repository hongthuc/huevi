<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
  <title>CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ | Thiết Kế &amp; Thi Công Trọn Gói Đà Nẵng - huevi.com</title>
  <meta name="description" content="Công Ty TNHH Xây Dựng và Thương Mại Huệ Vĩ (huevi.com) chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0907.836.324." />
  <link rel="canonical" href="https://huevi.com/" />

  <!-- Meta Open Graph & Twitter Card (Thumbnail Logo khi chia sẻ link trên Zalo, Facebook) -->
  <meta property="og:type" content="website" />
  <meta property="og:locale" content="vi_VN" />
  <meta property="og:site_name" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ" />
  <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ - huevi.com" />
  <meta property="og:description" content="Chuyên Thiết Kế Kiến Trúc - Thi Công Phần Thô - Hoàn Thiện &amp; Xây Nhà Trọn Gói Chuyên Nghiệp Tại Đà Nẵng. Hotline: 0907.836.324." />
  <meta property="og:url" content="https://huevi.com/" />
  <meta property="og:image" content="https://huevi.com/wp-content/uploads/logo-huevi-thumbnail.png" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta property="og:image:alt" content="Logo Công Ty TNHH Xây Dựng và Thương Mại Huệ Vĩ" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ - huevi.com" />
  <meta name="twitter:description" content="Thiết kế kiến trúc, thi công phần thô, hoàn thiện &amp; xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0907.836.324." />
  <meta name="twitter:image" content="https://huevi.com/wp-content/uploads/logo-huevi-thumbnail.png" />

  <!-- Favicon Logo SVG (Tự động hiển thị biểu tượng Huệ Vĩ trên tab trình duyệt) -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230E3A5D'/%3E%3Cpath d='M12 30L32 13L52 30H45V50H36V36H28V50H19V30H12Z' fill='%23FFFFFF'/%3E%3Cpath d='M32 13L52 30H45L32 19L19 30H12L32 13Z' fill='%23D98218'/%3E%3C/svg%3E" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

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
            brand: {
              navy: '#0E3A5D',      // Màu chủ đạo từ Logo
              navyDark: '#092740',  // Navy đậm cho footer & hover
              navyLight: '#17507D', // Navy sáng hơn cho chi tiết nhấn
              gold: '#D98218',      // Màu vàng đồng kiến trúc từ Logo
              goldHover: '#B96B0E', // Hover vàng đồng
              soft: '#F4F7FA',      // Nền xám xanh nhẹ chuẩn Flatsome
            }
          }
        }
      }
    };
  </script>

  <style>
    /* =====================================================================
       THIẾT LẬP CHỐNG TRÀN VIỀN & TỐI ƯU KHUNG 95% TRÊN MÁY TÍNH (FLATSOME)
       ===================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
    }

    body {
      font-family: 'Inter', sans-serif;
      color: #1e293b;
      background-color: #ffffff;
      overflow-x: hidden;
      width: 100%;
      margin: 0;
      padding: 0;
    }

    /* Khung container 95% trên máy tính, tối ưu gọn gàng trên điện thoại */
    .hv-container {
      width: 94%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
    }

    @media (min-width: 1024px) {
      .hv-container {
        width: 95%;
        max-width: 95%;
      }
    }

    /* Ẩn thanh cuộn cho dải danh mục cuộn ngang trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Hiệu ứng ảnh Flatsome UX Builder mượt mà */
    .flatsome-card-img {
      transition: transform 0.55s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    }
    .flatsome-card:hover .flatsome-card-img {
      transform: scale(1.06);
    }

    /* Đường kẻ tiêu đề chuẩn Flatsome */
    .flatsome-title-line {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-title-line::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background: linear-gradient(90deg, #0E3A5D 0%, #D98218 100%);
      border-radius: 999px;
    }

    .flatsome-title-left {
      position: relative;
      display: inline-block;
      padding-bottom: 8px;
    }
    .flatsome-title-left::after {
      content: '';
      position: absolute;
      left: 0;
      bottom: 0;
      width: 56px;
      height: 3px;
      background: #D98218;
      border-radius: 999px;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes hvPulse {
      0% { box-shadow: 0 0 0 0 rgba(217, 130, 24, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(217, 130, 24, 0); }
      100% { box-shadow: 0 0 0 0 rgba(217, 130, 24, 0); }
    }
    .hv-pulse-gold {
      animation: hvPulse 2s infinite;
    }

    @keyframes hvPulseBlue {
      0% { box-shadow: 0 0 0 0 rgba(0, 104, 255, 0.45); }
      70% { box-shadow: 0 0 0 10px rgba(0, 104, 255, 0); }
      100% { box-shadow: 0 0 0 0 rgba(0, 104, 255, 0); }
    }
    .hv-pulse-zalo {
      animation: hvPulseBlue 2.4s infinite;
    }
  </style>
</head>

<body class="bg-white text-slate-800 antialiased pb-16 md:pb-0">

  <!-- =====================================================================
       FLATSOME TOP BAR (Sạch gọn, không hiển thị thanh chỉnh sửa UX Builder)
       ===================================================================== -->
  <div class="bg-brand-navy text-white text-xs border-b border-white/10">
    <div class="hv-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 min-w-0">
        <span class="inline-flex items-center gap-1.5 whitespace-nowrap">
          <i class="fa-solid fa-phone text-brand-gold text-[11px]"></i>
          <a href="tel:0907836324" class="hover:text-brand-gold transition font-medium">0907.836.324</a>
        </span>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5 truncate">
          <i class="fa-solid fa-location-dot text-brand-gold text-[11px]"></i>
          <span class="truncate">H41/15/14B Kiệt 119 Phạm Như Xương, Hòa Khánh, Đà Nẵng</span>
        </span>
      </div>
      <div class="flex items-center gap-3 shrink-0">
        <span class="hidden md:inline text-white/80">Website: <strong class="text-white">huevi.com</strong></span>
        <span class="hidden md:inline text-white/30">|</span>
        <span class="text-white/90 text-[11px] sm:text-xs">MST: 0402177293</span>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       FLATSOME MAIN HEADER (Logo nhỏ gọn, Menu 1 hàng, KHÔNG nút gọi ngay)
       ===================================================================== -->
  <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200/80 shadow-sm">
    <div class="hv-container h-16 lg:h-[70px] flex items-center justify-between gap-3">
      <!-- Logo Công Ty Chuyên Nghiệp, Chỉnh Gọn Nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none" aria-label="Trang chủ Công Ty TNHH Xây Dựng và Thương Mại Huệ Vĩ">
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0 transition-transform duration-300 group-hover:scale-105" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Huệ Vĩ">
          <rect width="64" height="64" rx="12" fill="#0E3A5D"/>
          <!-- Khung mái kiến trúc vàng đồng -->
          <path d="M11 30L32 12L53 30H46.5L32 17.8L17.5 30H11Z" fill="#D98218"/>
          <!-- Khối tòa nhà và chữ cách điệu HV -->
          <path d="M18 31H24.5V40H32.5V31H39V51H32.5V45H24.5V51H18V31Z" fill="#FFFFFF"/>
          <path d="M41.5 31H47.5L43.5 51H39.8L41.5 31Z" fill="#D98218"/>
          <!-- Đường nền móng vững chắc -->
          <rect x="14" y="53" width="36" height="2.6" rx="1.3" fill="#D98218"/>
        </svg>
        <div class="flex flex-col leading-tight">
          <span class="text-[15px] sm:text-[17px] font-extrabold tracking-tight text-brand-navy">HUỆ VĨ</span>
          <span class="text-[9.5px] sm:text-[10.5px] font-semibold tracking-wider text-brand-gold uppercase">Xây Dựng &amp; Thương Mại</span>
        </div>
      </a>

      <!-- Menu Chính Trên Máy Tính (Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng) -->
      <nav class="hidden lg:flex items-center justify-end gap-4 xl:gap-6 flex-1 min-w-0" aria-label="Điều hướng chính">
        <a href="#trang-chu" class="text-[12.5px] xl:text-[13.5px] font-semibold text-brand-navy hover:text-brand-gold transition whitespace-nowrap py-2">Trang chủ</a>
        <a href="#gioi-thieu" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Giới thiệu</a>
        <a href="#dich-vu" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Dự án Đà Nẵng</a>
        <a href="#bao-gia" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Báo giá</a>
        <a href="#doi-tac" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Đối tác</a>
        <a href="#tin-tuc" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Bài viết</a>
        <a href="#lien-he" class="text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-2">Liên hệ</a>
      </nav>

      <!-- Nút Mở Menu Mobile -->
      <button id="mobile-menu-btn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-navy hover:bg-slate-50 transition" aria-label="Mở menu điều hướng" aria-expanded="false">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>

    <!-- Menu Mobile Trượt Xuống Mượt Mà -->
    <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="hv-container py-3 flex flex-col divide-y divide-slate-100">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 text-sm font-semibold text-brand-navy hover:text-brand-gold">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Giới thiệu</a>
        <a href="#dich-vu" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Dự án tại Đà Nẵng</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Yêu cầu &amp; Báo giá</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Đối tác</a>
        <a href="#tin-tuc" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Bài viết kiến thức</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-gold">Bản đồ &amp; Liên hệ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu">

    <!-- =====================================================================
         FLATSOME UX SLIDER: 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         - Hình ảnh và chữ nằm gọn hoàn toàn bên trong banner
         - Chữ cách xa viền ảnh banner (padding rộng an toàn cả mobile & PC)
         - Không bị cắt chữ hay lệch bố cục trên mọi kích thước màn hình
         ===================================================================== -->
    <section class="w-full bg-brand-navyDark py-3 sm:py-4">
      <div class="hv-container">
        <div id="hero-slider" class="relative w-full overflow-hidden rounded-xl shadow-lg bg-brand-navy">
          <!-- Track chứa 2 Slide kích thước bằng nhau tuyệt đối -->
          <div id="slider-track" class="flex transition-transform duration-700 ease-out w-full">

            <!-- SLIDE 1 -->
            <div class="w-full shrink-0 relative min-h-[340px] sm:min-h-[410px] lg:min-h-[470px] flex items-center">
              <img
                src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                alt="Thi công xây dựng trọn gói Công Ty TNHH Xây Dựng và Thương Mại Huệ Vĩ"
                class="hv-img absolute inset-0 w-full h-full object-cover object-center"
              />
              <!-- Lớp phủ chuyển màu đậm để chữ luôn sắc nét -->
              <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/95 via-brand-navy/80 to-brand-navy/40"></div>

              <!-- Nội dung chữ cách xa viền ảnh banner (px-10 sm:px-16 lg:px-24) -->
              <div class="relative z-10 w-full px-10 sm:px-16 lg:px-24 py-10 sm:py-14">
                <div class="max-w-2xl">
                  <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-brand-gold mb-2.5">
                    CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ
                  </p>
                  <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug sm:leading-tight mb-3.5">
                    Thiết Kế &amp; Thi Công Xây Dựng Trọn Gói Chuyên Nghiệp Tại Đà Nẵng
                  </h1>
                  <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-6">
                    Cam kết chuẩn kỹ thuật kết cấu, vật tư chính hãng minh bạch, giám sát trực tiếp từng hạng mục và bàn giao đúng tiến độ cho mọi công trình nhà phố, biệt thự, căn hộ.
                  </p>
                  <div class="flex flex-wrap items-center gap-3">
                    <a href="#bao-gia" class="inline-flex items-center gap-2 bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg shadow transition">
                      <span>Nhận báo giá miễn phí</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="#du-an-da-nang" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg backdrop-blur-sm transition">
                      <span>Xem dự án Đà Nẵng</span>
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <!-- SLIDE 2 (Cùng chiều cao tối thiểu và khoảng cách lề y hệt Slide 1) -->
            <div class="w-full shrink-0 relative min-h-[340px] sm:min-h-[410px] lg:min-h-[470px] flex items-center">
              <img
                src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                data-fallback="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                alt="Kiến tạo không gian sống bền vững tại Đà Nẵng - Huệ Vĩ"
                class="hv-img absolute inset-0 w-full h-full object-cover object-center"
              />
              <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/95 via-brand-navy/80 to-brand-navy/40"></div>

              <div class="relative z-10 w-full px-10 sm:px-16 lg:px-24 py-10 sm:py-14">
                <div class="max-w-2xl">
                  <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-brand-gold mb-2.5">
                    AN TOÀN • CHẤT LƯỢNG • TIẾN ĐỘ • BẢO HÀNH DÀI LÂU
                  </p>
                  <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug sm:leading-tight mb-3.5">
                    Kiến Tạo Tổ Ấm Vững Bền – Tiêu Chuẩn Công Trình Thực Tế
                  </h2>
                  <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-6">
                    Đội ngũ kỹ sư và thợ lành nghề của Huệ Vĩ trực tiếp thi công phần thô, hoàn thiện kiến trúc và cung ứng vật tư xây dựng chất lượng cao với chi phí tối ưu nhất.
                  </p>
                  <div class="flex flex-wrap items-center gap-3">
                    <a href="#cong-trinh" class="inline-flex items-center gap-2 bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg shadow transition">
                      <span>Xem công trình thực tế</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="tel:0907836324" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg backdrop-blur-sm transition">
                      <i class="fa-solid fa-phone text-xs"></i>
                      <span>Hotline: 0907.836.324</span>
                    </a>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển trái / phải đặt sát mép gọn gàng, không đè lên chữ -->
          <button id="slider-prev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
          </button>
          <button id="slider-next" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
          </button>

          <!-- Chấm chỉ báo Slide -->
          <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" data-slide="0" aria-label="Slide 1" class="slider-dot w-7 h-2 rounded-full bg-brand-gold transition-all"></button>
            <button type="button" data-slide="1" aria-label="Slide 2" class="slider-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: DỊCH VỤ TIÊU BIỂU (Lấy theo danh mục web mẫu Tín Trường Thịnh)
         ===================================================================== -->
    <section id="dich-vu" class="py-10 sm:py-14 bg-white">
      <div class="hv-container">
        <div class="text-center mb-8 sm:mb-10">
          <h2 class="flatsome-title-line text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
            Dịch Vụ &amp; Lĩnh Vực Hoạt Động
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Cung cấp giải pháp xây dựng toàn diện từ tư vấn thiết kế, thi công phần thô, hoàn thiện kiến trúc đến cung ứng vật tư thương mại tại Đà Nẵng và miền Trung.
          </p>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Dịch vụ 1 -->
          <div class="bg-brand-soft hover:bg-white border border-slate-200/80 hover:border-brand-gold/50 rounded-xl p-4 sm:p-6 transition shadow-sm hover:shadow-md flex flex-col">
            <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5">
              <i class="fa-solid fa-compass-drafting text-lg sm:text-xl"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thiết Kế Kiến Trúc – Nội Thất</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Thiết kế nhà phố, biệt thự, khách sạn, căn hộ tối ưu công năng, ánh sáng tự nhiên và phong thủy hài hòa.
            </p>
          </div>

          <!-- Dịch vụ 2 -->
          <div class="bg-brand-soft hover:bg-white border border-slate-200/80 hover:border-brand-gold/50 rounded-xl p-4 sm:p-6 transition shadow-sm hover:shadow-md flex flex-col">
            <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5">
              <i class="fa-solid fa-helmet-safety text-lg sm:text-xl"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thi Công Phần Thô</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Thi công móng, kết cấu bê tông cốt thép, xây tô chuẩn mác, kiểm soát chặt chẽ kỹ thuật từng giai đoạn.
            </p>
          </div>

          <!-- Dịch vụ 3 -->
          <div class="bg-brand-soft hover:bg-white border border-slate-200/80 hover:border-brand-gold/50 rounded-xl p-4 sm:p-6 transition shadow-sm hover:shadow-md flex flex-col">
            <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5">
              <i class="fa-solid fa-trowel-bricks text-lg sm:text-xl"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thi Công Hoàn Thiện Trọn Gói</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Xây nhà chìa khóa trao tay từ ốp lát, sơn nước, điện nước M&amp;E đến lắp đặt hoàn thiện đồng bộ, không phát sinh.
            </p>
          </div>

          <!-- Dịch vụ 4 -->
          <div class="bg-brand-soft hover:bg-white border border-slate-200/80 hover:border-brand-gold/50 rounded-xl p-4 sm:p-6 transition shadow-sm hover:shadow-md flex flex-col">
            <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5">
              <i class="fa-solid fa-couch text-lg sm:text-xl"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thi Công Nội Thất &amp; Vật Tư</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Sản xuất, lắp đặt nội thất gỗ tinh tế và thương mại cung cấp vật liệu xây dựng chính hãng giá tốt.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: GIỚI THIỆU & THẾ MẠNH CỦA HUỆ VĨ
         ===================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-soft border-y border-slate-200/70">
      <div class="hv-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center mb-10">
          <!-- Cột nội dung giới thiệu -->
          <div class="lg:col-span-6">
            <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Về Chúng Tôi</p>
            <h2 class="flatsome-title-left text-xl sm:text-2xl font-extrabold text-brand-navy uppercase mb-5">
              CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ
            </h2>
            <p class="text-sm text-slate-700 leading-relaxed mb-3.5">
              <strong>HUỆ VĨ (huevi.com)</strong> là đơn vị chuyên Thiết kế – Xây dựng – Hoàn thiện và Thương mại vật tư cho các công trình <strong>Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê, Văn phòng</strong> tại khu vực TP. Đà Nẵng và lân cận.
            </p>
            <p class="text-sm text-slate-700 leading-relaxed mb-5">
              Với phương châm <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, Huệ Vĩ luôn đặt chữ <strong>TÂM</strong> và chữ <strong>TÍN</strong> lên hàng đầu trong từng bản vẽ, từng mẻ bê tông và từng chi tiết hoàn thiện, mang lại kết quả <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – CHI PHÍ MINH BẠCH</strong> cho Quý khách hàng.
            </p>
            <div class="grid grid-cols-3 gap-3 text-center">
              <div class="bg-white rounded-xl p-3.5 border border-slate-200/80 shadow-sm">
                <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">100%</div>
                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Trực tiếp thi công</div>
              </div>
              <div class="bg-white rounded-xl p-3.5 border border-slate-200/80 shadow-sm">
                <div class="text-xl sm:text-2xl font-extrabold text-brand-gold">5 Năm</div>
                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo hành kết cấu</div>
              </div>
              <div class="bg-white rounded-xl p-3.5 border border-slate-200/80 shadow-sm">
                <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">24/7</div>
                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Hỗ trợ tận tâm</div>
              </div>
            </div>
          </div>

          <!-- Cột hình ảnh thực tế giới thiệu -->
          <div class="lg:col-span-6">
            <div class="grid grid-cols-2 gap-3 sm:gap-4">
              <div class="overflow-hidden rounded-xl shadow-md bg-slate-200 aspect-[4/3]">
                <img
                  src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1000"
                  data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                  alt="Hình ảnh thi công phần thô thực tế Huệ Vĩ"
                  class="hv-img w-full h-full object-cover"
                />
              </div>
              <div class="overflow-hidden rounded-xl shadow-md bg-slate-200 aspect-[4/3]">
                <img
                  src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w1000"
                  data-fallback="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                  alt="Công trình kiến trúc hoàn thiện Huệ Vĩ"
                  class="hv-img w-full h-full object-cover"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- 6 Thế Mạnh Cốt Lõi (Giống cấu trúc web mẫu Tín Trường Thịnh) -->
        <div class="pt-4">
          <div class="text-center mb-7">
            <h3 class="flatsome-title-line text-base sm:text-xl font-extrabold text-brand-navy uppercase">
              Thế Mạnh Của Chúng Tôi
            </h3>
          </div>
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
            <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
              <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-gold flex items-center justify-center shrink-0">
                <i class="fa-solid fa-users-gear text-base"></i>
              </div>
              <div>
                <h4 class="text-sm font-bold text-brand-navy mb-1">Đội ngũ kỹ sư, kiến trúc sư chuyên nghiệp</h4>
                <p class="text-xs text-slate-600 leading-relaxed">Đội ngũ kỹ sư giàu kinh nghiệm hiện trường kết hợp tổ đội thi công lành nghề, làm việc kỷ luật và tận tâm.</p>
              </div>
            </div>
            <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
              <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-gold flex items-center justify-center shrink-0">
                <i class="fa-solid fa-layer-group text-base"></i>
              </div>
              <div>
                <h4 class="text-sm font-bold text-brand-navy mb-1">Cập nhật xu hướng &amp; vật liệu hiện đại</h4>
                <p class="text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp kiến trúc tối ưu, chống nóng, chống thấm hiệu quả phù hợp khí hậu miền Trung – Đà Nẵng.</p>
              </div>
            </div>
            <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
              <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-gold flex items-center justify-center shrink-0">
                <i class="fa-solid fa-calendar-check text-base"></i>
              </div>
              <div>
                <h4 class="text-sm font-bold text-brand-navy mb-1">Giám sát tiến độ chuẩn xác từng ngày</h4>
                <p class="text-xs text-slate-600 leading-relaxed">Báo cáo hình ảnh thi công thường xuyên giúp gia chủ dễ dàng theo dõi chất lượng công trình mọi lúc, mọi nơi.</p>
              </div>
            </div>
            <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
              <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-gold flex items-center justify-center shrink-0">
                <i class="fa-solid fa-shield-halved text-base"></i>
              </div>
              <div>
                <h4 class="text-sm font-bold text-brand-navy mb-1">Bảo hành công trình lâu dài</h4>
                <p class="text-xs text-slate-600 leading-relaxed">Chính sách hậu mãi rõ ràng, bảo hành kết cấu dài hạn và hỗ trợ kỹ thuật nhanh chóng ngay khi khách hàng cần.</p>
              </div>
            </div>
            <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
              <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-gold flex items-center justify-center shrink-0">
                <i class="fa-solid fa-file-invoice-dollar text-base"></i>
              </div>
              <div>
                <h4 class="text-sm font-bold text-brand-navy mb-1">Dự toán minh bạch – Giá cả hợp lý</h4>
                <p class="text-xs text-slate-600 leading-relaxed">Bóc tách khối lượng chi tiết từng hạng mục vật tư, tối ưu ngân sách và cam kết không phát sinh vô lý.</p>
              </div>
            </div>
            <div class="bg-white rounded-xl p-5 border border-slate-200/80 shadow-sm flex items-start gap-3.5">
              <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-gold flex items-center justify-center shrink-0">
                <i class="fa-solid fa-headset text-base"></i>
              </div>
              <div>
                <h4 class="text-sm font-bold text-brand-navy mb-1">Hỗ trợ tư vấn &amp; khảo sát miễn phí 24/7</h4>
                <p class="text-xs text-slate-600 leading-relaxed">Tư vấn pháp lý giấy phép xây dựng, lên phương án mặt bằng sơ bộ và khái toán chi phí hoàn toàn miễn phí.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: CÔNG TRÌNH THỰC TẾ & DANH MỤC SẢN PHẨM (9 ẢNH GOOGLE DRIVE)
         - Danh mục chữ nhỏ gọn, viết liền trên 1 hàng (không xuống dòng trong tên danh mục)
         - Chia đúng 2 cột trên điện thoại, 3-4 cột trên máy tính
         - Không nhãn dán trên ảnh, tên sản phẩm hiển thị đầy đủ không cắt chữ
         ===================================================================== -->
    <section id="cong-trinh" class="py-10 sm:py-14 bg-white">
      <div class="hv-container">
        <div class="text-center mb-6 sm:mb-8">
          <h2 class="flatsome-title-line text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
            Công Trình Thực Tế &amp; Sản Phẩm Thi Công
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Hình ảnh thực tế quá trình thi công phần thô, hoàn thiện và bàn giao các hạng mục công trình do Công Ty TNHH Xây Dựng &amp; Thương Mại Huệ Vĩ trực tiếp triển khai.
          </p>
        </div>

        <!-- Thanh Danh Mục Sản Phẩm Tối Ưu Đẹp Trên Máy Tính & Điện Thoại (Không xuống dòng tên danh mục) -->
        <div class="mb-6 sm:mb-8">
          <div id="product-categories" class="flex items-center lg:justify-center gap-2 overflow-x-auto lg:overflow-visible lg:flex-wrap no-scrollbar pb-1.5" role="tablist" aria-label="Danh mục công trình thực tế">
            <button type="button" data-cat="all" class="prod-cat-btn active shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white shadow-sm transition">
              Tất cả công trình
            </button>
            <button type="button" data-cat="nha-pho" class="prod-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-soft text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Nhà phố
            </button>
            <button type="button" data-cat="biet-thu" class="prod-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-soft text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Biệt thự
            </button>
            <button type="button" data-cat="khach-san" class="prod-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-soft text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Khách sạn – Căn hộ – Phòng trọ
            </button>
            <button type="button" data-cat="van-phong" class="prod-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-soft text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Văn phòng
            </button>
            <button type="button" data-cat="phan-tho" class="prod-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-soft text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Thi công phần thô
            </button>
            <button type="button" data-cat="noi-that" class="prod-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-soft text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Thi công hoàn thiện &amp; Nội thất
            </button>
          </div>
        </div>

        <!-- Lưới Sản Phẩm: 2 Cột Trên Điện Thoại, 3 Cột Trên Tablet & Laptop, 3/4 Cột Gọn Đẹp -->
        <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-3 sm:gap-5">
          <!-- Render động từ dữ liệu 9 ảnh thực tế Google Drive -->
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH GOOGLE DRIVE)
         - Chia 2 cột trên điện thoại, 4-5 cột trên máy tính
         - Không nhãn dán trên ảnh, tên dự án đầy đủ rõ nét
         ===================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-soft border-y border-slate-200/70">
      <div class="hv-container">
        <div class="text-center mb-6 sm:mb-8">
          <h2 class="flatsome-title-line text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
            Các Dự Án Tiêu Biểu Tại Đà Nẵng
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Tổng hợp các dự án nhà ở, biệt thự, căn hộ dịch vụ và công trình dân dụng đã và đang thi công thực tế tại các quận trên địa bàn TP. Đà Nẵng.
          </p>
        </div>

        <!-- Bộ lọc khu vực Đà Nẵng (Chữ nhỏ gọn, viết liền không xuống dòng) -->
        <div class="mb-6 sm:mb-8">
          <div id="danang-categories" class="flex items-center lg:justify-center gap-2 overflow-x-auto lg:overflow-visible lg:flex-wrap no-scrollbar pb-1.5" role="tablist" aria-label="Khu vực dự án Đà Nẵng">
            <button type="button" data-area="all" class="dn-cat-btn active shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white shadow-sm transition">
              Tất cả Đà Nẵng
            </button>
            <button type="button" data-area="lien-chieu" class="dn-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Liên Chiểu – Hòa Khánh
            </button>
            <button type="button" data-area="cam-le" class="dn-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Cẩm Lệ – Hòa Xuân
            </button>
            <button type="button" data-area="son-tra" class="dn-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Sơn Trà – Ngũ Hành Sơn
            </button>
            <button type="button" data-area="hai-chau" class="dn-cat-btn shrink-0 whitespace-nowrap px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 hover:bg-brand-navy hover:text-white border border-slate-200 transition">
              Hải Châu – Thanh Khê
            </button>
          </div>
        </div>

        <!-- Lưới 10 Dự Án Đà Nẵng: 2 cột Mobile, 4 cột Desktop, 5 cột Màn rộng -->
        <div id="danang-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render động từ dữ liệu 10 ảnh dự án Đà Nẵng Google Drive -->
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ MIỄN PHÍ
         (Thiết kế đồng bộ cấu trúc mẫu Tín Trường Thịnh)
         ===================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white">
      <div class="hv-container">
        <div class="bg-brand-navy rounded-2xl overflow-hidden shadow-xl">
          <div class="grid grid-cols-1 lg:grid-cols-12">
            <!-- Cột thông tin báo giá tham khảo -->
            <div class="lg:col-span-5 p-6 sm:p-8 lg:p-10 text-white flex flex-col justify-between bg-gradient-to-br from-brand-navyDark to-brand-navy">
              <div>
                <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Miễn Phí Tư Vấn &amp; Khảo Sát</p>
                <h2 class="text-xl sm:text-2xl font-extrabold uppercase leading-snug mb-4">
                  Đăng Ký Yêu Cầu &amp; Nhận Báo Giá Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-6">
                  Quý khách đang dự định xây dựng nhà phố, biệt thự, căn hộ cho thuê hay cải tạo công trình tại Đà Nẵng? Hãy để lại thông tin, kỹ sư Huệ Vĩ sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết trong vòng 24h.
                </p>

                <!-- Gói báo giá tham khảo gọn đẹp -->
                <div class="space-y-2.5 text-xs sm:text-sm">
                  <div class="flex items-center justify-between bg-white/10 rounded-lg px-4 py-2.5 border border-white/10">
                    <span class="font-medium text-slate-100">Thiết kế kiến trúc – nội thất</span>
                    <span class="font-bold text-brand-gold whitespace-nowrap ml-2">Liên hệ ưu đãi</span>
                  </div>
                  <div class="flex items-center justify-between bg-white/10 rounded-lg px-4 py-2.5 border border-white/10">
                    <span class="font-medium text-slate-100">Thi công phần thô &amp; nhân công</span>
                    <span class="font-bold text-brand-gold whitespace-nowrap ml-2">Từ 3.500.000đ/m²</span>
                  </div>
                  <div class="flex items-center justify-between bg-white/10 rounded-lg px-4 py-2.5 border border-white/10">
                    <span class="font-medium text-slate-100">Thi công hoàn thiện trọn gói</span>
                    <span class="font-bold text-brand-gold whitespace-nowrap ml-2">Từ 5.600.000đ/m²</span>
                  </div>
                </div>
              </div>

              <div class="mt-7 pt-5 border-t border-white/15 flex items-center gap-3">
                <div class="w-10 h-10 rounded-full bg-brand-gold text-white flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-phone-volume"></i>
                </div>
                <div>
                  <div class="text-[11px] text-slate-300 uppercase tracking-wider">Hotline kỹ sư tư vấn trực tiếp</div>
                  <a href="tel:0907836324" class="text-lg font-extrabold text-white hover:text-brand-gold transition">0907.836.324</a>
                </div>
              </div>
            </div>

            <!-- Cột Form nhập thông tin báo giá -->
            <div class="lg:col-span-7 p-6 sm:p-8 lg:p-10 bg-white">
              <form id="quote-form" class="space-y-4" novalidate>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div>
                    <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên <span class="text-red-500">*</span></label>
                    <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn..." class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm text-slate-800 focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 transition" />
                  </div>
                  <div>
                    <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo <span class="text-red-500">*</span></label>
                    <input id="q-phone" name="phone" type="tel" required placeholder="VD: 0907 836 324" class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm text-slate-800 focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 transition" />
                  </div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div>
                    <label for="q-email" class="block text-xs font-semibold text-slate-700 mb-1.5">Email nhận bảng dự toán</label>
                    <input id="q-email" name="email" type="email" placeholder="example@gmail.com" class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm text-slate-800 focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 transition" />
                  </div>
                  <div>
                    <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                    <select id="q-type" name="projectType" class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm text-slate-800 bg-white focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 transition">
                      <option value="Nhà phố">Nhà phố hiện đại</option>
                      <option value="Biệt thự">Biệt thự / Nhà vườn</option>
                      <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                      <option value="Văn phòng">Văn phòng – Showroom</option>
                      <option value="Thi công phần thô">Thi công phần thô</option>
                      <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa – Nâng tầng</option>
                    </select>
                  </div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div>
                    <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                    <select id="q-budget" name="budget" class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm text-slate-800 bg-white focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 transition">
                      <option value="Chưa xác định">Chưa xác định</option>
                      <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                      <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                      <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                      <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                      <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                    </select>
                  </div>
                  <div>
                    <label for="q-area" class="block text-xs font-semibold text-slate-700 mb-1.5">Diện tích đất &amp; số tầng dự kiến</label>
                    <input id="q-area" name="area" type="text" placeholder="VD: 5x20m, 3 tầng, Hòa Khánh..." class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm text-slate-800 focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 transition" />
                  </div>
                </div>

                <div>
                  <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1.5">Nội dung yêu cầu chi tiết</label>
                  <textarea id="q-note" name="note" rows="3" placeholder="Mô tả nhu cầu thi công, thời gian dự kiến khởi công..." class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm text-slate-800 focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 transition"></textarea>
                </div>

                <div id="form-error" class="hidden text-xs font-medium text-red-600 bg-red-50 border border-red-200 rounded-lg px-3.5 py-2.5"></div>

                <button type="submit" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-sm px-7 py-3 rounded-lg shadow-md transition">
                  <i class="fa-solid fa-paper-plane"></i>
                  <span>Gửi Yêu Cầu Báo Giá Ngay</span>
                </button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ ĐỒNG HÀNH
         ===================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-14 bg-brand-soft border-y border-slate-200/70">
      <div class="hv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title-line text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
            Đối Tác &amp; Nhà Cung Cấp Vật Tư
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Huệ Vĩ liên kết trực tiếp với các thương hiệu vật liệu xây dựng hàng đầu Việt Nam nhằm đảm bảo nguồn vật tư chính hãng, chuẩn mác và giá thành cạnh tranh.
          </p>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-4 gap-3 sm:gap-4">
          <!-- Đối tác 1 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">HÒA PHÁT</div>
            <div class="text-[11px] text-slate-500 mt-1">Thép xây dựng tiêu chuẩn</div>
          </div>
          <!-- Đối tác 2 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">SÔNG GIANH</div>
            <div class="text-[11px] text-slate-500 mt-1">Xi măng công trình bền vững</div>
          </div>
          <!-- Đối tác 3 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">DULUX</div>
            <div class="text-[11px] text-slate-500 mt-1">Sơn nội ngoại thất cao cấp</div>
          </div>
          <!-- Đối tác 4 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">VIGLACERA</div>
            <div class="text-[11px] text-slate-500 mt-1">Gạch ốp lát &amp; sứ vệ sinh</div>
          </div>
          <!-- Đối tác 5 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">CADIVI</div>
            <div class="text-[11px] text-slate-500 mt-1">Dây cáp điện an toàn M&amp;E</div>
          </div>
          <!-- Đối tác 6 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">XINGFA</div>
            <div class="text-[11px] text-slate-500 mt-1">Hệ nhôm kính cao cấp</div>
          </div>
          <!-- Đối tác 7 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">BÌNH MINH</div>
            <div class="text-[11px] text-slate-500 mt-1">Hệ thống ống cấp thoát nước</div>
          </div>
          <!-- Đối tác 8 -->
          <div class="bg-white border border-slate-200/80 rounded-xl p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-gold/60 transition">
            <div class="text-base sm:text-lg font-black tracking-tight text-brand-navy">AN CƯỜNG</div>
            <div class="text-[11px] text-slate-500 mt-1">Vật liệu gỗ nội thất hiện đại</div>
          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: DANH MỤC CÁC BÀI VIẾT & KIẾN THỨC XÂY DỰNG
         ===================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
      <div class="hv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title-line text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
            Tin Tức &amp; Cẩm Nang Xây Dựng
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Chia sẻ kinh nghiệm thiết kế, kỹ thuật giám sát thi công phần thô, hoàn thiện và hướng dẫn lập dự toán xây nhà tiết kiệm tại Đà Nẵng.
          </p>
        </div>

        <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
          <!-- Render động từ danh sách bài viết -->
        </div>
      </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY TRANG CHỦ
         ===================================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-brand-soft border-t border-slate-200/70">
      <div class="hv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title-line text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
            Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Ghé thăm văn phòng Công Ty TNHH Xây Dựng &amp; Thương Mại Huệ Vĩ tại Hòa Khánh, TP. Đà Nẵng hoặc theo dõi Fanpage để cập nhật công trình mới mỗi ngày.
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-6 items-stretch">
          <!-- Cột trái: Google Map Trực Quan Ngay Trang Chủ -->
          <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200/80 shadow-sm overflow-hidden flex flex-col">
            <div class="px-4 py-3 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2 min-w-0">
                <i class="fa-solid fa-map-location-dot text-brand-gold"></i>
                <h3 class="text-sm font-bold text-brand-navy truncate">Vị Trí Văn Phòng Huệ Vĩ – Đà Nẵng</h3>
              </div>
              <a
                href="https://www.google.com/maps/search/?api=1&query=H41/15/14B+Kiệt+119+Phạm+Như+Xương,+Hòa+Khánh,+Đà+Nẵng"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold text-brand-gold hover:text-brand-navy transition whitespace-nowrap"
              >
                Mở Google Maps <i class="fa-solid fa-up-right-from-square text-[10px] ml-1"></i>
              </a>
            </div>
            <div class="w-full h-[300px] sm:h-[360px] bg-slate-100 flex-1">
              <iframe
                title="Bản đồ Công Ty TNHH Xây Dựng và Thương Mại Huệ Vĩ - 119 Phạm Như Xương, Hòa Khánh, Đà Nẵng"
                src="https://maps.google.com/maps?q=119%20Ph%E1%BA%A1m%20Nh%C6%B0%20X%C6%B0%C6%A1ng,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
            <div class="px-4 py-3 bg-slate-50 text-xs text-slate-600 flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brand-navy mt-0.5 shrink-0"></i>
              <span><strong>Địa chỉ:</strong> H41/15/14B Kiệt 119 Phạm Như Xương, Phường Hòa Khánh, TP Đà Nẵng</span>
            </div>
          </div>

          <!-- Cột phải: Fanpage Facebook Ngay Trên Trang Chủ -->
          <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200/80 shadow-sm overflow-hidden flex flex-col">
            <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between">
              <div class="flex items-center gap-2">
                <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                <h3 class="text-sm font-bold text-brand-navy">Fanpage Chính Thức</h3>
              </div>
              <span class="text-[11px] text-slate-500">facebook.com/huevicom</span>
            </div>

            <!-- Khối hiển thị Fanpage trực quan (luôn hiển thị đẹp không bị chặn bởi trình duyệt) -->
            <div class="p-4 flex-1 flex flex-col justify-between">
              <div class="rounded-xl overflow-hidden border border-slate-200 bg-white">
                <!-- Ảnh bìa Fanpage -->
                <div class="relative h-32 sm:h-36 bg-brand-navy">
                  <img
                    src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w900"
                    data-fallback="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w900"
                    alt="Ảnh bìa Fanpage Xây Dựng Huệ Vĩ"
                    class="hv-img w-full h-full object-cover opacity-80"
                  />
                  <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navyDark/35 to-transparent"></div>
                  <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                    <!-- Avatar Logo Fanpage -->
                    <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white shadow flex items-center justify-center shrink-0 p-1">
                      <svg class="w-full h-full" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect width="64" height="64" rx="10" fill="#0E3A5D"/>
                        <path d="M11 30L32 12L53 30H46.5L32 17.8L17.5 30H11Z" fill="#D98218"/>
                        <path d="M18 31H24.5V40H32.5V31H39V51H32.5V45H24.5V51H18V31Z" fill="#FFFFFF"/>
                        <path d="M41.5 31H47.5L43.5 51H39.8L41.5 31Z" fill="#D98218"/>
                      </svg>
                    </div>
                    <div class="min-w-0">
                      <div class="text-white font-bold text-sm leading-tight truncate">Xây Dựng &amp; Thương Mại Huệ Vĩ</div>
                      <div class="text-slate-200 text-[11px] mt-0.5">Nhà thầu xây dựng • Đà Nẵng</div>
                    </div>
                  </div>
                </div>

                <!-- Nút hành động Fanpage -->
                <div class="p-3.5 bg-slate-50 border-b border-slate-100 flex items-center justify-between gap-2">
                  <div class="text-xs text-slate-600">
                    <strong class="text-slate-800">Cập nhật tiến độ</strong> công trình hàng ngày
                  </div>
                  <a
                    href="https://www.facebook.com/"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center gap-1.5 bg-[#1877F2] hover:bg-[#1465D0] text-white text-xs font-semibold px-3 py-1.5 rounded-md transition whitespace-nowrap"
                  >
                    <i class="fa-brands fa-facebook-f text-[11px]"></i>
                    <span>Theo dõi Trang</span>
                  </a>
                </div>

                <!-- Bài đăng nổi bật trên Fanpage -->
                <div class="p-3.5 space-y-3 text-xs text-slate-600">
                  <div class="flex items-start gap-2.5">
                    <img
                      src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w300"
                      data-fallback="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w300"
                      alt="Tiến độ thi công thực tế Huệ Vĩ"
                      class="hv-img w-14 h-14 rounded-lg object-cover shrink-0 bg-slate-200"
                    />
                    <div class="min-w-0">
                      <p class="font-semibold text-slate-800 leading-snug">Nghiệm thu cốt thép dầm sàn &amp; đổ bê tông công trình nhà phố tại Hòa Khánh, Đà Nẵng.</p>
                      <p class="text-[11px] text-slate-400 mt-1">Xây Dựng Huệ Vĩ • huevi.com</p>
                    </div>
                  </div>
                  <div class="flex items-start gap-2.5 pt-2.5 border-t border-slate-100">
                    <img
                      src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w300"
                      data-fallback="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w300"
                      alt="Bàn giao công trình hoàn thiện Đà Nẵng"
                      class="hv-img w-14 h-14 rounded-lg object-cover shrink-0 bg-slate-200"
                    />
                    <div class="min-w-0">
                      <p class="font-semibold text-slate-800 leading-snug">Hoàn thiện bàn giao chìa khóa trao tay công trình dân dụng đúng tiến độ cam kết.</p>
                      <p class="text-[11px] text-slate-400 mt-1">Hotline tư vấn: 0907.836.324</p>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Nút nhắn tin Messenger trực tiếp -->
              <div class="mt-3.5 grid grid-cols-2 gap-2.5">
                <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 bg-[#1877F2]/10 hover:bg-[#1877F2] text-[#1877F2] hover:text-white font-semibold text-xs py-2.5 rounded-lg transition">
                  <i class="fa-brands fa-facebook-messenger"></i>
                  <span>Nhắn tin Fanpage</span>
                </a>
                <a href="https://zalo.me/0907836324" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 bg-[#0068FF]/10 hover:bg-[#0068FF] text-[#0068FF] hover:text-white font-semibold text-xs py-2.5 rounded-lg transition">
                  <i class="fa-solid fa-comment-dots"></i>
                  <span>Chat Zalo Nhanh</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- =====================================================================
       FLATSOME FOOTER (Chuẩn màu thương hiệu Logo Huệ Vĩ)
       ===================================================================== -->
  <footer class="bg-brand-navyDark text-slate-300 pt-12 pb-6">
    <div class="hv-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-9 border-b border-white/10">
        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-5">
          <div class="flex items-center gap-2.5 mb-4">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect width="64" height="64" rx="12" fill="#0E3A5D"/>
              <path d="M11 30L32 12L53 30H46.5L32 17.8L17.5 30H11Z" fill="#D98218"/>
              <path d="M18 31H24.5V40H32.5V31H39V51H32.5V45H24.5V51H18V31Z" fill="#FFFFFF"/>
              <path d="M41.5 31H47.5L43.5 51H39.8L41.5 31Z" fill="#D98218"/>
              <rect x="14" y="53" width="36" height="2.6" rx="1.3" fill="#D98218"/>
            </svg>
            <div>
              <div class="text-white font-extrabold text-sm sm:text-base tracking-wide">CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ</div>
              <div class="text-brand-gold text-xs font-semibold">huevi.com</div>
            </div>
          </div>
          <ul class="space-y-2.5 text-xs sm:text-[13px] leading-relaxed">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-brand-gold mt-1 shrink-0"></i>
              <span><strong>Trụ sở:</strong> H41/15/14B Kiệt 119 Phạm Như Xương, Phường Hòa Khánh, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-brand-gold shrink-0"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0907836324" class="text-white font-semibold hover:text-brand-gold transition">0907.836.324</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-globe text-brand-gold shrink-0"></i>
              <span><strong>Website:</strong> <a href="https://huevi.com" class="text-white hover:text-brand-gold transition">https://huevi.com</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-building-shield text-brand-gold shrink-0"></i>
              <span><strong>Mã số thuế:</strong> 0402177293</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3">
          <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 pb-2 border-b border-white/15 inline-block">Lĩnh Vực Hoạt Động</h4>
          <ul class="space-y-2 text-xs sm:text-[13px]">
            <li><a href="#dich-vu" class="hover:text-brand-gold transition">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-gold transition">Thi công xây dựng phần thô</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-gold transition">Thi công hoàn thiện nhà trọn gói</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-gold transition">Cải tạo, sửa chữa &amp; nâng tầng</a></li>
            <li><a href="#doi-tac" class="hover:text-brand-gold transition">Cung ứng vật tư xây dựng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục nhanh -->
        <div class="lg:col-span-4">
          <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 pb-2 border-b border-white/15 inline-block">Danh Mục Công Trình</h4>
          <div class="grid grid-cols-2 gap-2 text-xs sm:text-[13px]">
            <a href="#cong-trinh" class="hover:text-brand-gold transition">Nhà phố hiện đại</a>
            <a href="#cong-trinh" class="hover:text-brand-gold transition">Biệt thự sang trọng</a>
            <a href="#cong-trinh" class="hover:text-brand-gold transition">Khách sạn – Căn hộ</a>
            <a href="#cong-trinh" class="hover:text-brand-gold transition">Văn phòng làm việc</a>
            <a href="#du-an-da-nang" class="hover:text-brand-gold transition">Dự án tại Đà Nẵng</a>
            <a href="#bao-gia" class="hover:text-brand-gold transition">Nhận báo giá nhanh</a>
          </div>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <p>Copyright © 2026 <strong class="text-white">CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ</strong>. All rights reserved.</p>
        <p>Thiết kế chuẩn giao diện Flatsome • <span class="text-brand-gold font-medium">huevi.com</span></p>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       - Tương thích mượt mà trên cả Máy Tính và Điện Thoại
       ===================================================================== -->
  <!-- Phiên bản Máy Tính & Tablet (Cụm nút nổi gọn đẹp góc dưới bên phải) -->
  <div class="hidden md:flex fixed right-4 bottom-6 z-50 flex-col items-end gap-2.5">
    <a href="tel:0907836324" class="hv-pulse-gold group flex items-center gap-2.5 bg-brand-gold hover:bg-brand-goldHover text-white rounded-full pl-4 pr-3 py-2.5 shadow-lg transition">
      <span class="text-xs font-bold tracking-wide whitespace-nowrap">0907.836.324</span>
      <span class="w-8 h-8 rounded-full bg-white text-brand-gold flex items-center justify-center">
        <i class="fa-solid fa-phone text-sm"></i>
      </span>
    </a>

    <a href="https://zalo.me/0907836324" target="_blank" rel="noopener noreferrer" class="hv-pulse-zalo flex items-center gap-2.5 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full pl-4 pr-3 py-2.5 shadow-lg transition">
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
      <span class="w-8 h-8 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center">Zalo</span>
    </a>

    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2.5 bg-[#1877F2] hover:bg-[#1464CC] text-white rounded-full pl-4 pr-3 py-2.5 shadow-lg transition">
      <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
      <span class="w-8 h-8 rounded-full bg-white text-[#1877F2] flex items-center justify-center">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
    </a>

    <button id="scroll-top-btn" type="button" aria-label="Lên đầu trang" class="hidden w-10 h-10 rounded-full bg-brand-navy hover:bg-brand-navyDark text-white shadow-lg items-center justify-center transition">
      <i class="fa-solid fa-arrow-up text-xs"></i>
    </button>
  </div>

  <!-- Phiên bản Điện Thoại (Thanh liên hệ cố định dưới đáy: Hotline - Zalo - Facebook) -->
  <div class="md:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_16px_rgba(14,58,93,0.12)] px-2 py-2">
    <div class="grid grid-cols-3 gap-2">
      <a href="tel:0907836324" class="flex items-center justify-center gap-1.5 bg-brand-gold text-white font-bold text-xs py-2.5 rounded-lg shadow-sm active:scale-95 transition">
        <i class="fa-solid fa-phone text-xs"></i>
        <span>Hotline</span>
      </a>
      <a href="https://zalo.me/0907836324" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 bg-[#0068FF] text-white font-bold text-xs py-2.5 rounded-lg shadow-sm active:scale-95 transition">
        <i class="fa-solid fa-comment-dots text-xs"></i>
        <span>Zalo</span>
      </a>
      <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 bg-[#1877F2] text-white font-bold text-xs py-2.5 rounded-lg shadow-sm active:scale-95 transition">
        <i class="fa-brands fa-facebook-f text-xs"></i>
        <span>Facebook</span>
      </a>
    </div>
  </div>

  <!-- =====================================================================
       MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH / BÀI VIẾT / THÔNG BÁO BÁO GIÁ
       ===================================================================== -->
  <div id="hv-modal" class="hidden fixed inset-0 z-[60] bg-black/70 backdrop-blur-xs flex items-center justify-center p-3 sm:p-5">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
      <button id="hv-modal-close" type="button" aria-label="Đóng hộp thoại" class="sticky top-3 float-right mr-3 mt-3 z-10 w-9 h-9 rounded-full bg-slate-100 hover:bg-brand-navy hover:text-white text-slate-700 flex items-center justify-center transition">
        <i class="fa-solid fa-xmark text-base"></i>
      </button>
      <div id="hv-modal-body" class="p-5 sm:p-6 clear-both"></div>
    </div>
  </div>

  <!-- =====================================================================
       JAVASCRIPT ĐIỀU KHIỂN SLIDER, DỮ LIỆU 19 ẢNH DRIVE, LỌC DANH MỤC & FORM
       ===================================================================== -->
  <script>
    (function () {
      'use strict';

      // ===================================================================
      // 1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (GOOGLE DRIVE)
      // ===================================================================
      const constructionProducts = [
        {
          id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
          category: 'nha-pho',
          categoryLabel: 'Nhà phố',
          title: 'Thi Công Trọn Gói Nhà Phố 3 Tầng Kiến Trúc Hiện Đại',
          desc: 'Hạng mục thi công trọn gói từ móng đến hoàn thiện mặt tiền, tối ưu ánh sáng tự nhiên và không gian sinh hoạt gia đình.'
        },
        {
          id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
          category: 'phan-tho',
          categoryLabel: 'Thi công phần thô',
          title: 'Thi Công Phần Thô Kết Cấu Cốt Thép & Đổ Bê Tông Sàn',
          desc: 'Quy trình lắp dựng cốt thép đúng bản vẽ kết cấu, kiểm tra khoảng cách thép đai, con kê bê tông và nghiệm thu kỹ thuật nghiêm ngặt.'
        },
        {
          id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
          category: 'biet-thu',
          categoryLabel: 'Biệt thự',
          title: 'Thiết Kế & Thi Công Biệt Thự Hiện Đại 2 Mặt Tiền',
          desc: 'Công trình biệt thự phố thiết kế sang trọng, kết cấu kiên cố kết hợp hệ cửa kính lớn và vật liệu hoàn thiện cao cấp.'
        },
        {
          id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
          category: 'khach-san',
          categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
          title: 'Thi Công Xây Dựng Căn Hộ Cho Thuê & Khách Sạn Mini',
          desc: 'Giải pháp thiết kế và thi công căn hộ dịch vụ tối ưu số lượng phòng khai thác, hệ thống điện nước và PCCC đạt chuẩn.'
        },
        {
          id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
          category: 'noi-that',
          categoryLabel: 'Thi công hoàn thiện & Nội thất',
          title: 'Thi Công Hoàn Thiện Ốp Lát, Sơn Bả & Mặt Tiền Nhà Phố',
          desc: 'Đội thợ lành nghề thi công tô trát phẳng nét, chống thấm sàn mái, nhà vệ sinh và hoàn thiện bề mặt thẩm mỹ cao.'
        },
        {
          id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
          category: 'van-phong',
          categoryLabel: 'Văn phòng',
          title: 'Thiết Kế & Thi Công Văn Phòng Làm Việc Hiện Đại',
          desc: 'Thi công không gian văn phòng chuyên nghiệp, bố trí công năng khoa học, hệ thống chiếu sáng và điều hòa đồng bộ.'
        },
        {
          id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
          category: 'phan-tho',
          categoryLabel: 'Thi công phần thô',
          title: 'Thi Công Hệ Móng Cọc & Kết Cấu Khung Dầm Chuẩn Kỹ Thuật',
          desc: 'Thi công nền móng chịu lực chắc chắn, đảm bảo độ ổn định lâu dài cho công trình dân dụng nhiều tầng.'
        },
        {
          id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
          category: 'noi-that',
          categoryLabel: 'Thi công hoàn thiện & Nội thất',
          title: 'Thi Công Hoàn Thiện Nội Thất Phòng Khách & Bếp Sang Trọng',
          desc: 'Đồng bộ trần thạch cao, hệ đèn LED âm trần, tủ bếp và nội thất gỗ mang lại không gian ấm cúng, tiện nghi.'
        },
        {
          id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
          category: 'nha-pho',
          categoryLabel: 'Nhà phố',
          title: 'Thi Công Cải Tạo, Nâng Tầng & Hoàn Thiện Nhà Ở Dân Dụng',
          desc: 'Khảo sát hiện trạng kết cấu, gia cố móng cột an toàn và cải tạo công trình cũ thành không gian sống hiện đại.'
        }
      ];

      // ===================================================================
      // 2. DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (GOOGLE DRIVE)
      // ===================================================================
      const danangProjects = [
        {
          id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
          area: 'lien-chieu',
          location: 'Hòa Khánh – Liên Chiểu, Đà Nẵng',
          title: 'Nhà Phố 3 Tầng Khu Đô Thị Hòa Khánh – Liên Chiểu'
        },
        {
          id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
          area: 'cam-le',
          location: 'Hòa Xuân – Cẩm Lệ, Đà Nẵng',
          title: 'Nhà Phố Hiện Đại KĐT Sinh Thái Hòa Xuân – Cẩm Lệ'
        },
        {
          id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
          area: 'son-tra',
          location: 'Sơn Trà, Đà Nẵng',
          title: 'Tòa Nhà Căn Hộ Dịch Vụ Gần Biển Mỹ Khê – Sơn Trà'
        },
        {
          id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
          area: 'son-tra',
          location: 'Nam Việt Á – Ngũ Hành Sơn, Đà Nẵng',
          title: 'Biệt Thự Phố 2 Mặt Tiền KĐT Nam Việt Á – Ngũ Hành Sơn'
        },
        {
          id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
          area: 'lien-chieu',
          location: 'Phạm Như Xương – Liên Chiểu, Đà Nẵng',
          title: 'Nhà Ở Kết Hợp Kinh Doanh Phạm Như Xương – Hòa Khánh'
        },
        {
          id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
          area: 'hai-chau',
          location: 'Hải Châu, Đà Nẵng',
          title: 'Văn Phòng Đại Diện & Showroom Trung Tâm Hải Châu'
        },
        {
          id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
          area: 'cam-le',
          location: 'Phước Lý – Cẩm Lệ, Đà Nẵng',
          title: 'Nhà Phố 4 Tầng Khu Đô Thị Phước Lý – Cẩm Lệ'
        },
        {
          id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
          area: 'son-tra',
          location: 'An Thượng – Ngũ Hành Sơn, Đà Nẵng',
          title: 'Khách Sạn Boutique & Căn Hộ Biển An Thượng'
        },
        {
          id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
          area: 'lien-chieu',
          location: 'Nguyễn Chánh – Liên Chiểu, Đà Nẵng',
          title: 'Nhà Phố Gia Đình Mặt Tiền Nguyễn Chánh – Liên Chiểu'
        },
        {
          id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
          area: 'hai-chau',
          location: 'Thanh Khê – Hải Châu, Đà Nẵng',
          title: 'Công Trình Nhà Ở Hoàn Thiện Trọn Gói Quận Thanh Khê'
        }
      ];

      // ===================================================================
      // 3. DỮ LIỆU BÀI VIẾT & KIẾN THỨC XÂY DỰNG TRANG CHỦ
      // ===================================================================
      const articles = [
        {
          imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
          date: '15/11/2026',
          title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật sau khi đổ',
          excerpt: 'Bảo dưỡng ẩm bê tông đúng quy trình giúp kết cấu đạt cường độ thiết kế tối đa, hạn chế nứt chân chim và tăng tuổi thọ công trình.',
          content: 'Sau khi đổ bê tông móng và sàn từ 4–6 giờ (khi bề mặt đã se cứng), cần tiến hành giữ ẩm liên tục bằng cách phủ bao tải ẩm hoặc tưới nước dạng phun sương nhẹ nhàng. Trong 7 ngày đầu tiên, đặc biệt dưới nắng nóng miền Trung – Đà Nẵng, việc giữ ẩm đều đặn giúp quá trình thủy hóa xi măng diễn ra trọn vẹn, tránh hiện tượng co ngót gây nứt bề mặt.'
        },
        {
          imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
          date: '08/11/2026',
          title: 'Kinh nghiệm xây nhà trọn gói tại Đà Nẵng không phát sinh chi phí',
          excerpt: 'Lập hồ sơ thiết kế chi tiết, thống nhất chủng loại vật tư ngay từ hợp đồng giúp gia chủ chủ động 100% ngân sách đầu tư.',
          content: 'Để xây nhà trọn gói không phát sinh chi phí ngoài dự kiến, chủ đầu tư nên chuẩn bị bản vẽ kiến trúc – kết cấu – điện nước đầy đủ trước khi khởi công. Tại Huệ Vĩ, mọi hợp đồng đều kèm phụ lục chủng loại vật tư rõ ràng (thép, xi măng, gạch, dây điện, ống nước, sơn) giúp khách hàng hoàn toàn yên tâm về chất lượng lẫn tổng mức đầu tư.'
        },
        {
          imgId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
          date: '29/10/2026',
          title: '03 nỗi lo lớn nhất khi xây nhà và giải pháp kiểm soát từ kỹ sư Huệ Vĩ',
          excerpt: 'Chất lượng kết cấu, tiến độ thi công và chế độ bảo hành là ba yếu tố then chốt quyết định sự an tâm của mọi gia chủ.',
          content: 'Nhiều gia chủ lo ngại về tình trạng rút ruột vật tư, chậm tiến độ hoặc thấm dột sau khi vào ở. Huệ Vĩ giải quyết triệt để bằng quy trình nghiệm thu từng giai đoạn có chữ ký xác nhận của chủ đầu tư, báo cáo ảnh thực tế mỗi ngày và cam kết bảo hành kết cấu dài hạn.'
        },
        {
          imgId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
          date: '18/10/2026',
          title: 'Xu hướng thiết kế không gian sống xanh, thoáng mát cho nhà phố miền Trung',
          excerpt: 'Bố trí giếng trời, thông tầng và vật liệu cách nhiệt thông minh giúp giảm nhiệt mùa hè và tiết kiệm điện năng hiệu quả.',
          content: 'Với đặc trưng khí hậu nắng gió tại Đà Nẵng, các mẫu nhà phố do Huệ Vĩ thiết kế luôn chú trọng giải pháp thông gió chéo, giếng trời lấy sáng tự nhiên, lam chắn nắng mặt tiền hướng Tây và chống thấm nhiều lớp cho sân thượng, mang lại không gian sống mát mẻ quanh năm.'
        }
      ];

      // ===================================================================
      // HÀM TẠO LINK ẢNH GOOGLE DRIVE CÓ DỰ PHÒNG AN TOÀN
      // ===================================================================
      function driveUrl(id, size) {
        return 'https://lh3.googleusercontent.com/d/' + id + '=w' + (size || 900);
      }

      function driveFallbackUrl(id, size) {
        return 'https://drive.google.com/thumbnail?id=' + id + '&sz=w' + (size || 900);
      }

      function attachImageFallbacks(scope) {
        const imgs = (scope || document).querySelectorAll('img.hv-img');
        imgs.forEach(function (img) {
          if (img.dataset.boundError) return;
          img.dataset.boundError = '1';
          img.addEventListener('error', function () {
            if (!img.dataset.triedFallback && img.dataset.fallback) {
              img.dataset.triedFallback = '1';
              img.src = img.dataset.fallback;
            } else if (!img.dataset.triedPlaceholder) {
              img.dataset.triedPlaceholder = '1';
              img.src = 'https://placehold.co/800x600/0E3A5D/FFFFFF?text=HUE+VI+CONSTRUCTION';
            }
          });
        });
      }

      // ===================================================================
      // RENDER LƯỚI CÔNG TRÌNH THỰC TẾ (KHÔNG NHÃN DÁN, 2 CỘT MOBILE)
      // ===================================================================
      const productGrid = document.getElementById('product-grid');

      function renderProducts(filterCat) {
        if (!productGrid) return;
        const list = filterCat === 'all'
          ? constructionProducts
          : constructionProducts.filter(function (item) { return item.category === filterCat; });

        productGrid.innerHTML = list.map(function (item) {
          return (
            '<article class="flatsome-card group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col cursor-pointer" data-prod-id="' + item.id + '">' +
              '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
                '<img src="' + driveUrl(item.id, 900) + '" data-fallback="' + driveFallbackUrl(item.id, 900) + '" alt="' + item.title + '" loading="lazy" class="hv-img flatsome-card-img w-full h-full object-cover" />' +
              '</div>' +
              '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
                '<h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">' +
                  item.title +
                '</h3>' +
                '<div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-500">' +
                  '<span class="truncate pr-1">' + item.categoryLabel + '</span>' +
                  '<span class="text-brand-gold font-semibold shrink-0">Chi tiết &rarr;</span>' +
                '</div>' +
              '</div>' +
            '</article>'
          );
        }).join('');

        attachImageFallbacks(productGrid);

        productGrid.querySelectorAll('[data-prod-id]').forEach(function (card) {
          card.addEventListener('click', function () {
            const found = constructionProducts.find(function (p) { return p.id === card.dataset.prodId; });
            if (found) openProjectModal(found.id, found.title, found.categoryLabel, found.desc);
          });
        });
      }

      // ===================================================================
      // RENDER LƯỚI 10 DỰ ÁN ĐÀ NẴNG (KHÔNG NHÃN DÁN, 2 CỘT MOBILE)
      // ===================================================================
      const danangGrid = document.getElementById('danang-grid');

      function renderDanangProjects(filterArea) {
        if (!danangGrid) return;
        const list = filterArea === 'all'
          ? danangProjects
          : danangProjects.filter(function (item) { return item.area === filterArea; });

        danangGrid.innerHTML = list.map(function (item) {
          return (
            '<article class="flatsome-card group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col cursor-pointer" data-dn-id="' + item.id + '">' +
              '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
                '<img src="' + driveUrl(item.id, 800) + '" data-fallback="' + driveFallbackUrl(item.id, 800) + '" alt="' + item.title + '" loading="lazy" class="hv-img flatsome-card-img w-full h-full object-cover" />' +
              '</div>' +
              '<div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between">' +
                '<h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">' +
                  item.title +
                '</h3>' +
                '<p class="mt-2 text-[11px] text-slate-500 flex items-start gap-1 leading-snug">' +
                  '<i class="fa-solid fa-location-dot text-brand-gold mt-0.5 shrink-0"></i>' +
                  '<span>' + item.location + '</span>' +
                '</p>' +
              '</div>' +
            '</article>'
          );
        }).join('');

        attachImageFallbacks(danangGrid);

        danangGrid.querySelectorAll('[data-dn-id]').forEach(function (card) {
          card.addEventListener('click', function () {
            const found = danangProjects.find(function (p) { return p.id === card.dataset.dnId; });
            if (found) {
              openProjectModal(
                found.id,
                found.title,
                found.location,
                'Dự án tiêu biểu tại ' + found.location + ' do Công Ty TNHH Xây Dựng và Thương Mại Huệ Vĩ trực tiếp triển khai thi công đảm bảo tiêu chuẩn kỹ thuật, an toàn và thẩm mỹ.'
              );
            }
          });
        });
      }

      // ===================================================================
      // RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
      // ===================================================================
      const articlesGrid = document.getElementById('articles-grid');

      function renderArticles() {
        if (!articlesGrid) return;
        articlesGrid.innerHTML = articles.map(function (art, idx) {
          return (
            '<article class="flatsome-card group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col cursor-pointer" data-art-idx="' + idx + '">' +
              '<div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">' +
                '<img src="' + driveUrl(art.imgId, 700) + '" data-fallback="' + driveFallbackUrl(art.imgId, 700) + '" alt="' + art.title + '" loading="lazy" class="hv-img flatsome-card-img w-full h-full object-cover" />' +
              '</div>' +
              '<div class="p-4 flex-1 flex flex-col justify-between">' +
                '<div>' +
                  '<div class="text-[11px] text-slate-400 mb-1.5"><i class="fa-regular fa-calendar mr-1 text-brand-gold"></i>' + art.date + '</div>' +
                  '<h3 class="text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug mb-2">' + art.title + '</h3>' +
                  '<p class="text-xs text-slate-600 leading-relaxed">' + art.excerpt + '</p>' +
                '</div>' +
                '<div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-semibold text-brand-gold">Đọc tiếp &rarr;</div>' +
              '</div>' +
            '</article>'
          );
        }).join('');

        attachImageFallbacks(articlesGrid);

        articlesGrid.querySelectorAll('[data-art-idx]').forEach(function (card) {
          card.addEventListener('click', function () {
            const art = articles[Number(card.dataset.artIdx)];
            if (art) openArticleModal(art);
          });
        });
      }

      // ===================================================================
      // SỰ KIỆN LỌC DANH MỤC CÔNG TRÌNH & DỰ ÁN ĐÀ NẴNG
      // ===================================================================
      document.querySelectorAll('.prod-cat-btn').forEach(function (btn) {
        btn.addEventListener('click', function () {
          document.querySelectorAll('.prod-cat-btn').forEach(function (b) {
            b.classList.remove('bg-brand-navy', 'text-white', 'shadow-sm');
            b.classList.add('bg-brand-soft', 'text-slate-700', 'border', 'border-slate-200');
          });
          btn.classList.remove('bg-brand-soft', 'text-slate-700', 'border', 'border-slate-200');
          btn.classList.add('bg-brand-navy', 'text-white', 'shadow-sm');
          renderProducts(btn.dataset.cat);
        });
      });

      document.querySelectorAll('.dn-cat-btn').forEach(function (btn) {
        btn.addEventListener('click', function () {
          document.querySelectorAll('.dn-cat-btn').forEach(function (b) {
            b.classList.remove('bg-brand-navy', 'text-white', 'shadow-sm');
            b.classList.add('bg-white', 'text-slate-700', 'border', 'border-slate-200');
          });
          btn.classList.remove('bg-white', 'text-slate-700', 'border', 'border-slate-200');
          btn.classList.add('bg-brand-navy', 'text-white', 'shadow-sm');
          renderDanangProjects(btn.dataset.area);
        });
      });

      // ===================================================================
      // SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
      // ===================================================================
      const sliderTrack = document.getElementById('slider-track');
      const heroSlider = document.getElementById('hero-slider');
      const dots = document.querySelectorAll('.slider-dot');
      const totalSlides = 2;
      let currentSlide = 0;
      let slideTimer = null;

      function goToSlide(index) {
        currentSlide = (index + totalSlides) % totalSlides;
        if (sliderTrack) {
          sliderTrack.style.transform = 'translateX(-' + (currentSlide * 100) + '%)';
        }
        dots.forEach(function (dot, i) {
          if (i === currentSlide) {
            dot.classList.remove('w-2.5', 'bg-white/60');
            dot.classList.add('w-7', 'bg-brand-gold');
          } else {
            dot.classList.remove('w-7', 'bg-brand-gold');
            dot.classList.add('w-2.5', 'bg-white/60');
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        slideTimer = setInterval(function () {
          goToSlide(currentSlide + 1);
        }, 5000);
      }

      function stopAutoSlide() {
        if (slideTimer) {
          clearInterval(slideTimer);
          slideTimer = null;
        }
      }

      const prevBtn = document.getElementById('slider-prev');
      const nextBtn = document.getElementById('slider-next');
      if (prevBtn) prevBtn.addEventListener('click', function () { goToSlide(currentSlide - 1); startAutoSlide(); });
      if (nextBtn) nextBtn.addEventListener('click', function () { goToSlide(currentSlide + 1); startAutoSlide(); });

      dots.forEach(function (dot) {
        dot.addEventListener('click', function () {
          goToSlide(Number(dot.dataset.slide));
          startAutoSlide();
        });
      });

      if (heroSlider) {
        heroSlider.addEventListener('mouseenter', stopAutoSlide);
        heroSlider.addEventListener('mouseleave', startAutoSlide);

        // Hỗ trợ vuốt ngang trên điện thoại
        let touchStartX = 0;
        heroSlider.addEventListener('touchstart', function (e) {
          touchStartX = e.changedTouches[0].screenX;
          stopAutoSlide();
        }, { passive: true });
        heroSlider.addEventListener('touchend', function (e) {
          const diff = e.changedTouches[0].screenX - touchStartX;
          if (Math.abs(diff) > 45) {
            goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
          }
          startAutoSlide();
        }, { passive: true });
      }

      // ===================================================================
      // MENU MOBILE & NÚT LÊN ĐẦU TRANG
      // ===================================================================
      const mobileMenuBtn = document.getElementById('mobile-menu-btn');
      const mobileMenu = document.getElementById('mobile-menu');
      if (mobileMenuBtn && mobileMenu) {
        mobileMenuBtn.addEventListener('click', function () {
          const isHidden = mobileMenu.classList.toggle('hidden');
          mobileMenuBtn.setAttribute('aria-expanded', String(!isHidden));
        });
        document.querySelectorAll('.mobile-nav-link').forEach(function (link) {
          link.addEventListener('click', function () {
            mobileMenu.classList.add('hidden');
            mobileMenuBtn.setAttribute('aria-expanded', 'false');
          });
        });
      }

      const scrollTopBtn = document.getElementById('scroll-top-btn');
      window.addEventListener('scroll', function () {
        if (!scrollTopBtn) return;
        if (window.scrollY > 400) {
          scrollTopBtn.classList.remove('hidden');
          scrollTopBtn.classList.add('flex');
        } else {
          scrollTopBtn.classList.add('hidden');
          scrollTopBtn.classList.remove('flex');
        }
      }, { passive: true });

      if (scrollTopBtn) {
        scrollTopBtn.addEventListener('click', function () {
          window.scrollTo({ top: 0, behavior: 'smooth' });
        });
      }

      // ===================================================================
      // MODAL XEM ẢNH CÔNG TRÌNH, BÀI VIẾT & XÁC NHẬN FORM BÁO GIÁ
      // ===================================================================
      const modal = document.getElementById('hv-modal');
      const modalBody = document.getElementById('hv-modal-body');
      const modalClose = document.getElementById('hv-modal-close');

      function openModal(html) {
        if (!modal || !modalBody) return;
        modalBody.innerHTML = html;
        modal.classList.remove('hidden');
        document.body.style.overflow = 'hidden';
        attachImageFallbacks(modalBody);
      }

      function closeModal() {
        if (!modal) return;
        modal.classList.add('hidden');
        document.body.style.overflow = '';
      }

      if (modalClose) modalClose.addEventListener('click', closeModal);
      if (modal) {
        modal.addEventListener('click', function (e) {
          if (e.target === modal) closeModal();
        });
      }
      document.addEventListener('keydown', function (e) {
        if (e.key === 'Escape') closeModal();
      });

      function openProjectModal(imgId, title, subtitle, desc) {
        openModal(
          '<div class="rounded-xl overflow-hidden bg-slate-100 mb-4">' +
            '<img src="' + driveUrl(imgId, 1200) + '" data-fallback="' + driveFallbackUrl(imgId, 1200) + '" alt="' + title + '" class="hv-img w-full max-h-[420px] object-cover" />' +
          '</div>' +
          '<p class="text-xs font-bold uppercase tracking-wider text-brand-gold mb-1">' + subtitle + '</p>' +
          '<h3 class="text-lg sm:text-xl font-extrabold text-brand-navy mb-2.5">' + title + '</h3>' +
          '<p class="text-sm text-slate-600 leading-relaxed mb-5">' + desc + '</p>' +
          '<div class="flex flex-wrap items-center gap-3">' +
            '<a href="#bao-gia" onclick="document.getElementById(\'hv-modal-close\').click()" class="inline-flex items-center gap-2 bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm px-5 py-2.5 rounded-lg transition">Nhận báo giá công trình tương tự</a>' +
            '<a href="tel:0907836324" class="inline-flex items-center gap-2 bg-brand-navy hover:bg-brand-navyDark text-white font-semibold text-xs sm:text-sm px-5 py-2.5 rounded-lg transition"><i class="fa-solid fa-phone text-xs"></i> 0907.836.324</a>' +
          '</div>'
        );
      }

      function openArticleModal(art) {
        openModal(
          '<div class="rounded-xl overflow-hidden bg-slate-100 mb-4">' +
            '<img src="' + driveUrl(art.imgId, 1100) + '" data-fallback="' + driveFallbackUrl(art.imgId, 1100) + '" alt="' + art.title + '" class="hv-img w-full max-h-[340px] object-cover" />' +
          '</div>' +
          '<div class="text-xs text-slate-400 mb-1.5"><i class="fa-regular fa-calendar mr-1 text-brand-gold"></i>' + art.date + ' • Cẩm nang xây dựng Huệ Vĩ</div>' +
          '<h3 class="text-lg sm:text-xl font-extrabold text-brand-navy mb-3">' + art.title + '</h3>' +
          '<p class="text-sm text-slate-700 leading-relaxed mb-3">' + art.excerpt + '</p>' +
          '<p class="text-sm text-slate-600 leading-relaxed mb-5">' + art.content + '</p>' +
          '<div class="bg-brand-soft rounded-xl p-4 border border-slate-200 flex flex-wrap items-center justify-between gap-3">' +
            '<div class="text-xs text-slate-700">Cần tư vấn kỹ thuật trực tiếp cho công trình của bạn?</div>' +
            '<a href="tel:0907836324" class="inline-flex items-center gap-1.5 bg-brand-gold text-white text-xs font-bold px-4 py-2 rounded-lg">Gọi ngay: 0907.836.324</a>' +
          '</div>'
        );
      }

      // ===================================================================
      // XỬ LÝ FORM YÊU CẦU & BÁO GIÁ (KHÔNG DÙNG ALERT)
      // ===================================================================
      const quoteForm = document.getElementById('quote-form');
      const formError = document.getElementById('form-error');

      if (quoteForm) {
        quoteForm.addEventListener('submit', function (e) {
          e.preventDefault();
          const name = document.getElementById('q-name').value.trim();
          const phone = document.getElementById('q-phone').value.trim();
          const projectType = document.getElementById('q-type').value;
          const budget = document.getElementById('q-budget').value;

          if (!name || !phone) {
            if (formError) {
              formError.textContent = 'Vui lòng nhập đầy đủ Họ và tên cùng Số điện thoại để kỹ sư Huệ Vĩ liên hệ báo giá.';
              formError.classList.remove('hidden');
            }
            return;
          }

          if (formError) formError.classList.add('hidden');

          openModal(
            '<div class="text-center py-3">' +
              '<div class="w-14 h-14 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center mx-auto mb-4">' +
                '<i class="fa-solid fa-check text-2xl"></i>' +
              '</div>' +
              '<h3 class="text-lg sm:text-xl font-extrabold text-brand-navy mb-2">Đã Tiếp Nhận Yêu Cầu Báo Giá!</h3>' +
              '<p class="text-sm text-slate-600 leading-relaxed mb-4">Cảm ơn <strong>' + name + '</strong> đã tin tưởng <strong>CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI HUỆ VĨ</strong>. Bộ phận kỹ sư sẽ liên hệ qua số <strong>' + phone + '</strong> để tư vấn hạng mục <strong>' + projectType + '</strong> (' + budget + ') trong thời gian sớm nhất.</p>' +
              '<div class="flex flex-wrap items-center justify-center gap-3">' +
                '<a href="https://zalo.me/0907836324" target="_blank" rel="noopener noreferrer" class="bg-[#0068FF] text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg">Nhắn Zalo 0907.836.324</a>' +
                '<button type="button" onclick="document.getElementById(\'hv-modal-close\').click()" class="bg-brand-navy text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg">Đóng lại</button>' +
              '</div>' +
            '</div>'
          );

          quoteForm.reset();
        });
      }

      // ===================================================================
      // KHỞI TẠO BAN ĐẦU
      // ===================================================================
      attachImageFallbacks(document);
      renderProducts('all');
      renderDanangProjects('all');
      renderArticles();
      startAutoSlide();
    })();
  </script>
</body>
</html>
