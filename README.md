# Obunga Music

Aplicativo de música para Windows x64 e Android 7 ou superior, com biblioteca local e catálogos selecionáveis YouTube Music e Spotify.

## Baixar a versão 1.4.0

- [Windows — EXE gráfico](https://github.com/abacate77/obunga-music/releases/download/v1.4.0/ObungaMusic-1.4.0.exe)
- [Android — APK](https://github.com/abacate77/obunga-music/releases/download/v1.4.0/ObungaMusic-1.4.0.apk)
- [Código completo e arquivos de compilação](https://github.com/abacate77/obunga-music/releases/download/v1.4.0/ObungaMusic-1.4.0-Codigo.zip)
- [Notas da versão](https://github.com/abacate77/obunga-music/releases/tag/v1.4.0)
- [SHA-256 dos arquivos](https://github.com/abacate77/obunga-music/releases/download/v1.4.0/SHA256SUMS.txt)

O código completo está no arquivo **ObungaMusic-1.4.0-Codigo.zip** da release. O arquivo automático “Source code” do GitHub corresponde apenas aos arquivos deste repositório de distribuição.

No Windows, abra o EXE sem CMD. .NET, Python, Java e LibVLC acompanham o pacote; o [WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/) precisa estar instalado. No Android, instale o APK por cima da distribuição anterior com o mesmo certificado para preservar a biblioteca e as sessões.

## Interface

Navegação móvel por arrasto, player expandido com cabeçalho compacto, fila expansível e reorganizável, letras sincronizadas quando há timestamps, gestos e animações configuráveis. Em Configurações → Reprodução → Animações da interface, escolha Seguir o sistema, Ativadas ou Movimento reduzido.

O login Google acontece em uma janela interna. A importação JSON/CSV de playlists funciona sem login e sem Premium. Reproduzir áudio Spotify pelo SDK oficial exige conta Premium e autorização em cada aparelho; o acesso à biblioteca pela API segue as regras do Spotify.

## Atualizações

O aplicativo consulta o [manifesto assinado](https://github.com/abacate77/obunga-music/releases/latest/download/update.json), avisa quando existe uma versão mais recente e verifica assinatura, tamanho e SHA-256 antes de oferecer a instalação. O Android mantém a confirmação do instalador do sistema. Clientes anteriores ao atualizador precisam desta instalação manual inicial.

## Validação da 1.4.0

40 verificações offline, 22 verificações físicas Android e teste Jam Windows–Android com duas músicas, pausa, retomada, avanço e edição da fila. Pacotes públicos conferidos por tamanho e SHA-256. Essa cobertura não equivale a testar todos os dispositivos, conexões ou faixas dos provedores.

## Licenças

Código Obunga sob GPL-3.0, com LICENSE e THIRD-PARTY.md no arquivo de fontes e na distribuição. Chaves privadas de assinatura, perfis e sessões pessoais não fazem parte dos arquivos publicados.
