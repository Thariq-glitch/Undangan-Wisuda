<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Undangan Wisuda Thariq Maulana Ray</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Amiri:wght@700&display=swap" rel="stylesheet">

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family:'Poppins', sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b, #334155);
      min-height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      padding:30px;
      color:white;
    }

    .container{
      width:100%;
      max-width:850px;
    }

    .card{
      background:rgba(255,255,255,0.08);
      border:1px solid rgba(255,255,255,0.15);
      backdrop-filter: blur(10px);
      border-radius:30px;
      padding:50px;
      box-shadow:0 10px 40px rgba(0,0,0,0.4);
      position:relative;
      overflow:hidden;
    }

    .card::before{
      content:"";
      position:absolute;
      width:250px;
      height:250px;
      background:rgba(255,255,255,0.05);
      border-radius:50%;
      top:-100px;
      right:-100px;
    }

    .card::after{
      content:"";
      position:absolute;
      width:200px;
      height:200px;
      background:rgba(255,255,255,0.04);
      border-radius:50%;
      bottom:-100px;
      left:-100px;
    }

    .arabic{
      font-family:'Amiri', serif;
      font-size:38px;
      text-align:center;
      margin-bottom:25px;
      line-height:1.8;
      color:#ffffff;
      position:relative;
      z-index:2;
    }

    .title{
      text-align:center;
      margin-bottom:35px;
      position:relative;
      z-index:2;
    }

    .title h1{
      font-size:45px;
      margin-bottom:10px;
    }

    .title p{
      color:#cbd5e1;
      font-size:18px;
    }

    .content{
      position:relative;
      z-index:2;
    }

    .content p{
      font-size:16px;
      line-height:1.9;
      color:#e2e8f0;
      margin-bottom:20px;
      text-align:justify;
    }

    .event-box{
      background:rgba(255,255,255,0.07);
      border:1px solid rgba(255,255,255,0.15);
      border-radius:25px;
      padding:30px;
      margin:35px 0;
    }

    .event-box h2{
      text-align:center;
      margin-bottom:25px;
      font-size:30px;
    }

    .info{
      display:flex;
      align-items:center;
      gap:15px;
      margin-bottom:18px;
      font-size:18px;
    }

    .icon{
      font-size:24px;
    }

    .quote{
      text-align:center;
      font-style:italic;
      color:#cbd5e1;
      line-height:1.8;
      margin:30px 0;
    }

    .footer{
      text-align:center;
      margin-top:40px;
    }

    .footer p{
      text-align:center;
      margin-bottom:10px;
    }

    .footer h3{
      font-size:30px;
      margin-top:10px;
    }

    .btn{
      display:inline-block;
      margin-top:25px;
      padding:14px 32px;
      border-radius:50px;
      text-decoration:none;
      background:white;
      color:#0f172a;
      font-weight:600;
      transition:0.3s;
    }

    .btn:hover{
      transform:translateY(-3px);
      background:#e2e8f0;
    }

    @media(max-width:768px){

      body{
        padding:20px;
      }

      .card{
        padding:35px 25px;
      }

      .arabic{
        font-size:28px;
      }

      .title h1{
        font-size:32px;
      }

      .title p{
        font-size:16px;
      }

      .content p{
        font-size:15px;
      }

      .event-box h2{
        font-size:24px;
      }

      .info{
        font-size:15px;
      }

    }

  </style>
</head>

<body>

  <div class="container">

    <div class="card">

      <div class="arabic">
        بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيمِ
      </div>

      <div class="title">
        <h1>Undangan Wisuda</h1>
        <p>Thariq Maulana Ray</p>
      </div>

      <div class="content">

        <p>
          Assalamu’alaikum warahmatullahi wabarakatuh
        </p>

        <p>
          Dengan penuh rasa syukur ke hadirat Allah SWT atas segala rahmat,
          nikmat, dan karunia-Nya, saya telah menyelesaikan amanah dalam
          menempuh pendidikan di bangku perkuliahan.
        </p>

        <p>
          Maka dengan segala kerendahan hati, saya mengundang
          Bapak/Ibu/Saudara/i untuk hadir serta memberikan doa restu
          pada momen bahagia wisuda saya yang insyaAllah akan
          dilaksanakan pada:
        </p>

        <div class="event-box">

          <h2>🎓 Acara Wisuda</h2>

          <div class="info">
            <div class="icon">📅</div>
            <div>Rabu, 19 Mei 2026</div>
          </div>

          <div class="info">
            <div class="icon">📍</div>
            <div>Universitas Putra Indonesia “YPTK” Padang</div>
          </div>

        </div>

        <div class="quote">
          “Kehadiran dan doa restu dari Bapak/Ibu/Saudara/i akan menjadi
          kebahagiaan serta keberkahan tersendiri bagi saya.”
        </div>

        <p>
          Semoga langkah ini menjadi awal yang baik dalam menapaki masa depan,
          serta ilmu yang diperoleh dapat memberikan manfaat dan menjadi amal jariyah.
        </p>

        <div class="footer">

          <p>Jazakumullahu Khairan Katsiran</p>

          <h3>Thariq Maulana Ray</h3>

          <a href="#" class="btn">
            Wassalamu’alaikum Wr. Wb.
          </a>

        </div>

      </div>

    </div>

  </div>

</body>
</html>
