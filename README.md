<h1 align="center">Olá, eu sou o Edinei 👋</h1>

<p align="center">
  <b>Software Engineer · .NET Backend</b><br>
  Resolvendo problemas de negócio com sistemas confiáveis e fáceis de manter.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/edinei-ribeiro-0776a6271/"><img src="https://img.shields.io/badge/LinkedIn-Edinei%20Ribeiro-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Marília%2C%20SP-Brasil-2E7D32?style=for-the-badge" alt="Marília, SP">
</p>

---

### 🧑‍💻 Sobre mim

- 💼 Desenvolvedor backend .NET na **Breda's Sistemas**
- 🧱 Foco em **APIs**, **modelagem de domínio (DDD)**, **SQL** e **testes automatizados**

### 🛠️ Stack

<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge" alt="C#">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge" alt="AWS">
</p>

**Práticas:** DDD · Strategy & Factory · Testes unitários e de integração · Logs estruturados (Serilog)

---

### 🚀 Projeto em destaque

#### [🛒 PriceTracker](https://github.com/edineievr/PriceTracker)

Worker em **.NET 10** que monitora preços de peças de PC na **Kabum**, **Pichau** e **Terabyte** e avisa no **Telegram** quando o preço à vista cai.

- **Strategy + Factory**: cada plataforma tem sua estratégia de scraping, escolhida em tempo de execução. Adicionar uma loja nova não mexe no orquestrador
- **AngleSharp** para HTML estático e **Playwright** para páginas renderizadas via JavaScript
- Histórico de preços em **SQLite**, com cada consulta registrada
- Notificação desacoplada: dá para trocar o canal sem impacto no fluxo principal
- Testes com **NUnit**, incluindo integração contra as plataformas reais

<a href="https://github.com/edineievr/PriceTracker"><img src="https://img.shields.io/badge/Ver%20repositório-181717?style=for-the-badge&logo=github&logoColor=white" alt="Ver repositório"></a>

---

### 📫 Contato

Bora trocar ideia sobre .NET, arquitetura ou backend? Me chama no [LinkedIn](https://www.linkedin.com/in/edinei-ribeiro-0776a6271/).
