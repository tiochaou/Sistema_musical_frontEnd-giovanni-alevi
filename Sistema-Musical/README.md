# 🎵 Sistema Musical — Front-end

Interface web de um **Sistema Musical**, desenvolvida com **HTML5 e CSS3**, para apresentar o fluxo de gerenciamento de artistas e músicas em uma aplicação de biblioteca musical.

Este repositório contém a **parte visual (front-end)** do projeto, incluindo páginas de login, menu principal, formulários de cadastro e listagem de músicas.

## 🚀 Funcionalidades apresentadas

- **Login:** tela com campos de usuário e senha.
- **Menu principal:** navegação para as áreas de artistas, músicas e biblioteca musical.
- **Cadastro de artistas:** formulário com nome, gênero musical, país e foto, acompanhado de uma tabela de artistas de exemplo.
- **Cadastro de músicas:** formulário com artista, título, álbum, gênero, link do YouTube, imagem de capa e letra da música.
- **Biblioteca musical:** tabela de músicas com interface de busca e filtros por artista e gênero.
- **Ações na interface:** botões de editar, excluir e acessar músicas associadas a artistas.
- **Layout responsivo:** adaptação de formulários, menu e tabelas a telas menores.

> **Importante:** esta versão é um protótipo estático de front-end. Os dados exibidos nas tabelas são exemplos, e os formulários, filtros, login e ações de edição/exclusão **ainda não possuem processamento funcional, autenticação ou persistência de dados**. A integração com back-end e banco de dados poderá ser desenvolvida futuramente.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura e formulários das páginas.
- **CSS3** — estilização, componentes visuais e responsividade.

Não é necessário instalar bibliotecas ou dependências para visualizar as páginas.

## 📁 Estrutura do projeto

```text
sistema-musical/
├── index.html                # Menu principal
├── login.html                # Tela de login
├── cadastro_artistas.html    # Cadastro e listagem de artistas
├── cadastro_musica.html      # Cadastro e listagem de músicas
├── listagem_musicas.html     # Biblioteca musical e filtros
├── styles.css               # Estilos compartilhados
└── README.md                # Documentação do projeto
```

## ▶️ Como executar

1. Clone este repositório ou baixe os arquivos em ZIP.
2. Mantenha todos os arquivos HTML e o `styles.css` na mesma pasta.
3. Abra `index.html` no navegador para visualizar o menu principal ou `login.html` para visualizar a tela de login.

Você também pode utilizar a extensão **Live Server** no Visual Studio Code para visualizar o projeto durante o desenvolvimento.

**Atenção:** nos arquivos `index.html` e `cadastro_musica.html`, alguns links apontam para `cadastro_artista.html`, mas o arquivo fornecido está nomeado como `cadastro_artistas.html`. Para que a navegação funcione corretamente, ajuste esses links para `cadastro_artistas.html` ou renomeie o arquivo de maneira consistente.

## 📌 Status do projeto

🚧 **Em desenvolvimento — etapa de front-end.**

### Próximas etapas possíveis

- Implementar a lógica de autenticação.
- Integrar formulários com um back-end e banco de dados.
- Implementar cadastro, edição e exclusão de artistas e músicas.
- Tornar a busca e os filtros funcionais.
- Exibir imagens e links de músicas a partir de dados reais.

## 🎯 Objetivo

Praticar o desenvolvimento de interfaces web e a organização das páginas de um sistema de gerenciamento musical, criando uma base visual para futuras funcionalidades dinâmicas.

## 👥 Créditos

**Aluno / Desenvolvedor:** Giovanni Allevi  
**Professores:** Raul e Luis Denani
