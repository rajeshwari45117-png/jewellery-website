# jewellery-website
a responsive website built using html,css and javascript .showcase different model iteams and modern designs.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Riddhi Siddhi Jewels</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #fafafa; }
    header { display: flex; justify-content: space-between; align-items: center; padding: 15px 40px; background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    header img { height: 60px; }
    nav ul { list-style: none; display: flex; gap: 20px; margin: 0; padding: 0; }
    nav a { text-decoration: none; color: #333; font-weight: 500; }
    .hero { position: relative; width: 100%; overflow: hidden; }
    .hero img { width: 100%; height: auto; }
    .collections { padding: 40px; text-align: center; }
    .collections h2 { margin-bottom: 20px; }
    .circle-cats { display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; }
    .circle-cats img { width: 100px; height: 100px; border-radius: 50%; object-fit: cover; cursor: pointer; transition: transform .3s; }
    .circle-cats img:hover { transform: scale(1.1); }
    .products { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 20px; padding: 40px; }
    .product { background: #fff; border: 1px solid #ddd; border-radius: 10px; overflow: hidden; }
    .product img { width: 100%; }
    .product .info { padding: 15px; }
    footer { background: #d8a88b; padding: 30px; display: flex; justify-content: space-between; flex-wrap: wrap; }
    footer div { margin: 10px; }
    footer a { display: block; color: #222; text-decoration: none; margin-bottom: 5px; }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <img src="C:\Users\newba\OneDrive\文件\logo.jpg" alt="Riddhi Siddhi Logo">
    <nav>
      <ul>
        <li><a href="#">Collections</a></li>
        <li><a href="#">Wedding</a></li>
        <li><a href="#">Gifting</a></li>
        <li><a href="#">Rings</a></li>
        <li><a href="#">Earrings</a></li>
      </ul>
    </nav>
  </header>

  <!-- HERO BANNER -->
  <section class="hero">
    <img src="C:\Users\newba\OneDrive\文件\rbaner.jpg"w-50 alt="Hero Jewelry Banner">
  </section>

  <!-- COLLECTIONS -->
  <section class="collections">
    <h2>Discover Our Collections</h2>
    <div class="circle-cats">
      <img src="C:\Users\newba\OneDrive\文件\earing.jpg" alt="Earrings">
      <img src="C:\Users\newba\OneDrive\文件\shin.jpg" alt="Chain Pendant">
      <img src="C:\Users\newba\OneDrive\文件\bag.jpg" alt="Handbags">
      <img src="C:\Users\newba\OneDrive\文件\ban1.jpg" alt="Bangles">
      <img src="C:\Users\newba\OneDrive\文件\rin.jpg" alt="Rings">
      <img src="C:\Users\newba\OneDrive\文件\king.jpg" alt="Mangalsutra">
    </div>
  </section>

  <!-- PRODUCT LISTING -->
  <section class="products">
    <div class="product">
      <img src="C:\Users\newba\OneDrive\文件\rajii.jpg" alt="Necklace">
      <div class="info">
        <h4>Silver Plated AD Set</h4>
        <p>₹233 <del>₹424</del> (45% OFF)</p>
      </div>
    </div>
    <div class="product">
      <img src="C:\Users\newba\OneDrive\文件\post.jpg" alt="Necklace">
      <div class="info">
        <h4>Rose Gold Polish</h4>
        <p>₹232 <del>₹464</del> (50% OFF)</p>
      </div>
    </div>
    <div class="product">
      <img src="C:\Users\newba\OneDrive\文件\nec.jpg" alt="Necklace">
      <div class="info">
        <h4>Kundan Necklace</h4>
        <p>₹205 <del>₹324</del> (36% OFF)</p>
      </div>
    </div>
  </section>
  <!-- Trending Looks -->
<div class="container my-5">
  <h2 class="mb-3">Trending Looks</h2>
  <div class="d-flex overflow-auto trending">
    <video src="C:\Users\newba\OneDrive\文件\vedio3.mp4" autoplay muted loop></video>
    <br>
    <video src="C:\Users\newba\OneDrive\文件\vedio5.mp4" autoplay muted loop></video>
    <video src="look3.mp4" autoplay muted loop></video>
  </div>
</div>


  <!-- FOOTER -->
  <footer>
    <div>
      <h4>Associate With Us</h4>
      <a href="#">Contact Us</a>
      <a href="#">Blog</a>
      <a href="#">About</a>
    </div>
    <div>
      <h4>Policy Matters</h4>
      <a href="#">Privacy</a>
      <a href="#">Terms</a>
      <a href="#">Shipping</a>
      <a href="#">Return & Exchange</a>
    </div>
    <div>
      <h4>Stay Connected</h4>
      <input type="email" placeholder="Enter your email">
      <button>Subscribe</button>
    </div>
  </footer>

</body>
</html>