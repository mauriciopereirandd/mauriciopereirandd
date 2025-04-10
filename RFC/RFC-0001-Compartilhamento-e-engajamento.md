# RFC 001: Implementação de Reuniões para Compartilhamento de Conhecimento Técnico

| Metadados | |
|------------|-------------|
| **Autor** | mauriciopereirandd |
| **Status** | 📝 Rascunho |
| **Criado** | 2025-03-28 |
| **Última Atualização** | 2025-04-10 13:46:05 |
| **Versão** | 1.3 |

## 1. Resumo

Este documento propõe a implementação de um fórum recorrente para compartilhamento de conhecimento técnico entre as diferentes verticais de negócio da ndd.tech. O objetivo principal é melhorar a colaboração entre equipes, reduzir a rivalidade entre verticais e promover a troca de conhecimento técnico.

## 2. Motivação

### 2.1 Cenário Atual

Atualmente, as três verticais de negócios da ndd.tech operam de forma isolada, com pouca interação entre suas respectivas equipes de engenharia. Esta separação se manifesta não apenas entre verticais, mas também entre times/squads dentro da mesma vertical, criando múltiplos níveis de silos organizacionais.

### 2.2 Impactos dos Silos no Dia a Dia

Os silos técnicos têm impactado nossa organização de diversas formas concretas:

1. **Duplicação de Esforços**: Times desenvolvem soluções redundantes para problemas semelhantes.
   * *Exemplo*: Equipes de diferentes verticais implementaram três versões distintas de um serviço de autenticação, cada uma com suas próprias falhas e limitações.
   * *Exemplo*: Dentro da mesma vertical, dois squads criaram utilitários de validação de dados com funcionalidades quase idênticas.

2. **Inconsistência Técnica**: Abordagens divergentes para problemas similares.
   * *Exemplo*: Cada vertical adotou diferentes padrões de API REST, criando dificuldades para desenvolvedores que precisam trabalhar em múltiplos projetos.
   * *Exemplo*: Equipes utilizam bibliotecas e frameworks diferentes para resolver os mesmos tipos de problemas.

3. **Barreira de Conhecimento**: Experiências e aprendizados não são compartilhados.
   * *Exemplo*: Uma equipe enfrentou e solucionou um problema complexo de escalabilidade, mas outras equipes continuam enfrentando o mesmo problema por desconhecer a solução.
   * *Exemplo*: Boas práticas descobertas em um projeto não são propagadas para outros times.

4. **Rivalidade Improdutiva**: Competição em vez de colaboração.
   * *Exemplo*: Times são reconhecidos individualmente, sem incentivo para compartilhar soluções com outros grupos.
   * *Exemplo*: "Não foi inventado aqui" se tornou uma mentalidade comum, onde equipes resistem a adotar soluções de outras equipes.

### 2.3 Oportunidades Perdidas

A falta de visibilidade entre times resulta em:

1. **Talentos Subutilizados**: Desenvolvedores com experiência específica não têm oportunidade de contribuir em iniciativas relevantes de outras equipes.
   * *Exemplo*: Um desenvolvedor especialista em otimização de performance em uma vertical poderia resolver problemas críticos em outra, mas desconhece a necessidade.

2. **Problemas sem Resolução Eficiente**: Desafios técnicos persistem por mais tempo do que o necessário.
   * *Exemplo*: Uma equipe passou semanas tentando resolver um problema de integração que outra equipe já havia solucionado meses antes.

3. **Inovação Limitada**: Soluções criativas não se propagam pela organização.
   * *Exemplo*: Uma abordagem inovadora de testes automatizados desenvolvida por um squad permanece desconhecida para o resto da empresa.

### 2.4 Necessidade de Mudança

Esta proposta busca criar um mecanismo estruturado para fomentar a colaboração técnica e compartilhamento de conhecimento, semelhante ao conceito de guildas técnicas utilizado em várias organizações de tecnologia. Ao criar este fórum, oferecemos:

- Visibilidade das iniciativas técnicas entre todas as verticais e times
- Oportunidade para desenvolvedores contribuírem com soluções fora de suas equipes imediatas
- Plataforma para reconhecimento técnico além das fronteiras organizacionais
- Ambiente propício para disseminação de inovações e melhores práticas

## 3. Proposta Detalhada

### 3.1 Formato da Reunião

**Frequência:** Quinzenal  
**Duração:** 1 hora (máximo)  
**Participação:** Aberta a todos os membros técnicos, com pelo menos 2 representantes por vertical

### 3.2 Estrutura da Reunião

1. **Boas-vindas e Introdução (5 minutos)**
   - Recapitulação do propósito e regras da reunião

2. **Apresentações Técnicas (45 minutos total)**
   - Cada vertical apresenta um tema técnico (15 minutos por vertical)
   - Apresentações concisas e focadas
   - Inclui breve período para perguntas após cada apresentação

3. **Discussão Aberta Integrada (5 minutos)**
   - Discussão focada em possíveis sinergias entre os temas apresentados

4. **Encerramento (5 minutos)**
   - Resumo dos principais pontos discutidos
   - Anúncio dos próximos temas e apresentadores

### 3.3 Melhores Práticas

- Manter o foco em conteúdo técnico, evitando discussões de negócios ou métricas
- Criar ambiente psicologicamente seguro para compartilhamento de desafios
- Documentar e disponibilizar as apresentações após as reuniões
- Utilizar linguagem acessível, evitando jargões específicos de cada vertical
- Incentivar perguntas e feedback construtivo

### 3.4 Critérios de Sucesso

- Participação consistente das três verticais
- Aumento de colaborações técnicas entre equipes de diferentes verticais
- Feedback positivo dos participantes via pesquisas
- Redução mensurável de soluções técnicas duplicadas
- Exemplos concretos de contribuições entre times/verticais

## 4. Implementação

### 4.1 Cronograma Proposto

| Período | Atividade |
|---------|-----------|
| 10-24 Abril 2025 | Compartilhamento desta RFC com líderes técnicos para feedback |
| 24-30 Abril 2025 | Refinamento e aprovação final da proposta |
| 01-08 Maio 2025 | Reunião de lançamento e introdução do conceito |
| 15 Maio 2025 | Primeira reunião formal |
| Agosto 2025 | Revisão do formato após as primeiras 6 sessões |

### 4.2 Recursos Necessários

- Canal dedicado no Teams/Slack para comunicação contínua
- Repositório compartilhado para armazenamento de apresentações e documentos
- Calendário compartilhado para agendamento das reuniões
- Ferramenta para pesquisas de feedback

## 5. Alternativas Consideradas

- **Eventos técnicos trimestrais mais extensos:** Rejeitado por não promover interação contínua
- **Fóruns online apenas:** Rejeitado por falta de engajamento síncrono
- **Rotação forçada de membros entre equipes:** Rejeitado por impacto potencial na produtividade
- **Uma única apresentação por reunião:** Considerado, mas optou-se pelo formato múltiplo para maior engajamento entre verticais

## 6. Questões em Aberto

- Estratégia para garantir participação equilibrada das três verticais
- Processo para avaliar o impacto real na colaboração entre equipes
- Definição do processo de seleção de temas em cada vertical
- Como incentivar desenvolvedores a oferecer ajuda em iniciativas fora de suas equipes

## 7. Referências

- Modelo de Guildas Técnicas do Spotify
- Práticas de Compartilhamento de Conhecimento em Organizações Ágeis
- RFC 2119 - Palavras-chave para uso em RFCs para Indicar Níveis de Requisito

## 8. Anexos

### Anexo A: Modelo de Agenda para Primeira Reunião

| Atividade | Duração | Responsável |
|-----------|---------|-------------|
| Boas-vindas e introdução ao conceito | 5 min | Organizador |
| Apresentação técnica - Vertical 1 | 15 min | Representante V1 |
| Apresentação técnica - Vertical 2 | 15 min | Representante V2 |
| Apresentação técnica - Vertical 3 | 15 min | Representante V3 |
| Discussão aberta integrada | 5 min | Facilitador |
| Definição dos próximos temas e encerramento | 5 min | Organizador |

### Anexo B: Modelo para Registros de Temas Apresentados

| Data | Vertical | Tema | Apresentador | Link Materiais |
|------|----------|------|--------------|----------------|
| 15/05/2025 | Vertical 1 | [Título da Apresentação] | [Nome] | [Link] |
| 15/05/2025 | Vertical 2 | [Título da Apresentação] | [Nome] | [Link] |
| 15/05/2025 | Vertical 3 | [Título da Apresentação] | [Nome] | [Link] |

---

*Documento gerado por: mauriciopereirandd em 2025-04-10 13:46:05*