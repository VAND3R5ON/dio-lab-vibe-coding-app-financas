# App de Finanças Pessoais do Vanderson com Vibe Coding

## Sobre o Projeto

O FinChat é uma aplicação de organização financeira pessoal que simplifica o controle do dinheiro por meio de uma experiência conversacional.

O objetivo do projeto é permitir que usuários registrem receitas, despesas e metas financeiras utilizando linguagem natural, reduzindo a complexidade encontrada em aplicativos tradicionais de finanças.

---

## Resultado Final

Aplicação gerada no Lovable:

https://my-finance-buddy-441.lovable.app/chat

### Screenshot

<img width="1371" height="993" alt="image" src="https://github.com/user-attachments/assets/f472d455-3fe7-442b-aef3-2c834f660deb" />


---

## Resumo do Aplicativo

### Registro Conversacional de Transações

Permite registrar receitas e despesas utilizando linguagem natural.

Exemplos:

- "Gastei R$ 45 no almoço."
- "Recebi R$ 2.500 de salário."
- "Paguei R$ 120 de internet."

O sistema interpreta automaticamente:

- Valor da transação
- Tipo (receita ou despesa)
- Categoria financeira
- Data da movimentação

### Dashboard Financeiro

Apresenta uma visão consolidada da situação financeira do usuário.

Indicadores disponíveis:

- Saldo atual
- Total de receitas do mês
- Total de despesas do mês
- Alertas financeiros
- Resumo do desempenho mensal

### Análise de Gastos por Categoria

Os gastos são categorizados automaticamente e apresentados visualmente através de gráficos.

Permite visualizar:

- Distribuição percentual dos gastos
- Valor total por categoria
- Composição das despesas

### Evolução Financeira

Permite acompanhar receitas e despesas ao longo do tempo.

Recursos:

- Comparação entre entradas e saídas
- Histórico financeiro mensal
- Identificação de tendências de gastos

### Metas Financeiras

Possibilita criar e acompanhar objetivos financeiros pessoais.

Exemplos:

- Reserva de emergência
- Viagem
- Compra de notebook
- Entrada de imóvel

### Agente Financeiro

Assistente responsável por gerar insights e recomendações personalizadas com base nos hábitos financeiros do usuário.

### Registro Rápido

Permite adicionar movimentações financeiras de forma prática através de um fluxo simplificado.

---

## Processo de Vibe Coding

### Interação com a IA

Prompt utilizado no Lovable:

```text
Crie um App de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}
```

### Ferramentas Utilizadas

- Microsoft Copilot Web para refinamento do PRD
- Lovable para geração da aplicação
- Markdown para documentação do projeto

---

## PRD Utilizado

PRD refinado no Copilot Web:

```markdown
# PRD - FinChat

## Visão do Produto

Criar um aplicativo de finanças pessoais que permita aos usuários registrar, acompanhar e melhorar sua vida financeira por meio de conversas em linguagem natural, eliminando a complexidade de planilhas e formulários tradicionais.

## Problema

Muitas pessoas desejam controlar suas finanças, mas abandonam esse hábito porque:

- O cadastro de despesas é trabalhoso.
- Os aplicativos exigem muitas telas e campos manuais.
- A análise financeira costuma ser difícil de entender.
- Falta orientação personalizada para quem está começando.

O produto busca transformar o controle financeiro em uma conversa simples e intuitiva.

---

## Objetivo do MVP

Validar se usuários conseguem registrar e acompanhar suas finanças utilizando apenas linguagem natural, com menos esforço do que aplicativos financeiros tradicionais.

### Indicadores de Sucesso

- Usuário consegue registrar uma despesa em menos de 15 segundos.
- Pelo menos 80% das transações são classificadas corretamente.
- Usuário consegue visualizar seu saldo e gastos por categoria.
- Usuário recebe ao menos uma recomendação útil de economia por semana.

---

## Público-Alvo

### Primário

Pessoas iniciando sua organização financeira pessoal.

### Secundário

- Universitários.
- Jovens profissionais.
- Pessoas que nunca utilizaram aplicativos financeiros.
- Usuários que abandonaram planilhas por complexidade.

---

## Proposta de Valor

"Controle suas finanças conversando com um assistente, como se estivesse trocando mensagens com um amigo."

---

# Princípio Norteador

O usuário nunca deve precisar aprender finanças ou aprender a usar o aplicativo para conseguir controlar seu dinheiro.

O sistema deve se adaptar ao usuário, e não o contrário.

---

# Design Universal

## Objetivo

A aplicação deverá seguir os princípios de Design Universal para garantir que a experiência seja acessível, intuitiva e eficiente para o maior número possível de pessoas, independentemente de idade, experiência tecnológica, contexto de uso ou limitações físicas, sensoriais e cognitivas.

## Diretrizes de Experiência

### Clareza

- Utilizar linguagem simples e cotidiana.
- Evitar jargões financeiros.
- Explicar conceitos quando necessário.
- Exibir mensagens objetivas e fáceis de compreender.

Exemplo:

Em vez de:
"Seu fluxo de caixa apresentou variação negativa."

Utilizar:
"Você gastou mais dinheiro do que recebeu este mês."

### Legibilidade

- Fonte com boa leitura em dispositivos móveis.
- Contraste adequado entre texto e fundo.
- Hierarquia visual clara.
- Não depender apenas de cores para transmitir significado.

### Acessibilidade Cognitiva

- Fluxos simples.
- Poucas decisões por tela.
- Feedback imediato após cada ação.
- Linguagem acolhedora e educativa.

### Inclusão Digital

O sistema deve funcionar bem para:

- Iniciantes em finanças.
- Pessoas com pouca experiência digital.
- Idosos.
- Usuários com dificuldades de leitura ou interpretação.

### Flexibilidade de Uso

Permitir múltiplos caminhos para completar uma tarefa.

Exemplos:

- Registrar gasto via conversa.
- Registrar gasto por botão de ação rápida.
- Consultar saldo pelo chat.
- Consultar saldo pelo dashboard.

### Acessibilidade Técnica

- Compatível com leitores de tela.
- Navegação por teclado.
- Textos alternativos em imagens.
- Seguir boas práticas WCAG.

---

# Funcionalidades do MVP

## 1. Registro de Gastos por Conversa

### Descrição

Permitir que o usuário registre receitas e despesas utilizando linguagem natural.

### Exemplos

- "Gastei R$ 45 no almoço."
- "Paguei R$ 120 de internet."
- "Recebi R$ 2.500 de salário."

### Resultado Esperado

O sistema identifica automaticamente:

- Valor.
- Tipo da transação.
- Categoria.
- Data.

---

## 2. Classificação Automática

### Descrição

A IA classifica automaticamente cada transação.

### Categorias Iniciais

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Investimentos
- Outros

### Exemplo

Entrada:

"Gastei R$ 89 no supermercado."

Resultado:

"Despesa registrada em Alimentação."

---

## 3. Metas Financeiras

### Descrição

Permitir que usuários criem e acompanhem objetivos financeiros.

### Exemplos

- Viagem.
- Reserva de emergência.
- Compra de notebook.
- Entrada de imóvel.

### Recursos

- Nome da meta.
- Valor desejado.
- Data limite.
- Percentual de progresso.

---

## 4. Agente Financeiro

### Descrição

Assistente que analisa os hábitos financeiros do usuário e gera recomendações personalizadas.

### Exemplos

- "Você gastou 20% mais com delivery este mês."
- "Seu maior gasto atual é transporte."
- "Se economizar R$ 10 por dia, alcançará sua meta mais cedo."

---

## 5. Dashboard Simplificado

### Componentes

- Saldo atual.
- Receitas do mês.
- Despesas do mês.
- Gastos por categoria.
- Evolução mensal.
- Progresso das metas.

---

# Fluxo Principal

## Primeiro Acesso

1. Criar conta.
2. Informar objetivo financeiro principal.
3. Realizar onboarding.
4. Entrar no chat principal.

## Uso Diário

1. Abrir aplicativo.
2. Registrar movimentações financeiras por conversa.
3. Receber confirmação automática.
4. Consultar saldo, categorias ou metas.

---

# Principais Telas

## Tela 1 - Login e Cadastro

Objetivo:

Permitir acesso seguro ao sistema.

---

## Tela 2 - Onboarding

Objetivo:

Compreender os objetivos financeiros e perfil inicial do usuário.

---

## Tela 3 - Chat Principal

Objetivo:

Registrar movimentações e conversar com o Agente Financeiro.

Componentes:

- Histórico da conversa.
- Campo de mensagem.
- Sugestões rápidas.
- Respostas inteligentes.

---

## Tela 4 - Dashboard

Objetivo:

Apresentar um resumo da situação financeira.

Componentes:

- Cards de indicadores.
- Gráfico por categoria.
- Evolução financeira.
- Progresso das metas.

---

## Tela 5 - Metas Financeiras

Objetivo:

Criar, editar e acompanhar objetivos financeiros.

---

# Requisitos Não Funcionais

- Mobile-first.
- Interface simples e intuitiva.
- Linguagem acessível.
- Tempo de resposta inferior a 3 segundos.
- Proteção de dados do usuário.
- Experiência compatível com Design Universal.
- Acessibilidade compatível com padrões WCAG.
- Design inclusivo para diferentes perfis de usuários.

---

# Validação Inicial

## Hipótese

Usuários preferem registrar movimentações financeiras por conversa em vez de preencher formulários tradicionais.

## Teste

Realizar entrevistas e testes com 5 a 10 usuários.

Solicitar o registro de receitas e despesas utilizando apenas o chat.

## Métricas

- Tempo para registrar uma transação.
- Facilidade percebida.
- Taxa de retorno ao aplicativo.
- Precisão da classificação automática.
- Compreensão das informações apresentadas.

---

# Entregável Esperado da IA

Gerar:

- Arquitetura do MVP.
- Estrutura de navegação.
- Fluxos de usuário.
- Componentes de interface.
- Modelo de dados.
- Protótipo navegável.
- Estratégia de validação inicial.

## Tom de Comunicação

- Educativo.
- Simples.
- Acolhedor.
- Inclusivo.
- Adequado para iniciantes em educação financeira.
```

---

## Reflexão

### O que funcionou bem?

O refinamento do PRD previamente feito no Copilot ajudou muito a gerar uma aplicação mais alinhada aos objetivos do projeto.

### O que não funcionou como o esperado?

Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações realizadas já foram suficientes para compreender melhor o processo de construção assistida por IA.

### O que aprendi sobre conversar com IAs?

Aprendi que a qualidade das respostas está diretamente ligada à qualidade das instruções fornecidas. Quanto mais clareza, contexto e detalhes forem apresentados, melhores são os resultados obtidos.

---

## Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo é aprender a pensar junto com a IA, transformando ideias em produtos reais e utilizando a tecnologia como uma extensão do processo criativo.

Cada interação é um experimento: quanto mais clara for a intenção, mais relevante tende a ser o resultado obtido.
