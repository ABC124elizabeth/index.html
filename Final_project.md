<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Café</title>
  <link rel="stylesheet" href="styles.css">
  <style>

    /* Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #c7a7a7;
  background-color: #f9f9f9;
}

header {
  text-align: center;
  background-color: #36b5f0; 
  color: #f3e9dc;           
  padding: 2rem 1rem;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

header p {
  font-size: 1.2rem;
}

/* Card Grid */
.card-grid {
  display: grid;
  gap: 1.5rem;
  padding: 2rem;
}

/* Card Styles */
.card {
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(197, 148, 148, 0.1);
  padding: 1.5rem;
  text-align: center;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
}

.card h2 {
  font-size: 1.5rem;
  color: #3a886a; /* Deep green */
  margin-bottom: 0.5rem;
}

.card p {
  font-size: 1rem;
  color: #475866;
}

/* Footer */
.footer {
  text-align: center;
  background: #18dfdf;
  color: #f3e9dc;
  padding: 1rem;
}

/* Responsive Breakpoints */
/* Large Screens */
@media (min-width: 1024px) {
  .card-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* Medium Screens */
@media (min-width: 768px) and (max-width: 1023px) {
  .card-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Small Screens */
@media (max-width: 767px) {
  .card-grid {
    grid-template-columns: 1fr;
  }

  header h1 {
    font-size: 2rem;
  }

  header p {
    font-size: 1rem;
  }
}
</style>
</head>
<body>
  <header class="header">
    <h1>Welcome to Book Café</h1>
    <p>Discover your next great read!</p>
  </header>

  <main class="main-content">
    <section class="card-grid">
      <div class="card">
        <h2>Book Title 1</h2>
        <p>Learning web development.</p>
      </div>
      <div class="card">
        <h2>Book Title 2</h2>
        <p>Explore new worlds and ideas.</p>
      </div>
      <div class="card">
        <h2>Book Title 3</h2>
        <p>Use the content and skills to enjoy learning.</p>
      </div>
      <div class="card">
        <h2>Book Title 4</h2>
        <p>Get growing as a great developer.</p>
      </div>
    </section>
  </main>

  <footer class="footer">
    <p>&copy; 2025 Book Café. All rights reserved.</p>
  </footer>
</body>
</html>
