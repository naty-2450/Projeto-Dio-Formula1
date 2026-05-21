<div align="center">


# 🏎️ Formula 1 REST API

API REST desenvolvida com Node.js e TypeScript para listar dados de times e pilotos da Fórmula 1.

Projeto criado durante o bootcamp da **DIO (Digital Innovation One)**.

</div>

---

# ✨ Funcionalidades

- 🏁 Listar todos os times
- 👨‍✈️ Listar todos os pilotos
- 🔎 Buscar piloto por ID

---

# 🚀 Tecnologias Utilizadas

- ⚡ Node.js
- 🔷 TypeScript
- 🚄 Fastify
- 🌐 @fastify/cors
- 🛠️ TSX
- 📦 TSUP

---

# 📂 Estrutura do Projeto

```txt
src/
├── routes/
├── controllers/
├── services/
├── repositories/
├── models/
└── utils/
```

---

# 🌐 Endpoints da API

O servidor roda na porta **3333**.

| Método | Rota | Descrição |
|---|---|---|
| GET | `/teams` | Lista todos os times |
| GET | `/drivers` | Lista todos os pilotos |
| GET | `/drivers/:id` | Busca piloto por ID |

---

# 📄 Exemplos de Resposta

## 🏁 GET /teams

```json
{
  "teams": [
    {
      "id": 1,
      "name": "McLaren",
      "base": "Woking, United Kingdom"
    }
  ]
}
```

---

## 👨‍✈️ GET /drivers/1

```json
{
  "driver": {
    "id": 1,
    "name": "Max Verstappen",
    "team": "Red Bull Racing"
  }
}
```

---

# ⚙️ Instalação

## Clone o repositório

```bash
git clone https://github.com/seu-usuario/node-formula-1
```

## Entre na pasta

```bash
cd node-formula-1
```

## Instale as dependências

```bash
npm install
```

---

# ▶️ Executando o Projeto

## Desenvolvimento

```bash
npm run start:dev
```

## Modo Watch

```bash
npm run start:watch
```

## Gerar Build

```bash
npm run dist
```

## Executar Build

```bash
npm run start:dist
```

---

# 💻 Projeto feito para estudos

Projeto criado durante o bootcamp da **DIO (Digital Innovation One)** para praticar:

- APIs REST
- Node.js
- TypeScript
- Fastify
- Organização de rotas
- Estrutura em camadas
