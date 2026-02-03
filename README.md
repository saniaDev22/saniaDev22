<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sania Rawat - Full Stack Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    animation: {
                        'fade-in': 'fadeIn 1s ease-in-out',
                        'slide-up': 'slideUp 0.8s ease-out',
                        'pulse-glow': 'pulse 2s infinite, glow 2s infinite'
                    },
                    keyframes: {
                        fadeIn: {
                            '0%': { opacity: '0', transform: 'translateY(20px)' },
                            '100%': { opacity: '1', transform: 'translateY(0)' }
                        },
                        slideUp: {
                            '0%': { transform: 'translateY(50px)', opacity: '0' },
                            '100%': { transform: 'translateY(0)', opacity: '1' }
                        },
                        glow: {
                            '0%, 100%': { boxShadow: '0 0 20px rgba(59, 130, 246, 0.5)' },
                            '50%': { boxShadow: '0 0 40px rgba(59, 130, 246, 0.8)' }
                        }
                    }
                }
            }
        }
    </script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gradient-to-br from-indigo-900 via-purple-900 to-pink-900 min-h-screen text-white p-8 font-sans">
    <div class="max-w-4xl mx-auto">
        <!-- Hero Section -->
        <div class="text-center mb-16 animate-fade-in">
            <div class="w-32 h-32 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full mx-auto mb-8 shadow-2xl hover:scale-110 transition-all duration-500 animate-pulse-glow">
                <i class="fas fa-laptop-code text-4xl text-white p-8"></i>
            </div>
            <h1 class="text-5xl font-bold bg-gradient-to-r from-blue-400 to-purple-400 bg-clip-text text-transparent mb-4 animate-slide-up">
                Hi, I'm <span class="text-blue-300">Sania Rawat</span> 👋
            </h1>
            <p class="text-xl text-gray-300 mb-8 max-w-2xl mx-auto leading-relaxed animate-slide-up [animation-delay:0.2s]">
                Passionate <strong>Full Stack Web Developer</strong> building clean, scalable, and user-friendly web applications. 🚀
                I turn ideas into real-world products using modern web technologies. 🎯
            </p>
        </div>

        <!-- About Section -->
        <section class="mb-16 animate-fade-in">
            <h2 class="text-3xl font-bold text-blue-400 mb-8 flex items-center">
                <i class="fas fa-user text-2xl mr-4"></i>About Me
            </h2>
            <div class="grid md:grid-cols-2 gap-8 text-lg">
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl border border-white/20 hover:bg-white/20 transition-all duration-300">
                    <ul class="space-y-4">
                        <li><i class="fas fa-graduation-cap text-blue-400 mr-3"></i>Computer Science student (BCA)</li>
                        <li><i class="fas fa-seedling text-green-400 mr-3"></i>Learning Advanced Backend, System Design & AI Integration</li>
                        <li><i class="fas fa-binoculars text-purple-400 mr-3"></i>Building projects: GitHub Clone, AI Image Generator, Chat Apps</li>
                    </ul>
                </div>
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl border border-white/20 hover:bg-white/20 transition-all duration-300">
                    <ul class="space-y-4">
                        <li><i class="fas fa-handshake text-orange-400 mr-3"></i>Open to internships, collaborations & open-source</li>
                        <li><i class="fas fa-bolt text-yellow-400 mr-3"></i>Believe in learning by building</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="mb-16 animate-fade-in [animation-delay:0.1s]">
            <h2 class="text-3xl font-bold text-blue-400 mb-8 flex items-center">
                <i class="fas fa-tools text-2xl mr-4"></i>Skills & Technologies
            </h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-white/10 backdrop-blur-sm p-8 rounded-2xl border border-white/20 hover:scale-105 hover:shadow-2xl transition-all duration-300">
                    <h3 class="text-2xl font-semibold mb-6 text-purple-300 flex items-center">
                        <i class="fas fa-desktop text-2xl mr-3"></i>Frontend
                    </h3>
                    <ul class="space-y-3 text-lg">
                        <li><i class="fas fa-check text-green-400 mr-3"></i>HTML5, CSS3, JavaScript (ES6+)</li>
                        <li><i class="fab fa-react text-blue-400 mr-3"></i>React.js, Tailwind CSS</li>
                        <li><i class="fas fa-mobile-alt text-emerald-400 mr-3"></i>Responsive UI Design</li>
                    </ul>
                </div>
                <div class="bg-white/10 backdrop-blur-sm p-8 rounded-2xl border border-white/20 hover:scale-105 hover:shadow-2xl transition-all duration-300">
                    <h3 class="text-2xl font-semibold mb-6 text-purple-300 flex items-center">
                        <i class="fas fa-cogs text-2xl mr-3"></i>Tools & Platforms
                    </h3>
                    <ul class="space-y-3 text-lg">
                        <li><i class="fab fa-git-alt text-orange-400 mr-3"></i>Git & GitHub</li>
                        <li><i class="fas fa-code text-gray-300 mr-3"></i>VS Code</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Connect Section -->
        <section class="mb-16 animate-fade-in [animation-delay:0.2s]">
            <h2 class="text-3xl font-bold text-blue-400 mb-8 flex items-center justify-center">
                <i class="fas fa-address-book text-2xl mr-4"></i>Connect With Me
            </h2>
            <div class="grid md:grid-cols-3 gap-6 max-w-2xl mx-auto">
                <a href="https://www.linkedin.com/in/sania-rawat-816b18336" target="_blank" class="group bg-gradient-to-r from-blue-600 to-blue-700 hover:from-blue-500 hover:to-blue-600 p-8 rounded-2xl text-center border-2 border-transparent hover:border-white/50 transition-all duration-300 hover:scale-105 hover:shadow-2xl animate-pulse-glow">
                    <i class="fab fa-linkedin-in text-3xl mb-4 group-hover:rotate-12 transition-transform duration-300"></i>
                    <p class="font-semibold text-lg">LinkedIn</p>
                </a>
                <a href="mailto:sania.rawat@gmail.com" class="group bg-gradient-to-r from-green-600 to-green-700 hover:from-green-500 hover:to-green-600 p-8 rounded-2xl text-center border-2 border-transparent hover:border-white/50 transition-all duration-300 hover:scale-105 hover:shadow-2xl">
                    <i class="fas fa-envelope text-3xl mb-4 group-hover:-translate-y-1 transition-transform duration-300"></i>
                    <p class="font-semibold text-lg">Email</p>
                </a>
                <div class="bg-gradient-to-r from-gray-700 to-gray-800 p-8 rounded-2xl text-center border-2 border-white/30 cursor-pointer hover:bg-gray-700/50 transition-all duration-300 hover:scale-105 hover:shadow-2xl">
                    <i class="fas fa-globe text-3xl mb-4 opacity-70"></i>
                    <p class="font-semibold text-lg">Portfolio<br><span class="text-sm text-gray-400">Coming Soon</span></p>
                </div>
            </div>
        </section>

        <!-- Fun Fact -->
        <div class="text-center p-12 bg-white/5 backdrop-blur-xl rounded-3xl border border-white/20 hover:bg-white/10 transition-all duration-300 animate-slide-up">
            <i class="fas fa-bug text-5xl text-yellow-400 mb-6 animate-bounce"></i>
            <p class="text-2xl font-semibold text-gray-200 italic">"I love debugging bugs more than writing them 😄"</p>
        </div>
    </div>
</body>
</html>
