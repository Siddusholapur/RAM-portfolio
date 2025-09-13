# RAM-portfolio
my introduction 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="Ram's personal portfolio website showcasing skills, projects, and contact information.">
    <title>Ram's Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans antialiased bg-gray-200 text-gray-100">

    <!-- Header -->
    <header class="bg-gray-800 text-white p-4 shadow-md sticky top-0 z-50">
        <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
            <div class="text-2xl font-bold mb-2 md:mb-0">
                Ram <span class="text-blue-500 hover:text-yellow-400">Portfolio</span>
            </div>
            <p class="text-sm text-gray-400 mb-4 md:mb-0">Aspiring Web Developer</p>
            <nav >
                <ul class="flex flex-wrap justify-center space-x-4 text-lg">
                    <li><a href="#home" class="hover:text-red-200 text-blue-400 font-bold">Home</a></li>
                    <li><a href="#about" class="hover:text-red-200 text-blue-400 font-bold">About</a></li>
                    <li><a href="#skills" class="hover:text-red-200 text-blue-400 font-bold">Skills</a></li>
                    <li><a href="#projects" class="hover:text-red-200 text-blue-400 font-bold">Projects</a></li>
                    <li><a href="#contact" class="hover:text-red-200 text-blue-400 font-bold">Contact</a></li>
                </ul>
             </nav>
        </div>
    </header>

    <main class="container mx-auto mt-8 p-4">

        <!-- Hero Section -->
        <section id="home" class="flex flex-col md:flex-row items-center justify-center bg-white p-8 rounded-lg shadow-lg mb-12 text-center md:text-left">
            <img src="my img.jpg" alt="Ram's Photo" class="rounded-full w-48 h-48 object-cover mb-6 md:mb-0 md:mr-8 border-4 border-yellow-400">
            <div>
                <h1 class="text-5xl font-extrabold text-gray-900 mb-4">Hello, I'm Ram!</h1>
                <p class="text-xl text-gray-700 leading-relaxed max-w-2xl">
                    A passionate web developer eager to build engaging and user-friendly web experiences. I love bringing ideas to life through code.
                </p>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="bg-white  p-100 rounded-lg shadow-lg mb-12">
            <h2 class="text-4xl font-bold text-gray-900 mb-6 text-center">About Me</h2>
            <div class="max-w-3xl mx-auto">
                <p class="text-lg text-gray-900 leading-relaxed mb-6">
                    I'm Ram, a budding web developer with a strong interest in front-end technologies. My journey into web development started with a curiosity about how websites are built, and it quickly grew into a passion for creating beautiful and functional user interfaces. I enjoy solving problems and continuously learning new tools and techniques to improve my craft.
                </p>
                <h3 class="text-2xl font-semibold text-gray-800 mb-4">Hobbies & Interests:</h3>
                <ul class="list-disc list-inside text-lg text-gray-700 space-y-2">
                    <li>Reading sci-fi novels</li>
                    <li>Hiking and exploring nature trails</li>
                    <li>Playing acoustic guitar</li>
                    <li>Learning new programming languages</li>
                    <li>Photography</li>
                </ul>

                <!-- Resume Button -->
                   <div class="mt-6 text-center">
                     <a href="ram.resume.pdf" download 
                      class="inline-block bg-green-500 text-white px-6 py-3 rounded-lg hover:bg-green-600 transition duration-300 font-medium">
                        Download Resume
                      </a>
                   </div>

            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="bg-white p-8 rounded-lg shadow-lg mb-12">
            <h2 class="text-4xl font-bold text-gray-900 mb-6 text-center">My Skills</h2>
            <div class="overflow-x-auto">
                <table class="min-w-full bg-white border border-gray-100 rounded-lg">
                    <thead>
                        <tr class="bg-gray-100 border-b border-gray-300">
                            <th class="py-3 px-6 text-left text-sm font-medium text-gray-700 uppercase tracking-wider">Skill</th>
                            <th class="py-3 px-6 text-left text-sm font-medium text-gray-700 uppercase tracking-wider">Level</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-gray-200">
                        <tr>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-800">HTML</td>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-600">Expert</td>
                        </tr>
                        <tr>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-800">CSS</td>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-600">Intermediate</td>
                        </tr>
                        <tr>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-800">JavaScript</td>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-600">Beginner</td>
                        </tr>
                        <tr>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-800">Git & GitHub</td>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-600">Intermediate</td>
                        </tr>
                        <tr>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-800">Responsive Design</td>
                            <td class="py-4 px-6 whitespace-nowrap text-lg text-gray-600">Intermediate</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="bg-white p-8 rounded-lg shadow-lg mb-12">
            <h2 class="text-4xl font-bold text-gray-900 mb-8 text-center">My Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-gray-50 border border-gray-300 rounded-lg shadow-md overflow-hidden">
                    <img src="e-commence.jpeg" alt="Project 1 Image" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-3">E-commerce Product Page</h3>
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            A responsive product page for an online store, featuring product details, image gallery, and add-to-cart functionality. Built with HTML and Tailwind CSS.
                        </p>
                        <a href="#" class="inline-block bg-blue-500 text-white px-6 py-3 rounded-lg hover:bg-green-600 transition duration-300 font-medium">View Project</a>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="bg-gray-50 border border-gray-200 rounded-lg shadow-md overflow-hidden">
                    <img src="to-do.jpeg" alt="Project 2 Image" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-3">Interactive To-Do List</h3>
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            A simple yet interactive to-do list application allowing users to add, delete, and mark tasks as complete. Focus on clean UI/UX. (Frontend only)
                        </p>
                        <a href="#" class="inline-block bg-blue-500 text-white px-6 py-3 rounded-lg hover:bg-green-600 transition duration-300 font-medium">View Project</a>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="bg-gray-50 border border-gray-200 rounded-lg shadow-md overflow-hidden">
                    <img src="images.jpeg" alt="Project 3 Image" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-3">Personal Blog Layout</h3>
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            A clean and modern blog layout designed for readability and ease of navigation. Features responsive design for various devices.
                        </p>
                        <a href="#" class="inline-block bg-blue-500 text-white px-6 py-3 rounded-lg hover:bg-green-600 transition duration-300 font-medium">View Project</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="bg-white p-8 rounded-lg shadow-lg mb-12">  
            <h2 class="text-4xl font-bold text-gray-900 mb-6 text-center">Contact Me</h2>
            <form action="https://formspree.io/f/yourFormID" method="POST" class="max-w-xl mx-auto space-y-6">
                <div>
                    <label for="name" class="block text-lg font-medium text-gray-700 mb-2">Name</label>
                    <input type="text" id="name" name="name" class="mt-1 block w-full px-4 py-3 border border-gray-400 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-lg text-gray-800" placeholder="Your Name" required>
                </div>
                <div>
                    <label for="email" class="block text-lg font-medium text-gray-700 mb-2">Email</label>
                    <input type="email" id="email" name="email" class="mt-1 block w-full px-4 py-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text- lg text-gray-800" placeholder="your.email@example.com" required>
                </div>
                <div>
                    <label for="message" class="block text-lg font-medium text-gray-700 mb-2">Message</label>
                    <textarea id="message" name="message" rows="6" class="mt-1 block w-full px-4 py-3 border border-gray-400 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-lg text-gray-800" placeholder="Your message..." required></textarea>
                </div>
                <div>
                    <button type="submit" class="w-full bg-blue-600 text-white py-3 px-6 rounded-md hover:bg-yellow-400 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 text-lg font-semibold transition duration-300">Send Message</button>
                </div>
            </form>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white p-6 mt-12">
        <div class="container mx-auto text-center">
            <div class="flex justify-center space-x-6 mb-4">
                <a href="#" class="text-gray-300 hover:text-blue-400 transition duration-300 text-lg">Facebook</a>
                <a href="www.linkedin.com/in/siddaramsholapur" class="text-gray-300 hover:text-blue-400 transition duration-300 text-lg">LinkedIn</a>
                <a href="https://github.com/Siddusholapur/RAM-portfolio.git" class="text-gray-300 hover:text-blue-400 transition duration-300 text-lg">GitHub</a>
            </div>      
            <p class="text-gray-400 text-sm">&copy; 2025 Ram. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
