# Gerenciador de tarefas em C#

Gerenciador de tarefas feito em `C#` para simular e entender de forma simples como funciona a ordenação em `listas`

## Código

- O código foi separado em 3 arquivos para o funcionamento e organização do programa deixando legível ao usuário mesmo sem os comentários no código.
- O código possui o `Program.cs` para iniciar o programa, possuindo um menu na tela para que o usuário possa `Adicionar`, `Remover`, `Listar` e `Sair` do programa, utilizando uma lógica de programação simples com `switch-case`
- `Tarefas.cs` guarda informações do gerenciador e entrega ao usuário caso seja pedido
- `GerenciadorDeTarefas.cs` guarda as informações na lista e se comunica com `Tarefas.cs` para acessar o "Titulo" e a "Descrição" para adicionar, remover ou listar


### Usar o projeto para testes

1. Para usar o projeto para testes faça um git clone com SSH
```
git clone git@github.com:HDS0219/Gerenciador-de-tarefas-list.git
```
2. ou utilizando o https
```
git clone https://github.com/HDS0219/Gerenciador-de-tarefas-list.git
```

<!-- boa parte que está aqui é para entender e aprender como fazer um README organizado. -->
## Futuras adições!
- [ ] Arquivos de texto, para guardar as tarefas dentro dos arquivos de texto de forma organizada
- [ ] comentários no código
- [ ] Tempo de cada tarefa sendo colocado opcionalmente
