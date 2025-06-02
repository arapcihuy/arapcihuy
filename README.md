<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acit | Mobile & Web Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
        .floating {
            animation: float 6s ease-in-out infinite;
        }
        .tech-icon:hover {
            transform: scale(1.2) rotate(10deg);
            filter: drop-shadow(0 0 10px rgba(59, 130, 246, 0.5));
        }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #8b5cf6, #ec4899);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .card-hover {
            transition: all 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .typewriter {
            overflow: hidden;
            border-right: .15em solid #3b82f6;
            white-space: nowrap;
            margin: 0 auto;
            letter-spacing: .15em;
            animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #3b82f6; }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans antialiased">
    <!-- Animated Background -->
    <div class="fixed inset-0 -z-10 overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-br from-blue-50 via-purple-50 to-pink-50 opacity-70"></div>
        <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI1NiIgaGVpZ2h0PSIxMDAiPgo8cmVjdCB3aWR0aD0iNTYiIGhlaWdodD0iMTAwIiBmaWxsPSIjZmZmIj48L3JlY3Q+CjxwYXRoIGQ9Ik0yOCA2NkMwIDY2IDAgNDkgMCA0OSAwIDQ5IDE5IDQ5IDI4IDQ5IDI4IDQ5IDI4IDY2IDI4IDY2WiIgZmlsbD0iI2Y1ZjVmNSI+PC9wYXRoPgo8cGF0aCBkPSJNMjggNjZDMjggNjYgMTQgNjYgMTQgNTQgMTQgNTQgMTQgNTQgMjggNTQgMjggNTQgMjggNjYgMjggNjZaIiBmaWxsPSIjZjVmNWY1Ij48L3BhdGg+Cjwvc3ZnPg==')] opacity-20"></div>
    </div>

    <!-- Main Content -->
    <div class="container mx-auto px-4 py-12 max-w-6xl">
        <!-- Hero Section -->
        <section class="text-center mb-20">
            <div class="relative inline-block mb-8 floating">
                <img src="tumblr_owi25v6uAo1r4gsiio1_1280_gif (1000×300).gif" alt="Profile GIF" class="rounded-full h-48 w-48 object-cover border-4 border-white shadow-xl">
                <div class="absolute -bottom-2 -right-2 bg-blue-500 text-white rounded-full h-12 w-12 flex items-center justify-center shadow-lg">
                    <i class="fas fa-code text-xl"></i>
                </div>
            </div>
            
            <h1 class="text-5xl font-bold mb-4 gradient-text">Hi, I'm <span class="typewriter">Acit</span></h1>
            <h2 class="text-2xl text-gray-600 mb-6">A passionate <span class="font-semibold text-blue-500">Mobile & Web Developer</span> from Indonesia</h2>
            
            <div class="flex justify-center space-x-4">
                <a href="https://linkedin.com/in/your-profile" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-full flex items-center transition-all">
                    <i class="fab fa-linkedin-in mr-2"></i> Connect
                </a>
                <a href="mailto:rasyidahmad180@gmail.com" class="bg-gradient-to-r from-purple-500 to-pink-500 hover:from-purple-600 hover:to-pink-600 text-white px-6 py-3 rounded-full flex items-center transition-all">
                    <i class="fas fa-envelope mr-2"></i> Email Me
                </a>
            </div>
        </section>

        <!-- About Section -->
        <section class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-20">
            <div class="bg-white p-8 rounded-xl shadow-lg card-hover">
                <h3 class="text-2xl font-bold mb-4 text-gray-800 flex items-center">
                    <i class="fas fa-user-graduate text-blue-500 mr-3"></i> About Me
                </h3>
                <div class="space-y-4 text-gray-600">
                    <div class="flex items-start">
                        <i class="fas fa-leaf text-green-500 mt-1 mr-3"></i>
                        <p>Currently learning <span class="font-semibold text-blue-500">Ionic & Firebase</span> to build cross-platform mobile applications.</p>
                    </div>
                    <div class="flex items-start">
                        <i class="fas fa-laptop-code text-purple-500 mt-1 mr-3"></i>
                        <p>Working on <span class="font-semibold text-blue-500">a new mobile app</span> that will revolutionize how people interact with local communities.</p>
                    </div>
                    <div class="flex items-start">
                        <i class="fas fa-comments text-pink-500 mt-1 mr-3"></i>
                        <p>Ask me about <span class="font-semibold text-blue-500">Ionic, Firebase, and Web Development</span> - I love sharing knowledge!</p>
                    </div>
                </div>
            </div>

            <div class="bg-white p-8 rounded-xl shadow-lg card-hover">
                <h3 class="text-2xl font-bold mb-4 text-gray-800 flex items-center">
                    <i class="fas fa-project-diagram text-purple-500 mr-3"></i> Latest Project
                </h3>
                <div class="flex flex-col h-full">
                    <div class="mb-4">
                        <h4 class="text-xl font-semibold text-gray-800">Desa Potorono Website</h4>
                        <p class="text-gray-600 mt-2">A comprehensive website for Desa Potorono featuring information about the village, local businesses, and community events.</p>
                    </div>
                    <div class="mt-auto">
                        <a href="https://your-link.com" class="inline-flex items-center text-blue-500 hover:text-blue-700 font-medium">
                            View Project <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="mb-20">
            <h2 class="text-3xl font-bold text-center mb-12 gradient-text">My Tech Stack</h2>
            
            <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 lg:grid-cols-8 gap-6">
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Android</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Arduino</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Bootstrap</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">C++</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">CSS3</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Figma</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Firebase</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">HTML5</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Java</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">JavaScript</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Kotlin</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Python</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Unity</span>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md flex flex-col items-center tech-icon transition-all">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ionic/ionic-original.svg" class="h-12 w-12 mb-2">
                    <span class="text-sm font-medium text-gray-700">Ionic</span>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="bg-gradient-to-r from-blue-500 to-purple-600 rounded-xl p-8 text-white shadow-xl">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-3xl font-bold mb-4">Let's Build Something Amazing Together</h2>
                <p class="text-xl mb-8 opacity-90">I'm always open to discussing new projects, creative ideas or opportunities to be part of your vision.</p>
                
                <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="mailto:rasyidahmad180@gmail.com" class="bg-white text-blue-600 hover:bg-gray-100 px-6 py-3 rounded-full font-medium flex items-center justify-center transition-all">
                        <i class="fas fa-envelope mr-2"></i> Email Me
                    </a>
                    <a href="https://www.instagram.com/r.asyidahmad/" class="bg-black bg-opacity-20 hover:bg-opacity-30 px-6 py-3 rounded-full font-medium flex items-center justify-center transition-all">
                        <i class="fab fa-instagram mr-2"></i> DM on Instagram
                    </a>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="mt-16 text-center text-gray-500">
            <p>© 2023 Acit. All rights reserved.</p>
            <p class="mt-2 text-sm">Built with <i class="fas fa-heart text-red-500"></i> and <i class="fas fa-coffee text-yellow-600"></i> in Indonesia</p>
        </footer>
    </div>

    <script>
        // Simple animation trigger for elements when they come into view
        document.addEventListener('DOMContentLoaded', function() {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('animate-fadeIn');
                    }
                });
            }, { threshold: 0.1 });

            document.querySelectorAll('.tech-icon, .card-hover').forEach(el => {
                observer.observe(el);
            });
        });
    </script>
</body>
</html>
