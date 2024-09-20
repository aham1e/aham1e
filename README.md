<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة تسجيل الدخول</title>
    <link rel="stylesheet" href="C:/Users/mo/Desktop/ConnectHub/log/styles_log.css">
    <script>
        function handleLogin(event) {
            event.preventDefault(); // منع الإرسال الافتراضي
            // يمكنك إضافة منطق تسجيل الدخول هنا
            alert("تم تسجيل الدخول بنجاح!");
            window.location.href = 'C:/Users/mo/Desktop/ConnectHub/index.html'; // الانتقال إلى صفحة المسار المحدد
        }

        function redirectToRegister() {
            window.location.href = 'C:/Users/mo/Desktop/ConnectHub/log/register.html'; // الانتقال إلى صفحة التسجيل
        }
    </script>
</head>
<body>
    <div class="container">ConnectHub
        <h1>تسجيل الدخول</h1>
        <form action="C:/Users/mo/Desktop/ConnectHub/index.html" method="POST">
            <div class="input-group">
                <input type="email" name="email" placeholder="البريد الإلكتروني" required>
            </div>
            <div class="input-group">
                <input type="password" name="password" placeholder="كلمة السر" required>
            </div>
            <button type="submit">تسجيل الدخول</button>
            <button type="button" class="register" onclick="redirectToRegister()">إنشاء حساب</button>
        </form>
        
    </div>
</body>
</html>
