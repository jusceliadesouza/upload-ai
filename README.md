# upload-ai
Gerador de títulos e descrições para vídeos

![GitHub repo size](https://img.shields.io/github/repo-size/jusceliadesouza/upload-ai?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/jusceliadesouza/upload-ai?style=for-the-badge)
<!-- ![GitHub forks](https://img.shields.io/github/forks/jusceliadesouza/upload-ai?style=for-the-badge) -->
<!-- ![Bitbucket open issues](https://img.shields.io/bitbucket/issues/jusceliadesouza/upload-ai?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/jusceliadesouza/upload-ai?style=for-the-badge) -->

![Imagem de uma astronauta, à esquerda. Logo abaixo, os dizeres 'Learning Artificial Intelligence - Come to the AI Side - NLW IA - Rocketseat'. Ao lado, um computador mostrando a página inicial do projeto](github/readme-preview.svg)

Desenvolvido durante a NLW IA da [Rocketseat](https://rocketseat.com.br), o **upload.ai** utiliza a API da OpenAI para gerar títulos e descrições a partir de um vídeo escolhido pelo usuário. O vídeo, assim que enviado, é convertido para MP3 e, a partir daí, a aplicação transcreve o conteúdo do vídeo, enviando o resultado final para o usuário, de acordo com o prompt definido.

## Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [x] Configurações iniciais
- [x] UI do projeto
- [x] Backend do projeto
- [x] Integração do backend com o frontend
- [ ] Deploy

## Pré-requisitos

Para utilizar o **upload.ai** você precisará ter instalado em sua máquina as seguintes ferramentas:

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/)
- [pnpm](https://pnpm.io/)
- Além disso, é bom ter um editor para trabalhar com o código, como o [VSCode](https://code.visualstudio.com/)

Também será necessário ter as seguintes chaves de API:

- [OpenAI API Key](https://platatform.openai.com/)

## ☕ Usando upload.ai

Para usar **upload.ai** web, siga estas etapas:

1. Clone o projeto na sua máquina. `git clone https://github.com/jusceliadesouza/upload-ai.git`
2. No terminal, utilize o comando `cd..` para voltar à raiz do projeto e redirecione para a pasta `web`
3. Instale as dependências utilizando `pnpm install`
4. Execute o projeto com `pnpm run dev`
5. Abra o endereço `http://localhost:5173/` no seu navegador favorito

Para usar o servidor, siga as seguintes etapas:

1. No terminal, vá até a pasta `api` usando o comando `cd api`
2. Instale as dependências da api utilizando `pnpm install`
3. Renomeie o arquivo `.env.example` para `.env` e preencha com as suas variáveis de ambiente.
4. Rode o servidor com `pnpm run dev`
5. Para acessar as informações no navegador, utilize o endereço `http://localhost:3333/`

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

[⬆️ Voltar ao topo](#upload-ai)
