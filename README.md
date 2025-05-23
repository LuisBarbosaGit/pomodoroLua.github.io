# 🍅 Pomodoro Lua Study App 🚀

## Visão Geral

Bem-vindo ao **Pomodoro Lua**, uma aplicação web minimalista e eficaz, projetada para te ajudar a implementar a **Técnica Pomodoro** para aumentar a produtividade e o foco. Desenvolvido com **React** e **TypeScript**, este site oferece um temporizador direto, gerenciamento de tarefas e rastreamento de ciclos para guiar suas sessões de estudo ou trabalho.

### ✨ Funcionalidades

* **Temporizador Pomodoro:** Um temporizador personalizável para intervalos de trabalho focados (Pomodoros) e pausas curtas/longas.
* **Gerenciamento de Tarefas:** Adicione e acompanhe facilmente sua tarefa atual.
* **Rastreamento de Ciclos:** Indicadores visuais para monitorar seus ciclos Pomodoro concluídos.
* **Interface Intuitiva:** Um design limpo e amigável para uma experiência livre de distrações.
* **Configurações (Planejado/Implicado):** Opções para personalizar as durações do temporizador (trabalho, pausa curta, pausa longa) e outras preferências.
* **Alternar Tema (Implicado):** Mude entre os modos claro e escuro para uma visualização confortável.

### 💻 Tecnologias Utilizadas

* **React:** Uma biblioteca JavaScript para construção de interfaces de usuário.
* **TypeScript:** Um superconjunto de JavaScript que adiciona tipagem estática.
* **HTML/CSS:** Para estruturar e estilizar a aplicação.
* **JavaScript:** Para a lógica e interatividade da aplicação.

---

## Primeiros Passos

Para obter uma cópia local do projeto e colocá-lo em funcionamento, siga estes simples passos.

### ⚙️ Pré-requisitos

Certifique-se de ter o [Node.js](https://nodejs.org/en) e o [npm](https://www.npmjs.com/) (Node Package Manager) instalados em sua máquina.

* [Node.js](https://nodejs.org/en) (versão LTS recomendada)
* [npm](https://www.npmjs.com/) (geralmente vem com o Node.js)

### 🚀 Instalação

1.  Clone o repositório:
    ```bash
    git clone <your-repository-url>
    cd pomodoro-lua-app
    ```
    (Substitua `<your-repository-url>` pela URL real do seu repositório Git)

2.  Instale os pacotes NPM:
    ```bash
    npm install
    ```

### ▶️ Executando a Aplicação

Para executar o aplicativo em modo de desenvolvimento:

```bash
npm run dev
Isso abrirá a aplicação no seu navegador em http://localhost:3000. A página será recarregada automaticamente se você fizer edições. Você também verá quaisquer erros de lint no console.
```
# 📂 Estrutura do Projeto

```bash
POMODORO-LUA/
├── .vscode/          # Configurações específicas do VS Code
├── dist/             # Saída da build de produção
├── node_modules/     # Dependências do projeto
├── public/           # Arquivos estáticos (ex: index.html, favicons)
├── src/
│   ├── assets/       # Arquivos de mídia e recursos (imagens, ícones, etc.)
│   ├── components/   # Componentes de UI reutilizáveis
│   ├── models/       # Definições de modelos de dados (interfaces, types)
│   ├── pages/        # Componentes que representam páginas ou rotas
│   ├── styles/       # Arquivos de estilo (CSS, SCSS, etc.)
│   ├── templates/    # Possíveis modelos de layout ou componentes de alto nível
│   ├── App.tsx       # Componente principal da aplicação
│   ├── main.tsx      # Ponto de entrada do aplicativo React (renderiza o App)
│   └── vite-env.d.ts # Definições de tipo para variáveis de ambiente do Vite
```

# 💡 Melhorias Futuras

- **Durações do Temporizador Customizáveis**: Permitir que os usuários definam seus próprios tempos para trabalho, pausas curtas e pausas longas através de um menu de configurações.
- **Notificações**: Implementar notificações de desktop ou alertas sonoros quando um Pomodoro ou uma pausa terminar.
- **Persistência da Lista de Tarefas**: Salvar tarefas localmente (ex: usando `localStorage`) para que elas persistam mesmo após fechar o navegador.
- **Rastreamento de Progresso**: Adicionar uma forma de visualizar sessões Pomodoro históricas e rastrear a produtividade ao longo do tempo.
- **Aprimoramentos de Design Responsivo**: Otimizar ainda mais o layout para vários tamanhos de tela e dispositivos.
- **Efeitos Sonoros**: Adicionar sutis sinais sonoros para o início/fim do temporizador.
