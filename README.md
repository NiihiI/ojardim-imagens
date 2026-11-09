# Imagens do Jardim

Imagens das salas do servidor de TeamSpeak **O Jardim**. Cada sala aponta para um arquivo daqui pelo endereço `raw.githubusercontent.com`.

## Como são feitas

No TeamSpeak 6, cada sala tem uma imagem só, e ela aparece em dois lugares:

- **Na lista de canais**, só a faixa do meio, com uns 30 px de altura.
- **No painel da sala**, a imagem inteira, esticada para caber na caixa.

Por isso cada sala tem aqui um SVG com duas imagens dentro e uma regra de estilo que escolhe qual delas aparece, conforme o formato em que o SVG é desenhado:

- **No painel**, o SVG sai achatado, e aparece a pintura da sala, inteira e nítida.
- **Na lista**, o SVG mantém o formato alto, e aparece a faixa da pintura do grupo. O canal e as subsalas dividem uma pintura, cortada de modo que a lista continue de uma linha para a seguinte.

As pinturas saem dos arquivos originais do Wikimedia Commons e são reduzidas uma vez só, para o tamanho do painel (até 1400 px de largura). Imagem maior que isso sai borrada no TeamSpeak.

Os arquivos são gerados por script e trocados a cada nova geração. O nome de cada um leva um código do conteúdo, para o TeamSpeak não mostrar uma versão antiga guardada.

## Origem e licença

As pinturas estão em domínio público no Wikimedia Commons. A obra de cada imagem, com o link para a página dela, está em [CREDITOS.md](CREDITOS.md).
