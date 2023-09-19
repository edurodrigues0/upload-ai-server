# Upload.ai - Plataforma de Conversão de Vídeo para Texto e Sugestão de Títulos/Descrições para o YouTube

O Upload.ai é uma plataforma que permite aos usuários fazer o upload de vídeos no formato MP4 e, em seguida, converte automaticamente o conteúdo de áudio em texto transcrito. Além disso, o Upload.ai sugere três títulos e descrições para o vídeo, facilitando a publicação em plataformas como o YouTube.

## Funcionalidades

- **Upload de Vídeo**: Faça o upload de vídeos em formato MP4 para a plataforma.

- **Conversão de Áudio para Texto**: A plataforma utiliza a API da OpenAI para converter o conteúdo de áudio do vídeo em texto.

- **Sugestões de Títulos/Descrições**: Com base no conteúdo do vídeo transcrito, o Upload.ai gera automaticamente três sugestões de títulos e descrições para facilitar a publicação no YouTube.

## Tecnologias Utilizadas

### Back-End

- **Node.js**: Um ambiente de tempo de execução JavaScript.
- **Fastify**: Um framework web rápido e eficiente para Node.js.
- **Zod**: Uma biblioteca para validação de esquemas em TypeScript.
- **Prisma**: Um ORM (Object-Relational Mapping) moderno e robusto.
- **TypeScript**: Uma linguagem de programação de código aberto que se baseia em JavaScript.
- **OpenAI API**: API da OpenAI para processamento de linguagem natural.

### Como Executar o Projeto

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado no seu sistema.

1. Clone o repositório:

```Javascript
git clone https://github.com/seu-usuario/upload.ai.git
cd upload.ai
```

2. Instale as dependências:

```Javascript
npm install
```

3. Inicie o servidor 

```Javascript
npm run dev
```

4. Configure as variáveis de ambiente copiando o arquivo .env.example para .env e ajustando as configurações:

```Javascript
cp .env.example .env
```

obs: para o variavél OPENAI_KEY gerar uma chave secreta no site da openai