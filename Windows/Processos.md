# Processos

O termo o processo executa é impreciso o mais correto seria a **Thread** executa, o processo na verdade gerencia.

Todo processo tem o seguinte:

- Um programa executável que contém código executável e dados
- Uma área de endereço virtual privado, usada pra qualquer proposta que o código dentro necessitar.
- Um Token primário que é um objeto que guarda o contexto de segurança de um processo, esse Token será "herdado" pelas threads pertencentes a tal processo (a não ser que a thread use impersonation).
- Uma table privada de Handles pra eventos, arquivos, semaphores
- Uma ou mais threads em execução, quando um processo é spawnado em user-mode ele geralmente começa com uma thread que vai executar a função main/WinMain, caso o processo não tenha nenhuma Thread ele é terminado pelo Kernel.

![Processos](https://i.imgur.com/Ylvbjvw.png)


Créditos: 
# Windows Kernel Programming
#### Pavel Yosifovich

Eu realizei uma tradução e resumo do que é dito no livro.
