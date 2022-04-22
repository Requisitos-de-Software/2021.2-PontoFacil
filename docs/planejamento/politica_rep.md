# Política de repositórios

## Histórico de versão

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 22/04/2022 | 0.1 | Criação da primeira versão do documento | [@Lorenzo7377](https://github.com/Lorenzo7377) |

## Política de branchs

<p style='text-align: justify;'> <em>Branchs</em> são ferramentas do Github que servem para permitir a atualização do repositório do trabalho por diferentes pessoas ao mesmo tempo.</p>

<p style='text-align: justify;'>Para poder atualizar os arquivos do repositório, primeiro é necessário clonar a o repositório do grupo usando a chave SSH:</p>

```
git clone "SSH Key"
```

<p style='text-align: justify;'>Caso não existam branchs auxiliares para alteração de arquivos, deverá ser criada uma para tal com o seguinte comando:</p>

```
git checkout -b "Nome da branch entre aspas duplas"
```

<p style='text-align: justify;'>Após todas mudanças serem feitas, as alterações devem ser adicionadas ao status:</p>

```
git status
git add .
```

<p style='text-align: justify;'>Depois de dado o commit, ele deve ser enviado para o Github por meio do comando:</p>

```
git push
```

<p style='text-align: justify;'>Depois de um longo debate do grupo, foram acordadas as seguintes regras a serem seguidas:</p>
<p style='text-align: justify;'><li><b>NÃO</b> serão feitos commits por parte dos membros na branch principal do projeto;</li><li>Sempre que uma das branchs for juntada à branch principal, o membro dono da branch alternativa deverá avisar para que o resto do grupo atualizem seus repositórios locais;</li><li>Cada membro deve trabalhar com arquivos diferentes em branchs diferentes para que não ocorra sobreposição de código;</li><li>Todas as branchs devem ser revisadas pela equipe antes que o processo de merge ocorra;</li><li>Todos os commits e pull requests devem ser comentados pelo autor para que haja uma pequena descrição das alterações feitas;</li></p>

