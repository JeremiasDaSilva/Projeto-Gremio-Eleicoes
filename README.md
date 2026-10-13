# 🎓 Grêmio Escolar - Sistema de Gestão de Eleições e Eventos

> **ETEC de Cidade Tiradentes** — 1° Módulo do curso Técnico em Desenvolvimento de Sistemas (2026)

O **Grêmio Escolar** é um sistema web desenvolvido para centralizar, organizar e gerenciar as atividades e os processos eleitorais do Grêmio Estudantil das Escolas Técnicas Estaduais (ETEC - Centro Paula Souza).

---

## 📌 Sobre o Projeto

O objetivo principal da aplicação é digitalizar o processo eleitoral estudantil e facilitar o acesso dos alunos às novidades, propostas e eventos organizados pelo Grêmio.

### 👥 Autor e Alunos Integrantes
* **Alex Braian Condori Limachi**
* **Jeremias Alves da Silva Soares**
* **Ryan Guilherme Silva Pires**

---

## 🚀 Funcionalidades Principais

### 🎓 Módulo do Aluno
* **Cadastro e Login:** Autenticação segura por meio do RM (Registro de Matrícula).
* **Consulta de Chapas:** Visualização das chapas concorrentes e seus respectivos integrantes/propostas.
* **Votação Online:** Sistema seguro que garante o registro de **apenas um voto por aluno** por eleição.
* **Mural de Eventos:** Consulta aos eventos organizados pelo Grêmio.
* **Interatividade:** Publicação de comentários nas páginas de eventos.

### 🛡️ Módulo do Administrador (Gerenciador)
* **Gestão de Alunos:** Cadastro, consulta, edição e exclusão de registros de alunos.
* **Gestão de Chapas e Integrantes:** Cadastro das chapas eleitorais e vinculação dos alunos aos seus cargos.
* **Gestão de Eleições:** Abertura, configuração e controle do período das votações.
* **Gestão de Eventos:** Publicação e controle de eventos e atividades escolares.

---

## 🛠️ Regras de Negócio Importantes

* **RN-01 (Unicidade do RM):** Cada RM está vinculado a apenas um cadastro de aluno.
* **RN-04 (Voto Único):** O aluno pode votar apenas 1 (uma) vez em cada eleição.
* **RN-05 (Voto em Chapa):** O voto é computado para a chapa como um todo, não para candidatos individuais.
* **RN-06 e RN-11 (Integrantes):** Apenas alunos cadastrados podem compor uma chapa, e cada aluno só pode integrar a mesma chapa uma única vez.
* **RN-12 (Acesso Restrito):** Painel administrativo exclusivo para perfis autenticados como **Gerenciador**.

---

## 📐 Artefatos da Documentação

A documentação completa do projeto conta com os seguintes artefatos modelados:

1. **Descrição detalhada dos Casos de Uso (CSU-01 a CSU-12)**
2. **Diagramas de Casos de Uso (Geral, Aluno e Administrador)**
3. **Requisitos Funcionais ($RF-01$ a $RF-12$) e Não Funcionais ($RNF-01$ a $RNF-08$)**
4. **Regras de Negócio ($RN-01$ a $RN-12$)**
5. **Matriz de Rastreabilidade de Requisitos**

---

## 📊 Matriz de Rastreabilidade Resumida

| Requisito Funcional | Caso de Uso Associado | Regra de Negócio Vinculada |
| :--- | :--- | :--- |
| **RF-01** (Cadastro Aluno) | `CSU-01` | `RN-01` |
| **RF-02** (Login Aluno) | `CSU-02` | `RN-02` |
| **RF-04** (Votação) | `CSU-04` | `RN-03`, `RN-04`, `RN-05`, `RN-08` |
| **RF-06** (Comentários) | `CSU-06` | `RN-10` |
| **RF-07 / RF-08** (Login Admin & Gestão Alunos) | `CSU-07`, `CSU-08` | `RN-12` |
| **RF-10** (Cadastro Integrantes) | `CSU-10` | `RN-06`, `RN-11` |

---

## 💻 Tecnologias e Metodologia

* **Modelagem:** UML (Diagramas de Casos de Uso e Fluxogramas de Navegação)
* **Padrão de Documentação:** Normas ABNT / Centro Paula Souza (CPS)
* **Instituição:** ETEC de Cidade Tiradentes - Centro Paula Souza