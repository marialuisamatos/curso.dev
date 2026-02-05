# 🚀 Jornada TabNews: Do Zero ao Profissional

Este repositório é o registro fiel da minha evolução no [Curso.dev](https://curso.dev). Aqui, não estou apenas aprendendo a "codar", mas entendendo a arquitetura, a resiliência e os fundamentos que sustentam a internet.

> "Se você quer fabricar uma torta de maçã do zero, você deve primeiro inventar o universo." — Carl Sagan (citado no curso)

---

## 🧠 O que aprendi até agora

### 🏁 Dia 2: Onde tudo começa
* **Git vs GitHub:** Entendi que o Git é o motor de controle local (a ferramenta) e o GitHub é a plataforma social/remota (o serviço).
* **Repositórios:** A importância de guardar não apenas arquivos, mas o **histórico** de tudo o que foi feito.
* **Ambiente de Desenvolvimento:** Montei um setup resiliente no **Ubuntu (Linux)** focado em simplicidade e flexibilidade.

### 🛠️ Dia 3: A Fundação (Setup Técnico)
* **Docker:** Aprendi que no Linux ele roda "direto na máquina" (usando o Kernel), o que é muito mais performático que no Windows.
* **NVM (Node Version Manager):** Fundamental para alternar entre versões. Estou usando a `lts/hydrogen` (Node 18) para garantir paridade total com o projeto.
* **Next.js & React:** Instalação manual das versões exatas (`next@13.1.6`, `react@18.2.0`) para evitar conflitos e entender o papel de cada dependência.
* **Package-lock.json:** Entendi que ele serve para "congelar" as versões e garantir que o projeto rode igual em qualquer máquina.

### 🌐 Dia 4: Protocolos e Servidores
* **Cliente e Servidor:** Como a comunicação acontece através de protocolos (HTTP, TCP/IP).
* **Scripts NPM:** Aprendi por que precisamos do `npm run dev` e como ele localiza o Next.js dentro da `node_modules`.
* **Ambiente Local:** Configuração de pastas no Linux para evitar problemas de performance com o WSL.

### 📜 Dia 5: As Entranhas do Git
* **Snapshot vs Diff:** O Git tira "fotos" do projeto. Entendi como ele economiza espaço usando compressão e referências, em vez de apenas duplicar arquivos.
* **O Ciclo de Vida:** A diferença entre arquivos modificados, na *staging area* e commitados.

---

## 🏗️ Estrutura do Projeto



* **`pages/`**: Onde as rotas e componentes da interface ganham vida.
* **`package.json`**: O manifesto do projeto (comandos e dependências).
* **`.nvmrc`**: Garante que todos usem a mesma versão do Node.js.

---

## 🛠️ Tecnologias e Versões
| Ferramenta | Versão | Função |
| :--- | :--- | :--- |
| **Node.js** | `18.x (Hydrogen)` | Runtime Javascript |
| **Next.js** | `13.1.6` | Framework Fullstack |
| **React** | `18.2.0` | Biblioteca de UI |
| **Docker** | `Desktop` | Isolamento de serviços |

---

## 🚀 Como rodar o projeto localmente

1. **Versão do Node:**
   ```bash
   nvm install lts/hydrogen && nvm use lts/hydrogen

2. **Dependências:**
   ```bash
   npm install

3. **Desenvolvimento:**
   ```bash
   npm run dev     
