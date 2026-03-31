
## cadastro de usuário
### Como será feito:
 Formulário HTML5 com validação de campos via JavaScript (E-mail, CPF, Nome). Os dados são enviados e salvos em uma tabela usuarios no banco de dados SQL.
### Para que serve:
Registrar novos clientes para que possam realizar aluguéis e ter um histórico de uso.
## Login de usuários.
### Como será feito:
 Campos de entrada (Input) em HTML que consultam o banco de dados via SQL para verificar se o e-mail e a senha coincidem.

### Para que serve: 
Autenticar o cliente e garantir que apenas pessoas autorizadas acessem áreas restritas.

## Logout do sistema.
### Como será feito:
 Um botão "Sair" que, ao ser clicado, dispara um comando JavaScript para limpar a sessão do navegador.

### Para que serve:
 Encerrar a conexão do usuário com segurança, especialmente em computadores públicos.
 
## Recuperação de senha.

### Como será feito:
 Interface simples para digitar o e-mail. O sistema gera um link ou código via JavaScript/Backend e atualiza a senha no SQL (UPDATE).

### Para que serve:
 Permitir que o usuário recupere o acesso à sua conta sem precisar criar um novo cadastro.

 ## Cadastro de veículos.
 ### Como será feito: 
 Painel administrativo em HTML/CSS para inserir dados como Placa, Modelo, Marca e Valor da Diária, salvando tudo no banco de dados.

### Para que serve:
 Manter o catálogo de carros atualizado para os clientes.

## Listagem de veículos disponíveis.
### Como será feito:
 Painel administrativo em HTML/CSS para inserir dados como Placa, Modelo, Marca e Valor da Diária, salvando tudo no banco de dados.

### Para que serve:
 Manter o catálogo de carros atualizado para os clientes.


### Para que serve: 
Efetivar o aluguel e garantir que aquele carro fique bloqueado para outros usuários no período escolhido.
## Upload de imagens dos veículos.
### Como será feito:
 Utiliza a tag do HTML para selecionar arquivos. O JavaScript processa o envio da imagem para uma pasta no servidor ou serviço de nuvem.

### Para que serve:
 Permitir que o administrador cadastre fotos reais dos carros, tornando o catálogo muito mais atrativo e confiável para o cliente.

 ## Avaliação de Veículos pelos Usuários.
 ### Como será feito:
  Um sistema de "estrelas" feito com HTML/CSS. Ao clicar, o JavaScript captura a nota (ex: 1 a 5) e o SQL calcula a média aritmética de todas as notas dadas àquele carro.

### Para que serve:
 Gerar prova social e ajudar outros usuários a escolherem os melhores veículos da frota.
 ## Sistemas de comentários
 ### Como será feito: 
 Uma área de texto onde o usuário escreve sua experiência. O SQL armazena o texto vinculado ao ID do usuário e do veículo.

### Para que serve: 
Permitir um feedback detalhado sobre o estado do carro e o atendimento, aumentando a credibilidade do serviço.


 ## Notificação de cancelamento.
 ### Como será feito: 
 Quando uma reserva é excluída ou alterada no SQL, o sistema identifica a mudança e envia um aviso automático (e-mail ou pop-up) ao usuário.

### Para que serve:
 Manter o cliente informado sobre mudanças no status do seu aluguel, evitando desencontros na retirada do veículo.
 ## Suporte multíplos de idiomas.
 ### Como será feito:
  Utilização de arquivos de dicionário (JSON) em JavaScript. O sistema identifica a escolha do usuário e substitui os textos do HTML pelas traduções correspondentes (Ex: "Alugar" para "Rent").

### Para que serve:
 Tornar o software acessível para turistas e usuários estrangeiros, eliminando barreiras de comunicação no processo de reserva.
 ## Chat de suporte ao cliente.
 ### Como será feito:
  Implementação de uma janela flutuante em HTML/CSS que usa WebSockets (comunicação em tempo real via JavaScript) para enviar e receber mensagens instantâneas.

### Para que serve: 
Oferecer ajuda imediata ao usuário em caso de dúvidas sobre o veículo ou problemas no pagamento, aumentando a taxa de conversão.
