<h4 align="center">
<img src="https://i.pinimg.com/originals/dc/1a/1a/dc1a1a4287f57e4a80ea5ecfd912ee96.png" width="250px" /><br><br>
 <h1 align='center'>Arquivos estáticos no Github + CDN livre</h1>
 <h3 align='center'>Hospedar arquivos estáticos CSS e JS no github. Aprenda à hospedar!</h3>
</h4><br<<br>

## Passos iniciais 
1° Criar um repositório no GitHub <br>
2° Colocar o código do arquivo estático no GitHub

<h4 align="center">
<p>Crie um novo repositório no GitHub, é dentro do repositório que vai ser armazenados os arquivos estáticos criados,
deixe como público.</p><br><br>
<img src="https://i.imgur.com/ykUE85D.png" width="500px" /><br><br>
<p>Para colocar o código é preciso copiar e colar o código em um arquivo criado ou fazer upload dos arquivos.
Antes de criar o primeiro arquivo, crie o readme, pode deixar ele vazio mesmo.</p>
<img src="https://i.imgur.com/BbZteG2.png" width="500px" /><br><br>
<p>Depois dê um nome para o arquivo (ex: script.js) e cole o conteúdo do arquivo e selecione para salvar..</p>
<img src="https://i.imgur.com/HMqZDXN.png" width="500px" /><br><br>
</h4>
<h3 align='center'>
<img src="https://www.jsdelivr.com/img/logo-horizontal.svg" width="250px" /><br><br>
<b>Agora chegou o momento de falar do https://www.jsdelivr.com/</b>
</h3>
<h4 align='center'>
<p>O site jsdelivr.com é uma CDN nativa e oferece excelente performance em todos os pontos do mundo, possuindo dezenas de servidores espalhados em diversos países.

O jsdelivr transformas projetos NPM, github e wordpress em CDN, portanto qualquer arquivo JS e CSS nesses projetos pode ser convertido para utilizar a estrutura de CDN deles.

Como o foco aqui é o github, vou mostrar como transformar um arquivo CSS ou JS em um link disponível para utilizar em qualquer projeto como um site.

Vou dar o exemplo usando esse javascript de um projeto de fotos que não fornece uma CDN, seria necessário baixar os aquivos e usar no seu servidor.
</p>
<b>https://cdn.jsdelivr.net/gh/user/repo@version/file</b><br><br>

## O link começa com https://cdn.jsdelivr.net/gh
que é o URL da CDN + GH que significa que vai buscar um projeto no github.<br>

Depois vem o <b>USER</b>, que é o usuário que mantém o pacote no github, no caso se for usar um código seu, seria seu usuário.<br>

Depois vem <b>REPO</b>, que é o repositório.

Em seguida é preciso colocar @version, que seria o branche do repositório, existem projetos que organizam as versões em branches, se for usar seu repositório, geralmente o padrão é <b>master</b>, mas basta pegar no URL.

Para finalizar, tem que informar o <b>FILE</b>, ou arquivo que vai ser disponibilizado via CDN, lembrando que ele pode estar na raiz, então basta colocar o nome, ou coloque as pastas até chegar no arquivo.

Pronto, o link final e: 
https://cdn.jsdelivr.net/gh/devBKLucas/arquivos-estaticos-example@master/script.js

## Para mais informações, utilize o site deles com exemplos:
https://www.jsdelivr.com/features


