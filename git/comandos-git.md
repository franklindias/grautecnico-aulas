* Apresentação professor
* Apresentação turma
* Apresentação metodologia de aula
* Introdução ao git e github

### Comandos GIT:
* Para inicializar um repositório git
```bash
git init
```
* Adicionar repositório github ao seu repositório local
```bash
git remote add origin git@github.com:usuario/nomerepositorio.git
```
* Adicionar novos arquivos ou mudanças feitas no git
  * utilizar "." para adicionar todos os arquivos ou especificar o nome do arquivos para adicionar apenas 1
```bash
git add .
```
* Adicionar mensagem às mudanças feitas
```bash
git commit -m "Mensagem do commit"
```
* Envia mudanças para o servidor git
```bash
git push
```
* Criar um novo branch
```bash
git checkout -b nomedonovobranch
```
* Trocar de branch
```
git checkout nomedobranch
``` 
* Descartar mudanças feitas
  * Adicionar "." no final para descartar todas as mudanças ou especificar o nome de um arquivoas
```bash
git checkout -- .

```
* Puxar mudanças de outro branch
```
git merge nomedobranch
```