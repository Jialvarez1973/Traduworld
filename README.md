# 🌎 TraduWorld

**Tradutor de voz em tempo real para TeamSpeak e Discord** · **Real-time voice translator for TeamSpeak and Discord** · **Traductor de voz en tiempo real para TeamSpeak y Discord**

<p align="center">
  <a href="https://github.com/jialvarez1973/traduworld/releases/latest/download/Traduworld-Setup.exe"><b>⬇️ Baixar · Download · Descargar — Traduworld-Setup.exe (Windows 10/11)</b></a>
</p>

<p align="center">
  <a href="#pt">🇧🇷 Português</a> &nbsp;·&nbsp; <a href="#en">🇺🇸 English</a> &nbsp;·&nbsp; <a href="#es">🇪🇸 Español</a>
</p>

---

<a id="pt"></a>
## 🇧🇷 Português

### O que é

O **TraduWorld** é um programa gratuito para Windows que **traduz a conversa por voz em tempo real** no TeamSpeak e no Discord. Você fala no seu idioma e os outros ouvem no idioma deles. Eles falam no idioma deles e você ouve no seu.

Ele nasceu nas corridas de simulador (rFactor 2, iRacing, Assetto Corsa e outros), onde pilotos de vários países dividem a mesma sala de voz. Funciona em qualquer conversa por TeamSpeak ou Discord: jogos, ligas, treinos, reuniões e amizades.

### Para que serve

- **Correr e conversar com pilotos de outros países** sem saber o idioma deles.
- **Entender o que a equipe, o diretor de prova ou o spotter estão falando**, mesmo em outra língua.
- **Ser entendido por todos**: a sua voz chega traduzida no TeamSpeak ou no Discord.

### O que ele faz

**🎧 Você ouve**
- Os outros falam em um dos **23 idiomas** do programa, e o TraduWorld **descobre sozinho qual é** pela voz de quem está falando (você não precisa escolher).
- Você ouve a tradução no fone, no seu idioma, com voz de homem ou de mulher.
- Legendas na tela, por cima do jogo, com tamanho, cor e posição à sua escolha.
- Você pode continuar ouvindo as vozes originais junto com a tradução.

**🎙️ Você fala**
- Você segura o **botão que preferir**: do volante, de um controle, uma tecla, um botão do mouse ou do Stream Deck.
- Fala no seu idioma e solta o botão. Os outros ouvem a frase traduzida no TeamSpeak ou no Discord.
- Só é traduzido o que você fala com o botão apertado. Conversas com o engenheiro virtual ou palavras soltas no meio da curva não vão para a sala.
- **Minha própria voz:** a tradução pode sair com a sua própria voz.
- Opção de falar o seu nome antes da frase ("Jesus diz: ...").

### Destaques

- **23 idiomas**, entre eles português, inglês, espanhol, francês, italiano, alemão, holandês, polonês, russo, japonês, chinês, coreano e árabe.
- **Assistente de configuração** na primeira vez: microfone, fone, TeamSpeak ou Discord e o botão para falar.
- **Ajusta o TeamSpeak e o Discord para você**, sempre mostrando o **antes e o depois**. Nada muda sem o seu clique, e tudo pode ser **desfeito**.
- **Avisa quando algo pode atrapalhar o jogo**, como os atalhos do Windows que travam o teclado no meio da corrida, e oferece corrigir com um botão.
- **Atualização automática** com um clique, sem reinstalar. Dá para voltar para uma versão anterior.
- **Aproveita a placa de vídeo NVIDIA**, quando existe, para ser mais rápido. Sem ela, usa o processador.
- **Programa em português, inglês e espanhol.**
- **Relatório para o suporte** com um clique, se algo der errado. A sua chave de IA nunca vai junto.

### Como funciona

1. O TraduWorld **escuta** a voz (a sua, pelo microfone, ou a dos outros, pelo TeamSpeak/Discord).
2. **Reconhece** o que foi dito, com inteligência artificial que roda **no seu próprio computador**.
3. **Traduz** a frase: pela IA da Groq (opcional e gratuita), pelo Google ou, sem internet, por um tradutor que roda no seu PC.
4. **Fala** a tradução: no seu fone, ou para a sala, por um cabo de áudio virtual (VB-CABLE).

### O que você precisa

- **Windows 10 ou 11 de 64 bits.**
- **Microfone e fone de ouvido** (headset).
- **Internet** para baixar e para a melhor qualidade de tradução e de voz.
- Placa de vídeo **NVIDIA** é opcional: deixa tudo mais rápido.
- O instalador confere se o seu computador é compatível **antes de instalar qualquer coisa**.

### Como instalar

1. Baixe o **[Traduworld-Setup.exe](https://github.com/jialvarez1973/traduworld/releases/latest/download/Traduworld-Setup.exe)**.
2. Abra o arquivo e siga as telas (se o Windows mostrar um aviso, veja [É seguro?](#pt-seguro)). A instalação leva de 15 a 40 minutos, porque baixa os modelos de inteligência artificial.
3. Antes de começar, o instalador cria um **ponto de restauração do Windows**. Assim dá para voltar o computador exatamente como estava.
4. Abra o **TraduWorld** pela Área de Trabalho. O assistente guia o resto.

<a id="pt-seguro"></a>

### É seguro? (aviso do Windows na instalação)

- O TraduWorld **não contém vírus** e **não rouba senhas**. Ele não lê as suas senhas, não acessa o seu navegador e não mexe nos seus arquivos pessoais.
- Ele só mexe no que precisa para traduzir: o som do computador e as configurações de som do TeamSpeak e do Discord, sempre mostrando o antes e o depois e só com a sua autorização.
- **Ao instalar, o Windows pode mostrar um aviso** como *"O Windows protegeu o computador"* ou *"Editor desconhecido"*. Isso acontece porque o instalador **não tem assinatura digital paga** (um certificado comprado da Microsoft ou de outras empresas). Como o TraduWorld é **gratuito**, não faz sentido gastar dinheiro com esse certificado.
- Para continuar a instalação, clique em **"Mais informações"** e depois em **"Executar assim mesmo"**.
- Na instalação, o Windows também pede permissão (**"Sim"**) para instalar as peças necessárias: o cabo de áudio virtual VB-CABLE, o Python e o Visual C++ da Microsoft.
- Se quiser conferir por conta própria, envie o arquivo `Traduworld-Setup.exe` para **[virustotal.com](https://www.virustotal.com)**, que analisa com dezenas de antivírus ao mesmo tempo.

### Privacidade

- O reconhecimento da voz é feito **no seu computador**.
- Para traduzir e gerar as vozes, o texto das frases pode passar pela internet (Groq, Google e vozes da Microsoft).
- O cadastro pede **nome e e-mail**, só para o suporte saber de quem é um relatório e para o seu nome poder ser falado antes da tradução.
- Os relatórios para o suporte só são enviados quando **você** clica para enviar.

### Gratuito

O TraduWorld é **gratuito**. Se ele ajudar você, há um botão de doação opcional dentro do programa.

---

<a id="en"></a>
## 🇺🇸 English

### What it is

**TraduWorld** is a free Windows program that **translates voice conversations in real time** on TeamSpeak and Discord. You speak your language and the others hear theirs. They speak their language and you hear yours.

It was born in sim racing (rFactor 2, iRacing, Assetto Corsa and others), where drivers from many countries share the same voice channel. It works in any TeamSpeak or Discord conversation: games, leagues, practice sessions, meetings and friends.

### What it is for

- **Racing and chatting with drivers from other countries** without knowing their language.
- **Understanding what your team, the race director or the spotter is saying**, even in another language.
- **Being understood by everyone**: your voice reaches TeamSpeak or Discord already translated.

### What it does

**🎧 You listen**
- Others speak in one of the program's **23 languages**, and TraduWorld **detects which one by itself** from the speaker's voice (you don't need to choose).
- You hear the translation in your headset, in your language, with a male or female voice.
- On-screen subtitles over the game, with the size, color and position you like.
- You can keep hearing the original voices together with the translation.

**🎙️ You speak**
- Hold **the button you prefer**: on the wheel, a controller, a keyboard key, a mouse button or a Stream Deck.
- Speak in your language and release the button. The others hear the translated sentence on TeamSpeak or Discord.
- Only what you say while holding the button is translated. Talking to the virtual race engineer or a stray word in the middle of a corner does not reach the channel.
- **My own voice:** the translation can come out in your own voice.
- Option to say your name before the sentence ("Jesus says: ...").

### Highlights

- **23 languages**, including Portuguese, English, Spanish, French, Italian, German, Dutch, Polish, Russian, Japanese, Chinese, Korean and Arabic.
- **Setup assistant** the first time: microphone, headset, TeamSpeak or Discord, and the push-to-talk button.
- **Adjusts TeamSpeak and Discord for you**, always showing the **before and after**. Nothing changes without your click, and everything can be **undone**.
- **Warns you when something may get in the way of the game**, such as the Windows shortcuts that freeze the keyboard in the middle of a race, and offers to fix it with one button.
- **Automatic updates** with one click, no reinstall. You can go back to a previous version.
- **Uses an NVIDIA graphics card**, when there is one, to be faster. Without it, it uses the processor.
- **Program available in Portuguese, English and Spanish.**
- **Support report** with one click if something goes wrong. Your AI key is never included.

### How it works

1. TraduWorld **listens** to the voice (yours, from the microphone, or the others', from TeamSpeak/Discord).
2. It **recognizes** what was said, with artificial intelligence running **on your own computer**.
3. It **translates** the sentence: with Groq's AI (optional and free), with Google or, without internet, with a translator that runs on your PC.
4. It **speaks** the translation: in your headset, or to the channel through a virtual audio cable (VB-CABLE).

### What you need

- **Windows 10 or 11, 64-bit.**
- **Microphone and headphones** (headset).
- **Internet** to download, and for the best translation and voice quality.
- An **NVIDIA** graphics card is optional: it makes everything faster.
- The installer checks whether your computer is compatible **before installing anything**.

### How to install

1. Download **[Traduworld-Setup.exe](https://github.com/jialvarez1973/traduworld/releases/latest/download/Traduworld-Setup.exe)**.
2. Open the file and follow the screens (if Windows shows a warning, see [Is it safe?](#en-safe)). Installation takes 15 to 40 minutes, because it downloads the artificial intelligence models.
3. Before starting, the installer creates a **Windows restore point**, so you can put your computer back exactly as it was.
4. Open **TraduWorld** from the Desktop. The assistant guides you through the rest.

<a id="en-safe"></a>

### Is it safe? (Windows warning during installation)

- TraduWorld **contains no viruses** and **does not steal passwords**. It does not read your passwords, does not access your browser and does not touch your personal files.
- It only changes what it needs to translate: the computer's sound and the sound settings of TeamSpeak and Discord, always showing the before and after and only with your permission.
- **When installing, Windows may show a warning** such as *"Windows protected your PC"* or *"Unknown publisher"*. This happens because the installer **does not have a paid digital signature** (a certificate bought from Microsoft or other companies). Since TraduWorld is **free**, spending money on that certificate makes no sense.
- To continue the installation, click **"More info"** and then **"Run anyway"**.
- During installation, Windows also asks for permission (**"Yes"**) to install the parts it needs: the VB-CABLE virtual audio cable, Python and Microsoft Visual C++.
- If you want to check it yourself, upload the `Traduworld-Setup.exe` file to **[virustotal.com](https://www.virustotal.com)**, which scans it with dozens of antivirus programs at once.

### Privacy

- Voice recognition happens **on your computer**.
- To translate and create the voices, the text of the sentences may go through the internet (Groq, Google and Microsoft voices).
- Registration asks for **name and e-mail**, only so support knows whose report it is and so your name can be spoken before the translation.
- Support reports are only sent when **you** click to send them.

### Free

TraduWorld is **free**. If it helps you, there is an optional donation button inside the program.

---

<a id="es"></a>
## 🇪🇸 Español

### Qué es

**TraduWorld** es un programa gratuito para Windows que **traduce las conversaciones de voz en tiempo real** en TeamSpeak y Discord. Tú hablas en tu idioma y los demás escuchan en el suyo. Ellos hablan en su idioma y tú escuchas en el tuyo.

Nació en las carreras de simulador (rFactor 2, iRacing, Assetto Corsa y otros), donde pilotos de muchos países comparten el mismo canal de voz. Funciona en cualquier conversación por TeamSpeak o Discord: juegos, ligas, entrenamientos, reuniones y amigos.

### Para qué sirve

- **Correr y conversar con pilotos de otros países** sin saber su idioma.
- **Entender lo que dicen tu equipo, el director de carrera o el spotter**, aunque sea en otro idioma.
- **Que todos te entiendan**: tu voz llega traducida a TeamSpeak o Discord.

### Qué hace

**🎧 Tú escuchas**
- Los demás hablan en uno de los **23 idiomas** del programa, y TraduWorld **descubre solo cuál es** por la voz de quien habla (no tienes que elegirlo).
- Escuchas la traducción en el auricular, en tu idioma, con voz de hombre o de mujer.
- Subtítulos en pantalla, encima del juego, con el tamaño, color y posición que prefieras.
- Puedes seguir escuchando las voces originales junto con la traducción.

**🎙️ Tú hablas**
- Mantienes pulsado **el botón que prefieras**: del volante, de un mando, una tecla, un botón del ratón o del Stream Deck.
- Hablas en tu idioma y sueltas el botón. Los demás escuchan la frase traducida en TeamSpeak o Discord.
- Solo se traduce lo que dices con el botón pulsado. Hablar con el ingeniero virtual o una palabra suelta en medio de una curva no llegan al canal.
- **Mi propia voz:** la traducción puede salir con tu propia voz.
- Opción de decir tu nombre antes de la frase ("Jesus dice: ...").

### Destacados

- **23 idiomas**, entre ellos portugués, inglés, español, francés, italiano, alemán, neerlandés, polaco, ruso, japonés, chino, coreano y árabe.
- **Asistente de configuración** la primera vez: micrófono, auricular, TeamSpeak o Discord y el botón para hablar.
- **Ajusta TeamSpeak y Discord por ti**, siempre mostrando el **antes y el después**. Nada cambia sin tu clic, y todo se puede **deshacer**.
- **Avisa cuando algo puede estorbar en el juego**, como los atajos de Windows que bloquean el teclado en medio de la carrera, y ofrece corregirlo con un botón.
- **Actualización automática** con un clic, sin reinstalar. Puedes volver a una versión anterior.
- **Aprovecha la tarjeta de video NVIDIA**, si la hay, para ser más rápido. Sin ella, usa el procesador.
- **Programa en portugués, inglés y español.**
- **Informe para el soporte** con un clic, si algo sale mal. Tu clave de IA nunca se incluye.

### Cómo funciona

1. TraduWorld **escucha** la voz (la tuya, por el micrófono, o la de los demás, por TeamSpeak/Discord).
2. **Reconoce** lo que se dijo, con inteligencia artificial que funciona **en tu propia computadora**.
3. **Traduce** la frase: con la IA de Groq (opcional y gratuita), con Google o, sin internet, con un traductor que funciona en tu PC.
4. **Dice** la traducción: en tu auricular, o al canal, por un cable de audio virtual (VB-CABLE).

### Qué necesitas

- **Windows 10 u 11 de 64 bits.**
- **Micrófono y auriculares** (headset).
- **Internet** para descargar y para la mejor calidad de traducción y de voz.
- Una tarjeta de video **NVIDIA** es opcional: hace todo más rápido.
- El instalador comprueba si tu computadora es compatible **antes de instalar nada**.

### Cómo instalar

1. Descarga **[Traduworld-Setup.exe](https://github.com/jialvarez1973/traduworld/releases/latest/download/Traduworld-Setup.exe)**.
2. Abre el archivo y sigue las pantallas (si Windows muestra un aviso, mira [¿Es seguro?](#es-seguro)). La instalación tarda de 15 a 40 minutos, porque descarga los modelos de inteligencia artificial.
3. Antes de empezar, el instalador crea un **punto de restauración de Windows**, para poder dejar la computadora exactamente como estaba.
4. Abre **TraduWorld** desde el Escritorio. El asistente te guía en el resto.

<a id="es-seguro"></a>

### ¿Es seguro? (aviso de Windows al instalar)

- TraduWorld **no contiene virus** y **no roba contraseñas**. No lee tus contraseñas, no accede a tu navegador y no toca tus archivos personales.
- Solo cambia lo que necesita para traducir: el sonido de la computadora y la configuración de sonido de TeamSpeak y Discord, siempre mostrando el antes y el después y solo con tu permiso.
- **Al instalar, Windows puede mostrar un aviso** como *"Windows protegió su PC"* o *"Editor desconocido"*. Esto pasa porque el instalador **no tiene firma digital de pago** (un certificado comprado a Microsoft o a otras empresas). Como TraduWorld es **gratuito**, no tiene sentido gastar dinero en ese certificado.
- Para seguir con la instalación, haz clic en **"Más información"** y después en **"Ejecutar de todas formas"**.
- Durante la instalación, Windows también pide permiso (**"Sí"**) para instalar las piezas necesarias: el cable de audio virtual VB-CABLE, Python y Visual C++ de Microsoft.
- Si quieres comprobarlo por tu cuenta, sube el archivo `Traduworld-Setup.exe` a **[virustotal.com](https://www.virustotal.com)**, que lo analiza con decenas de antivirus a la vez.

### Privacidad

- El reconocimiento de voz se hace **en tu computadora**.
- Para traducir y crear las voces, el texto de las frases puede pasar por internet (Groq, Google y voces de Microsoft).
- El registro pide **nombre y correo**, solo para que el soporte sepa de quién es un informe y para que tu nombre pueda decirse antes de la traducción.
- Los informes para el soporte solo se envían cuando **tú** haces clic para enviarlos.

### Gratuito

TraduWorld es **gratuito**. Si te ayuda, hay un botón de donación opcional dentro del programa.

---

<p align="center">
  Feito por <b>Jesus Iglesias</b> · Baseado em projetos de código aberto (licença MIT): LiveLingo e realtime-voice-translator.<br>
  Made by <b>Jesus Iglesias</b> · Based on open-source projects (MIT license): LiveLingo and realtime-voice-translator.<br>
  Hecho por <b>Jesus Iglesias</b> · Basado en proyectos de código abierto (licencia MIT): LiveLingo y realtime-voice-translator.
</p>
