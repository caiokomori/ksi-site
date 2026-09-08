# Continuidade do projeto KSI

## Objetivo imediato

Concluir a primeira versão do site institucional rapidamente. O proprietário
pretende fazer uma revisão mais ampla futuramente. Preservar o design aprovado
e evitar rodadas desnecessárias de escolhas ou alterações fora do pedido.

## Empresa e posicionamento

KSI Serviços Industriais: manutenção, limpeza, recuperação e pintura de
reservatórios/caixas d'água e silos industriais. Os dois pilares devem ter o
mesmo peso comercial e visual. Não inventar datas, regiões atendidas, números,
clientes, certificações, garantias ou qualificações da equipe.

## Direção aprovada

- Industrial cinematográfica, editorial e técnica, apoiada por fotos reais.
- Títulos Barlow Condensed; corpo e navegação Inter.
- Azul muito escuro, branco e cinza. Vermelho apenas no logo oficial.
- Sem fotos de banco, imagens geradas, frases publicitárias enfeitadas, excesso
  de cards, gradientes ou animações.
- Hero aprovado com fotografia de silos e headline direta.
- Barra inferior do Hero teve vários ajustes e foi aceita provisoriamente.
  Não alterar sua posição sem solicitação.
- Textos curtos, claros e naturais. Comunicação profissional, sem brincadeiras.

## Estado atual: versão 20

1. Hero: “Manutenção de reservatórios e silos industriais.”
2. Áreas de atuação: dois painéis fotográficos, reservatórios e silos.
3. Condição da estrutura: registros reais de corrosão e deterioração.
4. Processo: fotografias de execução e resultado, com inspeção, planejamento,
   execução e entrega.
5. Serviços: índice técnico de seis serviços com troca de fotografia por
   mouse, foco do teclado ou clique/toque.
6. Sobre a KSI: texto aprovado provisoriamente, em composição curta.

Uma seção adicional de Obras reais foi descartada pelo usuário por redundância.
Não criá-la agora. As fotos das seções existentes já mostram o trabalho.

## Últimos ajustes aprovados

O usuário achou os títulos muito grandes e os textos de apoio pequenos e
isolados à direita. Nas seções 02, 03, 04 e 05, o layout agora coloca o texto
abaixo do título, reduz o título, aumenta o texto e aproxima as fotos.
A versão 13 corrigiu a seção 03, que havia ficado fora da versão 12.
Conferir todas as seções envolvidas quando uma mudança for solicitada em grupo.

Textos de apoio revisados:

- Áreas de atuação: “Realizamos limpeza, recuperação e pintura em reservatórios
  e silos, com serviços internos e externos conforme a necessidade de cada estrutura.”
- Processo: “Antes de começar, avaliamos a estrutura e definimos o serviço.
  Depois, organizamos os materiais, os equipamentos e as etapas de execução.”
- Serviços: “Os serviços podem atender uma necessidade pontual ou envolver a
  recuperação de toda a estrutura. Veja abaixo as principais atividades realizadas pela KSI.”
- Condição da estrutura conserva o texto: “A condição da estrutura determina o
  tratamento, a preparação e o método de execução.”

## Sobre a KSI — texto aceito por enquanto

Somos a KSI, uma empresa de manutenção de reservatórios e silos industriais.
Realizamos limpeza, recuperação e pintura, tanto na parte interna quanto na
externa das estruturas.

Atendemos desde serviços de conservação até a recuperação de áreas danificadas
pelo desgaste e pela corrosão. Em cada trabalho, avaliamos o que precisa ser
feito e organizamos a execução conforme as condições do local.

## Novidades da versão 14

- Navegação corrigida: removido o link para `#obras`, seção já descartada.
- O link “Conhecer nossa atuação” do Hero agora aponta para a seção de atuação.
- A seção de serviços detalhados recebeu o identificador `#escopo`.
- Criada a seção 07 / Contato e o rodapé.
- WhatsApp e e-mail ficam visualmente prontos, mas desativados enquanto os dados
  oficiais não forem fornecidos. A configuração está no início do bloco de
  contato em `dist/script.js`.

## O que falta

1. Receber WhatsApp com DDD e e-mail comercial oficiais. Foram solicitados,
   mas ainda não fornecidos. Não inventar esses dados.
2. Inserir esses dois dados em `contactConfig` dentro de `dist/script.js`.
3. Conferir links, uso no celular e legibilidade antes da entrega final.
4. Revisar posteriormente as afirmações técnicas e serviços com a empresa.
5. Definir domínio e hospedagem só depois. Devem ficar no nome da empresa ou
   proprietário. O usuário pediu para não gastar nem publicar nesta etapa.

## Limites da validação existente

Foram feitas verificações de sintaxe e geração do HTML, e o usuário avaliou
visualmente versões no seu navegador. Não considerar isso um teste completo
em vários dispositivos. O índice de serviços no celular usa imagem sticky;
conferir se a imagem permanece visível ao selecionar os últimos serviços.

## Mensagem para começar outra conversa

“Estou continuando o site da KSI. Leia CONTEXTO-PARA-CONTINUAR.md e os arquivos
de dist antes de editar. A versão atual é a 15. Preserve o design aprovado,
use apenas as fotos reais e não crie outra seção de obras. Contato e rodapé já foram incluídos na v14; quero revisar o restante futuramente. Não publique o
site sem meu pedido. Os dados comerciais ainda precisam ser informados.”


## Novidades da versão 18

- Os dois painéis de “Áreas de atuação” agora funcionam como carrosséis independentes.
- Reservatórios usa as três fotografias novas enviadas pelo usuário.
- Silos industriais usa as três fotografias novas enviadas pelo usuário.
- Cada carrossel troca automaticamente a imagem a cada 5 segundos.
- Foram adicionadas apenas setas discretas para navegação manual, sem bolinhas, conforme a Opção A escolhida pelo usuário.
- No celular também é possível deslizar horizontalmente para trocar a foto.
- Ao usar uma seta ou gesto manual, a contagem do autoplay reinicia.
- A última foto horizontal destacada pelo usuário continua separada desta alteração e pode ser usada posteriormente no Hero, se confirmado.


## Ajustes da v19
- Hero principal alterado para a imagem horizontal de reservatório destacada pelo usuário.
- Setas dos carrosséis redesenhadas em CSS, sem caracteres de fonte, para manter alinhamento preciso.
- Hover dos cards preserva zoom sutil, agora aplicado no contêiner das imagens para evitar tremor durante transições.
- Carrosséis de Reservatórios e Silos mantêm 3 fotos, autoplay e navegação manual.


## Alterações da versão 18
- A seção “Condição da estrutura” ganhou comparação manual Antes ↔ Depois nos três blocos.
- Mantidos os títulos existentes: Corrosão interna, Pontos críticos e Revestimento comprometido.
- Sem autoplay nessa comparação; a troca ocorre apenas ao clicar em “Antes ↔ Depois”.
- As seis novas fotos foram otimizadas e incorporadas ao projeto.


## Alterações da v19
- Nova seção **Orçamento** com formulário para o cliente informar nome, empresa, contato, estrutura, serviço, local e necessidade.
- O botão do cabeçalho e o CTA principal agora levam ao formulário de orçamento.
- O envio está preparado para WhatsApp ou e-mail assim que os dados comerciais forem configurados em `contactConfig`.
- Ajustado o enquadramento das imagens de **Pontos críticos / escotilha** no desktop.


## Ajustes da v20
- Reduzida de forma perceptível a altura dos cards de Reservatórios e Silos no desktop (aprox. 20–25%).
- Reduzida a altura do mosaico de Antes ↔ Depois e das fotos de Processo no desktop.
- Reduzida a altura da mídia fixa da seção de Serviços.
- No celular, as áreas fotográficas também foram compactadas de forma moderada, preservando as correções de títulos e setas da v19.
- Mantido `object-fit: cover` e os enquadramentos existentes; nenhum texto ou conteúdo foi removido.
