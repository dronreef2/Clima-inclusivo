**Documentação do Projeto Clima Inclusivo**

**Apresentação do Projeto**

Esse projeto foi desenvolvido pela turma Acelerado Inclusiva com o intuito de criar uma aplicação web que fornece informações climáticas acessíveis e úteis, considerando as necessidades dos usuários afetados por eventos climáticos extremos, como enchentes. A aplicação foi desenvolvida utilizando React e boas práticas de desenvolvimento.

**Objetivo**

O objetivo do Clima Inclusivo é:

Fornecer informações meteorológicas em tempo real para a população, com foco especial em alertas de eventos extremos.

Tornar os dados climáticos acessíveis, inclusive para pessoas com deficiências.

Ajudar comunidades vulneráveis a se prepararem melhor para eventos climáticos severos, promovendo segurança e bem-estar.

**Ferramentas Utilizadas**

React: Biblioteca JavaScript para construção da interface de usuário.

Node.js: Para configuração do backend e gerenciamento de dependências.

Git e GitHub: Controle de versão e hospedagem do código.

API Meteorológica: Utilização de serviços como OpenWeatherMap ou outros para fornecimento de dados climáticos.

**Estrutura do Projeto**

/clima-inclusivo

├── /src
│   ├── /components  # Componentes reutilizáveis da interface
│   ├── /pages       # Páginas principais da aplicação
│   ├── /services    # Serviços para consumo de APIs
│   ├── /styles      # Arquivos de estilização (CSS/Tailwind)
│   └── index.js     # Arquivo principal de entrada da aplicação

├── /public           # Recursos públicos como imagens e ícones
├── package.json      # Dependências e scripts do projeto
└── README.md         # Documentação inicial do projeto

**Guia de Instalação**

Certifique-se de ter o Node.js (versão 14 ou superior) instalado em sua máquina.

Utilize um gerenciador de pacotes como npm ou yarn.

**Comandos**

# Clonando o repositório:
git clone https://github.com/seu-usuario/clima-inclusivo.git
cd clima-inclusivo

# Instalando dependências:
npm install

# Executando o projeto:
npm start

# Acesse o projeto no navegador em http://localhost:3000.

**Comandos Essenciais GIT**

# Clonar o repositório:
git clone <link do projeto>

# Acessar a pasta do projeto:
cd clima-inclusivo

# Criar uma nova branch:
git checkout -b <nome-da-sua-branch>

# Adicionar as alterações:
git add .

# Realizar o commit:
git commit -m "Descrição das alterações realizadas"

# Enviar as alterações para o repositório remoto:
git push origin <nome-da-sua-branch>

# Atualizar sua branch local:
git pull origin main

**Alerta**: O nome da branch deve estar relacionado ao nome da tarefa.
Exemplo:

Nome da tarefa: Criar componente Sobre

Nome da branch: criar-componente-sobre

**Funcionalidades Principais**

**Consulta de Informações Climáticas**

Dados atualizados em tempo real sobre condições climáticas.

Alertas de eventos climáticos extremos, como enchentes.

**Interface Acessível**

Design responsivo para diferentes dispositivos.

Compatibilidade com leitores de tela.

**Personalização**

Configuração de notificações baseadas na localização do usuário.

**Histórico Climático**

Visualização de dados passados para análise de tendências.

**Referências**

OpenWeatherMap - API para dados climáticos.

React - Biblioteca JavaScript.

MDN Web Docs - CSS - Documentação oficial sobre CSS.
