# 🚀 Teste Técnico - Desenvolvedor Backend Jr

## 📋 Descrição

Este teste técnico tem como objetivo avaliar suas habilidades em desenvolvimento backend com **Node.js**. Você deverá criar uma API RESTful para gerenciamento de produtos de estoque, demonstrando conhecimentos em arquitetura de software, boas práticas de desenvolvimento e organização de código.

O desafio foi projetado para simular um cenário real de desenvolvimento, onde você precisará implementar uma solução completa que demonstre sua capacidade de:

- **Arquitetar soluções**: Organizar código de forma escalável e manutenível
- **Implementar funcionalidades**: Desenvolver operações CRUD completas
- **Validar dados**: Garantir integridade e segurança das informações
- **Tratar erros**: Implementar tratamento robusto de exceções
- **Documentar**: Criar documentação clara e profissional

## 🎯 Objetivo

Desenvolver uma API RESTful completa para gerenciamento de produtos de estoque, implementando operações CRUD com validações adequadas, tratamento de erros e estrutura organizada seguindo as melhores práticas de desenvolvimento backend.

### 🎯 **Objetivos Específicos:**

1. **Funcionalidade Completa**: Implementar todas as operações CRUD para produtos
2. **Arquitetura Limpa**: Separar responsabilidades em controllers, services, models e routes
3*Validação Robusta**: Garantir integridade dos dados de entrada
4**Tratamento de Erros**: Implementar middleware de erro centralizado5*Documentação Profissional**: README claro e instruções de setup6 **Código Limpo**: Seguir boas práticas e convenções de nomenclatura

## 📊 Critérios de Avaliação

A avaliação será baseada nos seguintes critérios, totalizando **100s** para os requisitos obrigatórios:

| Critério | Pontos | Descrição Detalhada |
|----------|--------|---------------------|
| **Funcionalidade** | 30 Implementação correta de todas as operações CRUD (Create, Read, Update, Delete) com endpoints funcionais |
| **Arquitetura** | 25 | Estrutura organizada seguindo padrões MVC com separação clara entre controllers, routes, services e models |
| **Validações** | 15 | Validações robustas nas requisições, incluindo tipos de dados, campos obrigatórios e regras de negócio |
| **Tratamento de Erros** | 10ware de tratamento de erros implementado com respostas padronizadas |
| **Documentação** |10aro e profissional com instruções de setup e execução |
| **Código Limpo** | 10| Boas práticas de desenvolvimento, legibilidade, nomenclatura consistente e organização do código |

### 📋 **Detalhamento dos Critérios:**

#### **Funcionalidade (30 pontos)**
- ✅ Todos os endpoints CRUD implementados e funcionais
- ✅ Respostas HTTP corretas (200201, 4004
- ✅ Dados persistidos corretamente no banco de dados
- ✅ Operações de listagem, busca, criação, atualização e exclusão

#### **Arquitetura (25 pontos)**
- ✅ Separação clara de responsabilidades
- ✅ Controllers apenas para receber requisições e retornar respostas
- ✅ Services para lógica de negócio
- ✅ Models para interação com banco de dados
- ✅ Routes organizadas e bem estruturadas

#### **Validações (15 pontos)**
- ✅ Validação de campos obrigatórios
- ✅ Validação de tipos de dados
- ✅ Validação de regras de negócio (preço > 0 quantidade >= 0)
- ✅ Mensagens de erro claras e informativas

#### **Tratamento de Erros (10 pontos)**
- ✅ Middleware de erro centralizado
- ✅ Respostas de erro padronizadas
- ✅ Logs de erro adequados
- ✅ Tratamento de exceções não capturadas

#### **Documentação (10 pontos)**
- ✅ README profissional e completo
- ✅ Instruções de setup claras
- ✅ Exemplos de uso da API
- ✅ Documentação de endpoints

#### **Código Limpo (10tos)**
- ✅ Nomenclatura consistente
- ✅ Código legível e bem comentado
- ✅ Estrutura de arquivos organizada
- ✅ Seguindo convenções do Node.js/Express

## 🏆 Itens Extras (Pontos Bônus)

Os itens extras demonstram conhecimentos avançados e podem somar até **+85 pontos** à sua nota final:

| Item | Pontos | Descrição Detalhada |
|------|--------|---------------------|
| **Testes Automatizados** | +15 | Testes unitários com Jest, cobrindo pelo menos80% do código |
| **Banco de Dados Real** | +10 | PostgreSQL, MongoDB ou MySQL com configuração adequada |
| **Docker** | +10 | Containerização completa com Dockerfile e docker-compose |
| **Swagger/OpenAPI** | +10 | Documentação interativa da API com exemplos de uso |
| **Deploy** | +15 | Aplicação deployada e acessível publicamente (Heroku, Vercel, Railway, etc.) |
| **TypeScript** | +10ementação completa com TypeScript e tipagem adequada |
| **Logs Estruturados** | +5 | Sistema de logs estruturados (Winston, Pino, Bunyan) |
| **Rate Limiting** | +5 | Limitação de requisições por IP/usuário |
| **Autenticação** | +10 Sistema de autenticação JWT com middleware de proteção |

### 🎯 **Detalhamento dos Itens Extras:**

#### **Testes Automatizados (+15 pontos)**
- ✅ Testes unitários com Jest
- ✅ Cobertura mínima de80do código
- ✅ Testes para controllers, services e models
- ✅ Mocks adequados para banco de dados
- ✅ Scripts de teste configurados (`npm test`, `npm run test:watch`)

#### **Banco de Dados Real (+10 pontos)**
- ✅ PostgreSQL, MongoDB ou MySQL configurado
- ✅ Conexão adequada com variáveis de ambiente
- ✅ Migrations/seeds (se aplicável)
- ✅ Configuração de produção

#### **Docker (+10 pontos)**
- ✅ Dockerfile otimizado
- ✅ docker-compose.yml para desenvolvimento
- ✅ Multi-stage builds (opcional)
- ✅ Volumes para persistência de dados

#### **Swagger/OpenAPI (+10 pontos)**
- ✅ Documentação interativa da API
- ✅ Exemplos de requisições e respostas
- ✅ Descrição detalhada de cada endpoint
- ✅ Interface visual para testar a API

#### **Deploy (+15ontos)**
- ✅ Aplicação acessível publicamente
- ✅ Configuração de produção
- ✅ Variáveis de ambiente configuradas
- ✅ Logs de aplicação disponíveis

#### **TypeScript (+10 pontos)**
- ✅ Configuração completa do TypeScript
- ✅ Tipagem adequada para todos os modelos
- ✅ Interfaces para requests/responses
- ✅ Configuração de build e desenvolvimento

#### **Logs Estruturados (+5 pontos)**
- ✅ Sistema de logs estruturado
- ✅ Diferentes níveis de log (info, warn, error)
- ✅ Formato JSON para logs
- ✅ Rotação de logs (opcional)

#### **Rate Limiting (+5 pontos)**
- ✅ Limitação de requisições por IP
- ✅ Configuração de janela de tempo
- ✅ Headers de rate limit nas respostas
- ✅ Tratamento adequado de limites excedidos

#### **Autenticação (+10 pontos)**
- ✅ Sistema de autenticação JWT
- ✅ Middleware de proteção de rotas
- ✅ Refresh tokens (opcional)
- ✅ Validação de tokens

## 📝 Requisitos Obrigatórios

### 🛠️ Stack Tecnológica

**Tecnologias Principais:**
- **Node.js** (versão 16 ou superior)
- **Express.js** (framework web)
- **Banco de dados**: SQLite, PostgreSQL, MongoDB, Firebase, ou arquivo local db.json (para fins didáticos)
- **dotenv** para gerenciamento de variáveis de ambiente

**Dependências Recomendadas:**
- `express` — Framework web principal
- `dotenv` — Gerenciamento de variáveis de ambiente
- `express-validator` — Validação de dados nas rotas
- `uuid` — Geração de identificadores únicos
- `cors` — Liberação de CORS para testes
- `helmet` — Segurança HTTP

**Dependências de Desenvolvimento:**
- `nodemon` — Hot reload para desenvolvimento
- `jest` — Testes automatizados (bônus)
- `supertest` — Testes de integração (bônus)

> **Observação:** Utilize sempre variáveis de ambiente para dados sensíveis e configuração do banco de dados. O uso de `.env` é obrigatório.

### 📦 Estrutura de Projeto Recomendada

Organize seu projeto seguindo o padrão abaixo para garantir escalabilidade e manutenibilidade:

```
src/
├── controllers/
│   └── ProductController.js
├── routes/
│   └── productRoutes.js
├── services/
│   └── ProductService.js
├── models/
│   └── Product.js
├── middlewares/
│   ├── errorHandler.js
│   └── validation.js
├── config/
│   └── database.js
└── app.js
```

> **Dica:** Separe claramente as responsabilidades de cada camada. Controllers devem apenas receber e responder requisições, services concentram a lógica de negócio, models cuidam da persistência e validação dos dados.

### Modelo de Dados - Produto

| Campo | Tipo | Obrigatório | Descrição |
|-------|------|-------------|-----------|
| `id` | string/uuid | ✅ | Identificador único (autogerado) |
| `nome` | string | ✅ | Nome do produto |
| `descricao` | string | ❌ | Descrição opcional do produto |
| `preco` | float | ✅ | Preço do produto (> 0) |
| `quantidade` | integer | ✅ | Quantidade em estoque (>= 0 |
| `criado_em` | timestamp | ✅ | Data de criação (autogerado) |

### Endpoints Obrigatórios

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| `GET` | `/api/products` | Listar todos os produtos |
| `GET` | `/api/products/:id` | Buscar produto por ID |
| `POST` | `/api/products` | Criar novo produto |
| `PUT` | `/api/products/:id` | Atualizar produto |
| `DELETE` | `/api/products/:id` | Deletar produto |

### Validações Obrigatórias
- Nome: obrigatório, string
- Preço: obrigatório, número positivo
- Quantidade: obrigatório, número inteiro >=0escrição: opcional, string

## ⚙️ Configuração e Execução

### Pré-requisitos
- Node.js 16 npm ou yarn
- Git

### Setup do Projeto

1. **Clone o repositório**
```bash
git clone <seu-repositorio>
cd <nome-do-projeto>
```

2. **Instale as dependências**
```bash
npm install
```
3*Configure as variáveis de ambiente**
```bash
cp .env.example .env
# Edite o arquivo .env com suas configurações
```

4. **Execute a aplicação**
```bash
# Desenvolvimento
npm run dev

# Produção
npm start
```

### Scripts Disponíveis
```json[object Object]  scripts": {
    start": "node src/app.js,dev": "nodemon src/app.js",
  test": jest,
 test:watch: "jest --watch  }
}
```

## 📁 Estrutura de Arquivos Esperada

```
├── README.md
├── package.json
├── .env.example
├── .gitignore
├── src/
│   ├── app.js
│   ├── controllers/
│   │   └── ProductController.js
│   ├── routes/
│   │   └── productRoutes.js
│   ├── services/
│   │   └── ProductService.js
│   ├── models/
│   │   └── Product.js
│   ├── middlewares/
│   │   ├── errorHandler.js
│   │   └── validation.js
│   └── config/
│       └── database.js
├── tests/ (opcional)
└── docs/ (opcional)
```

## 🗄️ Opções de Banco de Dados

### Opção 1: SQLite (Mais Simples)
- Arquivo local, sem configuração adicional
- Ideal para começar rapidamente

### Opção 2Firebase (Recomendado para Jr)
- Configuração simples
- Documentação excelente
- Gratuito para testes

### Opção 3: PostgreSQL/MongoDB (Mais Pontos)
- Bancos de dados reais
- Configuração mais complexa
- Pontuação extra na avaliação

## 📤 Como Entregar

1. **Crie um repositório no GitHub**
   - Nome: `teste-backend-jr-seu-nome`
   - Descrição: "Teste técnico Backend Jr - API de Produtos2Desenvolva a aplicação**
   - Implemente todos os requisitos obrigatórios
   - Adicione itens extras para pontuação bônus
3*Documente no README**
   - Instruções de setup claras
   - Exemplos de uso da API
   - Screenshots (opcional)
4 **Envie o link**
   - Repositório público no GitHub
   - Commit final com mensagem: "Entrega final - Teste Backend Jr"

## ⏰ Prazo de Entrega

**Tempo sugerido:48oras**

- **Mínimo**: 24 horas para implementação básica
- **Ideal**: 48 horas para implementação completa + extras
- **Máximo**: 72oras (com justificativa)

## 🎯 Dicas para Sucesso

1. **Comece simples**: Implemente primeiro os requisitos básicos
2. **Teste cada endpoint**: Use Postman ou Insomnia
3. **Organize o código**: Separe responsabilidades claramente4*Documente**: README claro é fundamental5 **Valide dados**: Implemente validações robustas
6. **Trate erros**: Middleware de erro é obrigatório

## 📞 Suporte

Em caso de dúvidas sobre o teste, entre em contato através do email fornecido no processo seletivo.

---

**Boa sorte! 🚀**

*Desenvolvido com ❤️ para avaliar talentos em Node.js* 
