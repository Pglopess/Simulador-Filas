# Sistema de Fila com Servidores Concorrentes

Este projeto simula um sistema de fila única para atendimento de clientes por múltiplos servidores concorrentes, utilizando `Threads` em Java.

## 📌 Funcionalidades
- Gerenciamento de **fila normal** e **fila prioritária**.
- Atendimento simultâneo por **múltiplos servidores**.
- Simulação de tempo de atendimento variável.
- Encerramento controlado do sistema após atendimento de todos os clientes.

## 🚀 Tecnologias Utilizadas
- **Java** (versão 8 ou superior)
- **Threads** para concorrência
- **Collections API** (`Queue` para gerenciamento de filas)

## 📂 Estrutura do Projeto
```
📦 trabalhoGrauB
 ┣ 📜 Cliente.java       # Representa um cliente no sistema
 ┣ 📜 Servidor.java      # Representa um servidor que atende clientes
 ┣ 📜 SistemaFilaUnica.java  # Classe principal que gerencia o sistema
```

## ⚙️ Como Executar o Projeto

1. **Clone este repositório**:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```
2. **Compile os arquivos Java**:
   ```sh
   javac trabalhoGrauB/*.java
   ```
3. **Execute o sistema**:
   ```sh
   java trabalhoGrauB.SistemaFilaUnica
   ```

## 🔎 Como Funciona o Sistema
- **Clientes** são adicionados aleatoriamente à fila normal ou prioritária.
- **Servidores** atendem os clientes, dando preferência à fila prioritária.
- **Cada atendimento** leva um tempo aleatório entre 1 e 5 segundos.
- Após atender 30 clientes, o sistema é finalizado automaticamente.

## 🛠️ Melhorias e Expansões Futuras
- Implementar um **sistema de logs** para registrar atendimentos.
- Criar uma **interface gráfica** para visualizar o funcionamento da fila.
- Permitir **ajuste dinâmico do número de servidores** em tempo real.

📌 **Autor:** [Pedro Gustavo Thomas](https://www.linkedin.com/in/pedro-gustavo-thomas-5935392b7)

