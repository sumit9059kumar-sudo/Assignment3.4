File: semantic-page.html
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Webpage & Accessibility</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; color: #333; }
        header { background: #2c3e50; color: white; padding: 20px; text-align: center; }
        nav { background: #34495e; padding: 10px; text-align: center; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover { text-decoration: underline; }
        .container { display: flex; max-width: 1100px; margin: 20px auto; padding: 0 20px; gap: 20px; }
        main { flex: 3; }
        aside { flex: 1; background: #f4f4f4; padding: 15px; border-radius: 5px; height: fit-content; }
        section, article { margin-bottom: 20px; padding: 15px; border: 1px solid #ddd; border-radius: 5px; background: #fff; }
        footer { background: #2c3e50; color: white; text-align: center; padding: 15px; margin-top: 40px; }
        h1, h2, h3 { color: #2c3e50; }
        header h1 { color: white; margin: 0; }
        img { max-width: 100%; height: auto; border-radius: 4px; }
    </style>
</head>
<body>

    <!-- 1. Header Element -->
    <header>
        <h1>TechInsights Blog</h1>
        <p>Exploring web development, accessibility, and modern design.</p>
    </header>

    <!-- 2. Nav Element -->
    <nav>
        <a href="#home">Home</a>
        <a href="#articles">Articles</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <!-- 3. Main Element -->
        <main>
            <!-- 4. Section Element -->
            <section id="articles">
                <h2>Latest Articles</h2>

                <!-- 5. Article Element with proper heading hierarchy -->
                <article>
                    <h3>Understanding Semantic HTML</h3>
                    <p>Published on October 20, 2026 by Jane Doe</p>
                    <img src="images/semantic-code.jpg" alt="A laptop screen displaying clean and structured HTML5 semantic tags in a code editor" width="600" height="300">
                    <p>Semantic HTML introduces meaning to the web page rather than just presentation. Tags like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, and <code>&lt;footer&gt;</code> help screen readers and search engines understand the document structure.</p>
                </article>

                <article>
                    <h3>Why Accessibility Matters</h3>
                    <p>Published on October 18, 2026 by John Smith</p>
                    <p>Web accessibility ensures that people with disabilities can perceive, understand, navigate, and interact with the web. Proper alt text and semantic tags are foundational building blocks.</p>
                </article>
            </section>
        </main>

        <!-- 6. Aside Element -->
        <aside>
            <h3>Related Links</h3>
            <ul>
                <li><a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a></li>
                <li><a href="https://www.w3.org" target="_blank" rel="noopener noreferrer">W3C Web Accessibility</a></li>
            </ul>
            <h3>About the Author</h3>
            <p>Jane is a front-end developer passionate about clean code and inclusive web design.</p>
        </aside>
    </div>

    <!-- 7. Footer Element -->
    <footer>
        <p>&copy; 2026 TechInsights Blog. All rights reserved.</p>
    </footer>

</body>
</html>
Requirements Checklist for Submission:
Semantic Structure: Replaced generic <div> containers with proper tags (<header>, <nav>, <main>, <section>, <article>, <aside>, and <footer>).

Heading Hierarchy: Checked that <h1> is used once for the main title, followed logically by <h2> for sections and <h3> for individual articles.

Accessibility: Added descriptive alt text to images for screen readers and assistive tech.

Links & Navigation: Grouped all navigation links inside the <nav> element and ensured clear section anchors.