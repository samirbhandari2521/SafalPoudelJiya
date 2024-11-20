<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
   * {
    margin: 0px;
    padding: 0px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border: border-box;
}

.navbar {
    min-height: 60px;
    background-color: #0F1111;
    display: flex;
    align-items: center;
    justify-content: space-evenly;


}

.nav-logo {
    height: 50px;
    width: 113px;
    margin: 0px 10px;
}

.logo {
    height: 50px;
    width: 113px;
    color: aliceblue;
    /* background-color: aqua; */
    background-image: url('https://wallpapers.com/images/hd/amazon-logo-black-background-xb9pdemosnjfz9ej.jpg');
    background-size: contain;

    margin: 1px 1px;
    padding: 1px 8px 0px 6px;
    background-repeat: no-repeat;
    box-sizing: border-box;
}

.border {
    border: 2px solid transparent;
}

.border:hover {
    border: 2px solid white;
    cursor: pointer;
}

/* box 2 */
.nav-address {
    color: white;
    margin: 2px 0px 2px 15px;
}

.add-first {
    font-size: 0.85rem;
    color: rgb(219, 217, 217);
}

.add-icon {
    margin: 5px 2px 5px 0px;
}

/* box 3 */
.nav-search {
    display: flex;
    align-items: center;
    margin: 0px 10px;
    padding: 10px 4px 10px 4px;
    height: 40px;
width: 40%;


}

.nav-text {
    margin: 0;
    width: 795px;
    width:100% ;
    height: 40px;
    box-sizing: border-box;
}

.select-btn {

    padding: 2px 5px;
}

.ser {
    color: white;
    background-color: rgb(161, 11, 116);
    height: 40px;
    width: 40px;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 0px 5px 5px 0px;
}

/* box4 */
.sign-in-nav {
    color: white;
    max-width: 131px;
    font-size: 13px;
}

.s-part {
    display: inline;
}

.retuen {
    font-size: 12px;
    color: white;
}

.order {
    font-size: 14px;
    color: white;
}

.return-order {
    margin: 0px 0px 0px 2px;
    padding: 0px 9px 10px;
}

.cart {
    margin: 0px 1px 0px 2px;
    padding: 0px 9px 10px;
    size: 84px 50px;
    box-sizing: border-box;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 13px;
}

/* lowerhead */
.lower-head {
    display: flex;
    background-color: #3e3f3f;
    list-style: none;
}

.lower-items {
    padding: 5px;
    margin: 5px;
    color: white;
}

/* section */
.a-section {
    box-sizing: border-box;

    width: 100%;
    min-height: 600px;
    background-image:         linear-gradient(to bottom, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0)),url('https://m.media-amazon.com/images/I/61zAjw4bqPL._SX3000_.jpg');
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    flex-wrap: wrap;
}

.box-m {
    border-radius: 10px;
    width: 23%;
    overflow: hidden;
    margin: 0.4rem;
    height: 400px;
    display: flex;
    align-items: center;
    
    flex-direction: column;
    justify-content: space-evenly;
   transition: all ease-in-out .3s;
    background-color: rgb(255, 255, 255);

}
.box-m:hover{
    width: 26%;
    /* height: 410px; */
}

.box-m img {
    width: 80%;
   height: 70%;
}
.box-det{
    font-size: 21px;
}
.see-more{
    color: rgb(133, 133, 203);
}
.pict{
    height: 15rem;
    background-image: url('https://m.media-amazon.com/images/I/71fgNuf3lIL._SX3000_.jpg');
    background-size: cover;
}
/* footer */
.sign-in-box{
    background-color: #dfe6e6f4;
    display: flex;
  justify-content:center;
    flex-direction: column;
    align-items:center;
    min-height: 200px;
}
.sign-in-box p{
margin: 2px;
padding: 2px;
}
.sign-btn{
    width: 230px;
    background-color: rgb(243, 247, 138);
    border: 1px solid orange;
    font-size: 19px;
    padding: 5px;
    border-radius: 4px;
}
.back-top{
    background-color:#3b495b ;
    text-align: center;
    padding: 15px;
    color: white;
    cursor: pointer;
    
}
a{
    text-decoration: none;
}
.back-top:hover{
    background-color:#556a82 ;

}
.f-text ul{
    list-style: none;
}
.f-text{
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background-color: #232f3e;
    color: white;
    padding: 55px;
}
.copyright{
    background-color: #232f3e;
    color: white;
    text-align: center;
    padding: 20px;
}
.main-img{
    transition: background-image 0.5s ease-in-out;
}
  </style>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
  <!-- <link rel="stylesheet" href="amzo.css"> -->
</head>

<body>
  <header>
    <div id="mn" class="navbar">
      <div dclass="nav-logo border">
        <div class="logo">

        </div>
      </div>
      <div class="border nav-address">
        <p class="add-first">Deliver to</p>
        <div class="add-icon">
          <i class="fa-solid fa-location-dot"></i>
          <p class="add-second">Nepal</p>
        </div>
      </div>
      <div class="nav-search">
        <select style="height: 40px;border-radius: 5px 0px 0px 5px;" class="select-btn" name="" id="">
          <option value="">All</option>
          <option value="">Hello</option>
          <option value="">Hello</option>
          <option value="">Hello</option>
          <option value="">Hello</option>
          <option value="">Hello</option>
        </select>
        <input type="text" onfocus="f()" placeholder="Search Amazon" class="nav-text">
        <img src="" alt="" class="src">
        <i class="fas fa-search ser"></i>
      </div>
      <div class="border sign-in-nav">
        <p class="f-part">Hello,sign in</p>
        <p class="s-part">Acoounts and Lists</p><span class="arrow">&#8595;</span>
      </div>
      <div class="border return-order">
        <p class="retuen">Returns</p>
        <p class="order">&orders</p>
      </div>
      <div class="cart">
        <i class="fa fa-shopping-cart" style="font-size:24px;color:white"></i>
        <span style="color:white">Cart</span>
      </div>
    </div>
    <div class="lower-nav">
      <ul class="lower-head">
        <li class="border lower-items">
          <span style="color:white;font-size: 14px;">&#9776;</span>
          <span style="font-size: 14px;">All</span>
        </li>
        <li class="border lower-items">Today's Deals</li>
        <li class="border lower-items">Customer Service</li>
        <li class="border lower-items">Registry</li>
        <li class="border lower-items">Gift Cards</li>
        <li class="border lower-items">Sell</li>
      </ul>
    </div>
  </header>
  <div class="pict">j</div>
  <div class="a-section">
    <div class="box-m">
      <p class="box-det">Gaming accessories</p>
      <img class="main-img"
        src="https://images.immediate.co.uk/production/volatile/sites/3/2020/06/best-ps4-accessories-43287ea.jpg" alt=""
        class="src">
      <p class="see-more">See more</p>
    </div>
    <div class="box-m">
      <p class="box-det">Shop for your home essentials</p>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQlEAVu4HsryBeh3NjK3aS8ICm7Dz849ri8jA&s" alt=""
        class="src">
      <p class="see-more">See more</p>
    </div>
    <div class="box-m">
      <p class="box-det">Top categories in Kitchen appliances</p>
      <img
        src="https://media.istockphoto.com/id/637699518/vector/home-appliances-gas-cooker-refrigerator-microwave-and-washi.jpg?s=612x612&w=0&k=20&c=IazFnGqtDuj7iND7ZJ9yWqRu_QYXIKVYuchLSGsdMNU="
        alt="" class="src">
      <p class="see-more">See more</p>
    </div>
    <div class="box-m">
      <p class="box-det">Shop deals in Fashion</p>
      <img src="https://www.picturecorrect.com/wp-content/uploads/2012/10/colorful-fashion-shoot-1.jpg" alt=""
        class="src">
      <p class="see-more">See more</p>
    </div>
    <div class="box-m">
      <p class="box-det">Shop deals in Fashion</p>
      <img src="https://www.picturecorrect.com/wp-content/uploads/2012/10/colorful-fashion-shoot-1.jpg" alt=""
        class="src">
      <p class="see-more">See more</p>
    </div>
    <div class="box-m">
      <p class="box-det">Top categories in Kitchen appliances</p>
      <img
        src="https://media.istockphoto.com/id/637699518/vector/home-appliances-gas-cooker-refrigerator-microwave-and-washi.jpg?s=612x612&w=0&k=20&c=IazFnGqtDuj7iND7ZJ9yWqRu_QYXIKVYuchLSGsdMNU="
        alt="" class="src">
      <p class="see-more">See more</p>
    </div>
    <div class="box-m">
      <p class="box-det">Shop deals in Fashion</p>
      <img src="https://www.picturecorrect.com/wp-content/uploads/2012/10/colorful-fashion-shoot-1.jpg" alt=""
        class="src">
      <p class="see-more">See more</p>
    </div>
    <div class="box-m">
      <p class="box-det">Gaming accessories</p>
      <img src="https://images.immediate.co.uk/production/volatile/sites/3/2020/06/best-ps4-accessories-43287ea.jpg"
        alt="" class="src">
      <p class="see-more">See more</p>
    </div>
  </div>
  <footer>
    <div class="sign-in-box">
      <p style="font-size: 24px;">See personalized recommendations</p>
      <button class="sign-btn">Sign in</button>
      <p style="font-size: 11px;">New customer? <a href="" style="text-decoration: none;">Start here.</a></p>
    </div>
    <section class="f-sec">
      <a href="#mn">
        <div class="back-top">
          <span style="text-decoration: none;">Back to top</span>
        </div>
      </a>
      <div class="f-text">
        <ul>
          <li>Get to Know Us</li>
          <li>Careere</li>
          <li>About Amazon</li>
          <li>Investor Relations</li>
          <li>Amazon Devices</li>
          <li>Amazon Science</li>
        </ul>
        <ul>
          <li>Get to Know Us</li>
          <li>Careere</li>
          <li>About Amazon</li>
          <li>Investor Relations</li>
          <li>Amazon Devices</li>
          <li>Amazon Science</li>
        </ul>
        <ul>
          <li>Get to Know Us</li>
          <li>Careere</li>
          <li>About Amazon</li>
          <li>Investor Relations</li>
          <li>Amazon Devices</li>
          <li>Amazon Science</li>
        </ul>
        <ul>
          <li>Get to Know Us</li>
          <li>Careere</li>
          <li>About Amazon</li>
          <li>Investor Relations</li>
          <li>Amazon Devices</li>
          <li>Amazon Science</li>
        </ul>
      </div>
      <hr>
      <div class="copyright">© 1996-2024, Amazon.com, Inc. or its affiliates
      </div>
    </section>
  </footer>
</body>
<script>
  var count = 0;
  var images = ['https://m.media-amazon.com/images/I/71qcoYgEhzL._SX3000_.jpg',
    'https://m.media-amazon.com/images/I/71Ie3JXGfVL._SX3000_.jpg', 'https://m.media-amazon.com/images/I/61lwJy4B8PL._SX3000_.jpg']
  var t = document.querySelector('.pict');
  setInterval(() => {
    console.log('l')
    t.style.transition = 'background-image .5s ease';
    t.style.backgroundImage = `url('${images[count]}')`;

    count++;
    if (count == 3) {
      count = 0;
    }
  }, 2000)
  function f() {
    // Dim the entire body (background and all elements)
    console.log(document.body.children)
    for (let i = 1; i < document.body.children.length; i++) {
      document.body.children[i].style.opacity = 0.3;
   }
  }
  var y = document.querySelector('input');
  y.addEventListener('blur', () => {
    document.body.style.opacity = 1;
    for (let i = 1; i < document.body.children.length; i++) {
      document.body.children[i].style.opacity = 1;
    }
  })
</script>

</html>
