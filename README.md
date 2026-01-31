# suryansh-kumar
make a website for college
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PYQ Hub - Previous Year Questions</title>
    <style>
        /* CSS: Website ka look design karne ke liye */
        * { box-sizing: border-box; }
        body { font-family: 'Arial', sans-serif; background-color: #f0f2f5; margin: 0; padding: 0; }
        
        header { background: #1a73e8; color: white; padding: 40px 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.5rem; }
        
        .container { max-width: 1100px; margin: 20px auto; padding: 20px; }
        
        .search-bar { width: 100%; padding: 15px; margin-bottom: 30px; border: 1px solid #ddd; border-radius: 25px; font-size: 18px; outline: none; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }

        .grid-container { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        
        .subject-card { background: white; border-radius: 12px; padding: 25px; text-align: center; box-shadow: 0 4px 15px rgba(0,0,0,0.05); transition: 0.3s; }
        .subject-card:hover { transform: translateY(-8px); box-shadow: 0 8px 25px rgba(0,0,0,0.1); }
        
        .subject-card h3 { color: #333; margin-bottom: 10px; }
        .subject-card p { color: #666; font-size: 14px; margin-bottom: 20px; }
        
        .download-btn { background: #1a73e8; color: white; text-decoration: none; padding: 10px 25px; border-radius: 5px; font-weight: bold; display: inline-block; }
        .download-btn:hover { background: #1557b0; }

        footer { text-align: center; padding: 20px; color: #777; font-size: 14px; }
    </style>
</head>
<body>

<header>
    <h1>PYQ Portal</h1>
    <p>Apne Exams ke Previous Year Questions yahan se download karein</p>
</header>

<div class="container">
    <input type="text" class="search-bar" placeholder="Apna subject search karein...">

    <div class="grid-container">
        <div class="subject-card">
            <h3>Mathematics</h3>
            <p>Class 10th & 12th (2015-2025)</p>
            <a href="#" class="download-btn">Download PDF</a>
        </div>

        <div class="subject-card">
            <h3>Physics</h3>
            <p>JEE & Board Papers (2018-2025)</p>
            <a href="#" class="download-btn">Download PDF</a>
        </div>

        <div class="subject-card">
            <h3>Chemistry</h3>
            <p>Full Set (2019-2025)</p>
            <a href="#" class="download-btn">Download PDF</a>
        </div>
    </div>
</div>

<footer>
    © 2026 PYQ Hub | Made by Suryansh
</footer>

</body>
</html>
