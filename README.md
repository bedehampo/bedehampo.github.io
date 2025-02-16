<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body class="bg-white text-black font-sans">
    <!-- Header -->
    <header class="text-center pb-10 ">
        <p class="text-xl mt-2 font-light text-justify">SWE - Backend Engineer | DevOps & Machine Learning Enthusiast</p>
        <p class="text-l mt-2 font-light text-justify">I am a Software Engineer specialising in backend systems, database design, and building scalable systems.<br/>I build efficient services using TypeScript, Python, and Java. While I have experience with frontend and mobile development, my core strength lies in backend logic and building scalable systems. I'm currently improving my DevOps skills with tools like Docker and CI/CD pipelines and continuously learning through hands-on projects, including machine learning applications.</p>
        <!-- Social Links -->
        <div class="flex justify-center mt-4 space-x-6">
            <a href="https://www.linkedin.com/in/hampoechebede" class="text-xl text-blue-600" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="mailto:hampoherobede@gmail.com" class="text-xl text-red-600" target="_blank"><i class="fas fa-envelope"></i></a>
            <a href="https://www.youtube.com/@bede_hampo" class="text-xl text-red-500" target="_blank"><i class="fab fa-youtube"></i></a>
            <a href="https://github.com/bedehampo" class="text-xl text-gray-900" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://dev.to/bede_hampo" class="text-xl text-black" target="_blank"><i class="fab fa-dev"></i></a>
        </div>
    </header>

    <!-- Main Content -->
    <main class="max-w-5xl mx-auto grid grid-cols-2 gap-6 p-6">
        <!-- Projects Column -->
        <section class="bg-white border border-gray-300 rounded-lg p-6">
            <h2 class="text-2xl font-semibold mb-4">Projects</h2>
            <div class="mb-4">
                <h3 class="text-lg font-bold">Project Name</h3>
                <p class="text-sm"><strong>Role:</strong> Backend Engineer</p>
                <p class="text-sm"><strong>Features Built:</strong></p>
                <ul class="list-disc ml-4 text-sm">
                    <li>Authentication with JWT</li>
                    <li>Payment Integration with Stripe</li>
                </ul>
                <p class="mt-2 text-sm">Implemented using NestJS and MongoDB with Docker containerization.</p>
                <p class="mt-2 text-sm">Code Snippet:</p>
                <pre class="bg-gray-200 p-3 text-xs rounded"><code>const jwt = require('jsonwebtoken');
const token = jwt.sign({ userId: user._id }, process.env.JWT_SECRET);</code></pre>
                <a href="#" class="text-blue-600 underline text-sm">Project Link</a>
            </div>
        </section>

        <!-- Activity Logs Column -->
        <section class="bg-white border border-gray-300 rounded-lg p-6">
            <h2 class="text-2xl font-semibold mb-4">Activity Logs</h2>
            <div class="mb-4">
                <h3 class="text-lg font-bold">Week 1 - September 2025</h3>
                <p class="text-sm"><strong>Tasks:</strong> Implemented API endpoints.</p>
                <p class="text-sm"><strong>Challenges:</strong> Debugging CORS issues.</p>
                <p class="text-sm"><strong>Solutions:</strong> Adjusted CORS settings in the server configuration.</p>
                <p class="text-sm"><strong>Learned:</strong> Proper CORS handling for cross-origin requests.</p>
            </div>
        </section>
    </main>

    <!-- Additional Info -->
    <section class="max-w-5xl mx-auto mt-6 p-6 bg-white border border-gray-300 rounded-lg">
        <h2 class="text-2xl font-semibold mb-4">Personal Insights</h2>
        <div class="mb-3">
            <h3 class="text-lg font-bold">Hobbies</h3>
            <p class="text-sm">Podcasting, Reading Tech Blogs, Hiking</p>
        </div>
        <div class="mb-3">
            <h3 class="text-lg font-bold">Strengths & Talents</h3>
            <p class="text-sm">Problem-Solving, Public Speaking, Mentoring</p>
        </div>
        <div class="mb-3">
            <h3 class="text-lg font-bold">Aspirations</h3>
            <p class="text-sm">To become a globally recognized backend engineer and thought leader.</p>
        </div>
        <div class="mb-3">
            <h3 class="text-lg font-bold">Philosophy</h3>
            <p class="text-sm">Continuous learning, innovation, and giving back to the community.</p>
        </div>
    </section>
</body>
</html>
