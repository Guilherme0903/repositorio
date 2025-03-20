``` git config --global user.email "seu email" ```

```git config --global user.name "seu nome"```

```git clone *link do repositorio*```                                           *clona o repositório online para local*

```cd git_na_pratica``` 		                                                    *entra na pasta do repositório*

```type nul>git_na_pratica.md``` 	                                              *cria um arquivo vazio do tipo(extensão) que eu defini*

```code .``` 				                                                            *abre o arquivo no visual studio code*

```git add git_na_pratica.md``` 	                                              *adiciona no repositório o arquivo que eu criei*

```git commit -m "primeiro commit da atividade"```                             *salva a versão atual do projeto local*

``` git push ```			                                                            *envia as alterações para o repositório online*

```git checkout -b primeira_branch```	                                          *cria uma nova branch com nome definido e entra nela*

``` git add .``` 			                                                          *adiciona as alterações feitas*

```git commit -m "primeiro commit em uma nova branch"```

``` git push --set-upstream origin primeira_branch```                            *sobe a branch no repositório online*

```git checkout main``` *(ou ```git checkout -``` para voltar à ramificação anterior) | volta pra ramificação principal*

``` git checkout -b segunda_branch```

``` git add .```

``` git commit -m "Mais um commit em uma nova branch"```

``` git push --set-upstream origin segunda_branch```

``` git checkout main``` 		                                                    *volta pra ramificação principal*

```git merge primeira_branch``` 	                                              *mescla a primeira branch com a principal*

```git push```

```git merge segunda_branch```	                                                *mescla a primeira branch com a principal*

```git push```

*accept both changes* no vscode e consertar o conflito manualmente

```git add .```

``` git commit -m "Resolução do conflito na Branch principal"```

```git push```
