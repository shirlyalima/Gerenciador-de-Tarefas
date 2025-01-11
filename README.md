# Gerenciador-de-Tarefas
Gerenciador de tarefas criado com PySimpleGUI.

Este projeto é um aplicativo simples de gerenciador de tarefas desenvolvido com a biblioteca PySimpleGUI. Ele permite criar, adicionar e reiniciar tarefas de forma intuitiva em uma interface gráfica minimalista.

Funcionalidades
* Adicionar Tarefas: O botão "Nova Tarefa" permite adicionar novas linhas onde o usuário pode inserir o nome de uma tarefa e marcar a caixa de seleção quando concluída.
* Resetar: O botão "Resetar" reinicia a interface, apagando todas as tarefas adicionadas.
* Interface Personalizável: O tema da interface pode ser modificado facilmente.

Como Usar
* Requisitos
Certifique-se de ter o Python instalado em sua máquina e a biblioteca PySimpleGUI instalada. Caso não tenha, instale-a com o comando:

bash
pip install PySimpleGUI

* Execução
1. Salve o código em um arquivo Python, por exemplo, gerenciador_tarefas.py.
2. Execute o script com o comando:
bash

python gerenciador_tarefas.py

Navegando no App
* Clique em Nova Tarefa para adicionar uma nova linha.
* Insira o nome da tarefa no campo de texto correspondente.
* Use a caixa de seleção para marcar as tarefas como concluídas.
* Clique em Resetar para reiniciar a interface, apagando todas as tarefas existentes.

Estrutura do Código
* Função criar_janela_inicial: Define o layout inicial da interface.
* Loop Principal: Monitora eventos (botões clicados) e executa ações correspondentes.
1. Nova Tarefa: Adiciona novas tarefas dinamicamente.
1. Resetar: Redefine a janela para o estado inicial.

Personalização
Você pode personalizar a aparência do aplicativo:
* Tema: Modifique o tema na linha sg.theme('DarkBlue4') para um tema diferente. Consulte a documentação do PySimpleGUI para outros temas disponíveis.
* Layout: Alterne os elementos ou adicione novas funcionalidades ao layout inicial.

Exemplos de Uso
1. Planejar atividades diárias.
2 Listar tarefas de estudo ou trabalho.
3. Organizar listas de compras.
