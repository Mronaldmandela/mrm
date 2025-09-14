
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MRM - Web Developer & Designer</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8fafc;
        }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #8b5cf6);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            left: 0;
            background-color: #3b82f6;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <span class="text-xl font-bold gradient-text">MRM</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-blue-600">Home</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-blue-600">About</a>
                    <a href="#services" class="nav-link text-gray-700 hover:text-blue-600">Services</a>
                    <a href="#projects" class="nav-link text-gray-700 hover:text-blue-600">Projects</a>
                    <a href="#contact" class="nav-link text-gray-700 hover:text-blue-600">Contact</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="menu-toggle" class="text-gray-700">
                        <i data-feather="menu"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white pb-3 px-4">
            <a href="#home" class="block py-2 text-gray-700 hover:text-blue-600">Home</a>
            <a href="#about" class="block py-2 text-gray-700 hover:text-blue-600">About</a>
            <a href="#services" class="block py-2 text-gray-700 hover:text-blue-600">Services</a>
            <a href="#projects" class="block py-2 text-gray-700 hover:text-blue-600">Projects</a>
            <a href="#contact" class="block py-2 text-gray-700 hover:text-blue-600">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="py-20 bg-gradient-to-r from-blue-50 to-purple-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0" data-aos="fade-right">
                    <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">
                        Hi, I'm <span class="gradient-text">Ronald Mandela</span>
                    </h1>
                    <h2 class="text-2xl md:text-3xl font-semibold text-gray-600 mb-6">
                        Web Developer & Designer
                    </h2>
                    <p class="text-gray-600 mb-8 text-lg">
                        I create beautiful, functional websites that help businesses grow and succeed in the digital world.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#contact" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-lg font-medium transition duration-300">
                            Get In Touch
                        </a>
                        <a href="#projects" class="border border-blue-600 text-blue-600 hover:bg-blue-50 px-6 py-3 rounded-lg font-medium transition duration-300">
                            View Work
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center" data-aos="fade-left">
                    <div class="relative">
                        <div class="w-64 h-64 md:w-80 md:h-80 bg-blue-100 rounded-full overflow-hidden shadow-xl">
                            <img src="http://static.photos/people/640x360/42" alt="Ronald Mandela" class="w-full h-full object-cover">
                        </div>
                        <div class="absolute -bottom-5 -right-5 bg-white p-4 rounded-lg shadow-md">
                            <div class="flex items-center">
                                <div class="bg-blue-100 p-2 rounded-full mr-3">
                                    <i data-feather="code" class="text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="text-sm text-gray-500">Currently working on</p>
                                    <p class="font-medium">New Project</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">About Me</h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-500 mx-auto"></div>
            </div>
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/3 mb-10 md:mb-0 flex justify-center" data-aos="fade-right">
                    <div class="relative">
                        <div class="w-64 h-64 bg-gradient-to-br from-blue-100 to-purple-100 rounded-lg overflow-hidden shadow-lg">
                            <img src="http://static.photos/office/640x360/23" alt="About Ronald" class="w-full h-full object-cover">
                        </div>
                        <div class="absolute -bottom-5 -left-5 bg-white p-3 rounded-lg shadow-md">
                            <div class="flex items-center">
                                <div class="bg-purple-100 p-2 rounded-full mr-2">
                                    <i data-feather="award" class="text-purple-600"></i>
                                </div>
                                <div>
                                    <p class="text-xs text-gray-500">Years of</p>
                                    <p class="font-medium">Experience</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="md:w-2/3 md:pl-12" data-aos="fade-left">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6">Who I Am</h3>
                    <p class="text-gray-600 mb-6">
                        I'm Ronald Mandela, a passionate web developer and designer with expertise in creating modern, responsive websites and web applications. With a keen eye for design and a strong technical background, I bridge the gap between aesthetics and functionality.
                    </p>
                    <p class="text-gray-600 mb-8">
                        My approach combines technical expertise with creative problem-solving to deliver solutions that not only look great but also perform exceptionally well across all devices and platforms.
                    </p>
                    <div class="grid grid-cols-2 gap-6 mb-8">
                        <div class="flex items-center">
                            <div class="bg-blue-100 p-2 rounded-full mr-4">
                                <i data-feather="check" class="text-blue-600"></i>
                            </div>
                            <span class="text-gray-700">Responsive Design</span>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-blue-100 p-2 rounded-full mr-4">
                                <i data-feather="check" class="text-blue-600"></i>
                            </div>
                            <span class="text-gray-700">Clean Code</span>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-blue-100 p-2 rounded-full mr-4">
                                <i data-feather="check" class="text-blue-600"></i>
                            </div>
                            <span class="text-gray-700">SEO Friendly</span>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-blue-100 p-2 rounded-full mr-4">
                                <i data-feather="check" class="text-blue-600"></i>
                            </div>
                            <span class="text-gray-700">Fast Loading</span>
                        </div>
                    </div>
                    <a href="#contact" class="inline-flex items-center text-blue-600 hover:text-blue-800 font-medium">
                        Contact Me <i data-feather="arrow-right" class="ml-2"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">My Services</h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-500 mx-auto"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="100">
                    <div class="bg-blue-100 p-4 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <i data-feather="code" class="text-blue-600 w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Web Development</h3>
                    <p class="text-gray-600">
                        Custom website development with clean, efficient code that ensures fast loading times and optimal performance across all devices.
                    </p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="200">
                    <div class="bg-purple-100 p-4 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <i data-feather="layout" class="text-purple-600 w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">UI/UX Design</h3>
                    <p class="text-gray-600">
                        Intuitive and beautiful user interfaces designed to enhance user experience and drive engagement with your brand.
                    </p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="300">
                    <div class="bg-green-100 p-4 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <i data-feather="smartphone" class="text-green-600 w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Responsive Design</h3>
                    <p class="text-gray-600">
                        Websites that look and function perfectly on any device, from desktop computers to smartphones and tablets.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Featured Projects</h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-500 mx-auto"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="project-card bg-white rounded-xl overflow-hidden shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="100">
                    <div class="h-48 overflow-hidden">
                        <img src="http://static.photos/technology/640x360/1" alt="Project 1" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">E-commerce Website</h3>
                        <p class="text-gray-600 mb-4">
                            A fully responsive e-commerce platform with secure payment integration and inventory management.
                        </p>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-blue-100 text-blue-800 text-xs px-3 py-1 rounded-full">HTML</span>
                            <span class="bg-purple-100 text-purple-800 text-xs px-3 py-1 rounded-full">CSS</span>
                            <span class="bg-yellow-100 text-yellow-800 text-xs px-3 py-1 rounded-full">JavaScript</span>
                        </div>
                    </div>
                </div>
                <div class="project-card bg-white rounded-xl overflow-hidden shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="200">
                    <div class="h-48 overflow-hidden">
                        <img src="http://static.photos/education/640x360/2" alt="Project 2" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Learning Platform</h3>
                        <p class="text-gray-600 mb-4">
                            An interactive online learning platform with course management and student progress tracking.
                        </p>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-blue-100 text-blue-800 text-xs px-3 py-1 rounded-full">React</span>
                            <span class="bg-green-100 text-green-800 text-xs px-3 py-1 rounded-full">Node.js</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="project-card bg-white rounded-xl overflow-hidden shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="300">
                    <div class="h-48 overflow-hidden">
                        <img src="http://static.photos/health/640x360/3" alt="Project 3" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Health App</h3>
                        <p class="text-gray-600 mb-4">
                            A mobile-friendly health tracking application with data visualization and reminder features.
                        </p>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-blue-100 text-blue-800 text-xs px-3 py-1 rounded-full">Vue.js</span>
                            <span class="bg-indigo-100 text-indigo-800 text-xs px-3 py-1 rounded-full">Firebase</span>
                            <span class="bg-pink-100 text-pink-800 text-xs px-3 py-1 rounded-full">Chart.js</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12" data-aos="fade-up">
                <a href="#" class="inline-flex items-center px-6 py-3 border border-blue-600 text-blue-600 hover:bg-blue-50 rounded-lg font-medium transition duration-300">
                    View All Projects <i data-feather="arrow-right" class="ml-2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gradient-to-r from-blue-50 to-purple-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Get In Touch</h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-500 mx-auto"></div>
            </div>
            <div class="flex flex-col md:flex-row">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-8" data-aos="fade-right">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6">Let's Talk About Your Project</h3>
                    <p class="text-gray-600 mb-8">
                        Have a project in mind or want to discuss potential collaboration? Feel free to reach out. I'm always open to discussing new opportunities and ideas.
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i data-feather="mail" class="text-blue-600"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">Email me at</p>
                                <a href="mailto:contact@example.com" class="font-medium text-gray-800 hover:text-blue-600">contact@example.com</a>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-purple-100 p-3 rounded-full mr-4">
                                <i data-feather="phone" class="text-purple-600"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">Call me at</p>
                                <a href="tel:+1234567890" class="font-medium text-gray-800 hover:text-purple-600">+123 456 7890</a>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-green-100 p-3 rounded-full mr-4">
                                <i data-feather="map-pin" class="text-green-600"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-500">Find me at</p>
                                <p class="font-medium text-gray-800">123 Design Street, Creative City</p>
                            </div>
                        </div>
                    </div>
                    <div class="mt-8 flex space-x-4">
                        <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white p-3 rounded-full">
                            <i data-feather="facebook"></i>
                        </a>
                        <a href="#" class="bg-blue-400 hover:bg-blue-500 text-white p-3 rounded-full">
                            <i data-feather="twitter"></i>
                        </a>
                        <a href="#" class="bg-pink-600 hover:bg-pink-700 text-white p-3 rounded-full">
                            <i data-feather="instagram"></i>
                        </a>
                        <a href="#" class="bg-blue-700 hover:bg-blue-800 text-white p-3 rounded-full">
                            <i data-feather="linkedin"></i>
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2" data-aos="fade-left">
                    <form class="bg-white p-8 rounded-xl shadow-sm">
                        <div class="mb-6">
                            <label for="name" class="block text-gray-700 font-medium mb-2">Your Name</label>
                            <input type="text" id="name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition duration-300" placeholder="John Doe">
                        </div>
                        <div class="mb-6">
                            <label for="email" class="block text-gray-700 font-medium mb-2">Email Address</label>
                            <input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition duration-300" placeholder="john@example.com">
                        </div>
                        <div class="mb-6">
                            <label for="subject" class="block text-gray-700 font-medium mb-2">Subject</label>
                            <input type="text" id="subject" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition duration-300" placeholder="Project Inquiry">
                        </div>
                        <div class="mb-6">
                            <label for="message" class="block text-gray-700 font-medium mb-2">Message</label>
                            <textarea id="message" rows="5" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition duration-300" placeholder="Tell me about your project..."></textarea>
                        </div>
                        <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-lg font-medium transition duration-300">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <span class="text-2xl font-bold gradient-text">MRM</span>
                    <p class="text-gray-400 mt-2">Creating digital experiences that matter.</p>
                </div>
                <div class="flex flex-col md:flex-row md:space-x-8 space-y-4 md:space-y-0">
                    <a href="#home" class="text-gray-400 hover:text-white transition duration-300">Home</a>
                    <a href="#about" class="text-gray-400 hover:text-white transition duration-300">About</a>
                    <a href="#services" class="text-gray-400 hover:text-white transition duration-300">Services</a>
                    <a href="#projects" class="text-gray-400 hover:text-white transition duration-300">Projects</a>
                    <a href="#contact" class="text-gray-400 hover:text-white transition duration-300">Contact</a>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm mb-4 md:mb-0">
                    &copy; 2023 Ronald Mandela. All rights reserved.
                </p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i data-feather="facebook"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i data-feather="twitter"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i data-feather="instagram"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i data-feather="linkedin"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i data-feather="github"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('menu-toggle').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking a link
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', function() {
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });

        // Initialize AOS
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });

        // Feather icons
        feather.replace();
    </script>
</body>
</html>
