<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README</title>
    <!-- Use Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Google Fonts for a clean, professional look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Poppins:wght@600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0f172a; /* A very dark blue background */
            color: #e2e8f0; /* Light gray text for contrast */
            line-height: 1.6;
        }
        h1, h2, h3 {
            font-family: 'Poppins', sans-serif;
        }
        h1 {
            color: #cbd5e1; /* Lighter heading color */
        }
        .container {
            max-width: 1000px;
        }
        .accent {
            color: #38b2ac; /* Teal accent color */
        }
    </style>
</head>
<body class="p-6">
    <div class="container mx-auto px-4 md:px-8 bg-slate-800 rounded-xl shadow-2xl p-8 md:p-12">
        <!-- Header Section -->
        <header class="text-center mb-12">
            <h1 class="text-5xl md:text-6xl font-extrabold mb-4 text-white">Git Hub</h1>
            <p class="text-slate-400 text-lg max-w-2xl mx-auto">             
           <span class="accent font-bold">Git Hub</span> is a beautifully crafted, thoughtful application designed to take the stress out of gift-giving. It combines a clean, modern user interface with intelligent search capabilities to help you find the perfect present for any occasion and any person.
            </p>
        </header>

        <!-- Badges & Banner -->
        <div class="flex flex-wrap justify-center gap-2 mb-12">
            <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Badge" class="rounded-md">
            <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js Badge" class="rounded-md">
            <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS Badge" class="rounded-md">
            <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma Badge" class="rounded-md">
            <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License: MIT" class="rounded-md">
        </div>
        
        <img src="https://placehold.co/1200x400/1e293b/94a3b8?text=Beautifully+Designed+Gift+Hub" alt="Project Banner" class="w-full rounded-xl shadow-lg mb-12">

        <hr class="border-t border-slate-700 my-12">

        <!-- UI/UX Section -->
        <section class="mb-12">
            <h2 class="text-4xl font-bold mb-6">🎨 UI/UX: The Heart of the Experience</h2>
            <p class="text-slate-300 mb-6">
                As a design-first project, Gift Hub's user experience was meticulously planned to be intuitive, delightful, and stress-free. Our core philosophy was to create an interface that feels both powerful and simple.
            </p>

            <h3 class="text-2xl font-semibold mb-4">User Personas</h3>
            <ul class="list-disc list-inside space-y-2 text-slate-300 mb-6">
                <li><strong class="accent">The Last-Minute Shopper:</strong> Rushes to find a gift, needs a quick and effective search.</li>
                <li><strong class="accent">The Thoughtful Planner:</strong> Plans well in advance, wants to browse by personality type and interests.</li>
                <li><strong class="accent">The Family Giver:</strong> Needs to manage multiple gift lists for different family members and events.</li>
            </ul>

            <h3 class="text-2xl font-semibold mb-4">Design System & Aesthetics</h3>
            <p class="text-slate-300 mb-4">
                We developed a comprehensive design system to ensure consistency and a cohesive visual identity.
            </p>
            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <h4 class="text-xl font-bold mb-2">Color Palette</h4>
                    <ul class="space-y-1 text-slate-300">
                        <li><span class="accent">#2D3748</span> (Slate Blue): Primary Heading & Text</li>
                        <li><span class="accent">#4A5568</span> (Dark Gray): Secondary Text & Elements</li>
                        <li><span class="accent">#38B2AC</span> (Teal): Primary Accent & Interactive Elements</li>
                        <li><span class="accent">#E2E8F0</span> (Light Gray): Background & Borders</li>
                        <li><span class="accent">#FFFFFF</span> (White): Main Backgrounds & Containers</li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-xl font-bold mb-2">Typography</h4>
                    <ul class="space-y-1 text-slate-300">
                        <li><strong class="accent">Headings:</strong> <span style="font-family: Poppins, sans-serif;">Poppins</span> - Bold and modern for strong visual hierarchy.</li>
                        <li><strong class="accent">Body:</strong> <span style="font-family: Inter, sans-serif;">Inter</span> - Clean and highly legible for a comfortable reading experience.</li>
                    </ul>
                </div>
            </div>
        </section>

        <hr class="border-t border-slate-700 my-12">

        <!-- Key Features Section -->
        <section class="mb-12">
            <h2 class="text-4xl font-bold mb-6">🚀 Key Features</h2>
            <ul class="list-disc list-inside space-y-2 text-slate-300">
                <li><strong class="accent">Intelligent Search:</strong> Find gifts by keyword, category, price range, and recipient's interests.</li>
                <li><strong class="accent">Curated Collections:</strong> Explore hand-picked gift lists for holidays, birthdays, and special moments.</li>
                <li><strong class="accent">Wishlist Creation:</strong> Save your favorite gift ideas for later.</li>
                <li><strong class="accent">Responsive Design:</strong> A seamless and beautiful experience on desktop, tablet, and mobile devices.</li>
            </ul>
        </section>

        <hr class="border-t border-slate-700 my-12">

        <!-- Tech Stack Section -->
        <section class="mb-12">
            <h2 class="text-4xl font-bold mb-6">🛠️ Tech Stack</h2>
            <ul class="list-disc list-inside space-y-2 text-slate-300">
                <li><strong class="accent">Frontend:</strong> React, Tailwind CSS</li>
                <li><strong class="accent">Backend:</strong> Node.js, Express.js</li>
                <li><strong class="accent">Database:</strong> MongoDB</li>
                <li><strong class="accent">API:</strong> Custom Gift Recommendation Engine</li>
            </ul>
        </section>

        <hr class="border-t border-slate-700 my-12">

        <!-- Project Statistics Section -->
        <section class="mb-12">
            <h2 class="text-4xl font-bold mb-6">📈 Project Statistics</h2>
            <p class="text-slate-300 mb-4">
                Here are some key development and design metrics for the project.
            </p>
            <div class="overflow-x-auto">
                <table class="min-w-full bg-slate-700 rounded-lg shadow-md mb-8">
                    <thead>
                        <tr class="bg-slate-600">
                            <th class="p-4 text-left font-bold text-slate-200">Metric</th>
                            <th class="p-4 text-left font-bold text-slate-200">Value</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Total Commits</strong></td>
                            <td class="p-4">258</td>
                        </tr>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Total Lines of Code</strong></td>
                            <td class="p-4">12,450</td>
                        </tr>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Pull Requests Merged</strong></td>
                            <td class="p-4">42</td>
                        </tr>
                        <tr class="border-b border-slate-600">
                            <td class="p-4"><strong>Figma Screens</strong></td>
                            <td class="p-4">35+</td>
                        </tr>
                        <tr>
                            <td class="p-4"><strong>Current Version</strong></td>
                            <td class="p-4">v1.2.0</td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <h3 class="text-2xl font-semibold mb-4">Top Contributors</h3>
            <ol class="list-decimal list-inside space-y-1 text-slate-300">
                <li>Jane Doe (150 Commits)</li>
                <li>John Smith (80 Commits)</li>
                <li>Creative Coder (28 Commits)</li>
            </ol>
        </section>

        <hr class="border-t border-slate-700 my-12">

        <!-- Getting Started Section -->
        <section class="mb-12">
            <h2 class="text-4xl font-bold mb-6">⚙️ Getting Started</h2>
            <p class="text-slate-300 mb-4">
                To get a local copy up and running, follow these simple steps.
            </p>
            <pre class="bg-slate-900 text-slate-100 p-6 rounded-lg overflow-x-auto shadow-inner">
                <code class="whitespace-pre-wrap">
# 1. Clone the repository
git clone https://github.com/yourusername/gift-hub.git

# 2. Navigate into the project directory
cd gift-hub

# 3. Install dependencies
npm install

# 4. Start the development server
npm start
                </code>
            </pre>
        </section>

        <hr class="border-t border-slate-700 my-12">

        <!-- Footer Section -->
        <footer class="text-center">
            <div class="mb-6">
                <h3 class="text-2xl font-bold mb-2">📝 License</h3>
                <p class="text-slate-400">
                    This project is licensed under the MIT License. See the <a href="#" class="accent underline">LICENSE</a> file for details.
                </p>
            </div>

            <div class="mb-6">
                <h3 class="text-2xl font-bold mb-2">🙏 Acknowledgements</h3>
                <ul class="space-y-1 text-slate-400">
                    <li><strong class="accent">Design Inspiration:</strong> Dribbble, Behance</li>
                    <li><strong class="accent">Icons:</strong> <a href="https://fontawesome.com/" class="accent underline">Font Awesome</a></li>
                    <li><strong class="accent">Images:</strong> <a href="https://unsplash.com/" class="accent underline">Unsplash</a> for placeholder and sample images</li>
                </ul>
            </div>
        </footer>
    </div>
</body>
</html>
