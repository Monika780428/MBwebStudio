# MBwebStudio
Web saytların hazırlanması<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <title>Proqramlaşdırma Kursları</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Proqramlaşdırmanı Öyrən!</h1>
    <nav>
      <ul>
        <li><a href="#">Ana səhifə</a></li>
        <li><a href="#">Kurslar</a></li>
        <li><a href="#">Bloq</a></li>
        <li><a href="#">Əlaqə</a></li>
        <li><a href="#">Daxil ol</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="welcome">
      <h2>Proqramlaşdırmaya Başla!</h2>
      <p>HTML, CSS, JavaScript və daha çoxu ilə addım-addım öyrən.</p>
      <button onclick="gosterMesaj()">Qeydiyyatdan keç</button>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Proqramlaşdırma Kursları. Bütün hüquqlar qorunur.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

header {
  background: #333;
  color: white;
  padding: 15px 0;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

main {
  padding: 30px;
  text-align: center;
}

button {
  padding: 10px 20px;
  font-size: 16px;
  background-color: #007bff;
  border: none;
  color: white;
  cursor: pointer;
  border-radius: 5px;
}function gosterMesaj() {
  alert("Qeydiyyat tezliklə aktiv olacaq!");
}

