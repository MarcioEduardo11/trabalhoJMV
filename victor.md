## Seleção de datas de retirada e devolução 

### Como será feito: 
Seleção das datas, validação, verificação de disponibilidade e cálculo do valor.

### Para que serve:
Definir o período, evitar conflitos e calcular o preço do aluguel.

## Cálculo automático do valor do aluguel

### Como será feito:
Sistema calcula o valor com base no período selecionado e na tarifa definida.

### Para que serve:
Exibir ao usuário o custo total do aluguel de forma automática e precisa.

## Verificar disponibilidade do veículo

### Como será feito:
Consulta ao banco de dados para checar se o veículo está livre nas datas selecionadas.

### Para que serve:
Garantir que o veículo possa ser reservado no período escolhido.


## Cancelamento de reserva

### Como será feito:
Ação que permite ao usuário cancelar a reserva, atualizando o status no banco de dados.

### Para que serve:
Permitir o cancelamento e liberar o veículo para novas reservas.

## Histórico de reservas do usuário

### Como será feito:
Consulta ao banco de dados para listar as reservas associadas ao usuário.

### Para que serve:
Permitir que o usuário visualize suas reservas passadas e atuais.

## Painel administrativo

### Como será feito:
Interface restrita para administradores gerenciarem veículos, reservas e usuários, com operações CRUD no banco de dados.

### Para que serve:
Permitir controle e administração completa do sistema.


## Cadastro de administradores

### Como será feito:
Formulário para criação de contas administrativas, com validação e armazenamento seguro no banco de dados.

### Para que serve:
Permitir o acesso de novos administradores ao painel do sistema.

## Controle de veículos (editar/remover)

### Como será feito:
Interface administrativa para editar ou remover veículos, com alterações refletidas no banco de dados.

### Para que serve:
Manter as informações dos veículos atualizadas e gerenciar a disponibilidade no sistema.


## Controle de usuários (bloquear/excluir)

### Como será feito:
Interface administrativa para bloquear ou excluir usuários, com atualização do status no banco de dados.

### Para que serve:
Gerenciar o acesso dos usuários e manter a segurança do sistema.

## Perfil do usuário (editar dados)

### Como será feito:
Formulário para o usuário atualizar suas informações pessoais, com validação e armazenamento no banco de dados.

### Para que serve:
Permitir que o usuário mantenha seus dados atualizados e corretos no sistema.

## Exibir veículos mais alugados

### Como será feito:
Consulta ao banco de dados para calcular e listar os veículos com maior número de reservas.

### Para que serve:
Fornecer insights sobre os veículos mais populares para usuários e administradores.

## Aplicação de cupons de desconto

### Como será feito:
Sistema verifica a validade do cupom e aplica o desconto automaticamente no valor do aluguel.

### Para que serve:
Oferecer promoções e reduzir o custo total para o usuário de forma prática.

## Relatório de reservas (admin)

### Como será feito:
Geração de relatórios detalhados com dados de reservas, filtráveis por período, usuário ou veículo.

### Para que serve:
Permitir aos administradores monitorar e analisar a atividade de reservas no sistema.

## Integração com pagamento (simulado)

### Como será feito:
Simulação de transações financeiras para testar processos de pagamento sem envolver dinheiro real.

### Para que serve:
Validar o fluxo de pagamento e garantir que o sistema calcula e confirma pagamentos corretamente.

## Status da reserva (ativa, concluída, cancelada)

### Como será feito:
Registro do status de cada reserva no banco de dados, atualizado automaticamente conforme ações do usuário ou administrador.

### Para que serve:
Informar ao usuário e ao administrador a situação atual de cada reserva de forma clara.

## FAQ (perguntas frequentes)

### Como será feito:
Seção com perguntas e respostas comuns, organizada por categorias e acessível no site.

### Para que serve:
Esclarecer dúvidas dos usuários de forma rápida, reduzindo a necessidade de suporte direto.

## Compartilhamento de veículos favoritos

### Como será feito:
Opção para o usuário selecionar veículos favoritos e compartilhar via link ou redes sociais.

### Para que serve:
Permitir que o usuário compartilhe seus veículos preferidos com amigos ou familiares.

## Mapa com localização das agências

### Como será feito:
Integração com API de mapas para exibir a posição das agências no mapa interativo.

### Para que serve:
Facilitar que o usuário encontre e planeje a visita às agências mais próximas.