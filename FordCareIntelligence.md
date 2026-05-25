# 🚗 FordCare Intelligence

> Plataforma inteligente de retenção e fidelização no pós-venda Ford.

---

# 📌 Sobre o Projeto

O **FordCare Intelligence** é uma solução corporativa desenvolvida para o Challenge FIAP 2026, com foco em retenção de clientes no pós-venda automotivo.

O projeto utiliza:

* Inteligência Artificial preditiva
* Gestão estratégica de leads
* Dashboard executivo
* Aplicação Mobile em React Native
* APIs REST documentadas com Swagger
* Segurança corporativa com JWT, RBAC e HTTPS/TLS

A proposta da solução é identificar clientes com risco de evasão da rede autorizada Ford e gerar ações estratégicas para aumentar fidelização, relacionamento e retenção.

---

# 🎯 Desafio Escolhido

O grupo escolheu o desafio relacionado à:

## Retenção de clientes no pós-venda Ford

O problema abordado envolve a perda de clientes após revisões, manutenções e relacionamento com concessionárias.

Muitas empresas automotivas enfrentam dificuldades em:

* identificar clientes com risco de abandono
* manter relacionamento contínuo
* converter oportunidades comerciais em fidelização
* monitorar indicadores estratégicos em tempo real

A solução proposta utiliza IA preditiva simulada para classificar o risco de evasão dos clientes e gerar leads estratégicos para atuação da equipe comercial.

---

# ✅ Funcionalidades Implementadas

## 🔐 Autenticação e Segurança

* Login corporativo
* Autenticação JWT
* Controle RBAC
* Proteção de rotas
* Armazenamento seguro de token
* Tratamento global de exceções
* Auditoria e logs
* Integração Swagger/OpenAPI

---

## 📊 Dashboard Executivo

* Quantidade total de clientes
* Quantidade de leads
* Clientes com alto risco
* Novos leads estratégicos
* Distribuição de risco em gráfico
* Resumo executivo automatizado

---

## 👥 Gestão de Clientes

* Listagem de clientes
* Visualização detalhada
* Exibição de veículo monitorado
* Dados estratégicos do cliente
* Score preditivo
* Classificação de risco

---

## 🤖 IA Preditiva

* Simulação de IA para classificação de risco
* Classificação:

  * LOW
  * MEDIUM
  * HIGH
* Score preditivo
* Geração automática de recomendação
* Atualização de classificação com IA

---

## 📈 Gestão de Leads

* Criação de leads estratégicos
* Conversão de leads
* Status comerciais
* Controle de prioridade
* Observações estratégicas
* Dashboard de leads

---

## 📚 APIs REST

* Backend Spring Boot
* Endpoints REST
* Swagger/OpenAPI
* Estrutura DTO + Services + Repositories
* PostgreSQL

---

# 👨‍💻 Integrantes do Grupo

| Nome         | RM |
| ------------ | -- |
| Luan Oralndelli Ramos | 554747 |
| Arthur Bobadilla Franchi | 555056 |
| Jorge Luiz Silva Santos | 554418 |


---

# ⚙️ Tecnologias Utilizadas

## 📱 Mobile

* React Native
* Expo
* Expo Router
* React Navigation
* Axios
* React Native Chart Kit
* React Native SVG

---

## 🖥️ Backend

* Java 21
* Spring Boot
* Spring Security
* JWT
* Swagger/OpenAPI
* JPA/Hibernate
* PostgreSQL

---

## 🔐 Segurança

* JWT Authentication
* RBAC
* HTTPS/TLS
* Tratamento seguro de erros
* Logs de auditoria
* Validação de entrada

---

## 🐳 Infraestrutura

* Docker
* Docker Compose

---

# 🧠 Estrutura do Projeto

## 📁 Estrutura Mobile

```bash
src/
 ├── components/
 ├── routes/
 ├── screens/
 ├── services/
 ├── storage/
 ├── theme/
```

---

## 📁 Estrutura Backend

```bash
src/main/java/
 ├── controller/
 ├── dto/
 ├── entity/
 ├── repository/
 ├── service/
 ├── security/
 ├── exception/
```

---

# 🔄 Integrações Realizadas

## 📡 Mobile ↔ Backend

A aplicação mobile consome APIs REST desenvolvidas em Spring Boot utilizando Axios.

As principais integrações incluem:

* Login JWT
* Dashboard executivo
* Listagem de clientes
* Detalhamento de cliente
* IA preditiva
* Gestão de leads

---

## 📚 Swagger

O projeto possui documentação automática das APIs utilizando Swagger/OpenAPI.

Endpoints disponíveis:

* /auth/login
* /customers
* /customers/{id}
* /insights/dashboard
* /predictions/classify
* /leads
* /recommendations/{customerId}
* /privacy/customers/{id}/anonymize

---

# 🏗️ Decisões Técnicas

## 📌 React Native + Expo

Escolhido pela rapidez de desenvolvimento, compatibilidade mobile e facilidade de prototipação.

---

## 📌 Spring Boot

Escolhido pela robustez corporativa, segurança e escalabilidade.

---

## 📌 PostgreSQL

Banco relacional utilizado para armazenar:

* clientes
* leads
* classificações
* recomendações
* auditorias

---

## 📌 JWT + RBAC

Implementados para garantir autenticação segura e controle de permissões.

---

## 📌 Arquitetura em Camadas

O backend foi estruturado utilizando:

* Controllers
* Services
* Repositories
* DTOs
* Entities

Essa abordagem melhora:

* organização
* manutenção
* escalabilidade
* desacoplamento

---

# 🚀 Como Rodar o Projeto

# 📱 Mobile

## Pré-requisitos

* Node.js
* NPM
* Expo CLI
* Android Studio ou Expo Go

---

## Clone o projeto

```bash
git clone LINK_DO_REPOSITORIO
```

---

## Entre na pasta

```bash
cd fordcare-mobile
```

---

## Instale as dependências

```bash
npm install
```

---

## Execute o projeto

```bash
npx expo start
```

---

# 🖥️ Backend

## Pré-requisitos

* Java 21
* Maven
* PostgreSQL

---

## Executar

```bash
./mvnw spring-boot:run
```

---

# 📷 Demonstração Visual

# 📱 Tela de Login

> Inserir print da tela.

---

# 📊 Dashboard Executivo

> Inserir print da tela.

---

# 👥 Gestão de Clientes

> Inserir print da tela.

---

# 📄 Detalhe do Cliente

> Inserir print da tela.

---

# 🤖 IA Preditiva

> Inserir print da tela.

---

# 📈 Gestão de Leads

> Inserir print da tela.

---

# 📚 Swagger / APIs REST

> Inserir print do Swagger.

---

# 🎥 Demonstração em Vídeo

## Link do Pitch

```txt
INSERIR LINK DO VÍDEO
```

---

# 🔥 Diferenciais da Solução

* IA preditiva aplicada ao pós-venda
* Gestão estratégica de leads
* Dashboard executivo em tempo real
* Arquitetura corporativa
* Segurança com JWT/RBAC
* APIs REST documentadas
* Estrutura escalável
* Aplicação mobile funcional

---

# 📈 Roadmap Futuro

Com mais tempo, o grupo pretende implementar:

* IA real utilizando Machine Learning
* Integração com CRM Ford
* Notificações push
* Integração com WhatsApp
* Analytics avançado
* Monitoramento em tempo real
* Painel web administrativo
* Hospedagem cloud
* Docker completo em produção
* Monitoramento observability

---

# 🛡️ Qualidade e Compliance

O projeto foi desenvolvido considerando:

* segurança corporativa
* boas práticas REST
* tratamento seguro de erros
* organização arquitetural
* padronização de código
* experiência do usuário
* documentação técnica

---

# 📌 Conclusão

O FordCare Intelligence entrega uma proposta moderna de retenção e fidelização no pós-venda automotivo, utilizando inteligência preditiva, dashboards estratégicos, gestão de leads e arquitetura corporativa escalável.

A solução demonstra o potencial da integração entre tecnologia, dados e experiência do cliente para aumentar competitividade e retenção no setor automotivo.
