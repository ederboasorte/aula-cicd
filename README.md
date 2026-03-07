# AULA 1 - Fundamentos de CI/CD


## 🎯 Objetivos de Aprendizado

Ao final desta aula, você será capaz de:
- ✅ Entender a arquitetura básica de CI/CD
- ✅ Escrever workflows em YAML para GitHub Actions
- ✅ Criar pipelines de CI completos com múltiplos jobs
- ✅ Analisar e debugar logs de execução
- ✅ Comparar Jenkins e GitHub Actions
- ✅ Entender opções de deploy na AWS
- ✅ Escolher a ferramenta certa para cada cenário

## 🚀 Como Usar Este Material

### Opção 1: Fork (Recomendado)
1. Clique em **Fork** no canto superior direito
2. Clone seu fork: `git clone https://github.com/SEU-USUARIO/fiap-dclt-aula01.git`
3. Siga os passos dos vídeos

### Opção 2: Clone Direto
```bash
git clone https://github.com/PROFESSOR/fiap-dclt-aula01.git
cd fiap-dclt-aula01
```

## 🛠️ Pré-requisitos

- Conta no GitHub
- Git instalado
- Node.js 18+ (para testes locais)
- Docker (opcional, para testes locais)
- AWS Learner Lab (para deploy na AWS)

## 📚 Tecnologias Utilizadas

- **Node.js 18** - Runtime JavaScript
- **Express.js** - Framework web
- **Jest** - Framework de testes
- **GitHub Actions** - CI/CD
- **Jenkins** - CI/CD alternativo
- **Docker** - Containerização
- **AWS** - Cloud (ECR, ECS)

## 🧪 Testar Localmente

```bash
# Instalar dependências
cd app
npm install

# Executar testes
npm test

# Executar com coverage
npm test -- --coverage

# Iniciar aplicação
npm start

# Testar API
curl http://localhost:3000/health
curl http://localhost:3000/api/todos
```

## 📖 Documentação Adicional

### 📹 Guias dos Vídeos
- [VIDEO-1.1-PASSO-A-PASSO.md](VIDEO-1.1-PASSO-A-PASSO.md) - Fundamentos e YAML
- [VIDEO-1.2-PASSO-A-PASSO.md](VIDEO-1.2-PASSO-A-PASSO.md) - Pipeline CI Completo
- [VIDEO-1.3-PASSO-A-PASSO.md](VIDEO-1.3-PASSO-A-PASSO.md) - Jenkins vs GitHub Actions

## 🤝 Contribuindo

Este é um material educacional. Sugestões e melhorias são bem-vindas via Pull Requests!

## 📄 Licença

MIT License - Sinta-se livre para usar este material para aprendizado.

---

**Aula 1 - Fundamentos de CI/CD**
