## *Navigation Bar*
'''.navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #34495e;
      padding: 10px 20px;
      color: #fff;
    }
    .navbar .logo {
      font-size: 1.5em;
    }
    .navbar ul {
      display: flex;
      list-style: none;
      margin: 0;
      padding: 0;
    }
    .navbar ul li {
      margin-left: 20px;
    }
    .navbar ul li a {
      color: #fff;
      text-decoration: none;
    }

'''<div class="navbar">
    <div class="logo">Reyn's Website</div>
    <ul>
      <li><a href="#">Product List</a></li>
      <li><a href="3">Employee Cards</a></li>
      <li><a href="#">Student Profiles</a></li>
    </ul>
  </div>
  
## *Product List*

'''.product-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      padding: 20px;
    }
    .product-card {
      flex: 0 1 calc(25% - 20px);
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 5px;
      padding: 15px;
      text-align: center;
    }
    .product-card img {
      max-width: 100%;
      border-radius: 5px;
    }
    .product-card h4 {
      margin: 10px 0;
      color: #34495e;
    }
    .product-card p {
      color: #7f8c8d;
    }

'''<div id="product-section">
    <h1>Product List</h1>
    <div class="product-container">
      <div class="product-card">
        <img src="product1.jpg" alt="Product 1">
        <h4>Acer Aspire 3</h4>
        <p>₱30,000.00</p>
      </div>
      <div class="product-card">
        <img src="product2.jpg" alt="Product 2">
        <h4>Inplay SK610</h4>
        <p>₱1,100.00</p>
      </div>
      <div class="product-card">
        <img src="product3.jpg" alt="Product 3">
        <h4>Raigor III WG21RS</h4>
        <p>₱600.00</p>
      </div>
    </div>
  </div>
  
## *Employee Cards*

'''.employee-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      padding: 20px;
      justify-content: center;
    }
    .employee-card {
      display: flex;
      align-items: center;
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 5px;
      padding: 15px;
      width: 300px;
    }
    .employee-card img {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      margin-right: 20px;
    }
    .employee-card .info {
      display: flex;
      flex-direction: column;
    }
    .employee-card .info h4 {
      margin: 0;
      color: #34495e;
    }
    .employee-card .info p {
      margin: 5px 0 0;
      color: #7f8c8d;
    }

'''<div id="employee-section">
    <h1>Employee Cards</h1>
    <div class="employee-container">
      <div class="employee-card">
        <img src="employee1.jpg" alt="Employee 1">
        <div class="info">
          <h4>Berlin</h4>
          <p>Software Engineer</p>
        </div>
      </div>
      <div class="employee-card">
        <img src="employee2.jpg" alt="Employee 2">
        <div class="info">
          <h4>Denver</h4>
          <p>Product Manager</p>
        </div>
      </div>
      <div class="employee-card">
        <img src="employee3.jpg" alt="Employee 3">
        <div class="info">
          <h4>Rio</h4>
          <p>Web Developer</p>
        </div>
      </div>
    </div>
  </div>
  
## *Student Profile*

'''.profile-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
      width: 300px;
      margin: 20px auto;
    }
    .profile-container img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
    }
    .profile-container h3 {
      margin: 15px 0;
      color: #34495e;
    }
    .profile-container p {
      color: #7f8c8d;
      text-align: center;
    }

'''<div id="student-section">
    <h1>Student Profiles</h1>
    <div class="profile-container">
      <img src="student1.jpg" alt="Student 1">
      <h3>Cruz, Reynalyn</h3>
      <p>Bachelor of Science in Information Technology</p>
    </div>
    <div class="profile-container">
      <img src="student2.jpg" alt="Student 2">
      <h3>The Professor</h3>
      <p>Bachelor of Science in Psychology</p>
    </div>
    <div class="profile-container">
      <img src="student3.jpg" alt="Student 3">
      <h3>Raquel Murillo</h3>
      <p>Bachelor of Science in Criminology</p>
    </div>
  </div>
  
## *Footer Layout*

'''.footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #34495e;
      color: #fff;
      padding: 15px 20px;
    }
    .footer .left, .footer .right {
      flex: 1;
    }
    .footer .center {
      flex: 2;
      text-align: center;
    }

'''<footer class="footer">
    <div class="left">© 2024 Reyn's Website</div>
    <div class="center">Follow us on social media</div>
    <div class="right">Privacy Policy</div>
  </footer>
