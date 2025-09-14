<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Malaki Ronald Mandela | Academic Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }
        .hero-gradient {
            background: linear-gradient(135deg, #e0e7ff 0%, #a5b4fc 100%);
        }
        .project-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.15), 0 10px 10px -5px rgba(0, 0, 0, 0.05);
        }
        .nav-link {
            position: relative;
            transition: color 0.3s ease;
        }
        .nav-link:after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: #4f46e5;
            transition: width 0.3s ease;
        }
        .nav-link:hover:after, .nav-link.active-nav:after {
            width: 100%;
        }
        .tabs-container {
            overflow-x: auto;
            scrollbar-width: none;
            -ms-overflow-style: none;
        }
        .tabs-container::-webkit-scrollbar {
            display: none;
        }
        .tabs {
            display: flex;
            min-width: max-content;
        }
        .tab {
            white-space: nowrap;
        }
        @media (min-width: 768px) {
            .tabs-container {
                overflow-x: visible;
            }
            .tabs {
                min-width: auto;
            }
        }
        /* Accessibility Improvements */
        .sr-only {
            position: absolute;
            width: 1px;
            height: 1px;
            padding: 0;
            margin: -1px;
            overflow: hidden;
            clip: rect(0, 0, 0, 0);
            border: 0;
        }
        /* Dark Mode Support */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #1f2937;
                color: #f3f4f6;
            }
            .hero-gradient {
                background: linear-gradient(135deg, #374151 0%, #4b5563 100%);
            }
            .project-card, .publication-item, .bg-white {
                background-color: #374151;
            }
            .bg-gray-50 {
                background-color: #4b5563;
            }
            .text-gray-600 {
                color: #d1d5db;
            }
            .text-gray-800 {
                color: #f3f4f6;
            }
            .text-gray-700 {
                color: #d1d5db;
            }
            nav {
                background-color: #1f2937;
            }
            footer {
                background-color: #111827;
            }
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- Navigation -->
    <nav class="fixed w-full bg-white bg-opacity-90 backdrop-filter backdrop-blur-sm z-50 shadow-sm dark:bg-gray-800 dark:bg-opacity-90">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex-shrink-0 flex items-center">
                    <span class="text-xl font-bold text-indigo-600 dark:text-indigo-400">Malaki R. Mandela</span>
                </div>
                <div class="hidden md:block">
                    <div class="tabs-container">
                        <div class="tabs ml-10 items-baseline space-x-4">
                            <a href="#home" class="tab nav-link active-nav px-3 py-2 text-sm font-medium text-indigo-600 dark:text-indigo-400">Home</a>
                            <a href="#about" class="tab nav-link px-3 py-2 text-sm font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">About</a>
                            <a href="#research" class="tab nav-link px-3 py-2 text-sm font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">Research</a>
                            <a href="#publications" class="tab nav-link px-3 py-2 text-sm font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">Publications</a>
                            <a href="#contact" class="tab nav-link px-3 py-2 text-sm font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">Contact</a>
                        </div>
                    </div>
                </div>
                <div class="md:hidden">
                    <button type="button" class="mobile-menu-button inline-flex items-center justify-center p-2 rounded-md text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400 focus:outline-none" aria-label="Toggle mobile menu">
                        <i data-feather="menu"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>
    <!-- Mobile Menu -->
    <div class="mobile-menu hidden md:hidden fixed inset-0 z-40 bg-white bg-opacity-95 backdrop-filter backdrop-blur-sm pt-16 dark:bg-gray-800 dark:bg-opacity-95">
        <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
            <a href="#home" class="block px-3 py-2 text-base font-medium text-indigo-600 dark:text-indigo-400">Home</a>
            <a href="#about" class="block px-3 py-2 text-base font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">About</a>
            <a href="#research" class="block px-3 py-2 text-base font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">Research</a>
            <a href="#publications" class="block px-3 py-2 text-base font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">Publications</a>
            <a href="#contact" class="block px-3 py-2 text-base font-medium text-gray-700 hover:text-indigo-600 dark:text-gray-300 dark:hover:text-indigo-400">Contact</a>
        </div>
    </div>
    <!-- Hero Section -->
    <section id="home" class="hero-gradient min-h-screen flex items-center pt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div data-aos="fade-right" data-aos-duration="800">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-800 dark:text-gray-100 mb-6">
                        Malaki Ronald <span class="text-indigo-600 dark:text-indigo-400">Mandela</span>
                    </h1>
                    <h2 class="text-xl md:text-2xl text-gray-600 dark:text-gray-300 mb-8">
                        Academic Researcher | Scholar | Thought Leader
                    </h2>
                    <p class="text-gray-600 dark:text-gray-300 mb-8 max-w-lg">
                        Exploring the frontiers of knowledge through rigorous research and interdisciplinary collaboration.
                        My work focuses on addressing complex challenges at the intersection of technology, society, and policy.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#research" class="px-6 py-3 bg-indigo-600 text-white font-medium rounded-md hover:bg-indigo-700 dark:bg-indigo-500 dark:hover:bg-indigo-600 transition duration-300">
                            View Research
                        </a>
                        <a href="#contact" class="px-6 py-3 border border-gray-300 text-gray-700 dark:text-gray-300 dark:border-gray-600 font-medium rounded-md hover:bg-gray-100 dark:hover:bg-gray-700 transition duration-300">
                            Contact Me
                        </a>
                    </div>
                </div>
                <div data-aos="fade-left" data-aos-duration="800" class="flex justify-center">
                    <div class="relative">
                        <div class="w-64 h-64 md:w-80 md:h-80 lg:w-96 lg:h-96 rounded-full overflow-hidden border-4 border-white dark:border-gray-800 shadow-xl">
                            <img src="http://static.photos/education/640x360/42" alt="Malaki Ronald Mandela" class="w-full h-full object-cover">
                        </div>
                        <div class="absolute -bottom-4 -right-4 bg-white dark:bg-gray-800 p-4 rounded-lg shadow-lg">
                            <div class="text-center">
                                <p class="text-sm font-medium text-gray-700 dark:text-gray-300">Currently</p>
                                <p class="text-lg font-bold text-indigo-600 dark:text-indigo-400">PhD Candidate</p>
                                <p class="text-sm text-gray-600 dark:text-gray-400">EBS Universität für Wirtschaft und Recht</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section id="about" class="py-20 bg-white dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 dark:text-gray-100 mb-4">About Me</h2>
                <div class="w-20 h-1 bg-indigo-600 dark:bg-indigo-400 mx-auto"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div data-aos="fade-right">
                    <h3 class="text-2xl font-bold text-gray-800 dark:text-gray-100 mb-6">Academic Journey</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-6">
                        I am a passionate researcher with a multidisciplinary background spanning computer science,
                        social sciences, and public policy. My academic journey has been driven by a curiosity to
                        understand how technology shapes and is shaped by society.
                    </p>
                    <p class="text-gray-600 dark:text-gray-300 mb-6">
                        Currently pursuing my PhD at EBS Universität für Wirtschaft und Recht, I focus on Applied Economics (Health, Labor Economics, Gender) from a development economics point of view.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <span class="px-4 py-2 bg-gray-100 dark:bg-gray-700 text-gray-700 dark:text-gray-300 rounded-full text-sm font-medium">Artificial Intelligence</span>
                        <span class="px-4 py-2 bg-gray-100 dark:bg-gray-700 text-gray-700 dark:text-gray-300 rounded-full text-sm font-medium">Ethics</span>
                        <span class="px-4 py-2 bg-gray-100 dark:bg-gray-700 text-gray-700 dark:text-gray-300 rounded-full text-sm font-medium">Social Justice</span>
                        <span class="px-4 py-2 bg-gray-100 dark:bg-gray-700 text-gray-700 dark:text-gray-300 rounded-full text-sm font-medium">Policy</span>
                    </div>
                </div>
                <div data-aos="fade-left">
                    <div class="bg-gray-50 dark:bg-gray-700 p-8 rounded-xl">
                        <h3 class="text-xl font-bold text-gray-800 dark:text-gray-100 mb-6">Education</h3>
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="flex-shrink-0 h-12 w-12 rounded-full bg-indigo-100 dark:bg-indigo-900 flex items-center justify-center mr-4">
                                    <i data-feather="book" class="text-indigo-600 dark:text-indigo-400"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-800 dark:text-gray-100">PhD in Computer Science</h4>
                                    <p class="text-gray-600 dark:text-gray-300">EBS Universität für Wirtschaft und Recht | 2020-Present</p>
                                    <p class="text-gray-500 dark:text-gray-400 text-sm mt-1">Focus: AI Ethics and Social Impact</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 h-12 w-12 rounded-full bg-indigo-100 dark:bg-indigo-900 flex items-center justify-center mr-4">
                                    <i data-feather="book" class="text-indigo-600 dark:text-indigo-400"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-800 dark:text-gray-100">MSc in Social Data Science</h4>
                                    <p class="text-gray-600 dark:text-gray-300">University of Oxford | 2018-2019</p>
                                    <p class="text-gray-500 dark:text-gray-400 text-sm mt-1">Distinction</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 h-12 w-12 rounded-full bg-indigo-100 dark:bg-indigo-900 flex items-center justify-center mr-4">
                                    <i data-feather="book" class="text-indigo-600 dark:text-indigo-400"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-800 dark:text-gray-100">BA in Philosophy & Computer Science</h4>
                                    <p class="text-gray-600 dark:text-gray-300">Harvard University | 2014-2018</p>
                                    <p class="text-gray-500 dark:text-gray-400 text-sm mt-1">Summa Cum Laude</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Research Section -->
    <section id="research" class="py-20 bg-gray-50 dark:bg-gray-700">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 dark:text-gray-100 mb-4">Research Projects</h2>
                <div class="w-20 h-1 bg-indigo-600 dark:bg-indigo-400 mx-auto"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="project-card bg-white dark:bg-gray-800 rounded-xl overflow-hidden shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="100">
                    <div class="h-48 overflow-hidden">
                        <img src="http://static.photos/technology/640x360/1" alt="AI Ethics Framework" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-800 dark:text-gray-100 mb-2">Ethical AI Framework</h3>
                        <p class="text-gray-600 dark:text-gray-300 mb-4">
                            Developing a comprehensive framework for assessing the societal impact of AI systems with a focus on fairness and accountability.
                        </p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm font-medium text-indigo-600 dark:text-indigo-400">Ongoing</span>
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                Read more <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="project-card bg-white dark:bg-gray-800 rounded-xl overflow-hidden shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="200">
                    <div class="h-48 overflow-hidden">
                        <img src="http://static.photos/science/640x360/2" alt="Algorithmic Bias Study" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-800 dark:text-gray-100 mb-2">Algorithmic Bias in Healthcare</h3>
                        <p class="text-gray-600 dark:text-gray-300 mb-4">
                            Investigating racial and gender biases in clinical decision support systems and proposing mitigation strategies.
                        </p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm font-medium text-indigo-600 dark:text-indigo-400">Published 2022</span>
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                Read more <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="project-card bg-white dark:bg-gray-800 rounded-xl overflow-hidden shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="300">
                    <div class="h-48 overflow-hidden">
                        <img src="http://static.photos/education/640x360/3" alt="Digital Literacy" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-800 dark:text-gray-100 mb-2">Digital Literacy in Africa</h3>
                        <p class="text-gray-600 dark:text-gray-300 mb-4">
                            Evaluating the impact of digital literacy programs on economic empowerment in Sub-Saharan Africa.
                        </p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm font-medium text-indigo-600 dark:text-indigo-400">Published 2021</span>
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                Read more <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12" data-aos="fade-up">
                <a href="#" class="px-6 py-3 border border-gray-300 text-gray-700 dark:text-gray-300 dark:border-gray-600 font-medium rounded-md hover:bg-gray-100 dark:hover:bg-gray-700 transition duration-300 inline-flex items-center">
                    View All Projects <i data-feather="arrow-right" class="ml-2 w-4 h-4"></i>
                </a>
            </div>
        </div>
    </section>
    <!-- Publications Section -->
    <section id="publications" class="py-20 bg-white dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 dark:text-gray-100 mb-4">Publications</h2>
                <div class="w-20 h-1 bg-indigo-600 dark:bg-indigo-400 mx-auto"></div>
            </div>
            <div class="space-y-8">
                <!-- Publication 1 -->
                <div class="publication-item bg-gray-50 dark:bg-gray-700 p-6 rounded-lg hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between">
                        <div class="mb-4 md:mb-0">
                            <h3 class="text-xl font-bold text-gray-800 dark:text-gray-100 mb-1">Fairness in Machine Learning: A Critical Review</h3>
                            <p class="text-gray-600 dark:text-gray-300 mb-2">Journal of Artificial Intelligence Research, 2023</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">AI Ethics</span>
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Fairness</span>
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Bias Mitigation</span>
                            </div>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                <i data-feather="file-text" class="mr-1 w-4 h-4"></i> PDF
                            </a>
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                <i data-feather="external-link" class="mr-1 w-4 h-4"></i> DOI
                            </a>
                        </div>
                    </div>
                </div>
                <!-- Publication 2 -->
                <div class="publication-item bg-gray-50 dark:bg-gray-700 p-6 rounded-lg hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="200">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between">
                        <div class="mb-4 md:mb-0">
                            <h3 class="text-xl font-bold text-gray-800 dark:text-gray-100 mb-1">The Digital Divide in Post-Pandemic Education</h3>
                            <p class="text-gray-600 dark:text-gray-300 mb-2">Nature Human Behaviour, 2022</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Education</span>
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Digital Divide</span>
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Policy</span>
                            </div>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                <i data-feather="file-text" class="mr-1 w-4 h-4"></i> PDF
                            </a>
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                <i data-feather="external-link" class="mr-1 w-4 h-4"></i> DOI
                            </a>
                        </div>
                    </div>
                </div>
                <!-- Publication 3 -->
                <div class="publication-item bg-gray-50 dark:bg-gray-700 p-6 rounded-lg hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="300">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between">
                        <div class="mb-4 md:mb-0">
                            <h3 class="text-xl font-bold text-gray-800 dark:text-gray-100 mb-1">Decolonizing AI: Perspectives from the Global South</h3>
                            <p class="text-gray-600 dark:text-gray-300 mb-2">AI & Society, 2021</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Decolonization</span>
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Global South</span>
                                <span class="px-2 py-1 bg-indigo-100 dark:bg-indigo-900 text-indigo-800 dark:text-indigo-300 text-xs rounded-full">Cultural Bias</span>
                            </div>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                <i data-feather="file-text" class="mr-1 w-4 h-4"></i> PDF
                            </a>
                            <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 flex items-center">
                                <i data-feather="external-link" class="mr-1 w-4 h-4"></i> DOI
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12" data-aos="fade-up">
                <a href="#" class="px-6 py-3 border border-gray-300 text-gray-700 dark:text-gray-300 dark:border-gray-600 font-medium rounded-md hover:bg-gray-100 dark:hover:bg-gray-700 transition duration-300 inline-flex items-center">
                    View All Publications <i data-feather="arrow-right" class="ml-2 w-4 h-4"></i>
                </a>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-indigo-50 dark:bg-indigo-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl font-bold text-gray-800 dark:text-gray-100 mb-4">Get In Touch</h2>
                <div class="w-20 h-1 bg-indigo-600 dark:bg-indigo-400 mx-auto"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div data-aos="fade-right">
                    <h3 class="text-2xl font-bold text-gray-800 dark:text-gray-100 mb-6">Contact Information</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-8">
                        I'm always open to discussing research collaborations, speaking engagements, or potential projects.
                        Feel free to reach out through any of the channels below.
                    </p>
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 h-12 w-12 rounded-full bg-white dark:bg-gray-800 flex items-center justify-center mr-4 shadow-sm">
                                <i data-feather="mail" class="text-indigo-600 dark:text-indigo-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800 dark:text-gray-100">Email</h4>
                                <a href="mailto:malaki.mandela@stanford.edu" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300">malaki.mandela@stanford.edu</a>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 h-12 w-12 rounded-full bg-white dark:bg-gray-800 flex items-center justify-center mr-4 shadow-sm">
                                <i data-feather="map-pin" class="text-indigo-600 dark:text-indigo-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800 dark:text-gray-100">Location</h4>
                                <p class="text-gray-600 dark:text-gray-300">EBS Universität für Wirtschaft und Recht, Economics Department</p>
                                <p class="text-gray-600 dark:text-gray-300">Stanford, CA 94305, USA</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 h-12 w-12 rounded-full bg-white dark:bg-gray-800 flex items-center justify-center mr-4 shadow-sm">
                                <i data-feather="calendar" class="text-indigo-600 dark:text-indigo-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800 dark:text-gray-100">Office Hours</h4>
                                <p class="text-gray-600 dark:text-gray-300">By appointment only</p>
                                <a href="#" class="text-indigo-600 dark:text-indigo-400 hover:text-indigo-800 dark:hover:text-indigo-300 text-sm flex items-center mt-1">
                                    Schedule a meeting <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="mt-8">
                        <h4 class="font-bold text-gray-800 dark:text-gray-100 mb-4">Connect With Me</h4>
                        <div class="flex space-x-4">
                            <a href="#" class="h-10 w-10 rounded-full bg-white dark:bg-gray-800 flex items-center justify-center shadow-sm hover:bg-indigo-100 dark:hover:bg-indigo-900 transition duration-300">
                                <i data-feather="twitter" class="text-indigo-600 dark:text-indigo-400"></i>
                            </a>
                            <a href="#" class="h-10 w-10 rounded-full bg-white dark:bg-gray-800 flex items-center justify-center shadow-sm hover:bg-indigo-100 dark:hover:bg-indigo-900 transition duration-300">
                                <i data-feather="linkedin" class="text-indigo-600 dark:text-indigo-400"></i>
                            </a>
                            <a href="#" class="h-10 w-10 rounded-full bg-white dark:bg-gray-800 flex items-center justify-center shadow-sm hover:bg-indigo-100 dark:hover:bg-indigo-900 transition duration-300">
                                <i data-feather="github" class="text-indigo-600 dark:text-indigo-400"></i>
                            </a>
                            <a href="#" class="h-10 w-10 rounded-full bg-white dark:bg-gray-800 flex items-center justify-center shadow-sm hover:bg-indigo-100 dark:hover:bg-indigo-900 transition duration-300">
                                <i data-feather="google-scholar" class="text-indigo-600 dark:text-indigo-400"></i>
                            </a>
                        </div>
                    </div>
                </div>
                <div data-aos="fade-left">
                    <div class="bg-white dark:bg-gray-800 p-8 rounded-xl shadow-sm">
                        <h3 class="text-2xl font-bold text-gray-800 dark:text-gray-100 mb-6">Send Me a Message</h3>
                        <div id="contact-form">
                            <div class="mb-6">
                                <label for="name" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">Name</label>
                                <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-md focus:outline-none focus:ring-2 focus:ring-indigo-500 dark:focus:ring-indigo-400 focus:border-indigo-500 dark:focus:border-indigo-400" required aria-required="true">
                            </div>
                            <div class="mb-6">
                                <label for="email" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">Email</label>
                                <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-md focus:outline-none focus:ring-2 focus:ring-indigo-500 dark:focus:ring-indigo-400 focus:border-indigo-500 dark:focus:border-indigo-400" required aria-required="true">
                            </div>
                            <div class="mb-6">
                                <label for="subject" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">Subject</label>
                                <input type="text" id="subject" class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-md focus:outline-none focus:ring-2 focus:ring-indigo-500 dark:focus:ring-indigo-400 focus:border-indigo-500 dark:focus:border-indigo-400" required aria-required="true">
                            </div>
                            <div class="mb-6">
                                <label for="message" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-1">Message</label>
                                <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-md focus:outline-none focus:ring-2 focus:ring-indigo-500 dark:focus:ring-indigo-400 focus:border-indigo-500 dark:focus:border-indigo-400" required aria-required="true"></textarea>
                            </div>
                            <button type="submit" class="w-full px-6 py-3 bg-indigo-600 text-white font-medium rounded-md hover:bg-indigo-700 dark:bg-indigo-500 dark:hover:bg-indigo-600 transition duration-300">
                                Send Message
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-gray-900 dark:bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Malaki Ronald Mandela</h3>
                    <p class="text-gray-400 dark:text-gray-400">
                        Academic researcher exploring the intersection of technology, ethics, and social justice.
                    </p>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white transition duration-300">Home</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white transition duration-300">About</a></li>
                        <li><a href="#research" class="text-gray-400 hover:text-white transition duration-300">Research</a></li>
                        <li><a href="#publications" class="text-gray-400 hover:text-white transition duration-300">Publications</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition duration-300">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Connect</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="h-10 w-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-indigo-600 dark:hover:bg-indigo-500 transition duration-300">
                            <i data-feather="twitter"></i>
                        </a>
                        <a href="#" class="h-10 w-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-indigo-600 dark:hover:bg-indigo-500 transition duration-300">
                            <i data-feather="linkedin"></i>
                        </a>
                        <a href="#" class="h-10 w-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-indigo-600 dark:hover:bg-indigo-500 transition duration-300">
                            <i data-feather="github"></i>
                        </a>
                        <a href="#" class="h-10 w-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-indigo-600 dark:hover:bg-indigo-500 transition duration-300">
                            <i data-feather="google-scholar"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 dark:border-gray-700 mt-12 pt-8 text-center text-gray-400 dark:text-gray-400">
                <p>&copy; 2025 Malaki Ronald Mandela. All rights reserved.</p>
            </div>
        </div>
    </footer>
    <script>
        // Mobile menu toggle
        document.querySelector('.mobile-menu-button').addEventListener('click', function() {
            const mobileMenu = document.querySelector('.mobile-menu');
            mobileMenu.classList.toggle('hidden');
            this.setAttribute('aria-expanded', mobileMenu.classList.contains('hidden') ? 'false' : 'true');
        });

        // Close mobile menu when clicking a link
        document.querySelectorAll('.mobile-menu a').forEach(item => {
            item.addEventListener('click', function() {
                document.querySelector('.mobile-menu').classList.add('hidden');
                document.querySelector('.mobile-menu-button').setAttribute('aria-expanded', 'false');
            });
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    // Update active nav link
                    document.querySelectorAll('.nav-link').forEach(link => {
                        link.classList.remove('active-nav', 'text-indigo-600', 'dark:text-indigo-400');
                        link.classList.add('text-gray-700', 'dark:text-gray-300');
                    });
                    this.classList.add('active-nav', 'text-indigo-600', 'dark:text-indigo-400');
                    this.classList.remove('text-gray-700', 'dark:text-gray-300');
                }
            });
        });

        // Highlight active nav link on scroll
        window.addEventListener('scroll', function() {
            const scrollPosition = window.scrollY + 100;
            document.querySelectorAll('section').forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.offsetHeight;
                const sectionId = section.getAttribute('id');
                
                if (scrollPosition >= sectionTop && scrollPosition < sectionTop + sectionHeight) {
                    document.querySelectorAll('.nav-link').forEach(link => {
                        link.classList.remove('active-nav', 'text-indigo-600', 'dark:text-indigo-400');
                        link.classList.add('text-gray-700', 'dark:text-gray-300');
                    });
                    const activeLink = document.querySelector(`.nav-link[href="#${sectionId}"]`);
                    if (activeLink) {
                        activeLink.classList.add('active-nav', 'text-indigo-600', 'dark:text-indigo-400');
                        activeLink.classList.remove('text-gray-700', 'dark:text-gray-300');
                    }
                }
            });
        });

        // Initialize AOS
        AOS.init({
            once: true,
            duration: 800,
            easing: 'ease-out-quart'
        });

        // Initialize Feather Icons
        feather.replace();

        // Form submission handling
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const subject = document.getElementById('subject').value;
            const message = document.getElementById('message').value;

            if (name && email && subject && message) {
                // Replace with actual form submission logic (e.g., API call)
                console.log('Form submitted:', { name, email, subject, message });
                alert('Message sent successfully!');
                this.reset();
            } else {
                alert('Please fill in all required fields.');
            }
        });
    </script>
</body>
</html>
