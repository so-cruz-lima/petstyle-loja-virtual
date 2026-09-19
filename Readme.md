

Passo 1 – Instalar Tailwind via NPM 
npm install tailwindcss @tailwindcss/cli

 2 – Criar seu arquivo CSS 
-  Adicione @import "tailwindcss"; import ao seu arquivo CSS principal.
 @import "tailwindcss";

Passo 3 – Rodar o CLI e compilar o CSS 

Execute a ferramenta CLI para escanear seus arquivos de origem em busca de classes e construir seu CSS.
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch


Passo 4 – Usar no HTML 
Adicione seu arquivo CSS compilado ao <head> e comece a usar as classes utilitárias do Tailwind para estilizar seu conteúdo.
    
... <head> ...  <link href="./output.css" rel="stylesheet">  <title>Tailwind Projeto</title> </head> <body>  
    <h1 class="text-3xl font-bold underline text-center mt-6">    Olá, Tailwind!  

    </h1> </body> </html> 
    
---

Classes de Utilidade O que são classes de utilidade? 
Características 
● São pequenas classes CSS criadas para executar uma única função específica, como aplicar margin, padding, cor de fundo, largura, entre outros. Tailwind CSS - Rapidly build modern websites without ever leaving your HTML. 
● Permitem aplicar estilos diretamente no HTML, dispensando a criação de folhas de estilo personalizadas para elementos simples. 
● Esse modelo de estilização contraria práticas tradicionais do CSS, mas oferece vantagens reais e comprovadas em produtividade e manutenção.