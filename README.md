# Estagio-web

<h3>1) Qual a função do "head" no HTML?</h3>

<p>R: Fornecer todos os dados e metadados existentes no site, como o título, arquivos exteriores como css ou js</p>


<h3>2) Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?</h3>

R: Não, você possuí duas opções para começar a criar a tela: mobile-first ou desktop. Ao criar para um ou para outro você irá precisar utilizar media queries para adpatar na responsividade, ou outros frameworks que facilitam isso.

<h3>3) O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?</h3>

R: Sim, passam pelo processo de ser renderizado no servidor e no final tudo é exibido na página, no processo de painting


<h3>4) Qual a função das tags H (h1, h2, h3, etc) no HTML?</h3>

R: Elas servem para identificar títulos e subtítulos do site, sendo H1 o mais importante (recomendado ter um por página) e h2,h3,h4 os subtítulos. Em uma estrutura é sempre bom manter a hierarquia organizada.

<h3>5) O que é SEO e como funciona?</h3>

R: É o sistema de busca do google, ele faz uma análise para identificar se o seu site está dentro das conformidade da web, caso sim, ele coloca o seu site no topo dos resultado do google.

<h3>6) O uso de media query é obrigatório em todas as páginas?</h3>

R: Depende do seu projeto, caso queira criar uma página que funcione em desktop e mobile você irá precisar utiliza-lo. Se for algo apenas para desktop por exemplo,

<h3>7) Qual a diferença entre CSS Inline e CSS em um arquivo?</h3>

R: CSS inline fica dentro da tag do html, por exemplo: 
<p style="font-size: 16px;"></p>

Já o CSS em arquivo, é um arquivo que você cria de forma separada: index.html style.css 

E você só coloca o arquivo dentro da tag head, em questão da cascata, o estilo do inline sobrepõe a estilização do css em arquivo

<h3>8) Como criar animações no CSS? Dê um exemplo.</h3>

R: Podemos criar animações utilizando o @keyframe

<h3>9) Qual a diferença entre class e ID no CSS?</h3>

Ambas servem para identificar uma tag, porém o class você pode utilizar mais de uma vez com o mesmo nome em diferentes elementos e o nome do ID é exclusivo de cada elemento, não podendo se repetir

<h3>10) Quais os diferentes tipos de seletores CSS?</h3>

Seletor por atributo, seletor por classe, seletor por ID, seletor negativo, seletero NTH.
