
# EstoqueSeguro

# Documento de Visão

### Histórico de Revisões

| Data                |  Versão             |          Descrição  |  Autores            |
| :-----------------: | :-----------------: | :-----------------: | :-----------------: |
| 23/06/2023 | 1.0 | Versão inicial |  Grupo 5 |
| 26/06/2023 | 1.1 | Visão atualizada do projeto |  Rafael Pessoa |

<br>

## 1. Objetivo do Projeto:

O objetivo deste projeto é desenvolver e implementar um sistema de gestão de vendas de papel que permita à empresa fictícia melhorar o fluxo de abastecimento de estoque, otimizar as vendas regionais e aprimorar o trabalho em cada uma das filiais. O sistema terá como principal mercado alvo os grandes escritórios, como os de contabilidade e advocacia, que ainda dependem amplamente do uso de papel em suas operações diárias

<br>

## 2. Descrição do problema:
| **Problema**            | A empresa enfrenta dificuldades na gestão do fluxo de abastecimento de papel, o que impacta negativamente o estoque e a capacidade de atender à demanda dos grandes escritórios. Além disso, a falta de uma ferramenta adequada de gestão de vendas e estoque resulta em processos manuais ineficientes, como o uso de planilhas, levando a erros, retrabalho e falta de insights para melhorar o trabalho nas filiais.|
| --- | :---: |
| **Afeta**               |	A empresa fictícia e os escritórios de contabilidade e advocacia, que dependem do papel em suas operações diárias. |  
| **Impacto**             | A gestão ineficiente do abastecimento de papel resulta em falta ou excesso de estoque, afetando a capacidade de atender à demanda dos clientes. Além disso, o trabalho manual e o uso de planilhas levam a erros, perda de tempo e falta de visibilidade sobre as vendas e estoque, resultando em decisões menos informadas. |
| **Solução**             | O desenvolvimento e implementação de um sistema de gestão de vendas de papel que otimize o fluxo de abastecimento, promova a visibilidade das vendas e estoque, e forneça insights para melhorar o trabalho nas filiais. O sistema oferecerá recursos como determinar o momento ideal para abastecer o estoque, gerenciar fornecedores, facilitar a compra direta com as fábricas, fornecer dados analíticos sobre vendas e estoque, além de oferecer uma interface intuitiva e fácil de usar. O objetivo é melhorar a eficiência operacional, evitar perdas de vendas devido à falta de estoque e fornecer uma base sólida para a tomada de decisões estratégicas.|

<br>

## 3. Descrição dos usuários:

| **Nome** | **Descrição** | **Responsabilidade** |
| :---: | --- | --- |
| Gerente de Suprimentos | Responsável pela gestão do fluxo de abastecimento de papel na empresa fictícia. | - Utilizar o sistema de gestão de vendas de papel para determinar o momento ideal para abastecer o estoque. <br> - Gerenciar e avaliar os fornecedores de papel. <br> - Monitorar o processo de compra direta com as fábricas. <br> - Analisar relatórios e insights gerados pelo sistema para tomar decisões estratégicas relacionadas ao abastecimento de papel. |
| Equipe de Vendas| Responsável por realizar as vendas de papel para os grandes escritórios. | - Utilizar o sistema de gestão de vendas de papel para registrar as vendas realizadas. <br> - Acompanhar o estoque disponível e verificar a disponibilidade de papel para atender aos pedidos dos clientes. <br> - Acessar informações sobre os clientes e suas preferências para melhorar o atendimento. |
| Equipe de TI	 | Responsável pela manutenção e suporte do sistema de gestão de vendas de papel. |  Garantir que o sistema esteja operacional e funcione corretamente. <br> - Realizar atualizações e melhorias no sistema conforme necessário. <br> - Fornecer suporte técnico aos usuários do sistema em caso de problemas ou dúvidas. |
| Cliente	 | Representa os escritórios de contabilidade, advocacia e empresas de saúde que são os principais compradores de papel da empresa fictícia.	 | - Realizar compras de papel por meio do sistema de gestão de vendas. <br> - Acompanhar o estoque disponível e fazer pedidos com base nas necessidades do escritório ou empresa. <br> - Fornecer feedback sobre a qualidade do papel e o atendimento recebido. <br> - Utilizar recursos do sistema, como consulta a informações de produtos e relatórios de compras. |

<br>


<br>

## 4. Principais necessidades dos usuários:
- Gerir de forma eficiente o fluxo de abastecimento de papel, aumentando a visibilidade e melhorando a gestão de vendas e estoque.
- Possui dificuldade em encontrar ferramentas para a melhora do fluxo.

<br>

## 5. Alternativas concorrentes:
- Sistema de gestão genérico

<br>

## 6. Visão geral do produto:
 - Sistema de Gestão Integrado: O produto oferece um sistema de gestão integrado que permite controlar e gerenciar eficientemente o fluxo de abastecimento de papel. Ele automatiza processos e substitui o uso de planilhas e métodos manuais, proporcionando uma gestão mais precisa e eficiente do estoque.
<br>

## 7. Requisitos FUNCIONAIS:

| **Código** | **Nome** | **Descrição** | **Prioridade** |
| :---: | :---: | --- | --- |
| RF001 | Login | O sistema deverá permitir a opção de login para os usuários | Alta
| RF002 | Cadastro de Cliente | O sistema deve permitir o cadastro de clientes, incluindo informações como nome, endereço, contato e histórico de compras. | Alta
| RF003 | Gestão de Vendas| O sistema deve permitir o registro de vendas de papel, incluindo informações como cliente, quantidade vendida, preço unitário, data e forma de pagamento. | Alta
| RF004 | Monitoramento de Demandas | O sistema deve ser capaz de monitorar a demanda regional de papel, permitindo identificar padrões e tendências de compra em diferentes regiões. | Alta
| RF005 | Planejamento de abastecimento | O sistema deve fornecer funcionalidades para auxiliar no planejamento de abastecimento de papel, considerando a demanda, estoque atual e prazos de entrega dos fornecedores.| Média
| RF006 | Integração com fornecedores | O sistema deve permitir a integração com os fornecedores de papel, facilitando a comunicação, o envio de pedidos e o recebimento de informações sobre prazos de entrega e disponibilidade de produtos. | Média
| RF007 | Controle de acesso | O sistema deve ter um controle de acesso seguro, permitindo diferentes níveis de permissões para usuários, como administradores, vendedores e gerentes, garantindo a privacidade e a segurança das informações. | Alta
| RF008 | Histórico de transações | O sistema deve manter um histórico completo das transações realizadas, incluindo compras, vendas, ajustes de estoque e movimentações internas. | Média
| RF009 | Integração com o financeiro | O sistema deve permitir a integração com o setor financeiro da empresa, possibilitando o registro e controle de faturas, pagamentos e outras informações relevantes para o processo de vendas. | Alta
| RF010 | Controle de estoque aprimorado | O sistema deve fornecer um controle de estoque mais abrangente e preciso do que as planilhas (Utilização de POWERBI), incluindo informações detalhadas sobre os produtos, quantidade em estoque, datas de entrada e saída, e alertas para estoque mínimo. | Baixa
| RF011 | Rastreamento de Produtos | O sistema deve permitir o rastreamento individual de cada produto em estoque, fornecendo informações detalhadas sobre sua origem, data de fabricação, lote e outras características relevantes. | Média
| RF012 | Acompanhamento dos pedidos | O sistema deve permitir o acompanhamento dos pedidos de compra, fornecendo informações atualizadas sobre o status do pedido, datas de entrega estimadas e eventuais atrasos. | Média
| RF013 | Alertas de Reabastecimento | O sistema deve enviar alertas automáticos quando determinados produtos atingirem um nível de estoque mínimo, informando os responsáveis sobre a necessidade de reabastecimento. | Baixa
| RF014 | Emissão de NFE | O sistema deve realizar a emissão de Nota Fiscal Eletrônica para os pedidos de papel dos clientes. | Alta




<br>

## 9. Requisitos NÃO FUNCIONAIS:

| **Código** | **Nome** | **Descrição** | **Classificação** |
| :---: | :---: | --- | :---: |
| RNF001 | Tempo de Resposta | A administração deve ser capaz de garantir a  comunicação entre o servidor e o cliente, não podendo ultrapassar o tempo de 5 segundos de resposta na exportação. | Desejável
| RNF002 | Facilidade de uso | A administração deve prover um sistema com uma interface amigável que possibilite a seus usuários uma interação fácil. | Desejável
| RNF003 | Requisitos legais |O administrador deverá adequar a plataforma de acordo com as normas legais(LGPD), garantindo a integridade de dados sensíveis armazenando-os com token de segurança| Obrigatório
