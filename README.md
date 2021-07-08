# jandirabot
Bot baseada na I.ris BOT (https://github.com/Ki.llovSky/i.ris/)

CONTATO: 556199811135

PRÉ REQUISITOS PARA INSTALAÇÃO(INSTALE TODOS CORRETAMENTE PARA A BOT FUNCIONAR):

Dois números no WhatsApp, um para o dono e outro para a BOT.
- [NodeJS](https://nodejs.org) - Recomendo a LTS.
- [Git](https://git-scm.com) - Para as Unix-Tools - Cuidado.
- [FFmpeg](https://ffmpeg.org) - Para conversões.
- [Libwebp](https://developers.google.com/speed/webp/download) - Ajuda no de cima e outras coisas.
- Para um tutorial de instalação do FFmpeg no Windows 7/8, veja [WikiHow](https://pt.wikihow.com/Instalar-o-FFmpeg-no-Windows), no caso de Windows 10 veja a [SoundArtifacts](https://soundartifacts.com/pt/how-to/186-how-to-install-ffmpeg-on-windows-10-amp-add-ffmpeg-to-windows-path.html).
- Para instalar o LibWebP siga os mesmos passos, mas mudando o nome da pasta para LibWebP em vez de FFmpeg.



INSTALAÇÃO DA BOT NO NPM (GIT BASH):

cd jandira
npm i 
npm start 

CONFIGURAR LOOP (ABRIR OUTRA JANELA NO GIT BASH):

npm install pm2

npm i -g pm2
 
pm2 start index.js

pm2 monit




EDITE as API's encontradas em:

- [Linguagem](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#2)
- [Dono](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#3)
- [DDI](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#4)
- [Prefix](https://github.comsmartywolf/jandirabot/blob/main/lib/config/Bot/config.json#5)
- [API 1 - API-Flash](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#6)
- [API 2 - RemoveBG](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#7)
- [API 3 - WallHaven](https://github.com/smartywolf/jandirabot/main/lib/config/Bot/config.json#8)
- [API 4 - Deep-AI](https://github.com/smartywolf/jandirabot/config/Bot/config.json#9)
- [Limite de Grupos](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#10)
- [Limite de Membros](https://github.com/smartywolf/jandirabot/main/lib/config/Bot/config.json#11)
- [Sticker-Autor](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#12)
- [Sticker-Pack](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#13)
- [User-Agent](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#14)
- [Tempo de Jogo](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#15)
- [Anti-Flood](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#16)
- [Max-Size](https://github.com/smartywolf/jandirabot/main/lib/config/Bot/config.json#17)
- [Win-Time](https://github.com/smartywolf/jandirabot/blob/main/lib/config/Bot/config.json#18)
- Elas são referentes aos sites [RemoveBG](https://www.remove.bg/pt-br), [API-Flash](https://apiflash.com), [WallHaven](https://wallhaven.cc/settings/account) & [Deep-AI](https://deepai.org).
- A DDI e Linguagem são necessárias apenas se você for de fora do Brasil, as linguagens disponiveis são "en" de inglês, "pt" de português e "es" de espanhol e afetam todos os diálogos e o akinator.
- Você pode inserir dois ou mais números de dono, se não quiser apenas deixe o segundo como está, o tempo de jogo deve ser inserido em MINUTOS, ele limitará o tempo para cada jogatina, o Anti-Flood deverá ser em SEGUNDOS e limita os comandos e a User-Agent é opcional, Max-Size é para Downloads, coloque entre 1 a 64 (Sugiro 16) e a Win-Time é o tempo de ganho de XP para cada mensagem.

