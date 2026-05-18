## Respostas do questionário

# Por que o Aluno B teve seu comando git push recusado na Fase 3?

O conflito no merge ocorreu pelo fato de que duas branches tentaram modificar a mesma linha de um arquivo de maneira diferente, fazendo com que o Git pausasse a integração e exigisse uma escolha manual sobre quais modificações manter.

# Qual a utilidade real de utilizarmos comandos como git checkout -b no dia a dia de uma equipe de desenvolvimento?

Agilizar o fluxo de trabalho criando e mudando para uma nova branch em um único comando.

#  Como o Git ajuda a garantir que o código de um desenvolvedor não apague acidentalmente o trabalho de outro?

O Git previne o código de ser sobrescrito por meio de trabalhos em ramificações isoladas e pelo bloqueio de envios destrutivos para o servidor, barrando a integração automática de alterações concorrentes.