🌤️ ClimaAgora 

O ClimaAgora é uma aplicação web desenvolvida em Angular para consulta e monitoramento de informações meteorológicas em tempo real, oferecendo uma interface simples, rápida e intuitiva para os usuários acompanharem os dados do clima.

---

  Equipe de Desenvolvimento & Responsabilidades

-  Gabriela Guedes — Estruturação de Páginas e Rotas 
-  Maria Maezia — Consumo de API & HttpClient 
-  Raissa Licar — Tratamento de Dados com Pipes
-  João Guilherme — Camada de Serviço / Service 
-  Maria Luíza Lopes — Diretivas Personalizadas e Estruturais 
-  Dafny Barbosa — Navegação Dinâmica e Parâmetros de Rota 

---

 Problema e Público-Alvo

- Problema: Dificuldade de acesso rápido, claro e sem poluição visual a previsões meteorológicas atualizadas. 
- Público-Alvo: Pessoas em geral (trabalhadores, estudantes e viajantes) que precisam consultar o clima diariamente de forma prática para o planejamento da rotina.

---

  Solução e Funcionalidades

O ClimaAgora centraliza os dados meteorológicos de diversas cidades por meio de integração com API pública, apresentando as informações de forma dinâmica:
-  Busca por Cidade: Consulta direta ao clima de qualquer região.
-  Navegação com Parâmetro de Rota: Transição de página enviando a cidade selecionada via URL.
-  Informações em Tempo Real: Exibição de temperatura, sensação térmica, umidade e vento.
-  Interface Responsiva: Design adaptado para telas mobile e desktop.

---

 Escopo do MVP (1ª Entrega)

- **Entregue no MVP:**
  - Aplicação Angular funcional composta por 2 páginas.
  - Consumo assíncrono de API externa de clima com método `GET`.
  - Tratamento visual de dados com Pipes nativos e customizados.
  - Renderização condicional e listagem com diretivas (`@if`, `@for`).
- **Desenvolvimento Futuro:**
  - Histórico de buscas salvas no `localStorage`.
  - Geolocalização automática do usuário via GPS.
  - Alertas climáticos e mapa interativo de previsão estendida.

---

 Tecnologias Utilizadas

- Framework: Angular (v17+)
- Linguagens:TypeScript, HTML5, CSS3
- Comunicação/Estado: RxJS, `HttpClient`
- API Externa: OpenWeatherMap API (ou equivalente)
- Controle de Versão: Git e GitHub

---

  Análise de Viabilidade

O projeto é altamente viável e sustentável. A escolha do ecossistema Angular permitiu a criação de componentes reutilizáveis, serviços isolados e tipagem forte com TypeScript, garantindo facilidade de manutenção, boa performance e cumprimento do escopo dentro do prazo.

---

📅 Cronograma, Riscos e Respostas

| Risco / Dificuldade | Impacto | Resposta da Equipe |

| Instabilidade ou limite de requisições da API | Médio | Tratamento de erros no `Service` e feedbacks visuais com `@if` |
| Configuração de rotas e parâmetros | Baixo | Uso de `ActivatedRoute` e `Router` do Angular |
| Conflitos de merge no Git entre a equipe | Médio | Uso de branches individuais por funcionalidade e code review antes do merge |

---

 🚀 Como Executar o Projeto

 Pré-requisitos
- [Node.js](https://nodejs.org/) instalado.
- [Angular CLI](https://angular.io/cli) instalado globalmente (`npm install -g @angular/cli`). 
 
