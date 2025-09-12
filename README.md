<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Além dos Fios - Projeto de Circuito Elétrico</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #3B82F6;
            --secondary: #10B981;
            --dark: #1F2937;
            --darker: #111827;
            --light: #F3F4F6;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--darker);
            color: var(--light);
        }
        .section {
            background-color: var(--dark);
            border-radius: 0.5rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .nav-link {
            transition: all 0.3s ease;
        }
        .nav-link:hover {
            color: var(--primary);
            transform: translateY(-2px);
        }
        .tech-item {
            transition: all 0.3s ease;
        }
        .tech-item:hover {
            background-color: rgba(59, 130, 246, 0.1);
            transform: translateX(5px);
        }
    </style>
</head>
<body class="min-h-screen">
    <header class="bg-gray-900 py-6 px-4 shadow-lg">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold text-blue-400">Além dos Fios</h1>
            <nav class="hidden md:flex space-x-8">
                <a href="#sobre" class="nav-link text-gray-300">Sobre</a>
                <a href="#integrantes" class="nav-link text-gray-300">Integrantes</a>
                <a href="#resumo" class="nav-link text-gray-300">Resumo</a>
                <a href="#tecnico" class="nav-link text-gray-300">Detalhes Técnicos</a>
                <a href="#fluxo" class="nav-link text-gray-300">Fluxo</a>
            </nav>
            <button class="md:hidden text-gray-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>
        </div>
    </header>

    <main class="container mx-auto px-4 py-8 space-y-8">
        <section id="sobre" class="section p-8 text-center">
            <h1 class="text-4xl md:text-5xl font-bold text-blue-400 mb-4">Além dos Fios</h1>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                Otimização do consumo energético através da automação com CLP em sistemas elétricos residenciais
            </p>
        </section>

        <section id="integrantes" class="section p-8">
            <h2 class="text-2xl font-semibold text-blue-400 mb-6">Integrantes do Grupo</h2>
            <div class="overflow-x-auto">
                <table class="min-w-full divide-y divide-gray-700">
                    <thead class="bg-gray-800">
                        <tr>
                            <th class="px-6 py-3 text-left text-xs font-medium text-gray-300 uppercase tracking-wider">Nome</th>
                            <th class="px-6 py-3 text-left text-xs font-medium text-gray-300 uppercase tracking-wider">Registro Acadêmico</th>
                        </tr>
                    </thead>
                    <tbody class="bg-gray-900 divide-y divide-gray-700">
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">Adrian Vinicius</td>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">202404250</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">Enzo Cezar</td>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">202400687</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">Gustavo Scotti</td>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">202401794</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">Luccas Ferraz</td>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">202404227</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">Matheus Lima</td>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">202400485</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">Rodrigo Azevedo</td>
                            <td class="px-6 py-4 whitespace-nowrap text-gray-300">202404226</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <section id="resumo" class="section p-8">
            <h2 class="text-2xl font-semibold text-blue-400 mb-6">Resumo do Projeto</h2>
            
            <div class="mb-8">
                <h3 class="text-xl font-medium text-green-400 mb-3">Objetivo</h3>
                <p class="text-gray-300">
                    Demonstrar como o CLP pode otimizar o consumo de energia em sistemas elétricos, abrindo ou fechando o circuito conforme a necessidade, evitando desperdício e promovendo uso sustentável de energia.
                </p>
            </div>
            
            <div class="mb-8">
                <h3 class="text-xl font-medium text-green-400 mb-3">Explicação</h3>
                <p class="text-gray-300 mb-4">
                    O CLP é programado para monitorar sinais de sensores ou horários programados. Quando não há necessidade de consumo (exemplo: ausência de pessoas em uma sala, carga da bateria solar completa ou iluminação natural suficiente), o CLP fecha o circuito e desliga a carga, evitando gasto desnecessário.
                </p>
                <p class="text-gray-300">
                    Quando há demanda real, o CLP abre o circuito e permite o funcionamento normal do sistema.
                </p>
            </div>
            
            <div>
                <h3 class="text-xl font-medium text-green-400 mb-3">Onde Será Usado</h3>
                <p class="text-gray-300">
                    Automatização Residencial
                </p>
            </div>
        </section>

        <section id="tecnico" class="section p-8">
            <h2 class="text-2xl font-semibold text-blue-400 mb-6">Detalhes Técnicos</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="tech-item p-4 border border-gray-700 rounded-lg">
                    <h3 class="text-lg font-medium text-green-400">CLP</h3>
                    <p class="text-gray-400">Controlador Lógico Programável</p>
                </div>
                <div class="tech-item p-4 border border-gray-700 rounded-lg">
                    <h3 class="text-lg font-medium text-green-400">Sensores de Tensão/Corrente</h3>
                    <p class="text-gray-400">Monitoramento energético</p>
                </div>
                <div class="tech-item p-4 border border-gray-700 rounded-lg">
                    <h3 class="text-lg font-medium text-green-400">Botão de Comando</h3>
                    <p class="text-gray-400">Controle manual do sistema</p>
                </div>
                <div class="tech-item p-4 border border-gray-700 rounded-lg">
                    <h3 class="text-lg font-medium text-green-400">Contatores</h3>
                    <p class="text-gray-400">Chaveamento de alta potência</p>
                </div>
                <div class="tech-item p-4 border border-gray-700 rounded-lg">
                    <h3 class="text-lg font-medium text-green-400">Relés Auxiliares</h3>
                    <p class="text-gray-400">Interface entre CLP e cargas</p>
                </div>
                <div class="tech-item p-4 border border-gray-700 rounded-lg">
                    <h3 class="text-lg font-medium text-green-400">Disjuntores</h3>
                    <p class="text-gray-400">Proteção do circuito</p>
                </div>
            </div>
        </section>

        <section id="fluxo" class="section p-8">
            <h2 class="text-2xl font-semibold text-blue-400 mb-6">Circuito Representativo (Fluxo)</h2>
            
            <div class="bg-gray-900 p-6 rounded-lg">
                <div class="flex flex-col md:flex-row justify-between items-center mb-8">
                    <div class="text-center mb-4 md:mb-0">
                        <div class="bg-gray-800 p-3 rounded-full inline-block">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
                            </svg>
                        </div>
                        <p class="text-gray-300 mt-2">Entrada</p>
                        <p class="text-sm text-gray-400">Sensor de presença / botão</p>
                    </div>
                    
                    <div class="hidden md:block">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 5l7 7-7 7M5 5l7 7-7 7" />
                        </svg>
                    </div>
                    
                    <div class="text-center mb-4 md:mb-0">
                        <div class="bg-gray-800 p-3 rounded-full inline-block">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z" />
                            </svg>
                        </div>
                        <p class="text-gray-300 mt-2">Processamento</p>
                        <p class="text-sm text-gray-400">CLP verifica a condição</p>
                    </div>
                    
                    <div class="hidden md:block">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 5l7 7-7 7M5 5l7 7-7 7" />
                        </svg>
                    </div>
                    
                    <div class="text-center">
                        <div class="bg-gray-800 p-3 rounded-full inline-block">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
                            </svg>
                        </div>
                        <p class="text-gray-300 mt-2">Saída</p>
                        <p class="text-sm text-gray-400">LED é ligada ou desligada automaticamente</p>
                    </div>
                </div>
                
                <div class="bg-gray-800 p-4 rounded-lg">
                    <h4 class="text-lg font-medium text-green-400 mb-2">Exemplo de fluxo completo:</h4>
                    <p class="text-gray-300">Sensor → CLP → Relé → Lâmpada (LED)</p>
                </div>
            </div>
        </section>
    </main>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const mobileMenuButton = document.querySelector('button[class*="md:hidden"]');
        });
    </script>
</body>
</html>
