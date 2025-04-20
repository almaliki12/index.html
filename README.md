# index.<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>المالكي للخدمات الالكترونية - أرقام وهمية</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        secondary: '#3F3D56',
                        accent: '#14B8A6'
                    }
                }
            }
        }
        
        // Dark mode detection
        if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
            document.documentElement.classList.add('dark');
        }
        
        window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', event => {
            if (event.matches) {
                document.documentElement.classList.add('dark');
            } else {
                document.documentElement.classList.remove('dark');
            }
        });
    </script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap');
        
        body {
            font-family: 'Tajawal', sans-serif;
        }
        
        .platform-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .custom-scrollbar::-webkit-scrollbar {
            width: 5px;
            height: 5px;
        }
        
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #5D5CDE;
            border-radius: 5px;
        }
        
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        
        .dark .custom-scrollbar::-webkit-scrollbar-track {
            background: #2d2d2d;
        }
        
        .shine {
            position: relative;
            overflow: hidden;
        }
        
        .shine::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(
                to right,
                rgba(255, 255, 255, 0) 0%,
                rgba(255, 255, 255, 0.3) 50%,
                rgba(255, 255, 255, 0) 100%
            );
            transform: rotate(30deg);
            animation: shine 3s infinite;
        }
        
        @keyframes shine {
            0% {
                transform: translateX(-100%) rotate(30deg);
            }
            100% {
                transform: translateX(100%) rotate(30deg);
            }
        }
        
        .dark .shine::after {
            background: linear-gradient(
                to right,
                rgba(255, 255, 255, 0) 0%,
                rgba(255, 255, 255, 0.1) 50%,
                rgba(255, 255, 255, 0) 100%
            );
        }
    </style>
</head>
<body class="bg-white dark:bg-gray-900 text-gray-800 dark:text-gray-200 transition-colors duration-300">
    <!-- Header -->
    <header class="sticky top-0 z-50 bg-white dark:bg-gray-900 shadow-md">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-4 space-x-reverse">
                <div class="text-2xl font-bold text-primary">
                    <span class="text-primary">المالكي</span>
                    <span class="text-secondary dark:text-gray-300"> للخدمات الالكترونية</span>
                </div>
            </div>
            <nav class="hidden md:flex space-x-6 space-x-reverse">
                <a href="#platforms" class="hover:text-primary transition-colors">المنصات</a>
                <a href="#search" class="hover:text-primary transition-colors">البحث</a>
                <a href="#featured" class="hover:text-primary transition-colors">الأكثر طلباً</a>
                <a href="#contact" class="hover:text-primary transition-colors">تواصل معنا</a>
            </nav>
            <div class="flex items-center space-x-4 space-x-reverse">
                <button id="mobileMenuButton" class="md:hidden text-gray-500 hover:text-primary">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-white dark:bg-gray-800 shadow-lg transition-all duration-300 absolute w-full">
            <div class="container mx-auto px-4 py-2">
                <nav class="flex flex-col space-y-3">
                    <a href="#platforms" class="py-2 hover:text-primary transition-colors">المنصات</a>
                    <a href="#search" class="py-2 hover:text-primary transition-colors">البحث</a>
                    <a href="#featured" class="py-2 hover:text-primary transition-colors">الأكثر طلباً</a>
                    <a href="#contact" class="py-2 hover:text-primary transition-colors">تواصل معنا</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative py-10 md:py-16 bg-gradient-to-br from-primary/10 to-primary/5 dark:from-primary/5 dark:to-gray-900 overflow-hidden">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center justify-between">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <h1 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-4 text-primary dark:text-white leading-tight">
                        أرقام وهمية لجميع المنصات الرقمية
                    </h1>
                    <p class="text-lg md:text-xl mb-6 text-gray-600 dark:text-gray-300">
                        نوفر أرقام وهمية لأكثر من 200 منصة رقمية مع ضمان التفعيل وبأسعار منافسة. الدفع آمن 100٪ والتسليم فوري.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#platforms" class="bg-primary hover:bg-primary/90 text-white px-6 py-3 rounded-lg font-medium transition duration-300 text-center shadow-lg hover:shadow-xl">
                            <i class="fas fa-mobile-alt ml-2"></i>تصفح الأرقام
                        </a>
                        <a href="#contact" class="bg-white dark:bg-gray-800 text-primary border border-primary hover:bg-gray-100 dark:hover:bg-gray-700 px-6 py-3 rounded-lg font-medium transition duration-300 text-center">
                            <i class="fas fa-headset ml-2"></i>تواصل معنا
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative w-full max-w-md">
                        <div class="shine rounded-xl bg-white dark:bg-gray-800 p-6 shadow-xl">
                            <div class="flex items-center justify-between mb-6">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 rounded-full bg-green-500 flex items-center justify-center text-white">
                                        <i class="fab fa-whatsapp text-xl"></i>
                                    </div>
                                    <div class="mr-3">
                                        <h3 class="font-bold">WhatsApp</h3>
                                        <p class="text-xs text-gray-500 dark:text-gray-400">أكثر من 1.4 مليون رقم</p>
                                    </div>
                                </div>
                                <span class="bg-green-100 text-green-800 dark:bg-green-800 dark:text-green-100 text-xs px-2 py-1 rounded-full">متوفر</span>
                            </div>
                            <div class="flex items-center justify-between mb-6">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 rounded-full bg-blue-500 flex items-center justify-center text-white">
                                        <i class="fab fa-telegram text-xl"></i>
                                    </div>
                                    <div class="mr-3">
                                        <h3 class="font-bold">Telegram</h3>
                                        <p class="text-xs text-gray-500 dark:text-gray-400">أكثر من 1.2 مليون رقم</p>
                                    </div>
                                </div>
                                <span class="bg-blue-100 text-blue-800 dark:bg-blue-800 dark:text-blue-100 text-xs px-2 py-1 rounded-full">متوفر</span>
                            </div>
                            <div class="flex items-center justify-between mb-6">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 rounded-full bg-pink-500 flex items-center justify-center text-white">
                                        <i class="fab fa-instagram text-xl"></i>
                                    </div>
                                    <div class="mr-3">
                                        <h3 class="font-bold">Instagram</h3>
                                        <p class="text-xs text-gray-500 dark:text-gray-400">أكثر من 2.8 مليون رقم</p>
                                    </div>
                                </div>
                                <span class="bg-pink-100 text-pink-800 dark:bg-pink-800 dark:text-pink-100 text-xs px-2 py-1 rounded-full">متوفر</span>
                            </div>
                            <div class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 rounded-full bg-red-500 flex items-center justify-center text-white">
                                        <i class="fab fa-tiktok text-xl"></i>
                                    </div>
                                    <div class="mr-3">
                                        <h3 class="font-bold">TikTok</h3>
                                        <p class="text-xs text-gray-500 dark:text-gray-400">أكثر من 1.8 مليون رقم</p>
                                    </div>
                                </div>
                                <span class="bg-red-100 text-red-800 dark:bg-red-800 dark:text-red-100 text-xs px-2 py-1 rounded-full">متوفر</span>
                            </div>
                        </div>
                        <div class="absolute -top-4 -right-4 bg-yellow-400 text-yellow-900 text-xs font-bold px-3 py-1 rounded-full shadow-lg">
                            عروض خاصة
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="py-12 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-12">كيف تعمل خدمتنا؟</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-md text-center">
                    <div class="w-16 h-16 mx-auto bg-primary/10 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-search text-primary text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">1. اختر المنصة والرقم</h3>
                    <p class="text-gray-600 dark:text-gray-400">ابحث عن المنصة التي تحتاجها واختر رقمًا من البلد المناسب لك</p>
                </div>
                <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-md text-center">
                    <div class="w-16 h-16 mx-auto bg-primary/10 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-credit-card text-primary text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">2. ادفع بأمان</h3>
                    <p class="text-gray-600 dark:text-gray-400">استخدم طريقة الدفع المفضلة لديك بكل أمان وخصوصية</p>
                </div>
                <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-md text-center">
                    <div class="w-16 h-16 mx-auto bg-primary/10 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-check-circle text-primary text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">3. استلم الرقم فورًا</h3>
                    <p class="text-gray-600 dark:text-gray-400">احصل على الرقم فورًا مع رمز التفعيل واستخدمه على الفور</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Search Section -->
    <section id="search" class="py-12">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-8">ابحث عن رقم وهمي</h2>
            <div class="max-w-4xl mx-auto bg-white dark:bg-gray-800 rounded-xl shadow-lg p-6">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-4">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">المنصة</label>
                        <select id="platformSelect" class="w-full px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base">
                            <option value="">جميع المنصات</option>
                            <option value="whatsapp">WhatsApp</option>
                            <option value="telegram">Telegram</option>
                            <option value="instagram">Instagram</option>
                            <option value="tiktok">TikTok</option>
                            <option value="facebook">Facebook</option>
                            <option value="twitter">Twitter</option>
                            <option value="netflix">Netflix</option>
                            <option value="tinder">Tinder</option>
                            <option value="snapchat">Snapchat</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">الدولة</label>
                        <select id="countrySelect" class="w-full px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base">
                            <option value="">جميع الدول</option>
                            <option value="sa">المملكة العربية السعودية</option>
                            <option value="us">الولايات المتحدة</option>
                            <option value="uk">المملكة المتحدة</option>
                            <option value="ph">الفلبين</option>
                            <option value="id">إندونيسيا</option>
                            <option value="th">تايلاند</option>
                            <option value="co">كولومبيا</option>
                            <option value="ca">كندا</option>
                            <option value="hk">هونغ كونغ</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">السعر</label>
                        <select id="priceSelect" class="w-full px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base">
                            <option value="">جميع الأسعار</option>
                            <option value="1">أقل من 10 ريال</option>
                            <option value="2">10 - 20 ريال</option>
                            <option value="3">20 - 50 ريال</option>
                            <option value="4">50 - 100 ريال</option>
                            <option value="5">أكثر من 100 ريال</option>
                        </select>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row gap-4 mt-6">
                    <input type="text" placeholder="ابحث عن رقم محدد..." class="flex-1 px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base">
                    <button id="searchButton" class="bg-primary hover:bg-primary/90 text-white px-6 py-3 rounded-lg font-medium transition duration-300 flex items-center justify-center">
                        <i class="fas fa-search ml-2"></i>
                        بحث
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Platform Section -->
    <section id="platforms" class="py-12 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-8">المنصات المتوفرة</h2>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4 md:gap-6">
                <!-- WhatsApp -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-green-500 flex items-center justify-center text-white mb-3">
                            <i class="fab fa-whatsapp text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">WhatsApp</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">1,491,514 رقم</p>
                        <button class="w-full bg-green-500 hover:bg-green-600 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Telegram -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-blue-500 flex items-center justify-center text-white mb-3">
                            <i class="fab fa-telegram-plane text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Telegram</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">1,224,038 رقم</p>
                        <button class="w-full bg-blue-500 hover:bg-blue-600 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Instagram -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-pink-600 flex items-center justify-center text-white mb-3">
                            <i class="fab fa-instagram text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Instagram</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">2,818,609 رقم</p>
                        <button class="w-full bg-pink-600 hover:bg-pink-700 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Facebook -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-blue-600 flex items-center justify-center text-white mb-3">
                            <i class="fab fa-facebook-f text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Facebook</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">2,596,356 رقم</p>
                        <button class="w-full bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- TikTok -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-black flex items-center justify-center text-white mb-3">
                            <i class="fab fa-tiktok text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">TikTok</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">1,872,909 رقم</p>
                        <button class="w-full bg-black hover:bg-gray-800 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Twitter -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-blue-400 flex items-center justify-center text-white mb-3">
                            <i class="fab fa-twitter text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Twitter</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">4,401,160 رقم</p>
                        <button class="w-full bg-blue-400 hover:bg-blue-500 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Snapchat -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-yellow-400 flex items-center justify-center text-white mb-3">
                            <i class="fab fa-snapchat-ghost text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Snapchat</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">3,086,748 رقم</p>
                        <button class="w-full bg-yellow-400 hover:bg-yellow-500 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Google -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-red-500 flex items-center justify-center text-white mb-3">
                            <i class="fab fa-google text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Google</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">997,815 رقم</p>
                        <button class="w-full bg-red-500 hover:bg-red-600 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Tinder -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-pink-500 flex items-center justify-center text-white mb-3">
                            <i class="fas fa-fire text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Tinder</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">4,178,095 رقم</p>
                        <button class="w-full bg-pink-500 hover:bg-pink-600 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
                
                <!-- Netflix -->
                <div class="platform-card bg-white dark:bg-gray-900 p-4 rounded-xl shadow-md hover:shadow-lg transition-all duration-300">
                    <div class="flex flex-col items-center">
                        <div class="w-14 h-14 rounded-full bg-red-600 flex items-center justify-center text-white mb-3">
                            <i class="fas fa-tv text-2xl"></i>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">Netflix</h3>
                        <p class="text-xs text-gray-500 dark:text-gray-400 mb-2">3,302,788 رقم</p>
                        <button class="w-full bg-red-600 hover:bg-red-700 text-white px-3 py-2 rounded-lg text-sm font-medium transition duration-300">
                            عرض الأرقام
                        </button>
                    </div>
                </div>
            </div>
            <div class="text-center mt-8">
                <button id="loadMorePlatforms" class="inline-flex items-center px-6 py-3 bg-white dark:bg-gray-900 border border-gray-300 dark:border-gray-700 rounded-lg text-primary hover:bg-gray-50 dark:hover:bg-gray-800 transition duration-300 font-medium">
                    عرض المزيد من المنصات
                    <i class="fas fa-chevron-down mr-2"></i>
                </button>
            </div>
        </div>
    </section>

    <!-- Featured Plans -->
    <section id="featured" class="py-12">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-2">المنصات الأكثر طلباً</h2>
            <p class="text-gray-600 dark:text-gray-400 text-center mb-8">اختر من بين أكثر المنصات طلباً بأسعار منافسة</p>
            
            <div class="overflow-x-auto pb-4 custom-scrollbar">
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-6 min-w-[800px]">
                    <!-- Whatsapp Featured Card -->
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 overflow-hidden">
                        <div class="p-1 bg-gradient-to-r from-green-500 to-green-600">
                            <div class="bg-white dark:bg-gray-900 p-2 text-center">
                                <div class="w-14 h-14 mx-auto rounded-full bg-green-500 flex items-center justify-center text-white">
                                    <i class="fab fa-whatsapp text-2xl"></i>
                                </div>
                                <h3 class="text-lg font-bold mt-2">WhatsApp</h3>
                            </div>
                        </div>
                        <div class="p-4">
                            <ul class="space-y-2 mb-4">
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-green-500 ml-2"></i>
                                    أرقام من 25+ دولة
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-green-500 ml-2"></i>
                                    ضمان التفعيل 100%
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-green-500 ml-2"></i>
                                    دعم فني 24/7
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-green-500 ml-2"></i>
                                    تسليم فوري
                                </li>
                            </ul>
                            <div class="text-center mt-2">
                                <div class="text-2xl font-bold text-primary mb-3">19 ريال</div>
                                <button class="w-full bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded-lg font-medium transition duration-300">
                                    شراء الآن
                                </button>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Telegram Featured Card -->
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 overflow-hidden">
                        <div class="p-1 bg-gradient-to-r from-blue-500 to-blue-600">
                            <div class="bg-white dark:bg-gray-900 p-2 text-center">
                                <div class="w-14 h-14 mx-auto rounded-full bg-blue-500 flex items-center justify-center text-white">
                                    <i class="fab fa-telegram-plane text-2xl"></i>
                                </div>
                                <h3 class="text-lg font-bold mt-2">Telegram</h3>
                            </div>
                        </div>
                        <div class="p-4">
                            <ul class="space-y-2 mb-4">
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-500 ml-2"></i>
                                    أرقام من 30+ دولة
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-500 ml-2"></i>
                                    ضمان التفعيل 100%
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-500 ml-2"></i>
                                    دعم فني 24/7
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-500 ml-2"></i>
                                    تسليم فوري
                                </li>
                            </ul>
                            <div class="text-center mt-2">
                                <div class="text-2xl font-bold text-primary mb-3">17 ريال</div>
                                <button class="w-full bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded-lg font-medium transition duration-300">
                                    شراء الآن
                                </button>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Tinder Featured Card -->
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 overflow-hidden relative">
                        <div class="absolute top-0 left-0 bg-red-500 text-white text-xs font-bold px-3 py-1 rounded-br-lg">الأكثر مبيعًا</div>
                        <div class="p-1 bg-gradient-to-r from-pink-500 to-pink-600">
                            <div class="bg-white dark:bg-gray-900 p-2 text-center">
                                <div class="w-14 h-14 mx-auto rounded-full bg-pink-500 flex items-center justify-center text-white">
                                    <i class="fas fa-fire text-2xl"></i>
                                </div>
                                <h3 class="text-lg font-bold mt-2">Tinder</h3>
                            </div>
                        </div>
                        <div class="p-4">
                            <ul class="space-y-2 mb-4">
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-pink-500 ml-2"></i>
                                    أرقام من 40+ دولة
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-pink-500 ml-2"></i>
                                    ضمان التفعيل 100%
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-pink-500 ml-2"></i>
                                    دعم فني 24/7
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-pink-500 ml-2"></i>
                                    تسليم فوري
                                </li>
                            </ul>
                            <div class="text-center mt-2">
                                <div class="text-2xl font-bold text-primary mb-3">22 ريال</div>
                                <button class="w-full bg-pink-500 hover:bg-pink-600 text-white px-4 py-2 rounded-lg font-medium transition duration-300">
                                    شراء الآن
                                </button>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Netflix Featured Card -->
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 overflow-hidden">
                        <div class="p-1 bg-gradient-to-r from-red-600 to-red-700">
                            <div class="bg-white dark:bg-gray-900 p-2 text-center">
                                <div class="w-14 h-14 mx-auto rounded-full bg-red-600 flex items-center justify-center text-white">
                                    <i class="fas fa-tv text-2xl"></i>
                                </div>
                                <h3 class="text-lg font-bold mt-2">Netflix</h3>
                            </div>
                        </div>
                        <div class="p-4">
                            <ul class="space-y-2 mb-4">
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-red-600 ml-2"></i>
                                    أرقام من 35+ دولة
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-red-600 ml-2"></i>
                                    ضمان التفعيل 100%
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-red-600 ml-2"></i>
                                    دعم فني 24/7
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-red-600 ml-2"></i>
                                    تسليم فوري
                                </li>
                            </ul>
                            <div class="text-center mt-2">
                                <div class="text-2xl font-bold text-primary mb-3">25 ريال</div>
                                <button class="w-full bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-lg font-medium transition duration-300">
                                    شراء الآن
                                </button>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Twitter Featured Card -->
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 overflow-hidden">
                        <div class="p-1 bg-gradient-to-r from-blue-400 to-blue-500">
                            <div class="bg-white dark:bg-gray-900 p-2 text-center">
                                <div class="w-14 h-14 mx-auto rounded-full bg-blue-400 flex items-center justify-center text-white">
                                    <i class="fab fa-twitter text-2xl"></i>
                                </div>
                                <h3 class="text-lg font-bold mt-2">Twitter</h3>
                            </div>
                        </div>
                        <div class="p-4">
                            <ul class="space-y-2 mb-4">
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-400 ml-2"></i>
                                    أرقام من 30+ دولة
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-400 ml-2"></i>
                                    ضمان التفعيل 100%
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-400 ml-2"></i>
                                    دعم فني 24/7
                                </li>
                                <li class="flex items-center text-sm">
                                    <i class="fas fa-check-circle text-blue-400 ml-2"></i>
                                    تسليم فوري
                                </li>
                            </ul>
                            <div class="text-center mt-2">
                                <div class="text-2xl font-bold text-primary mb-3">21 ريال</div>
                                <button class="w-full bg-blue-400 hover:bg-blue-500 text-white px-4 py-2 rounded-lg font-medium transition duration-300">
                                    شراء الآن
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Available Countries -->
    <section class="py-12 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-8">الدول المتوفرة</h2>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4">
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">المملكة العربية السعودية</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">متوفر</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">الولايات المتحدة</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">44 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">المملكة المتحدة</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">35 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">الفلبين</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">19 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">إندونيسيا</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">14 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">تايلاند</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">45 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">كولومبيا</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">38 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">كندا</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">17 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">أفغانستان</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">33 SAR</span>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-lg p-4 flex items-center justify-between shadow-md">
                    <div class="flex items-center">
                        <span class="text-sm font-medium">هونغ كونغ</span>
                    </div>
                    <span class="bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200 text-xs px-2 py-1 rounded-full">34 SAR</span>
                </div>
            </div>
            <div class="text-center mt-8">
                <button id="loadMoreCountries" class="inline-flex items-center px-6 py-3 bg-white dark:bg-gray-900 border border-gray-300 dark:border-gray-700 rounded-lg text-primary hover:bg-gray-50 dark:hover:bg-gray-800 transition duration-300 font-medium">
                    عرض المزيد من الدول
                    <i class="fas fa-chevron-down mr-2"></i>
                </button>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-12">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-8">آراء عملائنا</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="text-yellow-400 flex">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="mr-2 text-gray-600 dark:text-gray-400 text-sm">5.0</span>
                    </div>
                    <p class="text-gray-700 dark:text-gray-300 mb-4">"خدمة ممتازة وسريعة. قمت بشراء رقم لتفعيل واتساب وتمت العملية بنجاح. الدعم الفني سريع وممتاز."</p>
                    <div class="flex items-center">
                        <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="mr-3">
                            <h4 class="font-semibold">محمد عبدالله</h4>
                            <p class="text-xs text-gray-500 dark:text-gray-400">قبل 3 أيام</p>
                        </div>
                    </div>
                </div>
                <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="text-yellow-400 flex">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                        <span class="mr-2 text-gray-600 dark:text-gray-400 text-sm">4.5</span>
                    </div>
                    <p class="text-gray-700 dark:text-gray-300 mb-4">"تجربة جيدة جدًا، الأرقام فعالة وتعمل بشكل ممتاز. استخدمت الخدمة لتفعيل حسابات على عدة منصات وكانت النتيجة إيجابية."</p>
                    <div class="flex items-center">
                        <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="mr-3">
                            <h4 class="font-semibold">سارة الأحمد</h4>
                            <p class="text-xs text-gray-500 dark:text-gray-400">قبل أسبوع</p>
                        </div>
                    </div>
                </div>
                <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="text-yellow-400 flex">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="mr-2 text-gray-600 dark:text-gray-400 text-sm">5.0</span>
                    </div>
                    <p class="text-gray-700 dark:text-gray-300 mb-4">"أفضل خدمة أرقام وهمية جربتها. الأسعار ممتازة مقارنة بالمواقع الأخرى والتفعيل سريع جدًا. سأتعامل معهم مرة أخرى بالتأكيد."</p>
                    <div class="flex items-center">
                        <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="mr-3">
                            <h4 class="font-semibold">فهد العتيبي</h4>
                            <p class="text-xs text-gray-500 dark:text-gray-400">قبل شهر</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-12 bg-gradient-to-br from-primary/10 to-primary/5 dark:from-primary/5 dark:to-gray-900">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-8">تواصل معنا</h2>
            <div class="max-w-4xl mx-auto">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-lg">
                        <h3 class="text-xl font-semibold mb-4">معلومات التواصل</h3>
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary mt-1">
                                    <i class="fab fa-whatsapp"></i>
                                </div>
                                <div class="mr-4">
                                    <h4 class="font-semibold mb-1">واتساب - WhatsApp</h4>
                                    <a href="https://wa.me/967739590467" target="_blank" class="text-primary hover:underline">+967 739 590 467</a>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary mt-1">
                                    <i class="fab fa-telegram-plane"></i>
                                </div>
                                <div class="mr-4">
                                    <h4 class="font-semibold mb-1">تيليجرام - Telegram</h4>
                                    <a href="https://t.me/almaliki467" target="_blank" class="text-primary hover:underline">@almaliki467</a>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary mt-1">
                                    <i class="fab fa-instagram"></i>
                                </div>
                                <div class="mr-4">
                                    <h4 class="font-semibold mb-1">انستغرام - Instagram</h4>
                                    <a href="https://www.instagram.com/almal_ki44" target="_blank" class="text-primary hover:underline">@almal_ki44</a>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary mt-1">
                                    <i class="fab fa-snapchat-ghost"></i>
                                </div>
                                <div class="mr-4">
                                    <h4 class="font-semibold mb-1">سناب شات - Snapchat</h4>
                                    <a href="https://www.snapchat.com/add/almali_ki45" target="_blank" class="text-primary hover:underline">@almali_ki45</a>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary mt-1">
                                    <i class="fab fa-tiktok"></i>
                                </div>
                                <div class="mr-4">
                                    <h4 class="font-semibold mb-1">تيك توك - TikTok</h4>
                                    <a href="https://www.tiktok.com/@almal_ki44" target="_blank" class="text-primary hover:underline">@almal_ki44</a>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary mt-1">
                                    <i class="far fa-envelope"></i>
                                </div>
                                <div class="mr-4">
                                    <h4 class="font-semibold mb-1">البريد الإلكتروني - Email</h4>
                                    <a href="mailto:almaliki.electronic.services@gmail.com" class="text-primary hover:underline">almaliki.electronic.services@gmail.com</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow-lg">
                        <h3 class="text-xl font-semibold mb-4">أرسل رسالة</h3>
                        <form id="contactForm">
                            <div class="mb-4">
                                <label for="name" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">الاسم</label>
                                <input type="text" id="name" name="name" class="w-full px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base">
                            </div>
                            <div class="mb-4">
                                <label for="email" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">البريد الإلكتروني</label>
                                <input type="email" id="email" name="email" class="w-full px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base">
                            </div>
                            <div class="mb-4">
                                <label for="subject" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">الموضوع</label>
                                <select id="subject" name="subject" class="w-full px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base">
                                    <option value="استفسار عام">استفسار عام</option>
                                    <option value="مشكلة فنية">مشكلة فنية</option>
                                    <option value="طلب خاص">طلب خاص</option>
                                    <option value="دعم فني">دعم فني</option>
                                </select>
                            </div>
                            <div class="mb-6">
                                <label for="message" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">الرسالة</label>
                                <textarea id="message" name="message" rows="4" class="w-full px-4 py-3 rounded-lg border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-primary text-base"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-primary hover:bg-primary/90 text-white px-6 py-3 rounded-lg font-medium transition duration-300">
                                إرسال الرسالة
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-12">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-8">الأسئلة الشائعة</h2>
            <div class="max-w-3xl mx-auto">
                <div class="space-y-4">
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-md overflow-hidden">
                        <button class="faq-btn w-full px-6 py-4 text-right font-semibold flex justify-between items-center">
                            <span>ما هي الأرقام الوهمية؟</span>
                            <i class="fas fa-chevron-down text-primary transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content hidden px-6 pb-4">
                            <p class="text-gray-600 dark:text-gray-400">
                                الأرقام الوهمية هي أرقام هاتف حقيقية يمكن استخدامها لتلقي رسائل التحقق من المنصات المختلفة مثل واتساب وتيليجرام وغيرها. هذه الأرقام تكون مؤقتة وتستخدم مرة واحدة فقط لتفعيل الخدمة أو التطبيق الذي تريده.
                            </p>
                        </div>
                    </div>
                    
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-md overflow-hidden">
                        <button class="faq-btn w-full px-6 py-4 text-right font-semibold flex justify-between items-center">
                            <span>هل الأرقام آمنة للاستخدام؟</span>
                            <i class="fas fa-chevron-down text-primary transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content hidden px-6 pb-4">
                            <p class="text-gray-600 dark:text-gray-400">
                                نعم، الأرقام آمنة تمامًا للاستخدام. نحن نضمن لك أمان وخصوصية المعلومات. الأرقام التي نوفرها تستخدم لمرة واحدة فقط ولن يتم إعادة استخدامها أو بيعها لشخص آخر.
                            </p>
                        </div>
                    </div>
                    
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-md overflow-hidden">
                        <button class="faq-btn w-full px-6 py-4 text-right font-semibold flex justify-between items-center">
                            <span>كيف أستلم رمز التحقق؟</span>
                            <i class="fas fa-chevron-down text-primary transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content hidden px-6 pb-4">
                            <p class="text-gray-600 dark:text-gray-400">
                                بعد شراء الرقم، ستتمكن من رؤية رمز التحقق الذي سيصل إلى الرقم الذي اشتريته من خلال حسابك على موقعنا. ستجد رمز التحقق في قسم "الأرقام النشطة" في لوحة التحكم الخاصة بك.
                            </p>
                        </div>
                    </div>
                    
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-md overflow-hidden">
                        <button class="faq-btn w-full px-6 py-4 text-right font-semibold flex justify-between items-center">
                            <span>ما هي طرق الدفع المتاحة؟</span>
                            <i class="fas fa-chevron-down text-primary transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content hidden px-6 pb-4">
                            <p class="text-gray-600 dark:text-gray-400">
                                نحن نقبل العديد من طرق الدفع بما في ذلك: بطاقات الائتمان (فيزا، ماستركارد)، مدى، PayPal، Paysafecard، والتحويل البنكي. إذا كنت بحاجة إلى طريقة دفع أخرى، يرجى التواصل مع فريق الدعم الفني.
                            </p>
                        </div>
                    </div>
                    
                    <div class="bg-white dark:bg-gray-900 rounded-xl shadow-md overflow-hidden">
                        <button class="faq-btn w-full px-6 py-4 text-right font-semibold flex justify-between items-center">
                            <span>ماذا لو لم يصل رمز التحقق؟</span>
                            <i class="fas fa-chevron-down text-primary transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content hidden px-6 pb-4">
                            <p class="text-gray-600 dark:text-gray-400">
                                في حالة عدم وصول رمز التحقق خلال 5 دقائق، يمكنك التواصل مع فريق الدعم الفني وسنقوم بتوفير رقم بديل لك أو استرداد أموالك بالكامل حسب سياسة الضمان لدينا.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">المالكي للخدمات الالكترونية</h3>
                    <p class="text-gray-400 mb-4">
                        نوفر أرقام وهمية لأكثر من 200 منصة رقمية بأسعار تنافسية وضمان التفعيل 100%.
                    </p>
                    <div class="flex space-x-4 space-x-reverse">
                        <a href="https://wa.me/967739590467" target="_blank" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fab fa-whatsapp text-xl"></i>
                        </a>
                        <a href="https://t.me/almaliki467" target="_blank" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fab fa-telegram-plane text-xl"></i>
                        </a>
                        <a href="https://www.instagram.com/almal_ki44" target="_blank" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fab fa-instagram text-xl"></i>
                        </a>
                        <a href="https://www.snapchat.com/add/almali_ki45" target="_blank" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fab fa-snapchat-ghost text-xl"></i>
                        </a>
                        <a href="https://www.tiktok.com/@almal_ki44" target="_blank" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fab fa-tiktok text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">روابط سريعة</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">الصفحة الرئيسية</a></li>
                        <li><a href="#platforms" class="text-gray-400 hover:text-white transition-colors">المنصات</a></li>
                        <li><a href="#search" class="text-gray-400 hover:text-white transition-colors">البحث</a></li>
                        <li><a href="#featured" class="text-gray-400 hover:text-white transition-colors">الأكثر طلباً</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition-colors">تواصل معنا</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">المنصات الشائعة</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">WhatsApp</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Telegram</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Instagram</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Facebook</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">TikTok</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">العنوان</h3>
                    <p class="text-gray-400 mb-4">
                        المملكة العربية السعودية، الرياض، حي المعذر الشمالي، شارع عبدالرحمن بن سعد بن سعيد
                    </p>
                    <p class="text-gray-400">
                        الرمز: RGMA7486
                    </p>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 flex flex-col md:flex-row justify-between items-center">
                <div class="text-gray-400 text-sm mb-4 md:mb-0">
                    &copy; 2025 المالكي للخدمات الالكترونية. جميع الحقوق محفوظة.
                </div>
                <div>
                    <ul class="flex space-x-6 space-x-reverse">
                        <li><a href="#" class="text-gray-400 hover:text-white text-sm transition-colors">سياسة الخصوصية</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white text-sm transition-colors">الشروط والأحكام</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white text-sm transition-colors">سياسة الاسترجاع</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Mobile menu toggle
            const mobileMenuButton = document.getElementById('mobileMenuButton');
            const mobileMenu = document.getElementById('mobileMenu');
            
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
            
            // Close mobile menu when clicking on a link
            const mobileLinks = mobileMenu.querySelectorAll('a');
            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                });
            });
            
            // FAQ accordion
            const faqButtons = document.querySelectorAll('.faq-btn');
            faqButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const content = button.nextElementSibling;
                    const icon = button.querySelector('i');
                    
                    // Toggle current FAQ item
                    content.classList.toggle('hidden');
                    icon.classList.toggle('rotate-180');
                    
                    // Close other FAQ items
                    faqButtons.forEach(otherButton => {
                        if (otherButton !== button) {
                            const otherContent = otherButton.nextElementSibling;
                            const otherIcon = otherButton.querySelector('i');
                            
                            otherContent.classList.add('hidden');
                            otherIcon.classList.remove('rotate-180');
                        }
                    });
                });
            });
            
            // Contact form submission
            const contactForm = document.getElementById('contactForm');
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                
                // Get form values
                const name = document.getElementById('name').value;
                const email = document.getElementById('email').value;
                const subject = document.getElementById('subject').value;
                const message = document.getElementById('message').value;
                
                // Validation
                if (!name || !email || !message) {
                    alert('الرجاء ملء جميع الحقول المطلوبة');
                    return;
                }
                
                // Reset form fields
                contactForm.reset();
                
                // Show success message
                alert('تم إرسال رسالتك بنجاح! سنتواصل معك قريبًا.');
            });
            
            // Search button click handler
            const searchButton = document.getElementById('searchButton');
            searchButton.addEventListener('click', function() {
                const platform = document.getElementById('platformSelect').value;
                const country = document.getElementById('countrySelect').value;
                const price = document.getElementById('priceSelect').value;
                
                // In a real app, this would perform a search and update results
                console.log('Search params:', { platform, country, price });
            });
            
            // Simulate loading more platforms
            const loadMorePlatforms = document.getElementById('loadMorePlatforms');
            loadMorePlatforms.addEventListener('click', function() {
                // In a real app, this would load more platforms
                loadMorePlatforms.innerHTML = '<i class="fas fa-spinner fa-spin mr-2"></i> جاري التحميل...';
                
                setTimeout(() => {
                    loadMorePlatforms.innerHTML = 'تم تحميل جميع المنصات <i class="fas fa-check mr-2"></i>';
                    loadMorePlatforms.disabled = true;
                    loadMorePlatforms.classList.add('cursor-not-allowed');
                }, 1500);
            });
            
            // Simulate loading more countries
            const loadMoreCountries = document.getElementById('loadMoreCountries');
            loadMoreCountries.addEventListener('click', function() {
                // In a real app, this would load more countries
                loadMoreCountries.innerHTML = '<i class="fas fa-spinner fa-spin mr-2"></i> جاري التحميل...';
                
                setTimeout(() => {
                    loadMoreCountries.innerHTML = 'تم تحميل جميع الدول <i class="fas fa-check mr-2"></i>';
                    loadMoreCountries.disabled = true;
                    loadMoreCountries.classList.add('cursor-not-allowed');
                }, 1500);
            });
        });
    </script>
</body>
</html>
