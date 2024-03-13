## GitHub: como criar um projeto pelo iTerm 3 
- entre no iTerm 3 e em seguida entre na pasta "Documents":
```bash
cd Documents
```
- crie uma nova pasta para meu repository:
```bash
mkdir 'NomeDaPastaCriada'
```
- vá até a pasta criada com o comando:
```bash
cd 'NomeDaPastaCriada'
```
- inicie um novo repository git usando:
```bash
git init
```
- entre na página inicial do seu GitHub e clique em "New Repository";
- preencha um nome para o seu repository, selecione se deseja que seu repository seja privado ou público e clique em "Create repositoy";
- copie a URL do seu repository e adicione no iTerm 3 da seguinte forma:
```bash
git remote add origin 'URLRepositoryGit'
```
Agora, para abrir o VS Code e começar a criar seu projeto, digite:
```bash
open .
```
## commit

- adicione arquivos ao seu repository git e faça o commit com o comando:
```bash
git add .
git commit -m "primeiro commit"
```
- envie seus arquivos para o repository remoto no GitHub usando o comando:
```bash
git push -u origin master
```