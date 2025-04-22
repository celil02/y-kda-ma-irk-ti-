<!DOCTYPE html>
<html lang="az">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Yükdaşıma Şirkəti</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Bölməsi -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Ana Səhifə</a></li>
                <li><a href="#about">Haqqımızda</a></li>
                <li><a href="#services">Xidmətlər</a></li>
                <li><a href="#contact">Əlaqə</a></li>
            </ul>
        </nav>
    </header>

    <!-- Ana Səhifə Bölməsi -->
    <section id="home" class="hero">
        <h1>Yükdaşıma Şirkətinə Xoş Gəlmisiniz!</h1>
        <p>Biz, yük daşımacılığı sahəsində etibarlı və sürətli xidmətlər təqdim edirik.</p>
    </section>

    <!-- Haqqımızda Bölməsi -->
    <section id="about">
        <h2>Haqqımızda</h2>
        <p>Yükdaşıma şirkətimiz 20 ildən artıqdır ki, Azərbaycanın müxtəlif bölgələrinə sürətli və təhlükəsiz yük daşıma xidmətləri göstərir. Müasir nəqliyyat vasitələrimiz və təcrübəli komandamız ilə müştərilərimizin ehtiyaclarına uyğun həllər təqdim edirik.</p>
    </section>

    <!-- Xidmətlər Bölməsi -->
    <section id="services">
        <h2>Xidmətlərimiz</h2>
        <ul>
            <li>Şəhər daxili yük daşıma</li>
            <li>Beynəlxalq yük daşıma</li>
            <li>Daşınma və yükləmə xidmətləri</li>
            <li>Yük sığortası</li>
        </ul>
    </section>

    <!-- Əlaqə Bölməsi -->
    <section id="contact">
        <h2>Əlaqə</h2>
        <p>Bizimlə əlaqə saxlamaq üçün aşağıdakı formu doldurun:</p>
        <form action="submit_form.php" method="POST">
            <label for="name">Adınız:</label>
            <input type="text" id="name" name="name" required><br>

            <label for="email">E-poçt:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="message">Mesaj:</label>
            <textarea id="message" name="message" required></textarea


