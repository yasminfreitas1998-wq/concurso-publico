# Comandos do Framework

Este documento define todos os comandos que podem ser executados pela IA.

Sempre que um comando for solicitado, a IA deverá utilizar todas as configurações padrão definidas no projeto, solicitando ao usuário apenas os parâmetros que não estiverem previamente definidos.

---

# Simulado Prova

## Objetivo

Gerar um simulado completo que reproduza, da forma mais fiel possível, a experiência da prova oficial da banca.

## Configuração padrão

- 100 questões;
- distribuição proporcional ao edital;
- estilo FGV;
- casos contextualizados;
- alta densidade interpretativa;
- textos motivadores quando aplicável;
- diagramação padrão FGV;
- gabarito ao final;
- correção comentada ao final.

## Exemplo de uso

Executar

Simulado Prova

---

# Comunicação Revisão

## Objetivo

Gerar um simulado de revisão voltado exclusivamente para Comunicação Social, priorizando aprendizagem, revisão e fixação do conteúdo.

## Configuração padrão

- 60 questões;
- apenas Comunicação Social;
- cobertura integral do edital;
- questões inéditas;
- maior volume de questões;
- menor densidade textual;
- foco em revisão e fixação.

## Exemplo de uso

Executar

Comunicação Revisão

---

# Lista de Questões

## Objetivo

Gerar listas de questões conforme os parâmetros informados pelo usuário.

Caso nenhum parâmetro seja informado, utilizar as configurações padrão do projeto.

## Exemplo de uso

Executar

Lista de Questões

---

# Revisão

## Objetivo

Gerar uma revisão personalizada baseada nos erros do último Simulado Prova.

Quando existir histórico de desempenho, priorizar automaticamente os assuntos com menor desempenho.

## Exemplo de uso

Executar

Revisão

---

# Flashcards

## Objetivo

Gerar flashcards dos assuntos solicitados ou dos assuntos com menor desempenho registrados no histórico do candidato.

## Exemplo de uso

Executar

Flashcards

---

# Mapa Mental

## Objetivo

Gerar um mapa mental estruturado do assunto solicitado.

## Exemplo de uso

Executar

Mapa Mental

---

# Resumo

## Objetivo

Gerar um resumo objetivo, organizado e direcionado para revisão de concurso.

## Exemplo de uso

Executar

Resumo

---

# Cronograma

## Objetivo

Gerar ou atualizar o cronograma de estudos considerando o método definido pelo projeto.

## Plano Semanal

### Domingo

**Simulado Prova**

Objetivo:

Simular fielmente a prova da FGV.

Características:

- 100 questões;
- divididas em dois blocos de 50 questões;
- contextualização densa;
- casos práticos;
- diagramação padrão FGV;
- correção comentada ao final.

---

### Segunda

Estudo de legislação.

---

### Terça

Revisão personalizada dos erros do último Simulado Prova.

---

### Quarta

**Comunicação Revisão**

Objetivo:

Revisão intensiva do edital de Comunicação Social.

Características:

- 60 questões;
- apenas Comunicação Social;
- maior volume;
- questões mais objetivas;
- cobertura completa do edital.

---

### Quinta

50 questões oficiais da FGV.

---

### Sexta

- 15 minutos de revisão dos erros do último Simulado Prova;
- 35 questões oficiais da FGV.

---

### Sábado

12 questões oficiais de Raciocínio Lógico.

---

# Engenharia Reversa da Prova

## Objetivo

Analisar provas anteriores da banca, identificando padrões de cobrança, estrutura das questões, temas recorrentes, estilo de redação, nível de dificuldade e perfil do examinador.

## Exemplo de uso

Executar

Engenharia Reversa da Prova

---

# Análise de Desempenho

## Objetivo

Analisar o histórico de desempenho do candidato, identificar padrões de erro, evolução por disciplina e definir prioridades de estudo.

Quando existir histórico consolidado, sugerir automaticamente o próximo conteúdo a ser estudado.

## Exemplo de uso

Executar

Análise de Desempenho


# Próximo Estudo

## Objetivo

Analisar automaticamente o histórico de desempenho do candidato e definir qual deve ser o próximo estudo, respeitando o cronograma semanal e priorizando os assuntos com maior probabilidade de aumentar o desempenho na prova.

## Exemplo de uso

Executar

Próximo Estudo
