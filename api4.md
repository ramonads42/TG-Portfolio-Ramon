<div align="center">

# API 4 - (4º Semestre)
**Empresa Parceira:** TecSys <br>
**Projeto:** AdaTech - Automação de Instruções de Registro Aduaneiro

<img src="https://github.com/equipeAdalove/API-SEMESTRE4/blob/main/docs/assets/Banner%20-%20projeto.png?raw=true" alt="AdaTech" width="800">

</div>

---

**O Problema:** A TecSys enfrentava um problema operacional na elaboração manual de registros aduaneiros. O processo exigia que funcionários extraíssem dados técnicos de PDFs complexos e classificassem cada item conforme a tabela NCM. A falta de padronização gerava erros humanos frequentes, resultando em multas severas da Receita Federal e expondo dados sensíveis da empresa devido à ausência de uma camada de acesso controlada e auditável.

**A Solução:** Desenvolvemos a AdaTech, uma plataforma que utiliza um agente de IA (Ollama) integrado a um modelo de Machine Learning para automatizar a extração de dados e sugerir classificações fiscais precisas. O sistema centraliza o fluxo em uma interface web segura com autenticação robusta, permitindo que a equipe revise as informações antes da exportação final, garantindo conformidade legal e protegendo o histórico de processamento.

---

<div align="center">
  <video src="https://github.com/user-attachments/assets/f7dd8ed0-972f-4992-9278-dcad3be6500f" width="800" controls></video>
</div>

---

[Repositório do Projeto (AdaTech)](https://github.com/equipeAdalove/API-SEMESTRE4)


---

#### Tecnologias Utilizadas

* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" height="20" width="20"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" height="20" width="20"> **FastAPI & Python:** Framework de alta performance utilizado para construir a API e gerenciar o middleware de segurança e integração com IA.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" height="20" width="20"> **Scikit-learn & Joblib:** Utilizados para o pré-processamento de dados e carregamento do modelo de Machine Learning para predição de NCM.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" height="20" width="20"> **React & Context API:** Gestão de estado global para autenticação de usuários e proteção de rotas no front-end.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-plain.svg" height="20" width="20"> **PostgreSQL:** Banco de dados relacional responsável pela persistência segura de logs de auditoria e credenciais de usuários.
* <img src="./arquivos/mediaollama_logo.jpg" height="20" width="20"> **Ollama:** Integração de Large Language Models (LLMs) locais para a extração inteligente e normalização de dados dos PDFs.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" height="20" width="20"> **TypeScript:** Implementação de tipagem estrita no front-end para garantir a integridade dos dados manipulados na interface.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitejs/vitejs-original.svg" height="20" width="20"> **Vite:** Ferramenta de build utilizada para otimizar o ambiente de desenvolvimento e a performance da aplicação.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="20" width="20"> **Figma:** Utilizado para o design de interfaces (UI/UX) e prototipagem dos modos Light e Dark.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jira/jira-original.svg" height="20" width="20"> **Jira & Slack:** Ferramentas de gestão ágil e comunicação, garantindo o acompanhamento das Sprints e Backlog.
* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" height="20" width="20"> **Git:** Controle de versionamento e organização do fluxo de trabalho através de branches e Pull Requests.

---

#### Contribuições Pessoais
Neste projeto, minha atuação foi híbrida e focada em Segurança e Integração de Inteligência. Fui o responsável pela implementação do sistema de Autenticação **JWT** no backend, criando um middleware no **FastAPI** para proteger os endpoints de processamento de PDF. No frontend, desenvolvi o **AuthContext** e a lógica de proteção de rotas, garantindo o gerenciamento seguro da sessão e o fluxo de logout. 

Também colaborei na integração do serviço de predição de NCM utilizando Scikit-learn. Atuei no desenvolvimento da lógica inicial do serviço PredictNCMService, trabalhando no fluxo de carregamento de modelos treinados e no tratamento de descrições brutas para a sugestão automatizada de códigos fiscais, atuando em conjunto com o serviço de RAG do sistema.

---

#### Hard Skills
| Tecnologia/Metodologia | Nota | Proficiência |
| :--- | :---: | :--- |
| **FastAPI & Python** | 🟩 🟩 🟩 ⬜ ⬜ | Faço com ajuda |
| **Machine Learning Integration** | 🟩 🟩 ⬜ ⬜ ⬜ | Faço com ajuda |
| **React & Context API** | 🟩 🟩 🟩 ⬜ ⬜ | Faço com ajuda |
| **Segurança da Informação** | 🟩 🟩 🟩 ⬜ ⬜ | Faço com ajuda |

#### Soft Skills
| Habilidade | Descrição |
| :--- | :--- |
| **Pensamento Crítico** | Analisando a integração da IA, identifiquei que apenas a extração bruta de dados não seria suficiente para o modelo de negócio. Sugeri e ajudei a estruturar a lógica de predição via Scikit-learn como uma segunda camada de validação. |
| **Organização de Código** | Como o projeto unia múltiplos serviços (IA, Scraper e Auth), trabalhei na organização e padronização das rotas do FastAPI, o que facilitou a manutenção do código e a rastreabilidade de erros. |

---
<p align="center">
  <a href="./README.md">Início</a>
</p>
