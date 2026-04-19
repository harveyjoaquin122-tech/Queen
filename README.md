<!DOCTYPE html>
<html lang="tl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Queen of Biñan Choir | Nuestra Señora De La Paz Buen Viaje</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&family=Quicksand:wght@300;500;700&family=Great+Vibes&display=swap" rel="stylesheet">

    <style>
        :root {
            --royal-blue: #0f172a;
            --gold: #D4AF37;
            --accent-blue: #3b82f6;
        }

        body { 
            font-family: 'Quicksand', sans-serif; 
            scroll-behavior: smooth;
            overflow-x: hidden;
        }

        .font-cinzel { font-family: 'Cinzel', serif; }
        .font-cursive { font-family: 'Great Vibes', cursive; }

        ::-webkit-scrollbar { width: 10px; }
        ::-webkit-scrollbar-track { background: #f1f1f1; }
        ::-webkit-scrollbar-thumb { background: var(--gold); border-radius: 5px; }

        .hero-gradient {
            background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 50%, #60a5fa 100%);
            position: relative;
        }

        .hero-pattern {
            background-image: url('https://www.transparenttextures.com/patterns/cubes.png');
            opacity: 0.1;
        }

        .glass-nav {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(20px);
            border-bottom: 2px solid var(--gold);
        }

        .btn-shine {
            position: relative;
            overflow: hidden;
            transition: all 0.4s;
        }

        .btn-shine:after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: rgba(255,255,255,0.2);
            transform: rotate(45deg);
            transition: 0.6s;
        }

        .btn-shine:hover:after { left: 120%; }

        .floating-icon { animation: bounce 4s ease-in-out infinite; }

        @keyframes bounce {
            0%, 100% { transform: translateY(0) rotate(0); }
            50% { transform: translateY(-20px) rotate(10deg); }
        }

        .history-card {
            background: linear-gradient(to bottom right, #ffffff, #f8fafc);
            border-left: 5px solid var(--gold);
            transition: all 0.3s ease;
        }

        .history-card:hover {
            transform: scale(1.02);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1);
        }
    </style>
</head>
<body class="bg-white text-slate-900">

    <nav class="fixed w-full z-[100] px-4 md:px-12 py-6">
        <div class="max-w-7xl mx-auto flex justify-between items-center glass-nav px-8 py-4 rounded-full shadow-2xl">
            <div class="flex items-center gap-3">
                <div class="bg-blue-900 p-2 rounded-full shadow-lg">
                    <i class="fa-solid fa-crown text-yellow-400 text-xl"></i>
                </div>
                <span class="font-cinzel font-black text-blue-900 tracking-tighter text-lg hidden md:block uppercase">Queen of Biñan Choir</span>
            </div>
            
            <div class="hidden md:flex space-x-10 font-bold text-xs uppercase tracking-[0.2em]">
                <a href="#home" class="hover:text-amber-600 transition duration-300">Home</a>
                <a href="#vision" class="hover:text-amber-600 transition duration-300">Misyon</a>
                <a href="#history" class="hover:text-amber-600 transition duration-300">Kasaysayan</a>
                <a href="#gallery" class="hover:text-amber-600 transition duration-300">Gallery</a>
                <a href="#contact" class="hover:text-amber-600 transition duration-300">Contact</a>
            </div>

            <div class="flex items-center gap-4">
                <a href="https://www.facebook.com/profile.php?id=100089772245400" target="_blank" class="text-blue-900 hover:text-amber-600 transition text-xl">
                    <i class="fa-brands fa-facebook"></i>
                </a>
                <button class="md:hidden text-blue-900 text-xl"><i class="fa-solid fa-bars"></i></button>
            </div>
        </div>
    </nav>

    <section id="home" class="hero-gradient min-h-screen flex items-center justify-center text-white overflow-hidden relative pt-20">
        <div class="hero-pattern absolute inset-0"></div>
        
        <i class="fa-solid fa-music absolute top-40 left-10 text-white/5 text-[150px] floating-icon"></i>
        <i class="fa-solid fa-star absolute bottom-40 right-10 text-yellow-400/10 text-[120px] floating-icon" style="animation-delay: 2s;"></i>

        <div class="text-center px-4 z-10" data-aos="zoom-out" data-aos-duration="1500">
            <div class="flex justify-center mb-10">
                <div class="relative group">
                    <div class="absolute inset-0 bg-amber-400 rounded-full blur-2xl opacity-30 animate-pulse"></div>
                    <div class="relative w-48 h-48 md:w-64 md:h-64 rounded-full border-[6px] border-amber-500 p-2 bg-gradient-to-b from-amber-200 to-amber-600 shadow-2xl overflow-hidden transform transition-transform group-hover:scale-105 duration-500">
                        <div class="w-full h-full rounded-full border-4 border-white overflow-hidden bg-white">
                            <img src="logo.jpeg" alt="Queen of Biñan Choir Logo" class="w-full h-full object-cover">
                        </div>
                    </div>
                    <div class="absolute -top-6 left-1/2 -translate-x-1/2 bg-amber-500 text-blue-950 w-12 h-12 rounded-full flex items-center justify-center shadow-lg border-2 border-white">
                        <i class="fa-solid fa-crown text-xl"></i>
                    </div>
                </div>
            </div>

            <span class="uppercase tracking-[0.6em] text-amber-400 font-bold text-sm mb-6 block drop-shadow-lg">AVE MARIA PURISIMA • SIN PECADO CONCEBIDA </span>
            
            <h1 class="font-cinzel text-5xl md:text-8xl font-black mb-4 leading-tight tracking-tight">
                QUEEN OF BIÑAN <br><span class="text-transparent bg-clip-text bg-gradient-to-r from-amber-200 via-yellow-400 to-amber-200">CHOIR</span>
            </h1>
            
            <h2 class="font-cursive text-4xl md:text-6xl text-blue-100 mb-12 drop-shadow-md">
                Nuestra Señora De La Paz y Buen Viaje
            </h2>
            
            <div class="flex flex-col md:flex-row gap-8 justify-center items-center">
                <a href="#gallery" class="btn-shine bg-amber-500 text-blue-950 px-14 py-5 rounded-full font-black text-sm uppercase tracking-[0.2em] shadow-xl">
                    Mag-alay ng Himig
                </a>
                <a href="#history" class="group flex items-center gap-3 font-bold hover:text-amber-400 transition">
                    <span class="w-12 h-[2px] bg-amber-400 transition-all group-hover:w-20"></span>
                    ALAMIN ANG KASAYSAYAN
                </a>
            </div>
        </div>

        <div class="absolute bottom-10 left-1/2 -translate-x-1/2 animate-bounce">
            <i class="fa-solid fa-chevron-down text-amber-400 text-2xl"></i>
        </div>
    </section>

    <section id="vision" class="py-32 bg-slate-50 relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-20 items-center">
            <div class="relative" data-aos="fade-right">
                <div class="absolute -top-10 -left-10 w-64 h-64 bg-blue-200 rounded-full blur-3xl opacity-40"></div>
                <div class="relative z-10 rounded-[2.5rem] overflow-hidden shadow-2xl border-[12px] border-white">
                    <img src="QBC.jpeg" alt="Queen of Biñan Choir Group" class="hover:scale-105 transition duration-1000 w-full h-auto">
                </div>
                <div class="absolute -bottom-10 -right-10 bg-white p-8 rounded-3xl shadow-2xl z-20 max-w-[260px] border-b-8 border-amber-500">
                    <p class="font-cursive text-3xl text-blue-700 mb-2">"Isang Tinig"</p>
                    <p class="text-xs font-bold text-slate-400 uppercase tracking-widest">Para sa Ina ng Kapayapaan</p>
                </div>
            </div>

            <div data-aos="fade-left">
                <h3 class="text-amber-600 font-bold tracking-widest mb-4 uppercase text-sm">Ang Aming Panata</h3>
                <h2 class="text-5xl md:text-6xl font-cinzel font-black text-blue-900 mb-8 leading-tight">Bakit Kami <br><span class="text-blue-600">Umaawit?</span></h2>
                
                <div class="space-y-10">
                    <div class="flex gap-6">
                        <div class="bg-blue-900 text-amber-400 w-16 h-16 rounded-2xl flex items-center justify-center shrink-0 shadow-xl">
                            <i class="fa-solid fa-dove text-2xl"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-xl text-blue-900 mb-2">Kapayapaan</h4>
                            <p class="text-slate-600 leading-relaxed">Ang aming musika ay dala ang mensahe ng kapayapaan mula sa aming patrona, ang Birhen ng De La Paz.</p>
                        </div>
                    </div>
                    
                    <div class="flex gap-6">
                        <div class="bg-amber-500 text-blue-950 w-16 h-16 rounded-2xl flex items-center justify-center shrink-0 shadow-xl">
                            <i class="fa-solid fa-hands-praying text-2xl"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-xl text-blue-900 mb-2">Panalangin</h4>
                            <p class="text-slate-600 leading-relaxed">"Bis orat qui cantat" - Pinapahalagahan namin ang turo na ang umaawit ay nagdarasal ng dalawang ulit.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="history" class="py-32 bg-white relative">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-20" data-aos="fade-up">
                <span class="text-amber-600 font-bold tracking-[0.5em] text-xs uppercase">Ang Aming Pinagmulan</span>
                <h2 class="text-5xl font-cinzel font-black text-blue-950 mt-4">Kasaysayan at Pamana</h2>
            </div>

            <div class="grid md:grid-cols-3 gap-10">
                <div class="history-card p-10 shadow-xl rounded-2xl" data-aos="fade-up" data-aos-delay="100">
                    <h4 class="text-amber-500 font-black text-3xl mb-6 font-cinzel">Pagsibol</h4>
                    <p class="text-slate-600 leading-relaxed">
                        Itinatag noong <strong>Abril 2019</strong> sa ilalim ng gabay ni <strong>Rev. Fr. Raul Matienzo</strong>. Nagsimula bilang <em>NSDP Youth Choir</em>, ang grupo ay binuo upang maglingkod sa mga Banal na Misa tuwing Sabado sa Parokya ng Nuestra Señora de la Paz y Buen Viaje.
                    </p>
                </div>

                <div class="history-card p-10 shadow-xl rounded-2xl border-blue-900" data-aos="fade-up" data-aos-delay="200">
                    <h4 class="text-blue-900 font-black text-3xl mb-6 font-cinzel">Paglago</h4>
                    <p class="text-slate-600 leading-relaxed">
                        Pinagsama ang sigla ng kabataan at karanasan ng mga bihasang mang-aawit. Sa kabila ng pagkakaiba, nagkaisa ang lahat sa turo ni San Agustin: <strong>"Ang umaawit para sa Diyos ay nagdarasal nang dalawang beses,"</strong> na nagsilbing pundasyon ng aming samahan.
                    </p>
                </div>

                <div class="history-card p-10 shadow-xl rounded-2xl" data-aos="fade-up" data-aos-delay="300">
                    <h4 class="text-amber-500 font-black text-3xl mb-6 font-cinzel">Kasalukuyan</h4>
                    <p class="text-slate-600 leading-relaxed">
                        Bilang simbolo ng pagkakaisa, ang koro ay pormal nang kinikilala bilang <strong>Queen of Biñan Choir</strong>. Patuloy kaming nag-aalay ng himig na may dangal sa bawat banal na pagdiriwang at kapistahan ng ating Mahal na Ina.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="gallery" class="py-32 bg-blue-950">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-20" data-aos="fade-up">
                <h2 class="text-amber-400 font-cursive text-5xl mb-4">Galeriya ng Pananampalataya</h2>
                <h3 class="text-white font-cinzel text-4xl font-bold tracking-widest uppercase">Mga Banal na Sandali</h3>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="md:col-span-2 md:row-span-2 relative group overflow-hidden rounded-[3rem] h-[650px] shadow-2xl" data-aos="zoom-in">
                    <img src="mamama.jepg.jpg" alt="Fiesta Performance" class="w-full h-full object-cover group-hover:scale-110 transition duration-1000">
                    <div class="absolute inset-0 bg-gradient-to-t from-blue-950 via-transparent to-transparent opacity-90"></div>
                    <div class="absolute bottom-12 left-12 text-white">
                        <span class="bg-amber-500 text-blue-950 px-5 py-2 rounded-full text-xs font-black uppercase mb-4 inline-block tracking-widest">Fiesta 2026</span>
                        <h4 class="text-4xl font-bold font-cinzel uppercase tracking-tighter">Himig para sa Langit</h4>
                    </div>
                </div>
                
                <div class="relative group overflow-hidden rounded-[2.5rem] h-[310px] shadow-2xl" data-aos="fade-left">
                    <img src="voyagers.jpeg" alt="QBC Voyagers" class="w-full h-full object-cover group-hover:scale-110 transition duration-700">
                </div>
                
                <div class="relative group overflow-hidden rounded-[2.5rem] h-[310px] shadow-2xl" data-aos="fade-left" data-aos-delay="200">
                    <img src="mahal na ina.jpeg" alt="The Patroness" class="w-full h-full object-cover group-hover:scale-110 transition duration-700">
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-32 bg-white">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <div class="inline-block bg-blue-50 p-6 rounded-full mb-8 shadow-inner">
                <i class="fa-solid fa-microphone-lines text-blue-600 text-4xl"></i>
            </div>
            <h2 class="text-5xl md:text-7xl font-cinzel font-black text-blue-950 mb-8" data-aos="fade-up">Sumapi sa aming <br><span class="text-amber-500">Koro</span></h2>
            <p class="text-xl text-slate-500 mb-12 max-w-2xl mx-auto leading-relaxed">Ang <strong>Queen of Biñan Choir</strong> ay laging bukas sa mga kabataang nagnanais mag-alay ng kanilang talento sa Mahal na Birhen.</p>
            
            <a href="https://www.facebook.com/profile.php?id=100089772245400" target="_blank" class="inline-flex items-center gap-4 bg-blue-600 text-white px-14 py-6 rounded-full font-black text-lg shadow-2xl hover:bg-blue-700 transition transform hover:-translate-y-2 uppercase tracking-widest">
                <i class="fa-brands fa-facebook-messenger text-2xl"></i>
                Message Us on Messenger
            </a>
        </div>
    </section>

    <footer class="bg-slate-950 text-white pt-24 pb-12 border-t-8 border-amber-500">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid md:grid-cols-3 gap-16 items-center text-center md:text-left mb-20">
                <div>
                    <h4 class="font-cinzel text-2xl font-black mb-4 tracking-tight uppercase">Queen of Biñan Choir</h4>
                    <p class="text-blue-300/80 text-sm italic font-light">"Ave Maria, gratia plena, Dominus tecum."</p>
                </div>
                <div class="flex justify-center space-x-10 text-3xl">
                    <a href="https://www.facebook.com/profile.php?id=100089772245400" class="hover:text-amber-400 transition transform hover:scale-110"><i class="fa-brands fa-facebook"></i></a>
                    <a href="#" class="hover:text-amber-400 transition transform hover:scale-110"><i class="fa-brands fa-instagram"></i></a>
                    <a href="#" class="hover:text-amber-400 transition transform hover:scale-110"><i class="fa-brands fa-youtube"></i></a>
                </div>
                <div class="md:text-right">
                    <p class="text-slate-400 text-xs font-bold tracking-widest uppercase">© 2026 QBC • Biñan, Laguna</p>
                    <p class="text-amber-500 text-[10px] uppercase font-black tracking-[0.4em] mt-3">Sacred Music for the Queen</p>
                </div>
            </div>

            <div class="border-t border-white/5 pt-10 text-center">
                <p class="text-slate-600 text-[10px] uppercase tracking-[0.3em] font-bold">
                    Website Crafted for Queen of Biñan Choir by 
                    <span class="text-amber-500 ml-1">Mr. John Harvey Marcilla Joaquin</span>
                </p>
            </div>
        </div>
    </footer>

    <script>
        AOS.init({
            duration: 1200,
            once: true,
            easing: 'ease-in-out'
        });
    </script>
</body>
</html>
