# TreinoGit

__1. Crie um repositório em seu Github chamado TreinoGit;__
>git clone https://github.com/keitepassos/TreinoGit.git

2. Dentro dele crie 3 arquivos:

*Um arquivo .html

*Um arquivo .css

*Um arquivo .js

3. Crie uma página simples no html, com um css simples e um  js básico;

4. Adicione esses arquivos e dê um commit um por um no repositório, documentando o que você fez;
>git add index.html

>git commit - m "commit html"

>git add script.js

>git commit - m "commit js"

>git add estilo.css

>git commit - m "commit css"

5. Suba o projeto no repositório remoto;
>git push origin master

6. Crie uma branch teste e, dentro dela, altere os 3 arquivos criados;
>git branch -b teste

7. Faça o passo 4 novamente e suba sua branch teste no repositório remoto;
~~~
>git add index.html

>git commit - m "commit branch teste arquivo html"

>git add script.js

>git commit - m "commit branch teste arquivo' js"

>git add estilo.css
>git commit - m "commit branch teste arquivo css"

>git push origin teste
~~~
8. Suba o projeto no repositório remoto;
>git push origin master


9. Por fim, dê um merge com a branch master e suba no respositório;

>git checkout master

>git push origin master

