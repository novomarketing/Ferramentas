<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ferramentas de Alto Impacto: O Mapa Definitivo para o Sucesso Digital</title>
    <!-- Incluindo Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Inter para um visual limpo e moderno -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0F172A; /* Azul escuro principal */
            line-height: 1.6;
            scroll-behavior: smooth;
            padding: 0; /* Remove padding padrão do body */
            margin: 0; /* Remove margem padrão do body */
            min-height: 100vh; /* Garante que o body ocupa pelo menos 100% da altura da viewport */
            overflow-x: hidden; /* Evita barra de rolagem horizontal */
        }
        .container {
            max-width: 950px; /* Largura máxima para centralizar o conteúdo principal */
            margin: 0 auto; /* Centraliza o contêiner na tela */
            padding: 0;
            background-color: #ffffff;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.25); /* Sombra mais forte */
            border-radius: 20px; /* Cantos arredondados no contêiner principal */
            overflow: hidden;
        }

        /* Estilo para centralizar o conteúdo dentro das seções */
        .section-content {
            padding: 0 2rem; /* Adiciona padding lateral para respiro dentro do conteúdo */
        }

        .hero-section {
            background: linear-gradient(145deg, #1A202C 0%, #3B82F6 100%); /* Gradiente escuro para azul vibrante */
            color: white;
            padding: 5rem 0; /* Padding vertical, padding horizontal via .section-content */
            text-align: center;
            position: relative;
            overflow: hidden;
            border-bottom-left-radius: 40px; /* Cantos super arredondados */
            border-bottom-right-radius: 40px;
            box-shadow: inset 0 -8px 20px rgba(0, 0, 0, 0.3); /* Sombra interna para profundidade */
        }
        .hero-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image:
                url('https://images.unsplash.com/photo-1542831371-29b0f74f9713?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'), /* Código/Digital */
                url('https://images.unsplash.com/photo-1596558450268-ecc0350d6037?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'); /* Cérebro com tecnologia */
            background-size: cover, cover;
            background-position: center, center;
            filter: grayscale(80%) brightness(0.6) blur(3px); /* Mais escuro e desfocado */
            opacity: 0.2; /* Opacidade sutil */
            z-index: 0;
        }
        .hero-section h1 {
            font-size: 4rem; /* Título maior */
            font-weight: 900; /* Extra bold */
            line-height: 1.1;
            margin-bottom: 1.8rem;
            text-shadow: 3px 3px 12px rgba(0, 0, 0, 0.5);
            position: relative;
            z-index: 1;
            color: #FFD700; /* Amarelo vivo sólido */
        }
        .hero-section p {
            font-size: 1.8rem; /* Subtítulo maior */
            font-weight: 300;
            margin-bottom: 3rem;
            opacity: 0.95;
            position: relative;
            z-index: 1;
            color: #E0F2FE; /* Azul claro para legibilidade */
        }
        .cta-button {
            display: inline-block;
            background: linear-gradient(90deg, #F97316 0%, #FFD700 100%); /* Laranja para dourado */
            color: #1F2937; /* Texto escuro no botão */
            font-size: 2rem; /* Botão ainda maior */
            font-weight: 900;
            padding: 1.5rem 3.5rem;
            border-radius: 9999px; /* Botão super arredondado */
            text-decoration: none;
            transition: all 0.4s ease-in-out;
            box-shadow: 0 8px 25px rgba(249, 115, 22, 0.6);
            animation: bounceIn 1.5s forwards, pulse 2s infinite 1.5s; /* Animações combinadas */
            position: relative;
            z-index: 2;
            border: 3px solid rgba(255, 255, 255, 0.4);
        }
        .cta-button:hover {
            background: linear-gradient(90deg, #EAB308 0%, #F97316 100%); /* Inverte e escurece */
            transform: translateY(-8px) scale(1.05);
            box-shadow: 0 12px 30px rgba(249, 115, 22, 0.8);
        }

        @keyframes pulse {
            0% { transform: scale(1); box-shadow: 0 8px 25px rgba(249, 115, 22, 0.6); }
            50% { transform: scale(1.03); box-shadow: 0 10px 30px rgba(249, 115, 22, 0.8); }
            100% { transform: scale(1); box-shadow: 0 8px 25px rgba(249, 115, 22, 0.6); }
        }
        @keyframes bounceIn {
            0%, 20%, 40%, 60%, 80%, 100% {
                transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            }
            0% { opacity: 0; transform: scale3d(.3, .3, .3); }
            20% { transform: scale3d(1.1, 1.1, 1.1); }
            40% { transform: scale3d(.9, .9, .9); }
            60% { opacity: 1; transform: scale3d(1.03, 1.03, 1.03); }
            80% { transform: scale3d(.97, .97, .97); }
            100% { opacity: 1; transform: scale3d(1, 1, 1); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .animate-fade-in { animation: fadeIn 1s ease-out forwards; }
        .animate-slide-up { animation: slideUp 1s ease-out forwards; }
        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .section-padding {
            padding: 4rem 0; /* Padding vertical, padding horizontal via .section-content */
        }
        .section-title {
            font-size: 3rem; /* Títulos de seção maiores */
            font-weight: 800;
            color: #1F2937;
            text-align: center;
            margin-bottom: 3.5rem;
            position: relative;
            letter-spacing: -0.03em;
        }
        .section-title::after {
            content: '';
            display: block;
            width: 100px; /* Linha maior */
            height: 6px; /* Linha mais grossa */
            background: linear-gradient(90deg, #F97316 0%, #FFD700 100%); /* Gradiente nos títulos */
            margin: 1.2rem auto 0;
            border-radius: 5px;
        }
        .problem-card, .feature-card, .benefit-item {
            background-color: #fff;
            border-radius: 16px;
            padding: 2.5rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.4s ease-in-out, box-shadow 0.4s ease-in-out;
            border: 1px solid #E2E8F0;
        }
        .problem-card {
            border-left: 8px solid #EF4444; /* Borda vermelha para problemas */
        }
        .feature-card {
            border-left: 8px solid #3B82F6; /* Borda azul para soluções */
        }
        .problem-card:hover, .feature-card:hover, .benefit-item:hover {
            transform: translateY(-12px);
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
        }
        .problem-icon, .feature-icon, .benefit-icon {
            font-size: 4rem; /* Ícones maiores */
            margin-bottom: 1.5rem;
            animation: fadeIn 1s ease-out forwards;
        }
        .problem-icon { color: #EF4444; } /* Vermelho para ícones de problema */
        .feature-icon { color: #3B82F6; } /* Azul para ícones de solução */
        .benefit-icon { color: #10B981; } /* Verde para ícones de benefício */

        .testimonial-section {
            background: #F8FAFC; /* Fundo suave */
            padding: 4rem 0; /* Padding vertical, padding horizontal via .section-content */
            text-align: center;
            border-top: 1px solid #E2E8F0;
            border-bottom: 1px solid #E2E8F0;
        }
        .testimonial-card {
            background-color: #ffffff;
            border-radius: 16px;
            padding: 2.5rem;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
            text-align: center;
            border-left: 8px solid #8B5CF6; /* Borda roxa para depoimentos */
            max-width: 700px;
            margin: 0 auto;
        }
        .testimonial-text {
            font-style: italic;
            color: #4B5563;
            margin-bottom: 2rem;
            font-size: 1.2rem;
            line-height: 1.8;
        }
        .author-info {
            font-weight: 700;
            color: #1F2937;
            font-size: 1.1rem;
        }
        .author-title {
            color: #6B7280;
            font-size: 1rem;
        }

        .highlight-text {
            color: #EF4444; /* Vermelho forte para urgência */
            font-weight: 800;
        }
        .price-display {
            font-size: 3.5rem; /* Preço maior */
            font-weight: 900;
            color: #1F2937;
            margin-top: 2rem;
            margin-bottom: 2rem;
        }
        .price-original {
            font-size: 2.5rem;
            color: #9CA3AF;
            text-decoration: line-through;
            margin-right: 1.5rem;
        }
        .price-offer {
            color: #F97316; /* Laranja vibrante para o preço de oferta */
        }
        .offer-box {
            background-color: #FFFBEB; /* Amarelo muito claro */
            border: 2px dashed #FACC15; /* Borda tracejada amarela */
            padding: 2.5rem;
            border-radius: 16px;
            margin-top: 3rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        /* Nova seção de Bônus 1 (Script Infalível) */
        .bonus-section-script {
            background: linear-gradient(135deg, #10B981 0%, #059669 100%); /* Gradiente verde vibrante */
            color: white;
            padding: 4rem 0;
            text-align: center;
            border-radius: 20px;
            margin: 3rem 0; /* Margem apenas vertical para destacá-lo */
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
            border: 4px solid #FACC15; /* Borda amarela chamativa */
        }
        .bonus-section-script::before {
            content: '🎁 BÔNUS EXCLUSIVO 🎁';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            padding: 0.8rem 0;
            background-color: rgba(255, 255, 255, 0.2);
            font-size: 1.5rem;
            font-weight: 800;
            letter-spacing: 0.1em;
            transform: translateY(-100%);
            animation: slideDownBonus 1s ease-out forwards;
        }

        /* Nova seção de Bônus 2 (Instagram para Negócios) */
        .bonus-section-instagram {
            background: linear-gradient(135deg, #6366F1 0%, #8B5CF6 100%); /* Gradiente roxo/índigo */
            color: white;
            padding: 4rem 0;
            text-align: center;
            border-radius: 20px;
            margin: 3rem 0; /* Margem apenas vertical para destacá-lo */
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
            border: 4px solid #FFD700; /* Borda amarela chamativa */
        }
         .bonus-section-instagram::before {
            content: '🔥 BÔNUS INCRÍVEL! 🔥';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            padding: 0.8rem 0;
            background-color: rgba(255, 255, 255, 0.2);
            font-size: 1.5rem;
            font-weight: 800;
            letter-spacing: 0.1em;
            transform: translateY(-100%);
            animation: slideDownBonus 1s ease-out forwards;
        }

        @keyframes slideDownBonus {
            from { transform: translateY(-100%); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .bonus-section-script h2, .bonus-section-instagram h2 {
            font-size: 3.5rem;
            font-weight: 900;
            margin-bottom: 1.5rem;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
            color: #FFD700; /* Amarelo no título do bônus */
        }
        .bonus-section-script p, .bonus-section-instagram p {
            font-size: 1.4rem;
            margin-bottom: 1.5rem;
            color: #E0F2FE;
        }
        .bonus-list {
            list-style: none;
            padding: 0;
            margin: 2rem auto;
            max-width: 600px;
        }
        .bonus-list li {
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            padding: 0.8rem 1.5rem;
            margin-bottom: 0.8rem;
            display: flex;
            align-items: center;
            font-size: 1.1rem;
            font-weight: 600;
            color: #ffffff;
            border-left: 5px solid #FACC15; /* Borda amarela nos itens do bônus */
            text-align: left;
        }
        .bonus-list li svg {
            margin-right: 1rem;
            color: #FACC15; /* Ícone amarelo */
        }
        .bonus-section-instagram .bonus-list li {
            border-left: 5px solid #FFD700; /* Borda amarela nos itens do bônus Instagram */
        }
         .bonus-section-instagram .bonus-list li svg {
            color: #FFD700; /* Ícone amarelo */
        }


        /* Responsividade geral */
        @media (max-width: 768px) {
            .hero-section {
                padding: 3rem 0; /* Ajustado para 0 lateralmente */
                border-bottom-left-radius: 20px;
                border-bottom-right-radius: 20px;
            }
            .hero-section h1 {
                font-size: 2.8rem;
            }
            .hero-section p {
                font-size: 1.4rem;
            }
            .cta-button {
                font-size: 1.6rem;
                padding: 1rem 2.5rem;
            }
            .section-title {
                font-size: 2.2rem;
                margin-bottom: 2.5rem;
            }
            .section-padding {
                padding: 2.5rem 0; /* Ajustado para 0 lateralmente */
            }
            .section-content {
                padding: 0 1rem; /* Menor padding lateral em mobile */
            }
            .price-display {
                font-size: 2.5rem;
            }
            .price-original {
                font-size: 1.8rem;
            }
            .problem-card, .feature-card, .benefit-item {
                padding: 1.8rem;
            }
            .problem-icon, .feature-icon, .benefit-icon {
                font-size: 3rem;
            }
            .bonus-section-script, .bonus-section-instagram {
                padding: 3rem 0; /* Ajustado para 0 lateralmente */
                margin: 2rem 0; /* Margem apenas vertical */
            }
            .bonus-section-script h2, .bonus-section-instagram h2 {
                font-size: 2.5rem;
            }
            .bonus-section-script p, .bonus-section-instagram p {
                font-size: 1.2rem;
            }
            .bonus-section-script::before, .bonus-section-instagram::before {
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Seção Hero: Título Impactante e Chamada para Ação Principal -->
        <section class="hero-section">
            <div class="section-content">
                <h1 class="animate-fade-in">O Atalho Definitivo para o <br>Sucesso Digital Está Aqui!</h1>
                <p class="animate-slide-up">Descubra as Ferramentas de Alto Impacto: o arsenal secreto que otimiza sua produtividade, acelera seus resultados e multiplica seu faturamento de forma estratégica.</p>
                <a href="https://pay.kiwify.com.br/gCIegmS" target="_blank" class="cta-button">QUERO ACELERAR MEUS RESULTADOS AGORA!</a>
                <div class="mt-10 text-white text-xl font-semibold opacity-90">
                    <p>📈 Mais de 1.000 profissionais já transformaram suas rotinas com este guia!</p>
                </div>
            </div>
        </section>

        <!-- Seção de Dor e Problema -->
        <section class="section-padding bg-gray-50">
            <div class="section-content">
                <h2 class="section-title">Cansado de Perder Tempo e Dinheiro?</h2>
                <div class="grid md:grid-cols-2 gap-8 text-center text-gray-700">
                    <div class="problem-card">
                        <span class="problem-icon">😩</span>
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">Sobrecarga de Escolhas</h3>
                        <p class="text-lg">Milhares de ferramentas, pouca clareza. Qual realmente funciona para o seu negócio?</p>
                    </div>
                    <div class="problem-card">
                        <span class="problem-icon">⏰</span>
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">Produtividade Estagnada</h3>
                        <p class="text-lg">Tarefas repetitivas drenando sua energia e impedindo seu crescimento?</p>
                    </div>
                    <div class="problem-card">
                        <span class="problem-icon">💸</span>
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">Dinheiro Desperdiçado</h3>
                        <p class="text-lg">Investindo em plataformas que não entregam o que prometem ou que você nem usa?</p>
                    </div>
                    <div class="problem-card">
                        <span class="problem-icon">🤯</span>
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">Resultados Aquém do Esperado</h3>
                        <p class="text-lg">Sua concorrência avançando enquanto você sente que está ficando para trás?</p>
                    </div>
                </div>
                <div class="text-center mt-12">
                    <p class="text-3xl font-bold text-indigo-700">Se você se identificou, este material foi feito para VOCÊ!</p>
                </div>
            </div>
        </section>

        <!-- Seção de Solução/Benefícios Principais -->
        <section class="section-padding bg-blue-100">
            <div class="section-content">
                <h2 class="section-title">A Resposta Definitiva: O Guia de Ferramentas de Alto Impacto!</h2>
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="feature-card">
                        <span class="feature-icon">✅</span>
                        <h3 class="text-2xl font-semibold text-gray-900 mb-2">Curadoria Especialista</h3>
                        <p class="text-gray-700">Acesso exclusivo às ferramentas que realmente funcionam e foram testadas por décadas de experiência no mercado digital. Diga adeus às tentativas e erros caros!</p>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">🚀</span>
                        <h3 class="text-2xl font-semibold text-gray-900 mb-2">Otimização Extrema</h3>
                        <p class="text-gray-700">Automatize processos, libere seu tempo e foque no que realmente importa: escalar seus resultados e multiplicar seu faturamento com inteligência.</p>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">🎯</span>
                        <h3 class="text-2xl font-semibold text-gray-900 mb-2">Estratégia Comprovada</h3>
                        <p class="text-gray-700">Um mapa claro para criadores de conteúdo, social media, designers, copywriters, estrategistas e infoprodutores. Sua jornada digital será simplificada e lucrativa.</p>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">💎</span>
                        <h3 class="text-2xl font-semibold text-gray-900 mb-2">Transforme Tempo em Lucro</h3>
                        <p class="text-gray-700">Nosso objetivo é que você ganhe tempo, organize sua operação e transforme cada minuto em lucro. Este não é apenas um guia, é um investimento no seu faturamento.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção de Prova Social com Depoimento/Autoridade -->
        <section class="testimonial-section">
            <div class="section-content">
                <h2 class="section-title text-indigo-700">Quem Validou Esta Curadoria?</h2>
                <div class="testimonial-card">
                    <img src="https://media.licdn.com/dms/image/v2/D4D03AQGZDmf0D6zk8g/profile-displayphoto-shrink_800_800/B4DZblNQhSIAAc-/0/1747602180651?e=1756339200&v=beta&t=h4Z-GT4H9L6m3NWSgrPHqv3WPMw9ExY7d1Z8KWwiTB8" alt="Foto de Osmar Costa" class="profile-image mx-auto mb-6 w-36 h-36 rounded-full object-cover border-4 border-indigo-400 shadow-lg" onerror="this.onerror=null;this.src='https://placehold.co/144x144/e2e8f0/64748b?text=Foto+Osmar';"/>
                    <p class="testimonial-text">
                        "Depois de décadas de atuação no mercado digital e de testar centenas de ferramentas, eu separei aquelas que realmente funcionam. São as que me ajudaram e continuam me ajudando até hoje a otimizar processos, escalar resultados e trabalhar com mais leveza e estratégia. Este material é uma extensão prática da minha rotina. Tudo o que você vai encontrar aqui faz parte do meu dia a dia como criador e estrategista."
                    </p>
                    <p class="author-info">Osmar Costa</p>
                    <p class="author-title">Publicitário, Designer e Estrategista Digital (Ex-V4 Company)</p>
                </div>
            </div>
        </section>

        <!-- Seção de Bônus 1 (Script Infalível) -->
        <section class="bonus-section-script">
            <div class="section-content">
                <h2 class="animate-fade-in-up">🎉 BÔNUS EXCLUSIVO PARA VOCÊ! 🎉</h2>
                <p class="animate-slide-up">Ao adquirir o Guia de Ferramentas de Alto Impacto HOJE, você ganha acesso imediato ao:</p>
                <h3 class="text-5xl font-extrabold mb-6 text-white text-shadow-lg">SCRIPT DE VENDAS INFALÍVEL!</h3>
                <p class="text-xl font-semibold mb-8 text-yellow-100">Este script completo e pronto para usar é o seu atalho para: </p>
                <ul class="bonus-list">
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Quebrar Objeções de Valor e Preço.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Gerenciar Prazos de Entrega com Confiança.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Fazer Follow-up de Forma Persuasiva e Correta.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Conduzir Negociações de Ponta a Ponta.</li>
                </ul>
                <p class="text-2xl font-bold mt-8 text-yellow-300">Tudo que você precisa para FECHAR MAIS VENDAS com maestria!</p>
                <a href="https://pay.kiwify.com.br/gCIegmS" target="_blank" class="cta-button bg-yellow-300 text-blue-900 shadow-lg hover:bg-yellow-400 mt-8">EU QUERO O GUIA + O SCRIPT INFALÍVEL!</a>
            </div>
        </section>

        <!-- Nova Seção de Bônus 2 (Instagram para Negócios) -->
        <section class="bonus-section-instagram">
            <div class="section-content">
                <h2 class="animate-fade-in-up">🔥 BÔNUS INCRÍVEL: INSTAGRAM PARA NEGÓCIOS! 🔥</h2>
                <p class="animate-slide-up">Transforme seu perfil em uma máquina de vendas e construa uma marca poderosa com o método de Osmar Costa. Este guia bônus irá te capacitar a:</p>
                <ul class="bonus-list">
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Criar uma Foto de Perfil Clara, Profissional e Reconhecível.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Desenvolver uma Bio Perfeita com Palavras-Chave e CTA Direto.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Utilizar Destaques como Vitrines Eternas do seu Conteúdo.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Construir um Feed Estratégico com Qualidade Visual e Conteúdo de Valor.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Analisar as Principais Métricas de Engajamento e Insights do Instagram.</li>
                    <li><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg> Escalar e Viralizar seu Conteúdo no Instagram de forma estratégica.</li>
                </ul>
                <p class="text-2xl font-bold mt-8 text-yellow-300">Domine o Instagram e transforme seguidores em CLIENTES FIÉIS!</p>
                <a href="https://pay.kiwify.com.br/gCIegmS" target="_blank" class="cta-button bg-yellow-300 text-blue-900 shadow-lg hover:bg-yellow-400 mt-8">QUERO O GUIA + OS BÔNUS IMPERDÍVEIS!</a>
            </div>
        </section>

        <!-- Gatilho de Escassez/Urgência e CTA Secundário -->
        <section class="section-padding bg-red-50 text-center">
            <div class="section-content">
                <h2 class="text-4xl font-extrabold text-red-700 mb-6 animate-bounce">
                    🚨 ULTIMA CHANCE: PREÇO PROMOCIONAL POR TEMPO LIMITADO! 🚨
                </h2>
                <p class="text-2xl text-gray-800 mb-8 font-semibold">
                    Essa é a sua oportunidade de ouro para ter acesso imediato às ferramentas que vão revolucionar sua performance digital.
                </p>
                <div class="offer-box mb-10">
                    <p class="text-2xl font-bold text-gray-800 mb-4">Aproveite Agora:</p>
                    <div class="price-display">
                        De: <span class="price-original">R$ 297,00</span> Por Apenas: <span class="price-offer">R$ 29,90</span>
                    </div>
                    <p class="text-xl font-semibold text-gray-700">Isso mesmo! Menos de um café por dia para um arsenal completo de sucesso!</p>
                </div>
                <a href="https://pay.kiwify.com.br/gCIegmS" target="_blank" class="cta-button bg-yellow-300 text-blue-900 shadow-xl hover:bg-yellow-400">GARANTIR MEU ACESSO AGORA!</a>
                <p class="mt-8 text-lg font-semibold text-gray-700">Oferta válida somente para os próximos acessos. Não perca!</p>
            </div>
        </section>

        <!-- Seção de Benefícios Detalhados (com ícones) -->
        <section class="section-padding bg-gray-100">
            <div class="section-content">
                <h2 class="section-title">O Que Você Vai Destravar Imediatamente:</h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="benefit-item">
                        <span class="benefit-icon">🧠</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Produtividade Extrema</h3>
                        <p class="text-gray-600">Organize tarefas, ideias e projetos como um mestre digital.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">🤖</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Automação Inteligente</h3>
                        <p class="text-gray-600">Deixe as máquinas trabalharem por você e ganhe horas preciosas.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">📊</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Análise de Mercado Afiada</h3>
                        <p class="text-gray-600">Descubra tendências e domine seu nicho antes da concorrência.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">📝</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Copywriting Magnético</h3>
                        <p class="text-gray-600">Crie textos que vendem e convertem em qualquer plataforma.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">✨</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">IA para Criatividade</h3>
                        <p class="text-gray-600">Gere conteúdo, imagens e vídeos com o poder da Inteligência Artificial.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">🛍️</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">E-commerce Otimizado</h3>
                        <p class="text-gray-600">Plataformas e ferramentas para turbinar suas vendas online.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">🎬</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Vídeos e Lives Profissionais</h3>
                        <p class="text-600">Crie transmissões e conteúdos audiovisuais de alta qualidade.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">🤝</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Gestão de Comunidade Forte</h3>
                        <p class="text-gray-600">Construa e nutra comunidades engajadas e lucrativas.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">💰</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Finanças no Controle</h3>
                        <p class="text-gray-600">Mantenha suas finanças organizadas e seus lucros em crescimento.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">🌐</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Sites de Alta Conversão</h3>
                        <p class="text-gray-600">Crie páginas que transformam visitantes em clientes fiéis.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">🎨</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Design Impactante</h3>
                        <p class="text-gray-600">Ferramentas para criar visuais profissionais sem ser um expert.</p>
                    </div>
                    <div class="benefit-item">
                        <span class="benefit-icon">💼</span>
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Freelancer de Sucesso</h3>
                        <p class="text-gray-600">Encontre projetos e construa um portfólio que gera mais clientes.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA Final com Garantia -->
        <section class="section-padding bg-indigo-700 text-white text-center rounded-t-3xl shadow-inner">
            <div class="section-content">
                <h2 class="text-4xl font-extrabold mb-4 animate-fade-in-up">🌟 SUA JORNADA PARA O TOPO COMEÇA AGORA! 🌟</h2>
                <p class="text-2xl mb-8">Não espere mais para otimizar seu trabalho, aumentar seus lucros e ter o controle total da sua vida digital.</p>
                <div class="price-display">
                    De: <span class="price-original">R$ 297,00</span> Por Apenas: <span class="price-offer">R$ 29,90</span>
                </div>
                <a href="https://pay.kiwify.com.br/gCIegmS" target="_blank" class="cta-button bg-yellow-300 text-blue-900 shadow-lg hover:bg-yellow-400">CLIQUE AQUI E GARANTA SEU ACESSO COM DESCONTO!</a>
                <p class="mt-8 text-xl font-bold">🔒 Satisfação 100% Garantida ou Seu Dinheiro de Volta!</p>
                <p class="text-lg">Você tem 7 dias para testar. Se não gostar, basta pedir seu dinheiro de volta.</p>
                <div class="mt-6 text-sm text-gray-200">
                    <p>Processado com Segurança por Kiwify.</p>
                    <img src="https://images.seeklogo.com/logo-png/48/2/kiwify-logo-png_seeklogo-489310.png" alt="Logo da Kiwify" class="mx-auto mt-2 opacity-80"/>
                </div>
            </div>
        </section>

        <!-- Rodapé -->
        <footer class="bg-gray-900 text-white text-center py-6">
            <div class="section-content">
                <p>&copy; 2025 Ferramentas de Alto Impacto. Todos os direitos reservados.</p>
                <p class="text-sm mt-2">Desenvolvido por Osmar Costa</p>
            </div>
        </footer>
    </div>
</body>
</html>
