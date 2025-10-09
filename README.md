# Joao TextEditor
Código do Joao TextEditor (jTE) e outras 

Changelog:
```
v1.0.0:
Versão inicial. Trouxe:
Editor,
Tela de carregamento,
Salvar Como (baixa o texto como arquivo),
Abrir Arquivo,
Limpar Texto,
Texto na nova aba (com botões de imprimir e fechar)

v1.0.1:
Os botões ficaram mais arredondados (tanto na página inicial, tanto no "Texto na nova aba"),

O "Texto na nova aba" agora tem dark mode automático,

O <pre> do "Texto na nova aba" agora não tem mais espaços extras,

Corrigido a cor de fundo do "Texto na nova aba",

O <pre> do "Texto na nova aba" tem um outline azul ao focar nele,

Adicionado debaixo do <pre> do "Texto na nova aba" 2 <p>'s, com o seguinte texto:
jTE Mini Page
⚠️ Esta é uma página temporária. Recarregar irá apagar o conteúdo.

Adicionado um contador debaixo da área de edição de texto,

Agora a área de edição de texto e os botões tem aria-label,

Substituido document.write para innerHTML,

Adicionado a numeração da versão do jTE do lado dos botões.

v1.0.2
Acessibilidade:
Adicionado aria na <div> dos botões (Ações de texto) e na textarea.

IU & Atalhos:
Enquanto o contador não carrega, é exibido "Contador carregando..."
Adicionado emojis na Ações de texto e também os rótulos
Adicionado tema claro/escuro: acessível via o botão Tema ou pressionando Shift + T
O copiar, colar e recortar tem alertas mais fáceis de entender.

Atalhos de teclado adicionados (jTE):
Ctrl + S: Baixa/salva o texto em um arquivo
Ctrl + O: Abre um arquivo definido pelo usuário
Ctrl + L: Limpa o texto que o usuário escreveu
Ctrl + P: Abre a aba 'jTE Page'

Shift + T: Alternar tema do jTE
Shift + F: foca no editor de texto (<textarea>)
Shift + B: desfoca do editor de texto

Cor da área de edição de texto está mais branco e o tamanho de fonte foi de 16 pixels para 17 pixels.
Mais legibilidade na área de edição de texto.
Borda adicionada na página para evitar que usuários confudam a página com o navegador. 

Segurança e outros:
Para evitar erros no uso de &, o & será convertido para &amp;.
O menu de contexto vai ser escondido quando a página mudar de tamanho.
```
