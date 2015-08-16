# Quack BB
Módulo de pagamentos Banco do Brasil para Magento.
Desenvolvido a partir do Manual de Orientações Técnicas, fornecido pelo Banco do Brasil.

[![Build Status](https://travis-ci.org/rafaelpatro/Quack-BB.svg?style=flat)](https://travis-ci.org/rafaelpatro/Quack-BB)

## Compatibilidade
Magento 1.4.x - 1.9.x

## Requisitos
 - Ser cliente BB
 - Aderir ao regulamento do Comércio Eletrônico do BB
 - Formalizar os convênios para as modalidades de meio de pagamento escolhidas
 
## Introdução
Esta extensão tem por objetivo gerenciar pagamentos realizados através do convênio de comércio eletrônico do Banco do Brasil.

Após a instalação, uma nova forma de pagamento fica disponível para configuração.
![image](https://cloud.githubusercontent.com/assets/13813964/9291502/8155073a-439a-11e5-96ba-1fb4cdebd3ca.png)

Ao configurar a extensão, o cliente poderá optar pela nova forma de pagamento.

Após a finalização da compra o cliente é redirecionado ao ambiente do banco.
![image](https://cloud.githubusercontent.com/assets/13813964/9291537/b6d5104c-439c-11e5-80e5-27107f33140e.png)

Um link para pagamento fica disponível para o cliente, na página do pedido.

Também é possível configurar o e-mail de novos pedidos para exibir o link para pagamento.
![image](https://cloud.githubusercontent.com/assets/13813964/9291571/8d5684fa-439f-11e5-9642-3d4c5a1e0535.png)

A extensão monitora e confirma os pagamentos através do agendamento de tarefas do Magento.

O logista ainda pode ver a situação do pagamento na página do pedido, e faturar a compra.
![image](https://cloud.githubusercontent.com/assets/13813964/9291554/059eec56-439e-11e5-997b-7762770ab451.png)

O faturamento manual online do pedido só é concretizado caso o banco tenha recebido o pagamento. Caso contrário, o logista verá uma mensagem de erro.