# Módulo 6 — Benchmarking Concorrencial

Antes de desenhar qualquer tela, é fundamental realizar um benchmarking para mapear o mercado, entender onde os competidores falham e identificar métodos que garantem boas performances para adaptá-los à sua realidade.

**No nosso caso, essa análise precisa ir além do óbvio.** Como o nosso modelo de negócio tem o objetivo de transformar o tédio das rotinas físicas em dinâmicas sociais altamente engajadoras, o nosso "mercado" não é apenas o de saúde e fitness, mas sim o mercado da **retenção da atenção**.

Se queremos garantir uma Experiência do Cliente (CX) disruptiva, precisamos entender tanto os players tradicionais do esporte quanto as plataformas que dominam o entretenimento, a monetização e a cultura de desafios virtuais hoje. Só assim conseguiremos extrair as melhores mecânicas de engajamento para aplicar no nosso produto, criando uma barreira competitiva sólida e blindando nosso produto contra soluções genéricas, além também de nos fornecer uma visão melhor de onde e como estamos posicionados no mercado.

Para estruturar essa visão, dividimos nossa análise sob dois prismas fundamentais que são concorrentes diretos e indiretos:

## Análise de Concorrência e Referências

### Concorrente Direto vs. Concorrente Indireto

Concorrente não deve ser definido apenas pelo formato do produto, mas pela necessidade que ele resolve.

- **Concorrente Direto:** resolve o mesmo problema, para o mesmo público, com uma solução semelhante. Exemplo: outros aplicativos de treino com rankings e desafios.
- **Concorrente Indireto:** resolve a mesma necessidade principal por um caminho diferente, ou disputa a mesma audiência e o mesmo dinheiro que sustentam o seu modelo de negócio, mesmo sem competir pela necessidade central do seu produto.

No nosso caso, a necessidade central continua sendo treinar com mais constância. Twitch e os jogos competitivos (LoL/CS) não competem por essa necessidade, ninguém deixa de treinar por causa deles, mas entram como Indireto pelo segundo critério: nosso mecanismo de engajamento usa transmissão ao vivo, disputa em tempo real e matchmaking, e é exatamente essa audiência, de quem gosta de assistir e competir, que essas plataformas já dominam e monetizam. Competimos com elas por atenção e por dinheiro, mesmo sem competir por treino.

> Conhecer o próprio produto não é a mesma coisa que conhecer o mercado ao redor dele. O Strava compete com a gente pelo produto, treino e constância. O Twitch compete pela forma como monetizamos e utilizamos a atenção em lives para engajamento e retenção; mesmo vendendo algo completamente diferente, disputamos pelo mesmo dinheiro.

A tabela abaixo mapeia os principais concorrentes diretos e indiretos para o nosso mercado:

| Concorrente | Diferenciais | Porte | O que faz mal ou não faz? | O que pode ser imitado? | O que fazer melhor? |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Twitch** | Transmissão ao vivo e conteúdos diversos | Grande | Foco limitado ao público gamer e entretenimento passivo, sem ferramentas de métricas de saúde ou integração com mapas. | Sistema de monetização de criadores e arquitetura de baixa latência para interações em tempo real. | Trazer as transmissões ao vivo para o ambiente mobile focado estritamente em atletas e corredores de rua de forma integrada. |
| **Jogos Competitivos (LoL/CS)** | Experiência de jogo intensa e competitiva | Grande | Interação física limitada e comunidades por vezes tóxicas | Elementos de gamificação e rankings | Trazer a dinâmica competitiva para a realidade física do esporte |
| **Strava** | Registro de treinos, desafios e rankings | Grande | A interação entre amigos é estritamente assíncrona; não possui suporte para acompanhar treinos ou corridas ao vivo por vídeo. | Segmentação de rotas e criação de comunidades em torno de clubes de corrida. | Adicionar o fator de transmissão e torcida em tempo real (lives) dentro de grupos fechados. |
| **Apps de Musculação** | Planejamentos personalizados de treinos | Grande | Ausência de socialização e dinâmicas de entretenimento | Estrutura de fichas e treinos segmentados | Integrar elementos de diversão e comunidade aos treinos |
| **TikTok** | Conteúdo curto, viral e alto engajamento | Grande | Consumo de entretenimento puramente passivo e focado em algoritmos globais, sem ferramentas para engajamento em atividades físicas práticas locais. | Formato dinâmico de vídeos curtos, desafios virais e as interações rápidas de chat em lives. | Integrar o formato de lives interativas com métricas de performance reais (velocidade, batimento cardíaco) na tela do streaming. |
| **Plataformas de Desafios Locais** | Estruturação de desafios em formato de rede social | Pequeno | Apoio escasso à criação de conteúdo e validações frágeis | A disposição base de transformar metas em desafios sociais | Foco total na experiência do cliente (CX) e validação segura de desafios |

---

## Plano de Ação Baseado no Benchmarking

A partir da análise competitiva, estabelecemos a seguinte ordem de execução estratégica:

1. **O Problema Central:** Adultos perderam o contexto social e competitivo que tinham no treino em grupo, e mesmo os concorrentes que já tentam resolver isso, como o Strava, ficam limitados à interação assíncrona dentro do app. Isso significa que o usuário continua treinando sozinho a não ser que busque meios fora do aplicativo, mesmo cercado de rankings e comentários, porque nunca existe ninguém ali, ao vivo, para competir ou torcer no momento em que o esforço está acontecendo.

2. **Mecânicas de Modelagem:** Do LoL e do CS, absorver o mecanismo de ranking que sustenta a constância pelo medo de perder posição, além do sistema de matchmaking que conecta desconhecidos para uma partida justa. Da Twitch, absorver a dinâmica de transmissão em tempo real de baixa latência que sustenta o consumo ao vivo.

3. **Diferencial Inegociável:** Permitir que o usuário transmita sua corrida de rua ou treino em tempo real com dados de performance na tela, fazendo com que seu círculo de amigos assista, comente e torça ao vivo. Incluir também um sistema de matchmaking que permita a pessoas em locais diferentes se desafiarem ao vivo no mesmo tipo de treino, mesmo sem se conhecerem previamente. Essa mecânica cria uma comunidade ativa que atua tanto como atleta quanto como espectadora, **blindando** o ecossistema contra a concorrência de apps genéricos de treino.

4. **Estipular métricas de controle:** Acompanhar o volume de desafios criados, as taxas de retenção periódica e os contratos firmados com parceiros comerciais.

5. **Alinhar com a equipe:** Comunicar os caminhos de diferenciação e os indicadores que comprovarão o sucesso da estratégia.

---

## Exercício Prático: Mapeando o seu Mercado

Agora é a sua vez. Pegue o problema que você validou nos Módulos 2 e 3 e a solução que começou a desenhar no Lean Canvas (Módulo 5). Você vai analisar quem já está no campo de jogo e como seu projeto vai se diferenciar.

>Importante: O Lean Canvas representa as hipóteses atuais do seu negócio. Se o benchmarking revelar novas informações sobre clientes, concorrentes, canais ou diferenciais, revise o canvas antes de continuar. Atualizar hipóteses ao longo do processo é um sinal de aprendizado, não de erro.

### Passo 1: Monte sua Tabela de Benchmarking
Crie um arquivo chamado `exercicio-modulo-06.md` no seu repositório de acompanhamento. Escolha pelo menos **3 concorrentes ou referências** (diretos ou indiretos) e preencha a estrutura abaixo:

| Concorrente / Referência | Principais Diferenciais | Porte (Grande/Médio/Pequeno) | O que ele faz mal ou simplesmente não atende? | O que pode ser imitado/adaptado? | O que você vai fazer significativamente melhor? |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1.** | | | | | |
| **2.** | | | | | |
| **3.** | | | | | |

> **Dica de Ouro:** Não limite sua análise apenas a concorrentes idênticos. Olhe para mercados paralelos. Se você está criando um app de finanças para devs, seu concorrente indireto pode ser uma planilha ou o duolingo, tudo depende da forma como você enxerga seu produto e o mercado ao redor

---

### Passo 2: Defina seu Plano de Ação Comercial

Com a tabela preenchida, escreva um plano de ação de 5 pontos para o seu projeto, respondendo de forma direta:

1. **O Problema Central Isolado:** Qual é a falha exata dos concorrentes que você resolve?
2. **Referências de Modelagem:** Quais dinâmicas de outras plataformas ou mercados você vai absorver?
3. **Diferencial Inegociável:** Por que o cliente escolheria você e não a solução atual dele? Como você vai **blindar** o seu negócio contra a concorrência?
4. **Métricas de Controle:** Quais são os 2 ou 3 indicadores de mercado (ex: taxa de cadastro, recorrência, ações criadas) que vão provar que seu diferencial está funcionando?
5. **Próximo Passo Prático:** Qual é a primeira funcionalidade ou processo simples que você precisa estruturar para validar esse diferencial?

---

[Próximo módulo ➡️](./07-construindo-o-primeiro-mvp.md)

