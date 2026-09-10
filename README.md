<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GUIH_RIBASZ | Gestor de Tráfego + Lifestyle</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@700&display=swap');
    body { font-family: 'Inter', sans-serif; }
    .logo-font { font-family: 'Playfair Display', serif; }
    .hero { background: linear-gradient(135deg, #6b21a8, #c026d3); }
  </style>
</head>
<body class="bg-zinc-950 text-white">

  <!-- NAVBAR -->
  <nav class="fixed top-0 w-full bg-zinc-950/90 backdrop-blur-lg z-50 border-b border-zinc-800">
    <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <div class="w-9 h-9 bg-violet-600 rounded-2xl flex items-center justify-center text-2xl">🎯</div>
        <span class="logo-font text-3xl font-bold tracking-tighter">GUH</span>
      </div>
      <div class="flex gap-8 text-sm font-medium">
        <a href="#sobre" class="hover:text-violet-400 transition">Sobre</a>
        <a href="#sucesso" class="hover:text-violet-400 transition">Sucesso</p>
        <a href="#servicos" class="hover:text-violet-400 transition">Serviços</a>
        <a href="#viagens" class="hover:text-violet-400 transition">Viagens</a>
        <a href="#contato" class="hover:text-violet-400 transition">Contato</a>
      </div>
      <a href="https://instagram.com/guih_ribasz" target="_blank" 
         class="bg-white text-black px-6 py-3 rounded-2xl font-semibold flex items-center gap-2 hover:bg-violet-500 hover:text-white transition">
        <i class="fab fa-instagram"></i> Ver meu perfil
      </a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="hero min-h-screen flex items-center pt-20">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
      <div>
        <h1 class="text-7xl font-bold leading-none tracking-tighter logo-font">
          GUIH_RIBASZ<br>
          <span class="text-violet-200">Gestor de Tráfego +<br>Lifestyle Real</span>
        </h1>
        <p class="mt-8 text-xl text-violet-200 max-w-md">
          Eu ajudo famílias e empreendedores a crescerem suas redes com conteúdo autêntico e tráfego orgânico que realmente converte.
        </p>
        <div class="flex gap-4 mt-12">
          <a href="#servicos" 
             class="bg-white text-black px-8 py-4 rounded-3xl font-semibold flex items-center gap-3 hover:scale-105 transition">
            Ver meus serviços
          </a>
          <a href="https://instagram.com/guih_ribasz" target="_blank"
             class="border border-white px-8 py-4 rounded-3xl font-semibold flex items-center gap-3 hover:bg-white hover:text-black transition">
            Ver meu Instagram
          </a>
        </div>
      </div>

      <div class="relative">
        <img src="https://picsum.photos/id/1015/800/600" alt="Guilherme Ribasz" 
             class="rounded-3xl shadow-2xl w-full">
        <div class="absolute -bottom-6 -right-6 bg-zinc-900 p-6 rounded-3xl border border-violet-500">
          <div class="flex items-center gap-4">
            <div class="text-4xl">👋</div>
            <div>
              <p class="font-semibold">Olá, eu sou o Guilherme!</p>
              <p class="text-sm text-violet-300">2.6 anos no Instagram • 1.881 views hoje</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SOBRE -->
  <section id="sobre" class="py-24 bg-zinc-900">
    <div class="max-w-7xl mx-auto px-6">
      <div class="grid md:grid-cols-12 gap-12 items-center">
        <div class="md:col-span-7">
          <h2 class="text-5xl font-bold tracking-tighter">Bem-vindo ao meu mundinho</h2>
          <p class="mt-8 text-xl text-zinc-400">
            Guilherme Ribasz Lima, 26 anos, Gestor de Tráfego e criador de conteúdo autêntico.<br><br>
            Meu foco é ajudar famílias a crescerem orgânicos e empreendedores a aumentarem suas conversões com Reels e Stories que conectam de verdade.
          </p>
          <div class="mt-12 grid grid-cols-3 gap-8 text-center">
            <div>
              <div class="text-5xl font-bold text-violet-400">1.881</div>
              <div class="text-sm mt-2">views totais</div>
            </div>
            <div>
              <div class="text-5xl font-bold text-violet-400">60%</div>
              <div class="text-sm mt-2">de seguidores reais</div>
            </div>
            <div>
              <div class="text-5xl font-bold text-violet-400">2.6</div>
              <div class="text-sm mt-2">anos crescendo</div>
            </div>
          </div>
        </div>

        <div class="md:col-span-5">
          <img src="https://picsum.photos/id/201/600/700" alt="Guilherme" 
               class="rounded-3xl shadow-2xl">
        </div>
      </div>
    </div>
  </section>

  <!-- MAIOR SUCESSO -->
  <section id="sucesso" class="py-24">
    <div class="max-w-7xl mx-auto px-6">
      <div class="bg-gradient-to-br from-violet-900 to-fuchsia-900 rounded-3xl p-12 text-center">
        <div class="inline-flex items-center gap-3 bg-white/10 px-8 py-2 rounded-3xl text-sm mb-6">
          <i class="fas fa-trophy text-yellow-400"></i>
          MAIOR PICADA DO MÊS
        </div>
        <h2 class="text-6xl font-bold">1.881 views</h2>
        <p class="mt-6 text-2xl text-violet-200">em apenas 90 dias • com Reels e Stories</p>
        <p class="mt-8 max-w-md mx-auto text-lg">
          O pico aconteceu em setembro 2026 com o conteúdo da nossa filha e das viagens.
        </p>
      </div>
    </div>
  </section>

  <!-- SERVIÇOS -->
  <section id="servicos" class="py-24 bg-zinc-900">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold tracking-tighter text-center mb-16">O que eu entrego</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-zinc-800 p-8 rounded-3xl hover:-translate-y-3 transition">
          <div class="text-violet-400 text-4xl mb-6">📈</div>
          <h3 class="text-2xl font-semibold">Gestão de Tráfego</h3>
          <p class="mt-4 text-zinc-400">Reels + Stories que convertem • Estratégia completa • Relatórios mensais</p>
        </div>
        <div class="bg-zinc-800 p-8 rounded-3xl hover:-translate-y-3 transition">
          <div class="text-violet-400 text-4xl mb-6">🎯</div>
          <h3 class="text-2xl font-semibold">Conteúdo Autêntico</h3>
          <p class="mt-4 text-zinc-400">Família, viagens, lifestyle • Ideias de captions • Edição profissional</p>
        </div>
        <div class="bg-zinc-800 p-8 rounded-3xl hover:-translate-y-3 transition">
          <div class="text-violet-400 text-4xl mb-6">📊</div>
          <h3 class="text-2xl font-semibold">Crescimento Orgânico</h3>
          <p class="mt-4 text-zinc-400">Técnicas de algoritmo • Engajamento • 60%+ de seguidores reais</p>
        </div>
      </div>
    </div>
  </section>

  <!-- DEPOIMENTOS -->
  <section class="py-24">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold tracking-tighter text-center mb-12">O que meus clientes dizem</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <p class="italic">"Melhor gestão de tráfego que já tive. Em 30 dias dobramos as views."</p>
          <div class="mt-8 flex items-center gap-4">
            <div class="w-12 h-12 bg-violet-500 rounded-2xl"></div>
            <div>
              <p class="font-semibold">Ana Clara</p>
              <p class="text-sm text-zinc-400">Mãe de 2 filhos • Portugal</p>
            </div>
          </div>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <p class="italic">"O Guilherme transformou nosso perfil. Hoje vendemos mais só com conteúdo dele."</p>
          <div class="mt-8 flex items-center gap-4">
            <div class="w-12 h-12 bg-violet-500 rounded-2xl"></div>
            <div>
              <p class="font-semibold">João Mendes</p>
              <p class="text-sm text-zinc-400">Empreendedor • Espanha</p>
            </div>
          </div>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <p class="italic">"Sério, único gestor que entende família + tráfego. Recomendo 100%!"</p>
          <div class="mt-8 flex items-center gap-4">
            <div class="w-12 h-12 bg-violet-500 rounded-2xl"></div>
            <div>
              <p class="font-semibold">Sara Oliveira</p>
              <p class="text-sm text-zinc-400">Influencer • Brasil</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- VIAGENS -->
  <section id="viagens" class="py-24 bg-zinc-900">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold tracking-tighter text-center mb-12">Nossas viagens (Espanha & Portugal)</h2>
      <div class="grid md:grid-cols-4 gap-6">
        <div class="bg-zinc-800 rounded-3xl overflow-hidden">
          <img src="https://picsum.photos/id/201/600/400" class="w-full" alt="Espanha">
          <p class="p-4 font-semibold">Espanha 🇪🇸</p>
        </div>
        <div class="bg-zinc-800 rounded-3xl overflow-hidden">
          <img src="https://picsum.photos/id/251/600/400" class="w-full" alt="Portugal">
          <p class="p-4 font-semibold">Portugal 🇵🇹</p>
        </div>
        <div class="bg-zinc-800 rounded-3xl overflow-hidden">
          <img src="https://picsum.photos/id/29/600/400" class="w-full" alt="A Soma">
          <p class="p-4 font-semibold">A Soma ❤️</p>
        </div>
        <div class="bg-zinc-800 rounded-3xl overflow-hidden">
          <img src="https://picsum.photos/id/160/600/400" class="w-full" alt="Eu">
          <p class="p-4 font-semibold">Eu com a filha</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTATO -->
  <section id="contato" class="py-24">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-5xl font-bold tracking-tighter">Bora crescer juntos?</h2>
      <p class="mt-6 text-xl text-zinc-400 max-w-md mx-auto">
        Me manda mensagem agora e vamos planejar seu próximo pico de views!
      </p>
      
      <div class="mt-12 flex justify-center gap-6">
        <a href="https://instagram.com/guih_ribasz" target="_blank" 
           class="flex items-center gap-4 bg-zinc-900 hover:bg-zinc-800 px-10 py-6 rounded-3xl transition">
          <i class="fab fa-instagram text-3xl"></i>
          <div>
            <p class="font-semibold">@guih_ribasz</p>
            <p class="text-sm">Abrir Instagram</p>
          </div>
        </a>
        
        <a href="https://wa.me/351912345678" target="_blank" 
           class="flex items-center gap-4 bg-emerald-500 hover:bg-emerald-600 px-10 py-6 rounded-3xl transition">
          <i class="fab fa-whatsapp text-3xl"></i>
          <div>
            <p class="font-semibold">WhatsApp</p>
            <p class="text-sm">Fale comigo</p>
          </div>
        </a>
      </div>

      <p class="mt-16 text-sm text-zinc-500">© 2026 Guilherme Ribasz Lima • Criado com ❤️ para você</p>
    </div>
  </section>

</body>
</html>