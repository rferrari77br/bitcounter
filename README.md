# Contando bits em um byte

O objetivo desta tarefa é contar o número de bits 1 em um byte recebido como
entrada. No programa
fornecido como base, já há uma pequena função que converte um valor recebido na
entrada como hexadecimal e armazena o resultado numa variável de 1 byte to tipo
`unsigned char`. Também, há existe o cabeçalho de uma função `int
contar_bits_um(unsigned char c)` e algumas funções que imprimem seu resultado.
Isso significa que a solução desta tarefa se concentra somente em implementar a
função `contar_bits_um()`.

## Exemplos

Entrada | Saida
------- | -----
`00` | `0`
`FF` | `8`
`01` | `1`
`FE` | `7`
`80` | `1`
`7F` | `8`




## Instruções adicionais

1. Vá diretamente ao conjunto de testes para verificar como tratar casos
   limítrofes ou mal-definidos.
1. Lembre-se de seguir as [instruções de submissão](docs/instrucoes.md).
1. Se desejar, proponha novos casos de teste.
