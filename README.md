Glossário
Lista de Tags
Início
!DOCTYPE
Especifica a versão HTML utilizada no documento.

<!DOCTYPE ...>

Exemplo(s):

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2//EN">

Início
A
Serve para definir um link ou um "anchor".

<A [NAME="nome"] [HREF="url"] [TARGET="nome"]>

NAME
Define um "anchor" dentro de um documento HTML.
HREF
Define o endereço destino do link.
TARGET
Define a janela (ou frame) em que que o ficheiro destino deve ser aberto. Os valores possíveis são: o nome de uma janela (ou frame), "_top", "_self", "_parent" ou "_blank".
Exemplo(s):

<A NAME="Anchor1">Link1</a>
<A HREF="http://www.sapo.pt/">SAPO</a>
<A HREF="links.html" target="Win1">Links</a>

Início
ADDRESS
Define um endereço de mailing. O texto é normalmente visualizado em itálico.

<ADDRESS>

Exemplo(s):

<ADDRESS>hgr@mail.telepac.pt</ADDRESS>

Início
APPLET
Insere um applet Java num documento HTML.

<APPLET [CODEBASE="url"] [CODE="url"] [NAME="nome"] [ALT="texto"] WIDTH=pixels HEIGHT=pixels [ALIGN="alinhamento"] [HSPACE=pixels] [VSPACE=pixels]>

CODEBASE
Directoria em que o applet está localizado.
CODE
Nome do applet.
NAME
Nome utilizado por outros objectos na página para identificar o applet.
ALT
Texto alternativo.
WIDTH
Largura inicial da área da página reservada para mostrar o applet.
HEIGHT
Altura inicial da área da página reservada para mostrar o applet.
ALIGN
Alinhamento do applet em relação ao texto circundante.
HSPACE
Espaço horizontal entre o applet e os objectos circundantes na página.
VSPACE
Espaço vertical entre o applet e os objectos circundantes na página.
Exemplo(s):

<APPLET CODE="Bubbles.class" WIDTH=500 HEIGHT=500>Animated Bubbles</APPLET>

Início
AREA
Especifica a forma de um "ponto quente" de um "client-side image map".

<AREA [SHAPE="forma"] [COORDS="coordenadas"] [HREF="url"] [NOHREF] [TARGET="nome"] [ALT="texto"]>

SHAPE
Forma do "ponto quente". Os valores possíveis são:
RECT:
Rectângulo. Exige 4 coordenadas: x1, y1, x2 e y2.

CIRC:
Circulo. Exige 3 coordenadas: centrox, centroy e raio.

RECT:
Polígono. Aceita 3 ou mais pares de coordenadas que definam o polígono.

DEFAULT:
Corresponde a todas as áreas da imagem não definidas por outras tags AREA no mesmo image map.

COORDS
As coordenadas que definem a área do "ponto quente".
HREF
Endereço do documento destino.
NOHREF
Define que, se o utilizador clicar a região definida, não deve acontecer nada.
TARGET
Nome da janela (ou frame) onde o documento destivo deve ser visualizado.
ALT
Texto alternativo.
Exemplo(s):

<AREA SHAPE="rect" COORDS="10,10,40,50" HREF="doc1.html">
<AREA SHAPE="circ" COORDS="100,10,20" NOHREF>
<AREA SHAPE="default" HREF="doc3.html" TARGET="Frame2">

Início
B
Desenha o texto em bold (negrito).

<B>

Exemplo(s):

<B>Texto em negrito</a>

Início
BASE
Define o URL do documento actual.

<BASE [HREF="url"] [TARGET="nome"]>

HREF
URL do documento.
TARGET
Especifica a janela (ou frame) em que todos os links do documento devem ser abertos.
Exemplo(s):

<BASE HREF="http://www.fe.up.pt.pt/">

Início
BASEFONT
Define a formatação por defeito para o texto não formatado usando "style-sheets" ou tags FONT.

<BASEFONT [FACE="nome"] [SIZE=n] [COLOR="cor"]>

FACE
Tipo de letra (font).
SIZE
Tamanho (entre 1 e 7).
COLOR
Cor do texto.
Exemplo(s):

<BASEFONT FACE="Arial" SIZE=3>
<BASEFONT FACE="Arial" COLOR="white">
<BASEFONT SIZE="+1" COLOR="#008000">

Início
BGSOUND
Permite incluir m´sica de fundo numa página HTML.

<BGSOUND [SRC="url"] [LOOP=n]>

SRC
Endereço do ficheiro de som.
LOOP
Define o n´mero de vezes que o som deve tocar antes de parar. LOOP="-1" ou LOOP="infinite" causa que o som não páre de tocar.
Exemplo(s):

<BGSOUND SRC="music1.mid" LOOP=3>
<BGSOUND SRC="music1.mid" LOOP="infinite">

Início
BIG
Aumenta o tamanho do texto.

<BIG>

Exemplo(s):

<BIG>Texto Grande</BIG>

Início
BLOCKQUOTE
Utilizado para marcar citações.

<BLOCKQUOTE>

Exemplo(s):

<BLOCKQUOTE>Citação aqui</BLOCKQUOTE>

Início
BODY
Delimita o corpo do documento.

<BODY [BGCOLOR="cor"] [BACKGROUND="url"] [TEXT="cor"] [LINK="cor"] [VLINK="cor"] [ALINK="cor"] [LEFTMARGIN="pixels"] [TOPMARGIN="pixels"]>

BGCOLOR
Define a côr de fundo da página.
BACKGROUND
Define a imagem a utilizar como fundo da página.
TEXT
Define a cor do texto.
LINK
Define a cor dos links não visitados.
VLINK
Define a cor dos links já visitados.
ALINK
Define a cor dos links quando o utilizador os seleccionar.
LEFTMARGIN
Especifica o tamanho (em pixels) da margem horizontal do corpo da página.
TOPMARGIN
Especifica o tamanho (em pixels) da margem vertical do corpo da página.
Exemplo(s):

<BODY BGCOLOR="white" LINK="blue" ALINK="green" VLINK="red">...</BODY>
<BODY BACKGROUND="/Images/back.gif" TEXT="#000000">...</BODY>

Início
BR
Insere uma quebra de linha.

<BR [CLEAR="tipo"]>

CLEAR
Insere espaço vertical de forma que o texto seguinte seja desenhado abaixo de imagens (ou outros objectos) que estejam ao mesmo nível do texto anterior. Os valores possíveis são: LEFT, RIGHT e ALL.
Exemplo(s):

Linha 1<br>Linha 2

Início
CAPTION
Define o título de uma tabela.

<CAPTION [ALIGN="alinhamento"]>

ALIGN
Especifica o alinhamento do título em relação à tabela.
Exemplo(s):

<TABLE>
<CAPTION>Lista de Elementos</CAPTION>
...
</TABLE>

Início
CENTER
Centre os elementos incluidos entre a tag iniciadora e a tag terminadora.

<CENTER>

Exemplo(s):

<CENTER>Texto Centrado</CENTER>

Início
CITE
Indica uma citação.

<CITE>

Exemplo(s):

<CITE>Citação</CITE>

Início
CODE
Indica uma porção de código (C, por exemplo). O texto é, normalmente, desenhado usando uma font de largura fixa e num tamanho reduzido.

<CODE>

Exemplo(s):

<CODE>VarA := 10;</CODE>

Início
COL
Define as propriedades de uma ou mais colunas de uma tabela. Quando utilizado em conjunto com a tag COLGROUP, define as propriedades de uma coluna dentro de um grupo de colunas.

<COL [ALIGN="tipo"] [SPAN=n] [WIDTH=pixels]>

ALIGN
Define o alinhamento das células da coluna.
SPAN
Define o número de colunas consecutivas a que esta TAG se aplica.
WIDTH
Define a largura da coluna.
Exemplo(s):

<COLGROUP>
<COL WIDTH=30>
<COL WIDTH=100>

Início
COLGROUP
Define as propriedades de uma conjunto de colunas de uma tabela.

<COLGROUP [ALIGN="tipo"] [SPAN=n] [WIDTH=pixels]>

ALIGN
Define o alinhamento das células das colunas.
SPAN
Número de colunas consecutivas as quais se aplica a definição.
WIDTH
Define a largura das colunas.
Exemplo(s):

<TABLE>
<COLGROUP SPAN=10 WIDTH=130>
<COL WIDTH=30>
<COL WIDTH=100>
<COLGROUP>
<COL WIDTH=100>
...
</TABLE>

Início
DD
Define uma definição dentro de uma lista de definições.

<DD>

Exemplo(s):

<DL>
<DT>Nome:
<DD>Hugo Alexandre Ribeiro
<DT>Email:
<DD>hgr@mail.telepac.pt
</DL>

Início
DFN
Especifica uma definição.

<DFN>

Exemplo(s):

<DFN>Definição</DFN>

Início
DIV
Permite a definição de um grupo de elementos (tags) HTML como um todo, ou seja, permite definir uma divisão do documento.

<DIV [ALIGN="tipo"]>

ALIGN
Define o alinhamento dos conteúdos do elemento DIV.
Exemplo(s):

Linha1<DIV>Linha 2</DIV><DIV>Linha 3<P>Linha 4</DIV>

Início
DL
Define uma lista de definições.

<DL>

Exemplo(s):

<DL>
<DT>Nome:
<DD>Hugo Alexandre Ribeiro
<DT>Email:
<DD>hgr@mail.telepac.pt
</DL>

Início
DT
Especifica um termo numa lista de definições. Indica cada um dos termos que estão a ser definidos.

<DT>

Exemplo(s):

<DL>
<DT>Nome:
<DD>Hugo Alexandre Ribeiro
<DT>Email:
<DD>hgr@mail.telepac.pt
</DL>

Início
EM
Enfâse. Causa que o texto seja apresentado em itálico.

<EM>

Exemplo(s):

<EM>Texto</EM>

Início
EMBED
Insere um objecto numa página HTML.

<EMBED [SRC="url"] [NAME="nome"] [WIDTH=pixels] [HEIGHT=pixels] [OPTIONAL PARAM="valor"] [AUTOSTART="tipo"] [HIDDEN="tipo"] [LOOP="tipo"]>

SRC
Localização do objecto.
NAME
Nome a utilizar por outros objectos para referir este objecto.
WIDTH
Largura da área da página reservada para o objecto.
HEIGHT
Altura da área da página reservada para o objecto.
OPTIONAL PARAM
Define os parâmetros do objecto.
AUTOSTART
Define se o objecto deve ser iniciado imediatamente após ter sido carregado. TRUE ou FALSE.
HIDDEN
Define se o objecto deve ser visível na página. TRUE ou FALSE.
LOOP
TRUE ou FALSE.
Exemplo(s):

<EMBED SRC="movie.avi" WIDTH=100 HEIGHT=250 AUTOSTART="true">
<EMBED SRC="s1.mid" AUTOSTART="true" HIDDEN="true">

Início
FONT
Defino o tipo de letra, a cor e tamanho do texto.

<FONT [FACE="nome"] [SIZE=n] [COLOR="cor"]>

FACE
Lista dos tipos de letra do texto, por ordem de preferência.
SIZE
Define o tamanho do texto. De 1 (menor) a 7 (maior).
COLOR
Define a cor do texto.
Exemplo(s):

<FONT FACE="Arial,Helvetica" SIZE=4>Texto</FONT>
<FONT SIZE="+2" COLOR="blue">Texto</FONT>
<FONT SIZE="-1" COLOR="#008000">Texto</FONT>

Início
FORM
Define uma form.

<FORM [ACTION="url"] [METHOD="tipo"] [TARGET="nome"]>

ACTION
Especifica o endereço a usar para realizar a acção da form.
METHOD
Define a forma como os dados devem ser enviados para o servidor.
GET:
Adiciona os dados, como argumentos, ao URL.

POST:
Envia os dados através de uma transacção HTTP.

TARGET
Define a janela (ou frame) onde os resultados da form devem ser abertos.
Exemplo(s):

<FORM ACTION="http://server.pt/cgi-bin/adduser" METHOD="post" TARGET="_top">
...
</FORM>
<FORM ACTION="mailto:hgr@mail.telepac.pt" METHOD="post">
...
</FORM>

Início
FRAME
Define uma frame de um "frameset".

<FRAME [NAME="nome"] [SRC="url"] [FRAMEBORDER=n] [MARGINWIDTH=pixels] [MARGINHEIGHT=pixels] [NORESIZE] [SCROLLING="tipo"]>

NAME
Define o nome da frame.
SRC
Especifica o ficheiro fonte com os conteúdos da frame.
FRAMEBORDER
Especifica se o browser deve desenhar uma moldura em torno da frame. Os valores possíveis são 0 (sem frame) ou 1 (com frame).
MARGINWIDTH
Define a dimensão da margem horizontal da frame.
MARGINHEIGHT
Define a dimensão da margem vertical da frame.
NORESIZE
Impede o utilizador de alterar o tamanho da frame.
SCROLLING
Cria a frame com uma "scrolling bar" (barra de deslocamento).
Exemplo(s):

<FRAME NAME="Frame1" SRC="frame1.html" FRAMEBORDER=0 SCROLLING="yes">
<FRAME NAME="Frame2" SRC="frame2.html" FRAMEBORDER=0 SCROLLING="no" NORESIZE>

Início
FRAMESET
Define um "frameset".

<FRAMESET [COLS="valores"] [ROWS="valores"] [FRAMEBORDER=n] [FRAMESPACING="pixels"]>

COLS
Cria um frameset com colunas. As dimensões das colunas podem ser definidas em percentagens (%), pixels ou tamanhos relativos.
ROWS
Cria um frameset com linhas. As dimensões das linhas podem ser definidas em percentagens (%), pixels ou tamanhos relativos.
FRAMEBORDER
Especifica se o browser deve desenhar uma moldura em torno das frames. Os valores possíveis são 0 (sem frame) ou 1 (com frame).
FRAMESPACING
Define o espaço entre as frames (em pixels).
Exemplo(s):

<FRAMESET COLS="33%,33%,33%">
 <FRAMESET ROWS="*,200">
  <FRAME NAME="Frame1" SRC="frame1.html">
  <FRAME NAME="Frame2" SRC="frame2.html">
 </FRAMESET>
 <FRAME NAME="Frame3" SRC="frame3.html">
 <FRAME NAME="Frame4" SRC="frame4.html">
</FRAMESET>

Início
Hn
Heading.

<Hn [ALIGN="tipo"]>

ALIGN
Define o alinhamento do texto.
Exemplo(s):

<H1>Heading 1</H1>
<H3>Heading 3</H3>
<H6>Heading 6</H6>

Início
HEAD
Marca o cabeçalho do documento.

<HEAD>

Exemplo(s):

<HTML>
<HEAD>
<TITLE>Net Sites</TITLE>
</HEAD>
...
</HTML>

Início
HR
Insere uma linha horizontal.

<HR [ALIGN="tipo"] [SIZE=pixels] [WIDTH=pixels] [NOSHADE]>

ALIGN
Define o alinhamento da linha na página.
SIZE
Define a altura da linha em pixels.
WIDTH
Define a largura da linha.
NOSHADE
Desenha a linha sem sombra.
Exemplo(s):

<HR ALIGN="center" SIZE=3 WIDTH=200>
<HR WIDTH="75%" NOSHADE>
<HR NOSHADE>

Início
HTML
Especifica que o documento foi desenvolvido em HTML.

<HTML>

Exemplo(s):

<HTML>
...
</HTML>

Início
I
Itálico.

<I>

Exemplo(s):

<I>Texto em Itálico</I>

Início
IFRAME
Define uma "floating frame".

<IFRAME [NAME="nome"] [SRC="url"] [FRAMEBORDER=n] [MARGINWIDTH=pixels] [MARGINHEIGHT=pixels] [SCROLLING="tipo"] [ALIGN="tipo"] [WIDTH=pixels] [HEIGHT=pixels]>

NAME
Define o nome da frame.
SRC
Especifica o URL do ficheiro fonte.
FRAMEBORDER
Desenha, ou não, uma moldura à volta da frame. Os valores possíveis são 0 ou 1.
MARGINWIDTH
Tamanho, em pixels, da margem horizontal da frame.
MARGINHEIGHT
Tamanho, em pixels, da margem vertical da frame.
SCROLLING
Cria a frame com uma "scrolling bar". Os valores possíveis são YES ou NO.
ALIGN
Define o alinhamento da frame em relação ao texto circundante.
WIDTH
Largura, em pixels, da frame.
HEIGHT
Altura, em pixels, da frame.
Exemplo(s):

<IFRAME NAME"IFrame1" SRC="foo.html"></IFRAME>

Início
ILAYER
Define um "layer inline".

<ILAYER [NAME="nome"] [LEFT=pixels] [TOP=pixels] [PAGEX=pixels] [PAGEY=pixels] [SRC="url"] [WIDTH=pixels] [HEIGHT=pixels] [CLIP="valores"] [Z-INDEX=n] [ABOVE="nome"] [BELOW="nome"] [VISIBILITY="tipo"] [BGCOLOR="cor"] [BACKGROUND="url"]>

NAME
Define o nome do layer.
LEFT
Posição horizontal do canto superior-esquerdo do layer em relação ao layer que o contém.
TOP
Posição vertical do canto superior-esquerdo do layer em relação ao layer que o contém.
PAGEX
Posição horizontal do canto superior-esquerdo do layer em relação ao documento que o contém.
PAGEY
Posição vertical do canto superior-esquerdo do layer em relação ao documento que o contém.
SRC
Especifica o URL do ficheiro HTML fonte.
WIDTH
Largura, em pixels, do layer.
HEIGHT
Altura, em pixels, do layer.
CLIP
Define os limites da área visível do layer. Aceita um valor composto por quatro números que definem os limites, respectivamente, esquerdo, superior, direito e inferior em relação ao canto superior-esquerdo do layer contentor.
Z-INDEX
Especifica a "stacking order" do layer.
ABOVE
Coloca o novo layer imediatamente por cima do layer especificado por este atributo.
BELOW
Coloca o novo layer imediatamente por baixo do layer especificado por este atributo.
VISIBILITY
Determina se o layer devem, ou não, ser visível. Os valores possíveis são: HIDE, SHOW e INHERIT.
BGCOLOR
Define a cor de fundo do layer.
BACKGROUND
Define a imagem de fundo do layer.
Exemplo(s):

<ILAYER NAME"Layer1" SRC="foo.html"></ILAYER>

Início
IMG
Insere uma imagem na página.

<IMG SRC="url" [ALT="texto"] [ALIGN="tipo"] [WIDTH=pixels] [HEIGHT=pixels] [BORDER=n] [HSPACE=pixels] [VSPACE=pixels] [USEMAP="nome"] [ISMAP]>

SRC
URL do ficheiro fonte.
ALT
Texto alternativo.
ALIGN
Alinhamento da imagem em relação aos elementos circundantes.
WIDTH
Largura da imagem, em pixels.
HEIGHT
Altura da imagem, em pixels.
BORDER
Define a largura, em pixels, da moldura a desenhar à volta da imagem.
HSPACE
Define a margem horizontal da imagem em relação aos elementos circundantes.
VSPACE
Define a margem vertical da imagem em relação aos elementos circundantes.
USEMAP
Identifica a imagem como sendo um "client-side image map".
ISMAP
Identifica a imagem como sendo um "server-side image map".
Exemplo(s):

<IMG SRC="img1.gif" ALIGN="right" WIDTH=200 HEIGHT=156>
<IMG SRC="http://server.pt/gifs/img1.gif" ALT="Logo">
<IMG SRC="img1.gif" ALT="Logo" USEMAP="#Navmap">
<IMG SRC="../maps/img1.map" ISMAP>

Início
INPUT
Define um elemento de uma form.

<INPUT [TYPE="tipo"] [NAME="nome"] [VALUE="valor"] [CHECKED] [SIZE=n] [MAXLENGTH=n] [SRC="url"] [ALIGN="tipo"]>

TYPE
Define o tipo de elemento que está a ser definido.
TEXT:
Campo de texto.

PASSWORD:
Idêntico a TEXT, com excepção que o texto não será visualizado.

IMAGE:
Define uma imagem para substituir o botão de submissão da form.

HIDDEN:
O campo não é visualizado, apesar dos seus conteúdos serem enviados para o servidor.

CHECKBOX:
Utilizado para atributos booleanos e para atributos que podem assumir vários valores diferentes.

RADIO:
Para atributos que aceitam um só valor de um conjunto de alternativas.

SUBMIT:
Botão para submeter os dados da form.

RESET:
Botão para limpar o conteúdo de todos os campos da form.

NAME
Define o nome do elemento.
VALUE
Para elementos alfa-numéricos, define o seu valor por defeito. Para elementos booleanos (por exemplo, RADIO) define o valor a enviar ao servidor quando o elemento for seleccionado.
CHECKED
Define que o elemento deve estar seleccionado por defeito. Válido apenas para CHECKBOX e RADIO.
SIZE
Define o tamanho, em caracteres, do elemento.
MAXLENGTH
Define o número máximo de caracteres que o campo aceita.
SRC
Usando quando TYPE="image", define o localização da imagem.
ALIGN
Define o alinhamento do elemento em relação aos objectos circundantes. Válido apenas para IMAGE.
Exemplo(s):

<INPUT TYPE="text" NAME="Elem1">
<INPUT TYPE="submit" VALUE="Submeter">
<INPUT TYPE="image" SRC="/images/in.gif">
<INPUT TYPE="radio" NAME="Radio1" VALUE="Y"> Yes
<INPUT TYPE="checkbox" NAME="Check1" VALUE="Y" CHECKED> Yes

Início
ISINDEX
Indica a presença de um índice procurável.

<ISINDEX [ACTION="url"] [PROMPT="texto"]>

ACTION
Especifica a localização do programa que recebe o texto introduzido pelo utilizador.
PROMPT
Define o texto a apresentar ao utilizador.
Exemplo(s):

<ISINDEX PROMPT="Chave da Procura:">

Início
KBD
Desenha o texto num estilo de letra de largura fixa.

<KBD>

Exemplo(s):

<KBD>Texto aqui</KBD>

Início
LAYER
Define um layer normal.

<LAYER [NAME="nome"] [LEFT=pixels] [TOP=pixels] [PAGEX=pixels] [PAGEY=pixels] [SRC="url"] [WIDTH=pixels] [HEIGHT=pixels] [CLIP="valores"] [Z-INDEX=n] [ABOVE="nome"] [BELOW="nome"] [VISIBILITY="tipo"] [BGCOLOR="cor"] [BACKGROUND="url"]>

NAME
Define o nome do layer.
LEFT
Posição horizontal do canto superior-esquerdo do layer em relação ao layer que o contém.
TOP
Posição vertical do canto superior-esquerdo do layer em relação ao layer que o contém.
PAGEX
Posição horizontal do canto superior-esquerdo do layer em relação ao documento que o contém.
PAGEY
Posição vertical do canto superior-esquerdo do layer em relação ao documento que o contém.
SRC
Especifica o URL do ficheiro HTML fonte.
WIDTH
Largura, em pixels, do layer.
HEIGHT
Altura, em pixels, do layer.
CLIP
Define os limites da área visível do layer. Aceita um valor composto por quatro números que definem os limites, respectivamente, esquerdo, superior, direito e inferior em relação ao canto superior-esquerdo do layer contentor.
Z-INDEX
Especifica a "stacking order" do layer.
ABOVE
Coloca o novo layer imediatamente por cima do layer especificado por este atributo.
BELOW
Coloca o novo layer imediatamente por baixo do layer especificado por este atributo.
VISIBILITY
Determina se o layer devem, ou não, ser visível. Os valores possíveis são: HIDE, SHOW e INHERIT.
BGCOLOR
Define a cor de fundo do layer.
BACKGROUND
Define a imagem de fundo do layer.
Exemplo(s):

<LAYER NAME"Layer1" SRC="foo.html">
...
</LAYER>

Início
LI
Denota um elemento de uma lista (definida pelas tags OL ou UL).

<LI>

Exemplo(s):

<UL>
 <LI>Item1
 <LI>Item2
</UL>
<OL>
 <LI>Item1
 <LI>Item2
</OL>

Início
LINK
Estabelece uma organização hierarquica para a navegação entre documentos. Esta tag deve ser definida dentro do cabeçalho do documento.

<LINK [HREF="url"] [REL="tipo"] [REV="tipo"] [TYPE="tipo"] [TARGET="nome"]>

HREF
Especifica o URL do documento que tem uma relação com o documento actual.
REL
Define o tipo de relação entre o documento especificado e o actual.
REV
Define o tipo de relação entre o documento actual e o especificado.
TYPE
Define o "internet media type".
TARGET
Define em que janela (ou frame) o documento destino deve ser aberto.
Exemplo(s):

<LINK REL="Index" HREF="index.html">
<LINK REL="Previous" HREF="chapter3.html">
<LINK REL="Next" HREF="chapter1.html">

Início
MAP
Especifica um "client-side image map".

<MAP [NAME="nome"]>

NAME
Define o nome do mapa.
Exemplo(s):

<MAP NAME="NavMap">
<AREA SHAPE="rect" COORDS="10,10,187,27" HREF="main.html">
<AREA SHAPE="default" NOHREF>
</MAP>

Início
MARQUEE
Cria um "marquee".

<MARQUEE [ALIGN="tipo"] [BEHAVIOUR="tipo"] [BGCOLOR="cor"] [DIRECTION="tipo"] [LOOP=n] [SCROLLAMOUNT=n] [SCROLLDELAY=n] [WIDTH="pixels"] [HEIGHT="pixels"] [HSPACE="pixels"] [VSPACE="pixels"]>

ALIGN
Define o alinhamento do "marquee" em relação aos objectos circundantes.
BEHAVIOUR
Define o comportamento de "marquee". Os valores possíveis são SCROLL, SLIDE e ALTERNATE.
BGCOLOR
Define a cor de fundo.
DIRECTION
Define a orientação do deslocamento do texto.
LOOP
Número de vezes que o texto deve ser mostrado antes de parar.
SCROLLAMOUNT
Define o número de pixels entre visualizações consecutivas do "marquee".
SCROLLDELAY
Define o número de milisegundos entre visualizações consecutivas do "marquee".
WIDTH
Largura do "marquee".
HEIGHT
Altura do "marquee".
VSPACE
Define a margem vertical do "marquee".
HSPACE
Define a margem horizontal do "marquee".
Exemplo(s):

<MARQUEE DIRECTION="left" BEHAVIOUR>
Scrolling Marquee
</MARQUEE>

Início
META
Fornece informação acerca do documento HTML.

<META [HTTP-EQUIV="nome"] [NAME="nome"] [CONTENT="texto"]>

HTTP-EQUIV
Liga o documento a um "HTTP response header".
NAME
Especifica a propriedade que está a ser definida.
CONTENT
Define a meta-informação associada à propriedade.
Exemplo(s):

<META HTTP-EQUIV="refresh" CONTENT="10; URL=index.html">
<META NAME="author" CONTENT="Hugo Ribeiro">

Início
NOBR
Impede quebras de linha.

<NOFRAMES>

Exemplo(s):

<NOBR>Texto aqui</NOBR>

Início
NOFRAMES
Denota conteúdo visível apenas em browsers que não suportam frames.

<NOFRAMES>

Exemplo(s):

<NOFRAMES>
Conteúdo para browsers que não suportam frames
</NOFRAMES>

Início
NOLAYER
Denota conteúdo visível apenas em browsers que não suportam layers.

<NOLAYER>

Exemplo(s):

<NOLAYER>
Conteúdo para browsers que não suportam layers
</NOLAYER>

Início
NOSCRIPT
Denota conteúdo visível apenas em browsers que não suportam scripts.

<NOSCRIPT>

Exemplo(s):

<SCRIPT LANGUAGE="JavaScript">
...
</SCRIPT>
<NOSCRIPT>
Conteúdo Alternativo
</NOSCRIPT>

Início
OBJECT
Insere objectos (imagem, applets, documentos, etc.) na página.

<OBJECT [CODEBASE="url"] [CLASSID="url"] [DATA="url"] [SRC="url"] [ALIGN="tipo"] [WIDTH=pixels] [HEIGHT=pixels] [HSPACE=pixels] [VSPACE=pixels] [DECLARE] [USEMAP="nome"]>

CODEBASE
Especifica a localização do objecto.
CLASSID
Identifica a implementação do objecto.
DATA
Localização de dados do objecto.
SRC
Localização do objecto (no caso de imagens).
ALIGN
Alinhamento do objecto em relação aos elementos circundantes.
WIDTH
Largura da área da página reservada para o objecto.
HEIGHT
Altura da área da página reservada para o objecto.
HSPACE
Tamanho da margem horizontal.
VSPACE
Tamanho da margem vertical.
DECLARE
Declara o objecto mas não instancia.
USEMAP
Define o nome do "client-side map" a utilizar para o objecto.
Exemplo(s):

<OBJECT SRC="img1.gif"></OBJECT>
<OBJECT CLASSID="http://server.pt/clock.py">Texto Alternativo</OBJECT>

Início
OL
Lista ordenada de elementos.

<OL [TYPE="tipo"] [START=n]>

TYPE
Define o estilo de lista.
A:
Utiliza letras grandes para numerar os elementos. (A, B, ...)

a:
Utiliza letras pequenas para numerar os elementos (a, b, ...).

I:
Utiliza números romanos grandes para numerar os elementos (I, II, ...).

i:
Utiliza números romanos pequenos para numerar os elementos (i, ii, ...).

1:
Utiliza números para numerar os elementos (1, 2, ...).

START
Define o número inicial.
Exemplo(s):

<OL TYPE="a">
 <LI>Item 1
 <LI>Item 2
</OL>
<OL START=10>
 <LI>Item 10
 <LI>Item 11
</OL>

Início
OPTION
Define uma das opções de um bloco SELECT.

<OPTION [SELECTED] [VALUE="valor"]>

SELECT
Indica que a opção deve estar seleccionada por defeito.
VALUE
Valor a enviar ao servidor se o utilizador seleccionar a opção.
Exemplo(s):

<SELECT NAME="List1">
<OPTION VALUE="1">Opção 1
<OPTION VALUE="2" SELECTED>Opção 2
</SELECT>

Início
P
Insere um novo parágrafo.

<P [ALIGN="tipo"]>

ALIGN
Alinhamento do texto.
Exemplo(s):

<P>Parágrafo Normal</P>
<P ALIGN="center">Parágrafo Centrado</P>

Início
PARAM
Define o valor de um parâmetro de um objecto.

<PARAM [NAME="nome"] [VALUE="valor"] [VALUETYPE="tipo"]>

NAME
Nome do parâmetro.
VALUE
Valor.
VALUETYPE
Define a forma de interpretar o valor.
DATA:
Dados.

REF:
URL.

OBJECT:
URL de outro objecto do documento.

Exemplo(s):

<APPLET CODE="vba.class" WIDTH=100 HEIGHT=100>
<PARAM NAME="P1" VALUE="1">
<PARAM NAME="P2" VALUE="2">
</APPLET>

Início
PRE
Texto pré-formatado.

<PRE>

Exemplo(s):

<PRE>
Texto pré-formatado
</PRE>

Início
SAMP
Desenha o texto numa "font" de largura fixa.

<SAMP>

Exemplo(s):

<SAMP>Texto</SAMP>

Início
SCRIPT
Inclui uma script no documento. As scripts de um documento são executadas pela ordem que aparecem no documento.

<SCRIPT [LANGUAGE="nome"] [SRC="url"]>

LANGUAGE
Indica a linguagem que foi utilizada para escrever a script.
SRC
Localização do documento externo que contém o código da script.
Exemplo(s):

<SCRIPT LANGUAGE="JavaScript">
documente.write("A Primeira Script");
</SCRIPT>

Início
SELECT
Define um elemento de uma form do tipo "list box".

<SELECT [NAME="nome"] [SIZE=n] [MULTIPLE]>

NAME
Nome do elemento.
SIZE
Largura do elemento.
MULTIPLE
Indica que o utilizador pode seleccionar mais que uma das opções da lista.
Exemplo(s):

<SELECT NAME="List1">
<OPTION VALUE="Op1"> Opção 1
<OPTION VALUE="Op2"> Opção 2
</SELECT>
<SELECT NAME="List1" MULTIPLE>
<OPTION VALUE="Op1"> Opção 1
<OPTION VALUE="Op2"> Opção 2
<OPTION VALUE="Op3"> Opção 3
<OPTION VALUE="Op4"> Opção 4
</SELECT>

Início
SMALL
Diminui o tamanho do texto.

<SMALL>

Exemplo(s):

<SMALL>Texto em letra pequena</SMALL>

Início
STRIKE
"Strike-through".

<STRIKE>

Exemplo(s):

<STRIKE>Texto aqui</STRIKE>

Início
STRONG
Desenha o texto em "bold" (negrito).

<STRONG>

Exemplo(s):

<STRONG>Texto</STRONG>

Início
STYLE
Define uma "embedded style sheet".

<STYLE [TYPE="tipo"]>

TYPE
"Internet media type" (por exemplo, "text/css").
Exemplo(s):

<STYLE TYPE="text/css">
H1.mine {text-align: center; color: blue}
</STYLE>

Início
SUB
"Subscript".

<SUB>

Exemplo(s):

<SUB>Texto</SUB>

Início
SUP
"Supercript".

<SUP>

Exemplo(s):

<SUP>Texto</SUP>

Início
TABLE
Define uma tabela.

<TABLE [ALIGN="tipo"] [BGCOLOR="cor"] [BACKGROUND="url"] [WIDTH="pixels"] [COLS=n] [BORDER=n] [CELLSPACING=n] [CELLPADDING=n]>

ALIGN
Especifica o alinhamento da tabela.
BGCOLOR
Define a côr de fundo.
BACKGROUND
Define a imagem de fundo da tabela.
WIDTH
Largura.
COLS
Número de colunas da tabela.
BORDER
Tamanho, em pixels, da moldura da tabela.
CELLSPACING
Define o espaço, em pixels, entre os limites das células da tabela.
CELLPADDING
Define o espaço, em pixels, entre os limites das células da tabela e os seus conteúdos.
Exemplo(s):

<TABLE BORDER=0 WIDTH="100%" CELLPADDING=3 CELLSPACING=0>
...
</TABLE>
<TABLE BGCOLOR="#ffffff" WIDTH="300">
...
</TABLE>

Início
TBODY
Define o corpo ("body") da tabela. Este elemento é utilizado para distinguir as linhas da tabela que pertencem ao corpo desta, das que pertencem ao seu cabeçalho ("header") ou rodapé ("footer").

<TBODY>

Exemplo(s):

<TABLE>
<THEAD>
  <TR> header...
</THEAD>
<TFOOT>
  <TR> footer...
</TFOOT>
<TBODY>
  <TR> bloco 1 (linha 1)...
  <TR> bloco 1 (linha 2)...
</TBODY>
<TBODY>
  <TR> bloco 2 (linha 1)...
  <TR> bloco 2 (linha 2)...
</TBODY>
</TABLE>

Início
TD
Cria uma célula na tabela.

<TD [BGCOLOR="cor"] [BACKGROUND="url"] [ALIGN="tipo"] [VALIGN="tipo"] [WIDTH="pixels"] [ROWSPAN=n] [COLSPAN=n]>

BGCOLOR
Cor de fundo.
BACKGROUND
Imagem de fundo.
ALIGN
Alinhamento horizontal do conteúdo.
VALIGN
Alinhamento vertical do conteúdo.
WIDTH
Largura da célula.
ROWSPAN
Número de linhas que a célula ocupa.
COLSPAN
Número de colunas que a célula ocupa.
Exemplo(s):

<TABLE>
<TR>
  <TD WIDTH="100" ALIGN="center" VALIGN="top">
  ...
  </TD>
  <TD ALIGN="center" VALIGN="top" BGCOLOR="blue">
  ...
  </TD>
</TR>
</TABLE>

Início
TEXTAREA
Criar uma área numa form para o utilizador introduzir texto.

<TEXTAREA [NAME="nome"] [ROWS=n] [COLS=n]>

NAME
Nome do elemento.
ROWS
Altura, em caracteres, da área.
COLS
Largura, em caracteres, da área.
Exemplo(s):

<TEXTAREA NAME="texto" ROWS=4 COLS=30></TEXTAREA>

Início
TFOOT
Define o rodapé de uma tabela.

<TFOOT>

Exemplo(s):

<TABLE>
<THEAD>
  <TR> header...
</THEAD>
<TFOOT>
  <TR> footer...
</TFOOT>
<TBODY>
  <TR> bloco 1 (linha 1)...
  <TR> bloco 1 (linha 2)...
</TBODY>
<TBODY>
  <TR> bloco 2 (linha 1)...
  <TR> bloco 2 (linha 2)...
</TBODY>
</TABLE>

Início
TH
Define uma célula que identifica o título de uma linha ou a coluna de uma tabela.

<TH [BGCOLOR="cor"] [BACKGROUND="url"] [ALIGN="tipo"] [VALIGN="tipo"] [WIDTH="pixels"] [ROWSPAN=n] [COLSPAN=n]>

BGCOLOR
Cor de fundo.
BACKGROUND
Imagem de fundo.
ALIGN
Alinhamento horizontal do conteúdo.
VALIGN
Alinhamento vertical do conteúdo.
WIDTH
Largura da célula.
ROWSPAN
Número de linhas que a célula ocupa.
COLSPAN
Número de colunas que a célula ocupa.
Exemplo(s):

<TABLE>
<TR>
  <TH WIDTH="100" ALIGN="center" VALIGN="top">
  ...
  </TH>
  <TH ALIGN="center" VALIGN="top" BGCOLOR="blue">
  ...
  </TH>
</TR>
<TR>
  <TD WIDTH="100" ALIGN="center" VALIGN="top">
  ...
  </TD>
  <TD ALIGN="center" VALIGN="top" BGCOLOR="blue">
  ...
  </TD>
</TR>
</TABLE>

Início
THEAD
Define o cabeçalho de uma tabela.

<THEAD>

Exemplo(s):

<TABLE>
<THEAD>
  <TR> header...
</THEAD>
<TFOOT>
  <TR> footer...
</TFOOT>
<TBODY>
  <TR> bloco 1 (linha 1)...
  <TR> bloco 1 (linha 2)...
</TBODY>
<TBODY>
  <TR> bloco 2 (linha 1)...
  <TR> bloco 2 (linha 2)...
</TBODY>
</TABLE>

Início
TITLE
Define o título de um documento HTML. Válido apenas dentro da tag HEAD.

<TITLE>

Exemplo(s):

<HTML>
<HEAD>
<TITLE>Página do João</TITLE>
...
</HEAD>
<BODY>
...
</BODY>
</HTML>

Início
TR
Cria uma linha na tabela.

<TR [BGCOLOR="cols"] [BACKGROUND="url"] [ALIGN="tipo"] [VALIGN="tipo"]>

BGCOLOR
Côr de fundo.
BACKGROUND
Imagem de fundo.
ALIGN
Alinhamento horizontal do conteúdo.
VALIGN
Alinhamento vertical do conteúdo.
Exemplo(s):

<TABLE>
<TR BGCOLOR="white">
  <TD WIDTH="100" ALIGN="center" VALIGN="top">
  ...
  </TD>
  <TD ALIGN="center" VALIGN="top" BGCOLOR="blue">
  ...
  </TD>
</TR>
</TABLE>

Início
TT
"Teletype". Desenha o texto numa font de largura fixa.

<TT>

Exemplo(s):

<TT>Fixed-width Font</TT>

Início
U
Sublinhado.

<U>

Exemplo(s):

<U>Texto sublinhado</U>

Início
UL
Define uma lista, não ordenada, de elementos.

<UL [TYPE="tipo"]>

TYPE
Tipo de "bullet" a utilizar. Os valores possíveis são DISC, SQUARE e CIRCLE.
Exemplo(s):

<UL>
<LI> Item 1
<LI> Item 2
<LI> Item 3
</UL>

Início
VAR
Denota que o texto corresponde a uma variável. O texto é desenhado numa font de largura fixa.

<VAR>

Exemplo(s):

<VAR>Texto Aqui</VAR>

Início

<<< tema anterior                         próximo tema >>>

