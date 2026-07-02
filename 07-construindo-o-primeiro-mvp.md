# Módulo 7 — Construindo o Primeiro MVP

Com o benchmark em mãos, chegamos ao ponto de execução. A tentação natural de um desenvolvedor é abrir o editor de código e listar funcionalidades: sistemas de login complexos, perfis detalhados com upload de imagem e microsserviços de notificação. 

No entanto, nenhuma dessas ferramentas testa a hipótese mais importante primeiro: **os usuários voltam a se exercitar com mais constância quando existe um componente social e competitivo?** Se essa premissa for falsa, nenhuma arquitetura limpa ou interface bonita salvará o produto.

---

## Pensando no Menor Experimento Possível

Antes de construir qualquer código, desenhe uma validação manual, simples e trabalhosa. O objetivo do MVP (*Minimum Viable Product*) não é ser escalável, é ser um ambiente de aprendizado rápido.

No caso do nosso aplicativo de treinos, o MVP inicial não precisa de um app na Google Play ou App Store. Ele pode ser apenas:
1. Um grupo fechado no **WhatsApp** com 15 pessoas do segmento-alvo.
2. Uma planilha do **Google Sheets** compartilhada, atualizada manualmente por você ao final do dia com os treinos que a galera mandou no grupo, gerando um ranking semanal.

Se esse experimento manual, que levou 20 minutos para ser configurado, gerar engajamento, conversas no grupo e disputa, a hipótese de negócio está validada. Só então faz sentido automatizar o processo criando o produto de software real.

---

> **Perspectiva de Mercado: E se meu foco for B2B ou Consultoria?**
>
> Se a sua ideia de negócio está mapeada para resolver dores de Pequenas e Médias Empresas (PMEs), a lógica do MVP permanece idêntica. 
> 
> Imagine que você identificou que líderes de operação perdem horas na triagem manual de relatórios operacionais. Grandes *fintechs* resolvem isso com automações preditivas e dashboards complexos de IA. Em vez de desenvolver um software caro e demorado agora, você desenha um MVP manual: cria formulários gratuitos (Google Forms) integrados a uma planilha para consolidar as informações em um único painel que você mesmo alimenta. 
> 
> Isso resolve a dor de tempo do cliente imediatamente, valida se os gerentes realmente consumiriam esses dados diariamente e **blinda** o caixa da sua startup contra o desperdício de recursos de desenvolvimento.

---

## Exercício Prático: O Experimento Sem Código

Chegou a hora de definir o MVP do seu projeto. Você vai desenhar um teste que possa ser executado sem abrir o editor de código.

Crie o arquivo `exercicio-modulo-07.md` no seu repositório de acompanhamento e estruture os seguintes pontos:

### Passo 1: Declare sua Hipótese Central
Escreva a afirmação principal do seu negócio em uma única frase, utilizando obrigatoriamente o formato abaixo:

> **"Acreditamos que** `[Segmento de Clientes]` **vai** `[Comportamento Esperado]` **quando** `[Condição/Solução Manual]`**.**

*   *Exemplo:* "Acreditamos que **adultos que treinam sozinhos** vão **fazer 3 ou mais treinos por semana** quando **estiverem competindo em um ranking manual via WhatsApp com seus amigos**."

### Passo 2: Desenhe o Experimento Manual
Descreva, em até 5 linhas, como você vai testar essa hipótese usando ferramentas gratuitas e processos manuais (WhatsApp, Planilhas, Notion, Formulários, Instagram, etc.). **Lembre-se: proibidão codar aqui.**

### Passo 3: Defina a Métrica de Sucesso (Critérium de Parada)
Qual é o número mínimo que prova que as pessoas realmente se importam com a sua solução?
*   *Exemplo:* Pelo menos 60% das pessoas do grupo atualizarem seus treinos por duas semanas seguidas.

---

[Próximo módulo ➡️](./08-pitch-perfeito.md)
