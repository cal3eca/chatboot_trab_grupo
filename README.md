# chatboot_trab_grupo
# Estrutura do projeto de Encerramento Do módulo 1 (Fale comigo)

Esse repositório contém os arquivos que foram utilizados para a realização do projeto em grupo, para o encerramento do módulo 1
do curso de Analise de dados do Senac - Botafogo.

Criado por: Diego de Arruda Nieto, Douglas Klem Portugal
do Amaral, Matheus Barbosa Furtado e Yasmin Belo da Silva

Data de criação: 12/01/2023
versão = '4.0'

##PROBLEMA DO PROJETO:

Sua equipe foi chamada para criar um projeto que vai ajudar com atendimentos automatizados de dúvidas sobre a empresa e no futuro vai coletar informações para auxiliar na tomada de decisão. Desenvolvemos um código que lista opções de atendimento e o usuário é guiado por mensagens avançando dentro desse atendimento simulado até que chegue ao final obtendo a resposta desejada.

##RESOLUÇÃO:

Escolhemos uma empresa no ramo de atuação com coleta labotatorial e clínica diagnóstica.

A ideia de como nosso programa funciona é, há mensagens que são enviadas ao usuário de início onde é perguntado para esse um número de 1 a 5 de sua escolha contendo nesses valores as funcionalidade da clínica que elx deseja acessar, ou também uma mensagem para sair da aplicação. Nesse momento são utilizados os comandos (def), para separar as opções que irão estar no chat.

Após isso, o programa inicia com um contador no 0 Onde utilizando a função (while) que é um laço de repetição e aqui destacamos que enquanto a váriavel inicial que está definida em '0', for diferente de um número especifico, o programa continuará executando.

Dentro desse laço de repetição, destacamos diversas condições (If, else, elif), onde a partir disso construimos a conversa entre usuário e máquina, através de perguntas e respostas padronizadas.

ex: Caso usuário escolha no início o número 1, vá para um menu. existindo aqui, 5 opções de escolha, sendo a última com a função de parar o programa.

Funções e Códigos utilizados
**** def > Fazer o conjunto de mensagens que vão aparecer na tela, para a escolha do usuário. ****input > Dar o poder de escolha para quem utiliza a aplicação ****While Criar um laço de repetição onde, acaba a partir de uma instrução específica. ****If, else, elif > Criar a conversa entre usuário e maquina ****break > Fazer com que o atendimento seja encerrado ****pass > Fazer com que o programa faça um looping, e retorne ao início.
