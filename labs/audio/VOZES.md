# Arquivos de áudio — vozes oficiais dos jogos

Coloque os arquivos MP3 aqui com exatamente estes nomes.
O site detecta automaticamente e usa o arquivo real no lugar do TTS.

O site aceita `.mp3`, `.m4a` (GarageBand/iOS) ou `.ogg` — use qualquer um.

| Arquivo               | Fala                  | Jogo           |
|-----------------------|-----------------------|----------------|
| mario-yahoo.mp3/.m4a  | "Yahoo!"              | Super Mario 64 |
| mario-wahoo.mp3/.m4a  | "Wahoo!"              | Super Mario 64 |
| mario-letsago.mp3/.m4a| "Let's-a go!"         | Super Mario    |
| mario-mamamia.mp3/.m4a| "Mama mia!"           | Super Mario    |
| mario-herewego.mp3/.m4a| "Here we go!"        | Super Mario    |
| mk-fight.mp3/.m4a     | "Fight!"              | Mortal Kombat  |
| mk-finish-him.mp3/.m4a| "Finish him!"         | Mortal Kombat  |
| mk-flawless.mp3/.m4a  | "Flawless victory!"   | Mortal Kombat  |
| mk-fatality.mp3/.m4a  | "Fatality!"           | Mortal Kombat  |
| sf-hadouken.mp3/.m4a  | "Hadouken!"           | Street Fighter |
| sf-shoryuken.mp3/.m4a | "Shoryuken!"          | Street Fighter |
| sf-fight.mp3/.m4a     | "Fight!"              | Street Fighter |

## No iPhone (GarageBand)

1. Grave a tela com microfone ativado enquanto o YouTube toca
2. Abra GarageBand → novo projeto → Gravador de Áudio
3. Adicione o vídeo como arquivo de áudio na faixa
4. Corte só o trecho da fala
5. Compartilhar → Música → salva como .m4a
6. Suba o arquivo para esta pasta com o nome correto

Após adicionar os arquivos, faça commit e push para o repositório:

```
git add labs/audio/*.mp3
git commit -m "add: vozes oficiais dos personagens"
git push origin main
```
