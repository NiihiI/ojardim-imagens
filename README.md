# Imagens do Jardim

Imagens das salas do servidor de TeamSpeak **O Jardim**. Cada sala aponta para um arquivo daqui pelo endereço `raw.githubusercontent.com`.

## Como são feitas

No TeamSpeak 6, cada sala tem uma imagem só, e ela aparece em dois lugares:

- **Na lista de canais**, só a faixa do meio, com uns 30 px de altura.
- **No painel da sala**, a imagem inteira, esticada para caber na caixa.

Por isso há dois tipos de imagem em `banners/`:

- **Pedaço da pintura do grupo.** O canal e as subsalas dividem uma pintura, cortada de modo que a lista continue de uma linha para a seguinte.
- **Pintura própria da sala.** A imagem é bem alta, com a pintura da sala esticada na vertical de propósito. O painel encolhe a imagem e a pintura volta às proporções certas. A faixa do meio leva o pedaço da pintura do grupo, para a lista continuar; no painel, ela vira um fio fino.

Tudo sai das pinturas originais do Wikimedia Commons, na maior resolução disponível, reduzidas uma vez só para o tamanho do painel. Os arquivos são gerados por script e trocados a cada nova geração; o nome de cada um leva um código do conteúdo, para o TeamSpeak não mostrar uma versão antiga guardada.

## Origem e licença

As pinturas estão em domínio público no Wikimedia Commons. A obra de cada imagem, com o link para a página dela, está em [CREDITOS.md](CREDITOS.md).
