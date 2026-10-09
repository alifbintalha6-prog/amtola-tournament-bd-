<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Amtola Tournament BD 1</title>
<style>
*{box-sizing:border-box}
body{
  margin:0;
  background:#090909;
  color:white;
  font-family:Arial,sans-serif
}
header{
  background:#151515;
  padding:20px;
  text-align:center;
  border-bottom:2px solid #d4af37
}
h1{color:#d4af37;font-size:24px}
.tagline{color:#ccc}
.container{padding:16px;max-width:700px;margin:auto}
.card{
  background:#181818;
  border:1px solid #393020;
  border-radius:12px;
  padding:16px;
  margin:16px 0
}
h2{color:#e0bd4e}
button{
  background:#d4af37;
  color:#111;
  border:0;
  padding:12px 18px;
  border-radius:8px;
  font-weight:bold;
  cursor:pointer
}
input,select{
  width:100%;
  padding:12px;
  margin:8px 0 14px;
  background:#252525;
  color:white;
  border:1px solid #555;
  border-radius:7px
}
label{color:#ddd}
.notice{color:#ccc;line-height:1.6}
footer{text-align:center;padding:25px;color:#aaa}
</style>
</head>
<body>
<header>
  <h1>🏆 AMTOLA TOURNAMENT BD 1</h1>
  <p class="tagline">Free Fire Tournament Platform</p>
</header>

<main class="container">
  <section class="card">
    <h2>🎮 স্বাগতম!</h2>
    <p>তোমার পছন্দের Free Fire টুর্নামেন্টে অংশগ্রহণের জন্য প্রস্তুত হও।</p>
    <p class="notice">এটি ওয়েবসাইটের প্রাথমিক Demo। এখনো কোনো বাস্তব টুর্নামেন্ট বা পেমেন্ট চালু নেই।</p>
  </section>

  <section class="card">
    <h2>👤 Player Registration</h2>
    <form id="playerForm">
      <label>Player Name</label>
      <input id="playerName" required maxlength="50" placeholder="তোমার নাম">

      <label>Free Fire UID</label>
      <input id="playerUid" required maxlength="30" placeholder="তোমার গেম UID">

      <button type="submit">Register (Demo)</button>
    </form>
    <p id="message" class="notice"></p>
  </section>

  <section class="card">
    <h2>🏆 Tournaments</h2>
    <p>এখনো কোনো টুর্নামেন্ট প্রকাশ করা হয়নি।</p>
    <p class="notice">টুর্নামেন্ট চালু হলে এখানে নাম, Entry Fee ও Prize Pool দেখা যাবে।</p>
  </section>

  <section class="card">
    <h2>💳 Payment Information</h2>
    <p>bKash · Nagad · Rocket</p>
    <p class="notice">বাস্তব পেমেন্ট এখনো চালু হয়নি। Admin-এর যাচাইকৃত নির্দেশনা প্রকাশের আগে কোনো টাকা পাঠাবে না।</p>
  </section>
</main>

<footer>© 2026 Amtola Tournament BD 1</footer>

<script>
document.getElementById("playerForm").addEventListener("submit",function(e){
  e.preventDefault();
  document.getElementById("message").textContent =
    "Demo সফল! তথ্য শুধু এই পেজে পরীক্ষা করা হয়েছে; কোথাও সংরক্ষণ করা হয়নি।";
});
</script>
</body>
</html># amtola-tournament-bd-
 Free Fire Tournament Management App 
