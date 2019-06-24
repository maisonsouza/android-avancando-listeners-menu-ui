# Curso de Android parte 2: Avançando com listeners, menu e UI.
* Implementar clique longo com menu de contexto para remover da lista.
* Implementar clique curto como menu de contexto para alterar contato da lista.
* Implementar um menu de opções.

## Aula01 - Carregando aluno no formulário.
* Aba LogCat - Serve para identificar erros e exceções.
* O método putExtra permite trocar dados entre activities.
```
A técnica de transferência via extra, exige que o dado seja serializável. Sendo assim, faça com o que a classe Aluno implemente a interface Serializable.
``` 

## Aula02 - Editando aluno pelo Formulário
* Atributo id para diferenciar os objetos alunos
* Atributo id como estático e incrementando.
* Criação dos getters e setters de Aluno.
* Método hasExtra (Verifica se há algum dado no putExtra).
* Método parent.getItemAtPosition(position).
* CTRL + ALT + M (refatorações de métodos).
* CTRL + ALT + C (Criação de constantes).
* Isolar as constantes em interfaces que são publicas e final por padrão.
* setTitle para os diferentes modos (Inserção,Edição).
* Early return

## Aula03 - Removendo aluno da lista
* Uso do onItemLongClick
* Adapter clear e addAll.

## Aula04 -  Aplicando menus do Android
* registerForContextMenu.
* onContextItemSelected para criar o menu.

## Melhorando a experiência do formulário
* O ScrollView só aceita uma única viewGroup Filha.
* A rotação da tela destroi e recria a activity novamente.
* 
