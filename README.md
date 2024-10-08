<h1 align="center" style="font-weight: bold;">Text Editor ✍</h1>

![react](https://img.shields.io/badge/React-blue?style=flat&logo=react)
![Underdevelopment](https://img.shields.io/badge/GraphQL-e10098?style=flat&logo=graphql)


<p align="center">
 <a href="#tech">Technologies</a> • 
 <a href="#started">Getting Started</a> • 
 <a href="#contribute">Contribute</a> •
 <a href="#license">License</a>
</p>

<p align="center">
<b>This application is a online Text Editor, where users can create and edit markdown files.</b>
</p>

<p align="center">
    <img src="./.github/assets/file-edit.png" width="300px">
    <img src="./.github/assets/files.png" width="300px">
</p>


<h2 id="tech">Technologies</h2>

### Client:
  Built using [React JS](https://pt-br.reactjs.org/), this interface and the layout ware made from scratch by me.

### API
  For building the server of this application, I used [Hy Graph](https://hygraph.com/) that is an CMS that allow us to build [GraphQL](https://graphql.org/) Content APIs.

<h2 id="started">🚀 Getting Started</h2>

<h4> Prerequisites</h4>

- Node 12
- Git 2

<h4>Install project</h4>

```
git clone https://github.com/geovanesv/text-editor-github-actions.git
npm install
```

<h4>Environment Variables</h4>

In the root of this project, create a `.env` file with the keys and values located on `.env.example`

To get these values you need to create an Account on [HyGraph](https://app.hygraph.com/) and then:

- Create a new project
- Inside your project, go to "Project Settings"
- Inside settings, access the tab "API Access"
- Add all permisions

<h4>Start server</h4>

```
  //in root
  npm start
```


<h2 id="license">📃 License</h2>

This project is under [MIT](./.github/LICENSE) license



