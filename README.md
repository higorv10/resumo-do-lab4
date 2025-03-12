# Construindo Arquiteturas no Azure ☁

Através do portal da Azure, é possível visualizar um globo interativo que mostra a disponibilidade dos serviços por região. Ele indica a localização dos servidores e data centers, o que permite uma visão mais clara da infraestrutura, dos recursos disponíveis em cada região e também da latência associada a essa disponibilidade. Além disso, o portal fornece informações sobre a segurança no processo de replicação entre regiões. A replicação entre regiões é uma estratégia usada para garantir a continuidade dos dados em caso de falhas em uma localidade, aumentando a resiliência e a segurança dos dados.

É importante destacar que, de acordo com a LGPD (Lei Geral de Proteção de Dados), alguns tipos de dados não podem ser transferidos para fora do Brasil. Nesses casos, é necessário fazer uma solicitação direta à Microsoft ou ao provedor do serviço de nuvem, conforme estipulado por contrato. Embora, em alguns casos, dados não precisem ser mais replicados internacionalmente, a tendência é que, com o crescimento da infraestrutura local, seja possível replicar todos os dados dentro do território nacional, atendendo às exigências legais e melhorando a performance.

#### Lab Prático 📚:

1- Criar um Grupo de Recursos: Um grupo de recursos é um container lógico onde você organiza e gerencia recursos do Azure.

2- Selecionar uma Assinatura: Em empresas que possuem múltiplas assinaturas, a escolha da assinatura correta é fundamental para gerenciar os custos e a alocação de recursos.

3- Determinar o Nome do Grupo de Recursos: Nomear o grupo de recursos para fácil identificação.

4- Selecionar a Região: A região escolhida afeta a disponibilidade e a latência dos recursos. Algumas regiões podem não ser compatíveis com determinados serviços.

5- Utilizar Marcações (Tags): Adicionar tags para categorizar os recursos, o que facilita a organização e a divisão de custos.

6- Revisar o Status da Configuração: Verificar se todos os recursos foram configurados corretamente.

7- Histórico e Logs: Acompanhar o histórico e as atividades realizadas no grupo de recursos para rastrear alterações e auditorias.

8- IAM (Controle de Acesso): O Controle de Acesso Baseado em Função (RBAC) permite que você defina permissões e atribua funções aos usuários ou grupos de segurança.

9- Bloqueios de Recursos: Impede que ações específicas sejam realizadas, como a exclusão acidental de um grupo de recursos.

10- Visualizador de Recursos: Ferramenta visual para monitorar as alterações feitas no grupo de recursos e observar os impactos dessas mudanças.

11- Eventos: Permite configurar automações que serão executadas quando certos eventos ocorrerem, melhorando a gestão de recursos.

12- Criando uma VNET (Rede Virtual): Ao criar uma VNET, você pode atualizar o grupo de recursos e acompanhar as alterações nos logs, visualizador de recursos e eventos associados.
