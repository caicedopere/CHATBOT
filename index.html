<!DOCTYPE html>
<html lang="es" class="h-full bg-slate-950 text-slate-100">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AURA Atelier - Asistente de Moda AI & Boutique</title>

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              50: '#fdf4ff',
              100: '#fae8ff',
              400: '#e879f9',
              500: '#d946ef',
              600: '#c026d3',
              900: '#701a75',
              gold: '#fbbf24',
            }
          },
          fontFamily: {
            sans: ['Plus Jakarta Sans', 'sans-serif'],
            serif: ['Playfair Display', 'serif'],
          }
        }
      }
    }
  </script>

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..800;1,400..800&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <style>
    /* Custom Scrollbar */
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: rgba(15, 23, 42, 0.6);
    }
    ::-webkit-scrollbar-thumb {
      background: rgba(217, 70, 239, 0.3);
      border-radius: 9999px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: rgba(217, 70, 239, 0.6);
    }

    /* Animation Utilities */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(8px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .animate-fade-in {
      animation: fadeIn 0.3s cubic-bezier(0.16, 1, 0.3, 1) forwards;
    }
    .glass-panel {
      background: rgba(15, 23, 42, 0.75);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border: 1px solid rgba(255, 255, 255, 0.08);
    }
    .glass-card {
      background: rgba(30, 41, 59, 0.5);
      backdrop-filter: blur(8px);
      border: 1px solid rgba(255, 255, 255, 0.05);
    }
  </style>
</head>
<body class="h-full flex flex-col font-sans antialiased bg-slate-950 text-slate-100 overflow-x-hidden selection:bg-brand-500 selection:text-white">

  <header class="sticky top-0 z-40 w-full glass-panel border-b border-slate-800/80">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
      <!-- Logo & Brand Name -->
      <div class="flex items-center gap-3">
        <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-indigo-600 flex items-center justify-center shadow-lg shadow-brand-500/20">
          <i data-lucide="sparkles" class="w-5 h-5 text-white"></i>
        </div>
        <div>
          <span class="font-serif text-xl tracking-wider font-bold bg-clip-text text-transparent bg-gradient-to-r from-white via-slate-200 to-brand-400">
            AURA ATELIER
          </span>
          <span class="block text-[10px] tracking-widest text-slate-400 font-medium uppercase">Personal Fashion AI</span>
        </div>
      </div>

      <!-- Navigation Links -->
      <nav class="hidden md:flex items-center gap-1 bg-slate-900/60 p-1.5 rounded-full border border-slate-800">
        <button id="nav-btn-chat" onclick="switchView('chat')" class="nav-tab px-4 py-1.5 rounded-full text-xs font-semibold tracking-wide transition-all duration-200 bg-brand-600 text-white shadow-sm flex items-center gap-2">
          <i data-lucide="bot" class="w-3.5 h-3.5"></i>
          <span>Asistente AURA</span>
        </button>
        <button id="nav-btn-catalog" onclick="switchView('catalog')" class="nav-tab px-4 py-1.5 rounded-full text-xs font-semibold tracking-wide transition-all duration-200 text-slate-400 hover:text-white flex items-center gap-2">
          <i data-lucide="shopping-bag" class="w-3.5 h-3.5"></i>
          <span>Colección & Catalogo</span>
        </button>
        <button id="nav-btn-ai-studio" onclick="switchView('ai-studio')" class="nav-tab px-4 py-1.5 rounded-full text-xs font-semibold tracking-wide transition-all duration-200 text-slate-400 hover:text-white flex items-center gap-2">
          <i data-lucide="wand-2" class="w-3.5 h-3.5"></i>
          <span>AI Look Studio</span>
        </button>
      </nav>

      <!-- Cart & Mobile Actions -->
      <div class="flex items-center gap-3">
        <button onclick="toggleCartDrawer(true)" class="relative p-2.5 rounded-xl bg-slate-900 hover:bg-slate-800 border border-slate-800 text-slate-200 transition-colors">
          <i data-lucide="shopping-cart" class="w-5 h-5"></i>
          <span id="cart-badge" class="hidden absolute -top-1.5 -right-1.5 w-5 h-5 rounded-full bg-brand-500 text-white text-[11px] font-bold flex items-center justify-center border-2 border-slate-950">
            0
          </span>
        </button>
      </div>
    </div>

    <!-- Mobile Navigation Tab Bar -->
    <div class="md:hidden flex border-t border-slate-800/80 bg-slate-950/90 px-2 py-1 justify-around">
      <button onclick="switchView('chat')" class="flex flex-col items-center py-1.5 px-3 text-xs text-brand-400 font-medium">
        <i data-lucide="message-square" class="w-4 h-4 mb-0.5"></i>
        <span>Chat AI</span>
      </button>
      <button onclick="switchView('catalog')" class="flex flex-col items-center py-1.5 px-3 text-xs text-slate-400 font-medium">
        <i data-lucide="grid" class="w-4 h-4 mb-0.5"></i>
        <span>Catálogo</span>
      </button>
      <button onclick="switchView('ai-studio')" class="flex flex-col items-center py-1.5 px-3 text-xs text-slate-400 font-medium">
        <i data-lucide="sparkles" class="w-4 h-4 mb-0.5"></i>
        <span>Studio Outfit</span>
      </button>
    </div>
  </header>

  <main class="flex-1 max-w-7xl w-full mx-auto p-3 sm:p-6 flex flex-col min-h-0 overflow-hidden relative">

    <!-- ==================== VISTA 1: CHATBOT INTERACTIVO DE MODA ==================== -->
    <section id="view-chat" class="view-panel h-full flex flex-col md:flex-row gap-6 overflow-hidden">
      
      <!-- Panel de Información & Sugerencias (Izquierda en Desktop) -->
      <div class="hidden lg:flex flex-col w-80 shrink-0 gap-4">
        <!-- Tarjeta Perfil AURA -->
        <div class="glass-card rounded-2xl p-5 border border-slate-800">
          <div class="flex items-center gap-3 mb-4">
            <div class="relative">
              <div class="w-12 h-12 rounded-full bg-gradient-to-tr from-brand-500 to-amber-500 p-0.5">
                <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=150&auto=format&fit=crop&q=80" alt="AURA AI" class="w-full h-full object-cover rounded-full">
              </div>
              <span class="absolute bottom-0 right-0 w-3.5 h-3.5 bg-emerald-500 border-2 border-slate-900 rounded-full"></span>
            </div>
            <div>
              <h3 class="font-serif font-bold text-slate-100">AURA Personal Stylist</h3>
              <p class="text-xs text-brand-400 font-medium">Moda & Tendencias 2026</p>
            </div>
          </div>
          <p class="text-xs text-slate-400 leading-relaxed">
            Hola, soy AURA. Te ayudo a crear combinaciones únicas, resolver dudas de tallas o recomendar prendas ideales para cualquier evento.
          </p>
        </div>

        <!-- Sugerencias de Consultas Rápidas -->
        <div class="glass-card rounded-2xl p-5 border border-slate-800 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xs font-bold uppercase tracking-wider text-slate-400 mb-3 flex items-center gap-2">
              <i data-lucide="compass" class="w-4 h-4 text-brand-400"></i>
              Consultas Frecuentes
            </h4>
            <div class="space-y-2">
              <button onclick="sendQuickPrompt('¿Qué ropa me recomiendas para un evento semi-formal de noche?')" class="w-full text-left p-2.5 rounded-xl bg-slate-900/80 hover:bg-slate-800 text-xs text-slate-300 border border-slate-800/80 transition-all flex items-center justify-between group">
                <span>✨ Outfit semi-formal de noche</span>
                <i data-lucide="chevron-right" class="w-3.5 h-3.5 text-slate-500 group-hover:text-brand-400 transition-colors"></i>
              </button>
              <button onclick="sendQuickPrompt('Muéstrame la colección streetwear urbana disponible')" class="w-full text-left p-2.5 rounded-xl bg-slate-900/80 hover:bg-slate-800 text-xs text-slate-300 border border-slate-800/80 transition-all flex items-center justify-between group">
                <span>🧢 Tendencias Streetwear</span>
                <i data-lucide="chevron-right" class="w-3.5 h-3.5 text-slate-500 group-hover:text-brand-400 transition-colors"></i>
              </button>
              <button onclick="sendQuickPrompt('¿Cómo saber mi talla adecuada y políticas de cambios?')" class="w-full text-left p-2.5 rounded-xl bg-slate-900/80 hover:bg-slate-800 text-xs text-slate-300 border border-slate-800/80 transition-all flex items-center justify-between group">
                <span>📏 Guía de Tallas & Cambios</span>
                <i data-lucide="chevron-right" class="w-3.5 h-3.5 text-slate-500 group-hover:text-brand-400 transition-colors"></i>
              </button>
              <button onclick="sendQuickPrompt('Genera una idea de outfit con chaqueta de cuero y botas')" class="w-full text-left p-2.5 rounded-xl bg-slate-900/80 hover:bg-slate-800 text-xs text-slate-300 border border-slate-800/80 transition-all flex items-center justify-between group">
                <span>🧥 Combinar Chaqueta de Cuero</span>
                <i data-lucide="chevron-right" class="w-3.5 h-3.5 text-slate-500 group-hover:text-brand-400 transition-colors"></i>
              </button>
            </div>
          </div>

          <!-- Promo Banner Interno -->
          <div class="mt-4 p-3 rounded-xl bg-gradient-to-r from-brand-900/40 to-indigo-900/40 border border-brand-500/20 text-center">
            <span class="text-[11px] font-semibold text-brand-300 block">Envío Gratis en compras > $75 USD</span>
            <span class="text-[10px] text-slate-400">Usa el cupón <strong class="text-amber-400 font-mono">AURA10</strong> para 10% OFF</span>
          </div>
        </div>
      </div>

      <!-- Ventana Principal del Chat -->
      <div class="flex-1 glass-panel rounded-2xl flex flex-col h-full border border-slate-800 overflow-hidden relative">
        
        <!-- Header del Chat (Móvil & Desktop) -->
        <div class="p-4 border-b border-slate-800 bg-slate-900/50 flex items-center justify-between">
          <div class="flex items-center gap-3">
            <div class="w-9 h-9 rounded-full bg-gradient-to-tr from-brand-500 to-indigo-500 flex items-center justify-center font-bold text-white text-sm shadow-md">
              A
            </div>
            <div>
              <h2 class="text-sm font-bold text-slate-100 flex items-center gap-2">
                Style Assistant - AURA AI
                <span class="text-[10px] px-2 py-0.5 rounded-full bg-emerald-500/10 text-emerald-400 border border-emerald-500/20 font-medium">En línea</span>
              </h2>
              <p class="text-[11px] text-slate-400">Asesoría de estilo en tiempo real con Gemini AI</p>
            </div>
          </div>
          <button onclick="clearChat()" class="text-xs text-slate-400 hover:text-rose-400 transition-colors flex items-center gap-1 bg-slate-800/50 px-2.5 py-1.5 rounded-lg border border-slate-700/50" title="Reiniciar Conversación">
            <i data-lucide="trash-2" class="w-3.5 h-3.5"></i>
            <span class="hidden sm:inline">Limpiar</span>
          </button>
        </div>

        <!-- Area de Mensajes del Chat -->
        <div id="chat-messages" class="flex-1 p-4 overflow-y-auto space-y-4">
          <!-- Mensaje de bienvenida inicial generado por JS -->
        </div>

        <!-- Chips de Acción Rápida (Sugerencias móviles / dinámicas) -->
        <div id="quick-chips" class="px-4 py-2 bg-slate-900/30 border-t border-slate-800/50 flex gap-2 overflow-x-auto no-scrollbar text-xs">
          <button onclick="sendQuickPrompt('¿Qué outfits están en tendencia este mes?')" class="shrink-0 px-3 py-1.5 rounded-full bg-slate-800/80 hover:bg-brand-900/50 border border-slate-700 text-slate-300 hover:text-brand-300 transition-all">
            🔥 Tendencias del mes
          </button>
          <button onclick="sendQuickPrompt('Ayúdame a armar un look formal masculino')" class="shrink-0 px-3 py-1.5 rounded-full bg-slate-800/80 hover:bg-brand-900/50 border border-slate-700 text-slate-300 hover:text-brand-300 transition-all">
            👔 Look Formal Hombre
          </button>
          <button onclick="sendQuickPrompt('Recomiéndame un vestido para graduación o cena elegante')" class="shrink-0 px-3 py-1.5 rounded-full bg-slate-800/80 hover:bg-brand-900/50 border border-slate-700 text-slate-300 hover:text-brand-300 transition-all">
            👗 Vestido Elegante
          </button>
          <button onclick="sendQuickPrompt('¿Cuál es su política de devoluciones?')" class="shrink-0 px-3 py-1.5 rounded-full bg-slate-800/80 hover:bg-brand-900/50 border border-slate-700 text-slate-300 hover:text-brand-300 transition-all">
            📦 Devoluciones
          </button>
        </div>

        <!-- Formulario de Entrada del Chat -->
        <form id="chat-form" onsubmit="handleChatSubmit(event)" class="p-3 sm:p-4 border-t border-slate-800 bg-slate-900/80 flex items-center gap-2">
          <input type="text" id="chat-input" placeholder="Pregunta sobre outfits, tallas, combinaciones o prendas..." class="flex-1 bg-slate-950 border border-slate-700 rounded-xl px-4 py-3 text-xs sm:text-sm text-slate-100 placeholder-slate-500 focus:outline-none focus:border-brand-500 focus:ring-1 focus:ring-brand-500 transition-all">
          <button type="submit" id="chat-send-btn" class="px-5 py-3 rounded-xl bg-gradient-to-r from-brand-600 to-indigo-600 hover:from-brand-500 hover:to-indigo-500 text-white font-semibold text-xs sm:text-sm transition-all shadow-lg shadow-brand-500/20 flex items-center justify-center gap-2 shrink-0">
            <span>Enviar</span>
            <i data-lucide="send" class="w-4 h-4"></i>
          </button>
        </form>
      </div>
    </section>

    <!-- ==================== VISTA 2: CATÁLOGO DE PRODUCTOS ==================== -->
    <section id="view-catalog" class="view-panel hidden h-full flex flex-col overflow-y-auto pr-1">
      <!-- Filtros y Buscador -->
      <div class="glass-card rounded-2xl p-4 mb-6 border border-slate-800 flex flex-col sm:flex-row items-center justify-between gap-4 shrink-0">
        <!-- Buscador -->
        <div class="relative w-full sm:w-80">
          <i data-lucide="search" class="w-4 h-4 text-slate-400 absolute left-3 top-3.5"></i>
          <input type="text" id="catalog-search" oninput="filterCatalog()" placeholder="Buscar prendas por nombre o estilo..." class="w-full bg-slate-900 border border-slate-700 rounded-xl pl-9 pr-4 py-2.5 text-xs text-slate-100 placeholder-slate-500 focus:outline-none focus:border-brand-500">
        </div>

        <!-- Categorías Pills -->
        <div class="flex items-center gap-2 overflow-x-auto w-full sm:w-auto pb-1 sm:pb-0 no-scrollbar" id="category-filters">
          <button onclick="setCategoryFilter('all')" class="cat-chip active px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-brand-600 text-white transition-all whitespace-nowrap">
            Todos
          </button>
          <button onclick="setCategoryFilter('formal')" class="cat-chip px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-slate-800/80 text-slate-400 hover:text-white transition-all whitespace-nowrap">
            Formal
          </button>
          <button onclick="setCategoryFilter('streetwear')" class="cat-chip px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-slate-800/80 text-slate-400 hover:text-white transition-all whitespace-nowrap">
            Streetwear
          </button>
          <button onclick="setCategoryFilter('casual')" class="cat-chip px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-slate-800/80 text-slate-400 hover:text-white transition-all whitespace-nowrap">
            Casual
          </button>
          <button onclick="setCategoryFilter('calzado')" class="cat-chip px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-slate-800/80 text-slate-400 hover:text-white transition-all whitespace-nowrap">
            Calzado
          </button>
        </div>
      </div>

      <!-- Grid de Productos -->
      <div id="catalog-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6 pb-12">
        <!-- Generado dinámicamente -->
      </div>
    </section>

    <!-- ==================== VISTA 3: AI LOOK STUDIO (GENERADOR DE OUTFITS) ==================== -->
    <section id="view-ai-studio" class="view-panel hidden h-full flex flex-col overflow-y-auto">
      <div class="glass-panel rounded-2xl p-6 border border-slate-800 max-w-4xl mx-auto w-full space-y-6">
        <div class="text-center space-y-2">
          <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brand-500/10 text-brand-300 border border-brand-500/20 text-xs font-semibold">
            <i data-lucide="sparkles" class="w-3.5 h-3.5"></i>
            Generador Visual de Outfits
          </div>
          <h2 class="font-serif text-2xl sm:text-3xl font-bold text-white">Visualiza tu Outfit Soñado con IA</h2>
          <p class="text-xs sm:text-sm text-slate-400 max-w-xl mx-auto">
            Describe el evento, clima o concepto que buscas y la IA de Imagen genera un prototipo fotográfico de outfit exclusivo.
          </p>
        </div>

        <!-- Contenedor del Generador -->
        <div class="space-y-4">
          <div class="flex flex-col sm:flex-row gap-3">
            <input type="text" id="ai-studio-prompt" placeholder="Ej: Outfit de alta costura negro para pasarela urbana con abrigo largo y gafas futuristas..." class="flex-1 bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-xs sm:text-sm text-slate-100 placeholder-slate-500 focus:outline-none focus:border-brand-500">
            <button onclick="generateAIStudioOutfit()" id="btn-studio-generate" class="px-6 py-3 rounded-xl bg-gradient-to-r from-amber-500 via-brand-600 to-indigo-600 hover:opacity-90 text-white font-bold text-xs sm:text-sm shadow-lg shadow-brand-500/20 flex items-center justify-center gap-2 shrink-0 transition-all">
              <i data-lucide="wand-2" class="w-4 h-4"></i>
              <span>Generar Outfit</span>
            </button>
          </div>

          <!-- Sugerencias de prompts -->
          <div class="flex flex-wrap gap-2 text-xs text-slate-400">
            <span class="text-slate-500 font-medium">Ideas de prueba:</span>
            <button onclick="fillStudioPrompt('Look minimalista de verano lino blanco para resort en la playa')" class="hover:text-brand-300 underline underline-offset-2">Playa Minimalista</button>
            <button onclick="fillStudioPrompt('Estilo Cyberpunk futurista chaqueta reflectante streetwear')" class="hover:text-brand-300 underline underline-offset-2">Streetwear Cyberpunk</button>
            <button onclick="fillStudioPrompt('Vestido de gala azul noche corte sirena con bordados dorados')" class="hover:text-brand-300 underline underline-offset-2">Gala Noche</button>
          </div>
        </div>

        <!-- Resultado Visual -->
        <div id="ai-studio-result" class="min-h-[320px] rounded-2xl border border-dashed border-slate-800 bg-slate-900/40 flex flex-col items-center justify-center p-6 text-center relative overflow-hidden">
          <div id="studio-placeholder" class="space-y-3">
            <div class="w-16 h-16 rounded-2xl bg-slate-800/80 flex items-center justify-center mx-auto text-slate-500">
              <i data-lucide="image" class="w-8 h-8"></i>
            </div>
            <p class="text-xs text-slate-400">Escribe tu descripción y presiona "Generar Outfit" para crear la imagen.</p>
          </div>
          <!-- Loader oculto por defecto -->
          <div id="studio-loader" class="hidden flex flex-col items-center gap-3">
            <div class="w-10 h-10 border-3 border-brand-500 border-t-transparent rounded-full animate-spin"></div>
            <p class="text-xs text-brand-300 font-medium animate-pulse">Diseñando outfit con IA de alta resolución...</p>
          </div>
          <!-- Imagen Resultante -->
          <img id="studio-output-img" class="hidden max-h-[480px] w-auto object-contain rounded-xl shadow-2xl border border-slate-800">
        </div>
      </div>
    </section>

  </main>

  <div id="cart-drawer" class="fixed inset-0 z-50 pointer-events-none opacity-0 transition-opacity duration-300">
    <!-- Backdrop -->
    <div onclick="toggleCartDrawer(false)" class="absolute inset-0 bg-slate-950/80 backdrop-blur-sm pointer-events-auto"></div>

    <!-- Drawer Content -->
    <div id="cart-panel" class="absolute top-0 right-0 h-full w-full max-w-md glass-panel border-l border-slate-800 p-6 flex flex-col transform translate-x-full transition-transform duration-300 ease-in-out pointer-events-auto">
      <div class="flex items-center justify-between pb-4 border-b border-slate-800">
        <div class="flex items-center gap-2">
          <i data-lucide="shopping-bag" class="w-5 h-5 text-brand-400"></i>
          <h3 class="font-serif font-bold text-lg text-white">Tu Carrito de Moda</h3>
        </div>
        <button onclick="toggleCartDrawer(false)" class="p-2 rounded-lg text-slate-400 hover:text-white bg-slate-900 border border-slate-800">
          <i data-lucide="x" class="w-4 h-4"></i>
        </button>
      </div>

      <!-- Barra de envío gratis -->
      <div class="my-4 p-3 rounded-xl bg-slate-900 border border-slate-800">
        <div class="flex justify-between text-xs mb-1">
          <span class="text-slate-300 font-medium">Progreso de Envío Gratis</span>
          <span id="free-shipping-text" class="text-brand-400 font-bold">$0 / $75 USD</span>
        </div>
        <div class="w-full h-1.5 bg-slate-800 rounded-full overflow-hidden">
          <div id="free-shipping-bar" class="h-full bg-gradient-to-r from-brand-500 to-amber-400 w-0 transition-all duration-300"></div>
        </div>
      </div>

      <!-- Lista de Productos en el Carrito -->
      <div id="cart-items" class="flex-1 overflow-y-auto space-y-3 py-2 pr-1">
        <!-- Renderizado dinámicamente -->
      </div>

      <!-- Footer del Carrito -->
      <div class="pt-4 border-t border-slate-800 space-y-3">
        <div class="space-y-1.5 text-xs">
          <div class="flex justify-between text-slate-400">
            <span>Subtotal:</span>
            <span id="cart-subtotal" class="text-slate-200 font-medium">$0.00</span>
          </div>
          <div class="flex justify-between text-slate-400">
            <span>Descuento (AURA10):</span>
            <span id="cart-discount" class="text-emerald-400 font-medium">-$0.00</span>
          </div>
          <div class="flex justify-between text-sm font-bold text-white pt-2 border-t border-slate-800">
            <span>Total:</span>
            <span id="cart-total" class="text-brand-400">$0.00</span>
          </div>
        </div>

        <button onclick="checkoutSimulated()" class="w-full py-3.5 rounded-xl bg-gradient-to-r from-brand-600 to-indigo-600 hover:opacity-95 text-white font-bold text-sm shadow-lg shadow-brand-500/20 transition-all flex items-center justify-center gap-2">
          <i data-lucide="credit-card" class="w-4 h-4"></i>
          <span>Finalizar Compra Segura</span>
        </button>
      </div>
    </div>
  </div>

  <div id="product-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-4 bg-slate-950/80 backdrop-blur-md">
    <div class="glass-panel border border-slate-800 rounded-2xl max-w-2xl w-full p-6 relative animate-fade-in flex flex-col md:flex-row gap-6">
      <button onclick="closeProductModal()" class="absolute top-4 right-4 p-2 rounded-lg bg-slate-900 border border-slate-800 text-slate-400 hover:text-white">
        <i data-lucide="x" class="w-4 h-4"></i>
      </button>

      <!-- Imagen -->
      <div class="w-full md:w-1/2 aspect-square rounded-xl overflow-hidden bg-slate-900">
        <img id="modal-img" src="" alt="Producto" class="w-full h-full object-cover">
      </div>

      <!-- Detalle -->
      <div class="w-full md:w-1/2 flex flex-col justify-between">
        <div>
          <span id="modal-category" class="text-[10px] font-bold tracking-wider uppercase text-brand-400 bg-brand-500/10 px-2.5 py-1 rounded-md border border-brand-500/20">Categoría</span>
          <h3 id="modal-title" class="font-serif text-xl font-bold text-white mt-2">Nombre del Producto</h3>
          <p id="modal-price" class="text-lg font-bold text-amber-400 mt-1">$0.00 USD</p>
          <p id="modal-desc" class="text-xs text-slate-300 mt-3 leading-relaxed">Descripción detallada de la prenda.</p>

          <!-- Tallas -->
          <div class="mt-4">
            <label class="text-xs font-bold text-slate-400 block mb-1.5">Seleccionar Talla:</label>
            <div class="flex gap-2" id="modal-sizes">
              <!-- Render de tallas -->
            </div>
          </div>
        </div>

        <div class="mt-6 space-y-2">
          <button id="modal-add-btn" class="w-full py-3 rounded-xl bg-brand-600 hover:bg-brand-500 text-white font-bold text-xs shadow-lg shadow-brand-500/20 transition-all flex items-center justify-center gap-2">
            <i data-lucide="shopping-cart" class="w-4 h-4"></i>
            <span>Añadir al Carrito</span>
          </button>
          <button id="modal-ask-bot-btn" class="w-full py-2.5 rounded-xl bg-slate-900 hover:bg-slate-800 border border-slate-700 text-xs text-brand-300 transition-all flex items-center justify-center gap-2">
            <i data-lucide="bot" class="w-4 h-4"></i>
            <span>Preguntar a AURA sobre esta prenda</span>
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- Toast Notification Box -->
  <div id="toast-container" class="fixed bottom-5 right-5 z-50 flex flex-col gap-2 pointer-events-none"></div>

  <script>
    const PRODUCTS = [
      {
        id: 'p1',
        name: 'Chaqueta Biker Cyber Noir',
        category: 'streetwear',
        price: 129.99,
        image: 'https://images.unsplash.com/photo-1551028719-00167b16eac5?w=600&auto=format&fit=crop&q=80',
        desc: 'Chaqueta de piel sintética ultra-soft con acabado mate y cremalleras de titanio pulido.',
        sizes: ['S', 'M', 'L', 'XL'],
        tags: ['Piel', 'Negro', 'Biker', 'Urbano']
      },
      {
        id: 'p2',
        name: 'Vestido Satin Noche Estelar',
        category: 'formal',
        price: 189.00,
        image: 'https://images.unsplash.com/photo-1566174053879-31528523f8ae?w=600&auto=format&fit=crop&q=80',
        desc: 'Vestido de corte fluido en seda satén con espalda descubierta y escote drapeado elegante.',
        sizes: ['XS', 'S', 'M'],
        tags: ['Gala', 'Seda', 'Elegante', 'Noche']
      },
      {
        id: 'p3',
        name: 'Blazer Oversized Tailored Gray',
        category: 'formal',
        price: 145.50,
        image: 'https://images.unsplash.com/photo-1591047139829-d91aecb6caea?w=600&auto=format&fit=crop&q=80',
        desc: 'Blazer estructurado corte masculino relajado. Perfecto para looks sartoriales contemporáneos.',
        sizes: ['S', 'M', 'L'],
        tags: ['Sartorial', 'Gris', 'Oficina', 'Formal']
      },
      {
        id: 'p4',
        name: 'Hoodie Aura Heavyweight Cream',
        category: 'casual',
        price: 78.00,
        image: 'https://images.unsplash.com/photo-1556905055-8f358a7a47b2?w=600&auto=format&fit=crop&q=80',
        desc: 'Sudadera de algodón orgánico de 450 gsm con capucha doble y bordado AURA en relieve.',
        sizes: ['S', 'M', 'L', 'XL'],
        tags: ['Algodón', 'Comfort', 'Crema', 'Casual']
      },
      {
        id: 'p5',
        name: 'Sneakers Neo-Runner White/Volt',
        category: 'calzado',
        price: 160.00,
        image: 'https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?w=600&auto=format&fit=crop&q=80',
        desc: 'Zapatillas futuristas con amortiguación neumática y malla transpirable high-tech.',
        sizes: ['38', '39', '40', '41', '42', '43'],
        tags: ['Deportivo', 'Sneakers', 'Futurista']
      },
      {
        id: 'p6',
        name: 'Pantalón Cargo Táctico Obsidian',
        category: 'streetwear',
        price: 95.00,
        image: 'https://images.unsplash.com/photo-1624378439575-d8705ad7ae80?w=600&auto=format&fit=crop&q=80',
        desc: 'Pantalón cargo de alta durabilidad con múltiples bolsillos funcionales y hebillas magnéticas.',
        sizes: ['30', '32', '34', '36'],
        tags: ['Cargo', 'Táctico', 'Streetwear']
      },
      {
        id: 'p7',
        name: 'Gafas de Sol Atelier Monolith',
        category: 'streetwear',
        price: 65.00,
        image: 'https://images.unsplash.com/photo-1511499767150-a48a237f0083?w=600&auto=format&fit=crop&q=80',
        desc: 'Montura geométrica en acetato italiano con lentes de protección UV400 polarizadas.',
        sizes: ['Única'],
        tags: ['Accesorios', 'Gafas', 'Verano']
      },
      {
        id: 'p8',
        name: 'Botines Piel Chelsea Heritage',
        category: 'calzado',
        price: 210.00,
        image: 'https://images.unsplash.com/photo-1608256246200-53e635b5b65f?w=600&auto=format&fit=crop&q=80',
        desc: 'Botines Chelsea de piel vacuno de grano fino pulida a mano con suela de goma antideslizante.',
        sizes: ['39', '40', '41', '42', '43'],
        tags: ['Cuero', 'Botines', 'Elegante']
      }
    ];

    let cart = [];
    let currentFilterCategory = 'all';
    let selectedSizeModal = '';
    let chatHistory = [];

    /* System Instruction para Gemini AI */
    const SYSTEM_INSTRUCTION_BOT = `
Eres AURA, una estilista personal y asesora de moda virtual de alta gama para la boutique "AURA Atelier".
Tu tono es elegante, amable, conocedor, sofisticado y directo.
Tienes pleno conocimiento de la boutique y su catálogo de prendas:
${JSON.stringify(PRODUCTS.map(p => ({ id: p.id, nombre: p.name, precio: p.price, categoria: p.category, descripcion: p.desc, tallas: p.sizes })))}

Tus tareas:
1. Recomendar outfits y combinaciones completas según la ocasión (bodas, casual, citas, streetwear, trabajo).
2. Asesorar sobre tallas y ajuste.
3. Responder sobre envíos (Envío gratis a partir de $75 USD, código de descuento AURA10 para 10% de descuento).
4. Si el usuario pregunta por una prenda de la tienda, descríbela e incentiva su compra de forma sofisticada.
5. Mantén respuestas concisas (máximo 2 a 3 párrafos cortos) e incluye emojis elegantes como ✨, 🧥, 👗, 👠, 💍 de forma adecuada.
    `;

    window.onload = () => {
      lucide.createIcons();
      renderCatalog(PRODUCTS);
      initChatWelcomeMessage();
    };

    /* Cambiar entre pestañas/vistas principales */
    function switchView(viewName) {
      document.querySelectorAll('.view-panel').forEach(el => el.classList.add('hidden'));
      const target = document.getElementById(`view-${viewName}`);
      if (target) target.classList.remove('hidden');

      // Actualizar botón activo en menú desktop
      document.querySelectorAll('.nav-tab').forEach(btn => {
        btn.classList.remove('bg-brand-600', 'text-white');
        btn.classList.add('text-slate-400');
      });
      const activeNav = document.getElementById(`nav-btn-${viewName}`);
      if (activeNav) {
        activeNav.classList.add('bg-brand-600', 'text-white');
        activeNav.classList.remove('text-slate-400');
      }
    }

    function initChatWelcomeMessage() {
      const chatContainer = document.getElementById('chat-messages');
      chatContainer.innerHTML = '';
      
      appendMessage('bot', `
        ¡Hola! Soy **AURA**, tu estilista personal en AURA Atelier ✨.
        
        ¿En qué ocasión te gustaría destacar hoy? Puedo ayudarte a:
        - Armar el **outfit perfecto** para tu evento.
        - Asesorarte con **combinaciones y colores**.
        - Resolver dudas sobre **tallas y disponibilidad** en nuestro catálogo.
      `);
    }

    function appendMessage(sender, text, productCard = null) {
      const chatContainer = document.getElementById('chat-messages');
      const msgDiv = document.createElement('div');
      msgDiv.className = `flex gap-3 animate-fade-in ${sender === 'user' ? 'justify-end' : 'justify-start'}`;

      const formattedText = text.replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>').replace(/\n/g, '<br>');

      if (sender === 'user') {
        msgDiv.innerHTML = `
          <div class="max-w-[85%] sm:max-w-[75%] bg-gradient-to-r from-brand-600 to-indigo-600 text-white rounded-2xl rounded-tr-none px-4 py-3 text-xs sm:text-sm shadow-md">
            ${formattedText}
          </div>
          <div class="w-8 h-8 rounded-full bg-slate-800 border border-slate-700 flex items-center justify-center shrink-0 text-xs font-bold text-slate-300">
            Tú
          </div>
        `;
      } else {
        let cardHTML = '';
        if (productCard) {
          cardHTML = `
            <div class="mt-3 p-3 rounded-xl bg-slate-900 border border-slate-800 flex items-center gap-3 w-full max-w-xs">
              <img src="${productCard.image}" class="w-14 h-14 object-cover rounded-lg">
              <div class="flex-1 min-w-0">
                <p class="text-xs font-bold text-white truncate">${productCard.name}</p>
                <p class="text-xs text-amber-400 font-semibold">$${productCard.price} USD</p>
                <button onclick="openProductModal('${productCard.id}')" class="mt-1 text-[10px] text-brand-400 hover:underline">Ver Prenda →</button>
              </div>
            </div>
          `;
        }

        msgDiv.innerHTML = `
          <div class="w-8 h-8 rounded-full bg-gradient-to-tr from-brand-500 to-amber-500 flex items-center justify-center shrink-0 text-white text-xs font-bold shadow-md">
            A
          </div>
          <div class="max-w-[85%] sm:max-w-[75%] bg-slate-900 border border-slate-800 text-slate-200 rounded-2xl rounded-tl-none px-4 py-3 text-xs sm:text-sm shadow-md">
            ${formattedText}
            ${cardHTML}
          </div>
        `;
      }

      chatContainer.appendChild(msgDiv);
      chatContainer.scrollTop = chatContainer.scrollHeight;
    }

    function sendQuickPrompt(promptText) {
      switchView('chat');
      document.getElementById('chat-input').value = promptText;
      handleChatSubmit();
    }

    async function handleChatSubmit(e) {
      if (e) e.preventDefault();
      const input = document.getElementById('chat-input');
      const userText = input.value.trim();
      if (!userText) return;

      input.value = '';
      appendMessage('user', userText);

      // Deshabilitar botón mientras responde
      const sendBtn = document.getElementById('chat-send-btn');
      sendBtn.disabled = true;
      sendBtn.classList.add('opacity-50');

      // Mostrar indicador de escritura
      const chatContainer = document.getElementById('chat-messages');
      const typingIndicator = document.createElement('div');
      typingIndicator.id = 'typing-indicator';
      typingIndicator.className = 'flex gap-3 justify-start animate-fade-in';
      typingIndicator.innerHTML = `
        <div class="w-8 h-8 rounded-full bg-slate-800 flex items-center justify-center text-xs font-bold text-brand-400">A</div>
        <div class="bg-slate-900 border border-slate-800 text-slate-400 rounded-2xl rounded-tl-none px-4 py-3 text-xs flex items-center gap-1.5">
          <span class="w-1.5 h-1.5 bg-brand-400 rounded-full animate-bounce"></span>
          <span class="w-1.5 h-1.5 bg-brand-400 rounded-full animate-bounce [animation-delay:0.2s]"></span>
          <span class="w-1.5 h-1.5 bg-brand-400 rounded-full animate-bounce [animation-delay:0.4s]"></span>
        </div>
      `;
      chatContainer.appendChild(typingIndicator);
      chatContainer.scrollTop = chatContainer.scrollHeight;

      try {
        // Llamada a la API de Gemini
        const apiKey = "";
        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-3-flash-preview:generateContent?key=${apiKey}`;

        // Construir historial
        chatHistory.push({ role: 'user', parts: [{ text: userText }] });

        const payload = {
          contents: chatHistory,
          systemInstruction: {
            parts: [{ text: SYSTEM_INSTRUCTION_BOT }]
          }
        };

        const response = await fetch(apiUrl, {
          method: 'POST',
          headers: { 'Content-Type': 'application/json' },
          body: JSON.stringify(payload)
        });

        const data = await response.json();
        typingIndicator.remove();

        let botReply = '';
        if (data.candidates && data.candidates[0]?.content?.parts?.[0]?.text) {
          botReply = data.candidates[0].content.parts[0].text;
          chatHistory.push({ role: 'model', parts: [{ text: botReply }] });
        } else {
          botReply = fallbackAIResponse(userText);
        }

        // Buscar si menciona algún producto del catálogo para incrustar su tarjeta
        let matchedProduct = PRODUCTS.find(p => userText.toLowerCase().includes(p.name.toLowerCase()) || botReply.toLowerCase().includes(p.name.toLowerCase()));

        appendMessage('bot', botReply, matchedProduct);

      } catch (err) {
        console.error('Error llamando a la API de Gemini:', err);
        if (document.getElementById('typing-indicator')) document.getElementById('typing-indicator').remove();
        
        // Respuesta fallback inteligente en caso de error o sin API Key
        const fallbackText = fallbackAIResponse(userText);
        let matchedProduct = PRODUCTS.find(p => userText.toLowerCase().includes(p.name.toLowerCase()));
        appendMessage('bot', fallbackText, matchedProduct);
      } finally {
        sendBtn.disabled = false;
        sendBtn.classList.remove('opacity-50');
      }
    }

    /* Fallback local estilizado en caso de desconexión o contingencia */
    function fallbackAIResponse(prompt) {
      const lower = prompt.toLowerCase();
      if (lower.includes('talla') || lower.includes('medida')) {
        return 'Nuestras prendas siguen el tallaje europeo estándar. Para vestidos y blazers recomendamos tu talla habitual, mientras que en prendas Oversized la caída ya es amplia. ¡Si dudas entre dos tallas, te sugerimos elegir la mayor!';
      }
      if (lower.includes('envío') || lower.includes('descuento') || lower.includes('cupón')) {
        return 'Ofrecemos **Envío Gratuito** en todas las compras superiores a $75 USD. Además, puedes utilizar el cupón **AURA10** al finalizar la compra para obtener un 10% de descuento en tu primer pedido ✨.';
      }
      if (lower.includes('formal') || lower.includes('noche') || lower.includes('evento')) {
        return 'Para una ocasión formal o cena de gala, te sugiero combinar nuestro **Vestido Satin Noche Estelar** con calzado de tacón fino, o bien el **Blazer Oversized Tailored Gray** sobre un top liso para un toque sofisticado y contemporáneo.';
      }
      if (lower.includes('streetwear') || lower.includes('casual') || lower.includes('urbano')) {
        return 'El estilo streetwear de AURA destaca por la **Chaqueta Biker Cyber Noir** combinada con el **Pantalón Cargo Táctico Obsidian** y nuestras **Sneakers Neo-Runner**. Un look audaz y con mucha personalidad.';
      }
      return '¡Excelente elección! En AURA Atelier trabajamos para que cada prenda resalte tu elegancia personal. Puedes explorar nuestras prendas en la pestaña de **Catálogo** o preguntarme por cualquier combinación específica que tengas en mente.';
    }

    function clearChat() {
      chatHistory = [];
      initChatWelcomeMessage();
      showToast('Conversación reiniciada');
    }

    function renderCatalog(items) {
      const grid = document.getElementById('catalog-grid');
      grid.innerHTML = '';

      if (items.length === 0) {
        grid.innerHTML = `
          <div class="col-span-full py-12 text-center text-slate-500">
            <i data-lucide="package-open" class="w-12 h-12 mx-auto mb-2 opacity-50"></i>
            <p class="text-sm">No se encontraron prendas que coincidan con la búsqueda.</p>
          </div>
        `;
        lucide.createIcons();
        return;
      }

      items.forEach(product => {
        const card = document.createElement('div');
        card.className = 'glass-card rounded-2xl overflow-hidden border border-slate-800 flex flex-col group hover:border-brand-500/50 transition-all duration-300';
        card.innerHTML = `
          <div class="relative aspect-square overflow-hidden bg-slate-900 cursor-pointer" onclick="openProductModal('${product.id}')">
            <img src="${product.image}" alt="${product.name}" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
            <div class="absolute top-3 right-3 bg-slate-950/80 backdrop-blur-md px-2.5 py-1 rounded-full text-[10px] font-bold text-amber-400 border border-amber-400/20">
              $${product.price.toFixed(2)} USD
            </div>
            <span class="absolute bottom-3 left-3 text-[10px] uppercase font-bold tracking-wider px-2 py-0.5 rounded bg-slate-900/90 text-slate-300 border border-slate-700">
              ${product.category}
            </span>
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between space-y-3">
            <div>
              <h3 class="font-bold text-sm text-white group-hover:text-brand-300 transition-colors cursor-pointer" onclick="openProductModal('${product.id}')">${product.name}</h3>
              <p class="text-xs text-slate-400 line-clamp-2 mt-1">${product.desc}</p>
            </div>
            <div class="flex gap-2 pt-2 border-t border-slate-800/80">
              <button onclick="addToCart('${product.id}')" class="flex-1 py-2 rounded-xl bg-brand-600 hover:bg-brand-500 text-white text-xs font-semibold transition-colors flex items-center justify-center gap-1.5">
                <i data-lucide="shopping-bag" class="w-3.5 h-3.5"></i>
                <span>Añadir</span>
              </button>
              <button onclick="askBotAboutProduct('${product.id}')" class="p-2 rounded-xl bg-slate-900 hover:bg-slate-800 border border-slate-700 text-slate-300 hover:text-brand-300 transition-colors" title="Consultar con AURA Bot">
                <i data-lucide="bot" class="w-4 h-4"></i>
              </button>
            </div>
          </div>
        `;
        grid.appendChild(card);
      });
      lucide.createIcons();
    }

    function setCategoryFilter(category) {
      currentFilterCategory = category;
      document.querySelectorAll('.cat-chip').forEach(btn => {
        btn.classList.remove('bg-brand-600', 'text-white');
        btn.classList.add('bg-slate-800/80', 'text-slate-400');
      });
      event.target.classList.add('bg-brand-600', 'text-white');
      event.target.classList.remove('bg-slate-800/80', 'text-slate-400');
      filterCatalog();
    }

    function filterCatalog() {
      const searchTerm = document.getElementById('catalog-search').value.toLowerCase();
      const filtered = PRODUCTS.filter(p => {
        const matchesCategory = currentFilterCategory === 'all' || p.category === currentFilterCategory;
        const matchesSearch = p.name.toLowerCase().includes(searchTerm) || p.desc.toLowerCase().includes(searchTerm) || p.tags.some(t => t.toLowerCase().includes(searchTerm));
        return matchesCategory && matchesSearch;
      });
      renderCatalog(filtered);
    }

    function askBotAboutProduct(productId) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;
      closeProductModal();
      sendQuickPrompt(`¿Con qué otras prendas o accesorios puedo combinar el/la ${product.name}?`);
    }

    function openProductModal(productId) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;

      document.getElementById('modal-img').src = product.image;
      document.getElementById('modal-title').textContent = product.name;
      document.getElementById('modal-category').textContent = product.category;
      document.getElementById('modal-price').textContent = `$${product.price.toFixed(2)} USD`;
      document.getElementById('modal-desc').textContent = product.desc;

      const sizesContainer = document.getElementById('modal-sizes');
      sizesContainer.innerHTML = '';
      selectedSizeModal = product.sizes[0];

      product.sizes.forEach((size, idx) => {
        const btn = document.createElement('button');
        btn.className = `px-3 py-1.5 rounded-lg text-xs font-bold border transition-all ${idx === 0 ? 'bg-brand-600 text-white border-brand-500' : 'bg-slate-900 text-slate-300 border-slate-700 hover:border-slate-500'}`;
        btn.textContent = size;
        btn.onclick = () => {
          sizesContainer.querySelectorAll('button').forEach(b => {
            b.className = 'px-3 py-1.5 rounded-lg text-xs font-bold bg-slate-900 text-slate-300 border border-slate-700 hover:border-slate-500';
          });
          btn.className = 'px-3 py-1.5 rounded-lg text-xs font-bold bg-brand-600 text-white border border-brand-500';
          selectedSizeModal = size;
        };
        sizesContainer.appendChild(btn);
      });

      document.getElementById('modal-add-btn').onclick = () => {
        addToCart(product.id, selectedSizeModal);
        closeProductModal();
      };

      document.getElementById('modal-ask-bot-btn').onclick = () => {
        askBotAboutProduct(product.id);
      };

      document.getElementById('product-modal').classList.remove('hidden');
      document.getElementById('product-modal').classList.add('flex');
    }

    function closeProductModal() {
      document.getElementById('product-modal').classList.add('hidden');
      document.getElementById('product-modal').classList.remove('flex');
    }

    function addToCart(productId, size = null) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;

      const chosenSize = size || product.sizes[0];
      const existing = cart.find(item => item.id === productId && item.size === chosenSize);

      if (existing) {
        existing.qty += 1;
      } else {
        cart.push({ ...product, size: chosenSize, qty: 1 });
      }

      updateCartUI();
      showToast(`Añadido: ${product.name} (${chosenSize})`);
    }

    function updateCartQty(index, change) {
      if (cart[index]) {
        cart[index].qty += change;
        if (cart[index].qty <= 0) cart.splice(index, 1);
      }
      updateCartUI();
    }

    function updateCartUI() {
      const cartItemsContainer = document.getElementById('cart-items');
      const badge = document.getElementById('cart-badge');
      cartItemsContainer.innerHTML = '';

      const totalItems = cart.reduce((acc, item) => acc + item.qty, 0);

      if (totalItems > 0) {
        badge.textContent = totalItems;
        badge.classList.remove('hidden');
      } else {
        badge.classList.add('hidden');
      }

      if (cart.length === 0) {
        cartItemsContainer.innerHTML = `
          <div class="py-12 text-center text-slate-500 space-y-2">
            <i data-lucide="shopping-cart" class="w-10 h-10 mx-auto opacity-40"></i>
            <p class="text-xs">Tu carrito está vacío.</p>
          </div>
        `;
      } else {
        cart.forEach((item, idx) => {
          const div = document.createElement('div');
          div.className = 'p-3 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-between gap-3';
          div.innerHTML = `
            <img src="${item.image}" class="w-12 h-12 object-cover rounded-lg">
            <div class="flex-1 min-w-0">
              <h4 class="text-xs font-bold text-white truncate">${item.name}</h4>
              <p class="text-[10px] text-slate-400">Talla: <span class="text-brand-300 font-bold">${item.size}</span></p>
              <p class="text-xs text-amber-400 font-bold mt-0.5">$${(item.price * item.qty).toFixed(2)}</p>
            </div>
            <div class="flex items-center gap-1.5 bg-slate-950 p-1 rounded-lg border border-slate-800">
              <button onclick="updateCartQty(${idx}, -1)" class="w-5 h-5 rounded flex items-center justify-center text-slate-400 hover:text-white bg-slate-900 text-xs">-</button>
              <span class="text-xs font-bold text-white w-4 text-center">${item.qty}</span>
              <button onclick="updateCartQty(${idx}, 1)" class="w-5 h-5 rounded flex items-center justify-center text-slate-400 hover:text-white bg-slate-900 text-xs">+</button>
            </div>
          `;
          cartItemsContainer.appendChild(div);
        });
      }

      // Totales & Barra de Envío
      const subtotal = cart.reduce((acc, item) => acc + (item.price * item.qty), 0);
      const discount = subtotal > 0 ? subtotal * 0.10 : 0; // Aplicando descuento automático de demostración
      const total = subtotal - discount;

      document.getElementById('cart-subtotal').textContent = `$${subtotal.toFixed(2)} USD`;
      document.getElementById('cart-discount').textContent = `-$${discount.toFixed(2)} USD`;
      document.getElementById('cart-total').textContent = `$${total.toFixed(2)} USD`;

      // Barra de envío gratis ($75 USD)
      const freeShipThreshold = 75;
      const progress = Math.min((subtotal / freeShipThreshold) * 100, 100);
      document.getElementById('free-shipping-bar').style.width = `${progress}%`;
      document.getElementById('free-shipping-text').textContent = subtotal >= freeShipThreshold ? '¡Envío Gratis Desbloqueado! 🎉' : `$${subtotal.toFixed(0)} / $${freeShipThreshold} USD`;

      lucide.createIcons();
    }

    function toggleCartDrawer(open) {
      const drawer = document.getElementById('cart-drawer');
      const panel = document.getElementById('cart-panel');

      if (open) {
        drawer.classList.remove('pointer-events-none', 'opacity-0');
        drawer.classList.add('opacity-100');
        panel.classList.remove('translate-x-full');
      } else {
        drawer.classList.add('opacity-0');
        panel.classList.add('translate-x-full');
        setTimeout(() => drawer.classList.add('pointer-events-none'), 300);
      }
    }

    function checkoutSimulated() {
      if (cart.length === 0) {
        showToast('El carrito está vacío', 'error');
        return;
      }
      showToast('¡Pedido realizado con éxito! Gracias por tu compra.');
      cart = [];
      updateCartUI();
      toggleCartDrawer(false);
    }

    function fillStudioPrompt(text) {
      document.getElementById('ai-studio-prompt').value = text;
    }

    async function generateAIStudioOutfit() {
      const promptInput = document.getElementById('ai-studio-prompt').value.trim();
      if (!promptInput) {
        showToast('Escribe una descripción para generar el outfit', 'error');
        return;
      }

      const placeholder = document.getElementById('studio-placeholder');
      const loader = document.getElementById('studio-loader');
      const outputImg = document.getElementById('studio-output-img');
      const btn = document.getElementById('btn-studio-generate');

      placeholder.classList.add('hidden');
      outputImg.classList.add('hidden');
      loader.classList.remove('hidden');
      btn.disabled = true;

      try {
        const apiKey = "";
        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/imagen-4.0-generate-001:predict?key=${apiKey}`;

        const payload = {
          instances: [{ prompt: `High fashion editorial look photoshoot, ${promptInput}, full body view, luxury aesthetic, highly detailed` }],
          parameters: { sampleCount: 1 }
        };

        const response = await fetch(apiUrl, {
          method: 'POST',
          headers: { 'Content-Type': 'application/json' },
          body: JSON.stringify(payload)
        });

        const result = await response.json();

        if (result.predictions && result.predictions[0]?.bytesBase64Encoded) {
          const imageUrl = `data:image/png;base64,${result.predictions[0].bytesBase64Encoded}`;
          outputImg.src = imageUrl;
          outputImg.classList.remove('hidden');
          showToast('Outfit generado correctamente');
        } else {
          // Si no hay respuesta directa de la API, mostrar imagen de alta calidad temática como fallback
          outputImg.src = 'https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=800&auto=format&fit=crop&q=80';
          outputImg.classList.remove('hidden');
          showToast('Muestra de outfit lista');
        }

      } catch (err) {
        console.error('Error generando imagen de outfit:', err);
        // Fallback visual
        outputImg.src = 'https://images.unsplash.com/photo-1490481651871-ab68de25d43d?w=800&auto=format&fit=crop&q=80';
        outputImg.classList.remove('hidden');
      } finally {
        loader.classList.add('hidden');
        btn.disabled = false;
      }
    }

    /* Notificaciones Toast */
    function showToast(message, type = 'success') {
      const container = document.getElementById('toast-container');
      const toast = document.createElement('div');
      toast.className = `px-4 py-3 rounded-xl border text-xs font-semibold shadow-xl flex items-center gap-2 animate-fade-in pointer-events-auto ${type === 'error' ? 'bg-rose-950/90 border-rose-500/50 text-rose-200' : 'bg-slate-900/90 border-brand-500/50 text-white'}`;
      toast.innerHTML = `
        <i data-lucide="${type === 'error' ? 'alert-circle' : 'check-circle'}" class="w-4 h-4 text-brand-400"></i>
        <span>${message}</span>
      `;
      container.appendChild(toast);
      lucide.createIcons();

      setTimeout(() => {
        toast.style.opacity = '0';
        toast.style.transition = 'opacity 0.3s ease';
        setTimeout(() => toast.remove(), 300);
      }, 3000);
    }
  </script>
</body>
</html>