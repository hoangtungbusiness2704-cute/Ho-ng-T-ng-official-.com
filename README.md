<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoàng Tùng Official</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap');
        body { font-family: 'Inter', sans-serif; background: #0a0a0a; color: white; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(15px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .link-box { display: block; width: 100%; transition: all 0.3s ease; }
        .link-box:hover { box-shadow: 0 0 20px rgba(99, 102, 241, 0.3); border-color: rgba(99, 102, 241, 0.5); transform: translateY(-2px); }
    </style>
</head>
<body class="flex flex-col items-center min-h-screen py-10 px-4">

    <!-- Avatar -->
    <div class="relative mb-6">
        <div class="w-28 h-28 rounded-full border-2 border-blue-500/50 p-1">
            <div class="w-full h-full rounded-full bg-gradient-to-br from-blue-500 via-indigo-600 to-purple-600 flex flex-col items-center justify-center shadow-xl relative overflow-hidden">
                <!-- Hiệu ứng bóng sáng mờ bên trong -->
                <div class="absolute top-0 left-0 w-16 h-16 bg-white/20 rounded-full blur-xl"></div>
                
                <!-- Chữ HT cách điệu -->
                <span class="text-4xl font-black text-white tracking-tighter drop-shadow-md z-10 pr-1" style="font-family: Georgia, serif; font-style: italic;">HT</span>
                
                <!-- Chữ Hoàng Tùng cách điệu -->
                <div class="flex items-center gap-1 mt-0.5 z-10 opacity-90">
                    <div class="w-2 h-[1px] bg-white/70"></div>
                    <span class="text-[8px] font-bold text-white uppercase tracking-[0.15em]">Hoàng Tùng</span>
                    <div class="w-2 h-[1px] bg-white/70"></div>
                </div>
            </div>
        </div>
    </div>

    <h1 class="text-xl font-bold mb-1">Hoàng Tùng Official</h1>
    <p class="text-slate-500 text-sm mb-8">Content Creator | Tech & Lifestyle</p>

    <!-- Main Content -->
    <div class="w-full max-w-sm space-y-4">
        
        <!-- EP: Những góc bình yên -->
        <a href="https://rebrand.ly/HoangTungOfficial/ep-NGBY" target="_blank" rel="noopener noreferrer" class="link-box glass p-4 rounded-2xl">
            <div class="flex items-center gap-4">
                <div class="w-10 h-10 bg-indigo-500/10 rounded-xl flex items-center justify-center">
                    <i data-lucide="music" class="text-indigo-400 w-5 h-5"></i>
                </div>
                <div>
                    <h3 class="font-bold text-sm text-indigo-200">EP: Những góc bình yên</h3>
                    <p class="text-[10px] text-slate-400">Nghe ep tại đây</p>
                </div>
            </div>
        </a>

        <!-- Website (W) -->
        <a href="https://rebrand.ly/HoangTungOfficial" target="_blank" class="link-box glass p-4 rounded-2xl">
            <div class="flex items-center gap-4">
                <div class="w-10 h-10 bg-cyan-500/10 rounded-xl flex items-center justify-center font-bold text-cyan-400 text-xl">
                    W
                </div>
                <h3 class="font-semibold text-sm">Website</h3>
            </div>
        </a>

        <!-- Link Shopee (Đang tạm làm mờ) -->
        <a href="https://shopee.vn/shop_cua_tung" target="_blank" rel="noopener noreferrer" class="link-box glass p-4 rounded-2xl opacity-50 blur-[2px] pointer-events-none">
            <div class="flex items-center gap-4">
                <div class="w-10 h-10 bg-orange-500/10 rounded-xl flex items-center justify-center">
                    <i data-lucide="shopping-bag" class="text-orange-500 w-5 h-5"></i>
                </div>
                <div>
                    <h3 class="font-semibold text-sm">Góc Review Shopee</h3>
                    <p class="text-[10px] text-slate-400">Sản phẩm Tùng khuyên dùng</p>
                </div>
            </div>
        </a>

        <!-- Social Media Grid (F, I, T) -->
        <div class="grid grid-cols-3 gap-3">
            <a href="https://www.facebook.com/hoangtung27042010/" target="_blank" class="link-box glass p-4 rounded-2xl text-center flex items-center justify-center font-bold text-xl text-blue-400">
                F
            </a>
            <a href="https://instagram.com/nguyenhoangtung27042010" target="_blank" class="link-box glass p-4 rounded-2xl text-center flex items-center justify-center font-bold text-xl text-pink-400">
                I
            </a>
            <a href="https://tiktok.com/@hoangtung27042010" target="_blank" class="link-box glass p-4 rounded-2xl text-center flex items-center justify-center font-bold text-xl text-white">
                T
            </a>
        </div>
        
        <!-- Kênh YouTube (Y) -->
        <a href="https://youtube.com/@hoangtung2704" target="_blank" class="link-box glass p-4 rounded-2xl">
            <div class="flex items-center gap-4">
                <div class="w-10 h-10 bg-red-500/10 rounded-xl flex items-center justify-center font-bold text-red-500 text-xl">
                    Y
                </div>
                <h3 class="font-semibold text-sm">Kênh YouTube chính thức</h3>
            </div>
        </a>

        <!-- SoundCloud (S) -->
        <a href="https://on.soundcloud.com/cthsPiNMZtgqOPhhnC" target="_blank" class="link-box glass p-4 rounded-2xl">
            <div class="flex items-center gap-4">
                <div class="w-10 h-10 bg-orange-600/10 rounded-xl flex items-center justify-center font-bold text-orange-500 text-xl">
                    S
                </div>
                <h3 class="font-semibold text-sm">SoundCloud</h3>
            </div>
        </a>
    </div>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>



