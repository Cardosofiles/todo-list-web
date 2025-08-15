# Todo List Web

Aplicação web para organização de tarefas, permitindo ao usuário criar, editar, concluir e remover itens de uma lista de afazeres de modo simples e eficiente.

---

## Principais funcionalidades e casos de uso

- Adicionar novas tarefas à lista
- Editar o nome ou descrição de tarefas existentes
- Marcar tarefas como concluídas ou pendentes
- Remover tarefas individualmente
- Visualizar contagem de tarefas totais e concluídas
- Interface responsiva para desktop e dispositivos móveis

---

## Stack e tecnologias utilizadas

- **Frontend:** ReactJS
- **Linguagem:** TypeScript
- **Estilização:** CSS Modules ou Styled-components
- **Gerenciamento de estado:** Context API ou React hooks
- **Persistência:** LocalStorage (para salvar tarefas localmente)
- **Testes:** Jest, React Testing Library (se aplicável)
- **Outros:** dotenv para variáveis de ambiente

---

## Estrutura de pastas

```
todo-list-web/
├── public/                # Arquivos estáticos (index.html, favicon, etc)
├── src/
│   ├── assets/            # Imagens, ícones e recursos visuais
│   ├── components/        # Componentes reutilizáveis (TodoItem, Input, Button, etc)
│   ├── contexts/          # Contextos globais (ex: tarefas)
│   ├── hooks/             # Hooks personalizados
│   ├── pages/             # Páginas principais da aplicação
│   ├── styles/            # Estilos globais e temas
│   ├── utils/             # Funções auxiliares
│   ├── App.tsx            # Componente principal da aplicação
│   └── main.tsx           # Ponto de entrada da aplicação React
├── .env.example           # Exemplo de variáveis de ambiente
├── package.json           # Dependências e scripts do projeto
└── README.md              # Documentação do projeto
```

### Explicação das principais partes

- **public/**: Arquivos acessíveis diretamente pelo navegador.
- **src/assets/**: Imagens e ícones usados na interface.
- **src/components/**: Componentes reutilizáveis, como cards de tarefa, inputs e botões.
- **src/contexts/**: Gerenciamento de estados globais, como a lista de tarefas.
- **src/hooks/**: Hooks customizados para lógica reutilizável.
- **src/pages/**: Páginas principais, como a tela de tarefas.
- **src/styles/**: Estilos globais e temas do projeto.
- **src/utils/**: Funções auxiliares para manipulação de dados e tarefas.

---

## Instalação e execução local

### Pré-requisitos

- Node.js (18.x+ recomendado)
- npm ou yarn

### Passo a passo

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Cardosofiles/todo-list-web.git
   cd todo-list-web
   ```

2. **Configure as variáveis de ambiente**
   - Copie o arquivo `.env.example` para `.env` e ajuste conforme necessário.

3. **Instale as dependências**
   ```bash
   npm install
   # ou
   yarn
   ```

4. **Inicie o servidor de desenvolvimento**
   ```bash
   npm start
   # ou
   yarn start
   ```

5. **Acesse a aplicação**
   - Abra [http://localhost:3000](http://localhost:3000) no navegador.

---

## Como executar testes

```bash
npm test
# ou
yarn test
```

---

## Exemplos de uso das funcionalidades

- **Adicionar tarefa:**  
  Digite o nome da tarefa no campo apropriado e clique em "Adicionar" para incluí-la na lista.

- **Marcar como concluída:**  
  Clique no checkbox ao lado da tarefa para marcar como feita ou desfazer a conclusão.

- **Editar tarefa:**  
  Clique no ícone de edição para alterar o nome ou a descrição da tarefa.

- **Remover tarefa:**  
  Clique no ícone de lixeira ao lado da tarefa para removê-la da lista.

---

## Boas práticas e recomendações

- Utilize variáveis de ambiente para dados sensíveis e configurações.
- Prefira componentes isolados e reaproveitáveis.
- Escreva testes para garantir a estabilidade das principais funcionalidades.
- Revise e atualize as dependências regularmente.
- Siga o fluxo de contribuição do repositório para pull requests e issues.

---

*Contribuições são bem-vindas! Em caso de dúvidas, abra uma issue ou envie um pull request.*

## 📫 Contato

<div align="center">

<a href="mailto:cardosofiles@outlook.com">
  <img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"/>
</a>
<a href="https://www.linkedin.com/in/joaobatista-dev/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://github.com/Cardosofiles" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://cardosofiles.dev/" target="_blank">
  <img src="https://img.shields.io/badge/Portfólio-222222?style=for-the-badge&logo=about.me&logoColor=white" alt="Portfólio"/>
</a>

</div>
