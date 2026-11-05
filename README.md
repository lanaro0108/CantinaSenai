Plataforma Inteligente de Pedidos e Encomendas
Mais previsibilidade para quem vende, mais praticidade para quem compra e menos desperdício para todos.

Status: planejamento do MVP · Prazo previsto: 6 semanas · Nome comercial: a definir
Sobre o projeto
A Plataforma Inteligente de Pedidos e Encomendas é uma solução Web + Mobile para pequenos estabelecimentos que trabalham com pedidos antecipados, reservas e retiradas agendadas.

O projeto surgiu da necessidade de organizar pedidos e reservas de lanches e almoços na cantina do SENAI, mas foi ampliado para atender também marmitarias, padarias, cafeterias, confeitarias e outros pequenos comércios.

Em um único ecossistema, o cliente faz seu pedido e acompanha o andamento, enquanto o comerciante gerencia a demanda, os horários e o estoque. Um módulo de prevenção de perdas identifica produtos próximos do vencimento e sugere ações comerciais.
Problema que queremos resolver
Muitos pequenos comércios ainda recebem encomendas por mensagens, anotações ou planilhas separadas. Isso pode causar:
- Pedidos perdidos ou registrados incorretamente;
- Conflitos de horários e dificuldade para organizar retiradas;
- Falta de previsibilidade sobre a quantidade a produzir ou separar;
- Divergências entre as vendas e o estoque disponível;
- Perdas por produtos que se aproximam do vencimento.
Nossa solução
                       CLIENTE (APP MOBILE)
                   Escolhe, reserva e acompanha
                                |
                                v
                    BACKEND + BANCO DE DADOS
            Pedidos • Horários • Estoque • Validades
                       /                   \
                      v                     v
             PAINEL DO COMÉRCIO       ASSISTENTE DE PERDAS
          Gestão e monitoramento      Alertas e recomendações

        LANDING PAGE: apresenta a solução aos comerciantes
1. Aplicativo mobile — clientes
- Visualização do catálogo de produtos, preços e disponibilidade;
- Criação de pedidos e reservas antecipadas;
- Seleção de data e horário para retirada;
- Acompanhamento do status do pedido em tempo real;
- Consulta ao histórico de pedidos e às ofertas disponíveis.
2. Painel Web — comerciantes
- Cadastro e gerenciamento de produtos;
- Recebimento e atualização do status dos pedidos;
- Organização das reservas e dos horários de retirada;
- Definição da capacidade de atendimento por faixa de horário;
- Visualização de pedidos futuros para apoiar o planejamento;
- Gestão de estoque, lotes e datas de validade;
- Aprovação ou rejeição de sugestões de desconto.
3. Assistente de prevenção de perdas
- Identificação de lotes próximos do vencimento;
- Alertas sobre produtos que exigem atenção;
- Sugestões de descontos a partir de regras configuráveis;
- Publicação de ofertas somente após aprovação do comerciante.
No MVP, as recomendações podem ser geradas por regras transparentes (prazo de validade, quantidade e limites de desconto). Análises preditivas e um agente de IA mais avançado ficam para evoluções futuras.
4. Landing page
- Apresentação da plataforma e seus benefícios;
- Explicação do funcionamento para clientes e comerciantes;
- Demonstração das principais funcionalidades;
- Canal de interesse para possíveis estabelecimentos parceiros.
Principal diferencial
A plataforma não se limita a registrar pedidos. Ela conecta demanda antecipada, capacidade de atendimento, disponibilidade de estoque e prevenção de perdas.

Exemplo: ao receber 20 reservas de refeições para o dia seguinte, o estabelecimento visualiza a demanda antecipadamente. As quantidades ficam reservadas no sistema, os horários são organizados e o comerciante recebe alertas sobre produtos próximos do vencimento que podem receber ofertas.
Fluxo básico de pedido
1. O cliente acessa o catálogo e seleciona os produtos.
2. Escolhe a data e um horário de retirada disponível.
3. Confirma o pedido; o sistema reserva temporariamente as quantidades e a capacidade necessárias.
4. O comerciante recebe o pedido e acompanha a fila de preparo.
5. O status é atualizado em tempo real: recebido → confirmado → em preparo → pronto → retirado.
6. Ao finalizar a venda, o sistema registra a movimentação de estoque correspondente.
Regras importantes: o sistema deve evitar reservas acima do estoque disponível, liberar reservas canceladas ou expiradas e impedir a venda de produtos vencidos. Para produtos com validade, o estoque deve ser acompanhado por lote, e não apenas por quantidade total.
Pagamentos
Como os estabelecimentos podem ter necessidades fiscais e operacionais diferentes, os meios de pagamento serão configuráveis.
- MVP: pagamento presencial na retirada ou confirmação de pagamento realizado diretamente ao estabelecimento;
- Evolução: integração com gateway de pagamento, conciliação e fluxos de cancelamento/reembolso.
A plataforma não substitui as obrigações fiscais do comerciante. A emissão de documentos fiscais, quando exigida, deve seguir as regras aplicáveis ao negócio, independentemente do método de pagamento.

Escopo do MVP — 6 semanas
Incluído no MVP	Evoluções futuras
Aplicativo de clientes	Pagamento online integrado
Painel Web do comerciante	Integração com ERP e sistemas de caixa
Cadastro de produtos e estabelecimentos	Pedidos recorrentes e assinaturas
Pedidos e reservas com horários	Modelos avançados de previsão de demanda
Atualização de status em tempo real	Assistente com IA generativa
Estoque sincronizado e controle básico de lotes	Controle avançado de ingredientes e fichas técnicas
Alertas de validade e sugestões simples de desconto	Integrações IoT
Landing page de apresentação	Marketplace e expansão comercial


O desenvolvimento inicial será validado com a cantina do SENAI como caso de uso, mantendo a estrutura preparada para múltiplos estabelecimentos. O piloto pode utilizar dados e pedidos simulados caso não haja autorização para operar na cantina.
Tecnologias previstas (sugestão)
Camada	Tecnologia
Aplicativo mobile	Flutter + Dart
Painel Web e landing page	Next.js + TypeScript
Banco de dados	PostgreSQL
Backend e autenticação	Supabase (ou API própria, se necessário)
Atualizações em tempo real	Supabase Realtime
Design e prototipação	Figma


A stack ainda pode ser ajustada conforme a experiência da equipe e os requisitos validados.

Cronograma inicial
Semana	Entrega principal
1	Pesquisa com comerciantes, requisitos, fluxos e protótipo no Figma
2	Banco de dados, autenticação e estrutura dos projetos
3	Catálogo, carrinho, pedidos e reservas
4	Painel do comerciante e sincronização do estoque
5	Atualizações em tempo real, alertas de validade e landing page
6	Testes integrados, piloto demonstrativo, ajustes e documentação


Indicadores para validar a solução
- Tempo gasto para registrar e localizar um pedido;
- Quantidade de conflitos ou erros de reserva;
- Percentual de retiradas concluídas no horário previsto;
- Divergências entre estoque registrado e disponível;
- Quantidade de produtos em risco de vencimento identificados pelo sistema.
Segurança e confiabilidade
- Cada comércio acessa somente seus próprios dados e pedidos;
- Permissões distintas para cliente e comerciante;
- Reservas de estoque e confirmações de pedidos precisam ser transacionais;
- Alterações em preço, disponibilidade e desconto devem ser validadas no servidor;
- Dados pessoais devem ser coletados apenas quando necessários ao serviço;
- Informações de validade não substituem a conferência física e as boas práticas de armazenamento.
Próximos passos
- [ ] Validar o problema com estabelecimentos reais;
- [ ] Escolher o nome e a identidade visual;
- [ ] Definir regras de pedido, reserva, cancelamento e estoque;
- [ ] Projetar as telas do aplicativo e do painel;
- [ ] Modelar o banco de dados;
- [ ] Implementar e testar o MVP.
Projeto acadêmico em fase de planejamento, com foco em tornar pequenos negócios mais organizados, previsíveis e eficientes.
