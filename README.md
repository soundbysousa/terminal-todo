# Terminal To-do
Boas vindas ao Terminal To-do, meu aplicativo escrito em Python e SQLite para organização de tarefas!

![image](assets/terminal_print.png)

## Instalação
### Linux e macOS:
```sh
git clone https://github.com/jettsteel/terminal-todo
cd terminal-todo/src
chmod +x todo
```
Para executar, use o seguinte comando:
```
todo
```

**Para executá-lo em qualquer lugar, siga as instruções do seu shell para colocar o script no path!**

### Windows:
Apenas vá para releases e baixe o arquivo `todo.exe`.

## Sigam o tutorial abaixo para aprender os comandos:
### help
![help](assets/help.png) <br>
O comando `help` basicamente mostra todos os comandos, para fácil e rápida consulta!
```
> help
```

### todo
![todo](assets/todo.png) <br>
O comando todo é, sem dúvidas, a base do projeto. Com ele, é possível adicionar itens a datas específicas ou criar novas datas.
```
command data item
> todo hoje criar uma saga!
```

### done
![done](assets/done.png) <br>
O comando `done` é outro comando muito importante: com ele que você finaliza as tarefas e sente aquela boa sensação de realização. Os itens são excluídos da database principal, mas são adicionados a outra database justamente para caso você precise consultá-los depois.
```
done item
> done programação
```

### show e showall
Os comandos `show` e `showall` possuem o mesmo objetivo: mostrar os TODOs. A única diferença é que o `show` precisa de um argumento: a data para ver os itens daquele dia.
```
show data
> show hoje
```
![show](assets/show.png)
```
> showall
```
![showall](assets/showall.png)

### showdone
![showdone](assets/showdone.png) <br>
O comando `showdone` é similar ao `showall`, com a diferença dele mostrar os itens finalizados, não os TODOs.
```
> showdone
```

### reset
![reset](assets/reset.png) <br>
O comando `reset` **exclui todos os bancos de dados (as databases), use-o com precaução**.
```
> reset 
> sim eu tenho
```

## Conclusão
Bom, é isso, espero que meu pequeno app te ajude! Boa sorte!
