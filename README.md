# -JIOWAILIH.github.io
<!doctype html>
<html lang="zh-TW">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>就愛栗 - 精選堅果果乾專賣店</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap');
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            letter-spacing: -0.01em;
            box-sizing: border-box;
        }
        
        .font-display {
            font-family: 'Playfair Display', serif;
        }
        
        .smooth-scroll {
            scroll-behavior: smooth;
        }
        
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        .product-card {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(10px);
        }
        
        .product-card:hover {
            transform: translateY(-8px) scale(1.02);
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.15);
        }
        
        .hero-bg {
            background: linear-gradient(135deg, #faf8f5 0%, #f1ede7 50%, #e8e0d6 100%);
            position: relative;
        }
        
        .hero-bg::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23d4af37' fill-opacity='0.03'%3E%3Ccircle cx='30' cy='30' r='2'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
        
        .glass-effect {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .luxury-gradient {
            background: linear-gradient(135deg, #d4af37 0%, #f4e4a6 50%, #d4af37 100%);
        }
        
        .text-shadow {
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        .btn-luxury {
            background: linear-gradient(135deg, #2c1810 0%, #3d2317 100%);
            box-shadow: 0 4px 15px rgba(44, 24, 16, 0.3);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .btn-luxury:hover {
            background: linear-gradient(135deg, #3d2317 0%, #4a2a1c 100%);
            box-shadow: 0 8px 25px rgba(44, 24, 16, 0.4);
            transform: translateY(-2px);
        }
        
        .section-divider {
            height: 1px;
            background: linear-gradient(90deg, transparent 0%, #d4af37 50%, transparent 100%);
            margin: 4rem 0;
        }
        
        .category-btn {
            color: #6b7280;
            background: transparent;
        }
        
        .category-btn.active {
            background: linear-gradient(135deg, #d4af37 0%, #f4e4a6 50%, #d4af37 100%);
            color: white;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.3);
        }
        
        .category-btn:hover:not(.active) {
            background: rgba(212, 175, 55, 0.1);
            color: #d4af37;
        }
    </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="/_sdk/element_sdk.js" type="text/javascript"></script>
 </head>
 <body class="smooth-scroll bg-white"><!-- 導航欄 -->
  <nav class="fixed top-0 w-full glass-effect shadow-lg z-50">
   <div class="max-w-7xl mx-auto px-6 lg:px-8">
    <div class="flex justify-between items-center h-20">
     <div class="flex items-center">
      <div class="flex items-center space-x-3">
       <div class="w-10 h-10 luxury-gradient rounded-full flex items-center justify-center"><span class="text-white font-bold text-lg">栗</span>
       </div>
       <h1 class="text-2xl font-display font-semibold text-gray-800 tracking-tight">就愛栗 <span class="text-lg text-gray-500 font-light">JIOW AI LIH</span></h1>
      </div>
     </div>
     <div class="hidden md:block">
      <div class="ml-10 flex items-center space-x-10"><a href="#home" class="text-gray-600 hover:text-gray-900 text-sm font-medium tracking-wide transition-all duration-300 relative group"> 首頁 <span class="absolute -bottom-1 left-0 w-0 h-0.5 luxury-gradient group-hover:w-full transition-all duration-300"></span> </a> <a href="#story" class="text-gray-600 hover:text-gray-900 text-sm font-medium tracking-wide transition-all duration-300 relative group"> 品牌故事 <span class="absolute -bottom-1 left-0 w-0 h-0.5 luxury-gradient group-hover:w-full transition-all duration-300"></span> </a> <a href="#about" class="text-gray-600 hover:text-gray-900 text-sm font-medium tracking-wide transition-all duration-300 relative group"> 關於我們 <span class="absolute -bottom-1 left-0 w-0 h-0.5 luxury-gradient group-hover:w-full transition-all duration-300"></span> </a> <a href="#products" class="text-gray-600 hover:text-gray-900 text-sm font-medium tracking-wide transition-all duration-300 relative group"> 商品介紹 <span class="absolute -bottom-1 left-0 w-0 h-0.5 luxury-gradient group-hover:w-full transition-all duration-300"></span> </a> <a href="#reviews" class="text-gray-600 hover:text-gray-900 text-sm font-medium tracking-wide transition-all duration-300 relative group"> 顧客回饋 <span class="absolute -bottom-1 left-0 w-0 h-0.5 luxury-gradient group-hover:w-full transition-all duration-300"></span> </a> <a href="#contact" class="text-gray-600 hover:text-gray-900 text-sm font-medium tracking-wide transition-all duration-300 relative group"> 聯絡我們 <span class="absolute -bottom-1 left-0 w-0 h-0.5 luxury-gradient group-hover:w-full transition-all duration-300"></span> </a> <a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full text-sm font-medium tracking-wide"> 出攤公告 </a>
      </div>
     </div>
     <div class="md:hidden"><button id="mobile-menu-btn" class="text-gray-700 hover:text-amber-600">
       <svg class="h-6 w-6" fill="none" viewbox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
       </svg></button>
     </div>
    </div>
   </div><!-- 手機版選單 -->
   <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
    <div class="px-2 pt-2 pb-3 space-y-1"><a href="#home" class="block px-3 py-2 text-gray-700 hover:text-amber-600">首頁</a> <a href="#story" class="block px-3 py-2 text-gray-700 hover:text-amber-600">品牌故事</a> <a href="#about" class="block px-3 py-2 text-gray-700 hover:text-amber-600">關於我們</a> <a href="#products" class="block px-3 py-2 text-gray-700 hover:text-amber-600">商品介紹</a> <a href="#reviews" class="block px-3 py-2 text-gray-700 hover:text-amber-600">顧客回饋</a> <a href="#contact" class="block px-3 py-2 text-gray-700 hover:text-amber-600">聯絡我們</a> <a href="#order" class="block px-3 py-2 bg-amber-600 text-white rounded-lg mx-3 text-center">立即訂購</a>
    </div>
   </div>
  </nav><!-- 首頁橫幅 -->
  <section id="home" class="hero-bg pt-20 min-h-screen flex items-center relative overflow-hidden">
   <div class="max-w-7xl mx-auto px-6 lg:px-8 py-20 relative z-10">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
     <div class="fade-in">
      <div class="mb-6"><span class="inline-block px-4 py-2 bg-white/80 backdrop-blur-sm rounded-full text-sm font-medium text-gray-700 tracking-wide border border-gray-200/50"> PREMIUM QUALITY SINCE 1998 </span>
      </div>
      <h2 class="text-6xl lg:text-7xl font-display font-bold text-gray-900 mb-8 leading-tight text-shadow"><span class="bg-gradient-to-r from-amber-600 via-yellow-500 to-amber-700 bg-clip-text text-transparent">就愛栗</span><br>
        精選堅果果乾</h2>
      <p class="text-xl text-gray-700 mb-10 leading-relaxed font-light max-w-lg">嚴選世界頂級堅果與果乾，保留原始風味與營養精華。<br><span class="font-medium">純天然無添加，每一口，皆是大自然最純粹的饋贈，</span><br>成就高品質的健康美味。</p>
      <div class="flex flex-col sm:flex-row gap-6"><a href="#products" class="btn-luxury text-white px-10 py-4 rounded-full text-lg font-medium tracking-wide text-center group"> 瀏覽商品 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a> <a href="#about" class="border-2 border-gray-800 text-gray-800 px-10 py-4 rounded-full text-lg font-medium hover:bg-gray-800 hover:text-white transition-all duration-300 text-center tracking-wide"> 關於我們 </a>
      </div>
     </div>
     <div class="fade-in">
      <div class="relative"><!-- 主要產品展示 -->
       <div class="glass-effect rounded-3xl shadow-2xl p-10 transform rotate-2 hover:rotate-0 transition-transform duration-500">
        <div class="text-center">
            <img src="index/官網/合照.jpg" alt="替代文字" />
         
        </div>
       </div><!-- 浮動元素 -->
       <div class="absolute -top-6 -left-6 w-24 h-24 luxury-gradient rounded-full opacity-20 animate-pulse"></div>
       <div class="absolute -bottom-8 -right-8 w-32 h-32 bg-gradient-to-br from-amber-200 to-orange-200 rounded-full opacity-30 animate-pulse" style="animation-delay: 1s;"></div><!-- 小卡片 -->
       <div class="absolute -bottom-6 -left-6 glass-effect rounded-2xl shadow-xl p-4 transform -rotate-6 hover:rotate-0 transition-transform duration-300">
        <div class="text-3xl mb-2">
         🌿
        </div>
        <p class="text-sm font-medium text-gray-800">100% 天然</p>
       </div>
      </div>
     </div>
    </div>
   </div><!-- 背景裝飾 -->
   <div class="absolute top-1/4 right-10 w-2 h-2 bg-amber-400 rounded-full opacity-60"></div>
   <div class="absolute top-1/3 right-32 w-1 h-1 bg-amber-500 rounded-full opacity-40"></div>
   <div class="absolute bottom-1/4 left-10 w-3 h-3 bg-amber-300 rounded-full opacity-50"></div>
  </section><!-- 品牌故事 - 時間軸設計 -->
  <section id="story" class="py-32 bg-gradient-to-br from-slate-50 via-blue-50 to-indigo-50 relative overflow-hidden"><!-- 背景裝飾 -->
   <div class="absolute inset-0">
    <div class="absolute top-20 left-10 w-32 h-32 bg-gradient-to-br from-amber-200/30 to-orange-200/30 rounded-full blur-3xl"></div>
    <div class="absolute bottom-20 right-10 w-40 h-40 bg-gradient-to-br from-blue-200/30 to-purple-200/30 rounded-full blur-3xl"></div>
    <div class="absolute top-1/2 left-1/4 w-24 h-24 bg-gradient-to-br from-green-200/20 to-teal-200/20 rounded-full blur-2xl"></div>
   </div>
   <div class="max-w-7xl mx-auto px-6 lg:px-8 relative z-10"><!-- 標題區域 -->
    <div class="text-center mb-20 fade-in"><span class="inline-block px-4 py-2 bg-white/80 backdrop-blur-sm rounded-full text-sm font-medium text-gray-700 tracking-wide mb-6 border border-gray-200/50"> OUR JOURNEY </span>
     <h2 class="text-5xl lg:text-6xl font-display font-bold text-gray-900 mb-6 text-shadow">品牌<span class="bg-gradient-to-r from-amber-600 to-yellow-600 bg-clip-text text-transparent">故事</span></h2>
     <p class="text-xl text-gray-600 max-w-3xl mx-auto font-light">從一顆栗子開始的夢想，到今天成為您信賴的品牌</p>
    </div><!-- 時間軸區域 -->
    <div class="relative mb-20"><!-- 中央時間線 -->
     <div class="absolute left-1/2 transform -translate-x-1/2 h-full w-1 bg-gradient-to-b from-amber-400 via-blue-500 to-purple-600 rounded-full"></div><!-- 1998年 - 左側 -->
     <div class="relative mb-16 fade-in">
      <div class="flex items-center">
       <div class="w-1/2 pr-12">
        <div class="glass-effect rounded-3xl p-8 shadow-xl hover:shadow-2xl transition-all duration-500 hover:-translate-y-2">
         <div class="flex items-center mb-6">
          <div class="w-16 h-16 bg-gradient-to-br from-amber-400 to-orange-500 rounded-full flex items-center justify-center mr-4 shadow-lg">
           <svg class="w-8 h-8 text-white" fill="currentColor" viewbox="0 0 24 24"><path d="M9 21c0 .5.4 1 1 1h4c.6 0 1-.5 1-1v-1H9v1zm3-19C8.1 2 5 5.1 5 9c0 2.4 1.2 4.5 3 5.7V17c0 .5.4 1 1 1h6c.6 0 1-.5 1-1v-2.3c1.8-1.3 3-3.4 3-5.7 0-3.9-3.1-7-7-7z" />
           </svg>
          </div>
          <div>
           <h3 class="text-2xl font-display font-bold text-gray-900">白手起家的開始</h3>
           <p class="text-amber-600 font-medium">品牌創立的初心</p>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed">1998年，懷著對栗子的純粹熱愛，我們白手起家創立了「就愛栗」。從傳統市場中飄散的糖炒栗子香味開始，憑著一股熱忱與堅持，我們決心將這份溫暖與甜蜜分享給更多人。一路從最基礎的設備、最簡單的攤位做起，在反覆試驗中找出最能呈現栗子原味的烘炒方式。即使環境再艱苦，我們也始終相信，只要用心、踏實地做，每一顆栗子都能成為陪伴顧客的美好記憶。</p>
        </div>
       </div>
       <div class="absolute left-1/2 transform -translate-x-1/2 w-16 h-16 bg-gradient-to-br from-amber-400 to-orange-500 rounded-full flex items-center justify-center shadow-lg border-4 border-white"><span class="text-2xl font-bold text-white">98</span>
       </div>
       <div class="w-1/2 pl-12">
        <div class="text-8xl font-display font-bold text-gray-200 opacity-50">
         1998
        </div>
       </div>
      </div>
     </div><!-- 2005年 - 右側 -->
     <div class="relative mb-16 fade-in">
      <div class="flex items-center">
       <div class="w-1/2 pr-12">
        <div class="text-8xl font-display font-bold text-gray-200 opacity-50 text-right">
         2005
        </div>
       </div>
       <div class="absolute left-1/2 transform -translate-x-1/2 w-16 h-16 bg-gradient-to-br from-green-400 to-emerald-500 rounded-full flex items-center justify-center shadow-lg border-4 border-white"><span class="text-2xl font-bold text-white">05</span>
       </div>
       <div class="w-1/2 pl-12">
        <div class="glass-effect rounded-3xl p-8 shadow-xl hover:shadow-2xl transition-all duration-500 hover:-translate-y-2">
         <div class="flex items-center mb-6">
          <div class="w-16 h-16 bg-gradient-to-br from-green-400 to-emerald-500 rounded-full flex items-center justify-center mr-4 shadow-lg">
           <svg class="w-8 h-8 text-white" fill="currentColor" viewbox="0 0 24 24"><path d="M12,1L3,5V11C3,16.55 6.84,21.74 12,23C17.16,21.74 21,16.55 21,11V5L12,1M10,17L6,13L7.41,11.59L10,14.17L16.59,7.58L18,9L10,17Z" />
           </svg>
          </div>
          <div>
           <h3 class="text-2xl font-display font-bold text-gray-900">品質堅持</h3>
           <p class="text-green-600 font-medium">嚴格把關每個環節</p>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed">建立完善的品質管控系統，從原料採購到包裝出貨，每個環節都經過嚴格檢驗。我們堅持只選用當季的新鮮食材，並採取當天現炒的方式呈現最原始的風味。因為我們相信，只有用心、即時、而且真材實料製作的產品，才能帶給顧客真正的滿足。</p>
        </div>
       </div>
      </div>
     </div><!-- 2015年 - 左側 -->
     <div class="relative mb-16 fade-in">
      <div class="flex items-center">
       <div class="w-1/2 pr-12">
        <div class="glass-effect rounded-3xl p-8 shadow-xl hover:shadow-2xl transition-all duration-500 hover:-translate-y-2">
         <div class="flex items-center mb-6">
          <div class="w-16 h-16 bg-gradient-to-br from-blue-400 to-indigo-500 rounded-full flex items-center justify-center mr-4 shadow-lg">
           <svg class="w-8 h-8 text-white" fill="currentColor" viewbox="0 0 24 24"><path d="M16,6L18.29,8.29L13.41,13.17L9.41,9.17L2,16.59L3.41,18L9.41,12L13.41,16L19.71,9.71L22,12V6H16Z" />
           </svg>
          </div>
          <div>
           <h3 class="text-2xl font-display font-bold text-gray-900">快速成長</h3>
           <p class="text-blue-600 font-medium">擴展與創新</p>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed">擴展產品線，引進更多優質堅果與果乾，讓選擇更加多元。同時，我們積極建立線上銷售平台，讓更多消費者能夠輕鬆享受到我們精心挑選的健康美味。隨著銷售管道的拓展與口碑的累積，我們的品牌成長速度迅速提升，持續吸引更多喜愛天然與健康食品的顧客加入。</p>
        </div>
       </div>
       <div class="absolute left-1/2 transform -translate-x-1/2 w-16 h-16 bg-gradient-to-br from-blue-400 to-indigo-500 rounded-full flex items-center justify-center shadow-lg border-4 border-white"><span class="text-2xl font-bold text-white">15</span>
       </div>
       <div class="w-1/2 pl-12">
        <div class="text-8xl font-display font-bold text-gray-200 opacity-50">
         2015
        </div>
       </div>
      </div>
     </div><!-- 2024年 - 右側 -->
     <div class="relative fade-in">
      <div class="flex items-center">
       <div class="w-1/2 pr-12">
        <div class="text-8xl font-display font-bold text-gray-200 opacity-50 text-right">
         2024
        </div>
       </div>
       <div class="absolute left-1/2 transform -translate-x-1/2 w-16 h-16 bg-gradient-to-br from-rose-400 to-pink-500 rounded-full flex items-center justify-center shadow-lg border-4 border-white"><span class="text-2xl font-bold text-white">24</span>
       </div>
       <div class="w-1/2 pl-12">
        <div class="glass-effect rounded-3xl p-8 shadow-xl hover:shadow-2xl transition-all duration-500 hover:-translate-y-2">
         <div class="flex items-center mb-6">
          <div class="w-16 h-16 bg-gradient-to-br from-rose-400 to-pink-500 rounded-full flex items-center justify-center mr-4 shadow-lg">
           <svg class="w-8 h-8 text-white" fill="currentColor" viewbox="0 0 24 24"><path d="M16 4C18.2 4 20 5.8 20 8C20 10.2 18.2 12 16 12C13.8 12 12 10.2 12 8C12 5.8 13.8 4 16 4M16 14C18.7 14 22 15.3 22 18V20H10V18C10 15.3 13.3 14 16 14M8 4C10.2 4 12 5.8 12 8C12 10.2 10.2 12 8 12C5.8 12 4 10.2 4 8C4 5.8 5.8 4 8 4M8 14C10.7 14 14 15.3 14 18V20H2V18C2 15.3 5.3 14 8 14Z" />
           </svg>
          </div>
          <div>
           <h3 class="text-2xl font-display font-bold text-gray-900">深耕信賴</h3>
           <p class="text-rose-600 font-medium">成為您信賴的品牌</p>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed">建立深厚的顧客關係，成為值得信賴的品牌。我們不只是賣產品，更是在分享健康美味的生活方式，與每一位顧客建立長久的夥伴關係。透過持續傾聽回饋、提升服務品質，以及堅持提供透明安心的食材來源，我們希望成為顧客日常生活中能放心依靠的存在，陪伴大家一起追求更健康、更美好的飲食習慣。</p>
        </div>
       </div>
      </div>
     </div>
    </div><!-- 核心價值區域 -->
    <div class="mb-20 fade-in">
     <div class="text-center mb-20">
      <h3 class="text-4xl font-display font-bold text-gray-900 mb-6">核心價值</h3>
      <p class="text-xl text-gray-600 max-w-2xl mx-auto leading-relaxed">我們堅信，好的品牌不只是賣東西，而是在生活中提供真實的價值。</p>
     </div><!-- 專業網格排版設計 -->
     <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 max-w-6xl mx-auto"><!-- 誠信為本 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-blue-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-blue-50 to-sky-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-blue-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             🤝
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">誠信為本</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-blue-300 to-sky-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">每一件商品，都以誠信態度對待客戶與供應鏈。我們相信，誠實透明的經營方式是建立長久信任關係的基石。</p>
        </div>
       </div>
      </div><!-- 持續創新 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-purple-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-purple-50 to-violet-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-purple-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             💡
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">持續創新</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-purple-300 to-violet-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">不斷優化設計與流程，追求更高的使用體驗。創新不只是技術，更是對品質和服務的不懈追求。</p>
        </div>
       </div>
      </div><!-- 天然食材 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-green-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-green-50 to-emerald-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-green-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             🌿
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">天然食材</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-green-300 to-emerald-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">堅持使用純天然食材，無添加防腐劑、色素或添加物，讓您品嚐到最原始的美味，如大自然所賜。</p>
        </div>
       </div>
      </div><!-- 以客為尊 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-rose-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-rose-50 to-pink-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-rose-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             💖
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">以客為尊</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-rose-300 to-pink-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">傾聽客戶需求，以顧客為中心，提供貼心周到的服務體驗。每一位顧客的滿意都是我們前進的動力。</p>
        </div>
       </div>
      </div>
     </div><!-- 底部統計數據 - 四個獨立格子 -->
     <div class="mt-20 grid grid-cols-2 lg:grid-cols-4 gap-6">
      <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300 p-8 text-center group border border-blue-200/50 hover:border-blue-300">
       <div class="text-5xl font-bold text-blue-600 mb-3 group-hover:scale-110 transition-transform duration-300">
        26+
       </div>
       <p class="text-gray-800 font-medium mb-2">年專業經驗</p>
       <p class="text-gray-600 text-sm font-light">持續創新進步</p>
      </div>
      <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300 p-8 text-center group border border-emerald-200/50 hover:border-emerald-300">
       <div class="text-5xl font-bold text-green-600 mb-3 group-hover:scale-110 transition-transform duration-300">
        5000+
       </div>
       <p class="text-gray-800 font-medium mb-2">滿意顧客</p>
       <p class="text-gray-600 text-sm font-light">持續成長中</p>
      </div>
      <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300 p-8 text-center group border border-amber-200/50 hover:border-amber-300">
       <div class="text-5xl font-bold text-amber-600 mb-3 group-hover:scale-110 transition-transform duration-300">
        15+
       </div>
       <p class="text-gray-800 font-medium mb-2">精選商品</p>
       <p class="text-gray-600 text-sm font-light">嚴格品質把關</p>
      </div>
      <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300 p-8 text-center group border border-rose-200/50 hover:border-rose-300">
       <div class="text-5xl font-bold text-rose-600 mb-3 group-hover:scale-110 transition-transform duration-300">
        98%
       </div>
       <p class="text-gray-800 font-medium mb-2">顧客滿意度</p>
       <p class="text-gray-600 text-sm font-light">品質有保證</p>
      </div>
     </div>
    </div><!-- 未來願景區域 -->
    <div class="relative fade-in"><!-- 多層背景裝飾 -->
     <div class="absolute inset-0 bg-gradient-to-r from-amber-50/80 via-orange-50/80 to-yellow-50/80 rounded-3xl"></div>
     <div class="absolute inset-2 bg-gradient-to-br from-white/60 to-transparent rounded-3xl"></div>
     <div class="relative glass-effect rounded-3xl p-12 text-center">
      <h3 class="text-5xl font-display font-bold text-gray-900 mb-6">未來願景</h3>
      <p class="text-xl text-gray-600 mb-12 max-w-3xl mx-auto leading-relaxed">讓「就愛栗」成為每個家庭健康生活的首選，用最純粹的美味，連結最真摯的情感，<br>為下一代創造更美好的飲食環境。</p><!-- 品牌標語 - 溫馨舒適設計 -->
      <div class="flex flex-wrap justify-center gap-6 max-w-5xl mx-auto">
       <div class="flex items-center bg-gradient-to-r from-blue-50 to-sky-50 rounded-2xl px-8 py-4 shadow-sm hover:shadow-md transition-all duration-300 group border border-blue-100/80">
        <div class="text-3xl mr-4 group-hover:scale-110 transition-transform duration-300">
         🏠
        </div><span class="text-base font-medium text-blue-800">家庭首選</span>
       </div>
       <div class="flex items-center bg-gradient-to-r from-rose-50 to-pink-50 rounded-2xl px-8 py-4 shadow-sm hover:shadow-md transition-all duration-300 group border border-rose-100/80">
        <div class="text-3xl mr-4 group-hover:scale-110 transition-transform duration-300">
         💝
        </div><span class="text-base font-medium text-rose-800">真摯情感</span>
       </div>
       <div class="flex items-center bg-gradient-to-r from-emerald-50 to-green-50 rounded-2xl px-8 py-4 shadow-sm hover:shadow-md transition-all duration-300 group border border-emerald-100/80">
        <div class="text-3xl mr-4 group-hover:scale-110 transition-transform duration-300">
         🌱
        </div><span class="text-base font-medium text-emerald-800">美好未來</span>
       </div>
       <div class="flex items-center bg-gradient-to-r from-amber-50 to-yellow-50 rounded-2xl px-8 py-4 shadow-sm hover:shadow-md transition-all duration-300 group border border-amber-100/80">
        <div class="text-3xl mr-4 group-hover:scale-110 transition-transform duration-300">
         ✨
        </div><span class="text-base font-medium text-amber-800">品質第一</span>
       </div>
      </div>
     </div>
    </div>
   </div>
  </section><!-- 迪化街年貨大街 -->
  <section class="py-32 bg-gradient-to-br from-red-50 via-orange-50 to-amber-50 relative overflow-hidden"><!-- 背景裝飾 -->
   <div class="absolute inset-0">
    <div class="absolute top-10 left-10 w-40 h-40 bg-gradient-to-br from-red-200/40 to-orange-200/40 rounded-full blur-3xl"></div>
    <div class="absolute bottom-10 right-10 w-32 h-32 bg-gradient-to-br from-amber-200/40 to-yellow-200/40 rounded-full blur-3xl"></div>
    <div class="absolute top-1/3 right-1/4 w-24 h-24 bg-gradient-to-br from-rose-200/30 to-pink-200/30 rounded-full blur-2xl"></div>
   </div>
   <div class="max-w-7xl mx-auto px-6 lg:px-8 relative z-10"><!-- 標題區域 -->
    <div class="text-center mb-20 fade-in"><span class="inline-block px-4 py-2 bg-white/80 backdrop-blur-sm rounded-full text-sm font-medium text-red-700 tracking-wide mb-6 border border-red-200/50"> TRADITIONAL MARKET HERITAGE </span>
     <h2 class="text-5xl lg:text-6xl font-display font-bold text-gray-900 mb-6 text-shadow"><span class="bg-gradient-to-r from-red-600 to-orange-600 bg-clip-text text-transparent">迪化街</span>年貨大街</h2>
     <p class="text-xl text-gray-600 max-w-3xl mx-auto font-light leading-relaxed">連續二十一年在台北最具歷史的年貨大街與您相見，傳承百年的年節文化</p>
    </div><!-- 主要內容區域 -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center mb-20"><!-- 左側文字內容 -->
     <div class="fade-in">
      <div class="glass-effect rounded-3xl p-10 shadow-xl">
       <h3 class="text-3xl font-display font-bold text-gray-900 mb-6">十年傳統，百年文化</h3>
       <div class="space-y-6 text-gray-600 leading-relaxed">
        <p class="text-lg">自2003年起，「就愛栗」每年農曆春節前夕都會在<span class="font-semibold text-red-600">迪化街年貨大街</span>設立攤位， 與來自全台各地的民眾分享我們精心製作的堅果果乾。</p>
        <p>迪化街擁有超過百年的歷史，是台北最具代表性的傳統市集。在這裡，我們不只是在販售商品， 更是在傳承台灣的年節文化，讓每一位顧客都能感受到濃濃的年味與人情味。</p>
        <p><span class="font-semibold text-amber-600">連續二十一年的堅持</span>，讓我們與許多老顧客建立了深厚的情感連結。 每年過年前，總有熟悉的面孔會特地來到我們的攤位，這份信任與支持是我們最珍貴的資產。</p>
       </div><!-- 特色標籤 -->
       <div class="flex flex-wrap gap-3 mt-8"><span class="px-4 py-2 bg-red-100 text-red-700 rounded-full text-sm font-medium">連續二十一年參與</span> <span class="px-4 py-2 bg-orange-100 text-orange-700 rounded-full text-sm font-medium">百年歷史街區</span> <span class="px-4 py-2 bg-amber-100 text-amber-700 rounded-full text-sm font-medium">傳統年節文化</span>
       </div>
      </div>
     </div><!-- 右側視覺內容 -->
     <div class="fade-in">
      <div class="relative"><!-- 主要展示卡片 -->
       <div class="glass-effect rounded-3xl shadow-2xl p-10 transform hover:scale-105 transition-transform duration-500">
        <div class="text-center "><!-- 年貨大街圖標 -->
         <img src="index/迪化街/82595474_150321119733319_5530487167807127552_n.jpg" width="960" alt="替代文字" />
         <br>
         <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">迪化街年貨大街</h4>
         <p class="text-gray-600 mb-6">台北最具歷史的年貨市集</p><!-- 統計數據 -->
         <div class="grid grid-cols-2 gap-4 mt-6">
          <div class="text-center">
           <div class="text-3xl font-bold text-red-600 mb-1">
            21+
           </div>
           <div class="text-sm text-gray-600">
            連續參與年數
           </div>
          </div>
          <div class="text-center">
           <div class="text-3xl font-bold text-orange-600 mb-1">
            100+
           </div>
           <div class="text-sm text-gray-600">
            年歷史街區
           </div>
          </div>
         </div>
        </div>
       </div><!-- 浮動裝飾元素 -->
       <div class="absolute -top-6 -right-6 w-24 h-24 bg-gradient-to-br from-red-300 to-orange-300 rounded-full opacity-30 animate-pulse"></div>
       <div class="absolute -bottom-8 -left-8 w-32 h-32 bg-gradient-to-br from-amber-200 to-yellow-200 rounded-full opacity-40 animate-pulse" style="animation-delay: 1s;"></div><!-- 小裝飾卡片 -->
       <div class="absolute -bottom-6 -right-6 glass-effect rounded-2xl shadow-xl p-4 transform rotate-6 hover:rotate-0 transition-transform duration-300">
        <div class="text-3xl mb-2">
         🏮
        </div>
        <p class="text-sm font-medium text-gray-800">年節傳統</p>
       </div>
      </div>
     </div>
    </div><!-- 年貨大街特色區域 -->
    <div class="mb-20 fade-in">
     <div class="text-center mb-16">
      <h3 class="text-4xl font-display font-bold text-gray-900 mb-6">年貨大街的特色體驗</h3>
      <p class="text-xl text-gray-600 max-w-2xl mx-auto leading-relaxed">在迪化街，我們提供的不只是商品，更是完整的年節文化體驗</p>
     </div>
     <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8"><!-- 特色1 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-red-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-red-50 to-orange-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-red-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             🏮
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">傳統年味</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-red-300 to-orange-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">在百年老街的氛圍中，感受最道地的台灣年節文化，每一口堅果都充滿濃濃的年味。</p>
        </div>
       </div>
      </div><!-- 特色2 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-orange-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-orange-50 to-amber-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-orange-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             👥
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">人情味濃</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-orange-300 to-amber-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">與老顧客面對面交流，分享年節故事，建立超越買賣關係的深厚情感連結。</p>
        </div>
       </div>
      </div><!-- 特色3 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-amber-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-amber-50 to-yellow-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-amber-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             🎁
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">現場試吃</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-amber-300 to-yellow-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">提供現場試吃服務，讓您親自品嚐每一種堅果果乾的獨特風味，安心選購。</p>
        </div>
       </div>
      </div>
     </div>
    </div>
   </div>
  </section><!-- 關於我們 -->
  <section id="about" class="py-20 bg-white">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16 fade-in">
     <h2 class="text-4xl font-bold text-gray-800 mb-4">關於我們</h2>
     <p class="text-xl text-gray-600">用心製作，品質保證</p>
    </div>
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-16">
     <div class="fade-in">
      <div class="bg-gray-50 rounded-2xl p-8">
       <h3 class="text-2xl font-bold text-gray-800 mb-6">我們的理念</h3>
       <p class="text-gray-600 leading-relaxed mb-6">我們相信大自然最優質食材的非凡力量，好的食品不只是填飽肚子，更是為生活帶來健康與快樂。 因此，我們堅持選用最優質的原料，採用最嚴格的製作標準。 每一顆堅果、每一片果乾都訴說著品質、永續與工藝卓越的故事。</p>
       <p class="text-gray-600 leading-relaxed">從採購、加工到包裝，每一個環節都經過嚴格把關， 只為了讓您品嚐到最純淨、最美味的堅果果乾。</p>
      </div>
     </div>
     <div class="fade-in">
      <div class="bg-gray-50 rounded-2xl p-8">
       <h3 class="text-2xl font-bold text-gray-800 mb-6">品質承諾</h3>
       <div class="space-y-4">
        <div class="flex items-center">
         <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center mr-4"><span class="text-green-600">✓</span>
         </div><span class="text-gray-700">100% 天然無添加</span>
        </div>
        <div class="flex items-center">
         <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center mr-4"><span class="text-green-600">✓</span>
         </div><span class="text-gray-700">嚴選優質原料</span>
        </div>
        <div class="flex items-center">
         <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center mr-4"><span class="text-green-600">✓</span>
         </div><span class="text-gray-700">專業品質檢驗</span>
        </div>
        <div class="flex items-center">
         <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center mr-4"><span class="text-green-600">✓</span>
         </div><span class="text-gray-700">新鮮配送保證</span>
        </div>
       </div>
      </div>
     </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-5 gap-6">
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">🌱</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">天然健康</h3>
      <p class="text-gray-600 text-sm">我們只堅持使用天然食材，無人工添加物，讓您吃得安心健康。</p>
     </div>
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">⚙️</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">工藝流程</h3>
      <p class="text-gray-600 text-sm">手工初樣 → 精密機械加工 → <br>手工修整 → 最終品檢</p>
     </div>
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">👨‍🔧</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">匠人精神</h3>
      <p class="text-gray-600 text-sm">由具有多年經驗的師傅親自監工，每一細節皆經反覆檢查。</p>
     </div>
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">⭐</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">嚴選品質</h3>
      <p class="text-gray-600 text-sm">每一批產品都經過嚴格篩選，<br>確保品質穩定優良。</p>
     </div>
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-rose-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">❤️</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">用心服務</h3>
      <p class="text-gray-600 text-sm">以客戶滿意為目標，提供最貼心完善的服務，確保商品安全送達。</p>
     </div>
    </div>
   </div>
  </section><!-- 開口栗子專屬介紹 -->
  <section class="py-32 bg-gradient-to-br from-amber-50 via-yellow-50 to-orange-50 relative overflow-hidden"><!-- 背景裝飾 -->
   <div class="absolute inset-0">
    <div class="absolute top-20 right-10 w-40 h-40 bg-gradient-to-br from-amber-200/30 to-orange-200/30 rounded-full blur-3xl"></div>
    <div class="absolute bottom-20 left-10 w-32 h-32 bg-gradient-to-br from-yellow-200/30 to-amber-200/30 rounded-full blur-3xl"></div>
    <div class="absolute top-1/2 left-1/3 w-24 h-24 bg-gradient-to-br from-orange-200/20 to-red-200/20 rounded-full blur-2xl"></div>
   </div>
   <div class="max-w-7xl mx-auto px-6 lg:px-8 relative z-10"><!-- 標題區域 -->
    <div class="text-center mb-20 fade-in">
     <div class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-red-500 to-orange-500 text-white rounded-full text-sm font-medium tracking-wide mb-6 shadow-lg"><span class="mr-2">🍂</span> 全新上市
     </div>
     <h2 class="text-5xl lg:text-6xl font-display font-bold text-gray-900 mb-6 text-shadow"><span class="bg-gradient-to-r from-amber-600 to-orange-600 bg-clip-text text-transparent">開口栗子</span></h2>
     <p class="text-xl text-gray-600 max-w-3xl mx-auto font-light leading-relaxed">職人手工劃開，急速冷凍保鮮，讓您輕鬆享受栗子的天然香甜</p>
    </div><!-- 主要內容區域 -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center mb-20"><!-- 左側視覺內容 -->
     <div class="fade-in">
      <div class="relative"><!-- 主要產品展示卡片 -->
       <div class="glass-effect rounded-3xl shadow-2xl p-10 transform hover:scale-105 transition-transform duration-500">
        <div class="text-center"><!-- 栗子圖標 -->
       <img src="index/開口栗橫向/開口.png" width="960" alt="替代文字" />
       <br>
         <h4 class="text-3xl font-display font-bold text-gray-900 mb-3">開口栗子</h4>
         <p class="text-gray-600 mb-6 text-lg">職人手工劃開，急速冷凍保鮮</p><!-- 特色標籤 -->
         <div class="flex flex-wrap justify-center gap-3"><span class="px-4 py-2 bg-blue-100 text-blue-700 rounded-full text-sm font-medium">職人手工</span> <span class="px-4 py-2 bg-green-100 text-green-700 rounded-full text-sm font-medium">急速冷凍</span> <span class="px-4 py-2 bg-purple-100 text-purple-700 rounded-full text-sm font-medium">方便食用</span>
         </div>
        </div>
       </div><!-- 浮動裝飾元素 -->
       <div class="absolute -top-6 -right-6 w-24 h-24 bg-gradient-to-br from-amber-300 to-orange-300 rounded-full opacity-30 animate-pulse"></div>
       <div class="absolute -bottom-8 -left-8 w-32 h-32 bg-gradient-to-br from-yellow-200 to-amber-200 rounded-full opacity-40 animate-pulse" style="animation-delay: 1s;"></div><!-- 小裝飾卡片 -->
       <div class="absolute -bottom-6 -right-6 glass-effect rounded-2xl shadow-xl p-4 transform rotate-6 hover:rotate-0 transition-transform duration-300">
        <div class="text-3xl mb-2">
         🌰
        </div>
        <p class="text-sm font-medium text-gray-800">香甜可口</p>
       </div>
      </div>
     </div><!-- 右側文字內容 -->
     <div class="fade-in">
      <div class="space-y-8"><!-- 主要介紹 -->
       <div class="glass-effect rounded-3xl p-8 shadow-xl">
        <h3 class="text-3xl font-display font-bold text-gray-900 mb-6">為什麼選擇開口栗子？</h3>
        <div class="space-y-6 text-gray-600 leading-relaxed">
         <p class="text-lg">還在為栗子難剝殼而煩惱嗎？我們用心推出的<span class="font-semibold text-amber-600">「開口栗子」</span>， 讓您輕鬆享受栗子的美味。</p>
         <p>每一顆栗子都由職人細心手工劃開，再進行急速冷凍，完整保留栗子的天然香氣與甜味。 不需費力剝殼，一開即食，方便又好吃！</p>
        </div>
       </div><!-- 食用方式 -->
       <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div class="bg-white rounded-2xl shadow-lg p-6 border border-blue-100 hover:border-blue-200 transition-colors">
         <div class="flex items-center mb-4">
          <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4"><span class="text-2xl">❄️</span>
          </div>
          <h4 class="text-lg font-bold text-gray-900">冷凍直接吃</h4>
         </div>
         <p class="text-gray-600 text-sm">冰冰的口感，像是在品嚐綿密的栗子冰淇淋</p>
        </div>
        <div class="bg-white rounded-2xl shadow-lg p-6 border border-orange-100 hover:border-orange-200 transition-colors">
         <div class="flex items-center mb-4">
          <div class="w-12 h-12 bg-orange-100 rounded-full flex items-center justify-center mr-4"><span class="text-2xl">🔥</span>
          </div>
          <h4 class="text-lg font-bold text-gray-900">加熱享用</h4>
         </div>
         <p class="text-gray-600 text-sm">加熱後香氣濃郁、口感鬆軟，比一般栗子更細緻綿密</p>
        </div>
       </div><!-- 行動按鈕 -->
       <div class="flex justify-center"><a href="#contact" class="bg-gradient-to-r from-amber-500 to-orange-500 text-white px-12 py-4 rounded-full text-lg font-medium hover:from-amber-600 hover:to-orange-600 transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1"> 立即訂購 </a>
       </div>
      </div>
     </div>
    </div><!-- 產品特色區域 -->
    <div class="mb-20 fade-in">
     <div class="text-center mb-16">
      <h3 class="text-4xl font-display font-bold text-gray-900 mb-6">開口栗子的獨特優勢</h3>
      <p class="text-xl text-gray-600 max-w-2xl mx-auto leading-relaxed">每一個細節都經過精心設計，只為給您最完美的栗子體驗</p>
     </div>
     <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8"><!-- 優勢1 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-amber-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-amber-50 to-orange-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-amber-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             ✂️
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">職人手工劃開</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-amber-300 to-orange-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">每顆栗子都由經驗豐富的職人手工劃開，確保開口大小適中，既方便食用又不破壞栗子完整性。</p>
        </div>
       </div>
      </div><!-- 優勢2 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-blue-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-blue-50 to-sky-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-blue-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             ❄️
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">急速冷凍保鮮</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-blue-300 to-sky-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">採用急速冷凍技術，完整鎖住栗子的天然香氣與營養成分，讓您隨時都能品嚐到最新鮮的栗子。</p>
        </div>
       </div>
      </div><!-- 優勢3 -->
      <div class="group relative">
       <div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-500 p-8 h-full border border-gray-100 hover:border-green-200">
        <div class="flex flex-col h-full">
         <div class="flex items-start mb-6">
          <div class="flex-shrink-0 mr-6">
           <div class="w-20 h-20 bg-gradient-to-br from-green-50 to-emerald-100 rounded-3xl flex items-center justify-center shadow-sm group-hover:shadow-md transition-all duration-300 border border-green-100/50">
            <div class="text-4xl group-hover:scale-110 transition-transform duration-300">
             ⚡
            </div>
           </div>
          </div>
          <div class="flex-1">
           <h4 class="text-2xl font-display font-bold text-gray-900 mb-3">方便即食</h4>
           <div class="w-12 h-1 bg-gradient-to-r from-green-300 to-emerald-400 rounded-full mb-4"></div>
          </div>
         </div>
         <p class="text-gray-600 leading-relaxed flex-1">不需要任何工具，輕輕一掰就能享用。無論是辦公室零食、旅行點心，都能隨時隨地品嚐美味。</p>
        </div>
       </div>
      </div>
     </div>
    </div>
   </div>
  </section><!-- 商品介紹 -->
  <section id="products" class="py-32 bg-white">
   <div class="max-w-7xl mx-auto px-6 lg:px-8">
    <div class="text-center mb-20 fade-in"><span class="inline-block px-4 py-2 bg-gray-100 rounded-full text-sm font-medium text-gray-700 tracking-wide mb-6"> PREMIUM COLLECTION </span>
     <h2 class="text-5xl lg:text-6xl font-display font-bold text-gray-900 mb-6 text-shadow">精選<span class="bg-gradient-to-r from-amber-600 to-yellow-600 bg-clip-text text-transparent">商品</span></h2>
     <p class="text-xl text-gray-600 max-w-3xl mx-auto font-light">探索我們精心挑選的世界頂級堅果與果乾系列</p>
    </div><!-- 商品分類選單 -->
    <div class="flex justify-center mb-16 fade-in">
     <div class="bg-gray-100 rounded-full p-2 inline-flex"><button onclick="showCategory('all')" class="category-btn active px-8 py-3 rounded-full font-medium transition-all duration-300" data-category="all"> 全部商品 </button> <button onclick="showCategory('nuts')" class="category-btn px-8 py-3 rounded-full font-medium transition-all duration-300" data-category="nuts"> 🥜 堅果類 </button> <button onclick="showCategory('dried-fruits')" class="category-btn px-8 py-3 rounded-full font-medium transition-all duration-300" data-category="dried-fruits"> 🍓 果乾類 </button>
     </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10"><!-- 商品卡片 7 - 葵花籽 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-yellow-50 via-amber-50 to-orange-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/葵花子.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">現炒葵花籽</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">香脆可口的葵花籽，富含維生素E和健康油脂，營養滿分。</p>

       <button onclick="showProductDetails('葵花籽', '我們採用當季新鮮葵花子，收到訂單後才現炒，不添加任何化學調味。富含不飽和脂肪酸、維生素E與多種礦物質，營養健康看得見。純粹原味、香脆新鮮，是最自然的日常小點心。', 'NT$ 100', ['零添加化學調味・天然最安心', '營養豐富・健康一次到位', '當季現炒・最新鮮的原味', '香脆可口不油膩'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 19 - 南瓜籽 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-green-50 via-lime-50 to-yellow-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/南瓜籽.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">現炒南瓜籽</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">香脆南瓜籽，富含鋅與蛋白質，營養價值高的健康零食。</p>

       <button onclick="showProductDetails('南瓜籽', '當季現炒南瓜籽，一開封就聞得到的天然香氣，真正的新鮮看得見。富含鋅、鎂與優質好油，從能量代謝到入睡放鬆，全方位守護每日健康。無論男性保養、女性調理或上班族補充體力，一包就能輕鬆補給。', 'NT$ 100', ['當季現炒新鮮力・嚐得到的原味品質', '高效營養配方・鋅鎂補給一次到位', '高纖順暢力・全面提升代謝機能', '助眠舒壓關鍵成分・打造日常健康力'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 8 - 紅心芭樂乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-pink-50 via-rose-50 to-red-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/紅心芭樂乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">紅心芭樂乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">精選紅心芭樂製成，保留天然甜味與豐富維生素C。</p>

       <button onclick="showProductDetails('紅心芭樂乾', '紅心芭樂乾以自然熟成的紅心芭樂製成，保留濃郁果香與純粹風味。富含纖維、維生素A與C，以及磷、鈣、鎂等多種營養元素。高纖特性有助腸胃順暢，是兼具美味與健康的輕奢果乾新選擇。', 'NT$ 200', ['高纖滿分・促進腸胃蠕動', '維生素A、C豐富・提升日常保護力', '多種礦物質補給・營養更均衡', '天然紅心芭樂製成・健康美味一次擁有'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 200</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 9 - 燕巢芭樂乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-green-50 via-lime-50 to-emerald-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/燕巢芭樂乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">燕巢芭樂乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">高雄燕巢特產芭樂製成，口感Q彈，天然果香濃郁。</p>

       <button onclick="showProductDetails('燕巢芭樂乾', '嚴選燕巢當季芭樂，以純水果製成，呈現最真實的天然原味。全程零化學添加，無防腐劑、人工香料與色素，安心看得見。採低溫烘焙技術鎖住營養與果肉口感，帶來最純粹的高品質果乾享受。', 'NT$ 200', ['嚴選當季燕巢芭樂・品質更升級', '100%純果製作・吃得到真實果香', '零添加更安心・健康無負擔首選', '低溫烘焙技術・完美鎖住營養與原味'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 200</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 10 - 地瓜乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-orange-50 via-amber-50 to-yellow-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/地瓜乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">地瓜乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">台灣優質地瓜製成，香甜軟Q，富含膳食纖維與營養。</p>

       <button onclick="showProductDetails('地瓜乾', '嚴選優質品種地瓜，低脂零添加，以細緻工法長時間烘製，保留自然香甜與柔軟糯香的完美口感。每片皆以人工挑選與真空獨立包裝呈現，衛生安心、肉厚飽滿、纖維細膩。純粹天然的甘甜風味，讓老少皆宜的健康美味隨時輕鬆享用。', 'NT$ 260', ['嚴選特級地瓜・零脂肪更健康', '長時烘製工法・Q軟香甜不乾硬', '真空獨立包裝・衛生便利品質穩定', '無糖無添加・老少皆宜的天然甘甜'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 260</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 11 - 蔓越莓乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-red-50 via-pink-50 to-rose-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/蔓越莓乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">蔓越莓乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">酸甜蔓越莓乾，富含花青素與抗氧化物，美味又健康。</p>

       <button onclick="showProductDetails('蔓越莓乾', '蔓越莓被譽為「北美紅寶石」，以鮮豔紅潤的果實凝聚珍貴 A 型前花青素與多種微量元素。精心乾燥保留酸甜原香，每一口都富含膳食纖維與天然抗氧化力。無論日常保養或健康小食，都能優雅補充能量，展現由內而外的亮麗。', 'NT$ 200', ['北美紅寶石・天然酸甜的高營養果乾', '富含A型前花青素・女性私密保養首選', '維生素C與抗氧化成分・養顏美容更亮采', '高膳食纖維・促進腸道蠕動與消化健康'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 200</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 12 - 草莓乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-pink-50 via-red-50 to-rose-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/草莓乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">草莓乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">香甜草莓乾，保留新鮮草莓的天然甜味與豐富維生素。</p>

       <button onclick="showProductDetails('草莓乾', '我們堅持真材實料與零添加，用最純粹的方式呈現有機草莓的自然原味。精選大顆鮮果急凍凍乾，無精緻糖、無防腐劑、無香精，保留最真實的香氣與口感。一口品嚐，就能感受健康、純淨、毫不妥協的高品質享受。', 'NT$ 100', ['有機特選大顆草莓・真材實料看得見', '零添加五無堅持・健康無負擔', '低溫凍乾技術・保留草莓原始香甜', '安心純粹配方・全家都能放心享用'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 13 - 水蜜桃乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-orange-50 via-yellow-50 to-pink-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/水蜜桃乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">水蜜桃乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">香甜水蜜桃乾，濃郁果香與柔軟口感，如夏日陽光般溫暖。</p>

       <button onclick="showProductDetails('水蜜桃乾', '嚴選飽滿多汁的當季水蜜桃，以低溫烘焙技術鎖住天然果香與細緻甜味，呈現最純粹的蜜桃滋味。每一片都保有柔軟Q彈的口感與自然色澤，無添加香精、色素與防腐劑，吃得到真實果肉的層次。香甜而不膩、清爽而耐嚼，是追求健康零食的你隨時都能享受的輕奢果乾選擇。', 'NT$ 100', ['當季鮮果製作・鎖住原生蜜桃香', '低溫烘焙工法・保留柔軟Q彈口感', '零香精零色素・純天然更安心', '真果肉厚切・輕奢級健康零食'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 14 - 金鑽鳳梨乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-yellow-50 via-amber-50 to-orange-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/鳳梨乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-yellow-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        預購
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">金鑽鳳梨乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">台灣金鑽鳳梨製成，酸甜平衡完美，濃郁熱帶風味。</p>

       <button onclick="showProductDetails('金鑽鳳梨乾', '選用台灣在地金鑽鳳梨，採收後低溫慢烘，完整保留果肉的濃郁香氣與自然酸甜。纖維細緻、果香飽滿，不添加糖與香料，讓你品嚐到最純粹的天然風味。每一片都是陽光、土壤與時間淬鍊出的黃金滋味，甘甜不膩、越嚼越香。', 'NT$ 200', ['嚴選台灣金鑽・天然原果香氣', '零糖零添加・純粹無負擔', '低溫慢烘工法・鎖住酸甜精華', '果肉厚實飽滿・越嚼越香的好滋味'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 200</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 15 - 蜜棗 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-red-50 via-rose-50 to-pink-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/蜜棗.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">蜜棗</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">精選蜜棗，蜜糖香甜，口感軟嫩，富含維生素與礦物質。</p>

       <button onclick="showProductDetails('蜜棗', '採用頂級飽滿的大蜜棗，經過反覆蒸曬與多道細緻工序，將果實的香甜凝縮至最純粹的狀態。全程完全無添加，保留蜜棗天然的香、糯、甜，每一口都是大自然最純粹的味道。', 'NT$ 100', ['頂級大果嚴選・飽滿甜度更升級', '反覆蒸曬工法・濃縮天然原香', '零添加製程・安心純淨味蕾享受', '多道手作工序・呈現香糯細緻口感'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 16 - 芝麻糕 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-gray-50 via-stone-50 to-amber-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/芝麻糕.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">芝麻糕</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">傳統手工芝麻糕，香濃芝麻味，口感綿密，懷舊美味。</p>
       
       <button onclick="showProductDetails('芝麻糕', '手工精製的芝麻糕，以嚴選黑芝麻結合何首烏製成，香濃不膩、入口即化。堅持純粹原料與傳統工法，每一口都能品嚐到芝麻的天然香氣與溫潤滋味。口感細緻、不黏牙，大人小孩都能輕鬆享受的健康小點。', 'NT$ 100', ['手工製作・香濃細膩更迷人', '芝麻 × 何首烏・雙重養生精華', '不黏牙口感・老少皆宜的甜點', '純粹原料・無負擔的安心美味'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 17 - 甘栗仁 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-amber-50 via-yellow-50 to-orange-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/甘栗仁.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">甘栗仁</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">精選優質甘栗仁，香甜軟糯，營養豐富，品牌招牌商品。</p>

       <button onclick="showProductDetails('甘栗仁', '採用 河北省高山 A 級樹上自然熟成、自然掉落的優質栗子，以專業工法低溫製作，全程 無添加香精、香料、防腐劑，完整保留栗子最純粹的香甜與綿密。色澤因天然熟成而略有差異，屬正常現象，請安心品嚐。粒粒飽滿、鬆綿香甜、入口即化，免剝殼即可享受最天然的甘栗風味。採用無菌包裝，未拆封可依標示保存；拆封後未食用完請冷藏。', 'NT$ 100', ['樹上熟成 A 級高山栗・天然香甜更升級', '零添加保留原味・安心純素最簡單', '免剝殼即開即食・隨時享受綿密口感', '無菌包裝更安心・美味保存更持久'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100 (3包) </span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 18 - 開口栗子 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-yellow-50 via-amber-50 to-orange-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/開口栗.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
       <div class="absolute top-4 left-4 bg-red-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        🍂 全新上市
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">開口栗子</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">經典開口栗子，方便食用，香甜可口，老少皆宜的美味。</p>

       <button onclick="showProductDetails('開口栗子', '還在為剝不開栗子而煩惱嗎？開口栗子替你省去所有麻煩，每一顆都精準切口、輕鬆一剝即開。冷熱皆宜、綿密香甜，並以接單現做的方式確保新鮮與最佳風味，是你隨時品味天然甜香的完美選擇。', 'NT$ 100', ['開口即食・輕鬆不費力', '冷熱皆香・綿密雙享受', '接單現做・新鮮看得見', '天然甜香・零負擔美味'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 20 - 阿克蘇帶殼紙皮核桃 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-amber-50 via-orange-50 to-yellow-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/核桃.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        現貨
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">阿克蘇帶殼紙皮核桃</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">新疆阿克蘇帶殼紙皮核桃，皮薄肉厚，營養豐富，頂級品質。</p>

       <button onclick="showProductDetails('阿克蘇帶殼紙皮核桃', '嚴選來自新疆阿克蘇的紙皮核桃，堅持傳統 帶殼日曬，自然成熟、風味濃郁。薄紙皮好剝、果仁飽滿，入口清香醇厚，保留核桃原始的健康營養。無添加、無烘油，純粹天然，讓你吃得到最樸實的堅果原味。', 'NT$ 100', ['日曬熟成・風味更濃香', '薄皮好剝・顆顆飽滿香脆', '天然無添加・健康零負擔', '原產地直送・品質安心可見'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 21 - 腰果 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-yellow-50 via-cream-50 to-orange-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/腰果.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-yellow-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        預購
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">腰果</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">香濃腰果，口感滑順，富含健康脂肪與蛋白質，營養美味。</p>

       <button onclick="showProductDetails('腰果', '嚴選飽滿大顆的頂級腰果，使用低溫烘焙方式保留其天然堅果香氣與細緻奶香口感。無添加化學調味，純粹原味更能品嘗腰果的清甜與滑順。富含優質植物性蛋白、不飽和脂肪酸及多種維生素礦物質，是兼具美味與營養的健康零食選擇。', 'NT$ 200', ['特選大顆原粒・口感飽滿更香脆', '低溫烘焙工法・保留天然奶香', '零添加更純粹・健康輕鬆吃', '高營養好能量・隨時補充元氣'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 200</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 22 - 開心果 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-green-50 via-lime-50 to-emerald-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/開心果.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
       
       </div>
       <div class="absolute top-4 right-4 bg-yellow-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        預購
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">開心果</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">優質開心果，香脆可口，富含抗氧化物，讓您開心享受美味。</p>

       <button onclick="showProductDetails('開心果', '嚴選優質開心果，果粒飽滿、自然清香，以低溫烘焙方式保留原始風味與營養。口感香脆不油膩，淡雅堅果香在口中綻放，每一顆都是真材實料的天然美味。無人工添加、不過度調味，健康輕負擔，是日常補充能量與享受零嘴的最佳選擇。', 'NT$ 200', ['嚴選大果・飽滿香脆', '低溫烘焙・保留自然風味', '無人工添加・健康更安心', '優質營養補給・輕鬆好享受'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 200</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 23 - 葡萄乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-purple-50 via-violet-50 to-indigo-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/葡萄乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-yellow-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        預購
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">葡萄乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">天然葡萄乾，香甜可口，富含鐵質與天然糖分，營養豐富。</p>

       <button onclick="showProductDetails('葡萄乾', '嚴選日照充足、果肉飽滿的優質葡萄，以低溫自然乾燥方式保留天然甜味與完整營養。每顆葡萄乾皆皮薄多汁、柔軟Q彈，散發濃郁果香，酸甜平衡不卡喉。無添加糖與人工香料，是隨手可享的純粹天然零食，也是烘焙、料理的最佳營養配料。', 'NT$ 100', ['嚴選飽滿果粒・天然原味保留', '低溫慢烘工法・濃縮果香精華', '零添加糖與香料・純淨更安心', '多用途好搭配・零食烘焙皆適合'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 24 - 李子乾 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="dried-fruits">
      <div class="relative h-80 bg-gradient-to-br from-purple-50 via-pink-50 to-red-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/李子乾.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-yellow-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        預購
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">李子乾</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">酸甜李子乾，口感Q彈，富含維生素與膳食纖維，健康美味。</p>

       <button onclick="showProductDetails('李子乾', '嚴選成熟飽滿的新鮮李子，經低溫精緻烘乾工法保留果香層次，呈現自然酸甜、柔軟Q彈的口感。無添加香精色素，每一口都是真實果味。獨立包裝設計方便衛生，是兼具健康與美味的每日輕零食首選。', 'NT$ 100', ['嚴選鮮果・自然原味保留', '低溫慢烘・酸甜Q彈不死甜', '零香精色素・純粹更安心', '大包裝分享・健康美味更實在'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 100</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div><!-- 商品卡片 25 - 胡桃 -->
     <div class="product-card glass-effect rounded-3xl shadow-xl overflow-hidden fade-in group" data-category="nuts">
      <div class="relative h-80 bg-gradient-to-br from-brown-50 via-amber-50 to-orange-100 flex items-center justify-center overflow-hidden cursor-pointer product-image" onclick="showPrice(this)">
       <div class="absolute inset-0 bg-gradient-to-br from-transparent via-white/20 to-transparent"><img src="index/官網/胡桃.png" alt="替代文字" /></div>
       <div class="relative z-10 text-center">
        
       </div>
       <div class="absolute top-4 right-4 bg-yellow-500 text-white text-xs px-2 py-1 rounded-full font-medium">
        預購
       </div>
      </div>
      <div class="p-8">
       <h3 class="text-2xl font-display font-semibold text-gray-900 mb-3">胡桃</h3>
       <p class="text-gray-600 mb-6 font-light leading-relaxed">優質胡桃，香脆可口，富含Omega-3脂肪酸，有益心血管健康。</p>

       <button onclick="showProductDetails('胡桃', '嚴選高山胡桃，富含Omega-3、不飽和脂肪酸、膳食纖維與多種抗氧化營養素。以低溫烘焙保留堅果最自然的油脂香氣，口感酥脆、香味濃郁，純粹無調味，更能品嚐胡桃本身的高級風味。無論作為日常零食或搭配沙拉、早餐穀物，都能為你的飲食增添天然健康能量。', 'NT$ 200', ['低溫烘焙・保留純粹胡桃香氣', '富含Omega-3・營養全面升級', '無添加更安心・天然原味享受', '嚴選飽滿果仁・酥脆頂級口感'])" class="text-amber-600 hover:text-amber-700 text-sm font-medium mb-4 inline-flex items-center group"> 了解更多 
        <svg class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg></button>

       <div class="flex justify-between items-center">
        <div class="price-display hidden"><span class="text-xl font-bold text-gray-900">NT$ 200</span>
        </div>
        <div class="price-placeholder"><span class="text-lg text-gray-500">點擊圖片查看價格</span>
        </div><a href="#contact" class="btn-luxury text-white px-6 py-3 rounded-full font-medium tracking-wide group order-btn hidden"> 立即訂購 <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span> </a>
       </div>
      </div>
     </div>
    </div>
   </div>
  </section><!-- 顧客回饋 -->
  <section id="reviews" class="py-20 bg-white">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16 fade-in">
     <h2 class="text-4xl font-bold text-gray-800 mb-4">顧客回饋</h2>
     <p class="text-xl text-gray-600">聽聽我們顧客的真實心聲</p>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
     <div class="bg-gray-50 rounded-2xl p-8 fade-in">
      <div class="flex items-center mb-4">
       <div class="w-12 h-12 bg-amber-200 rounded-full flex items-center justify-center mr-4"><span class="text-xl">👩</span>
       </div>
       <div>
        <h4 class="font-bold text-gray-800">林小姐</h4>
        <div class="flex text-yellow-400">
         ⭐⭐⭐⭐⭐
        </div>
       </div>
      </div>
      <p class="text-gray-600 italic">"品質真的很棒！堅果很新鮮，包裝也很精美。已經回購好幾次了，會繼續支持！"</p>
     </div>
     <div class="bg-gray-50 rounded-2xl p-8 fade-in">
      <div class="flex items-center mb-4">
       <div class="w-12 h-12 bg-amber-200 rounded-full flex items-center justify-center mr-4"><span class="text-xl">👨</span>
       </div>
       <div>
        <h4 class="font-bold text-gray-800">陳先生</h4>
        <div class="flex text-yellow-400">
         ⭐⭐⭐⭐⭐
        </div>
       </div>
      </div>
      <p class="text-gray-600 italic">"果乾的甜度剛好，不會太甜膩。送貨速度也很快，客服態度很好，推薦給大家！"</p>
     </div>
     <div class="bg-gray-50 rounded-2xl p-8 fade-in">
      <div class="flex items-center mb-4">
       <div class="w-12 h-12 bg-amber-200 rounded-full flex items-center justify-center mr-4"><span class="text-xl">👵</span>
       </div>
       <div>
        <h4 class="font-bold text-gray-800">王奶奶</h4>
        <div class="flex text-yellow-400">
         ⭐⭐⭐⭐⭐
        </div>
       </div>
      </div>
      <p class="text-gray-600 italic">"孫子們都很喜歡吃，比外面買的健康多了。價格合理，品質有保證，很滿意！"</p>
     </div>
    </div>
   </div>
  </section><!-- 聯絡資訊 -->
  <section id="contact" class="py-20 bg-gray-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16 fade-in">
     <h2 class="text-4xl font-bold text-gray-800 mb-4">聯絡我們</h2>
     <p class="text-xl text-gray-600">有任何問題歡迎與我們聯繫</p>
    </div>
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
     <div class="fade-in">
      <div class="bg-white rounded-2xl shadow-lg p-8">
       <h3 class="text-2xl font-bold text-gray-800 mb-6">聯絡資訊</h3>
       <div class="space-y-6">
        <div class="flex items-center">
         <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4"><span class="text-xl">📞</span>
         </div>
         <div>
          <h4 class="font-bold text-gray-800">電話</h4>
          <p class="text-gray-600">0932-245-037 / 0986-375-001</p>
         </div>
        </div>
        <div class="flex items-center">
         <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4"><span class="text-xl">💬</span>
         </div>
         <div>
          <h4 class="font-bold text-gray-800">官方LINE</h4><a href="https://lin.ee/oVmKR5H" target="_blank" rel="noopener noreferrer" class="text-green-600 hover:text-green-700 transition-colors underline"> https://lin.ee/oVmKR5H </a>
         </div>
        </div>
        <div class="flex items-start">
         <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4 mt-2"><span class="text-xl">📱</span>
         </div>
         <div class="flex-1">
          <h4 class="font-bold text-gray-800 mb-3">LINE QR Code</h4>
          <div class="bg-white p-4 rounded-lg shadow-md inline-block border-2 border-green-200"><!-- LINE QR Code SVG -->
           <svg width="10" height="10" viewbox="0 0 10 10" class="block"><img src="index/就愛栗官方LINE/就愛栗官方LINE.jpg" style="width:150px; height:auto;" alt="替代文字" /><!-- QR Code 背景 --> 
           </svg>
          </div>
          <p class="text-sm text-gray-500 mt-2">掃描QR Code 加入官方LINE</p>
         </div>
        </div>
       </div>
      </div>
     </div>
     <div class="fade-in">
      <div class="bg-white rounded-2xl shadow-lg p-8">
       <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center">🌰 就愛栗 明日出攤公告！</h3><!-- 出攤資訊卡片 -->
       <div class="bg-gradient-to-br from-amber-50 to-orange-50 border-2 border-amber-200 rounded-2xl p-6 mb-6">
        <div class="space-y-4">
         <div class="flex items-center"><span class="text-2xl mr-3">📅</span>
          <div><span class="font-bold text-gray-800">明天 !!! &nbsp; 11/27(週四)</span>
          </div>
         </div>
         <div class="flex items-center"><span class="text-2xl mr-3">📍</span>
          <div><span class="text-gray-700">我們會在 </span> <span class="font-bold text-amber-700">宜蘭南館市場</span> <span class="text-gray-700"> 出攤囉！</span>
          </div>
         </div>
         <div class="flex items-center"><span class="text-2xl mr-3">🕒</span>
          <div><span class="text-gray-700">時間：</span> <span class="font-bold text-blue-700">07:00 – 13:00</span>
          </div>
         </div>
         <div class="flex items-start"><span class="text-2xl mr-3 mt-1">🧭</span>
          <div><span class="text-gray-700">攤位位置：</span> <span class="font-bold text-green-700">宜蘭市民生街24號</span>
          </div>
         </div>
        </div>
       </div><!-- 商品介紹 -->
       <div class="bg-gradient-to-r from-rose-50 to-pink-50 border border-rose-200 rounded-xl p-5 mb-6">
        <p class="text-gray-700 leading-relaxed text-center">香噴噴的栗子、酥脆的葵花子<br>好吃不膩的果乾與堅果都準備好啦～<br>
          快來跟我們打個招呼、聞香一下 <span class="text-red-500">❤️</span></p>
       </div><!-- 提醒訊息 -->
       <div class="bg-blue-50 border border-blue-200 rounded-xl p-5">
        <div class="flex items-start"><span class="text-2xl mr-3 mt-1">👉</span>
         <div class="text-blue-800">
          <p class="font-medium mb-1">每天晚上更新「明日出攤地點」，</p>
          <p class="text-sm">想找就愛栗，不怕撲空唷！</p>
         </div>
        </div>
       </div>
      </div>
     </div>
    </div>
   </div>
  </section><!-- 訂購資訊 -->
  <section id="order" class="py-20 bg-white">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16 fade-in">
     <h2 class="text-4xl font-bold text-gray-800 mb-4">訂購資訊</h2>
     <p class="text-xl text-gray-600">簡單快速的訂購流程</p>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-12">
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">🛒</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">選擇商品</h3>
      <p class="text-gray-600">瀏覽我們的商品<br>選擇您喜歡的堅果果乾</p>
     </div>
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">📝</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">填寫資料</h3>
      <p class="text-gray-600">填寫收件人資訊和寄送方式</p>
     </div>
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">💳</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">確認付款</h3>
      <p class="text-gray-600">確認訂單內容與付款方式</p>
     </div>
     <div class="text-center fade-in">
      <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-4"><span class="text-2xl">🚚</span>
      </div>
      <h3 class="text-lg font-bold text-gray-800 mb-2">快速配送</h3>
      <p class="text-gray-600">1-3個工作天內送達您指定的地址</p>
     </div>
    </div>
    <div class="bg-amber-50 rounded-2xl p-8 fade-in">
     <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center">訂購須知</h3>
     <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div>
       <h4 class="text-lg font-bold text-gray-800 mb-4">配送資訊</h4>
       <ul class="space-y-3 text-gray-600">
        <li class="flex items-start"><span class="text-green-600 mr-2">✅</span>
         <div><strong class="text-green-700">滿 NT$ 1,500 元免運費</strong>
         </div></li>
        <li class="flex items-start"><span class="text-amber-600 mr-2">✅</span>
         <div><strong>未滿 NT$ 1,500 元酌收運費：</strong>
          <ul class="mt-2 ml-4 space-y-1">
           <li>• 宅配到府：NT$ 150</li>
           <li>• 7-11 店到店：NT$ 38</li>
           <li>• 全家 店到店：NT$ 39</li>
          </ul>
         </div></li>
        <li class="text-sm text-gray-500">※ 以上皆支援貨到付款</li>
       </ul>
      </div>
      <div>
       <h4 class="text-lg font-bold text-gray-800 mb-4">訂購平台</h4>
       <div class="space-y-4"><a href="https://myship.7-11.com.tw/general/detail/GM2209129533610" target="_blank" rel="noopener noreferrer" class="flex items-center p-4 bg-green-50 border border-green-200 rounded-lg hover:bg-green-100 transition-colors group">
         <div class="w-12 h-12 bg-green-500 rounded-lg flex items-center justify-center mr-4"><span class="text-white font-bold text-lg">7</span>
         </div>
         <div class="flex-1">
          <h5 class="font-bold text-gray-800">7-ELEVEN</h5>
          <p class="text-sm text-gray-600">店到店取貨付款</p>
         </div><span class="text-green-600 group-hover:translate-x-1 transition-transform">→</span> </a> <a href="https://famistore.famiport.com.tw/famistore/users/1642104/malls/0100000000000000007063fe" target="_blank" rel="noopener noreferrer" class="flex items-center p-4 bg-blue-50 border border-blue-200 rounded-lg hover:bg-blue-100 transition-colors group">
         <div class="w-12 h-12 bg-blue-500 rounded-lg flex items-center justify-center mr-4"><span class="text-white font-bold text-sm">全家</span>
         </div>
         <div class="flex-1">
          <h5 class="font-bold text-gray-800">全家便利商店</h5>
          <p class="text-sm text-gray-600">店到店取貨付款</p>
         </div><span class="text-blue-600 group-hover:translate-x-1 transition-transform">→</span> </a> <a href="https://shopee.tw/gingerben" target="_blank" rel="noopener noreferrer" class="flex items-center p-4 bg-orange-50 border border-orange-200 rounded-lg hover:bg-orange-100 transition-colors group">
         <div class="w-12 h-12 bg-orange-500 rounded-lg flex items-center justify-center mr-4"><span class="text-white font-bold text-sm">蝦皮</span>
         </div>
         <div class="flex-1">
          <h5 class="font-bold text-gray-800">蝦皮購物</h5>
          <p class="text-sm text-gray-600">線上購物平台</p>
         </div><span class="text-orange-600 group-hover:translate-x-1 transition-transform">→</span> </a>
       </div>
      </div>
     </div>
    </div>
   </div>
  </section><!-- 頁尾 -->
  <footer class="bg-gray-800 text-white py-12">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
     <div>
      <h3 class="text-2xl font-bold mb-4">🌰 就愛栗</h3>
      <p class="text-gray-300">提供最優質的堅果果乾，讓您享受健康美味的生活。</p>
     </div>
     <div>
      <h4 class="text-lg font-bold mb-4">快速連結</h4>
      <ul class="space-y-2 text-gray-300">
       <li><a href="#story" class="hover:text-amber-400 transition-colors">品牌故事</a></li>
       <li><a href="#about" class="hover:text-amber-400 transition-colors">關於我們</a></li>
       <li><a href="#products" class="hover:text-amber-400 transition-colors">商品介紹</a></li>
       <li><a href="#contact" class="hover:text-amber-400 transition-colors">聯絡我們</a></li>
      </ul>
     </div>
     <div>
      <h4 class="text-lg font-bold mb-4">聯絡資訊</h4>
      <ul class="space-y-2 text-gray-300">
       <li>📞 0932-245-037 / 0986-375-001</li>
       <li>💬 <a href="https://lin.ee/oVmKR5H" target="_blank" rel="noopener noreferrer" class="hover:text-green-400 transition-colors">官方LINE</a></li>
      </ul>
     </div>
     <div>
      <h4 class="text-lg font-bold mb-4">關注我們</h4>
      <ul class="space-y-2 text-gray-300">
        <li><a href="https://www.facebook.com/JIOW.AY.LIH.0932245037" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-amber-400 transition-colors">Facebook</a></li>
        <li><a href="https://www.instagram.com/jiow_ay_lih?utm_source=ig_web_button_share_sheet&amp;igsh=ZDNlZDc0MzIxNw==" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-amber-400 transition-colors">Instagram</a></li>
        <li><a href="https://lin.ee/oVmKR5H" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-amber-400 transition-colors">LINE</a></li>
        <li><a href="https://www.tiktok.com/@jiow_ay_lih?_r=1&_t=ZS-91iZ7tkykKN" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-amber-400 transition-colors">TikTok</a></li>
      </ul>
     </div>
    </div>
    <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-300">
     <p>© 1998 就愛栗 JIOW AI LIH. All rights reserved.</p>
    </div>
   </div>
  </footer>
  <script>
        // 淡入動畫
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.fade-in').forEach(el => {
            observer.observe(el);
        });

        // 手機版選單
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // 平滑滾動
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // 商品價格顯示功能
        function showPrice(element) {
            const card = element.closest('.product-card');
            const priceDisplay = card.querySelector('.price-display');
            const pricePlaceholder = card.querySelector('.price-placeholder');
            const orderBtn = card.querySelector('.order-btn');
            
            // 隱藏提示文字，顯示價格和按鈕
            pricePlaceholder.classList.add('hidden');
            priceDisplay.classList.remove('hidden');
            orderBtn.classList.remove('hidden');
            
            // 添加點擊效果
            element.style.transform = 'scale(0.98)';
            setTimeout(() => {
                element.style.transform = '';
            }, 150);
        }

        // 商品分類篩選功能
        function showCategory(category) {
            // 更新按鈕狀態
            document.querySelectorAll('.category-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            document.querySelector(`[data-category="${category}"]`).classList.add('active');
            
            // 篩選商品
            const products = document.querySelectorAll('.product-card');
            products.forEach(product => {
                if (category === 'all' || product.dataset.category === category) {
                    product.style.display = 'block';
                    // 重新觸發淡入動畫
                    product.style.opacity = '0';
                    product.style.transform = 'translateY(30px)';
                    setTimeout(() => {
                        product.style.opacity = '1';
                        product.style.transform = 'translateY(0)';
                        product.style.transition = 'all 0.6s cubic-bezier(0.4, 0, 0.2, 1)';
                    }, 100);
                } else {
                    product.style.display = 'none';
                }
            });
        }

        // 表單提交處理
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('感謝您的留言！我們會盡快回覆您。\n\n注意：這是展示用的表單，實際功能需要後端支援。');
        });

 // 顯示商品詳細資訊（更新版 - 支援自訂特色）
        function showProductDetails(productName, productDescription, productPrice, features) {
            // 創建彈窗背景
            const modalBackdrop = document.createElement('div');
            modalBackdrop.className = 'fixed inset-0 bg-black bg-opacity-50 z-50 flex items-center justify-center p-4';
            modalBackdrop.style.backdropFilter = 'blur(5px)';
            
            // 如果沒有提供特色，使用預設值
            if (!features) {
                features = [
                    '100% 天然無添加',
                    '嚴選優質原料',
                    '專業品質檢驗',
                    '新鮮配送保證'
                ];
            }
            
            // 創建特色列表HTML
            const featuresHTML = features.map(feature => `
                <li class="flex items-start">
                    <svg class="w-5 h-5 text-green-600 mr-2 mt-0.5 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                    </svg>
                    <span>${feature}</span>
                </li>
            `).join('');
            
            // 創建彈窗內容
            const modalContent = document.createElement('div');
            modalContent.className = 'bg-white rounded-3xl shadow-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto';
            modalContent.innerHTML = `
                <div class="p-8">
                    <div class="flex justify-between items-start mb-6">
                        <h3 class="text-3xl font-display font-bold text-gray-900">${productName}</h3>
                        <button onclick="closeProductModal(this)" class="text-gray-400 hover:text-gray-600 transition-colors">
                            <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
                            </svg>
                        </button>
                    </div>
                    
                    <div class="mb-6">
                        <h4 class="text-lg font-semibold text-gray-900 mb-3">商品描述</h4>
                        <p class="text-gray-600 leading-relaxed">${productDescription}</p>
                    </div>
                    
                    <div class="mb-6 p-4 bg-amber-50 rounded-2xl">
                        <h4 class="text-lg font-semibold text-gray-900 mb-3">商品特色</h4>
                        <ul class="space-y-2 text-gray-700">
                            ${featuresHTML}
                        </ul>
                    </div>
                    
                    <div class="flex items-center justify-between pt-6 border-t border-gray-200">
                        <div>
                            <p class="text-sm text-gray-500 mb-1">建議售價</p>
                            <p class="text-3xl font-bold text-gray-900">${productPrice}</p>
                        </div>
                        <a href="#contact" onclick="closeProductModal(this)" class="btn-luxury text-white px-8 py-4 rounded-full font-medium tracking-wide group">
                            立即訂購
                            <span class="ml-2 group-hover:translate-x-1 transition-transform duration-300 inline-block">→</span>
                        </a>
                    </div>
                </div>
            `;
            
            modalBackdrop.appendChild(modalContent);
            document.body.appendChild(modalBackdrop);
            
            // 點擊背景關閉彈窗
            modalBackdrop.addEventListener('click', function(e) {
                if (e.target === modalBackdrop) {
                    closeProductModal(modalBackdrop);
                }
            });
        }

        // 關閉商品詳細資訊彈窗
        function closeProductModal(element) {
            const modal = element.closest('.fixed');
            if (modal) {
                modal.remove();
            }
        }

        // 平滑滾動
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    // 關閉手機選單
                    if (mobileMenu && !mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });

    </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'99c3ddfa214db016',t:'MTc2Mjc2MDA2My4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
