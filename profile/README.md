# Manual do Hackathon Overnight 🌙💻


## 🗺️ Mapa do Evento

⏰ *Timer disponível no telão para acompanhamento das etapas*

| Horário        | Atividade                           | Detalhes                                                                 |
|----------------|-------------------------------------|--------------------------------------------------------------------------|
| **19h30-21h**  | **Abertura Institucional**          | • História do Garrafa no Mar<br>• Explicação dos desafios                |
| **21h-22h**    | **Formação de Squads + Planejamento** | • Divisão de times<br>• Definição de escopo e tecnologias               |
| **22h-10h**    | **Coding Sprint** (12h de dev)      | • Implementação com mentoria técnica<br>• *Check-ins a cada 3h no Discord* |
| **10h-11h**    | **Preparação de Apresentações**     | • Documentação técnica<br>• Pitch e ajustes finais no MVP               |
| **11h-12h**    | **Demo Day & Avaliação Final**      | • Apresentações de 10min por squad<br>• Critérios técnicos e criatividade |


> **Nota:** Tempos de apresentação serão ajustados conforme número de squads

---

## 🏆Critérios de Avaliação

### 🤝 Colaboração

* Ser comunicativo com o seu e os demais squads
* **Uso do** Discord:
  * `#geral` para **colaborar com outros squads**
  * `#squad-X` para discussões internas do squad
* **Sincronizações obrigatórias** a cada 3 horas (20h, 23h, 02h, 05h, 08h)
  * **Check-ins de 10 minutos** por squad no canal de voz designado.

### 💡 **Criatividade**

* Soluções não óbvias para os problemas propostos
* Interface intuitiva e acessível

### 📁 Versionamento

* **1 Repositório GitHub por squad**:
  * Deve conter: `README.md` com documentação clara dentro das pastas (ex.: `frontend/`, `backend/`)
* **Padrão de commits**: 
  * Conventional Commits
* **Histórico de Contribuição**
  * Todos os membros devem ter **commits** no repositório

### 🧼 **Qualidade do Código**

* Código modularizado
* Tratamento de erros
* Separação de responsabilidades na implementação

### 🚀 **Entrega Funcional**

* Entrega que atende aos casos de uso
* Funcionalidades **core** do desafio implementadas

---

## 👥 Dinâmica dos Squads

### 🔀 Formação de Times

1. Auto-organização inicial dos participantes
2. Eleição de **Tech Lead** em cada squad

### ✅ Responsabilidades do Lead

* Gerenciar fluxo de trabalho do squad
* Garantir comunicação com outros squads
* Mediar decisões técnicas

---

## 🎯 Desafios Técnicos

### 📋 Stack Recomendada

* NextJS (Front)
* NestJS (Back)
* SQLite + Prisma (Banco) `Dica: Configuração simplificada`

### ⚠️ Regras Gerais

* Desafios serão sorteados no início do evento
* Uso da stack recomendada é obrigatório
* Integrações externas devem seguir especificações de cada desafio

---

### 🧩 Desafio 1: Sistema de Pagamentos (Payment)

#### 📌 Stack Obrigatória

```markdown
- **Frontend (NextJS)**: 
  - Checkout
  - Gestão de cofres
  - Fluxo de pagamentos
- **Backend (NestJS)**:
  - Processamento de filas
  - Gestão de assinaturas
  - API de cobranças
- **Banco**: SQLite + Prisma
```

#### 🔗 Integrações

```markdown
- Efipay APIs (Pix/Cobranças)
- Simulação de ambiente produtivo para pagamentos
```

#### 🛠️ Ferramentas

```
- REST Client / Postman / Insominia
- Dados fake para testes (contas de consumo)
```

> **Detalhamento completo**: [README do Desafio Payment](github-link)

---

### 🧩 Desafio 2: Sistema de Tagging com IA

#### 📌 Stack Obrigatória

```markdown
- **Frontend (NextJS)**:
  - Cadastro de teses
  - Dashboard de tags
- **Backend (NestJS)**:
  - API de classificação
  - Gestão de modelos
- **Banco**: SQLite + Prisma
```

#### 🤖 Integração AI

```
- Vercel AI SDK
- API Token AI (qualquer uma)
```

#### ✨ Funcionalidades-Chave

```
- Geração automática de tags
- Sistema de sugestão contextual
- Histórico de classificações
```

> **Detalhamento completo**: [README do Desafio Tagging AI](github-link)

---

## ⚡ Dicas Cruciais

1. Mantenham o `main` sempre estável
2. Documentem decisões técnicas no README (front ou back)
3. Testem integrações críticas primeiro
4. Priorizem MVP funcional sobre features complexas

*Boa sorte, hackers! O futuro tech-for-good começa agora!* 🚀

---
