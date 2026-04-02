# Atividade - Estrutura Switch em Java

## Switch Tradicional

Este programa utiliza a estrutura `switch` tradicional para definir o estado da personagem Wanda com base em uma fase informada.

### Características:

* Utiliza `switch-case` com `break`
* Cada caso representa uma fase da personagem
* O `break` é necessário para evitar que os próximos casos sejam executados
* Possui um `default` para tratar valores não reconhecidos

### Execução:

Entrada:

* Valor fixo atribuído à variável `faseWanda`

Saída:

* Mensagem com o status correspondente à fase

---

## Switch Moderno (Switch Expression)

Este programa utiliza a versão moderna do `switch`, disponível em versões mais recentes do Java.

### Características:

* Utiliza `switch` como expressão
* Retorna diretamente um valor para a variável
* Não utiliza `break`
* Sintaxe mais limpa e reduzida
* Usa `->` para definir os casos

### Execução:

Entrada:

* Valor fixo atribuído à variável `faseWanda`

Saída:

* Mensagem com o status correspondente à fase

---

## Comparação

| Aspecto          | Switch Tradicional | Switch Moderno |
| ---------------- | ------------------ | -------------- |
| Uso de break     | Obrigatório        | Não utiliza    |
| Sintaxe          | Mais extensa       | Mais simples   |
| Retorno de valor | Indireto           | Direto         |
| Legibilidade     | Média              | Alta           |

---
