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

