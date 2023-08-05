<template>
    <!-- partial:index.partial.html -->
    <!-- Start Landing Page -->
    <div class="landing-page">
        <header>
            <div class="container">
                <div href="http://127.0.0.1:8000/" class="logo text-center ">Welcom To Yosif<br><b>Website</b></div>
                
                    <ul class="links">
                        <li class="nav-item font-bold">
                            <a class="nav-link m-2 text-dark" href="https://yosif999.000webhostapp.com/welcome.blade.php">Home</a>
                        </li>
                        <li class="nav-item font-bold">
                            <a class="nav-link m-2 text-dark" href="https://yosif999.000webhostapp.com/singup.blade.php">Singup</a>
                        </li>
                        <li class="nav-item font-bold">
                            <a class="nav-link m-2 text-dark" href="https://yosif999.000webhostapp.com/about.blade.php">من انا ؟</a>
                        </li>

                        <li class=" font-bold">Get Started</li>

                    </ul>
            </div>
        </header>
        <div class="content">
            <div class="container  font-bold">
                <div class="info  font-bold">

                    
                    <h1 class=" text-dark  font-bold">Looking For Inspiration</h1>
                    <p class=" text-dark font-bold">The company itself is a very successful company. He hates nothing to repel, they know nothing</p><hr>
                        <img src="https://i.pinimg.com/564x/9d/ee/0b/9dee0b0b54657e6c1963616045fc59ba.jpg" height="250" >
                </div>
                
                <div class="image">
                    <img src="https://i.postimg.cc/65QxYYzh/001234.png">
                </div>
            </div>
        </div>
    </div>
    <!-- End Landing Page -->
    <!-- partial -->







    <div class="loader"></div>
    
        <h2 class="text-center font-bold">لنبقئ عل تواصل</h2><br>
        <h5 class="text-center font-bold">اشترك في القائمه البريديه المجانيه واحصل علئ اخر التحديثات</h5>
        <div class="container font-bold">
        <form method="post">
            <label for="email">Email Address :</label>
            <input class="form-control font-bold " type="email"  name="email" placeholder="example.com" required>
            <p class="m-1">

بالنقر فوق مربع الاختيار هذا ، فإنك توافق على تلقي رسائل بريد إلكتروني من هذا الموقع</p><input class="form-check m-2" type="checkbox">
            <button class="btn btn-primary  font-bold" type="submit">إرسال</button>
        </form>
  </div>














        <!-- CSS -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css">




      
      
</template>



    <style>
    a {
        font-size: x-large;
    }
    </style>

    <style>
    .loader {
        position: fixed;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        background: #333333;
        transition: opacity 1s, visibility 1s;
    }

    .loader--hidden {
        opacity: 0;
        visibility: hidden;
    }

    .loader::after {
        content: "";
        width: 75px;
        height: 75px;
        border: 3px solid #dddddd;
        border-top-color: rgb(0, 0, 255);
        border-radius: 50%;
        animation: loading 1.5s ease infinite;
    }

    @keyframes loading {
        from {
            transform: rotate(0turn);
        }

        to {
            transform: rotate(1turn);
        }
    }
    </style>
    <style>
    * {
        margin: 0;
        padding: 0;
    }

    .title {
        font-size: 30px;
    }

    ul {
        position: relative;
        right: 20px;
    }

    a {
        font-size: 18px;
    }

    .reaload {
        padding: 10px;
        margin-top: 10px;
        outline: none;
        border: none;
        color: white;
        border-radius: 50px;
        cursor: pointer;
    }

    nav {
        font-size: 20px;
    }
    </style>
    <style>
    /* Start Global Rules */
    * {
        box-sizing: border-box;
    }

    body {
        font-family: 'Open Sans', sans-serif;
    }

    a {
        text-decoration: none;
    }

    ul {
        list-style: none;
        padding: 0;
        margin: 0;
    }

    .container {
        padding-left: 15px;
        padding-right: 15px;
        margin-left: auto;
        margin-right: auto;
    }

    /* Small */
    @media (min-width: 768px) {
        .container {
            width: 750px;
        }
    }

    /* Medium */
    @media (min-width: 992px) {
        .container {
            width: 970px;
        }
    }

    /* Large */
    @media (min-width: 1200px) {
        .container {
            width: 1170px;
        }
    }

    /* End Global Rules */

    /* Start Landing Page */
    .landing-page header {
        min-height: 80px;
        display: flex;
    }

    @media (max-width: 767px) {
        .landing-page header {
            min-height: auto;
            display: initial;
        }
    }

    .landing-page header .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    @media (max-width: 767px) {
        .landing-page header .container {
            flex-direction: column;
            justify-content: center;
        }
    }

    .landing-page header .logo {
        color: #5d5d5d;
        font-style: italic;
        text-transform: uppercase;
        font-size: 20px;
    }

    @media (max-width: 767px) {
        .landing-page header .logo {
            margin-top: 20px;
            margin-bottom: 20px;
        }
    }

    .landing-page header .links {
        display: flex;
        align-items: center;
    }

    @media (max-width: 767px) {
        .landing-page header .links {
            text-align: center;
            gap: 10px;
        }
    }

    .landing-page header .links li {
        margin-left: 30px;
        color: #5d5d5d;
        cursor: pointer;
        transition: .3s;
    }

    @media (max-width: 767px) {
        .landing-page header .links li {
            margin-left: auto;
        }
    }

    .landing-page header .links li:last-child {
        border-radius: 20px;
        padding: 10px 20px;
        color: #FFF;
        background-color: #6c63ff;
    }

    .landing-page header .links li:not(:last-child):hover {
        color: #6c63ff;
    }

    .landing-page .content .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 140px;
        min-height: calc(100vh - 80px);
    }

    @media (max-width: 767px) {
        .landing-page .content .container {
            gap: 0;
            min-height: calc(100vh - 101px);
            justify-content: center;
            flex-direction: column-reverse;
        }
    }

    @media (max-width: 767px) {
        .landing-page .content .info {
            text-align: center;
            margin-bottom: 15px
        }
    }

    .landing-page .content .info h1 {
        color: #5d5d5d;
        font-size: 44px;
    }

    .landing-page .content .info p {
        margin: 0;
        line-height: 1.6;
        font-size: 15px;
        color: #5d5d5d;
    }

    .landing-page .content .info button {
        border: 0;
        border-radius: 20px;
        padding: 12px 30px;
        margin-top: 30px;
        cursor: pointer;
        color: #FFF;
        background-color: #6c63ff;
    }

    .landing-page .content .image img {
        max-width: 100%;
    }

    .center {
        position: absolute;
        top: 120%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 400px;
        padding: 20px;

    }
    button.submitButton {
        width: 77%;
        height: 40px;
        outline: none;
        color: #ffffff;
        font-weight: bold;
        border-radius: 30px;
        background: black;
        cursor: pointer;
        transition: all 0.3s;
    }

    button.submitButton:hover {
        opacity: 0.7;
    }
    .container {
    text-align: center;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;

}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

label, input {
    margin: 10px 0;
}

button {
    padding: 10px 20px;
    background-color: #007BFF;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}
    


    </style>



            <!-- JavaScript -->
        <script>
        window.addEventListener("load", () => {
            const loader = document.querySelector(".loader");

            loader.classList.add("loader--hidden");

            loader.addEventListener("transitionend", () => {
                document.body.removeChild(loader);
            });
        });
        </script>



