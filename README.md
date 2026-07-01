# Gerenciador de Tarefas em Python (CLI)

Um gerenciador de tarefas simples e funcional, totalmente desenvolvido em Python e executado na linha de comando (CLI). O projeto permite ao usuário adicionar, listar e marcar tarefas como concluídas, com uma interface colorida para facilitar a visualização.

Este projeto foi criado como exercício final da disciplina de **Lógica de Programação** (1º semestre), como forma de reforçar conceitos fundamentais como manipulação de listas, funções, laços de repetição e captura de entrada do usuário.

## Funcionalidades

* **Adicionar Tarefas:** Permite a criação de novas tarefas com descrição personalizada.
* **Marcar como Concluídas:** Modifica o status de uma tarefa pendente para concluída.
* **Visualização Completa:** Lista todas as tarefas cadastradas, diferenciando pendentes e concluídas por cores.
* **Filtros de Visualização:** Permite listar apenas as tarefas pendentes ou apenas as concluídas.
* **Interface Colorida:** Utiliza códigos de cores ANSI para melhorar a experiência do usuário no terminal.
* **Validação de Entrada:** Trata entradas inválidas do usuário para evitar que o programa quebre.

## Como executar

Requer apenas Python 3 instalado (sem dependências externas).

```bash
git clone https://github.com/Ana-3105-Pessoal/gerenciador-simples-tarefas-python.git
cd gerenciador-simples-tarefas-python
python Gerenciador_De_Tarefas.py
```

> **Observação:** as cores ANSI funcionam nativamente em Linux/macOS e no Windows Terminal / PowerShell moderno. Em terminais mais antigos do Windows (cmd clássico), os códigos de cor podem aparecer como texto.

## Tecnologias

* Python 3 (biblioteca padrão apenas)

## Licença

Este projeto está sob a licença MIT — veja o arquivo [LICENSE](LICENSE) para mais detalhes.
