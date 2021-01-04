# TreinoGit
>git
1-Crie um repositório em seu Github chamado TreinoGit;

2-Dentro dele crie 3 arquivos:

a-Um arquivo .html

b-Um arquivo .css

c-Um arquivo .js

3-Crie uma página simples no html, com um css simples e um  js básico;

4-Adicione esses arquivos e dê um commit um por um no repositório, documentando o que você fez;
>git add index.html

>git commit - m "up arquivo .html"

>git add script.js

>git commit - m "up arquivo .js"

>git add estilo.css

>git commit - m "up arquivo .css"

5-Suba o projeto no repositório remoto;
>git push origin main

6-Crie uma branch teste e, dentro dela, altere os 3 arquivos criados;
>git branch -b teste

5-Faça o passo 4 novamente e suba sua branch teste no repositório remoto;
>git add index.html

>git commit - m "up branch teste arquivo .html"

>git add script.js

>git commit - m "up branch teste arquivo .js"

>git add estilo.css
>git commit - m "up branch teste arquivo .css"

>git push origin teste

5-Suba o projeto no repositório remoto;
>git push origin main


8-Por fim, dê um merge com a branch master e suba no respositório;

>git checkout main

>git push origin main

