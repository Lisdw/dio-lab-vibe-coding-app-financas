💸 App de Organização de Finanças Pessoais com IA — Minha Entrega
Desafio DIO · Vibe Coding · App de Finanças Pessoais com Inteligência Artificial
📋 Índice
Resumo do App
Prompt Final — PRD
Interações com a IA
Reflexão sobre o Processo
🎯 Resumo do App
FinançasIA é um aplicativo de organização financeira pessoal que funciona por meio de conversas naturais com um agente de IA — o Finn, um consultor financeiro virtual.
Em vez de preencher planilhas ou categorizar gastos manualmente, o usuário simplesmente conversa: "Gastei R$ 45 no mercado hoje" ou "Quero economizar para uma viagem em 6 meses" — e o Finn entende, registra, categoriza e sugere ações.
Principais funcionalidades do MVP:
#
Funcionalidade
Descrição
1
💬 Registro por chat
O usuário informa gastos em linguagem natural, sem formulários
2
🏷️ Categorização automática
A IA classifica as transações (alimentação, transporte, lazer etc.)
3
🎯 Metas financeiras
Definição e acompanhamento de objetivos (ex: "guardar R$ 500/mês")
4
💡 Agente Financeiro (Finn)
Dicas personalizadas de economia baseadas no perfil de gastos
5
📊 Relatórios simples
Visão mensal dos gastos com gráficos e resumo em linguagem acessível
Público-alvo:
Pessoas entre 18 e 35 anos que querem começar a organizar as finanças de forma prática, sem experiência prévia com planilhas ou apps complexos.
🧠 Prompt Final — PRD
Este é o PRD (Product Requirements Document) utilizado como briefing para a IA:
Código
🖥️ Interações com a IA
Interação 1 — Refinamento do PRD com Copilot
Prompt enviado ao Copilot:
Código
Resultado:
O Copilot sugeriu:
Adicionar o nome do agente de IA para personalizar a experiência
Incluir exemplos de frases reais que o usuário usaria no chat
Especificar o tom de voz do agente ("empático, motivador, sem jargões")
Detalhar as métricas de validação do MVP
📸 [Print da conversa com o Copilot — refino do PRD]
Interação 2 — Definição do Agente Finn no Lovable
Prompt enviado ao Lovable:
Código
Resposta gerada pela IA (resumo):
Finn — Seu Consultor Financeiro Pessoal
Personalidade: Amigável, paciente, motivador. Trata o dinheiro como ferramenta, não como problema. Celebra pequenas vitórias e nunca julga os gastos do usuário.
Tom: Informal, direto, com emojis ocasionais. Sem termos técnicos.
Exemplos de respostas:
Boas-vindas: "Oi! Sou o Finn 👋 Vou te ajudar a cuidar do seu dinheiro sem estresse. Me conta: qual é o seu maior desafio financeiro hoje?"
Registro de gasto: "Anotei! R$ 32 em alimentação 🍽️ Você já usou 68% do seu orçamento de alimentação este mês."
Meta atingida: "ARRASOU! 🎉 Você bateu sua meta de economia de R$ 300 esse mês! Quer aumentar o desafio para o próximo?"
Alerta de orçamento: "Ei, olha só 👀 Seus gastos com lazer já passaram do planejado. Quer ver onde dá pra ajustar?"
Dica de economia: "Notei que você gasta muito em delivery às quartas. Que tal cozinhar uma vez por semana e economizar uns R$ 80? 🥘"
📸 [Print da conversa com o Lovable — definição do Agente Finn]
Interação 3 — Fluxo de Telas do MVP
Prompt enviado ao Lovable:
Código
Fluxo de telas gerado pela IA:
Código
📸 [Print da conversa com o Lovable — fluxo de telas]
Interação 4 — Plano de MVP
Prompt enviado ao Lovable:
Código
Plano de MVP gerado pela IA:
Funcionalidades prioritárias:
Funcionalidade
Justificativa
Chat de registro de gastos
É o diferencial central — sem isso, o app é igual aos outros
Categorização automática
Elimina o trabalho manual que faz as pessoas desistirem
Agente Finn com dicas
Cria vínculo emocional e engajamento recorrente
Metas financeiras
Dá propósito ao uso — o usuário volta porque tem um objetivo
Relatório mensal simples
Fecha o ciclo: o usuário vê resultado e continua usando
Recursos técnicos mínimos:
LLM (modelo de linguagem) para o chat do Finn e categorização
Banco de dados simples para armazenar transações e metas
Interface mobile-first com tela de chat
Sistema de notificações push para alertas do Finn
Métricas de validação:
70% dos usuários registram ao menos 1 gasto na primeira semana
50% criam ao menos 1 meta no primeiro mês
Taxa de retenção de 40% após 30 dias de uso
NPS (satisfação) acima de 7 após 1 mês
📸 [Print da conversa com o Lovable — plano de MVP]
💭 Reflexão sobre o Processo
✅ O que funcionou bem
A clareza do PRD fez toda a diferença. Quando o briefing estava bem estruturado — com contexto, problema, público, funcionalidades e tom de voz — as respostas da IA foram muito mais úteis e precisas. A IA não é adivinha: ela entrega na proporção do que recebe.
Iterar com o Copilot antes do Lovable foi uma estratégia inteligente. Usar uma ferramenta para refinar o prompt antes de levá-lo à outra poupou tokens e gerou resultados mais consistentes.
Nomear o agente ("Finn") transformou uma funcionalidade técnica em uma experiência. A IA conseguiu manter coerência de personalidade quando teve um nome e um perfil claro para referenciar.
❌ O que não funcionou como esperado
O limite de interações do Lovable (5/dia) exige planejamento. Desperdiçar uma interação com um prompt vago é frustrante — aprendi que vale a pena escrever e revisar antes de enviar.
Pedir tudo de uma vez gerou respostas genéricas. Dividir em interações menores e mais focadas ("agora só o agente", "agora só o fluxo de telas") produziu resultados muito melhores.
📚 O que aprendi sobre conversar com IAs
A maior lição foi entender que IA é parceira, não mágica. Ela amplifica sua intenção — se a intenção é vaga, o resultado é vago. Se a intenção é clara, o resultado é surpreendente.
Aprendi também que o Vibe Coding não é sobre código: é sobre desenvolver a habilidade de transformar uma ideia em linguagem que a IA entende. Isso é uma competência nova e cada vez mais valiosa no mercado.
Por fim: iterar é o processo. A primeira resposta raramente é a melhor. Ajustar, pedir variações e questionar a IA faz parte do método — e é onde o aprendizado real acontece.
🔗 Repositório Base
digitalinnovationone/dio-lab-vibe-coding-app-financas
Desafio concluído como parte da trilha de IA na plataforma DIO.me 🚀
