# 🚆🏴‍☠️ Trens - Controle de Concorrência

Repositório para agregar o projeto de **Simulação de Condições de Corrida entre trens por trilhos**, desenvolvido em **Java** com interface gráfica em **JavaFX**.  

O projeto tem como objetivo demonstrar, de forma prática, os problemas e soluções de concorrência em sistemas computacionais, aplicados a um cenário de trens que compartilham trilhos em variadas combinações de posicionamento inical do trajeto.

---

## 🧩 Funcionalidades
- Simulação de corrida entre trens em trilhos compartilhados.  
- Interface gráfica desenvolvida em **JavaFX**.  
- Implementação de **mecanismos de controle de concorrência**, tais como:
  - Variáveis de Travamento  
  - Estrita Alternância  
  - Solução de Peterson  

---

## 🛠️ Tecnologias Utilizadas
- **Java 8**  
- **JavaFX**
- **Threads**
- Padrão de arquitetura **MVC (Model-View-Controller)**  

---

## 📂 Estrutura do Projeto

```

├── assets/ # Recursos estáticos (imagens, ícones etc.)
├── controller/ # Lógica de controle da aplicação
├── model/ # Classes de modelagem do projeto
├── view/ # Marcação gráfica (FXML)
└── Principal.java # Classe principal de execução

```

---

## 🖥️ Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/ItaloSLeao/Trens-Controle-Concorrencia.git
   ```
   
2. Abra o projeto em um Terminal de Comandos. Compile e execute a classe **Principal.java** usando os comandos:

   ```java
   javac Principal.java
   java Principal

---

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como parte da disciplina Programação Concorrente, com o objetivo de aplicar e ilustrar conceitos de **exclusão mútua** e **espera ocupada** (*busy-waiting*) entre processos.

---

## 📄 Licença

Este projeto é de uso acadêmico e está sob a licença MIT
