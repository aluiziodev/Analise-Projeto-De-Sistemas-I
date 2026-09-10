# Histórias de Usuário - Plataforma de Comunidade da LEGO
 
## Épicos e Objetivos

- **Épico 1 - Comunidade e Perfil:** Fornecer identidade do usuário e espaços comunitários para interação.

- **Épico 2 - Marketplace (Troca, Compra e Venda):** Habilitar negociação entre usuários. 
- **Épico 3 - Projetos:** Permitir criação, documentação e colaboração em projetos de construção.
- **Épico 4 - Eventos:** Suportar organização e participação em encontros presenciais. 
- **Épico 5 - Painel Administrativo / BI:** Fornecer visão analítica e controles administrativos. 
- **Épico 6 - Arquitetura Agnóstica:** Modelar o sistema sem acoplamento com a marca.

Cada história segue o formato **Como [persona], eu quero [ação], para que [benefício]**, com Título, Prioridade, Pontos. As histórias respeitam o princípio **INVEST** (Independentes, Negociáveis, Valiosas, Estimáveis, Pequenas e Testáveis).
 
**Escala de prioridade:** 
- Alta (MVP)
- Média (MVP ou Fase 2)
- Baixa (Fase 2)

**Escala de pontos:** Fibonacci (1, 2, 3, 5, 8, 13), quanto maior, mais complexidade/incerteza.

---
 
## Épico 1 - Comunidade e Perfil
 
### E1-US01: Cadastro e login
**Como** visitante da plataforma, **eu quero** me cadastrar e fazer login, **para que** eu possa acessar as funcionalidades da comunidade com uma identidade própria.
**Prioridade:** Alta
**Pontos:** 3

### E1-US02: Perfil com histórico
**Como** usuário da plataforma, **eu quero** ter um perfil que mostre meu histórico de projetos, eventos e reputação, **para que** outros usuários confiem em mim para trocar, vender ou organizar encontros.
**Prioridade:** Alta
**Pontos:** 3

### E1-US03: Criar comunidade própria
**Como** usuário da plataforma, **eu quero** criar uma comunidade temática ou local, **para que** eu possa reunir pessoas com interesses em comum (ex: cidade, tema de construção, faixa etária).
**Prioridade:** Alta
**Pontos:** 5
### E1-US04: Comunidades oficiais da marca
**Como** administrador da LEGO, **eu quero** criar e disponibilizar comunidades oficiais pré-definidas, **para que** os usuários já encontrem espaços de referência assim que entram na plataforma.
**Prioridade:** Média
**Pontos:** 3

### E1-US05: Comunicação dentro da comunidade
**Como** membro de uma comunidade, **eu quero** publicar e ler mensagens/posts dentro dela, **para que** eu possa me comunicar com outros membros sobre projetos, trocas e eventos.
**Prioridade:** Alta
**Pontos:** 5

---
 
## Épico 2 - Marketplace (Troca, Compra e Venda)
 
### E2-US01: Anunciar peça ou set
**Como** colecionador , **eu quero** anunciar peças ou sets para venda ou troca, **para que** outros usuários possam encontrá-los e negociar comigo.
**Prioridade:** Alta
**Pontos:** 5

### E2-US02: Buscar e negociar peça
**Como** colecionador, **eu quero** buscar uma peça específica e entrar em contato com quem a anuncia, **para que** eu consiga comprá-la ou trocá-la diretamente com outro colecionador.
**Prioridade:** Alta
**Pontos:** 5

### E2-US03: Avaliar transação
**Como** colecionador que concluiu uma troca ou compra, **eu quero** avaliar a outra parte da transação, **para que** a reputação dela reflita seu histórico de confiabilidade.
**Prioridade:** Alta
**Pontos:** 3

### E2-US04: Montar carrinho a partir de uma lista de peças
**Como** construtor, **eu quero** informar a lista de peças que preciso para um projeto, **para que** o sistema monte automaticamente um carrinho de compra com os anúncios disponíveis que atendam essa lista.
**Prioridade:** Média
**Pontos:** 8

 
---
 
## Épico 3 - Projetos
 
### E3-US01: Criar projeto
**Como** creator, **eu quero** criar um projeto de construção, **para que** eu possa documentar e compartilhar minha ideia com a comunidade.
**Prioridade:** Alta
**Pontos:** 5

### E3-US02: Colaborar em projeto
**Como** construtor, **eu quero** contribuir em um projeto criado por outra pessoa, **para que** possamos construir algo maior juntos.
**Prioridade:** Média
**Pontos:** 5

### E3-US03: Ranking de projetos
**Como** construtor, **eu quero** ver um ranking dos projetos mais populares, **para que** eu me inspire nos projetos mais bem avaliados pela comunidade.
**Prioridade:** Baixa
**Pontos:** 3

### E3-US04: Referenciar gerador externo de lista de peças
**Como** creator, **eu quero** que meu projeto referencie a lista de peças gerada por uma ferramenta externa já existente, **para que** eu não precise recriar manualmente essa lista.
**Prioridade:** Média
**Pontos:** 5


---
 
## Épico 4 - Eventos
 
### E4-US01: Criar evento
**Como** Organizador de evento, **eu quero** criar um evento presencial, **para que** eu possa organizar um encontro com outros membros da comunidade.
**Prioridade:** Alta
**Pontos:** 5

### E4-US02: Confirmar presença em evento
**Como** usuário da plataforma, **eu quero** sinalizar que vou participar de um evento, **para que** o organizador saiba quantas pessoas esperar.
**Prioridade:** Alta
**Pontos:** 2

### E4-US03: Selo de evento oficial
**Como** administrador da LEGO, **eu quero** marcar um evento como oficial, **para que** os usuários identifiquem encontros endossados pela marca.
**Prioridade:** Baixa
**Pontos:** 2

### E4-US04: Ganho de credibilidade como organizador
**Como** organizador de evento, **eu quero** que minha credibilidade cresça conforme organizo eventos bem avaliados, **para que** minha reputação na plataforma reflita minha experiência.
**Prioridade:** Média
**Pontos:** 5
 
---
 
## Épico 5 - Painel Administrativo / BI 
 
### E5-US01: Visualizar locais mais ativos
**Como** diretor de operações da LEGO, **eu quero** visualizar quais localidades têm mais eventos bem-sucedidos, **para que** eu possa decidir onde investir em ações e encontros oficiais.
**Prioridade:** Baixa
**Pontos:** 8

### E5-US02: Visualizar demanda de peças por região
**Como** diretor de operações da LEGO, **eu quero** visualizar quais peças são mais demandadas por localidade, **para que** eu possa embasar decisões de distribuição/estoque regional.
**Prioridade:** Baixa
**Pontos:** 8

 
### E5-US03: Gerenciar comunidades oficiais pelo painel
**Como** administrador da LEGO, **eu quero** gerenciar comunidades oficiais pelo painel de administrador, **para que** eu não dependa da equipe técnica para manter esse conteúdo atualizado.
**Prioridade:** Baixa
**Pontos:** 3

---
 
## Épico 6 - Arquitetura Agnóstica 
 
### E6-US01: Modelar entidades desacopladas da marca
**Como** arquiteto do sistema, **eu quero** que comunidade, evento, projeto e marketplace sejam modelados sem acoplamento direto à marca LEGO, **para que** o mesmo framework possa futuramente ser reaproveitado por outra empresa/vertical de colecionáveis.
**Prioridade:** Alta
**Pontos:** 3

 
---
 
## MVP Sugerido
 
| # | História | Pontos |
|---|---|---|
| E1-US01 | Cadastro e login | 3 |
| E1-US02 | Perfil com histórico | 3 |
| E1-US03 | Criar comunidade própria | 5 |
| E1-US05 | Comunicação dentro da comunidade | 5 |
| E2-US01 | Anunciar peça ou set | 5 |
| E2-US02 | Buscar e negociar peça | 5 |
| E2-US03 | Avaliar transação | 3 |
| E3-US01 | Criar projeto | 5 |
| E4-US01 | Criar evento | 5 |
| E4-US02 | Confirmar presença em evento | 2 |
| E6-US01 | Modelar entidades desacopladas da marca | 3 |
| **Total MVP** | | **44 pts** |
 
 
As histórias de prioridade Média e Baixa ficam sugeridas para Fase 2.
 
---
 
