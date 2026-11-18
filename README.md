<!-- Topo: nome e constelação de tecnologias, num céu só (assets/topo.svg) -->
<img width="100%" src="assets/topo.svg" alt="Cybelle Martins, full stack em formação. Constelação do que já sei: Java, Spring Boot, Spring Security, APIs REST, JUnit e Mockito, PostgreSQL, Flyway, HTML e CSS, Bootstrap e JavaScript. Aprendendo agora: React. No horizonte: TypeScript. Aberta a estágio." />


<p align="center">
  <a href="https://cybellesantos-byte.github.io/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio" /></a>
  <a href="mailto:cybellemartins11@gmail.com"><img src="https://img.shields.io/badge/E--mail-7c3aed?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" /></a>
</p>

---

## 👩‍💻 Sobre mim

Sou estudante do **4º período de Sistemas de Informação** na **UFPB, Campus IV** (Rio Tinto, PB).

**Antes do código, veio o balcão.** Sou técnica em Comércio, já estagiei na área e ajudo
na pastelaria da família. Foi lá que aprendi que um sistema só é bom quando resolve o
problema de quem está do outro lado. Por isso gosto de **entender a regra de negócio
antes de escrever a primeira linha**, e de conseguir explicar cada parte do que construo.

- 🎯 **Foco:** desenvolvimento **full stack**. Minha base é o backend com Java, e estou construindo o lado do frontend (JavaScript e React, depois TypeScript)

- 🧪 **Me importo com:** testes, segurança e operações que não podem dar errado (como dinheiro)

- 🧭 **Também me interessam:** modelagem de dados, ética em Engenharia de Software e uso responsável de IA

- 🌍 **Gosto de** projetos com impacto social e que apoiam a aprendizagem

---

## 🛠️ Ferramentas do dia a dia

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,postgres,docker,maven,git,github,githubactions,postman,idea,vscode,html,css,bootstrap,js&perline=8" alt="Java, Spring, PostgreSQL, Docker, Maven, Git, GitHub, GitHub Actions, Postman, IntelliJ, VS Code, HTML, CSS, Bootstrap, JavaScript" />
</p>

---

## 🚀 Projetos

<table width="100%"><tr><td>

### 🥟 Galo & Cia
**Gestão de pastelaria e peixaria** · projeto pessoal · ✅ **em uso real**

Nasceu de uma necessidade da minha família: tirar o controle do caderno. Hoje está no ar, com um painel interno e um cardápio para o cliente pedir pelo WhatsApp.

[![Testar a demo](https://img.shields.io/badge/Testar_a_demo-0f766e?style=for-the-badge&logo=githubpages&logoColor=white)](https://cybellesantos-byte.github.io/galo-e-cia-demo/) [![Ver o cardápio](https://img.shields.io/badge/Ver_o_card%C3%A1pio-c2410c?style=for-the-badge&logo=whatsapp&logoColor=white)](https://cybellesantos-byte.github.io/galo-e-cia-demo/cardapio.html) [![Ver o código](https://img.shields.io/badge/Ver_o_c%C3%B3digo-24292f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybellesantos-byte/galo-e-cia)

`Java 25` `Spring Boot` `PostgreSQL` `Flyway` `Testcontainers` `JavaScript` `Docker` `GitHub Actions`

<details>
<summary><b>Ver destaques</b></summary>

- **Cardápio público (sem login):** o cliente vê o que tem hoje, escolhe os itens, retirada ou entrega, Pix ou dinheiro, e toca em "Pedir pelo WhatsApp" com o pedido já escrito.
- **Painel interno (com login):** caixa do dia, vendas, despesas, repasses ao entregador e relatórios, no computador e no celular.
- **Qualidade:** 291 testes automatizados, com integração contra um PostgreSQL real, rodando sozinhos no GitHub Actions a cada mudança. O site só é publicado depois que todos passam.
- **Segurança:** login com perfis, proteção contra CSRF e cabeçalho CSP em toda resposta, com um teste que acusa qualquer tela fora da regra.
- **Aprendizado:** o escopo mudou várias vezes conforme eu entendia melhor o negócio.

<sub>A demo é toda fictícia: dá para vender, abrir e fechar o caixa e ver os relatórios. O pedido do cardápio só mostra a mensagem, não envia nada.</sub>

</details>

</td></tr></table>

<table width="100%"><tr><td>

### 🩺 Vitallis
**Gestão para profissionais autônomos da saúde** · projeto pessoal

Contas, pacientes, agendamentos e controle financeiro: cobranças, pagamentos, pacotes de sessões e créditos.

![Código privado](https://img.shields.io/badge/C%C3%B3digo_privado-6b7280?style=for-the-badge&logo=github&logoColor=white)

`Java 25` `Spring Boot` `Spring Security` `JWT (RSA)` `PostgreSQL` `Flyway` `Testcontainers`

<details>
<summary><b>Ver destaques</b></summary>

- **Multi-tenant:** cada profissional só enxerga os próprios dados, com controle de acesso por conta e papel.
- **Dinheiro sem erro:** transações garantem que um pagamento nunca fique registrado pela metade.

</details>

</td></tr></table>

<table width="100%"><tr><td>

### 📚 EDUPlanner
**Organizador de estudos** · projeto acadêmico em equipe

Organiza a vida acadêmica num lugar só: disciplinas, tarefas, eventos, anotações e um dashboard com o resumo dos estudos.

![Código privado](https://img.shields.io/badge/C%C3%B3digo_privado-6b7280?style=for-the-badge&logo=github&logoColor=white)

`Java 25` `Javalin` `Thymeleaf` `PostgreSQL` `JDBC` `JWT` `Docker` `GitHub Actions`

<details>
<summary><b>Ver destaques</b></summary>

- **Backend:** Javalin com páginas em Thymeleaf e acesso ao banco direto por JDBC (pool HikariCP).
- **Segurança:** login com JWT e senhas protegidas com BCrypt.
- **Testes e entrega:** JUnit, Mockito e testes HTTP de integração, com pipeline no GitHub Actions.

</details>

</td></tr></table>

<sub>🔒 Os projetos privados eu mostro numa conversa: abro o código e explico as decisões.</sub>

---

## 🦥 SLOTH: Liga Acadêmica de Ética em Engenharia de Software

Sou **Diretora de Pesquisa** da SLOTH, na UFPB Campus IV.

A liga tem foco em formação crítica, impacto social e **uso ético de IA no desenvolvimento de software**.

Organizo as leituras e discussões de artigos, as duplas de pesquisa e a comunicação com integrantes e professores.

---

## 🌱 Aprendendo agora

| | Estudando | Assuntos |
|---|---|---|
| ⚛️ | **React** | componentes, estado, hooks e consumo de APIs |
| ☕ | **Backend Java** | arquitetura, segurança e regras de negócio mais complexas |
| 🌳 | **Estruturas de dados** | árvores de busca, heaps, HeapSort e Skip List |

**Próximo passo:** TypeScript, para deixar o frontend mais seguro e conectá-lo ao meu backend em Java.

---

<p align="center">
  <i>"Um sistema bom é aquele que alguém consegue usar no dia mais corrido da semana."</i>
</p>

<img width="100%" src="assets/rodape.svg" alt="" />
