Avaliação Prática – Versionamento de Código com Git e GitHub (Java)

Passos Realizados:

1. Criei um repositório no GitHub com o nome: avaliacao-git-nome-sobrenome
2. Clonei o repositório usando o comando: git clone <URL_DO_REPOSITORIO>
3. Criei o arquivo Main.java com um método main que imprime uma mensagem.
4. Adicionei, comitei e enviei o Main.java com os comandos:
   git add Main.java
   git commit -m "Adiciona Main.java"
   git push origin main
5. Criei uma nova branch chamada funcoes com: git checkout -b funcoes
6. Nessa branch, criei o arquivo Calculadora.java com os métodos soma() e multiplicacao().
7. Comitei e enviei com: git add, commit e push.
8. Fiz merge da branch funcoes com a main: git checkout main, git merge funcoes, git push origin main
9. Criei o arquivo README.md com explicações da atividade.
10. Enviei todas as alterações para o GitHub.
