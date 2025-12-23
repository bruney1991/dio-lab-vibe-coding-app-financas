 # 📊 App de Organização de Finanças Pessoais — Sua Grana Amiga

Este projeto foi desenvolvido como um Desafio de Projeto da DIO, no contexto de Vibe Coding, utilizando as ferramentas Lovable e Copilot Web. O objetivo é desenvolver um aplicativo de organização financeira pessoal que facilite o controle de receitas, despesas e metas por meio de interações em linguagem natural, oferecendo uma experiência simples, acessível e intuitiva para usuários iniciantes em controle financeiro.


## 📌 1. Contexto

O aplicativo busca simplificar o controle financeiro pessoal por meio de
interações em linguagem natural.

Em vez de formulários complexos ou planilhas, o usuário conversa com o app
como se fosse um “assistente financeiro”, tornando o processo mais
intuitivo e acessível.


❗ **2. PROBLEMA**
--------------------------------------------------
- Apps atuais exigem muita entrada manual e pouca personalização.
- Usuários iniciantes acabam desistindo por acharem o processo burocrático
  e pouco amigável.
- Falta de recomendações práticas e contextualizadas para ajudar na
  economia.
- Não há visão completa do caixa, pois muitos apps focam apenas em
  despesas.


🎯 **3. PÚBLICO-ALVO**
--------------------------------------------------
- Pessoas que desejam começar a organizar suas finanças sem complicação.
- Usuários iniciantes em controle financeiro.
- Pessoas que preferem interações simples e conversacionais em vez de
  interfaces tradicionais.

📝 **Nota importante:**
A solução deve seguir princípios de **design universal**, garantindo
acessibilidade e boa experiência para o maior número possível de usuários,
independentemente de idade, nível de letramento digital ou possíveis
limitações físicas.


⚙️ **4. FUNCIONALIDADES-CHAVE**
--------------------------------------------------
1. Registrar gastos via chat em linguagem natural.
2. Registrar receitas (salários, dividendos, aluguéis, etc.) via chat.
3. Classificação automática de transações (despesas e receitas).
4. Definir e acompanhar metas financeiras.
5. Receber dicas de economia do “Agente Financeiro”.
6. Visualizar relatórios simples e personalizados.
7. Exibir balanço financeiro (receitas vs despesas).
8. Função “Zerar” gastos e receitas para iniciar novo ciclo de controle.


🧩 **5. SUGESTÕES INCORPORADAS**
--------------------------------------------------

📈 Métricas de sucesso:
- Percentual de usuários que registram gastos/receitas pelo menos 3 vezes
  na semana.
- Taxa de engajamento com dicas do agente financeiro.
- Nível de satisfação (NPS ou feedback simples).

💬 Tom da conversa:
- O “Agente Financeiro” terá personalidade amigável, educativa e
  motivadora.

🚀 Fluxo inicial (onboarding):
- Perguntas simples para entender o perfil financeiro.
- Explicação rápida de como usar o chat.
- Primeira meta sugerida automaticamente.

🛠 Priorização das funcionalidades:
- MVP: registro via chat, classificação automática, relatórios básicos,
  balanço financeiro.
- Futuro: metas avançadas, integração com bancos, relatórios detalhados.

🧪 Validação com usuários reais:
- Testes com 5–10 pessoas para validar se o chat substitui planilhas e
  formulários.
- Coletar feedback sobre clareza das dicas e relatórios.

♿ Design universal:
- Interface inclusiva, linguagem simples, contraste adequado, suporte a
  leitores de tela e navegação intuitiva.


🤖 **6. ENTREGÁVEL DA IA**
--------------------------------------------------
Plano de MVP (Produto Mínimo Viável)

📱 Principais telas:
- Tela de chat (interação com o agente financeiro).
- Tela de metas (definição e acompanhamento).
- Tela de relatórios (visualização simples e personalizada).
- Tela de balanço financeiro (receitas vs despesas).
- Tela ou comando de “zerar” ciclo financeiro.

🧠 Recursos necessários:
- Processamento de linguagem natural (NLP).
- Banco de dados para armazenar transações e metas.
- Motor de classificação automática de gastos e receitas.
- Módulo de geração de relatórios e balanço.

✅ Validação inicial:
- Testar com grupo pequeno de usuários iniciantes.
- Avaliar se conseguem registrar gastos e receitas sem esforço.
- Medir engajamento com dicas do agente financeiro.
- Garantir boa experiência para diferentes perfis de usuários.


🔗 **7. INTERAÇÕES COM O LOVABLE**
--------------------------------------------------
> Crie um App de Finanças Pessoais com base no seguinte PRD
(Product Requirements Document).

> Solicita-se a implementação de um leitor de PDF que permita o envio da
fatura do cartão de crédito, possibilitando a identificação e
categorização dos gastos (alimentação, transporte, combustível, lazer,
outros).

> Solicita-se a inclusão de funcionalidade para registro de receitas via
chat, com classificação automática das entradas (salário, dividendos,
aluguel, etc.), permitindo o cálculo do balanço financeiro (receitas,
despesas e saldo).

> Solicita-se a inclusão de uma função “Zerar” que permita reiniciar gastos
e/ou receitas, com confirmação prévia, registro de histórico da ação e
atualização dos relatórios.


🖼 **8. REFERÊNCIAS VISUAIS (TELAS DO MVP)**
--------------------------------------------------

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/29841991-5f44-4f22-8e9f-012d44d8ba40"
    width="300"
    alt="Tela de Chat"
  />
  <img
    src="https://github.com/user-attachments/assets/ce1096a0-cd1e-43d6-ac22-53a54974d13d"
    width="300"
    alt="Tela de Relatórios"
  />
</p>

**RESUMO DAS TELAS — DASHBOARD E RELATÓRIOS**

As telas apresentadas representam o Dashboard financeiro do aplicativo
“Sua Grana Amiga”, oferecendo ao usuário uma visão consolidada, clara e
imediata da sua saúde financeira, conforme definido no PRD.

No topo da interface, o usuário visualiza o saldo do mês e o balanço
financeiro, destacando quanto ainda está disponível. Em seguida, são
exibidos cards-resumo com os principais indicadores financeiros, como:
- Total de receitas do mês
- Total de despesas do mês
- Percentual de metas atingidas
- Comparação entre valores planejados e realizados

A seção de análise mensal apresenta informações de destaque, incluindo:
- Maior gasto do mês, com categoria e valor
- Maior receita do mês, facilitando a identificação da principal fonte
  de entrada financeira

Os gastos do mês são exibidos de forma progressiva, mostrando:
- Valor já utilizado
- Valor restante em relação ao planejamento
- Percentual de consumo do orçamento

A tela também apresenta a visualização de gastos por categoria, permitindo
ao usuário identificar rapidamente onde estão concentradas suas despesas,
além de uma lista de últimos gastos, garantindo transparência e fácil
acompanhamento das transações recentes.

De forma geral, as telas reforçam os princípios definidos no PRD:
- Simplicidade visual
- Clareza das informações
- Apoio à tomada de decisão
- Acessibilidade para usuários iniciantes

A navegação mantém coerência com o fluxo do aplicativo, integrando chat,
dashboard, metas e relatórios, incentivando o acompanhamento contínuo da
vida financeira de maneira intuitiva e amigável.

📘 **9. CONCEITOS EXPLICADOS**
--------------------------------------------------

PRD (Product Requirements Document):
Documento que descreve requisitos de produto e alinha visão, problema,
público-alvo, funcionalidades e entregáveis antes do desenvolvimento.

Vibe Coding:
Prática de programação leve e criativa, focada em experimentação rápida,
aprendizado prático e construção de protótipos guiados por intuição e
feedback.

Design Universal:
Abordagem de design que busca criar produtos acessíveis e utilizáveis pelo
maior número possível de pessoas, considerando diferentes perfis desde o
início.


📊 **10. AVALIAÇÃO DO MVP**
--------------------------------------------------

### O que funcionou bem:
- Interação via chat em linguagem natural intuitiva e fácil de usar.
- Registro de despesas e receitas sem formulários complexos.
- Classificação automática contribuiu para melhor organização financeira.
- Visualização de relatórios e saldo facilitou a compreensão.

### O que não funcionou como o esperado:
- Falhas de classificação em mensagens genéricas ou ambíguas.
- Ausência de funcionalidades avançadas (edição em massa, filtros).
- Dependência de mensagens claras do usuário.
- Relatórios ainda limitados para análises mais profundas.
- Baixa interação no Lovable devido às limitações da conta gratuita.
- Limitações da IA em cenários mais complexos.

### O que aprendemos sobre conversar com IAs:
- Instruções claras geram respostas mais precisas.
- Contexto definido melhora o desempenho da IA.
- Linguagem natural reduz barreiras para usuários leigos.
- Validações e confirmações evitam interpretações incorretas.
