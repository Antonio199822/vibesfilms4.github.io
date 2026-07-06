<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anthony Makuta | VIBESFILMS - Portfolio Officiel</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body { background-color: #080808; color: #e0e0e0; font-family: 'Inter', sans-serif; }
        .font-serif { font-family: 'Playfair Display', serif; }
        .text-gold { color: #d4af37; }
        .bg-gold { background-color: #d4af37; }
        .border-gold { border-color: #d4af37; }
        .nav-link:hover { color: #d4af37; transition: 0.3s; }
        .hero-gradient { background: linear-gradient(180deg, rgba(8,8,8,0) 0%, rgba(8,8,8,1) 100%); }
    </style>
</head>
<body class="overflow-x-hidden">

    <nav class="fixed w-full z-50 px-8 py-6 flex justify-between items-center bg-black/80 backdrop-blur-md">
        <div class="text-2xl font-bold tracking-tighter uppercase font-serif text-gold">VIBESFILMS</div>
        <div class="hidden md:flex space-x-10 text-sm font-light uppercase tracking-widest">
            <a href="#about" class="nav-link">Bio</a>
            <a href="#experience" class="nav-link">Expérience</a>
            <a href="#gear" class="nav-link">Matériel</a>
            <a href="#contact" class="nav-link text-gold">Contact</a>
        </div>
    </nav>

    <section class="h-screen flex items-center justify-center relative bg-center bg-cover" style="background-image: url('http://googleusercontent.com/image_collection/image_retrieval/12335226969121906094');">
        <div class="absolute inset-0 bg-black/60"></div>
        <div class="relative z-10 text-center px-4">
            <h1 class="text-6xl md:text-8xl font-serif mb-4">Anthony Makuta</h1>
            <p class="text-gold text-lg md:text-2xl tracking-[0.3em] uppercase font-light">Réalisateur & Directeur de la Photographie</p>
            <div class="mt-12 flex justify-center space-x-6">
                <a href="#experience" class="px-8 py-3 border border-white/20 hover:border-gold transition uppercase text-xs tracking-widest">Voir mon parcours</a>
            </div>
        </div>
    </section>

    <section id="about" class="py-32 px-8 max-w-6xl mx-auto grid md:grid-cols-2 gap-20 items-center">
        <div>
            <span class="text-gold uppercase tracking-widest text-sm mb-4 block">— À propos</span>
            <h2 class="text-4xl font-serif mb-8">Vidéaste Pro Full-Stack & Expert DaVinci Resolve</h2>
            <p class="text-gray-400 leading-relaxed mb-6">
                Diplômé en Design & Multimédia avec distinction (75%), j'ai forgé mon regard à travers 5 années de production intensive. Je ne me contente pas de filmer : je crée des émotions.
            </p>
            <p class="text-gray-400 leading-relaxed">
                Expert DaVinci Resolve, je maîtrise l'intégralité du workflow : montage cinématique, colorimétrie avancée (grading), sound design et effets visuels.
            </p>
        </div>
        <div class="grid grid-cols-2 gap-4">
            <div class="bg-zinc-900 p-8 rounded shadow-2xl border-b-2 border-gold">
                <div class="text-3xl font-bold mb-2">5+</div>
                <div class="text-xs uppercase tracking-widest text-gray-500">Années d'Expérience</div>
            </div>
            <div class="bg-zinc-900 p-8 rounded shadow-2xl">
                <div class="text-3xl font-bold mb-2">75%</div>
                <div class="text-xs uppercase tracking-widest text-gray-500">Graduation ISAM</div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-32 bg-zinc-950 px-8">
        <div class="max-w-4xl mx-auto">
            <h3 class="text-center font-serif text-4xl mb-20">Chronologie de Carrière</h3>
            <div class="space-y-16 border-l border-zinc-800 pl-10 relative">
                <div class="relative">
                    <div class="absolute -left-[45px] top-1 w-2 h-2 rounded-full bg-gold shadow-[0_0_10px_#d4af37]"></div>
                    <span class="text-gold text-xs font-bold mb-2 block uppercase">Fév 2026 — Juin 2026</span>
                    <h4 class="text-xl font-bold">Directeur de la Photographie — Nexyor Sarl</h4>
                    <p class="text-gray-500 mt-2 italic">Direction artistique, gestion lumière et esthétique visuelle.</p>
                </div>
                <div class="relative">
                    <div class="absolute -left-[45px] top-1 w-2 h-2 rounded-full bg-zinc-700"></div>
                    <span class="text-zinc-500 text-xs font-bold mb-2 block uppercase">2024 — 2025</span>
                    <h4 class="text-xl font-bold">Vidéaste Corporate — Nexyor Sarl</h4>
                </div>
                <div class="relative">
                    <div class="absolute -left-[45px] top-1 w-2 h-2 rounded-full bg-zinc-700"></div>
                    <span class="text-zinc-500 text-xs font-bold mb-2 block uppercase">Jan — Mai</span>
                    <h4 class="text-xl font-bold">Vidéaste Marketing — Liberty Mamaison</h4>
                </div>
            </div>
        </div>
    </section>

    <section id="gear" class="py-32 px-8 max-w-7xl mx-auto">
        <div class="text-center mb-20">
            <h3 class="text-4xl font-serif">Mon Arsenal Technique</h3>
            <p class="text-gray-500 mt-4 uppercase tracking-[0.2em] text-xs">Outils haut de gamme pour des résultats premium</p>
        </div>
        <div class="grid md:grid-cols-3 gap-8">
            <div class="group overflow-hidden relative">
                <img src="http://googleusercontent.com/image_collection/image_retrieval/7321843202941906737" class="w-full h-80 object-cover grayscale group-hover:grayscale-0 transition duration-700" alt="Camera Gear">
                <div class="absolute inset-0 bg-black/40 p-8 flex flex-col justify-end">
                    <h5 class="font-bold text-xl">Cinéma & Mirrorless</h5>
                    <p class="text-sm text-gray-300 mt-2">BM 6K Pro, Sony A7MIV, Lumix S5MIIX</p>
                </div>
            </div>
            <div class="group overflow-hidden relative">
                <img src="http://googleusercontent.com/image_collection/image_retrieval/10696211476610167501" class="w-full h-80 object-cover grayscale group-hover:grayscale-0 transition duration-700" alt="Drone Gear">
                <div class="absolute inset-0 bg-black/40 p-8 flex flex-col justify-end">
                    <h5 class="font-bold text-xl">Air & Stabilisation</h5>
                    <p class="text-sm text-gray-300 mt-2">DJI Mini 4 Pro, DJI RS4 Pro</p>
                </div>
            </div>
            <div class="group overflow-hidden relative">
                <img src="http://googleusercontent.com/image_collection/image_retrieval/12197478572909188252" class="w-full h-80 object-cover grayscale group-hover:grayscale-0 transition duration-700" alt="Editing Suite">
                <div class="absolute inset-0 bg-black/40 p-8 flex flex-col justify-end">
                    <h5 class="font-bold text-xl">Post-Production</h5>
                    <p class="text-sm text-gray-300 mt-2">MacBook M4, Razer Blade, DaVinci Suite</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="py-20 border-t border-zinc-900 text-center">
        <h2 class="font-serif text-3xl mb-10">Restons connectés</h2>
        <div class="flex justify-center space-x-12 mb-12 text-2xl">
            <a href="https://www.instagram.com/anthonius.antonio" class="hover:text-gold transition"><i class="fab fa-instagram"></i></a>
            <a href="https://www.youtube.com/@antonioanthonius1717" class="hover:text-gold transition"><i class="fab fa-youtube"></i></a>
            <a href="https://www.tiktok.com/@vibesfilms4" class="hover:text-gold transition"><i class="fab fa-tiktok"></i></a>
        </div>
        <p class="text-gray-600 text-xs tracking-widest uppercase">© 2026 VIBESFILMS | Anthony Makuta</p>
    </footer>

</body>
</html>
