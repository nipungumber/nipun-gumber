<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nipun Gumber's Portfolio</title>
    <!-- Use Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Google Fonts for a clean, professional look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Poppins:wght@600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0f172a;
            color: #e2e8f0;
            line-height: 1.6;
        }
        h1, h2, h3 {
            font-family: 'Poppins', sans-serif;
        }
        .accent-text {
            color: #fca5a5;
        }
        .container-bg {
            background-color: #1e293b;
            border: 1px solid #334155;
        }
        .section-separator {
            background-color: #334155;
        }
        .badge-img {
            transition: transform 0.2s;
        }
        .badge-img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="p-4 md:p-8">
    <div class="container mx-auto px-4 py-8 md:px-12 md:py-16 container-bg rounded-2xl shadow-3xl">

        <!-- Header Section -->
        <header class="text-center mb-16">
            <h1 class="text-5xl md:text-7xl font-extrabold text-white mb-4 leading-tight tracking-wider">
                Hey, I'm Nipun 🎨
            </h1>
            <p class="text-slate-400 text-lg md:text-xl max-w-3xl mx-auto font-medium">
                <span class="accent-text font-bold">Crafting beautiful and intuitive digital experiences</span> where design and functionality collide ⚡
            </p>
        </header>

        <!-- Badges & Banner -->
        <div class="flex flex-wrap justify-center gap-3 mb-12">
            <img src="https://img.shields.io/badge/Graphic%20Designer-%23FCA5A5?style=for-the-badge&logo=adobeillustrator&logoColor=black" alt="Graphic Designer Badge" class="rounded-md badge-img">
            <img src="https://img.shields.io/badge/UI%2FUX-%23F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="UI/UX Badge" class="rounded-md badge-img">
            <img src="https://img.shields.io/badge/Creative%20Suite-DD001A?style=for-the-badge&logo=adobe&logoColor=white" alt="Creative Suite Badge" class="rounded-md badge-img">
            <img src="https://img.shields.io/badge/Branding-%23F7DF1E?style=for-the-badge&logo=brandfolder&logoColor=black" alt="Branding Badge" class="rounded-md badge-img">
            <img src="https://img.shields.io/badge/Open%20Source%20Lover-%2300FF99?style=for-the-badge&logo=github&logoColor=black" alt="Open Source Badge" class="rounded-md badge-img">
        </div>
        
        <img src="https://placehold.co/1200x400/2f4055/fca5a5?text=Nipun's+Design+Portfolio" alt="Project Banner" class="w-full rounded-2xl shadow-xl mb-16">

        <div class="h-0.5 w-full section-separator mb-16"></div>

        <!-- About Me Section -->
        <section class="mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 text-white">🧑‍💻 About Me</h2>
            <p class="text-slate-300 text-lg mb-6">
                I'm Nipun, a passionate graphic designer specializing in crafting visually stunning and user-friendly digital experiences. From brand identity to UI/UX design, I love bringing ideas to life with a clean, modern aesthetic. I believe great design is about both beauty and purpose.
            </p>
            <ul class="list-disc list-inside space-y-2 text-slate-300">
                <li><strong class="accent-text">Design Ethos:</strong> I focus on user-centric design principles to create interfaces that are not just beautiful, but also intuitive and accessible.</li>
                <li><strong class="accent-text">Skill Set:</strong> Expert in Figma, Adobe Creative Suite (Illustrator, Photoshop, InDesign), and advanced typography.</li>
                <li><strong class="accent-text">Passion Project:</strong> I love exploring the intersection of design and emerging tech, like creating AR filters and dynamic web animations.</li>
            </ul>
        </section>

        <div class="h-0.5 w-full section-separator mb-16"></div>

        <!-- Design Toolkit Section -->
        <section class="mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 text-white">🛠️ Design Toolkit</h2>
            <div class="overflow-x-auto">
                <table class="min-w-full bg-slate-700 rounded-lg shadow-md">
                    <thead>
                        <tr class="bg-slate-600 rounded-t-lg">
                            <th class="p-4 text-left font-bold text-slate-200 uppercase tracking-wider">Category</th>
                            <th class="p-4 text-left font-bold text-slate-200 uppercase tracking-wider">Tools & Skills</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Design Tools</strong></td>
                            <td class="p-4">Figma, Adobe XD, Sketch</td>
                        </tr>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Creative Suite</strong></td>
                            <td class="p-4">Adobe Photoshop, Illustrator, InDesign</td>
                        </tr>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>UI/UX</strong></td>
                            <td class="p-4">Wireframing, Prototyping, User Research</td>
                        </tr>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Concepts</strong></td>
                            <td class="p-4">Branding, Typography, Color Theory, Motion Graphics</td>
                        </tr>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Web Dev</strong></td>
                            <td class="p-4">HTML, CSS, JavaScript (basics)</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <div class="h-0.5 w-full section-separator mb-16"></div>

        <!-- GitHub Trophies Section -->
        <section class="mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 text-white">🏆 GitHub Trophies</h2>
            <div class="flex justify-center">
                <a href="https://github.com/ryo-ma/github-profile-trophy">
                    <img src="https://github-profile-trophy.vercel.app/?username=nipungumber&theme=flat&no-frame=true&margin-w=10" alt="GitHub Trophies" class="w-full h-auto max-w-2xl">
                </a>
            </div>
        </section>

        <div class="h-0.5 w-full section-separator mb-16"></div>

        <!-- GitHub Stats Section -->
        <section class="mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 text-white">📊 GitHub Stats</h2>
            <div class="flex flex-col md:flex-row justify-center gap-6">
                <img src="https://github-readme-stats.vercel.app/api?username=nipungumber&show_icons=true&theme=buefy&hide_rank=false" alt="Nipun's GitHub stats" class="rounded-lg shadow-lg w-full md:w-1/2">
                <img src="https://streak-stats.demolab.com?user=nipungumber&theme=buefy" alt="GitHub Streak" class="rounded-lg shadow-lg w-full md:w-1/2">
            </div>
        </section>

        <div class="h-0.5 w-full section-separator mb-16"></div>

        <!-- Connect With Me Section -->
        <section class="mb-16 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 text-white">🌐 Connect With Me</h2>
            <ul class="list-none space-y-4 text-slate-300 max-w-xl mx-auto text-left">
                <li><strong class="accent-text">Portfolio:</strong> <a href="https://nipun-gumber.netlify.app" class="accent-text underline transition-colors duration-200 hover:text-white">nipun-gumber.netlify.app</a></li>
                <li><strong class="accent-text">GitHub:</strong> <a href="https://github.com/nipungumber" class="accent-text underline transition-colors duration-200 hover:text-white">@nipungumber</a></li>
                <li><strong class="accent-text">LinkedIn:</strong> <a href="https://www.linkedin.com/in/nipungumber" class="accent-text underline transition-colors duration-200 hover:text-white">in/nipungumber</a></li>
            </ul>
        </section>

        <div class="h-0.5 w-full section-separator mb-16"></div>

        <!-- Footer Section -->
        <footer class="text-center">
            <p class="text-xl md:text-2xl font-bold text-slate-300">
                💡 <span class="accent-text">*"Turning pixels into captivating stories"*</span> ⚡
            </p>
        </footer>
    </div>
</body>
</html>
