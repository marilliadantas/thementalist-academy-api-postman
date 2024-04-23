<h1 align="center"> Automação API com Postman - Squad The Mentalist 🧠</h1>

![STATUS](https://img.shields.io/static/v1?label=STATUS&message=%20EM%20CONSTRU%C3%87%C3%83O&color=yellow&style=for-the-badge)



## 💬 Sobre o projeto
<p> Esse projeto foi proposto pelo Academy da instuituição Qa.Coders. O nosso objetivo nesse projeto, é encontrar melhorias e inconsitências e além de tudo, aprender novas tecnologias e trabalhar em equipe. Para documentar o projeto e executar os testes nós utilizamos um swagger e as  PBIs disponibilizadas pelos Qa.Coders durante as 6 Sprints dos projeto.

## Tecnologias utilizadas

- Postman web version

- node v20.11.0

- newman v6.1.1

- newman reporter-htmlextra

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)

- Segundo: realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)

```bash
npm install -g newman
```

- Terceiro: realize a instalação da dependência dos relatórios (opcional) 
 [baixe aqui](https://www.npmjs.com/package/newman-reporter-htmlextra)

```bash
npm install -g newman-reporter-htmlextra
```

## Como rodar os testes

### Pelo Postman web ou desktop

- Importe a collection e as variáveis de ambiente e globals

- Execute a seguinte linha de comando para rodar os testes

 ```bash
newman run nome_da_collection.json -e env-automacao.json -g env-global.json -r cli
  ```

## Execução com Report html-extra (opcional)

```bash
newman run nome_da_collection.json -e env-automacao.json -g env-global.json -r htmlextra
```

### Obs: Lembre-se de substituir [nome_da_collection.json] pelo nome da collection que você deseja rodar. 
Neste projeto temos as seguintes collections: 
- auth_collection.json
- department_collection.json
- user_collection.json

### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos teses e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.

# 👥 Autores do projeto
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%">
        <a href="https://www.linkedin.com/in/aleticia-da-silva/" target="_blank"><img src="https://avatars.githubusercontent.com/u/61994404?v=4" width="100px;" alt="Letícia da Silva"/></a><br />
        <sub><b><a href="https://github.com/ALeticiadaSilva" target="_blank">Letícia da Silva</a></b></sub><br />
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://www.linkedin.com/in/marilliadantas/" target="_blank"><img src="https://avatars.githubusercontent.com/u/105676314?v=4" width="100px;" alt="Marillia Dantas"/></a><br />
        <sub><b><a href="https://github.com/marilliadantas" target="_blank">Marillia Dantas</a></b></sub><br />
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://www.linkedin.com/in/amandaoliveira--/" target="_blank"><img src="https://avatars.githubusercontent.com/u/73588768?v=4" width="100px;" alt="Amanda Oliveira"/></a><br />
        <sub><b><a href="https://github.com/Amandatec" target="_blank">Amanda Oliveira</a></b></sub><br />
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://www.linkedin.com/in/jeieljacques/" target="_blank"><img src="https://avatars.githubusercontent.com/u/133384467?v=4" width="100px;" alt="Jeiel Jacques"/></a><br />
        <sub><b><a href="https://github.com/JeielJacques" target="_blank">Jeiel Jacques</a></b></sub><br />
      </td>
    </tr>
  </tbody>
</table>


