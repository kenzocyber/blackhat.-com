
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BlackHat</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <script>
    // Auto Theme
    if (window.matchMedia('(prefers-color-scheme: light)').matches) {
      document.documentElement.classList.remove('dark');
    } else {
      document.documentElement.classList.add('dark');
    }
  </script>
  <style>
    body {
      background-color: #0c0c1d;
      color: #00fff7;
      font-family: 'Courier New', monospace;
    }
    h2, h3 {
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    .card {
      border: 1px solid #00fff7;
      border-radius: 0.5rem;
      padding: 1.25rem;
      text-align: center;
      background-color: #111122;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #00fff7;
    }
  </style>
</head>
<body class="dark">

  <!-- Header -->
  <header class="text-center py-6 text-2xl font-bold tracking-widest border-b border-cyan-400">
    BLACK HAT
  </header>

  <!-- Hero Section -->
  <section class="text-center p-8" data-aos="fade-down">
    <h3 class="text-cyan-300 mb-2">black hat</h3>
    <h1 class="text-2xl md:text-3xl font-bold mb-4">Ethical Hacker | Cybersecurity Enthusiast</h1>
  </section>

  <!-- About Me -->
  <section class="px-6 py-8" data-aos="fade-up">
    <h2 class="text-xl mb-4 text-cyan-300">About Me</h2>
    <p class="leading-relaxed text-base">
      Passionate about ethical hacking and cybersecurity. I believe in securing the digital world and constantly learning new techniques to stay ahead in the ever-evolving landscape.
    </p>
  </section>

  <!-- Skills -->
  <section class="px-6 py-8 bg-zinc-900" data-aos="zoom-in">
    <h2 class="text-xl mb-6 text-cyan-300">Skills</h2>
    <div class="grid gap-4">
      <div class="card"> <h3 class="mb-2 text-cyan-200">Programming</h3><p>Python, JavaScript, Bash</p> </div>
      <div class="card"> <h3 class="mb-2 text-cyan-200">Security</h3><p>Penetration Testing, Network Security</p> </div>
      <div class="card"> <h3 class="mb-2 text-cyan-200">Tools</h3><p>Kali Linux, Metasploit, Wireshark</p> </div>
    </div>
  </section>

  <!-- Projects -->
  <section class="px-6 py-8" data-aos="fade-up">
    <h2 class="text-xl mb-6 text-cyan-300">Projects</h2>
    <div class="grid gap-4">
      <div class="card">
        <h3 class="mb-2 text-cyan-200">nethunter-termux</h3>
        <p class="mb-2">Hacking via smartphone.</p>
        <p>⭐ Stars: 68</p>
        <a href="#" class="underline text-cyan-400">View Repository</a>
      </div>
      <div class="card">
        <h3 class="mb-2 text-cyan-200">XSS Detector</h3>
        <p class="mb-2">Detect XSS in web apps.</p>
        <p>⭐ Stars: 102</p>
        <a href="#" class="underline text-cyan-400">View Repository</a>
      </div>
      <div class="card">
        <h3 class="mb-2 text-cyan-200">AutoRecon</h3>
        <p class="mb-2">Bug bounty recon automation.</p>
        <p>⭐ Stars: 87</p>
        <a href="#" class="underline text-cyan-400">View Repository</a>
      </div>
    </div>
  </section>

  <!-- Blog Link -->
  <section class="px-6 py-8 bg-zinc-900 text-center" data-aos="zoom-in">
    <h2 class="text-xl mb-4 text-cyan-300">Blog</h2>
    <p class="mb-4">Sharing tips, writeups, and hacker stories.</p>
    <a href="#" class="underline text-cyan-400">Visit My Blog</a>
  </section>

  <!-- Tools Page Link -->
  <section class="px-6 py-8 text-center" data-aos="fade">
    <h2 class="text-xl mb-4 text-cyan-300">Tools</h2>
    <p class="mb-4">My collection of hacking tools & utilities.</p>
    <a href="#" class="underline text-cyan-400">Explore Tools</a>
  </section>

  <!-- Contact Form -->
  <section class="px-6 py-8 bg-zinc-900" data-aos="fade-up" id="contact">
    <h2 class="text-xl mb-6 text-cyan-300">Contact</h2>
    <form class="grid gap-4 max-w-xl mx-auto">
      <input type="text" placeholder="Your Name" class="p-2 rounded bg-black text-white border border-cyan-400">
      <input type="email" placeholder="Your Email" class="p-2 rounded bg-black text-white border border-cyan-400">
      <textarea rows="4" placeholder="Message" class="p-2 rounded bg-black text-white border border-cyan-400"></textarea>
      <button class="bg-cyan-500 hover:bg-cyan-400 text-black font-bold py-2 rounded">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="text-center text-sm py-6 border-t border-cyan-400">
    &copy; 2025 BlackHat — Designed with ⚡ by BlackHat
  </footer>

  <script>
    AOS.init();
  </script>

</body>
</html>
