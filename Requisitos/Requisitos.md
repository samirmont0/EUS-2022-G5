# Requisitos do sistema

## Requisitos Funcionais
- Permitir cadastro de clientes (nome, número de telefone, endereço, cidade, UF, CPF, Intenções de compra) (Fonte: Software feito por aluno do grupo; Meio: Software Similar)
- Permitir cadastro de carros (modelo, marca, ano, placa, preço, cor, RENAVAM, chassi, quilometragem, acessórios), para que seja mantido um controle de estoque (Fonte: Software feito por aluno do grupo; Meio: Software Similar)
- Permitir adicionar gastos em um carro, contendo tipo de gasto (peças e/ou serviço e valor) (Fonte: Dono de loja; Meio: Entrevista)
- Possibilitar a mudança de um possível gasto de um carro para a realização do serviço
de fato, contabilizando para o valor do carro (Fonte: Funcionário; Meio: Entrevista)
- Realização de uma venda de um carro previamente cadastrado no sistema a um
cliente (Fonte: Software feito por aluno do grupo; Meio: Software Similar)
- Produção de um contrato da venda realizada contendo a forma de pagamento, os dados do cliente e da loja, os dados do carro, cláusulas de contrato, parte para assinatura das partes e data do contrato (Fonte: Software feito por aluno do grupo; Meio: Software Similar)
- Permitir o cadastro de informações de contato de fornecedores (Mecânico,
autopeças - contendo nome, telefone, e-mail, endereço...) (Fonte: Funcionário; Meio: Software Entrevista)
- Permitir obtenção de dados do carro (modelo, marca, cor, ano fabricação/ano modelo) a partir da placa do veiculo durante o cadastro do mesmo (Fonte: Cilia; Meio: Software Similar)
- Permitir a automatização da postagem de carros em redes sociais e sites de anúncios (OLX, Mercado livre, USADOFácil, etc)  (Fonte: RevendaMais; Meio: Software Similar)
- Ao cadastrar um carro que coincida com uma intenção de compra o cliente deve ser notificado (Fonte: Dono de loja; Meio: Entrevista)
- Permitir filtrar carros com base em informações fornecidas (modelo, marca, ano, preço, cor, quilometragem, acessórios) (Fonte: Dono de loja; Meio: Entrevista)
- Permitir que o administrador gere relatórios de vendas  e compras (Fonte: Dono de loja; Meio: Entrevista)
- Permitir o administrador gerar relatório de gastos e lucros obtidos (Fonte: Dono de loja; Meio: Entrevista)

## Requisitos Não-funcionais
- A obtenção dos dados do veiculo a partir da placa será obtido através de uma conexão com a API do Sinesp  (Fonte: Cilia; Meio: Software Similar)
- A automatização das postagens deve permitir a publicação em apenas um clique (Fonte: Dono de loja; Meio: Entrevista)
- A automatização das postagens será realizada através do uso das APIs das redes sociais e sites de anúncios (OLX, Mercado livre, USADOFácil, etc) (Fonte: RevendaMais; Meio: Software Similar)
- A notificação do cliente ao cadastrar um carro que corresponda a uma de suas intenções de compra deve ser feita através do WhatsApp (Fonte: Dono de loja; Meio: Entrevista)
- Relatórios de vendas e compras devem mostrar informações das vendas e compras e vincula-las aos vendedores que realizaram a mesma  (Fonte: Dono de loja; Meio: Entrevista) 
- Os papéis dos usuários devem ser divididos em Administrador e vendedor (Fonte: Software feito por aluno do grupo; Meio: Software Similar)
- O papel de Administrador deve ter acesso a todas funcionalidades do sistema  (Fonte: Software feito por aluno do grupo; Meio: Software Similar)
- A função de vendedor deve ter acesso apenas ao cadastro de carros, gastos, clientes e vendas  (Fonte: Software feito por aluno do grupo; Meio: Software Similar)
- O sistema deve obedecer a lei LGPD - Lei Geral de Proteção de Dados Pessoais, mais especificamente os artigos inseridos no capitulo 2, para proteger os dados especificados no requisito 1(Fonte: Legislação brasileira)
- O sistema deve ser desenvolvido em uma aplicação WEB, para a disponibilização das informações para os administradores de qualquer local (Fonte: Donos de loja; Meio: Entrevista)
