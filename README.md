Descrição de projeto (pois infelizmente não condigo usar o AWS)

Automação de Tarefas com AWS Step Functions e Amazon Bedrock:

- Este projeto explora o uso de AWS Step Functions e Amazon Bedrock para automatizar fluxos de trabalho. A proposta é descrever uma forma prática e intuitiva de configurar esses serviços para gerenciar tarefas em sequência.

Objetivo:

- Criar uma automação que usa AWS Step Functions para definir, em etapas detalhadas, um workflow automatizado, utilizando JSON ou ASL (Amazon States Language) como fluxograma para ilustrar as etapas.

Ideia do projeto:
- Recepção do pedido: O usuário insere o pedido e o workflow aciona uma função para registrar o pedido e verificar a disponibilidade do restaurante, além de oferecer sugestões para complementar o desejo do cliente.

- Processamento do pedido: A workflow utiliza uma função para confirmar o pedido, estimar o tempo de preparo e notificar o usuário sobre o tempo estimado de entrega.

- Acompanhamento do pedido: Durante o processo de entrega, o workflow se comunica com o serviço de rastreamento para atualizar o usuário em cada etapa.

- Confirmação da entrega: Após a entrega, o workflow envia uma notificação ao usuário para confirmar que ele recebeu o pedido e solicita feedback.

O que aprendi:

- Organizar tarefas em etapas com Step Functions, entendendo o formato ASL e com ele interage JSON para estruturar as operações.

- Representar as tarefas como fluxogramas para tornar o fluxo mais fácil de entender.

- Utilizar Bedrock para monitorar e gerenciar os processos em tempo real.