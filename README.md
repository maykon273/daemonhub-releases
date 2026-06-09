# DaemonHub Releases

<p align="center">
  <strong>Chat overlay leve, direto e feito para streamers que querem acompanhar tudo em uma janela so.</strong>
</p>

<p align="center">
  <a href="https://github.com/maykon273/daemonhub-releases/releases/latest">
    <img alt="Latest release" src="https://img.shields.io/github/v/release/maykon273/daemonhub-releases?style=for-the-badge&label=latest">
  </a>
  <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  <img alt="Free" src="https://img.shields.io/badge/Free-Download-00d4aa?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/maykon273/daemonhub-releases/releases/latest">
    <strong>Baixar a versao mais recente</strong>
  </a>
</p>

---

## Sobre

O **DaemonHub** e um overlay de chat para lives que junta mensagens de plataformas como YouTube e Twitch em uma interface limpa, leve e personalizavel.

Ele foi pensado para quem faz live e precisa acompanhar o chat sem abrir varias janelas, sem pesar o PC e sem atrapalhar o jogo ou a transmissao.

## Principais recursos

- Chat overlay para acompanhar mensagens durante a live.
- Suporte a YouTube, Shorts Live e Twitch.
- Janela sempre no topo.
- Modo click-through para clicar no jogo sem interferencia.
- Temas visualmente diferentes: transparente, claro, escuro, compacto e bubble.
- Ajuste de transparencia, fonte, tamanho e posicao.
- Reconexao automatica quando o chat cai.
- Suporte a emojis e emotes.
- Configuracoes salvas automaticamente.
- Distribuicao em `.exe`, sem precisar instalar Python.

## Download

A versao mais recente fica sempre na pagina de releases:

**https://github.com/maykon273/daemonhub-releases/releases/latest**

O arquivo segue este padrao:

```text
DaemonHub-VERSAO.exe
```

Exemplo:

```text
DaemonHub-1.5.0.exe
```

## Como instalar

1. Acesse a pagina de releases.
2. Baixe o arquivo `DaemonHub-VERSAO.exe`.
3. Abra o executavel.
4. Configure suas plataformas e links.
5. Posicione o overlay onde preferir.

## Aviso do Windows SmartScreen

O Windows pode mostrar um aviso de seguranca ao abrir o DaemonHub, principalmente porque o app ainda nao possui uma assinatura digital paga.

Isso pode acontecer com aplicativos novos ou independentes baixados da internet. Para sua seguranca, baixe o DaemonHub apenas pelos links oficiais deste repositorio.

## Verificacao do arquivo

Cada versao publicada possui um hash SHA256 proprio. Esse hash muda sempre que o `.exe` muda, entao ele deve ser conferido de acordo com a versao baixada.

SHA256 da versao `1.5.0`:

```text
6EB637F6C8FE9AF7FAEE642114BDAB3DA1D9D7ECA731BDFCCF2B3995F3346A27  DaemonHub-1.5.0.exe
```

Para conferir no Windows, abra o PowerShell na pasta onde baixou o arquivo e rode:

```powershell
Get-FileHash -Algorithm SHA256 .\DaemonHub-1.5.0.exe
```

O valor mostrado deve ser igual ao hash publicado na release.

## Links aceitos no DaemonHub

- `https://www.youtube.com/watch?v=ID`
- `https://www.youtube.com/live/ID`
- `https://www.youtube.com/shorts/ID`
- `https://www.youtube.com/live_chat?is_popout=1&v=ID`
- `https://www.twitch.tv/canal`
- ID direto do video, quando aplicavel.

## Dica para jogos

Para o overlay aparecer corretamente sobre o jogo, prefira rodar o jogo em:

- Janela sem bordas.
- Modo janela.

Tela cheia exclusiva pode cobrir overlays externos em alguns jogos. Jogos com anticheat mais rigoroso tambem podem bloquear overlays.

## Atualizacoes

As novas versoes do DaemonHub sao publicadas aqui na pagina de releases.

Sempre que houver uma atualizacao, baixe o novo `.exe` pela versao mais recente e substitua a versao antiga.

---

<p align="center">
  <strong>DaemonHub</strong><br>
  simples, leve e pronto para live.
</p>
