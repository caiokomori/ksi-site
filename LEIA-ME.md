# KSI — site em desenvolvimento, versão 20

## Abrir o site

Extraia o ZIP inteiro antes de abrir os arquivos. Para visualizar, abra
`KSI-Home-v20.html` no navegador. Esse arquivo contém o CSS, JavaScript e as
imagens utilizadas. As fontes Barlow Condensed e Inter vêm do Google Fonts:
é necessário acesso à internet para carregar essas fontes; sem ele, o navegador
utiliza as fontes alternativas definidas no CSS.

## Continuar o desenvolvimento

- `dist/index.html`: conteúdo e estrutura da Home.
- `dist/styles.css`: aparência e adaptação para celular.
- `dist/script.js`: menu e troca das imagens dos serviços.
- `dist/assets/`: logotipo e fotografias utilizadas, otimizadas para o site.
- `scripts/build-single-file.mjs`: gera a versão de arquivo único.
- `CONTEXTO-PARA-CONTINUAR.md`: decisões e pendências para a próxima conversa.

Edite os arquivos de `dist/` e depois gere novamente o HTML único. Com uma
versão moderna do Node.js (22 ou superior), execute na pasta do projeto:

```sh
node scripts/build-single-file.mjs
```

O script atualmente grava `KSI-Home-v20.html`. Atualize o nome de saída e o
título no script se quiser numerar a próxima versão. Também é possível abrir
`dist/index.html`, mantendo sua pasta e todos os arquivos juntos.

O pacote é uma cópia do estado atual da versão 20.
Não contém histórico de conversas, versões antigas nem todas as fotografias
originais enviadas: inclui as imagens efetivamente utilizadas no site.
Não há domínio, hospedagem, backend ou envio de formulário configurados.

