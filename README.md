
# 💸 App de Reorganização Financeira para pessoas endividadas usando Vibe Coding (Lovable) assistida por IA (Copilot)

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.


## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).


## 🎯 Desafio

[Problema]

Muitas pessoas:
- abandonam aplicativos financeiros;
- sentem ansiedade ao lidar com dinheiro;
- não sabem por onde começar;
- possuem dívidas acumuladas;
- evitam olhar suas finanças.

[Solução]

**Reconstrua** é um Coach de Recuperação Financeira com IA criado para ajudar pessoas endividadas ou financeiramente desorganizadas a retomarem o controle das suas finanças por meio de uma **jornada simples, acolhedora e sem julgamentos.**

[Visão]

A maioria das ferramentas financeiras ajuda usuários a analisar números.
O **Reconstrua** ajuda usuários a mudar comportamentos.
O objetivo é **transformar decisões financeiras emocionais em decisões conscientes** através de educação financeira simples, acompanhamento contínuo e pequenas vitórias.

[Proposta de Valor]

Um **coach financeiro guiado por IA** que ajuda pessoas a reconstruírem sua vida financeira **sem culpa, sem julgamentos e sem promessas irreais.**

[Público Alvo]

### Persona 1 - Ana
- 35 anos
- cartão de crédito atrasado
- ansiedade financeira
- já desistiu de outros aplicativos

### Persona 2 - Carlos
- 42 anos
- renda variável
- múltiplas dívidas
- não possui orçamento estruturado

[Principais funcionalidades]

**Mais do que funcionalidades, tentamos descrever a jornada do cliente** e deixamos a implementação do por conta da IA:

1. **Acolhimento**
2. Dinheiro que Entra
3. Dinheiro que Sai
4. **Necessidades vs Desejos**
5. Criar Fôlego Financeiro
6. **Pague-se Primeiro**
7. Diagnóstico de Dívidas
8. Estratégia das Dívidas
9. Plano de 90 Dias
10. Construção de Futuro

[Entregável da IA]

Gerar um plano d3e MVP com entrega de valor real ao usuário e um **protótipo funcional para realização de Beta testes** com um grupo de potenciais clientes / usuários, visando validar o conceito e a aceitabilidade do produto para avaliar seu potencial de mercado e decidir pelo **GO / NO GO** do projeto.

[Estratégia de desenvolvimnento]

Foram realizadas várias iterações com o CoPilot para geração de um **Product Requirement Document (PRD)** para guiar o desenvolvimento pelo LOVLABLE e economizar créditos.

Ao longo do processo ainda foram gerados o **AI Agent Design Spec** e o **Beta Test Plan** para guiar o desenvolvimento e validar se todas as funcionalidades esperadas no plano de testes foram realmente desenvolvidas.

O PRD foi divido em 5 etapas (sprints) que foram executadas uma a uma no Lovlabe e validadas individual e incrementalmente, para evitar retrabalho caso uma das etapas apresente falhas ou inconsistências.


# Entregável da IA

1. **Plano de MVP** com a definição da jornada do cliente, telas, detalhes funcionais, recursos e requisitos necessários. Este documento deve trazer as características adequadas para criação de uma coach financeira que tenha empatia e respeito ao cliente / usuário.
2. **Plano de Testes** para garantir o entendimento da proposta e validar o desenvolvimento com os resultados a serem avaliados
3. **Protótipo Funcional** para aplicação dos testes em uma amostra de cliente para validação de conceito e análise de aceitação do produto
4. **Questionário de Feedback do uso da Aplicação** para tabular as observações registradas durante os testes e gerar insigths para o **GO/NO GO**


## 🏆 Entrega Final

**Prompt completo (PRD)**

```
# PRD Lovable v1 - Coach de Recuperação Financeira com IA

## Visão do Produto

O produto é um coach financeiro guiado por IA que ajuda pessoas em dificuldades financeiras a recuperar o controle do dinheiro através de uma jornada estruturada, educativa e acolhedora.
O foco não é investir, enriquecer ou maximizar patrimônio.
O foco é:
- reduzir ansiedade financeira;
- criar hábitos saudáveis;
- equilibrar renda e gastos;
- lidar com dívidas de forma racional;
- reconstruir a capacidade de planejamento.
O aplicativo deve funcionar como um guia diário, semelhante a um Duolingo financeiro.

## Problema

Pessoas endividadas normalmente:
- não sabem exatamente quanto recebem e quanto gastam;
- evitam olhar para suas finanças;
- sentem culpa ou vergonha;
- tomam decisões emocionais;
- não possuem um plano concreto de recuperação.

Os aplicativos atuais são excessivamente técnicos e focados em relatórios históricos.
O produto deve focar em decisões práticas para o presente e para os próximos passos.

---

## Público-Alvo

### Persona Primária

**Ana**
- 35 anos
- Assistente administrativa
- Renda mensal: R$ 3.200
Características:
- possui cartão atrasado;
- faz compras impulsivas ocasionalmente;
- já tentou usar aplicativos financeiros;
- abandona rapidamente ferramentas complexas;
- sente ansiedade ao pensar em dinheiro.

Objetivo: recuperar o controle financeiro sem se sentir julgada.

### Persona Secundária

**Carlos**
- 42 anos
- Autônomo
- Renda variável
Características:
- possui várias dívidas;
- não sabe o valor total devido;
- não tem orçamento formal;
- vive apagando incêndios financeiros.

Objetivo: construir estabilidade financeira.

---

## Tom de Voz do Produto

### O agente deve ser
- acolhedor;
- simples;
- paciente;
- educativo;
- direto.

### O agente não deve ser
- professoral;
- moralista;
- agressivo;
- vendedor;
- coach motivacional vazio.

### Frases permitidas
- Vamos resolver uma etapa de cada vez.
- Você não precisa fazer tudo hoje.
- Já demos um passo importante.

### Frases proibidas
- Você precisa economizar mais.
- Foi um erro gastar isso.
- Você deveria ter se planejado.
- Fique rico fazendo isso.

---

## Estrutura da Jornada

### Módulo 0 - Acolhimento

Objetivo: criar segurança psicológica.

### Módulo 1 - Dinheiro que Entra

Coleta:
- salário;
- benefícios;
- renda variável;
- frequência.

Resultado: renda mensal calculada.

### Módulo 2 - Dinheiro que Sai

Coleta:
- moradia;
- alimentação;
- transporte;
- saúde;
- educação;
- lazer;
- assinaturas.

Resultado: mapa simplificado de despesas.

### Módulo 3 - Essencial vs Desejo

Classificação automática:
- Essencial
- Importante
- Desejo

### Módulo 4 - Criando Fôlego

Identificar cortes, substituições e gastos renegociáveis.

### Módulo 5 - Pague-se Primeiro

Definição de valor mínimo viável para poupança.

### Módulo 6 - Diagnóstico de Dívidas

Etapa opcional e não bloqueante.

### Módulo 7 - Estratégia das Dívidas

Priorização, renegociação e organização.

### Módulo 8 - Plano de 90 Dias

Metas, compromissos e acompanhamento.

### Módulo 9 - Futuro Financeiro

Reserva de emergência, objetivos e sonhos.

---

## Sistema de Progressão

- 🥉 Primeiro passo
- 🥉 Raio-X financeiro
- 🥈 Gastos organizados
- 🥈 Primeira economia
- 🥇 Plano financeiro criado
- 🥇 Reconstrutor financeiro

---

## Telas do Aplicativo

### Tela 1 - Onboarding
- mensagem de boas-vindas;
- explicação da jornada;
- botão começar.

### Tela 2 - Dashboard
- etapa atual;
- progresso;
- renda;
- gastos;
- próximas ações.

### Tela 3 - Chat Principal
- conversa com IA;
- registro de gastos;
- dúvidas financeiras;
- orientações.

### Tela 4 - Jornada
Timeline visual da evolução.

### Tela 5 - Plano Financeiro
Objetivos atuais, plano de ação e metas.

### Tela 6 - Conquistas
Badges, evolução e marcos atingidos.

---

## Funcionalidades de IA

### Extração de Gastos

Entrada:
> Gastei R$ 48 no mercado.

Saída:

```json
{
  "tipo": "despesa",
  "valor": 48,
  "categoria": "alimentação",
  "descricao": "mercado"
}

### Classificação de Prioridade

- essencial;
- importante;
- desejo.

### Geração de Insights

"Você identificou R$ 180 que podem ser economizados este mês."

### Check-in Diário

Tempo máximo: 30 segundos.

---

## Banco de Dados (Supabase)

### users
- id
- nome
- email
- created_at

### financial_profiles
- user_id
- renda_mensal
- tipo_renda
- etapa_atual

### expenses
- id
- user_id
- valor
- categoria
- prioridade
- data

### debts
- id
- user_id
- credor
- saldo_devedor
- parcela
- status

### goals
- id
- user_id
- titulo
- valor_meta
- valor_atual

### achievements
- id
- user_id
- badge
- data_conquista

### checkins
- id
- user_id
- humor_financeiro
- observacoes

---

## Stack Técnica

Frontend:
- Lovable
- React
- TypeScript
- Tailwind

Backend:
- Supabase

Autenticação:
- Supabase Auth

IA:
- OpenAI GPT-5 ou equivalente

Persistência:
- PostgreSQL (Supabase)

## Regras Críticas

1. Nunca julgar o usuário.
2. Nunca prometer enriquecimento.
3. Nunca recomendar produtos financeiros.
4. Nunca vender crédito.
5. Não oferecer aconselhamento jurídico.
6. Sempre sugerir apenas o próximo passo.
7. Permitir que o usuário pule a análise completa das dívidas.
8. Priorizar redução da ansiedade financeira.
9. Explicar conceitos com linguagem simples.
10. Recompensar progresso, não perfeição.

## Prompt Mestre do Agente

Você é um Coach de Recuperação Financeira.

Sua missão é ajudar pessoas a reconstruir sua vida financeira através de pequenas decisões práticas.

Você nunca faz julgamentos.

Você não promete riqueza.

Você não utiliza jargões.

Seu objetivo é reduzir ansiedade, aumentar clareza e indicar sempre o próximo passo mais útil.

Antes de tentar resolver um problema complexo, garanta que o usuário compreenda sua situação atual.

Comemore pequenas vitórias e transforme decisões emocionais em decisões conscientes.

```

**Plano de Testes**

```
# Beta Test Plan v1
## Projeto Reconstrua

---

# Objetivo do Beta

Validar se o Reconstrua gera valor percebido suficiente para justificar investimentos adicionais em tecnologia, ferramentas e aquisição de usuários.

O objetivo principal não é validar funcionalidades.

O objetivo principal é validar:

- proposta de valor;
- experiência emocional;
- utilidade percebida;
- potencial de retenção.

---

# Hipóteses a Validar

## H1
Os usuários preferem conversar sobre finanças em vez de preencher planilhas.

## H2
Uma experiência sem julgamentos aumenta o engajamento.

## H3
A jornada guiada reduz ansiedade financeira.

## H4
Pequenas vitórias aumentam motivação.

## H5
Usuários enxergam valor antes da etapa de análise completa das dívidas.

---

# Perfil dos Participantes

Quantidade recomendada:

- mínimo: 5 usuários
- ideal: 10 a 15 usuários

Critérios:

- idade entre 25 e 60 anos
- já enfrentou dificuldades financeiras
- utiliza smartphone diariamente
- não trabalha no mercado financeiro

---

# Cenários de Teste

## Cenário 1
Primeiro contato

Objetivo:
Avaliar reação ao posicionamento do produto.

## Cenário 2
Onboarding

Objetivo:
Verificar se a jornada é fácil de entender.

## Cenário 3
Registro de gastos

Objetivo:
Validar simplicidade do fluxo.

## Cenário 4
Interação com o Coach

Objetivo:
Avaliar sensação de acolhimento.

## Cenário 5
Exploração da jornada

Objetivo:
Verificar clareza das etapas.

---

# Roteiro de Entrevista

## Antes do uso

1. Como você se sente quando pensa em dinheiro?
2. Você utiliza algum aplicativo financeiro?
3. O que mais te incomoda ao tentar controlar gastos?

---

## Durante o uso

1. O que você acredita que este aplicativo faz?
2. O que chamou mais sua atenção?
3. Houve algum momento confuso?
4. Você se sentiu julgado em algum momento?

---

## Após o uso

1. Você utilizaria este produto novamente?
2. Qual funcionalidade foi mais útil?
3. O que faltou?
4. Você indicaria para alguém?
5. Você pagaria por este produto futuramente?

---

# Métricas de Sucesso

## Ativação

Meta:
70% completam onboarding.

## Compreensão

Meta:
80% entendem a proposta de valor.

## Utilidade

Meta:
70% afirmam que o produto pode ajudá-los.

## Recomendação

Meta:
NPS superior a 50.

## Continuidade

Meta:
60% demonstram interesse em continuar usando.

---

# Registro de Feedback

Para cada participante registrar:

- pontos positivos;
- dúvidas;
- dificuldades;
- sugestões;
- nota geral.

---

# Matriz Go / No-Go

## GO

Prosseguir com investimento se:

- usuários entenderem rapidamente a proposta;
- o coach gerar confiança;
- a jornada fizer sentido;
- houver intenção clara de retorno.

## NO-GO

Reavaliar o produto se:

- parecer apenas mais um controle financeiro;
- usuários não enxergarem diferencial;
- o agente parecer genérico;
- a retenção potencial parecer baixa.

---

# Próximos Passos Após o Beta

1. Consolidar aprendizados.
2. Revisar PRD.
3. Priorizar melhorias.
4. Evoluir MVP.
5. Iniciar beta fechado ampliado.
6. Avaliar contratação da versão paga do Lovable.

```

**Protótipo Funcional**

O protótipo funcional pode ser visualizado e testado pelo link https://spec-to-app-workshop.lovable.app/

Segue algumas telas da aplicação:

<img width="1413" height="736" alt="image" src="https://github.com/user-attachments/assets/d632bcde-e913-4dec-9e25-6753e6950321" />
<img width="1305" height="832" alt="image" src="https://github.com/user-attachments/assets/94699f05-8629-4ded-b3cb-b5a3b863dc83" />
<img width="1637" height="813" alt="image" src="https://github.com/user-attachments/assets/0ab4890f-49ce-49e9-a284-d12d6cf1e9e3" />
<img width="1157" height="840" alt="image" src="https://github.com/user-attachments/assets/c181f0a9-f79a-493b-9c1f-2f9b504e71ec" />
<img width="1222" height="826" alt="image" src="https://github.com/user-attachments/assets/388fc87a-148d-4632-8cb0-f52a3131cd1e" />
<img width="1062" height="832" alt="image" src="https://github.com/user-attachments/assets/84fb6dbb-0885-4ce4-b8d0-aad4b7f1e0cf" />
<img width="978" height="851" alt="image" src="https://github.com/user-attachments/assets/acff22d5-a1dd-4d91-8122-71b8b66bef01" />
<img width="975" height="840" alt="image" src="https://github.com/user-attachments/assets/0497f5c2-9ea1-4df9-8a4b-fe621eb5fd59" />
<img width="1100" height="863" alt="image" src="https://github.com/user-attachments/assets/a38626a0-83d4-455a-a366-0f23e13e2cdd" />
<img width="1321" height="853" alt="image" src="https://github.com/user-attachments/assets/68c4f6f2-c467-4698-a1f7-e7f8345ca88d" />
<img width="1044" height="869" alt="image" src="https://github.com/user-attachments/assets/ee338b1f-245e-4047-bcec-cc5c99a98080" />
<img width="1094" height="858" alt="image" src="https://github.com/user-attachments/assets/857bf3b1-7d09-48da-91c1-9766fcdaca11" />
<img width="1108" height="828" alt="image" src="https://github.com/user-attachments/assets/b361c4ac-cfd8-4a42-80e5-1bf09316a96f" />
<img width="1100" height="862" alt="image" src="https://github.com/user-attachments/assets/762ba79c-60fa-48a2-acbc-00d2684f2d5e" />
<img width="1191" height="850" alt="image" src="https://github.com/user-attachments/assets/6376403a-f0b7-4993-a6dc-908fcf08855a" />
<img width="1133" height="819" alt="image" src="https://github.com/user-attachments/assets/252266ac-b1f1-4564-b971-e014862158dc" />
<img width="1154" height="860" alt="image" src="https://github.com/user-attachments/assets/eb7e29e3-14ce-484e-bb71-e931d7db0d00" />


**Questionário de Feedback do uso da Aplicação**
```
# Formulário de Feedback - Beta Test Reconstrua

## Informações Gerais

**Nome (opcional):** ______________________

**Data:** ____/____/______

**Tempo utilizando o protótipo:**

- ( ) Menos de 10 minutos
- ( ) 10 a 20 minutos
- ( ) 20 a 30 minutos
- ( ) Mais de 30 minutos

---

# Primeira Impressão

### 1. Você entendeu rapidamente o propósito do produto?

- ( ) Sim
- ( ) Parcialmente
- ( ) Não

Comentários:

________________________________________________

### 2. Em uma frase, o que você acredita que o Reconstrua faz?

________________________________________________

---

# Experiência de Uso

Avalie de 1 a 5:

| Critério | 1 | 2 | 3 | 4 | 5 |
|-----------|---|---|---|---|---|
| Facilidade de uso | ○ | ○ | ○ | ○ | ○ |
| Clareza da jornada | ○ | ○ | ○ | ○ | ○ |
| Organização das informações | ○ | ○ | ○ | ○ | ○ |
| Visual do aplicativo | ○ | ○ | ○ | ○ | ○ |
| Navegação | ○ | ○ | ○ | ○ | ○ |

---

# Coach Financeiro

### 3. O assistente pareceu acolhedor?

- ( ) Muito
- ( ) Um pouco
- ( ) Neutro
- ( ) Pouco
- ( ) Nada

### 4. Em algum momento você se sentiu julgado?

- ( ) Sim
- ( ) Não

Se sim, explique:

________________________________________________

### 5. Você confiaria nesse assistente para falar sobre sua vida financeira?

Nota de 0 a 10:

______

---

# Valor Percebido

### 6. O que foi mais útil?

________________________________________________

### 7. O que foi menos útil?

________________________________________________

### 8. Você acredita que este produto poderia ajudar pessoas endividadas?

- ( ) Sim
- ( ) Talvez
- ( ) Não

Por quê?

________________________________________________

---

# Diferenciação

### 9. Este produto parece diferente dos aplicativos financeiros tradicionais?

- ( ) Muito diferente
- ( ) Um pouco diferente
- ( ) Igual aos demais

Explique:

________________________________________________

---

# Intenção de Uso

### 10. Você utilizaria este aplicativo novamente?

- ( ) Sim
- ( ) Talvez
- ( ) Não

### 11. Você recomendaria este aplicativo para alguém?

Nota de 0 a 10:

______

### 12. Você pagaria por uma versão futura?

- ( ) Sim
- ( ) Talvez
- ( ) Não

---

# Perguntas Abertas

### 13. O que mais gostou?

________________________________________________

### 14. O que deveria melhorar?

________________________________________________

### 15. O que está faltando?

________________________________________________

---

# Decisão Final

Após usar o protótipo, qual afirmação melhor representa sua opinião?

- ( ) Eu usaria este produto.
- ( ) Eu testaria novamente após melhorias.
- ( ) Não vejo valor suficiente.

Comentários finais:

________________________________________________

________________________________________________
```

**Exemplos de interações com a IA**


**Resumo da jornada com o CoPilot**

```
**Esse documento costuma ser o mais valioso de todos após alguns meses, porque evita a pergunta:

"Em que estágio eu parei?"

e permite retomar o projeto em poucos minutos.

Poderia fazer um resumo de nossas interações neste chat? Por exemplo, 1.Marco inseriu PRD inicial,

Claro. Na verdade, você percorreu uma jornada bastante estruturada de ideia → descoberta → produto → protótipo → validação. Abaixo está um resumo cronológico das nossas interações.

Histórico Executivo da Construção do Projeto Reconstrua
1. Marco apresentou o PRD inicial

Você começou com um conceito simples:

Aplicativo de organização financeira pessoal baseado em conversas.

Objetivos iniciais:

registrar gastos por chat;
categorizar despesas automaticamente;
metas financeiras;
agente financeiro;
relatórios simples.

Nessa fase o produto ainda estava posicionado como um organizador financeiro conversacional.

2. Refinamento da proposta de valor

Discutimos que:

"Registrar gastos" não é o verdadeiro problema.

A principal dor identificada foi:

ansiedade financeira;
abandono de aplicativos financeiros;
excesso de foco no passado;
decisões emocionais.

Conclusão:

O produto deveria deixar de ser um simples organizador financeiro.

3. Mudança de posicionamento

O produto evoluiu de:

Controle financeiro via chat

para:

Coach de Recuperação Financeira com IA

Nova proposta:

ajudar pessoas endividadas;
reduzir ansiedade financeira;
ensinar educação financeira;
criar hábitos financeiros;
orientar decisões práticas.
4. Definição da jornada do usuário

Construímos uma jornada progressiva:

Acolhimento
Dinheiro que entra
Dinheiro que sai
Necessidades vs desejos
Criar fôlego financeiro
Pague-se primeiro
Diagnóstico de dívidas
Estratégia das dívidas
Plano de 90 dias
Construção de futuro
5. Decisão importante sobre dívidas

Você levantou uma preocupação importante:

Pedir todas as dívidas logo no início pode gerar desistência.

Após análise, definimos:

não exigir todas as dívidas inicialmente;
focar primeiro no presente;
tratar dívidas de forma progressiva;
permitir que o usuário adie a etapa.

Isso se tornou um princípio central do produto.

6. Transformação da jornada em requisitos MVP

A jornada foi convertida em:

requisitos funcionais;
critérios de conclusão;
funcionalidades mínimas;
princípios de UX.

Nasceu o primeiro MVP formal.

7. Criação do PRD MVP

Foi gerado:

📄 PRD_Coach_Recuperacao_Financeira_MVP.md

Contendo:

visão;
problema;
funcionalidades;
jornada;
métricas de sucesso.
8. Evolução para um PRD específico para Lovable

Adaptamos o PRD para Vibe Coding.

Foram adicionados:

personas;
telas;
fluxos;
banco de dados;
comportamento da IA;
stack tecnológica.

Foi criado:

📄 PRD_Lovable_Coach_Recuperacao_Financeira_v1.md

9. Criação do Lovable Build Plan

Estruturamos o desenvolvimento em quatro sprints:

Sprint 1:

estrutura visual

Sprint 2:

persistência

Sprint 3:

jornada

Sprint 4:

IA conversacional

Documento criado:

📄 Lovable_Build_Plan_v1_Reconstrua.md

10. Criação do AI Agent Design Spec

Definimos profundamente:

personalidade do agente;
tom de voz;
memória;
regras;
limitações;
tratamento de dívidas;
tratamento de ansiedade financeira.

Documento criado:

📄 AI_Agent_Design_Spec_Reconstrua_v1.md

11. Criação do Master Prompt

Consolidamos o projeto em um prompt único para o Lovable.

Documento criado:

📄 Master_Prompt_Lovable_Reconstrua.md

12. Criação do Product Discovery Pack

Estruturamos:

hipóteses;
riscos;
concorrentes;
diferenciais;
métricas;
monetização.

Documento criado:

📄 Product_Discovery_Pack_Reconstrua_v1.md

13. Planejamento da validação

Criamos:

📄 Beta_Test_Plan_Reconstrua_v1.md

Definindo:

entrevistas;
métricas;
critérios Go/No-Go.
14. Criação do formulário de feedback

Documento criado:

📄 Formulario_Feedback_Beta_Reconstrua_v1.md

Objetivos:

validar proposta de valor;
validar acolhimento;
validar intenção de uso.
15. Consolidação para execução

Criamos:

📄 Reconstrua_Execution_Master_Pack_v1.md

Contendo:

visão consolidada;
MVP;
sprints;
critérios de decisão.
16. Criação do guia operacional

Documento criado:

📄 Reconstrua_Guia_Execucao_IA_v1.md

Definindo:

como usar o Lovable;
como consumir as 5 iterações gratuitas;
quando investir.
17. Estratégia das 5 iterações gratuitas

Definimos os prompts de:

Estrutura inicial
Jornada
Coach financeiro
Funcionalidades
Refinamento final

Objetivo:

Validar conceito antes de contratar a versão paga.

18. Artefatos pós-beta

Criamos:

📄 Reconstrua_Beta_Results_Template.md

📄 Reconstrua_Learning_Synthesis.md

📄 Reconstrua_Priorization_Matrix.md

Objetivos:

consolidar resultados;
transformar feedback em melhorias;
priorizar backlog.
19. Criação do README

Documento criado:

📄 README_Reconstrua.md

Servindo como porta de entrada do projeto.

20. Criação do Resumo Executivo

Documento criado:

📄 Resumo_Executivo_Reconstrua_v1.md

Voltado para:

investidores;
sócios;
mentores;
desenvolvedores.
21. Estrutura de Pastas V2

Definimos uma arquitetura de documentação preparada para:

Discovery
Produto
IA
Construção
Arquitetura
Negócio
Beta
Analytics
22. Empacotamento do Projeto

Foi gerado:

📦

Reconstrua_Complete_Project_Pack_v1.zip

Consolidando toda a documentação produzida.

Situação Atual do Projeto

Nome: Reconstrua

Fase Atual: Discovery + Prototipação

Próxima Ação Recomendada: Executar as 5 iterações gratuitas do Lovable

Hipótese Principal:

Pessoas endividadas valorizam mais um coach financeiro acolhedor e sem julgamentos do que um aplicativo tradicional de controle financeiro.

Objetivo Imediato:

Validar o conceito com usuários reais antes de investir em tecnologia, integrações e planos pagos.

```

**Evidências da jornada com o CoPilot**

<img width="1020" height="491" alt="image" src="https://github.com/user-attachments/assets/224b384e-ea4b-4639-a1c7-c49ab02c8ea7" />
<img width="1092" height="521" alt="image" src="https://github.com/user-attachments/assets/af901e3f-9a95-4288-ae7e-41752238d961" />
<img width="1051" height="473" alt="image" src="https://github.com/user-attachments/assets/dea3dcfc-c298-475a-8786-8abdf0dc6b6b" />
<img width="920" height="758" alt="image" src="https://github.com/user-attachments/assets/582da1d8-7581-487b-95ee-3a7398fdea35" />
<img width="991" height="684" alt="image" src="https://github.com/user-attachments/assets/218415e7-59bd-4e41-855f-6e0e3ac26c2b" />
<img width="1096" height="484" alt="image" src="https://github.com/user-attachments/assets/63ca9ac1-ba45-4311-85b4-7b318b119670" />
<img width="1002" height="596" alt="image" src="https://github.com/user-attachments/assets/8d1b65a0-447c-4499-a996-0acf88c34b72" />
<img width="1067" height="604" alt="image" src="https://github.com/user-attachments/assets/2a1f700d-46b9-487a-847b-4bb2669d43f2" />
<img width="1117" height="350" alt="image" src="https://github.com/user-attachments/assets/27b21c21-a21b-4190-bf2d-711f06b9f439" />
<img width="1113" height="654" alt="image" src="https://github.com/user-attachments/assets/51356f31-65f0-49e8-9f13-604f8af1a493" />
<img width="1105" height="640" alt="image" src="https://github.com/user-attachments/assets/55c25628-60c7-4767-80f6-6094060cf913" />
<img width="1150" height="668" alt="image" src="https://github.com/user-attachments/assets/f4ab3873-6c93-4418-832e-52d9d9ba682d" />

**Evidências da jornada com o Lovlable**

<img width="562" height="622" alt="image" src="https://github.com/user-attachments/assets/45bfc756-bc65-4a05-bf12-229348f47ccd" />
<img width="488" height="499" alt="image" src="https://github.com/user-attachments/assets/1fe685a5-17b7-486e-96ae-d65755746147" />
<img width="535" height="507" alt="image" src="https://github.com/user-attachments/assets/bbbcd293-6c61-45bc-b8be-34302a9ff6ef" />
<img width="529" height="558" alt="image" src="https://github.com/user-attachments/assets/ad174319-4e39-4412-8fd0-85f4d3845412" />
<img width="546" height="546" alt="image" src="https://github.com/user-attachments/assets/40e60b7e-76ce-4ec0-866d-3d08d83b9b66" />
<img width="538" height="454" alt="image" src="https://github.com/user-attachments/assets/6c0146b5-5069-4eca-9864-e7e9f0343cb4" />
<img width="535" height="501" alt="image" src="https://github.com/user-attachments/assets/52d084af-1f18-42a3-8d28-20877b5d11cb" />
<img width="559" height="481" alt="image" src="https://github.com/user-attachments/assets/0d4a99da-2368-494b-af17-623fe6cf8e7b" />
<img width="564" height="579" alt="image" src="https://github.com/user-attachments/assets/e1653f85-637c-4263-9c7c-948bd3ed0ce3" />
<img width="513" height="528" alt="image" src="https://github.com/user-attachments/assets/2e9bfc04-e2d1-4a20-9368-88eeb5ceb246" />
<img width="515" height="540" alt="image" src="https://github.com/user-attachments/assets/7862d917-03d1-48d5-a9aa-cee0c9d06ebb" />
<img width="537" height="485" alt="image" src="https://github.com/user-attachments/assets/44276691-11d7-4f19-9119-736201549c7e" />
<img width="552" height="542" alt="image" src="https://github.com/user-attachments/assets/b15d9eb8-69d5-4580-b69a-78dbd935ea4f" />
<img width="544" height="500" alt="image" src="https://github.com/user-attachments/assets/69ac38ea-2b36-4387-806f-bce20e8ba3ff" />
<img width="548" height="504" alt="image" src="https://github.com/user-attachments/assets/d8919556-544d-4a72-8cf5-d92adc7d1c06" />
<img width="542" height="496" alt="image" src="https://github.com/user-attachments/assets/83c54242-2e23-4d54-8ec1-9d0e4c20a45f" />
<img width="536" height="526" alt="image" src="https://github.com/user-attachments/assets/5ed78b4b-60be-4867-8acd-b054d4a1e73f" />
<img width="525" height="512" alt="image" src="https://github.com/user-attachments/assets/0e81020d-4f37-41d7-9ef0-6d121c0ab4c2" />


**Resumo do Aplicativo**

O aplicativo foi pensado para guiar a jornada de endividados rumo à educação financeira de forma leve, não-agressiva e não-estressante.
O **Reconstrua** não é apenas um aplicativo financeiro, mas uma jornada guiada para solução de dívidas de forma gradual ao mesmo tempo que oferece conforto emocional ao devedor à medida que o coloca como protagonista da aplicação e não o dinheiro.
É muito comum pessoas endividadas tentarem uma ou duas vezes ao ano reestruturar suas dívidas mas desistem ao começar confrontar valores atrasados, dívidas impagáveis, etc.
O foco do **Reconstrua** é ajustar primeiro o presente, orientando o devedor a equilibrar entradas e saídas, refletindo sobre desejos e necessidades, ensinando o conceito do **pague-se primeiro** e ajudando-o a fazer o planejando passo-a-passo, começando pelo mapeamento de receitas e despesas atuais.
Este é o grande diferencial em relação ao mercado, **ao invés de focar nas dívidas** o **Reconstrua** coloca **o indivíduo como protagonista** e oferece **apoio nesta jornada**
Para ser coerente e consistente com a sua finalidade, o **Reconstrua** **não trata de investimento e não vende produtos**. Sua receita será proveniente exclusivamente  da mensalidade do produto.


**Reflexão sobre o processo de desenvolvimento**

### O que funcionou bem?
As interações com as duas IA's foram tranquilas e produtivas. Poucos ajustes necessários para a construção de um protótipo navegável.

### O que não funcionou como o esperado?
Mesmo com todo o refinamento feito pelo Copilot, devido à quantidade de funcionalidades previstas, o consumo do Lovlable foi acima do esperado: eu tinha 5 créditos da versão Free mas o desenvolvimento exigiu mais 20 crédito para conclusão, pelo qual paguei contratando o Lovlable com pagamento mensal (R% 25).

### O que aprendeu sobre conversar com IAs?
Eu já uso IAs regularmente. Mas a questão do uso de créditos do Lovlable chama a atenção para o controle de custos. Pela complexidade do desenvolvimento, um custo de R$ 25 não foi excessivo, mas sem controle, alarmes e relatórios de acompanhamento, os custos podem ficar excessivamente elevados.

