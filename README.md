
# 🏦 WW Bank & Support - Sistema Financeiro Inteligente

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![Tech](https://img.shields.io/badge/tech-HTML5%20%7C%20TailwindCSS%20%7C%20JavaScript-orange.svg)

O **WW Bank & Support** é uma plataforma Web responsiva focada em **Gestão Financeira, Acompanhamento de Investimentos e Suporte ao Cliente**. Diferente dos aplicativos bancários tradicionais, o foco principal da aplicação é a **Orientação de Gastos Seguros (Indicador WW)** e o **Suporte Inteligente via Chat/Tickets**.

---

## 🌟 Principais Funcionalidades

### 💡 1. O Conceito & Limite de Gastos Seguros (WW)
A grande inovação do app é a fórmula que calcula quanto o usuário pode gastar mensalmente sem impactar o seu patrimônio acumulado:
$$\text{Limite WW} = \text{Lucro dos Investimentos} + (\text{Renda Mensal} \times \% \text{Liberada})$$
* **Exemplo Prático:** Se o seu patrimônio rende **R$ 800,00/mês** e você libera **20% da sua renda** (ex: 20% de R$ 12.000 = R$ 2.400), o app calcula que você tem **R$ 3.200,00** para gastar com total segurança no mês!

---

### 💼 2. Gestão Completa de Carteira de Investimentos
* **Diversificação Ativa:** Distribuição de patrimônio entre Tesouro Direto/Renda Fixa, FIIs, Ações, Criptomoedas e Poupança.
* **Operações de Mercado:** Botões de **Aporte (Comprar)** e **Resgate (Vender)** de ativos em tempo real com atualização imediata dos rendimentos.
* **Cálculo Realista:** Rentabilidade calculada proporcionalmente ao percentual individual de cada categoria da carteira.

---

### 💬 3. Suporte ao Cliente & Assistente Virtual
* **Chat de Orientação com IA:** Assistente virtual inteligente integrado que analisa em tempo real os dados da sua conta para responder dúvidas sobre aportes, rendimentos e orçamento.
* **Gestão de Chamados (Tickets):** Formulário integrado para criação, envio e visualização de chamados técnicos com sistema de status.

---

### ⚙️ 4. Outras Recursos
* **Simulador de Evolução Patrimonial:** Calculadora de juros compostos para projeção de acúmulo de capital a longo prazo.
* **Modo Privacidade:** Ocultação rápida de valores e saldos com um único clique no botão de olho.
* **Sessão & Persistência Local:** Salvamento instantâneo via `localStorage` com opção de **Logout / Novo Cadastro** para reconfiguração completa dos dados a qualquer instante.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e acessível.
* **Tailwind CSS (CDN):** Estilização moderna e layout completamente responsivo (*Mobile-First*).
* **JavaScript Vanilla (ES6+):** Lógica do app, cálculos financeiros dinâmicos e persistência via `localStorage`.
* **FontAwesome:** Ícones de interface.

---

## 🚀 Como Executar o Projeto

Como o aplicativo foi desenvolvido dentro da arquitetura **Single-File (Arquivo Único)**, não é necessário instalar o Node.js ou rodar gerenciadores de pacote (`npm` / `yarn`).

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/ww-bank-support.git
   ```
2. **Navegue até a pasta do projeto:**
   ```bash
   cd ww-bank-support
   ```
3. **Abra o arquivo `index.html` em qualquer navegador moderno:**
   * Basta dar dois cliques no arquivo `index.html` ou arrastá-lo para dentro do Chrome, Firefox, Edge ou Safari.

---

## 📁 Estrutura do Arquivo

```text
├── index.html     # Aplicação completa (Estrutura, Design e Lógica JS)
└── README.md      # Documentação oficial do projeto
```

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p center>Desenvolvido para simplificar sua vida financeira com segurança e inteligência! 🚀</p>
