<h1 align="center">
    <img alt="GoBarber" title="GoBarber" src="https://github.com/radaelilucca/gobarber-backend/blob/8db8538d5c31fe31d9dbda321950c5d4cd8dbe23/src/assets/GoBarber.png?raw=true" width="250px" />
</h1>

<h3 align="center"> 
	Desenvolvido no Bootcamp GoStack da <a href="https://rocketseat.com.br/"> Rocketseat</a>
</h3>

<p align="center">

  <img alt="Language" src="https://img.shields.io/github/languages/top/radaelilucca/GoBarber?style=for-the-badge">
  
	
  <a href="https://www.linkedin.com/in/luccaradaeli/">
    <img alt="Made by Lucca Radaeli" src="https://img.shields.io/badge/made%20by-Lucca_Radaeli-%2304D361?style=for-the-badge">
  </a>

  <a href="https://github.com/radaelilucca/GoBarber/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/radaelilucca/gobarber-mobile?style=for-the-badge">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?style=for-the-badge">
   <a href="https://github.com/radaelilucca/GoBarber/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/radaelilucca/gobarber?style=for-the-badge">
  </a>
</p>

<h3 align="center">
  🌟 &nbsp; <a href="#-NLW">Bootcamp GoStack</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  💻 &nbsp;<a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  🚀 &nbsp; <a href="#rocket-Technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  🎆 &nbsp; <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</h3>

<h3 align="center">
  👨‍🏫 &nbsp; <a href="#gear-executando">Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  ➕ &nbsp; <a href="#-como-contribuir">Contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  :memo: &nbsp; <a href="#memo-licença">Licença</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  📧 &nbsp;<a href="#-contato">Contato</a>
</h3>

<br/>

## 🌟 Bootcamp GoStack - O que é?

O GoStack é um treinamento online, prático e intensivo, no formato de bootcamp. No GoStack o aluno vai a fundo nas tecnologias NodeJS, ReactJS e React Native, e todo o ecossistema ao redor dessas ferramentas, do zero ao deploy. Incluindo testes automatizados, integração contínua, publicação nas stores, e todas as bibliotecas e frameworks importantes para quem deseja ficar pronto para os desafios do mundo real e se destacar no mercado de trabalho. No GoStack os módulos são liberados semana a semana de acordo com o cronograma da turma, utilizando o nosso método para te dar segurança e mostrar que você está assimilando todos os conceitos através de exercícios e desafios. Além disso, ao final do treinamento você terá que desenvolver uma aplicação completa para garantir que dominou a stack e receber a sua certificação.

## 💻 Projeto

O GoBarber é um app que conecta clientes a prestadores de serviços de barbearia.

Pela plataforma web o prestador de serviços pode ver seus agendamentos, seus horários disponíveis, editar seu perfil e receber notificações de novos agendamentos.

Já pelo aplicativo móvel o cliente consegue marcar, cancelar e consultar agendamentos com qualquer prestador cadastrado na plataforma, assim como editar seu perfil.

<h1 align="center">
    <img alt="Example" title="Example" src="https://raw.githubusercontent.com/radaelilucca/ECokleta-NLW01/master/readme-assets/readme-example-image.png" width="900px" />
</h1>

## :rocket: Tecnologias Utilizadas

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js][nodejs]
- [Docker][docker]
- [PostgreSQL][postgresql]
- [MongoDb][mongodb]
- [Redis][redis]
- [Sequelize][sequelize]
- [React][reactjs]
- [React Native][rn]

## :gear: Executando

Para baixar e executar esta aplicação você vai precisar de: [Git](https://git-scm.com), [Docker][docker], [PostgreSQL][postgresql] e [Node.js][nodejs] + [Yarn][yarn].

### 🗄️ Executando a API (backend)

<a href="https://insomnia.rest/run/?label=Ecoleta-nlw-radaelilucca&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fradaelilucca%2FEColketa-NLW01%2Fmaster%2Fbackend%2FInsomnia_ecoleta.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>

```bash
# Clone este repositório:
$ git clone https://github.com/radaelilucca/GoBarber.git

# Entre na basta backend e execute o comando Yarn para baixar todos os pacotes e suas dependências.
$ cd GoBarber/gobarber-backend && yarn install

# Suba os containers no Docker com PostgreSQL, MongoDB e Redis.

$ docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d postgres

$ docker run --name some-mongo -d mongo

$ docker run --name some-redis -d redis:alpine

#  Crie o .env na raiz do projeto e edite suas variáveis de ambiente, tendo como base o .envexample.

# Rode yarn dev - para iniciar o servidor, e yarn queue - para iniciar o serviço de background jobs.

$ yarn dev

$ yarn queue

# Se os containers e as variáveis ambiente estiverem okay, tudo deverá funcionar corretamente.

# O backend roda por padrão na porta 3333!
```


### 🌐 Executando o Frontend

```bash
# Clone este repositório:
$ git clone https://github.com/radaelilucca/GoBarber.git

# Entre na pasta do repositório, em seguida na pasta do mobile:
$ cd GoBarber/gobarber-frontend

# Instale as dependências:
$ yarn install

# Execute o projeto em modo desenvolvimento:
$ yarn start

-> Não se esqueça de preencher as variáveis ambiente no arquivo .env.example e renomeá-lo para '.env'.

# O frontend roda por padrão na porta 3000!
```

### 📱 Executando o Aplicativo Mobile

```bash
# Clone este repositório:
$ git clone https://github.com/radaelilucca/GoBarber.git

# Entre na pasta do repositório, em seguida na pasta do mobile:
$ cd GoBarber/gobarber-mobile

# Instale as dependências:
$ yarn install

# Execute o projeto em modo desenvolvimento:
$ yarn start

Para testes, utilize um dispositivo físico ou emuladores.

```

## ➕ Como contribuir

- Primeiramente deixe uma ⭐;
- Faça um fork deste repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Após o merge da sua PR você pode deletar sua branch por conta própria!

## :memo: Licença

This project is under the MIT license. See the [LICENSE](https://github.com/radaelilucca/gobarber/blob/master/LICENSE) for details.

## 📧 Contato

 <h4>Gostou do Projeto e quer conversar sobre? Me chama pra gente trocar uma idéia! </h4>  
  <p>
    <a href="https://www.linkedin.com/in/luccaradaeli/">
      <img src="https://github.com/radaelilucca/FinDevs/blob/master/Assets/Linkedin.png?raw=true" width=10%/> 
      </a>
  </p>
<p>
</p>


Made with ♥ by Lucca Radaeli :wave:

[nodejs]: https://nodejs.org/
[docker]: https://www.docker.com/
[postgresql]: https://www.postgresql.org/
[mongodb]: https://www.mongodb.com/
[redis]: https://redis.io/
[sequelize]: https://sequelize.org/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[yarn]: https://yarnpkg.com/
