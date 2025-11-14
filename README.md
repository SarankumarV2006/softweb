# Ex.07 Restuarant Website
## Date:14.11.2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
HOME PAGE
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kaimanam Restaurant - Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="header-inner">
      <div class="brand">Kaimanam Restaurant</div>
      <nav class="nav">
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="hero-inner">
      <h1>Welcome to Kaimanam</h1>
      <p>Authentic taste. Pure quality. Experience traditional flavours prepared with love and fresh ingredients.</p>
    </div>
  </section>

  <main class="container">
    <section class="section">
      <h2>Our Promise</h2>
      <p style="max-width:820px;margin:12px auto;color:var(--muted);line-height:1.6">
        Kaimanam brings a blend of classic recipes and seasonal produce. Dine-in or take away — each plate is prepared to deliver a memorable experience.
      </p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="f-inner container">
      <div>© 2025 Kaimanam Restaurant</div>
      <div>Designed by SARAN</div>
    </div>
  </footer>
</body>
</html>
```
MENU
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kaimanam Restaurant - Menu</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="header-inner">
      <div class="brand">Kaimanam Restaurant</div>
      <nav class="nav">
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="section">
      <h2>Our Menu</h2>

      <div class="menu-grid">
        <!-- 12 menu cards: image, name, price, small desc -->
        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1606756796389-7b1b1f0d1d9a?q=80&w=1400&auto=format&fit=crop" alt="Chicken Biryani">
          <div class="body">
            <div>
              <h3>Chicken Biryani</h3>
              <p class="desc">Aromatic basmati rice layered with spiced chicken.</p>
            </div>
            <p class="price">₹180</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1525755662778-989d0524087e?q=80&w=1400&auto=format&fit=crop" alt="Mutton Curry">
          <div class="body">
            <div>
              <h3>Mutton Curry</h3>
              <p class="desc">Slow-cooked mutton in rich masala gravy.</p>
            </div>
            <p class="price">₹220</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1543352634-1f5b0f0f4c33?q=80&w=1400&auto=format&fit=crop" alt="Fish Fry">
          <div class="body">
            <div>
              <h3>Fish Fry</h3>
              <p class="desc">Crispy marinated fillet with coastal spices.</p>
            </div>
            <p class="price">₹150</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1543353071-087092ec393c?q=80&w=1400&auto=format&fit=crop" alt="Veg Meals">
          <div class="body">
            <div>
              <h3>Veg Meals</h3>
              <p class="desc">Traditional vegetable thali with rice and sides.</p>
            </div>
            <p class="price">₹120</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1551218808-94e220e084d2?q=80&w=1400&auto=format&fit=crop" alt="Parotta & Beef Curry">
          <div class="body">
            <div>
              <h3>Parotta & Beef Curry</h3>
              <p class="desc">Flaky parotta served with rich beef curry.</p>
            </div>
            <p class="price">₹160</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=1400&auto=format&fit=crop" alt="Grill Chicken">
          <div class="body">
            <div>
              <h3>Grilled Chicken</h3>
              <p class="desc">Herb-marinated chicken, chargrilled.</p>
            </div>
            <p class="price">₹250</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1604908177225-df86cf5f3c3a?q=80&w=1400&auto=format&fit=crop" alt="Prawn Masala">
          <div class="body">
            <div>
              <h3>Prawn Masala</h3>
              <p class="desc">Tangy prawn masala with coconut notes.</p>
            </div>
            <p class="price">₹200</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?q=80&w=1400&auto=format&fit=crop" alt="Korma">
          <div class="body">
            <div>
              <h3>Vegetable Korma</h3>
              <p class="desc">Creamy coconut & cashew vegetable curry.</p>
            </div>
            <p class="price">₹140</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1562967916-eb82221dfb36?q=80&w=1400&auto=format&fit=crop" alt="Dosa">
          <div class="body">
            <div>
              <h3>Masala Dosa</h3>
              <p class="desc">Crispy dosa with potato masala and chutney.</p>
            </div>
            <p class="price">₹90</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1542444459-db4b7f19f32a?q=80&w=1400&auto=format&fit=crop" alt="Appam">
          <div class="body">
            <div>
              <h3>Appam & Stew</h3>
              <p class="desc">Soft appam served with vegetable stew.</p>
            </div>
            <p class="price">₹95</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1514512364185-6b6a4b4f39b3?q=80&w=1400&auto=format&fit=crop" alt="Payasam">
          <div class="body">
            <div>
              <h3>Payasam</h3>
              <p class="desc">Traditional sweet rice pudding.</p>
            </div>
            <p class="price">₹60</p>
          </div>
        </div>

        <div class="menu-card">
          <img src="https://images.unsplash.com/photo-1559056199-79b1d94f8f05?q=80&w=1400&auto=format&fit=crop" alt="Tea">
          <div class="body">
            <div>
              <h3>Cardamom Tea</h3>
              <p class="desc">Fresh brewed tea with a hint of cardamom.</p>
            </div>
            <p class="price">₹25</p>
          </div>
        </div>

      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="f-inner container">
      <div>© 2025 Kaimanam Restaurant</div>
      <div>Designed by SARAN</div>
    </div>
  </footer>
</body>
</html>
```
ADMINISTRATION
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kaimanam Restaurant - Administration</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="header-inner">
      <div class="brand">Kaimanam Restaurant</div>
      <nav class="nav">
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="section">
      <h2>Administration Team</h2>

      <div class="team-grid">
        <!-- 6 team members -->
        <div class="team-card">
          <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=1200&auto=format&fit=crop" alt="Manager">
          <div style="padding:12px">
            <h4>Mr. Ramesh</h4>
            <p class="role">General Manager</p>
          </div>
        </div>

        <div class="team-card">
          <img src="https://images.unsplash.com/photo-1547425260-76bcadfb4f2c?q=80&w=1200&auto=format&fit=crop" alt="Chef">
          <div style="padding:12px">
            <h4>Ms. Anitha</h4>
            <p class="role">Head Chef</p>
          </div>
        </div>

        <div class="team-card">
          <img src="https://images.unsplash.com/photo-1545996124-1a6f5f6b2d7f?q=80&w=1200&auto=format&fit=crop" alt="Operations">
          <div style="padding:12px">
            <h4>Mr. Vinod</h4>
            <p class="role">Operations Manager</p>
          </div>
        </div>

        <div class="team-card">
          <img src="https://images.unsplash.com/photo-1544006659-f0b21884ce1d?q=80&w=1200&auto=format&fit=crop" alt="HR">
          <div style="padding:12px">
            <h4>Ms. Priya</h4>
            <p class="role">HR & Admin</p>
          </div>
        </div>

        <div class="team-card">
          <img src="https://images.unsplash.com/photo-1545239351-1141bd82e8a6?q=80&w=1200&auto=format&fit=crop" alt="Marketing">
          <div style="padding:12px">
            <h4>Mr. Ajay</h4>
            <p class="role">Marketing Lead</p>
          </div>
        </div>

        <div class="team-card">
          <img src="https://images.unsplash.com/photo-1545996124-c6fbd07a5846?q=80&w=1200&auto=format&fit=crop" alt="Accounts">
          <div style="padding:12px">
            <h4>Ms. Leela</h4>
            <p class="role">Accountant</p>
          </div>
        </div>
      </div>

    </section>
  </main>

  <footer class="site-footer">
    <div class="f-inner container">
      <div>© 2025 Kaimanam Restaurant</div>
      <div>Designed by SARAN</div>
    </div>
  </footer>
</body>
</html>
```
CONTACT PAGE
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kaimanam Restaurant - Contact</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="header-inner">
      <div class="brand">Kaimanam Restaurant</div>
      <nav class="nav">
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="section">
      <h2>Contact Us</h2>

      <div class="contact-box">
        <div style="margin-bottom:12px">
          <strong>Address:</strong>
          <div>12, Marina Road, Kaimanam, Tamil Nadu, India - 600001</div>
        </div>

        <div style="margin-bottom:12px">
          <strong>Phone:</strong>
          <div>+91 98765 43210</div>
        </div>

        <div style="margin-bottom:12px">
          <strong>Email:</strong>
          <div>contact@kaimanamrestaurant.com</div>
        </div>

        <div style="margin-top:14px">
          <strong>Opening Hours:</strong>
          <div>Mon – Sun: 10:00 AM – 11:00 PM</div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="f-inner container">
      <div>© 2025 Kaimanam Restaurant</div>
      <div>Designed by SARAN</div>
    </div>
  </footer>
</body>
</html>
```

## OUTPUT:
![WhatsApp Image 2025-11-14 at 12 32 42_d497e608](https://github.com/user-attachments/assets/3ba145ca-54d2-4b80-b1e1-07e00100e613)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
