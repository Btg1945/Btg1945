 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>EKI</title>

<style>
@import url('http://fonts.cdnfonts.com/css/alphacentauri');

*{    
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  }

  body{
    background-color: black;
    }

  .background {
    background-image: url("background.jpg");
    height: 100vh;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    justify-content: center;
    align-items: center;
    }

  .about {
    color: white;
    position: absolute;
    text-align: center;
    top: 33%;
    }

  .cardA {
    width: 305px;
    height: 505px;
    background-color: rgba(230, 230, 250, 0.2);
    border: 3px solid rgba(30, 144, 255, 0.6);
    border-radius: 40px;
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);
    backdrop-filter: blur(5px);
    text-align: center;
    margin: 0 auto;
    margin-top: 5vh;
    }

  .logo{
    width: 250px;
    height: 250px;
    margin: 0 auto;
    position: absolute;
    bottom: 57%;
    left: 50%;
    transform: translateX(-50%);
    }

    .isi_about{
      text-align: justify;
      text-justify: newspaper;
      margin: 11px;
      }

    .Welcome h1{
      color: #00d2ff;
      font-family: 'AlphaCentauri', sans-serif;
      font-size: 40px;
      }

      .project {
            color: white;
            text-align: center;
          }

      .card1 {
            margin: 0 auto;
            z-index: 1;
          }

      .card-text {
            text-align: justify;
            text-justify: newspaper;
          }

      h3,h1{
            color: white;
          }


      .card-title {
            color: #69696A;
          }

      .wrapper {
            padding-left: 20px;
            border-radius: 7px;
            margin-left: 10px;
          }

      .buttonQR {
            margin-top: 9px;
            border-radius: 5px;
            border: solid 1px;
            padding: 5px;
          }

      .input {
            padding: 3px;
            border-radius: 5px;
          }

      .qr-code {
            margin-top: 12px;
            color: blue;
          }

      .contact {
            text-align: center;
          } 

      .button{
            position: relative;
            width: 70px;
            height: 30px;
            font-size: 20px;
            background-color: deepskyblue;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: width .5s, border-radius 
            .5s;
          }

      .button *{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            transition: opacity .25s;
          }

      .terkirim{
            opacity: 0;
            color: white;
          }

      .button:focus{
            width: 130px;
            border-radius: 5px;
            background-color: greenyellow;
          }

      .button:focus .send {
            opacity: 0;
          }

      .button:focus .terkirim {
            opacity: 1;
            transition-delay: .5s;
          }

      form {
            display: flex;
            flex-direction: column;
            margin: 20px auto;
            width: 16rem;
            text-align: center;
            align-content: center;
            gap: 1rem;
          }

      input {
            padding: 1.4rem;
            border: 2px solid #3548F4;
            color: #11DE40;
            background-color: rgba(50, 67, 223, 1);
            border-radius: 10px;
            border-color: white;

          }

      :placeholder-shown{
            color: red;
          }

      ::placeholder{
            color: #CDDDFC;
          }

      .navbar-toggler {
            color: orange;
            box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
          }

          .navbar-toggler-icon {
            font-size: 20px;
          }

      .icon {
            font-size: 30px;
            display: inline-flex;
          }

      i {
            padding: 10px;
          }


.animate-text{
  text-align: center;
  margin: 0 ;
  overflow: hidden;
}

.animate-text,span {
  font-size: 40px;
  color: #ff2c45;
  font-weight: 700;
  display: inline-block;
  line-height: 46px;
  display: none;
}

.animate-text, span.text-in {
  display: block;
  animation: textIn .5s ease;
}

.animate-text, span.text-out {
  animation: textOut .5s ease;
}

@keyframes textIn {
  0% {
    transform: translateY(100%);
  }

  100% {
    transform: translateY(0%);
  }
}

@keyframes textOut {
  0% {
    transform: translateY(0%);
  }

  100% {
    transform: translateY(-100%);

  }
}
</style>
<!-- HTML -->


  <!-- Custom Styles -->
   <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"></script>
 <link href="http://fonts.cdnfonts.com/css/alphacentauri" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
 <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" rel="stylesheet">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
<link rel="stylesheet" href="style.css">

</head>
<body>
<nav class="navbar fixed-top" style="background-color: transparent;">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About Me</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">My Project</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Game</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

  <div class="background">
    <div class="Welcome">
      <br>
  <h1><b>WELCOME</b></h1>
     <p class="animate-text">
       <span>Hello</span>
       <span>I'm Eki</span>
       <span>Bye</span>
     </p>
    </div>
     </div>


  <div class="cardA">
    <img class="logo" src="logo.png">
      <div class="about">
      <h1><b>ABOUT ME</b></h1>

    <p class="isi_about">Perkenalkan nama saya Eki Zulfar Rachman atau biasa di panggil eki. Saya adalah seorang pelajar SMK kelas X jurusan TKJ. Saya lahir di Bekasi, pada 5 Desember 2006. Hobi saya bermain sepak bola,bermain game dan ngoding. Cita-cita saya adalah ingin menjadi seorang progammer Dan masi banyak hal lain yang belum saya raih. Mungkin singkat itu saja tentang diri saya, Terima kasih.
    </p>
  </div>
  </div>
  <br><br><br>
  <div class="project">
  <h1><b><u>MY PROJECT</u></b></h1>
  </div>


  <br>
  <div class="card1" style="width: 18rem;">
    <img src="background.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Barisan Aritmatika</h5>
      <p class="card-text">project sederhana membuat program Barisan Aritmatika jika diketahui hanya dua suku dengan menggunakan python</p>
      <a href="#" class="btn btn-primary">Lihat</a>
    </div>
  </div>

  <br>
   <div class="card1" style="width: 18rem;">
    <img src="background.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Barisan Geometri</h5>
      <p class="card-text">project sederhana membuat program Barisan Geometri jika diketahui hanya dua suku dengan menggunakan python
       <hr>Note : belum tau 100℅ berhasil atau engga
      </p>
      <a href="#" class="btn btn-primary">Lihat</a>
    </div>
   </div>
  <br><br>

  <div class="wrapper">
    <header>
      <h3>QR Code Generator</h3>
      <p>Paste a url or enter text to create QR code</p>
    </header>
    <div class="form">
      <input class="input" type="text" spellcheck="false" placeholder="Enter text or url">
      <button class="buttonQR">Generate QR Code</button>
    </div>
    <div class="qr-code">
      <img src="" alt="qr-code">
    </div>
  </div>
  <br><br>

<div class="contact">
<h1>Contact Me</h1>
  <form action="https://formsubmit.co/0d2c889ccd1c1f81a02447f9d640256f" method="POST">
    <input type="text" name="name" required placeholder="Name">
    <input type="email" name="email" required placeholder="emailasal@gmail.com">
    <input type="text" name="message" required placeholder="pesan">

     <button type="submit" class="button" >
       <span class="send">Kirim</span>
       <div class="terkirim">Terkirim</div>
     </button>

     <input type="hidden" name="_captcha" value="false">
     <input type="hidden" name="_template" value="table">
  </form>
</div>

  <center>
    <div class="icon">
      <a href="https://instagram.com/ekizr_">
        <i class="fab fa-instagram">
        </i>
      </a>
      <a href="https://youtube.com/channel/UChlS0DjFMmDi99OKpsHWRtQ">
        <i class="fab fa-youtube">
        </i>
      </a>
      <a href="https://www.tiktok.com/@luarnalarcoy?_t=8VVG9LxHiZF&_r=1">
        <i class="fab fa-tiktok"></i>
    </div>
  </center>


    <!-- Project -->
  <script src="main.js"></script>
</body>
</html>