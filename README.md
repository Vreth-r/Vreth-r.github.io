<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Web Development Framework Page</title>

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    body {
      background: #f3f4f6;
    }
  </style>
</head>
<body class="text-gray-800 p-6">

  <div class="max-w-3xl mx-auto bg-white shadow-lg rounded-xl p-8">
    <h1 class="text-4xl font-bold mb-6 text-indigo-600">
      Building This Page Using Tailwind CSS
    </h1>

    <!-- Section 1 -->
    <section class="mb-8">
      <h2 class="text-2xl font-semibold text-indigo-500 mb-3">1. Installation of the Framework</h2>
      <p class="leading-relaxed">
        For this project, I chose <strong>Tailwind CSS</strong> as my web development framework. 
        Since I am hosting the site on <strong>GitHub Pages</strong> and do not need a build pipeline, 
        I installed Tailwind in the simplest way possible: by using the official CDN.
      </p>

      <pre class="bg-gray-900 text-green-300 p-4 rounded-lg mt-3 overflow-x-auto">
&lt;script src="https://cdn.tailwindcss.com"&gt;&lt;/script&gt;
      </pre>

      <p class="mt-3 leading-relaxed">
        This allowed me to use Tailwind utility classes directly inside my HTML without installing Node.js or running build tools.
      </p>
    </section>

    <!-- Section 2 -->
    <section class="mb-8">
      <h2 class="text-2xl font-semibold text-indigo-500 mb-3">2. How I Built the Page</h2>
      <p class="leading-relaxed">
        I created a single <code>README.md</code> file and structured the content into three main
        sections: installation, building process, and difficulties as you can see on this page. Tailwind utility classes were
        used for layout, spacing, typography, and styling.
      </p>

      <p class="leading-relaxed mt-3">
        I uploaded the file to a GitHub repository and enabled <strong>GitHub Pages</strong> from the
        repository settings to make the site public.
      </p>
    </section>

    <!-- Section 3 -->
    <section class="mb-8">
      <h2 class="text-2xl font-semibold text-indigo-500 mb-3">3. Difficulties Encountered & Solutions</h2>

      <ul class="list-disc pl-6 leading-relaxed">
        <li class="mb-2">
          <strong>Difficulty:</strong> Tailwind did not seem to load at first.<br>
          <strong>Solution:</strong> I realized GitHub Pages caches files aggressively. Doing a
          <code>Ctrl + Shift + R</code> hard refresh fixed the issue.
        </li>

        <li class="mb-2">
          <strong>Difficulty:</strong> Page content looked too “boxy”.<br>
          <strong>Solution:</strong> Added Tailwind utility classes like <code>shadow-lg</code>,
          <code>rounded-xl</code>, and <code>p-8</code> to improve the design quickly.
        </li>
        
        <li class="mb-2">
          <strong>Difficulty:</strong> I hate web development and genuinely thought of not doing this section of the lab.<br>
          <strong>Solution:</strong> I plan on not doing very well on the exam so I figured I need as many marks on the labs as possible.
        </li>
      </ul>
    </section>

    <footer class="text-center text-gray-500 mt-10">
      © 2025 - Hosted on GitHub Pages
    </footer>
  </div>

</body>
</html>
