<!DOCTYPE html>
<html lang="nl" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Black M | Continu NIS2-Monitoring voor MKB</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #0a0a0a; color: #ffffff; }
        .gradient-text { background: linear-gradient(90deg, #00ff87, #60efff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .hero-glow { position: absolute; top: -10%; left: 50%; transform: translateX(-50%); width: 600px; height: 300px; background: rgba(0, 255, 135, 0.1); filter: blur(100px); z-index: -1; }
    </style>
</head>
<body class="font-sans antialiased">
    <div class="hero-glow"></div>
    
    <nav class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
        <div class="text-2xl font-bold tracking-tighter">Black <span class="text-[#00ff87]">M</span></div>
        <div class="hidden md:flex space-x-8 text-sm font-medium text-gray-400">
            <a href="#werking" class="hover:text-white transition">Werking</a>
            <a href="#compliance" class="hover:text-white transition">NIS2-Check</a>
            <a href="mailto:jardan@blackm.nl" class="hover:text-white transition">Contact</a>
        </div>
        <a href="#leads" class="bg-white text-black px-5 py-2 rounded-full text-sm font-bold hover:bg-[#00ff87] transition shadow-lg shadow-white/5">Beta Toegang</a>
    </nav>

    <header class="max-w-4xl mx-auto text-center mt-20 px-4">
        <div class="inline-block px-4 py-1.5 mb-6 border border-gray-800 rounded-full text-xs font-semibold uppercase tracking-widest text-[#00ff87] bg-black/50">
            AI-Gedreven Security voor MKB Nederland
        </div>
        <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight mb-8 leading-tight">
            Continu <span class="gradient-text">NIS2-Monitoring</span> zonder de stress.
        </h1>
        <p class="text-gray-400 text-lg md:text-xl mb-10 max-w-2xl mx-auto leading-relaxed">
            Black M is de 'always-on' security agent die uw bedrijfsworkflow bewaakt, risico's signaleert en compliance automatiseert.
        </p>
        
        <section id="leads" class="max-w-md mx-auto bg-[#111] p-1 rounded-2xl border border-gray-800 focus-within:border-[#00ff87] transition shadow-2xl">
            <form action="mailto:info@blackm.nl" method="POST" enctype="text/plain" class="flex p-1">
                <input type="email" placeholder="uw@bedrijfsemail.nl" required class="bg-transparent border-none focus:ring-0 text-white flex-1 px-4 py-3 outline-none">
                <button type="submit" class="bg-[#00ff87] text-black px-6 py-3 rounded-xl font-bold hover:scale-105 transition">Vraag Beta Aan</button>
            </form>
        </section>
        <p class="mt-4 text-xs text-gray-500">Word lid van de exclusieve wachtlijst voor Q2 2026.</p>
    </header>

    <main id="werking" class="max-w-7xl mx-auto grid md:grid-cols-3 gap-8 px-8 py-32">
        <div class="bg-[#111] p-8 rounded-3xl border border-gray-900 hover:border-gray-700 transition">
            <div class="w-12 h-12 bg-[#00ff87]/10 rounded-xl flex items-center justify-center mb-6 text-[#00ff87]">🛡️</div>
            <h3 class="text-xl font-bold mb-4">Zero-Touch Monitoring</h3>
            <p class="text-gray-400 leading-relaxed">AI-analyse van workflowgedrag zonder de privacy van medewerkers te schenden.</p>
        </div>
        <div class="bg-[#111] p-8 rounded-3xl border border-gray-900 hover:border-gray-700 transition">
            <div class="w-12 h-12 bg-blue-500/10 rounded-xl flex items-center justify-center mb-6 text-blue-400">📋</div>
            <h3 class="text-xl font-bold mb-4">Directe NIS2-Check</h3>
            <p class="text-gray-400 leading-relaxed">Real-time signalering van security compliance risico's voor de nieuwe EU-richtlijn.</p>
        </div>
        <div class="bg-[#111] p-8 rounded-3xl border border-gray-900 hover:border-gray-700 transition">
            <div class="w-12 h-12 bg-purple-500/10 rounded-xl flex items-center justify-center mb-6 text-purple-400">🤖</div>
            <h3 class="text-xl font-bold mb-4">AI Tool Audit</h3>
            <p class="text-gray-400 leading-relaxed">Monitoring van schaduw-IT en onveilig gebruik van AI-tools binnen uw organisatie.</p>
        </div>
    </main>

    <footer class="text-center py-20 border-t border-gray-900">
        <p class="text-gray-600 text-sm">© 2026 Black M - Cybersecurity voor MKB Nederland.</p>
    </footer>
</body>
</html>
