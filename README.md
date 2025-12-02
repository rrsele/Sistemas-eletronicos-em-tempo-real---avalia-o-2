## 🎯 Objetivo do Projeto
Este projeto tem como objetivo desenvolver um *jogo multiplayer simples* que demonstre, de forma prática, os principais conceitos da disciplina de *Programação Concorrente e Comunicação entre Processos (IPC)*.  
O jogo simula uma competição entre jogadores que, em turnos controlados pelo servidor, realizam jogadas até que um deles alcance o objetivo definido.  

Além de ser uma aplicação lúdica, o projeto serve como laboratório para explorar:
- Criação e gerenciamento de *processos* e *threads*.
- Uso de *semáforos, mutexes e variáveis de condição* para sincronização.
- Comunicação entre processos via *pipes, memória compartilhada e sinais*.
- Demonstração de *condições de corrida* e suas soluções.

---

## ⚙ Como Executar

### Pré-requisitos
- Sistema operacional Linux (ou compatível com POSIX).
- Compilador gcc.
- Bibliotecas POSIX habilitadas (pthread, rt).

### Passos
1. Clone ou copie o projeto para sua máquina.
2. Compile o código:
   ```bash
   gcc servidor.c -o servidor -lpthread -lrt
