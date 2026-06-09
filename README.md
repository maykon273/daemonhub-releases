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

No Windows, pode aparecer um aviso de seguranca por ser um executavel baixado da internet. Se voce baixou pela pagina oficial de releases deste repositorio, confirme a execucao para continuar.

## Padrao para publicar novas versoes

Para o site detectar o download automaticamente, mantenha sempre o mesmo padrao:

Tag do release:

```text
v1.5.0
```

Nome do arquivo no release:

```text
DaemonHub-1.5.0.exe
```

Quando lancar uma nova versao, por exemplo `1.6.0`, publique:

```text
Tag: v1.6.0
Arquivo: DaemonHub-1.6.0.exe
```

Depois atualize apenas o `version.json` do site:

```json
{
  "version": "1.6.0"
}
```

O site vai montar automaticamente o link:

```text
https://github.com/maykon273/daemonhub-releases/releases/download/v1.6.0/DaemonHub-1.6.0.exe
```

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

## Projeto

Este repositorio e usado para distribuir as builds publicas do DaemonHub.

Repositorio principal e site podem usar este repositorio como fonte dos downloads oficiais.

---

<p align="center">
  <strong>DaemonHub</strong><br>
  simples, leve e pronto para live.
</p>
