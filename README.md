Movvi
Encomende. Agende. Retire.

Plataforma Web + Mobile para pequenos comércios receberem encomendas antecipadas, planejarem a produção e organizarem retiradas com pagamento via Pix.

Status: planejamento do MVP · Prazo inicial estimado: 6 semanas · Validação com estabelecimento parceiro: pendente
Este README descreve a proposta e o escopo planejado. As funcionalidades abaixo ainda precisam ser implementadas e validadas; não representam recursos já disponíveis.

Sobre o projeto
A Movvi surgiu de uma necessidade observada na cantina do SENAI: os pedidos eram anotados em papel, os alunos nem sempre conheciam o cardápio e a organização das reservas e retiradas podia gerar confusões.

Durante o planejamento, a equipe identificou a necessidade de entender melhor a relação entre pedidos, pagamentos e o processo fiscal utilizado pelo estabelecimento. A proposta foi ampliada para pequenos comércios que também recebem encomendas e precisam organizar sua demanda: marmitarias, padarias, confeitarias, cafeterias e cantinas.

O foco da Movvi é conectar a compra antecipada ao planejamento do comércio. O cliente escolhe o que deseja, agenda quando vai retirar e acompanha sua encomenda. O estabelecimento sabe o que precisa produzir ou separar, em qual quantidade e para qual horário.
Problema
Pedidos recebidos por papel, mensagens ou canais separados podem dificultar o acompanhamento da operação e causar:
- Falta de acesso ao catálogo e à disponibilidade por data;
- Encomendas esquecidas, duplicadas ou registradas incorretamente;
- Pedidos acima da quantidade disponível ou da capacidade de produção;
- Concentração de retiradas no mesmo horário;
- Dificuldade para relacionar cada pagamento ao seu pedido;
- Falta de um resumo das quantidades a preparar.
Proposta de valor
Ajudar o comércio a saber o que preparar, em qual quantidade e para quando.

A plataforma reúne catálogo por data, pedidos antecipados, disponibilidade, agenda de retirada, pagamento e resumo de produção em uma mesma operação.

Exemplo: uma marmitaria recebe 30 encomendas para o dia seguinte. No painel, o responsável visualiza 18 marmitas de frango e 12 vegetarianas, distribuídas entre os horários de retirada, com a situação de pagamento de cada pedido.
Público e casos de uso
Estabelecimento	Exemplo de encomenda	Configuração necessária
Marmitaria	Almoço de amanhã com retirada às 12h	Cardápio por dia, limite de refeições e encerramento dos pedidos
Padaria	50 pães para sábado às 8h	Antecedência mínima, quantidade e capacidade de produção
Confeitaria	Bolo para sexta-feira	Tamanhos e sabores predefinidos e prazo de preparo
Cafeteria	Combo reservado para retirada pela manhã	Disponibilidade por data e capacidade de retirada
Cantina	Lanche reservado para o intervalo	Quantidade disponível e faixas de horário


Piloto proposto: uma marmitaria com cardápio diário e retirada agendada. Os demais segmentos representam possibilidades de expansão, não uma obrigação de validação simultânea no MVP.
Modelo de produto
A Movvi será uma plataforma configurável para múltiplos estabelecimentos, com uma base de software compartilhada e ambientes separados para cada comércio.

Cada estabelecimento poderá configurar:
- Nome, logo, endereço e horários de funcionamento;
- Catálogo, preços e opções predefinidas dos produtos;
- Disponibilidade e limites por data;
- Antecedência mínima e prazo de encerramento das encomendas;
- Faixas e capacidade de retirada;
- Informações e políticas apresentadas ao cliente antes da confirmação.
A personalização inicial será feita por configuração. Demandas que exijam novas funcionalidades serão avaliadas separadamente, considerando sua utilidade para o produto e o esforço de desenvolvimento.

Modelo comercial em estudo: mensalidade pelo uso da plataforma, com possível cobrança de implantação e configuração. Valores e condições ainda serão definidos após a validação com comerciantes.
Posicionamento e limites
O foco é encomenda antecipada, planejamento de produção e retirada no estabelecimento.
Dentro da proposta	Fora do MVP
Catálogo próprio de cada comércio	Marketplace para comparar estabelecimentos
Reservas e encomendas com data e horário	Entregas, frete e gestão de entregadores
Agenda e resumo de produção	Rastreamento de transporte
Pagamento Pix vinculado ao pedido	Sistema completo de caixa ou ERP
Disponibilidade para encomendas	Emissão fiscal integrada


Cada comércio poderá divulgar seu acesso por link, código ou QR Code. O cliente será direcionado à loja escolhida. Links e QR Codes terão uma alternativa para quem ainda não instalou o aplicativo, com orientações de acesso; a compra completa pelo navegador fica prevista para uma evolução.
Aplicativo mobile — cliente
O aplicativo será o canal para consultar o estabelecimento, encomendar e acompanhar a retirada.
- Cadastro, login e acesso à loja por código ou link compatível;
- Visualização do estabelecimento, catálogo, preços e opções;
- Consulta de produtos disponíveis para a data desejada;
- Seleção de produtos e quantidades;
- Escolha de data e faixa de horário disponível;
- Revisão dos itens, valores e condições da encomenda;
- Pagamento por Pix com QR Code e código copia e cola;
- Acompanhamento do pagamento e do preparo;
- Histórico de pedidos;
- Apresentação de código de retirada.
Um único aplicativo atenderá os estabelecimentos cadastrados, preservando o contexto e os dados de cada loja. O MVP não prevê um aplicativo publicado separadamente para cada comércio.
Painel web — comerciante
O painel será o ambiente de configuração e acompanhamento da operação.
- Acesso do responsável e de funcionários autorizados;
- Configuração do perfil do estabelecimento;
- Cadastro e gerenciamento de produtos, preços e opções;
- Publicação do catálogo e das quantidades disponíveis por data;
- Definição da antecedência e do encerramento de pedidos;
- Configuração de horários e limites de retirada;
- Agenda de encomendas com filtros por data, horário e situação;
- Resumo da produção agrupado por produto e opções relevantes;
- Consulta da situação dos pagamentos;
- Atualização do preparo e confirmação da retirada por código;
- Gestão de cancelamentos e acompanhamento de eventuais devoluções.
Exemplo de resumo de produção: “Amanhã: 20 marmitas de frango, 10 vegetarianas e 8 porções extras de arroz”.
Landing page — apresentação da Movvi
A página pública apresentará o produto aos comerciantes, com problema atendido, benefícios, exemplos de uso, divisão entre aplicativo e painel e canal de interesse para possíveis parceiros.
Fluxo de encomenda
1. O cliente acessa o estabelecimento e consulta o catálogo para a data desejada.
2. Seleciona produtos, quantidades e opções disponíveis.
3. Escolhe uma faixa de retirada e revisa o pedido.
4. O servidor valida preços, antecedência, disponibilidade e capacidade do horário.
5. O sistema reserva temporariamente as quantidades e a capacidade necessárias e solicita a cobrança Pix.
6. O cliente paga dentro do prazo apresentado.
7. A integração confirma o pagamento, e o pedido passa a confirmado.
8. O comerciante acompanha o resumo de produção e atualiza o preparo.
9. O cliente acompanha quando a encomenda está pronta.
10. O funcionário confere o código e registra a retirada.
Situação do pedido e do pagamento
O andamento operacional e o financeiro serão registrados separadamente.
Controle	Estados planejados
Pedido	Aguardando pagamento, confirmado, em preparo, pronto, retirado, cancelado ou expirado
Pagamento	Pendente, confirmado, expirado, falhou, devolução pendente ou devolvido


O fluxo habitual do pedido será: aguardando pagamento → confirmado → em preparo → pronto → retirado. Exceções, como pagamento tardio, exigirão tratamento próprio.
Regras de agendamento e disponibilidade
- Cada produto terá disponibilidade por data, com opções predefinidas quando necessário.
- O estabelecimento definirá a antecedência mínima e o horário de encerramento dos pedidos.
- Cada faixa de retirada terá capacidade configurável; para o piloto, a unidade proposta é quantidade de pedidos por faixa.
- O limite de produtos por data e o limite de pedidos por faixa serão verificados separadamente.
- Reservas temporárias e pedidos confirmados ocuparão a disponibilidade correspondente, evitando excesso de encomendas simultâneas.
- Reservas expiradas ou canceladas liberarão a capacidade aplicável, considerando se a produção já começou.
- Alterações de catálogo e preço não modificarão os dados já confirmados de um pedido.
- A confirmação da retirada será restrita a funcionários autorizados e não poderá ser repetida.
Disponibilidade no MVP: controle das quantidades oferecidas para encomenda por produto e data. Controle completo de estoque físico, ingredientes, lotes e validade fica para evolução. Caso o mesmo estoque seja vendido no balcão, o comércio deverá separar a quantidade destinada às encomendas ou ajustar a disponibilidade no painel.
Pagamento Pix
A integração Pix faz parte do MVP planejado, por meio de um provedor de pagamentos a definir. Inicialmente, a proposta é vincular o recebimento ao próprio estabelecimento; a Movvi não terá uma carteira própria nem dividirá valores entre vários vendedores no mesmo pedido.

Requisitos previstos:
- Cobrança identificada para cada pedido, com valor e prazo de pagamento;
- QR Code e código copia e cola no aplicativo;
- Confirmação automática pelo backend, com validação dos eventos recebidos do provedor;
- Processamento idempotente para impedir confirmação ou baixa duplicada;
- Reserva temporária alinhada ao prazo da cobrança;
- Liberação da reserva quando não houver pagamento no prazo;
- Tratamento de falhas ao gerar cobranças e de confirmações recebidas com atraso;
- Registro e acompanhamento de cancelamentos e devoluções.
Pagamento tardio: o sistema deverá verificar novamente a disponibilidade. Se não puder atender, deverá encaminhar a situação para resolução e eventual devolução, sem confirmar automaticamente uma encomenda sem capacidade disponível.

Cancelamento de pedido não será tratado como devolução já concluída. As regras de cancelamento, devolução e não comparecimento serão definidas com o parceiro e informadas ao cliente antes da compra.

O protótipo e os testes iniciais utilizarão o ambiente de testes do provedor. A operação com pagamentos reais dependerá da configuração do estabelecimento e da validação do fluxo completo.
Processo fiscal
Pagamento e documento fiscal serão tratados como processos distintos. A Movvi organizará pedidos e registrará sua situação financeira; no MVP, o processo fiscal continuará no sistema utilizado pelo estabelecimento.

A viabilidade do piloto deverá considerar como o comerciante relacionará os pedidos da Movvi ao caixa e à emissão fiscal existentes. Uma integração com esses sistemas poderá ser estudada posteriormente. A confirmação do Pix e o código de retirada não serão apresentados como documentos fiscais.
Identidade visual
Nome: Movvi
Assinatura proposta: Encomende. Agende. Retire.

A direção visual apresentada combina um símbolo de “M” com curvas, tipografia de peso forte e cores vermelha, preta e branca. O objetivo é comunicar movimento, praticidade e organização.

Diretrizes iniciais:
- Utilizar versões do logo para fundos claros e escuros;
- Aplicar o vermelho em ações principais e destaques, mantendo leitura e contraste nas interfaces;
- Diferenciar ações da marca de mensagens de erro, sucesso e atenção por texto e ícones, além da cor;
- Testar o símbolo isolado como ícone do aplicativo e em tamanhos pequenos;
- Preparar uma versão monocromática;
- Destacar a identidade do estabelecimento em sua loja, com assinatura discreta “Powered by Movvi”;
- Dar maior presença à marca Movvi na landing page e no ambiente de gestão.
Os códigos oficiais de cores, a família tipográfica, os arquivos vetoriais e as regras de aplicação ainda serão consolidados. O logo apresentado é a referência visual inicial.
Escopo do MVP
Incluído	Evoluções futuras
Aplicativo do cliente	Compra completa pelo navegador
Painel web do comerciante	Integrações com caixa, ERP e emissão fiscal
Cadastro e configuração de estabelecimentos	Pedidos recorrentes e assinaturas
Catálogo e disponibilidade por data	Controle de ingredientes e fichas técnicas
Encomendas e retirada agendada	Estoque físico, lotes e validade
Limites de produtos e horários	Alertas de validade e sugestões de desconto
Resumo de produção	Previsão avançada de demanda
Pix em ambiente de testes e fluxo de devolução validado	Operação Pix em produção após validação
Acompanhamento do pedido e código de retirada	Notificações push
Landing page de apresentação	Integrações IoT, se houver necessidade validada


O módulo de prevenção de perdas do planejamento anterior será adiado para priorizar o fluxo completo de encomenda, pagamento e retirada. Entregas e marketplace não fazem parte do posicionamento inicial.
Arquitetura e tecnologias propostas
Mobile e web compartilharão um backend responsável pelas regras de negócio, isolamento de estabelecimentos e integração de pagamentos.
Camada	Tecnologia proposta	Responsabilidade
Aplicativo mobile	Flutter + Dart	Jornada do cliente
Painel web e landing page	Next.js + TypeScript	Gestão e apresentação comercial
Banco de dados	PostgreSQL	Estabelecimentos, catálogo, disponibilidade, pedidos e pagamentos
Backend e autenticação	Supabase com funções de servidor, ou API própria	Autenticação, autorização e operações de negócio
Atualizações de status	Supabase Realtime, se adotado	Sincronização do andamento dos pedidos
Pagamentos	Provedor com integração Pix, a definir	Cobranças, confirmações e devoluções
Prototipação	Figma	Fluxos e interface


As tecnologias são propostas e serão confirmadas pela equipe. A integração de pagamentos e as operações que alteram disponibilidade serão executadas no servidor, sem expor credenciais nos aplicativos.
Segurança e confiabilidade
- Isolar os dados de cada estabelecimento no servidor e no banco;
- Diferenciar permissões de cliente, responsável e funcionário;
- Permitir que cada cliente consulte apenas seus próprios pedidos;
- Validar preços, opções, datas e limites no backend;
- Reservar quantidades e horários de forma transacional;
- Validar a autenticidade dos eventos de pagamento e conferir sua associação ao pedido;
- Manter histórico das mudanças de pedido e pagamento;
- Restringir e registrar o uso dos códigos de retirada;
- Coletar apenas os dados necessários à operação.
Cronograma inicial — 6 semanas
Semana	Entrega planejada
1	Validar a rotina do parceiro, regras de encomenda, processo fiscal existente e viabilidade do provedor Pix; prototipar os fluxos
2	Modelar os dados, autenticação, isolamento por estabelecimento e estrutura dos projetos
3	Implementar catálogo por data, disponibilidade, carrinho e agendamento
4	Implementar painel, resumo de produção, status e conferência de retirada
5	Integrar Pix em testes, expiração, confirmações, cancelamentos e devoluções; preparar landing page
6	Testar os fluxos integrados, executar piloto demonstrativo, corrigir falhas e documentar


O prazo é uma estimativa acadêmica e depende da equipe, do acesso ao parceiro e do provedor. Se necessário, o piloto utilizará dados simulados e pagamentos em ambiente de testes.
Critérios de validação
- O cliente consegue consultar a disponibilidade, encomendar, pagar em testes e acompanhar a retirada.
- O comércio visualiza as encomendas por horário e o total a produzir por produto.
- Pedidos simultâneos não ultrapassam os limites configurados.
- Reservas não pagas expiram e liberam a disponibilidade.
- Eventos de pagamento repetidos não duplicam a confirmação.
- Pagamentos tardios, cancelamentos e devoluções têm tratamento verificável.
- O código de retirada só pode ser utilizado uma vez e por funcionário autorizado.
- Um estabelecimento não acessa os dados de outro.
Indicadores do piloto: tempo para registrar e localizar pedidos, erros de encomenda, conflitos de horário, retiradas concluídas na faixa prevista e diferença entre quantidades encomendadas e preparadas. As metas serão definidas após observar a rotina atual do parceiro.
Próximos passos
- [ ] Selecionar um estabelecimento parceiro e validar o problema;
- [ ] Confirmar as regras de agendamento, capacidade, cancelamento e não comparecimento;
- [ ] Documentar como pedidos e pagamentos serão relacionados ao processo fiscal existente;
- [ ] Selecionar o provedor Pix e validar seu ambiente de testes;
- [ ] Consolidar os arquivos e as diretrizes da identidade visual;
- [ ] Prototipar aplicativo, painel e landing page;
- [ ] Confirmar as tecnologias e modelar os dados;
- [ ] Implementar o MVP e executar os critérios de validação;
- [ ] Avaliar os resultados do piloto antes de ampliar segmentos e funcionalidades.
Projeto acadêmico em planejamento, com foco em tornar as encomendas e retiradas de pequenos comércios mais organizadas e previsíveis.
