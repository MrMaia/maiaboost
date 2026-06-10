<div align="center">
  <img src="assets/imgs/logo.png" alt="Maia Boost Logo" width="180"/>

  <h1>⚔️ Maia Boost</h1>
  <p><strong>O serviço de Elo Boost mais acessível e confiável para League of Legends</strong></p>

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-orange?style=for-the-badge"/>
</div>

---

> ⚠️ **Este projeto está em desenvolvimento.** Algumas páginas e funcionalidades ainda não foram finalizadas. Veja o [Roadmap](#-roadmap) para acompanhar o que está planejado.

---

## 📸 Preview

| Página Inicial | Elojob |
|---|---|
| ![Home](assets/imgs/index.png) | ![Elojob](assets/imgs/elojob.png) |

---

## 🚀 Sobre o Projeto

**Maia Boost** é um site de serviços de **Elo Boost para League of Legends**, desenvolvido com foco em conversão, visual impactante e experiência de compra fluida.

O site apresenta os serviços oferecidos, depoimentos de clientes, FAQ detalhado e uma página de configuração de pedido interativa — onde o usuário seleciona o elo atual, elo desejado, tipo de fila e visualiza o preço em tempo real.

---

## ✨ Funcionalidades

- 🎮 **Landing Page** completa com hero section, cards de serviços, depoimentos e FAQ
- ⚔️ **Página de Elojob** interativa com:
  - Seleção de elo atual e elo desejado (Ferro → Desafiante)
  - Imagens dos ranks atualizadas dinamicamente ao selecionar
  - Seleção de fila (Solo/Duo ou Flex)
  - Cálculo de preço em tempo real
  - Exibição de desconto e botão de compra
- 📱 **Design responsivo** (mobile-first com Bootstrap 5)
- 🌑 **Tema dark** com gradientes roxo/dark e destaque em vermelho
- 💳 Suporte a múltiplos meios de pagamento (Pix, MercadoPago, crédito em até 18x)

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura das páginas |
| CSS3 | Estilização customizada com gradientes e animações |
| Bootstrap 5 | Grid, componentes e responsividade |
| Bootstrap Icons | Ícones de interface |
| JavaScript (Vanilla) | Lógica de troca de imagem de rank e cálculo de preço |
| Google Fonts (Montserrat) | Tipografia |

---

## 📁 Estrutura do Projeto

```
maiaboost/
├── index.html             # Página principal (landing page)
├── elojob.html            # Página de pedido de Elojob
├── README.md
└── assets/
    ├── css/
    │   ├── index.css      # Estilos da página principal
    │   └── elojob.css     # Estilos da página de elojob
    ├── js/
    │   └── trocaimg.js    # Script auxiliar
    └── imgs/
        ├── logo.png
        ├── index.png      # Screenshot da página inicial
        ├── elojob.png     # Screenshot da página de elojob
        ├── rank-1.png → rank-9.png   # Emblemas de rank
        ├── astronauta-1.png
        ├── poro-jinx.png
        ├── mp.png, pix.png           # Ícones de pagamento
        └── ...
```

---

## 🎮 Serviços Oferecidos

| Serviço | Descrição |
|---|---|
| **Elojob** | Um jogador de alto nível joga na sua conta até o elo desejado |
| **Duo Boost** | Você joga junto com um booster Mestre/Desafiante |
| **MD10** | 80% de vitórias garantidas nas 10 partidas de posicionamento |
| **Vitórias** | Pacotes de vitórias individuais |
| **Maestria** | Acúmulo de pontos de maestria em campeões |
| **Coach** | Sessões de coaching com jogadores de alto nível |
| **Manutenção de Elo** | Manutenção do elo atual sem queda de divisão |
| **Clash** | Elojob e Duo Boost para torneios Clash |

---

## ⚙️ Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/maiaboost.git
   ```

2. Abra a pasta do projeto e clique em `index.html` para abrir no navegador.

> Não há necessidade de servidor ou dependências — é um projeto 100% front-end estático.

---

## 📋 Roadmap

### Páginas pendentes
- [ ] Duo Boost
- [ ] MD10
- [ ] Vitórias
- [ ] Maestria
- [ ] Coach
- [ ] Manutenção de Elo
- [ ] Clash (Elojob e Duo Boost)

### Funcionalidades planejadas
- [ ] Integração com gateway de pagamento (Pix / MercadoPago)
- [ ] Painel de área do cliente
- [ ] Sistema de cadastro de boosters
- [ ] Backend para gerenciamento de pedidos
- [ ] Chat em tempo real com o booster

### Extras / Opcionais no pedido (a implementar na página de serviços)

Opções adicionais que o cliente poderá adicionar ao contratar:

| Extra | Descrição |
|---|---|
| **Taxa MMR** | Boost com ajuste de MMR |
| **Fila Smurf / MMR Bufado** | Serviço em conta smurf ou com MMR elevado |
| **Chat Offline** | Booster joga com o chat desativado |
| **Posição de Feitiços** | Escolha da posição do Flash e demais feitiços |
| **Rotas Específicas** | Booster joga apenas nas rotas escolhidas pelo cliente |
| **Serviço Prioritário** | Atendimento com prioridade máxima na fila |
| **Vitória Extra** | Adição de vitórias extras ao pedido |
| **Booster Favorito** | Escolha de um booster específico da equipe |
| **Campeões Específicos** | Booster joga apenas com os campeões selecionados |
| **Maestria** | Aumento de pontos de maestria nos campeões escolhidos |
| **Horários Restritos** | Jogo apenas nos horários definidos pelo cliente |
| **Stream Online** | Acompanhamento do serviço em tempo real via stream |
| **Redução de KDA** | Booster joga de forma discreta para não chamar atenção |
| **Redução de Prazo** | Entrega acelerada do pedido |
| **Serviço Solo** | Serviço garantido em fila solo |

---

## 📄 Aviso Legal

> League of Legends é uma marca registrada da Riot Games, Inc. A Maia Boost não é afiliada, associada ou endossada pela Riot Games, Inc. Todos os direitos autorais, marcas e imagens pertencem a seus respectivos proprietários.

---

<div align="center">
  <p>Feito com ❤️ por <strong>Maia Studio</strong></p>
  <p>Copyright © Maia Boost 2024 – 2025</p>
</div>
