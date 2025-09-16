# 🏟️ FIFA World Cup 26 – Booking & Match Planner

Uma aplicação web interativa para **planejamento de serviços (bookings)** e **associação de cenários a partidas da Copa do Mundo FIFA 2026™**.  
Permite navegar pelo catálogo de serviços, montar cenários customizados, visualizar valores, e relacionar cenários a partidas no calendário oficial do torneio.

---

## ✨ Funcionalidades

- **Catálogo de Bookings**
  - Importação automática de `bookings.csv`.
  - Filtro por Tipo, Subtipo, Código, Nome e Descrição.
  - Seleção de múltiplos itens com quantidades e cálculo de valores.
  - Criação, edição, renomeio e exclusão de **cenários**.

- **Cenários**
  - Salvos localmente (persistem entre visitas).
  - Sincronização opcional com **Supabase** → permite que todos os usuários vejam os cenários criados.
  - Resumo geral de custos por cenário.

- **Calendário de Partidas**
  - Baseado no **match schedule oficial** (M1 a M104).
  - Visualização por datas, com estádios e fases do torneio (GS, R32, R16, QF, SF, Bronze, Final).
  - Cada partida é clicável → permite associar cenários a jogos específicos.
  - Resumo de custos por partida e visão consolidada de todos os jogos.

- **Extras**
  - Suporte a fontes customizadas (`fonte.ttf` e `fontefina.ttf`).
  - Estilo escuro inspirado em branding esportivo (cores `#3f3e3f` e `#231f20`).
  - Layout responsivo.
