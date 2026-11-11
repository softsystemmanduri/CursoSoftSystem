💻 Informática Básica Simples e Direta

Curso interativo de informática do básico ao intermediário, em uma única página HTML. Criado pela Soft System para ensinar idosos, crianças e iniciantes a usar o computador, o celular, a internet e a inteligência artificial com segurança, e a se preparar para o mercado de trabalho.

Instrutor: Jonatas Uchoas da Silva, técnico em informática há 20 anos Empresa: Soft System · CNPJ 64.858.422/0001-85 Instagram: @softsysteminfo

📚 Conteúdo

São 9 módulos principais + 6 bônus, com aulas curtas, glossário, exercícios práticos, desafios divertidos e um teste ao final de cada módulo.

#	Módulo
1	Comece aqui: seu primeiro contato (para quem nunca usou um computador)
2	Conhecendo o computador e o celular
3	Primeiros passos no sistema
4	Digitação e documentos
5	Internet com segurança
6	E-mail e comunicação
7	Planilhas e apresentações básicas
8	Inteligência artificial no dia a dia
9	Preparação para o mercado de trabalho
🎁 10	PCs gamers e otimização
🎁 11	Como ganhar dinheiro na internet
🎁 12	Manutenção básica de PC e notebook
🎁 13	Finanças digitais: Pix, banco e controle de gastos 🔥
🎁 14	Marketing digital e redes sociais para vender 🔥
🎁 15	Produtividade e organização digital 🔥

🔥 = temas em alta no mercado de cursos online (inteligência artificial, finanças e negócios, marketing e vendas), segundo pesquisa de mercado de 2026. Esses módulos aparecem com a etiqueta "Tema em alta" na página.

✨ Recursos da página
Tela inicial com visual de página de vendas, fundo temático de informática e cartões de módulos com tempo estimado
Aulas em slides com navegação por botões e pelas setas do teclado
Cartões 3D das peças do computador que viram ao toque
Tela de computador simulada (ícones, janelas e menu Iniciar) para o aluno treinar
Treino interativo de mouse (clique, duplo clique, clique direito e arrastar) e teclado na tela
Testes de múltipla escolha com correção explicada e nota por módulo
Botão Preciso de ajuda com dúvidas frequentes de cada módulo e link para o Instagram
Leitura em voz alta: ao passar o mouse (ou tocar) em textos, módulos e botões, a página lê o conteúdo em português; há também o botão "Ouvir esta aula" e uma chave para ligar ou desligar a voz (usa a síntese de voz do próprio navegador)
Rádio no topo: atalhos com play/pause para a Rádio Mix FM e a Rádio Metropolitana, com controle de volume, ao lado do título
Botão para silenciar a voz do curso, no topo da página
Progresso salvo no navegador do aluno (localStorage)
Certificado de conclusão com o nome do aluno, a logo da Soft System, CNPJ e assinatura, pronto para imprimir ou salvar em PDF
Seção "Sobre o instrutor" e rodapé com os dados da empresa
Layout responsivo, pensado para celular e computador, com letras grandes para facilitar a leitura
🗂️ Arquivos
.
├── index.html   # o curso completo (HTML, CSS e JavaScript em um só arquivo, com a logo embutida)
└── README.md

O arquivo não tem dependências externas: não precisa de instalação, internet para bibliotecas ou servidor.

▶️ Como usar

Localmente: baixe o index.html e abra no navegador (Chrome, Edge, Firefox ou Safari).

No GitHub Pages:

Envie o index.html e o README.md para o repositório.
Vá em Settings → Pages.
Em Source, escolha a branch principal (main) e a pasta / (root).
Salve. O curso ficará disponível em https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/.

Em plataformas de cursos (ex.: Hotmart): use o endereço publicado como aula na área de membros e anexe a apostila em PDF.

🛠️ Como personalizar

Tudo está dentro do index.html, na seção <script>.

O que mudar	Onde procurar
Textos das aulas, glossário e exercícios	Variáveis M, X, Y e Z
Perguntas dos testes	Campo q de cada módulo em M
Dúvidas frequentes	Variável F
Objetivo e tempo de cada módulo	Variável O
Instagram, CNPJ e nome do instrutor	Busque por softsysteminfo, 64.858.422/0001-85 e Jonatas Uchoas da Silva
Carga horária do certificado	Variável hrs na função makeCert
Rádios do topo (nomes e endereços das transmissões)	Variável RD
Cores	Variáveis CSS no início de <style> (--y, --b, --o e outras)
Logo	Atributo src da imagem no <header> (imagem em base64)

Formato de um módulo:

js
{ t: "Título", i: "🧩", s: [ ["Título da aula", ["item 1", "item 2"]] ],
  q: [ ["Pergunta?", ["opção A", "opção B"], indiceDaCorreta, "explicação"] ] }
⚠️ Observações
Ajuda por IA: o campo "Pergunte à IA" só aparece em ambientes que oferecem esse recurso (como o Claude). Fora deles, ele fica oculto e o resto da ajuda continua funcionando.
Certificado e progresso: são gerados e guardados no navegador do aluno. Para uso comercial com controle de conclusão, prefira liberar o certificado pela plataforma de ensino.
Valores do MEI: limites e valores mudam. Revise o conteúdo do módulo 11 antes de cada lançamento.
Voz: a leitura usa a voz do navegador ou do aparelho do aluno, então a qualidade varia. Em alguns navegadores, o áudio só começa depois do primeiro clique na página.
Rádios: os endereços de transmissão (streams) podem mudar ou bloquear tocar em outros sites. Se uma rádio não tocar, a página mostra um link para o site oficial. Atualize a variável RD quando necessário. Esse recurso funciona melhor hospedado no seu próprio site ou no GitHub Pages.
Imagens: os desenhos das peças são ilustrações em cartões. Você pode trocar por fotos reais.
📄 Licença

© Soft System. Todos os direitos reservados. O conteúdo deste curso não pode ser copiado, revendido ou redistribuído sem autorização. Se preferir uma licença aberta, substitua esta seção.
