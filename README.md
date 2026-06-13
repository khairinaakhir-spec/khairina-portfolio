<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nurul Khairina Mohd Akhir | Real Estate Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- FontAwesome Premium Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Typography Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .font-serif-display {
            font-family: 'DM Serif Display', serif;
        }
        .bg-corporate-dark { background-color: #0A1D37; }
        .bg-corporate-blue { background-color: #0F2C59; }
        .text-gold { color: #C5A880; }
        .bg-gold { background-color: #C5A880; }
        .border-gold { border-color: #C5A880; }
        .hover-bg-gold-dark:hover { background-color: #B3966E; }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased selection:bg-gold/30">

    <!-- STICKY TOP NAVIGATION BAR -->
    <nav class="fixed top-0 left-0 right-0 z-50 bg-corporate-dark/95 backdrop-blur-md border-b border-white/10 text-white shadow-xl">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex-shrink-0">
                    <span class="text-xl font-bold tracking-wider font-serif-display">NURUL <span class="text-gold">KHAIRINA</span></span>
                </div>
                <div class="hidden lg:block">
                    <div class="ml-10 flex items-center space-x-6 text-xs uppercase font-semibold tracking-widest">
                        <a href="#hero" class="hover:text-gold transition-colors">Home</a>
                        <a href="#about" class="hover:text-gold transition-colors">About</a>
                        <a href="#education" class="hover:text-gold transition-colors">Education</a>
                        <a href="#experience" class="hover:text-gold transition-colors">Experience</a>
                        <a href="#projects" class="hover:text-gold transition-colors">Projects</a>
                        <a href="#skills" class="hover:text-gold transition-colors">Skills</a>
                        <a href="#awards" class="hover:text-gold transition-colors">Awards</a>
                        <a href="#volunteer" class="hover:text-gold transition-colors">Volunteer</a>
                        <a href="#contact" class="bg-gold hover-bg-gold-dark text-corporate-dark px-4 py-2 rounded font-bold transition-all shadow-md">Contact Us</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <!-- 1. HERO MAIN HEADER SECTION -->
    <header id="hero" class="pt-28 min-h-screen bg-corporate-dark text-white relative flex items-center overflow-hidden pb-16 lg:pb-0">
        <!-- Abstract Branding Accent Elements -->
        <div class="absolute bottom-0 right-0 w-full h-1/2 bg-gradient-to-t from-corporate-blue/40 to-transparent pointer-events-none"></div>
        <div class="absolute -bottom-16 -left-16 w-96 h-96 bg-gold/5 rounded-full blur-3xl pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 w-full z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Narrative Content Column -->
                <div class="lg:col-span-7 order-2 lg:order-1 space-y-6 text-center lg:text-left">
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight font-serif-display leading-tight uppercase">
                        NURUL KHAIRINA<br><span class="text-gold">MOHD AKHIR</span>
                    </h1>
                    <p class="text-sm sm:text-base text-slate-300 tracking-wide font-medium max-w-2xl mx-auto lg:mx-0 border-t lg:border-t-0 lg:border-l-4 border-gold pt-4 lg:pt-0 lg:pl-4">
                        Real Estate Management Student | Aspiring Property Valuer | Estate Agency Professional
                    </p>
                    
                    <!-- Dashboard Statistics Counters Module -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 max-w-xl mx-auto lg:mx-0 pt-4">
                        <div class="bg-white/5 border border-white/10 rounded-xl p-4 text-center backdrop-blur-sm hover:border-gold/30 transition-all">
                            <div class="text-2xl font-bold font-serif-display text-gold">310</div>
                            <div class="text-[10px] text-slate-400 uppercase tracking-wider font-semibold mt-0.5">Estate Agents Surveyed</div>
                        </div>
                        <div class="bg-white/5 border border-white/10 rounded-xl p-4 text-center backdrop-blur-sm hover:border-gold/30 transition-all">
                            <div class="text-2xl font-bold font-serif-display text-gold">30+</div>
                            <div class="text-[10px] text-slate-400 uppercase tracking-wider font-semibold mt-0.5">Property Inspections</div>
                        </div>
                        <div class="bg-white/5 border border-white/10 rounded-xl p-4 text-center backdrop-blur-sm hover:border-gold/30 transition-all">
                            <div class="text-2xl font-bold font-serif-display text-gold">100+</div>
                            <div class="text-[10px] text-slate-400 uppercase tracking-wider font-semibold mt-0.5">Listings Managed</div>
                        </div>
                        <div class="bg-white/5 border border-white/10 rounded-xl p-4 text-center backdrop-blur-sm hover:border-gold/30 transition-all">
                            <div class="text-2xl font-bold font-serif-display text-gold">3.67</div>
                            <div class="text-[10px] text-slate-400 uppercase tracking-wider font-semibold mt-0.5">Current CGPA</div>
                        </div>
                    </div>

                    <!-- Call To Action Buttons -->
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="#projects" class="bg-gold hover-bg-gold-dark text-corporate-dark font-bold px-6 py-3 rounded text-sm uppercase tracking-wider transition-all shadow-lg">Explore Projects</a>
                        <a href="#contact" class="border border-white/30 hover:border-white text-white font-semibold px-6 py-3 rounded text-sm uppercase tracking-wider transition-all">Contact Me</a>
                    </div>
                </div>

                <!-- Right Profile Image Section showcasing WhatsApp Image 2026-06-14 at 5.46.02 AM_3.jpeg -->
                <div class="lg:col-span-5 order-1 lg:order-2 flex justify-center lg:justify-end">
                    <div class="relative w-72 h-72 sm:w-85 sm:h-85 lg:w-96 lg:h-96 rounded-2xl overflow-hidden border-2 border-gold/40 shadow-2xl bg-white p-3 group">
                        <div class="absolute inset-0 bg-gradient-to-tr from-corporate-dark/10 to-transparent z-10 pointer-events-none"></div>
                        <img src="WhatsApp Image 2026-06-14 at 5.46.02 AM_3.jpeg" alt="Nurul Khairina Mohd Akhir Portfolio" class="w-full h-full object-contain rounded-xl transform scale-102 group-hover:scale-105 transition-all duration-500">
                    </div>
                </div>

            </div>
        </div>
    </header>

    <!-- 2. ABOUT ME SUMMARY SECTION -->
    <section id="about" class="py-24 bg-corporate-dark text-white relative">
        <!-- Curved Bottom Edge Transition -->
        <div class="absolute bottom-0 left-0 right-0 h-16 bg-white rounded-t-[50px] lg:rounded-t-[100px]"></div>
        
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 pb-16 relative z-10">
            <div class="space-y-6 text-center">
                <h2 class="text-3xl font-bold font-serif-display tracking-wide uppercase">About Me</h2>
                <div class="h-0.5 w-12 bg-gold mx-auto"></div>
                <p class="text-base sm:text-lg text-slate-300 leading-relaxed max-w-3xl mx-auto pt-2">
                    I am a driven Bachelor of Real Estate Management (Hons) student at Universiti Teknologi MARA (UiTM), recognized with Dean's List honors. I am enthusiastic to acquire hands-on experience through an internship in the Real Estate and Property industry. Aiming to apply academic knowledge, gain practical insights, and develop professionally within a dynamic work environment to achieve both personal and organizational objectives.
                </p>
                <p class="text-base sm:text-lg text-gold font-medium font-serif-display italic">
                    Seeking an internship placement from 27 September 2026 until 28 January 2027 (18 weeks) as a Property Management Intern / Valuer / Estate Agent.
                </p>
            </div>
        </div>
    </section>

    <!-- 3. EDUCATION CHRONOLOGY SECTION -->
    <section id="education" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16">
                <h2 class="text-2xl font-bold font-serif-display text-corporate-dark uppercase tracking-wide">Educational Background</h2>
                <div class="h-0.5 w-12 bg-gold mt-2"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Undergrad Program Card -->
                <div class="bg-slate-50 rounded-xl p-6 border border-slate-100 flex items-start space-x-4 shadow-sm hover:shadow-md transition-all">
                    <div class="bg-corporate-blue text-gold p-3 rounded-lg flex-shrink-0 shadow-inner">
                        <i class="fa-solid fa-graduation-cap text-xl"></i>
                    </div>
                    <div class="space-y-2">
                        <span class="text-xs font-bold text-gold tracking-wider uppercase">Oct 2024 - Jan 2027</span>
                        <h3 class="font-bold text-lg text-corporate-dark font-serif-display leading-tight">Bachelor in Real Estate Management (Hons)</h3>
                        <p class="text-sm font-medium text-slate-500">Universiti Teknologi MARA | Seri Iskandar, Perak</p>
                        <ul class="text-xs text-slate-600 space-y-1 pt-2 list-disc list-inside">
                            <li>Current CGPA: <strong class="text-corporate-dark">3.67</strong></li>
                            <li>Dean's List award for semester 5 distinction</li>
                        </ul>
                    </div>
                </div>

                <!-- Diploma Program Card -->
                <div class="bg-slate-50 rounded-xl p-6 border border-slate-100 flex items-start space-x-4 shadow-sm hover:shadow-md transition-all">
                    <div class="bg-corporate-blue text-gold p-3 rounded-lg flex-shrink-0 shadow-inner">
                        <i class="fa-solid fa-certificate text-xl"></i>
                    </div>
                    <div class="space-y-2">
                        <span class="text-xs font-bold text-gold tracking-wider uppercase">Oct 2022 - July 2024</span>
                        <h3 class="font-bold text-lg text-corporate-dark font-serif-display leading-tight">Diploma Estate Management</h3>
                        <p class="text-sm font-medium text-slate-500">Universiti Teknologi MARA | Seri Iskandar, Perak</p>
                        <ul class="text-xs text-slate-600 space-y-1 pt-2 list-disc list-inside">
                            <li>Graduated Performance: <strong class="text-corporate-dark">3.33 CGPA</strong></li>
                            <li>Malaysian University English Test (MUET): Band 3.50</li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <!-- High School Sub-timeline Block -->
            <div class="mt-8 bg-slate-50/60 rounded-xl p-6 border border-slate-100/80 grid grid-cols-1 md:grid-cols-2 gap-4 text-xs text-slate-600">
                <div>
                    <p class="font-bold text-corporate-dark text-sm font-serif-display">Maktab Mahmud Pokok Sena</p>
                    <p class="text-slate-400 mb-1">Jan 2016 - Dis 2020 | Langgar, Kedah</p>
                    <p>Malaysian Higher School Certificate (SPM) - Accounting and Arabic Stream</p>
                    <p class="font-medium text-gold mt-0.5">SPM Grade Record: 5A 1B+ 5C</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. WORK HISTORY SECTION -->
    <section id="experience" class="py-20 bg-corporate-dark text-white">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16 text-center md:text-left">
                <h2 class="text-2xl font-bold font-serif-display uppercase tracking-wide">Work History</h2>
                <div class="h-0.5 w-12 bg-gold mt-2 mx-auto md:mx-0"></div>
            </div>

            <div class="space-y-8 max-w-4xl mx-auto">
                <!-- Job Position 1 -->
                <div class="bg-white/5 border border-white/10 rounded-xl p-6 md:p-8 space-y-4 hover:border-gold/30 transition-all shadow-md">
                    <div class="flex flex-col md:flex-row md:items-center justify-between gap-2 border-b border-white/10 pb-4">
                        <div>
                            <span class="text-xs font-bold text-gold uppercase tracking-widest block mb-1">July 2024 - Present</span>
                            <h3 class="text-xl font-bold font-serif-display">Real Estate Negotiator</h3>
                            <p class="text-sm text-slate-400">Esp Esprit Estate Agent Sdn Bhd | Sungai Petani, Kedah</p>
                        </div>
                    </div>
                    <ul class="space-y-2 text-sm text-slate-300 list-none pl-0">
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Advised 4-6 clients weekly on property purchases, financing options, and market conditions.</li>
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Coordinated property sales and rental transactions between buyers, sellers, and financial institutions.</li>
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Generated leads through networking, referrals, and prospecting activities.</li>
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Conducted market research and property analysis to support pricing and marketing decisions.</li>
                    </ul>
                </div>

                <!-- Job Position 2 -->
                <div class="bg-white/5 border border-white/10 rounded-xl p-6 md:p-8 space-y-4 hover:border-gold/30 transition-all shadow-md">
                    <div class="flex flex-col md:flex-row md:items-center justify-between gap-2 border-b border-white/10 pb-4">
                        <div>
                            <span class="text-xs font-bold text-gold uppercase tracking-widest block mb-1">March 2024 - July 2024</span>
                            <h3 class="text-xl font-bold font-serif-display">Interpretation Intern</h3>
                            <p class="text-sm text-slate-400">Esp Esprit Estate Agent Sdn Bhd | Sungai Petani, Kedah</p>
                        </div>
                    </div>
                    <ul class="space-y-2 text-sm text-slate-300 list-none pl-0">
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Assisted in 30+ property inspections for residential, commercial, and industrial properties.</li>
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Conducted market research and maintained 100+ property listings for valuation and marketing purposes.</li>
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Verified property information and prepared supporting data for valuation assignments.</li>
                        <li class="flex items-start"><span class="text-gold mr-3 mt-1 text-xs">&#9642;</span> Developed marketing materials and managed social media content using Canva Pro.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. ACADEMIC PROJECT SECTION -->
    <section id="projects" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16 text-center">
                <h2 class="text-2xl font-bold font-serif-display text-corporate-dark uppercase tracking-wide">Academic Projects</h2>
                <div class="h-0.5 w-12 bg-gold mt-2 mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Project Card 1 -->
                <div class="bg-slate-50 border border-slate-100 rounded-xl p-6 shadow-sm flex flex-col justify-between hover:shadow-md hover:border-gold/20 transition-all">
                    <div class="space-y-4">
                        <div class="w-12 h-12 rounded-lg bg-corporate-blue/5 flex items-center justify-center text-corporate-blue">
                            <i class="fa-solid fa-vr-cardboard text-xl text-gold"></i>
                        </div>
                        <h3 class="font-bold text-lg text-corporate-dark font-serif-display leading-tight">VR Technology Adoption Study</h3>
                        <p class="text-xs font-semibold text-gold uppercase tracking-wider">Final Year Research Project (May 2026-Present)</p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Led a comprehensive study involving 310 estate agents to examine crucial factors influencing Virtual Reality (VR) technology adoption in Kedah. Analyzed complex survey statistics using SPSS to extract strategic real estate technology acceptance insights.
                        </p>
                    </div>
                    <div class="pt-6 mt-4 border-t border-slate-200/60 flex flex-wrap gap-1">
                        <span class="bg-corporate-blue/5 text-corporate-blue text-[10px] font-bold px-2 py-0.5 rounded uppercase">SPSS Analysis</span>
                        <span class="bg-corporate-blue/5 text-corporate-blue text-[10px] font-bold px-2 py-0.5 rounded uppercase">PropTech Research</span>
                    </div>
                </div>

                <!-- Project Card 2 -->
                <div class="bg-slate-50 border border-slate-100 rounded-xl p-6 shadow-sm flex flex-col justify-between hover:shadow-md hover:border-gold/20 transition-all">
                    <div class="space-y-4">
                        <div class="w-12 h-12 rounded-lg bg-corporate-blue/5 flex items-center justify-center text-corporate-blue">
                            <i class="fa-solid fa-map-location-dot text-xl text-gold"></i>
                        </div>
                        <h3 class="font-bold text-lg text-corporate-dark font-serif-display leading-tight">REMPEX Mixed-Use Proposal</h3>
                        <p class="text-xs font-semibold text-gold uppercase tracking-wider">Property Exhibition Exhibition (Jan 2026)</p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Co-developed an elite RM50 million+ mixed-use development project proposal as part of a 5-member team. Conducted market feasibility metrics, formal property valuations, and constructed vector assets using AutoCAD and Revit 3D environments.
                        </p>
                    </div>
                    <div class="pt-6 mt-4 border-t border-slate-200/60 flex flex-wrap gap-1">
                        <span class="bg-corporate-blue/5 text-corporate-blue text-[10px] font-bold px-2 py-0.5 rounded uppercase">AutoCAD</span>
                        <span class="bg-corporate-blue/5 text-corporate-blue text-[10px] font-bold px-2 py-0.5 rounded uppercase">Revit 3D</span>
                        <span class="bg-corporate-blue/5 text-corporate-blue text-[10px] font-bold px-2 py-0.5 rounded uppercase">Valuation</span>
                    </div>
                </div>

                <!-- Project Card 3 -->
                <div class="bg-slate-50 border border-slate-100 rounded-xl p-6 shadow-sm flex flex-col justify-between hover:shadow-md hover:border-gold/20 transition-all">
                    <div class="space-y-4">
                        <div class="w-12 h-12 rounded-lg bg-corporate-blue/5 flex items-center justify-center text-corporate-blue">
                            <i class="fa-solid fa-lightbulb text-xl text-gold"></i>
                        </div>
                        <h3 class="font-bold text-lg text-corporate-dark font-serif-display leading-tight">PRIDE Showcase Award Stick</h3>
                        <p class="text-xs font-semibold text-gold uppercase tracking-wider">Idea Innovation Showcase (Dec 2025)</p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Co-developed an innovative multifunction hiking stick concept prioritizing outdoor user safety. Managed the core product architecture design, winning the premier <span class="text-corporate-dark font-medium">Best Poster Award</span> among 20+ rival competing teams.
                        </p>
                    </div>
                    <div class="pt-6 mt-4 border-t border-slate-200/60 flex flex-wrap gap-1">
                        <span class="bg-corporate-blue/5 text-corporate-blue text-[10px] font-bold px-2 py-0.5 rounded uppercase">Product Design</span>
                        <span class="bg-corporate-blue/5 text-corporate-blue text-[10px] font-bold px-2 py-0.5 rounded uppercase">Canva Pro</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. SKILLS & PROPERTY SEARCH CHANNELS -->
    <section id="skills" class="py-20 bg-slate-50 border-t border-b border-slate-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                
                <!-- Core Skills Badges Grid -->
                <div class="lg:col-span-7">
                    <h2 class="text-2xl font-bold font-serif-display text-corporate-dark uppercase tracking-wide">Technical Skills</h2>
                    <div class="h-0.5 w-12 bg-gold mt-2 mb-8"></div>
                    
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-4">
                        <div class="bg-white p-4 rounded-xl border border-slate-200/60 text-center shadow-sm">
                            <i class="fa-solid fa-calculator text-gold text-xl mb-2"></i>
                            <p class="text-xs font-bold text-corporate-dark tracking-wide uppercase">Property Valuation</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl border border-slate-200/60 text-center shadow-sm">
                            <i class="fa-solid fa-house-chimney-search text-gold text-xl mb-2"></i>
                            <p class="text-xs font-bold text-corporate-dark tracking-wide uppercase">Property Inspection</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl border border-slate-200/60 text-center shadow-sm">
                            <i class="fa-solid fa-magnifying-glass-chart text-gold text-xl mb-2"></i>
                            <p class="text-xs font-bold text-corporate-dark tracking-wide uppercase">Market Research</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl border border-slate-200/60 text-center shadow-sm">
                            <i class="fa-solid fa-chart-bar text-gold text-xl mb-2"></i>
                            <p class="text-xs font-bold text-corporate-dark tracking-wide uppercase">SPSS / GIS Systems</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl border border-slate-200/60 text-center shadow-sm">
                            <i class="fa-solid fa-compass-drafting text-gold text-xl mb-2"></i>
                            <p class="text-xs font-bold text-corporate-dark tracking-wide uppercase">AutoCAD & Revit</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl border border-slate-200/60 text-center shadow-sm">
                            <i class="fa-solid fa-file-excel text-gold text-xl mb-2"></i>
                            <p class="text-xs font-bold text-corporate-dark tracking-wide uppercase">Microsoft Office</p>
                        </div>
                    </div>

                    <!-- Digital Research Subpanel integration -->
                    <div class="mt-6 bg-white p-5 rounded-xl border border-slate-200/60 shadow-sm space-y-2">
                        <h4 class="text-xs font-bold uppercase text-slate-400 tracking-wider">Digital Market Research Fluency</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Skilled in synthesizing comprehensive data across analytics engines including <strong class="text-corporate-dark">Brickz</strong> for historical transaction trends, <strong class="text-corporate-dark">Mudah</strong>, <strong class="text-corporate-dark">EdgeProp</strong>, <strong class="text-corporate-dark">iProperty</strong>, and <strong class="text-corporate-dark">Trovit</strong> for listing streams to support precise valuations.
                        </p>
                    </div>
                </div>

                <!-- Logistics & Communication Capabilities Panel -->
                <div class="lg:col-span-5">
                    <h2 class="text-2xl font-bold font-serif-display text-corporate-dark uppercase tracking-wide">Additional Information</h2>
                    <div class="h-0.5 w-12 bg-gold mt-2 mb-8"></div>
                    
                    <div class="bg-corporate-blue text-white rounded-xl p-6 shadow-md space-y-4">
                        <div class="flex items-start space-x-3 text-sm">
                            <i class="fa-solid fa-car text-gold text-base mt-0.5 w-6 text-center"></i>
                            <span>Possess a valid Class B2 & DA Driving Licence with personal vehicle transport logistics. Fully prepared for field travel.</span>
                        </div>
                        <div class="flex items-start space-x-3 text-sm">
                            <i class="fa-solid fa-language text-gold text-base mt-0.5 w-6 text-center"></i>
                            <span>Advanced multi-language fluency: Bahasa Melayu (Native), English (Advanced), and Arabic (Advanced).</span>
                        </div>
                        <div class="flex items-start space-x-3 text-sm">
                            <i class="fa-solid fa-people-arrows text-gold text-base mt-0.5 w-6 text-center"></i>
                            <span>Expertise in managing customer relations across banking contacts, property legal firms, and asset negotiators.</span>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- 7. AWARDS & CO-CURRICULAR SECTION -->
    <section id="awards" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16 text-center">
                <h2 class="text-2xl font-bold font-serif-display text-corporate-dark uppercase tracking-wide">Awards & Achievements</h2>
                <div class="h-0.5 w-12 bg-gold mt-2 mx-auto"></div>
            </div>

            <!-- Awards Highlight Grid Elements -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center mb-12">
                <div class="p-6 bg-slate-50 border border-slate-100 rounded-xl shadow-sm">
                    <i class="fa-solid fa-award text-gold text-3xl mb-3"></i>
                    <h4 class="font-bold text-corporate-dark font-serif-display">Dean's List Award</h4>
                    <p class="text-xs text-slate-500 mt-1">Conferred for outstanding academic marks in Semester 5</p>
                </div>
                <div class="p-6 bg-slate-50 border border-slate-100 rounded-xl shadow-sm">
                    <i class="fa-solid fa-shield-halved text-gold text-3xl mb-3"></i>
                    <h4 class="font-bold text-corporate-dark font-serif-display">JPA Scholarship</h4>
                    <p class="text-xs text-slate-500 mt-1">Awarded to elite students maintaining above a 3.0 CGPA every semester</p>
                </div>
                <div class="p-6 bg-slate-50 border border-slate-100 rounded-xl shadow-sm">
                    <i class="fa-solid fa-trophy text-gold text-3xl mb-3"></i>
                    <h4 class="font-bold text-corporate-dark font-serif-display">PRIDE Best Poster</h4>
                    <p class="text-xs text-slate-500 mt-1">Won 1st place award out of 20+ competing innovation panels</p>
                </div>
            </div>

            <!-- Co-Curricular Extra Panel Box -->
            <div class="bg-slate-50 rounded-xl p-6 border border-slate-100 max-w-4xl mx-auto">
                <h4 class="text-xs font-bold uppercase text-slate-400 tracking-wider mb-4 font-serif-display text-center md:text-left">Co-Curricular & Leadership Activity</h4>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-xs text-slate-600">
                    <div class="flex items-start space-x-2">
                        <span class="text-gold mt-0.5">&#9642;</span>
                        <span><strong>Multimedia Deputy Exco Head:</strong> Managed organizational brand architecture and presentation workflows for Majlis Pimpinan Universiti Rakan Siswa YADIM.</span>
                    </div>
                    <div class="flex items-start space-x-2">
                        <span class="text-gold mt-0.5">&#9642;</span>
                        <span><strong>MASMED Young Entrepreneur:</strong> Active corporate program builder nominee for the premier Best Icon award track (2023).</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 8. VOLUNTEER EXPERIENCES SECTION -->
    <section id="volunteer" class="py-20 bg-slate-50 border-t border-slate-100">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16 text-center">
                <h2 class="text-2xl font-bold font-serif-display text-corporate-dark uppercase tracking-wide">Volunteer Experience</h2>
                <div class="h-0.5 w-12 bg-gold mt-2 mx-auto"></div>
            </div>

            <!-- Three Column Civic Grid matching graphic asset layout structure perfectly -->
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-6 text-center">
                <div class="p-5 bg-white border border-slate-200/60 rounded-xl shadow-sm space-y-2 hover:shadow-md transition-all">
                    <i class="fa-solid fa-leaf text-gold text-2xl"></i>
                    <h4 class="font-bold text-sm text-corporate-dark font-serif-display">Environmental Initiatives</h4>
                    <p class="text-xs text-slate-500">Free Tree Society Ecosystem Activation x EMAS PERAK (Jun 2026)</p>
                </div>
                <div class="p-5 bg-white border border-slate-200/60 rounded-xl shadow-sm space-y-2 hover:shadow-md transition-all">
                    <i class="fa-solid fa-users text-gold text-2xl"></i>
                    <h4 class="font-bold text-sm text-corporate-dark font-serif-display">Community Events Support</h4>
                    <p class="text-xs text-slate-500">Pekan Manjung Run & Jalinan Kasih Orang Asli Community Drives</p>
                </div>
                <div class="p-5 bg-white border border-slate-200/60 rounded-xl shadow-sm space-y-2 hover:shadow-md transition-all">
                    <i class="fa-solid fa-hand-holding-heart text-gold text-2xl"></i>
                    <h4 class="font-bold text-sm text-corporate-dark font-serif-display">Conservation Efforts</h4>
                    <p class="text-xs text-slate-500">Sungkai Wild Life Hub & Segari Turtle Conservation Centers</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 9. CONTACT / FOOTER SECTION -->
    <footer id="contact" class="bg-corporate-dark text-white pt-20 pb-8 border-t border-white/5">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 mb-12">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-start">
                
                <div class="space-y-4 text-center lg:text-left">
                    <h2 class="text-3xl font-bold font-serif-display uppercase tracking-wide">Get In Touch</h2>
                    <p class="text-slate-400 text-sm max-w-md mx-auto lg:mx-0">
                        Available for an 18-week corporate industrial internship placement starting from 27 September 2026 until 28 January 2027. Let's connect to discuss valuation or property management placements.
                    </p>
                </div>

                <!-- Verified Contact Matrix Rows -->
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm">
                    <div class="space-y-3">
                        <div class="flex items-center space-x-3 bg-white/5 p-3 rounded-lg border border-white/10 hover:border-gold/30 transition-all">
                            <i class="fa-solid fa-envelope text-gold w-5 text-center text-base"></i>
                            <a href="mailto:khairinaakhir@gmail.com" class="hover:text-gold transition-colors truncate">khairinaakhir@gmail.com</a>
                        </div>
                        <div class="flex items-center space-x-3 bg-white/5 p-3 rounded-lg border border-white/10 hover:border-gold/30 transition-all">
                            <i class="fa-solid fa-phone text-gold w-5 text-center text-base"></i>
                            <a href="tel:+601155022829" class="hover:text-gold transition-colors">+6011-55022829</a>
                        </div>
                    </div>
                    <div class="space-y-3">
                        <div class="flex items-center space-x-3 bg-white/5 p-3 rounded-lg border border-white/10 hover:border-gold/30 transition-all">
                            <i class="fa-brands fa-linkedin text-gold w-5 text-center text-base"></i>
                            <a href="https://www.linkedin.com/in/khairina-akhir-96a1ab2a7" target="_blank" class="hover:text-gold transition-colors">LinkedIn Profile</a>
                        </div>
                        <div class="flex items-center space-x-3 bg-white/5 p-3 rounded-lg border border-white/10 hover:border-gold/30 transition-all">
                            <i class="fa-solid fa-link text-gold w-5 text-center text-base"></i>
                            <a href="https://linktr.ee/khaeproperties" target="_blank" class="hover:text-gold transition-colors">Linktree Portfolio</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
        
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 pt-8 border-t border-white/5 text-center text-xs text-slate-500">
            <p>&copy; 2026 Nurul Khairina Mohd Akhir. Designed for Professional Real Estate Internships.</p>
        </div>
    </footer>

</body>
</html>
