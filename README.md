# README.md

## CEPSmart
Aplicação web simples para consulta de CEP utilizando a API ViaCEP, com interface amigável, listagem de endereços e sistema de modais. O projeto foi estruturado de forma modular usando JavaScript puro, facilitando manutenção e expansão.

---

## Funcionalidades
- Consulta de CEP via API pública ViaCEP
- Validação simples de entrada do usuário
- Exibição dos dados retornados em uma lista dinâmica
- Controle de modais para visualização de detalhes
- Organização modular (Controllers, Services, Models)

---

## Estrutura do Projeto
```
proj-cepsmart
├── index.html
├── css/
│   ├── buttons.css
│   ├── modal.css
│   └── styles.css
├── js/
│   ├── controllers/
│   ├── models/
│   └── services/
└── README.md
```

---

## Tecnologias Utilizadas
- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **ViaCEP API**

---

## Como Executar
1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/proj-cepsmart.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd proj-cepsmart
   ```
3. Abra o arquivo `index.html` em seu navegador.

Não é necessário backend ou instalações adicionais.

---

## Organização do Código
### **Models**
- `address.js`: Representa um endereço retornado pela API.

### **Services**
- `request-service.js`: Faz requisições HTTP.
- `address-service.js`: Controla a lógica de busca e normalização de dados.
- Exceções customizadas em `exceptions/`.

### **Controllers**
- `form-controller.js`: Gerencia o formulário de busca.
- `list-controller.js`: Lista e manipula endereços retornados.
- `modal-controller.js`: Exibe dados em modal.
- `page-controller.js`: Integra os demais controllers.
