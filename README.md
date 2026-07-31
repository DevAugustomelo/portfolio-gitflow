# 💻 Projeto Portfólio - Demonstração de Gitflow

Este projeto é um portfólio profissional responsivo desenvolvido para consolidar os fundamentos de versionamento colaborativo utilizando o modelo de ramificação **Gitflow** e boas práticas de código moderno.

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico**: Estruturação limpa utilizando tags nativas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3 Moderno**: Arquitetura baseada em Propriedades Customizadas (Variáveis CSS), Layout responsivo fluido com **CSS Grid** e alinhamentos com **Flexbox**.
- **Design**: Estilização com blocos de contraste (Dark Mode localizado) e efeitos interativos de elevação nos cartões de projetos.

---

## 🔄 Fluxo de Versionamento (Gitflow)

O projeto simulou o cenário real de desenvolvimento de software do mercado de trabalho, utilizando a extensão CLI do Git Flow para automatizar as seguintes ramificações:

1. **`main`**: Armazena estritamente o código estável e homologado de produção.
2. **`develop`**: A branch principal de integração do dia a dia da equipe.
3. **`feature/`**: Ramificações isoladas criadas para desenvolver seções específicas sem interferir no trabalho dos outros desenvolvedores.
   - `feature/estrutura-base`
   - `feature/secao-perfil`
   - `feature/galeria-projetos`
4. **`release/`**: Ramificação temporária para congelamento de código, preparação de testes e publicação da versão **`v1.0.0`** com geração automática de Tags.

---

## 🤝 Práticas de Trabalho em Equipe

- **Conventional Commits**: Mensagens padronizadas no imperativo indicando a semântica da alteração (ex: `feat:`, `chore:`, `docs:`).
- **Code Review**: Abertura de **Pull Requests (PRs)** direcionados para a branch `develop`, exigindo a revisão e aprovação antes da integração do código.

