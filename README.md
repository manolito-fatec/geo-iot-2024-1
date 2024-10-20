<h1 align="center">🌍📡 GEO-IOT 🚀</h1>
<h3 align="center">Repositório dedicado ao versionamento do projeto API do quarto semestre de Banco de Dados.</h3>

---

## 📌 Tópicos
- [👥 Membros](https://github.com/manolito-fatec/geo-iot-2024-1?tab=readme-ov-file#-team-members)
- [📋 Requisitos](https://github.com/manolito-fatec/geo-iot-2024-1?tab=readme-ov-file#-requisitos)
- [📈 Product Backlog](https://github.com/manolito-fatec/geo-iot-2024-1?tab=readme-ov-file#-product-backlog)
- [📚 Documentação](https://github.com/manolito-fatec/geo-iot-2024-1?tab=readme-ov-file#-documentação)
- [💻 Tecnologias](https://github.com/manolito-fatec/geo-iot-2024-1?tab=readme-ov-file#-tecnologias)

---

# 👥 Team Members
|Nome|Função|LinkedIn|
| -------- | -------- | -------- |
|**Julio Cesar Ferreira de Freitas**|Product Owner|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/julio-freitas-415b73216)|
|**Otavio Calderan Bruguel**|Scrum Master|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/otavio-calderan-578b48239)|
|**André Hideaki Wakugawa**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/andrewakugawa/)|
|**Cauan Vinicius Barbaglio**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/cauan-barbaglio/)|
|**Cauê Vieira da Silva**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/cau%C3%AA-vieira-ba62b4244/)|
|**Gabriel Bartolomeu Guska**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabiel-guska-5860a1271/)|
|**Gabriel de Souza Mota**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabriel-mota-4a0816a0/)|
|**Paulo Arantes Machado**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/paulo-antonio-arantes-machado-a8a89b23b)|
|**Pedro Henrique da Silva Bozzano Pereira**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/pedro-bozzano)|
|**Vinícius da Silva Chaves**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/vinícius-chaves-197353244/)|

---

# 📋 Requisitos
### ⚙️ Requisitos Funcionais

| **ID** | **Requisito** | **Descrição** |
| :-------------: | :-----------: | ------------- |
|1|**API - Autenticação e Autorização** | - A API deve implementar um sistema de autenticação para garantir que apenas usuários autorizados possam acessar os serviços. <br> - A API deve permitir diferentes níveis de acesso (admin, usuário comum, etc.). |
|2|**API - CRUD** | - A API deve permitir a criação, leitura, atualização e exclusão de recursos específicos, como: <br> &nbsp;&nbsp;&nbsp;&nbsp;• Usuários <br> &nbsp;&nbsp;&nbsp;&nbsp;• Dispositivos IoT <br> &nbsp;&nbsp;&nbsp;&nbsp;• Dados de geolocalização, etc. |
|3|**API - Geolocalização** | - A API deve fornecer endpoints para registrar e consultar dados de geolocalização de pessoas ou objetos. <br> - A API deve permitir o rastreamento e histórico das localizações. |
|4|**API - Consultas e Relatórios** | - A API deve fornecer mecanismos para realizar consultas complexas com filtros por: <br> &nbsp;&nbsp;&nbsp;&nbsp;• Tempo <br> &nbsp;&nbsp;&nbsp;&nbsp;• Localização <br> &nbsp;&nbsp;&nbsp;&nbsp;• Tipo de dispositivo, etc. <br> - A API deve gerar relatórios baseados em consultas definidas pelo usuário. |
|5|**Banco de Dados - Armazenamento de Geolocalização** | - O sistema deve armazenar dados de geolocalização, incluindo latitude, longitude, e carimbo de tempo. <br> - Suporte ao armazenamento de dados de múltiplos tipos de dispositivos IoT, como wearables, tags e smartphones. |
|6|**Banco de Dados - Consultas** | - Implementar suporte para consultas espaciais eficientes, permitindo a busca por proximidade, região geográfica específica e rotas. <br> - Permitir a consulta de histórico de localização para indivíduos, ativos ou objetos específicos. |
|7|**Banco de Dados - Gerenciamento de Identidade e Acesso** | - O sistema deve fornecer autenticação e autorização robustas para controlar o acesso a dados sensíveis. <br> - Implementar diferentes níveis de acesso com base em perfis de usuários e requisitos de segurança. |
|8|**Frontend - Menus Suspensos com Filtros** | - Tipo de Objeto: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve oferecer um menu suspenso que permita filtrar resultados por tipo de objeto (Pessoa, Veículo). <br> - Pessoa ou Objeto: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve permitir a seleção de pessoas ou objetos para focar a pesquisa em um indivíduo ou item específico. <br> - Origem do Dado: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve incluir um filtro para selecionar a origem dos dados (Wearables, Tags, Smartphones). <br> - Período da Pesquisa: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve permitir a definição de um período de tempo (início e fim) para refinar os resultados. |
|9|**Frontend - Pesquisa Rápida** | - O sistema deve disponibilizar um campo de pesquisa rápida para que o usuário possa inserir termos específicos e encontrar resultados relevantes de forma eficiente. <br> - Filtros como: Hoje, Últimos 3 dias, Nessa semana, Último mês, etc. devem estar disponíveis. |
|10|**Frontend - Dialog para Seleção de Funções** | - Velocidade de Reprodução dos Pontos ou Movimentações: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve permitir que o usuário selecione a velocidade de reprodução dos pontos de parada ou movimentação no mapa para análise. <br> - Elemento que Mostra a Movimentação: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve permitir avançar ou retroceder no histórico de movimentação, visualizando pontos de parada e trajetórias em um intervalo de tempo específico. |
|11|**Frontend - Mapa** | - Plotagem de Pontos de Parada e Movimentação: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve plotar automaticamente no mapa os pontos de parada com intervalos de 15 minutos e mostrar a movimentação entre eles. <br> - Funcionalidades Básicas de Mapa: <br> &nbsp;&nbsp;&nbsp;&nbsp;• O sistema deve incluir funcionalidades básicas como arrasto e zoom, para que o usuário navegue facilmente pela área de interesse. |


### 🔒 Requisitos Não Funcionais

| **ID** | **Requisito** | **Descrição** |
| :-------------: | :-----------: | ------------- |
|12|**Escalabilidade** | - O sistema deve ser capaz de escalar horizontalmente para suportar um número crescente de dispositivos IoT e volume de dados sem degradação de desempenho. <br> - Suporte para aumento e redução de capacidade sem interrupção dos serviços. <br> - A API deve ser escalável horizontalmente para lidar com o aumento no número de usuários e no volume de dados de geolocalização. |
|13|**Desempenho** | - A solução deve garantir tempos de resposta rápidos para operações de leitura e escrita, mesmo sob alta carga. <br> - A latência das operações deve ser minimizada, mantendo-se dentro de limites aceitáveis (menos de 100ms). <br> - A API deve responder às solicitações em tempo hábil, mesmo sob carga alta, com tempo de resposta aceitável (menos de 200ms por requisição). <br> - As funcionalidades de filtro e plotagem no mapa devem ser rápidas e eficientes, mesmo com grandes volumes de dados. <br> - A reprodução dos pontos e movimentações deve ser suave, sem atrasos ou travamentos, garantindo uma experiência fluida ao usuário. |
|14|**Segurança** | - Os dados armazenados devem ser protegidos com criptografia tanto em repouso quanto em trânsito. <br> - Implementar auditoria e monitoramento contínuos para detectar e responder a acessos não autorizados ou anomalias de segurança. <br> - Todos os dados transmitidos pela API devem ser criptografados usando HTTPS. <br> - A API deve proteger contra ataques comuns, como SQL Injection, Cross-Site Scripting (XSS) e Cross-Site Request Forgery (CSRF). |
|15|**Consistência** | - Implementar mecanismos de resolução de conflitos para manter a integridade dos dados em caso de falhas. |
|16|**Usabilidade** | - O sistema deve oferecer uma interface de usuário intuitiva e fácil de usar, com menus suspensos e diálogos claros e responsivos. <br> - A experiência do usuário deve ser otimizada para garantir que as funções de filtro, seleção e navegação sejam acessíveis e fáceis de manipular. |
|17|**Compatibilidade e Integração** | - A solução deve ser compatível com diferentes plataformas de IoT e facilitar a integração com outros sistemas e serviços, como sistemas de análise de dados ou plataformas de visualização geoespacial. <br> - Suporte a APIs RESTful para facilitar a integração com sistemas de terceiros e aplicações cliente. <br> - O código da API deve ser modular e seguir boas práticas de programação para facilitar a manutenção e atualização. <br> - A API deve incluir documentação clara e abrangente para facilitar o desenvolvimento e a integração, como Swagger ou Postman Collections. <br> - O sistema deve ser compatível com diferentes navegadores web modernos e dispositivos, garantindo acessibilidade e funcionalidade consistente em desktops e tablets. |

---

# 📈 Product Backlog

| 🏅 Rank| 🔥 Prioridade| 📝 User Story| 🚀 Sprint| 🎯 Requisito do Parceiro|
| :--------: | :--------: | -------- | :--------: | :--------: |
|1|Alta|Como administrador do sistema, quero que os dados de latitude, longitude, velocidade, direção e tempo de dispositivos IoT sejam processados, para que eu possa acompanhar continuamente a movimentação e trajetória de pessoas e objetos, identificando padrões de deslocamento e possíveis anomalias como acidentes.|1| 2, 5, 13, 14|
|2|Alta|Como administrador do sistema, quero que as informações que consulto frequentemente sejam carregadas rapidamente, para poder responder de forma ágil em situações críticas, como em investigações de segurança ou análise de desempenho em tempo real, sem perder tempo com atrasos que possam comprometer a tomada de decisão.|1|4, 5, 14|
|3|Média|Como administrador do sistema, quero que os dados de localização dos dispositivos sejam capturados automaticamente, para poder monitorar em tempo real a movimentação de pessoas e objetos, garantindo que operações logísticas, de segurança ou de rastreamento sejam acompanhadas de forma precisa e confiável, evitando erros manuais ou lacunas de informação.|1| 2, 5, 14, 15|
|4|Média|Como administrador do sistema, quero filtrar, pesquisar e visualizar dados de geolocalização por colaborador, dispositivo e período, para localizar rapidamente as informações necessárias, permitindo uma análise precisa e monitoramento eficiente, especialmente em situações de segurança, como movimentações suspeitas, ou para verificar o cumprimento de rotas e horários operacionais.1/2|7, 14, 17|
|5|Alta|Como administrador do sistema, quero visualizar as pessoas e objetos em um mapa interativo, para monitorar a movimentação e trajetória de indivíduos e itens em tempo real, garantindo que o acompanhamento de deslocamentos seja eficiente, ajudando a identificar desvios ou problemas logísticos, além de melhorar a segurança em caso de movimentações não autorizadas.|1/2|7, 14, 17|
|6|Média|Como administrador do sistema, quero acessar facilmente dados históricos e informações, para monitorar eventos atuais e analisar padrões passados, permitindo identificar tendências ou anomalias, melhorando a tomada de decisões em relação à segurança, eficiência operacional ou resolução de problemas recorrentes.|2|7, 8, 17|
|7|Média|Como administrador do sistema, quero ajustar a velocidade de reprodução das movimentações no mapa, para poder analisar dados de forma detalhada em investigações de eventos críticos, como incidentes de segurança, ou acelerar a visualização em análises de rotina, adequando a reprodução ao contexto, evitando perda de tempo ou detalhes importantes.|2|9|
|8|Alta|Como administrador de segurança, quero implementar criptografia SSL/TLS para proteger os dados em trânsito e criptografia AES para os dados armazenados no banco de dados, para garantir a confidencialidade e integridade de informações sensíveis, evitando acessos não autorizados ou interceptações durante a transmissão e armazenamento, protegendo a empresa de vazamentos de dados e possíveis ataques cibernéticos.|2|6, 14, 15|
|9|Alta|Como administrador do sistema, quero definir áreas geográficas específicas (geofences) e receber alertas quando dispositivos entram ou saem dessas áreas, para monitorar de forma eficaz eventos como a entrada e saída de zonas críticas, permitindo ações rápidas em casos de movimentações não autorizadas ou anômalas, garantindo a segurança e a gestão adequada de recursos.|2|6, 7, 13, 14|
|10|Baixa|Como administrador do sistema, quero poder cadastrar novos usuários com diferentes níveis de acesso (administradores e usuários comuns), para que possam acessar a aplicação com suas credenciais e permissões definidas, garantindo que cada um tenha acesso apenas às informações e funcionalidades necessárias, evitando riscos de segurança e promovendo a responsabilidade na gestão de dados.|3|1, 14|

---

# 📚 Documentação

+ [Documentação](https://github.com/manolito-fatec/geo-iot-2024-1/wiki)

---

# 💻 Tecnologias
<h4 align="center">

|                                                         | Tecnologia   | Versão  | Descrição                                            |
|---------------------------------------------------------|--------------|---------|------------------------------------------------------|
| ![My Skills](https://skillicons.dev/icons?i=java)       | Java         | 17      | Linguagem de programação utilizada                   |
| ![My Skills](https://skillicons.dev/icons?i=spring)     | Spring Boot  | 3.3.2   | Framework para criação de aplicações Java            |
| ![My Skills](https://skillicons.dev/icons?i=mysql)      | Oracle Cloud | X.X.X   | Banco de dados relacional                            |
| ![My Skills](https://skillicons.dev/icons?i=docker)     | Docker       | ~27.2.1 | Plataforma para containerização de aplicações        |
| ![My Skills](https://skillicons.dev/icons?i=vue)        | Vue.js       | 3.4.29  | Framework JavaScript para interfaces de usuário      |
| ![My Skills](https://skillicons.dev/icons?i=vite)       | Vite         | 5.3.1   | Ferramenta de build e desenvolvimento para Vue       |
| ![My Skills](https://skillicons.dev/icons?i=redis)      | Redis        | 3.X.X   | Banco de dados em memória para cache                 |
| ![My Skills](https://skillicons.dev/icons?i=git)        | Git          | ~2.43.0 | Sistema de controle de versão                        |
| ![My Skills](https://skillicons.dev/icons?i=typescript) | TypeScript   | ~5.4.0  | Superset do JavaScript com tipagem estática          |

</h4>
