# qutoes-wod
Some excellent and heart touching quotes around 50,000k
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, initial-scale=1.0">
    <title>Quotes World</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
            color: #333;
        }

        /* Landing Page Animation */
        .landing {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-image: linear-gradient(to right, #00c6ff, #0072ff);
            color: white;
            text-align: center;
        }

        .landing h1 {
            font-size: 4em;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: scale(0.9);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        /* Category Section */
        .categories {
            padding: 50px;
            background-color: #fff;
        }

        .category-title {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 30px;
            color: #333;
        }

        .category {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .category-card {
            background-color: #0072ff;
            color: white;
            margin: 20px;
            padding: 20px;
            width: 300px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .category-card:hover {
            transform: translateY(-10px);
        }

        /* Quotes Section */
        .quotes {
            padding: 50px;
        }

        .quote-block {
            margin-bottom: 20px;
            background-color: #f0f0f0;
            padding: 20px;
            border-left: 5px solid #0072ff;
            border-radius: 5px;
        }

        .quote-text {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .quote-author {
            text-align: right;
            font-style: italic;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .landing h1 {
                font-size: 2em; /* Adjust font size for mobile */
            }

            .category-card {
                width: 100%; /* Full width on mobile */
                margin: 10px 0; /* Adjust margin */
            }
        }
    </style>
</head>
<body>

    <!-- Landing Page -->
    <header class="landing">
        <h1>Welcome to Quotes World</h1>
    </header>

    <!-- Categories Section -->
    <main class="categories">
        <h2 class="category-title">Explore Quotes by Category</h2>
        <div class="category">
            <div class="category-card">
                <h3>Motivation</h3>
                <p>Find your daily dose of inspiration.</p>
            </div>
            <div class="category-card">
                <h3>Love</h3>
                <p>Beautiful thoughts on love and relationships.</p>
            </div>
            <div class="category-card">
                <h3>Life</h3>
                <p>Quotes that reflect the essence of life.</p>
            </div>
            <div class="category-card">
                <h3>Success</h3>
                <p>Words that inspire you to achieve greatness.</p>
            </div>
        </div>
    </main>

    <!-- Quotes Section -->
    <section class="quotes">
        <h2 class="category-title">Selected High-Quality Quotes</h2>

        <!-- English Quotes -->
        <div class="quote-block">
            <p class="quote-text">"The only limit to our realization of tomorrow is our doubts of today."</p>
            <p class="quote-author">- Franklin D. Roosevelt</p>
        </div>

        <div class="quote-block">
            <p class="quote-text">"Success is not final, failure is not fatal: It is the courage to continue that counts."</p>
            <p class="quote-author">- Winston Churchill</p>
        </div>

        <!-- Bangla Quotes -->
        <div class="quote-block">
            <p class="quote-text">"যে কখনো ভুল করেনি সে কখনো নতুন কিছু চেষ্টা করেনি।"</p>
            <p class="quote-author">- আলবার্ট আইনস্টাইন</p>
        </div>

        <div class="quote-block">
            <p class="quote-text">"জীবনটা হচ্ছে একটি আইসক্রিম, উপভোগ করো যতক্ষণ না গলে যায়।"</p>
            <p class="quote-author">- বুদ্ধদেব বসু</p>
        </div>
    </section>

</body>
</html>
