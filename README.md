# Obunga Music

Aplicativo de música para Windows x64 e Android 7 ou superior, com biblioteca local e catálogos selecionáveis YouTube, YouTube Music e Spotify.

## Baixar a versão 1.5.2

- [Windows — EXE gráfico](https://github.com/abacate77/obunga-music/releases/download/v1.5.2/ObungaMusic-1.5.2.exe)
- [Android — APK](https://github.com/abacate77/obunga-music/releases/download/v1.5.2/ObungaMusic-1.5.2.apk)
- [Código completo e arquivos de compilação](https://github.com/abacate77/obunga-music/releases/download/v1.5.2/ObungaMusic-1.5.2-Codigo.zip)
- [Notas da versão](https://github.com/abacate77/obunga-music/releases/tag/v1.5.2)
- [SHA-256 dos arquivos](https://github.com/abacate77/obunga-music/releases/download/v1.5.2/SHA256SUMS.txt)

O código completo está no arquivo **ObungaMusic-1.5.2-Codigo.zip** da release. O arquivo automático “Source code” do GitHub corresponde apenas aos arquivos deste repositório de distribuição.

No Windows, abra o EXE sem CMD. .NET, Python, Java e LibVLC acompanham o pacote; o [WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/) precisa estar instalado. No Android, instale o APK por cima da distribuição anterior com o mesmo certificado para preservar a biblioteca e as sessões.

## Animações e gestos na 1.5.2

O player e a fila acompanham o arrasto. As transições substituem a animação anterior ao reabrir rapidamente, e o próximo toque intencional funciona logo depois do gesto. Controles e cabeçalhos deixam de selecionar texto ou mostrar o destaque de toque do navegador; foco de teclado, edição de texto e movimento reduzido continuam disponíveis. A biblioteca tem transições ao trocar abas, ordenar e alternar lista/grade.

## Sua biblioteca

A biblioteca abre em **Playlists**, com capas, nomes e quantidade de músicas. As abas **Playlists, Músicas, Álbuns e Artistas** separam as coleções das faixas soltas. Busca, ordenação, lista/grade e criação/importação de playlists ficam no cabeçalho. As playlists e faixas existentes são preservadas.

## Recursos

YouTube geral como terceiro catálogo de áudio, com busca, importação por link, título, capa, artista e biblioteca. Letras sincronizadas com timestamps reais quando disponíveis, correspondência da gravação e ajuste por faixa.

O botão **Baixar playlist** coloca as faixas disponíveis em uma fila com progresso, retomada e nova tentativa das falhas. Arquivos existentes não são baixados novamente; as faixas baixadas podem tocar pela própria playlist offline. Mantenha o aplicativo aberto para avançar a fila. Ao interromper, o arquivo atual termina antes da parada.

Temas escuro, claro e AMOLED, cinco cores de destaque, aparência integrada ao sistema, mais gestos, animações configuráveis e atalhos de teclado. Veja os controles em Configurações.

O download atende às fontes YouTube e YouTube Music disponíveis ao mecanismo do aplicativo. Faixas locais já estão disponíveis; faixas do SDK Spotify não são convertidas automaticamente. O login Google acontece em uma janela interna. A importação JSON/CSV de playlists funciona sem login e sem Premium. Reproduzir áudio Spotify pelo SDK oficial exige Premium e autorização em cada aparelho.

## Atualizações

O aplicativo consulta o [manifesto assinado](https://github.com/abacate77/obunga-music/releases/latest/download/update.json), avisa quando existe uma versão mais recente e verifica assinatura, tamanho e SHA-256 antes de oferecer a instalação. O Android mantém a confirmação do instalador do sistema. Clientes anteriores ao atualizador precisam desta instalação manual inicial.

## Validação da 1.5.2

Doze suítes JavaScript, cinco testes Python e 14 verificações de gestos no WebView2 nativo aprovadas, incluindo cancelamento, reabertura rápida, arrasto contínuo e redimensionamento. Biblioteca conferida em 320, 390 e 1280 pixels. Conteúdo dos pacotes, assinatura Android, manifesto assinado e downloads públicos conferidos.

O APK desta versão ainda não foi testado em aparelho físico. Medições no Windows não representam FPS garantido no Android; os testes não cobrem todos os dispositivos ou catálogos.

## Licenças

Código Obunga sob GPL-3.0, com LICENSE e THIRD-PARTY.md no arquivo de fontes e na distribuição. Chaves privadas de assinatura, perfis e sessões pessoais não fazem parte dos arquivos publicados.
