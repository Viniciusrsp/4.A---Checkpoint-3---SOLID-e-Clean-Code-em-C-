1. SRP (Single Responsibility Principle)
- Classe: GerenciadorBiblioteca
- Problema: Acumula responsabilidades de cadastro, empréstimos, devoluções e notificações.

2. OCP (Open/Closed Principle)
- Classe: GerenciadorBiblioteca
- Problema: Difícil adicionar novos tipos de notificação sem modificar a classe.

3. ISP (Interface Segregation Principle)
- Classe: GerenciadorBiblioteca
- Problema: Lógica de notificação centralizada, sem interfaces separadas.

4. DIP (Dependency Inversion Principle)
- Classe: GerenciadorBiblioteca
- Problema: Depende diretamente de métodos concretos de notificação (e-mail e SMS).

5. Clean Code - Métodos grandes
- Classe: GerenciadorBiblioteca
- Problema: Métodos como RealizarEmprestimo e RealizarDevolucao têm muitas responsabilidades.

- Consertar o Código
