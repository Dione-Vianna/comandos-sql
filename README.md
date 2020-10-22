# Comandos SQL

## Selecionar uma tabela

- seleciona toda a tabela

```
SELECT * FROM nome-da-tabela
```

- Selecionar um campo

```
SELECT nome-do-campo FROM nome-da-tabela
```

- Selecionar um item em uma tabela

```
SELECT * FROM nome-da-tabela WHERE nome-do-campo = 'item-a-pesquisar'
```

- Deletar todos os itens em uma tabela

```
DELETE FROM nome-da-tabela
```

- Deletar um item

```
DELETE FROM nome-da-tabela WHERE campo-da-tabela
```

- Procurar por um campo vazio

```
SELECT campo-da-tabela FROM nome-da-tabela where campo-da-tabela is null
```

- Atualizar dados em uma tabela

```
UPDATE Nome-tabela 
SET Nome-tabela.coluna = 20
WHERE Nome-tabela.Id-coluna = 12584
```

