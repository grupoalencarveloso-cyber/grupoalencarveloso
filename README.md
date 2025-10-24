<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grupo Alencar Veloso</title>
    <!-- Carrega o Tailwind CSS para design rápido e responsivo --><script src="https://cdn.tailwindcss.com"></script>
    <!-- Configura a fonte Inter --><link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* Configurações de cores personalizadas e fonte */
        :root {
            --color-primary: #0A1931; /* Azul Marinho Profundo */
            --color-secondary: #C5C6C7; /* Cinza Claro */
            --color-text: #1F2937; /* Cinza Escuro para texto */
        }
        body {
            font-family: 'Inter', sans-serif;
            color: var(--color-text);
            background-color: #052449; /* Fundo azul marinho profundo (Cor do Cliente) */
            background-image: none;
            /* Adiciona rolagem suave ao clicar em âncoras (href="#id") */
            scroll-behavior: smooth;
        }

        /* 1. Animação de entrada dinâmica para a logo (Fade-in e Slide-up) */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px); /* Começa um pouco mais para baixo */
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        /* Aplica a animação, mantendo o elemento invisível inicialmente */
        .animate-logo-entry {
            opacity: 0; 
            animation: fadeInUp 1.5s ease-out 0.5s forwards; 
        }

        /* 2. Classe para o efeito de hover sutil nos logos */
        .partner-logo {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            cursor: pointer;
        }
        .partner-logo:hover {
            transform: translateY(-5px);
            /* Sombra mais intensa no hover */
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5); 
        }
        
        /* 3. Estilos da Logo Principal */
        .main-logo {
            max-width: 350px; /* Mobile */
            height: auto;
            margin: 0 auto;
            display: block;
        }
        @media (min-width: 768px) { /* Desktop */
            .main-logo {
                max-width: 480px; 
            }
        }
        /* Cor de fundo para o container dos parceiros */
        .partner-bg-dark {
            background-color: #052449;
        }

        /* Novo estilo para as imagens dos parceiros */
        .partner-img {
            max-width: 100%; /* Garante que a imagem não exceda a largura do seu contêiner */
            height: auto; /* Permite que a altura se ajuste automaticamente */
            object-fit: contain; /* Redimensiona a imagem para caber dentro do elemento, mantendo a proporção */
            padding: 5px; /* Adiciona um pequeno padding interno para que a logo não "grude" nas bordas do cartão */
        }
    </style>
</head>
<body class="min-h-screen antialiased flex flex-col items-center justify-center p-4">

    <!-- Container Principal Centrado e com Fundo Semi-Transparente --><div class="logo-overlay w-full max-w-7xl mx-auto p-8 md:p-12 lg:p-16 rounded-3xl shadow-2xl bg-white/90 backdrop-blur-sm">

        <!-- Seção de Título Principal --><header class="text-center mb-10">
            <!-- LOGO PRINCIPAL --><img src="https://i.imgur.com/n5vgmLm.jpeg" alt="Grupo Alencar Veloso Logo" class="main-logo mb-6 animate-logo-entry" onerror="this.onerror=null; this.src='https://placehold.co/400x150/0A1931/ffffff?text=LOGO+GRUPO+AV';"> 
            
            <p class="mt-4 text-xl md:text-2xl font-light max-w-3xl mx-auto" style="color: var(--color-text);">
                Sua porta de entrada para um ecossistema de soluções estratégicas e inovadoras.
            </p>
            <p class="mt-2 text-md text-gray-500">
                Liderança, Parceria e Crescimento.
            </p>
        </header>

        <!-- Botão Principal de Contato --><div class="text-center mb-16">
            <a href="#contato" class="inline-block px-10 py-3 bg-[#0A1931] text-white font-semibold rounded-full shadow-xl hover:bg-[#1f375f] transition duration-300 transform hover:scale-105 text-lg md:text-xl">
                Fale Conosco e Saiba Mais
            </a>
        </div>

        <!-- Seção de Nossos Parceiros Estratégicos --><section class="mt-16 pt-8 border-t border-gray-200">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-10" style="color: var(--color-primary);">
                Nossos Parceiros Estratégicos
            </h2>

            <!-- Grid Responsivo Ajustado para 5 Logos (2 no Mobile, 3 no Tablet, 5 no Desktop) --><div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-6 lg:gap-8">

                <!-- Parceiro 1 - FUNDO ESCURO APLICADO --><a href="javascript:void(0)" class="partner-logo flex flex-col items-center justify-center p-6 partner-bg-dark rounded-xl border border-gray-700 shadow-xl">
                    <img src="https://i.imgur.com/ZytpQOB.png" 
                         alt="Logo da Empresa Parceira 1"
                         class="partner-img"
                         onerror="this.onerror=null; this.src='https://placehold.co/180x80/CCCCCC/000000?text=Logo+1';">
                </a>

                <!-- Parceiro 2 - FUNDO ESCURO APLICADO --><a href="javascript:void(0)" class="partner-logo flex flex-col items-center justify-center p-6 partner-bg-dark rounded-xl border border-gray-700 shadow-xl">
                    <img src="https://i.imgur.com/dRwjmel.jpeg"
                         alt="Logo da Empresa Parceira 2"
                         class="partner-img"
                         onerror="this.onerror=null; this.src='https://placehold.co/180x80/CCCCCC/000000?text=Logo+2';">
                </a>

                <!-- Parceiro 3 - FUNDO ESCURO APLICADO --><a href="javascript:void(0)" class="partner-logo flex flex-col items-center justify-center p-6 partner-bg-dark rounded-xl border border-gray-700 shadow-xl">
                    <img src="https://i.imgur.com/tJtWLPq.png"
                         alt="Logo da Empresa Parceira 3"
                         class="partner-img"
                         onerror="this.onerror=null; this.src='https://placehold.co/180x80/CCCCCC/000000?text=Logo+3';">
                </a>

                <!-- Parceiro 4 - FUNDO ESCURO APLICADO --><a href="javascript:void(0)" class="partner-logo flex flex-col items-center justify-center p-6 partner-bg-dark rounded-xl border border-gray-700 shadow-xl">
                    <img src="https://i.imgur.com/62vXE9E.jpeg"
                         alt="Logo da Empresa Parceira 4"
                         class="partner-img"
                         onerror="this.onerror=null; this.src='https://placehold.co/180x80/CCCCCC/000000?text=Logo+4';">
                </a>

                <!-- Parceiro 5 - FUNDO ESCURO APLICADO --><a href="javascript:void(0)" class="partner-logo flex flex-col items-center justify-center p-6 partner-bg-dark rounded-xl border border-gray-700 shadow-xl">
                    <img src="https://i.imgur.com/sxXoSNZ.jpeg"
                         alt="Logo da Empresa Parceira 5"
                         class="partner-img"
                         onerror="this.onerror=null; this.src='https://placehold.co/180x80/CCCCCC/000000?text=Logo+5';">
                </a>

            </div>
        </section>

        <!-- NOVA SEÇÃO: Informações de Contato (Âncora de destino do botão) --><section id="contato" class="mt-20 pt-12 border-t border-gray-200">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-8" style="color: var(--color-primary);">
                Fale Conosco
            </h2>
            <div class="text-center space-y-6">
                
                <!-- Email Contact com Ícone --><p class="text-lg md:text-xl font-medium flex items-center justify-center" style="color: var(--color-text);">
                    <!-- Ícone de Email (Lucide Mail) --><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6 mr-3 text-gray-500">
                        <rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.83 1.83 0 0 1-2.06 0L2 7"/>
                    </svg>
                    <span class="font-bold mr-2">Email:</span> 
                    <a href="mailto:Residuosambientalltda@gmail.com" class="text-[#0A1931] hover:text-[#1f375f] transition duration-200 underline">Residuosambientalltda@gmail.com</a>
                </p>
                
                <!-- Telefone Contact com Ícone --><p class="text-lg md:text-xl font-medium flex items-center justify-center" style="color: var(--color-text);">
                    <!-- Ícone de Telefone (Lucide Phone) --><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6 mr-3 text-gray-500">
                        <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-8.63-3.07A19.5 19.5 0 0 1 3 10.19a2 2 0 0 1 2-2h3"/><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-8.63-3.07A19.5 19.5 0 0 1 3 10.19a2 2 0 0 1 2-2h3"/>
                    </svg>
                    <span class="font-bold mr-2">Telefone:</span> 
                    <a href="tel:+558688615356" class="text-[#0A1931] hover:text-[#1f375f] transition duration-200 underline">+55 86 8861-5356</a>
                </p>
            </div>
        </section>

    </div>

    <!-- Footer Simples --><footer class="mt-8 text-center text-gray-300 text-sm">
        &copy; 2025 Grupo Alencar Veloso. Todos os direitos reservados.
    </footer>

</body>
</html>
