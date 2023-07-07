# SQLDATABASE
Descrição:
O projeto de Sistema de Gestão para Oficina Mecânica é uma aplicação baseada em SQL que tem como objetivo auxiliar na administração de uma oficina mecânica, desde o atendimento aos clientes até a conclusão dos serviços e controle de estoque de peças. O sistema permitirá o gerenciamento de clientes, serviços, ordens de serviço (OS), autorizações de pedido, mecânicos e estoque de peças.

Entidades Principais:

Cliente: representa os clientes da oficina, contendo informações de contato, endereço e veículo.
Serviço: representa os diferentes tipos de serviços oferecidos pela oficina, como revisão, conserto e tabela de mão de obra.
OS (Ordem de Serviço): registra os detalhes específicos de cada serviço realizado, incluindo o valor do serviço, data de conclusão, valor das peças, data de emissão e status.
Autorização de Pedido: registra a autorização do cliente para a execução do serviço, contendo informações de status e data.
Mecânico: representa os mecânicos que trabalham na oficina, incluindo informações como código, nome, endereço e especialidade.
Estoque de Peças: armazena informações sobre as peças disponíveis em estoque, incluindo o tipo de peça e quantidade.
Relacionamentos:

Cliente - Autorização de Pedido: um cliente pode ter uma ou várias autorizações de pedido, enquanto cada autorização de pedido está associada a um único cliente.
Cliente - Serviço: um cliente pode solicitar um ou vários serviços, e cada serviço está associado a um único cliente.
Autorização de Pedido - Mecânico: uma autorização de pedido pode envolver um ou vários mecânicos, enquanto um mecânico pode ser associado a várias autorizações de pedido.
Mecânico - Serviço: um mecânico pode executar um ou vários serviços, e cada serviço pode ser realizado por um ou vários mecânicos.
Serviço - OS: um serviço pode estar presente em uma ou várias ordens de serviço, e uma ordem de serviço pode incluir um ou vários serviços.
OS - Mecânico: uma ordem de serviço pode envolver um ou vários mecânicos, e um mecânico pode estar associado a várias ordens de serviço.
OS - Estoque de Peças: uma ordem de serviço pode envolver uma ou várias peças em estoque, e uma peça em estoque pode estar presente em uma ou várias ordens de serviço.
Funcionalidades Principais:

Cadastro de Clientes: permite o registro de informações dos clientes, incluindo dados de contato, endereço e veículo.
Registro de Serviços: possibilita o cadastro dos serviços oferecidos pela oficina, como revisão, conserto e tabela de mão de obra.
Emissão de Ordens de Serviço (OS): permite a criação de ordens de serviço para cada serviço solicitado pelo cliente, registrando informações como valor do serviço, data de conclusão, valor das peças e data de emissão.
Autorização de Pedido: registra a autorização do cliente para a execução do serviço, mantendo o controle do status e data de autorização.
Gerenciamento de Mecânicos: possibilita o cadastro e controle dos mecânicos que trabalham na oficina, incluindo informações como código, nome, endereço e especialidade.
Controle de Estoque de Peças: permite o registro e controle das peças disponíveis em estoque, incluindo o tipo de peça e quantidade.
Essa descrição oferece uma visão geral do projeto conceitual do sistema de gestão para oficina mecânica, destacando as principais entidades, seus relacionamentos e as funcionalidades-chave que serão implementadas. Lembre-se de que essa é apenas uma estrutura básica, que pode ser expandida e adaptada às necessidades específicas do seu projeto.
