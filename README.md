<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Learn the fundamentals of HTML5 semantic elements and build accessible, SEO-friendly web pages." />
  <meta name="author" content="Your Name" />
  <title>Accessible HTML5 Web Page Example</title>
</head>

<body>
  <header role="banner">
    <h1>Learn Semantic HTML5</h1>
    <p>Build accessible and SEO-friendly websites using modern HTML5 practices.</p>
  </header>

  <nav role="navigation" aria-label="Main navigation">
    <ul>
      <li><a href="#about" aria-label="About this site">About</a></li>
      <li><a href="#features" aria-label="Key features section">Features</a></li>
      <li><a href="#contact" aria-label="Contact section">Contact</a></li>
    </ul>
  </nav>

  <main role="main">
    <section id="about">
      <h2>About This Page</h2>
      <p>This page demonstrates how to use semantic HTML5 tags to structure a basic website layout that is accessible to screen readers and optimized for search engines.</p>
    </section>

    <section id="features">
      <h2>Key Features</h2>
      <article>
        <h3>Semantic Markup</h3>
        <p>Using elements like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, and <code>&lt;footer&gt;</code> makes the structure of your page clear and meaningful.</p>
      </article>
      <article>
        <h3>Accessibility Support</h3>
        <p>Landmark roles and descriptive link labels improve usability for screen readers and assistive technologies.</p>
      </article>
      <article>
        <h3>SEO Optimization</h3>
        <p>Proper use of heading tags and meta descriptions helps search engines understand your content and index it effectively.</p>
      </article>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>If you have questions or feedback, please reach out via email at <a href="mailto:info@example.com" aria-label="Email us at info@example.com">info@example.com</a>.</p>
    </section>
  </main>

  <footer role="contentinfo">
    <p>&copy; 2025 Your Name. All rights reserved.</p>
  </footer>
</body>
</html>

