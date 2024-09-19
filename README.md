# **A.R.I.S.** – Artificial Response & Intrusion Security

O projeto **A.R.I.S.** consiste no desenvolvimento de uma **aplicação web distribuída** que combina **segurança de rede**, **inteligência artificial** e **gestão de dispositivos IoT** para monitorar e proteger redes domésticas inteligentes. O sistema se concentra na **detecção de intrusões em tempo real**, utilizando técnicas de **machine learning** e **ferramentas IDS (Snort ou Suricata)** para identificar comportamentos suspeitos. A plataforma inclui um **assistente virtual** (chatbot) que permite aos usuários interagir diretamente, receber notificações e executar comandos de segurança, como o bloqueio de dispositivos comprometidos.

---

## **Objetivo Geral**

O objetivo do **A.R.I.S.** é fornecer uma **plataforma de segurança inteligente e interativa**, permitindo que os usuários monitorem suas redes de maneira simplificada e automatizada, reagindo rapidamente a ameaças potenciais e mantendo controle sobre dispositivos IoT conectados. A aplicação é projetada para ser **escalável**, **segura** e fácil de usar, oferecendo suporte tanto para redes domésticas quanto para redes empresariais.

---

## **Objetivos Específicos**
- **Conforto do Usuário:** Promover um ambiente de interação agradável e eficiente para os utilizadores.
- **Comunicação Humanizada:** Garantir uma comunicação fluida, clara e profissional entre o sistema e o usuário, utilizando o chatbot.
- **Análise e Ação sobre Ameaças:** Detectar, analisar e agir automaticamente ou manualmente sobre potenciais ameaças à rede.
- **Compatibilidade de Dispositivos:** Permitir o monitoramento e controle de diversos dispositivos IoT presentes no ambiente.
- **Segurança Autónoma:** Oferecer um ambiente inteligente com **segurança autônoma**, utilizando inteligência artificial e respostas automatizadas.

---

## **Arquitetura do Sistema**

O **backend** gerencia toda a lógica de negócios, processamento de eventos de segurança e resposta a intrusões. Ele também se comunica com o **frontend**, que fornece uma **interface web intuitiva** onde os usuários podem monitorar o estado da rede e tomar decisões sobre a segurança dos dispositivos conectados. A aplicação suporta **operações CRUD** para gerenciamento de dispositivos IoT e logs de segurança, além de contar com um **sistema robusto de autenticação e autorização** para garantir acesso seguro.

A arquitetura do sistema é baseada em uma **infraestrutura distribuída**, onde cada componente (backend, frontend, IDS, chatbot, base de dados) é executado em máquinas ou containers independentes, garantindo escalabilidade e flexibilidade, possibilitando sua adaptação a diferentes cenários de uso.

---
`
## **Principais Funcionalidades**

1. **Monitoração de Rede:** 
   - Detecção de intrusões em tempo real utilizando **ferramentas IDS (Snort ou Suricata)** e **machine learning**.
   
2. **Assistente Virtual (Chatbot):**
   - Interação com o sistema por meio de um **chatbot**, que fornece o status da rede e sugestões de ações de segurança, além de notificar o usuário sobre eventos relevantes.
   
3. **Controle de Dispositivos IoT:**
   - Gestão e monitoramento de dispositivos conectados à rede, permitindo ações como **bloquear** dispositivos comprometidos ou **ajustar configurações**.
   
4. **Autenticação e Autorização:**
   - Implementação de um sistema robusto de autenticação e autorização, garantindo que apenas **usuários autenticados** e com **permissões adequadas** possam interagir com o sistema.

5. **Infraestrutura Distribuída:**
   - Cada componente do sistema é executado em máquinas ou **containers independentes**, garantindo **escalabilidade**, **disponibilidade** e **segurança** do sistema.
`
---
`
## **Tecnologias Utilizadas**

- **Frontend:** React / Vue.js / Angular, Chart.js / D3.js.
- **Backend:** Flask / Django (Python), APIs REST, WebSockets, Docker.
- **Detecção de Intrusões (IDS):** Snort / Suricata, Python, Machine Learning (Scikit-learn, TensorFlow, PyTorch).
- **Assistente Virtual (Chatbot):** Dialogflow / Rasa / IBM Watson, WebSockets.
- **IoT:** MQTT, paho-mqtt (Python).
- **Segurança:** JWT / OAuth 2.0, TLS/SSL.
- **Banco de Dados:** PostgreSQL / MySQL.
- **Infraestrutura:** Docker, Kubernetes (opcional), Prometheus / Grafana.
`
---

## **Contribuições das Disciplinas**

### 1. **Engenharia de Software**
   A disciplina de **Engenharia de Software** é fundamental para garantir o desenvolvimento e a organização do projeto, desde a concepção até a implementação. As contribuições incluem:
   - **Design da Arquitetura:** Modelagem da infraestrutura distribuída e organização dos componentes do sistema (frontend, backend, IDS, chatbot, base de dados) em containers independentes.
   - **Processo de Desenvolvimento:** Aplicação de práticas ágeis e engenharia de software para gerenciar o ciclo de vida do projeto, como a utilização de **SCRUM** ou **Kanban** para organização de tarefas.
   - **Implementação de Interfaces:** Desenvolvimento de interfaces web amigáveis e interativas utilizando **React**, **Vue.js** ou **Angular**.

### 2. **Sistemas Distribuídos**
   A disciplina de **Sistemas Distribuídos** é responsável pela divisão dos serviços do A.R.I.S. em máquinas ou containers independentes, garantindo que cada parte do sistema funcione de maneira distribuída e integrada. As contribuições incluem:
   - **Separação de Componentes:** Implementação de uma arquitetura de **microserviços** onde o backend, frontend, IDS e base de dados funcionam de forma independente e se comunicam via **APIs REST** e **WebSockets**.
   - **Orquestração e Escalabilidade:** Uso de ferramentas como **Docker** para a containerização dos serviços e **Kubernetes** para a orquestração e escalabilidade dos containers.
   - **Comunicação entre Serviços:** Garantir que os serviços distribuídos se comuniquem de forma segura e eficiente, mantendo a integridade dos dados e a robustez do sistema.

### 3. **Segurança Informática**
   A disciplina de **Segurança Informática** é crucial para a implementação de medidas de proteção contra ataques e a segurança dos dados e comunicações. As contribuições desta área incluem:
   - **Autenticação e Autorização:** Implementação de um sistema seguro de **autenticação e autorização** com **JWT (JSON Web Tokens)** ou **OAuth 2.0**, garantindo que apenas usuários autorizados possam acessar o sistema.
   - **Criptografia:** Utilização de **TLS/SSL** para proteger a comunicação entre o frontend e o backend, garantindo que os dados transmitidos sejam criptografados.
   - **Proteção de Dispositivos IoT:** Monitoramento e controle dos dispositivos conectados à rede, garantindo que dispositivos comprometidos possam ser isolados e suas comunicações protegidas.

### 4. **Inteligência Artificial**
   A disciplina de **Inteligência Artificial** contribui significativamente para a detecção de intrusões e a automação das respostas a eventos de segurança. As principais contribuições são:
   - **Detecção de Anomalias:** Implementação de **algoritmos de machine learning** para detectar padrões anômalos no tráfego de rede, utilizando ferramentas como **Scikit-learn**, **TensorFlow** ou **PyTorch**.
   - **Processamento de Linguagem Natural (NLP):** Desenvolvimento do **assistente virtual (chatbot)** usando técnicas de NLP, permitindo que o chatbot interaja com o usuário de maneira natural e forneça sugestões baseadas no estado da rede.
   - **Automação de Respostas:** Desenvolvimento de um sistema de resposta automática a ameaças, baseado em decisões geradas por algoritmos de IA, como o bloqueio de dispositivos ou o ajuste de configurações de rede.

---

## **Conclusão**
O projeto **A.R.I.S.** busca melhorar a segurança de ambientes IoT de forma eficiente, sem causar prejuízos ou atrasos na resolução de problemas. A aplicação oferece uma ferramenta **autônoma e amigável**, promovendo ambientes **tecnológicos mais confortáveis e seguros**, que atendem à crescente demanda da nova indústria, que é muitas vezes complexa e estressante. O **futuro da segurança em redes inteligentes** já está à porta, e o **A.R.I.S.** é uma solução voltada para enfrentar esses desafios de forma inovadora e eficaz.

