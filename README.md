# ffmpeg

`07/09/2024`

meu objetivo é estudar como funciona o ffmpeg, tudo que eu preciso saber para fazer um ffmpeg

FUNCAMENTOS DE PROCESSAMENTO DE AUDIO E VIDEO - isso inclui codecs como por exemplo H.264 VP9 AAC, Conteinerer de mídia como MP4 MKV AVI e como que encapsulam fluxos de vaudio e video algo chamado como transcoding que é pra pra converter entre formato de audio e vídeo

BIBLIOTECAS DE MANIPULAÇÃO DE MÍDIA  - como o Libavcoded e o Libavformat - pelo que o gpt falou o ffmpeg é construido em cima dessas lib então é um bom objeto de estudo tambem, GStreamer é outra lib pra manipular midia em tempo real

MANIPUTAÇÃO DE FLUXOS DE VIDEO - Frame by frame processing é como extrair e processar frames de videos como o ffmpeg que trabalha com imagens em sequencia. tem o filtros de video que o ffmpeg supoerta tambem como por exemplo redimensionamento corte e por ai vai

PROTOCOLOS DE STREAMING segundo o gpt tem alguns protocolo pra transmissão ao vivo e sob demanda fundamentais para criar ferramentas de streaming por exemplo RTMP HRL MPEG-DASH assim como Socket pra passar via rede (estudei um pouco sobre socket de barkley e tambem sobre webSocket então talvez eu possa ignorar isso)

ESTRUTURA DE ARQUIVOS E METODOS DE CONVERSAO - Aqui tem Arquitetura de arquivos de mida que é pra entender a estrtura interna dos aqruivos de video e audio como o cabeçalhos metadados e flxuos de bits como funcionam tem tbm essencialmente a cli dele que tem que estudar pra ver como funciona pra tambem implementar se quiser
SISTEMAS DE ARQUIVOS E E/S es é entrada e saida enfim manipulação de arquivos binários é para saber ler e escrever arquivops de midia manipulando bytes diretamente legal acho que isso eu sei fazer +- em C# sei ler e pegar o byte atual que colocar dentro de um buffer modificar o buffer tbm é algo possivel mas ainda n sei manipular objetivamente. buffering e IO de fluxos aqui a gente tem o basicamente oq eu acabei de falar mas te m o  io de fluxo talvez seja interessante olhar... n sei

SINCRONIZAÇÃO DE AUDIO E VIDEO - aqui fala do timestamp e algo chamado pts/dts já n sei oq é, tambem falou da licena e da do C/c++ que o ffmpeg usa mas n sei se é algo que eu vou querer ver não

agora que falei de tudo que o gpt me falou pra agora é interessante focar em alguns pontos que ele me apresentou que seriam os funcamentos de proessamento de video que tambem se categoriza como processamento de  imagem e disso eu lembro que tem um puta de um livro deixa eu ve .... interessante que acabei de sver aqui tem um 
[Grokkin Streaming System](https://www.amazon.com.br/Grokking-Streaming-Systems-Real-Time-Processing/dp/1617297305/ref=sr_1_2?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&sr=8-2&ufe=app_do%3Aamzn1.fos.db68964d-7c0e-4bb2-a95c-e5cb9e32eb12). interessante eu to curtindo bastante oq o meu livrinho de grokkin dsa tem agora esse ai eu tenho certeza que vem coisa boa, mas quem sabe se eu vou pegar pra ler, esse pessoal do grokking tem bastante coisa, olha só falando em bastante coisa enbfim, vamos voltar achei isso aqui pra processamento de video [livro](https://www.amazon.com.br/Multidimensional-Signal-Image-Processing-Coding/dp/0123814200/ref=sr_1_4?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&sr=8-4&ufe=app_do%3Aamzn1.fos.a492fd4a-f54d-4e8d-8c31-35e0a04ce61e). não sei parece que tem uma base matematica muito pesada... pelo que o pessoal ta falando não é pra iniciantes, agora pra processamento de imagem tem esse [livro aqui, PROCESSAMENTO DIGITAL DE IMAGENS](https://www.amazon.com.br/Processamento-digital-imagens-Rafael-Gonzalez/dp/8576054019/ref=sr_1_1?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&sr=8-1&ufe=app_do%3Aamzn1.fos.db68964d-7c0e-4bb2-a95c-e5cb9e32eb12), lembro que tinha graduação pra esse tipo de coisa de tão complexo que é sera que a facens tem??? tem não.
enfim falando mas um poco sobre oq tanto que eu tenho que estudar pra entender como funciona é sobre CODEX principalemente e tambem do Libavcodec e Libavformat

Algo interessante tambem de estudar é como que funciona pro windows mostrar video, mas é algo mais avançado que sai um pouco do escopo mas acabei achando um processamnete de imagem aqui no [microsft learn ](https://learn.microsoft.com/pt-br/windows-hardware/drivers/image/image-processing). mas vou deixa pra dps
