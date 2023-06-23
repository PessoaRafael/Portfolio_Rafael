<h3 align="center">
  <a href="[https://github.com/tads-cnat/MipsCode](https://github.com/tads-cnat/MipsCode)">
    <img alt="Logo" src="../../Banner.png" width="400">
  </a>
</h3>

# Documento de Visão

### Histórico de Revisões

| Data                |  Versão             |          Descrição  |  Autores            |
| :-----------------: | :-----------------: | :-----------------: | :-----------------: |
| 23/06/2023 | 1.0 | Versão inicial |  Grupo 5 |
| XX/XX/2023 | 1.1 | Visão atualizada do projeto |  Rafael Pessoa |

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
| RF001 | Login | O usuário e visitante terão a opção de login disponibilizada de acordo com o nível de permissão do usuário. |
| RF002 | Cadastro | O visitante terá acesso ao cadastro para o uso de mais funcionalidades do site. |
| RF003 | Acessar documentação | O usuário/visitante deverá ter a disponibilização da IDE para uso. |
| RF004 | Acessar IDE | O usuário/visitante irá acessar a área do site que possui a documentação do MIPS Assembly. |
| RF005 | Contatar | Usuário e visitante poderão contatar a equipe desenvolvedora. |
| RF006 | Console decimal | Todos os usuários terão exibidos os valores dos registradores e do console. |
| RF007 | Montar código | O usuário/visitante poderá realizar a compilação do código assembly |
| RF008 | Voltar uma etapa | Todos os usuários podem retroceder uma linha da execução do código, manualmente. |
| RF009 | Avançar uma etapa | Todos os usuários podem executar o código linha por linha manualmente. |
| RF010 | Executar código | O usuário e visitante poderá executar o código completo após compilado. |
| RF011 | Desmontar código | Usuário e Visitante poderão cancelar o processo de compilação do código assembly. |
| RF012 | Visualizar registradores | Será disponibilizado para todos a visualização de registradores na versão mobile. |
| RF013 | Abrir console |Usuário e Visitante poderão abrir um console que mostra o resultado do código que já foi rodado na versão mobile. |
| RF014 | Acessar dashboard | O usuário poderá entrar na área de apresentação das funcionalidades do sistema. |
| RF015 | Filtrar projetos | O usuário poderá filtrar entre as opções dada pelo sistema os projetos solicitados. |
| RF016 | Acessar tutoriais | O usuário poderá entrar na área de guia de aprendizagem. |
| RF017 | Favoritar projetos | O usuário poderá favoritar um ou mais projetos para melhor identificação. |
| RF018 | Gerenciar perfil | O usuário poderá: Inserir, editar, excluir dados(bio, foto, e-mail, nome, github…) e mudar tema do site. |
| RF019 | Filtrar tutoriais | O usuário poderá: Filtrar entre as opções dada pelo sistema os tutoriais solicitados. |
| RF020 | Acessar fórum externo | Acessar fórum da comunidade externa ao site. |
| RF021 | Exportar arquivo | Usuário e visitante poderão fazer download de arquivo de texto referente ao código. |
| RF022 | Importar arquivo | Usuário e visitante poderão fazer o download do arquivo de texto referente ao código. |
| RF023 | Manter Projeto | Apenas o usuário poderá Criar, editar, salvar e excluir projetos que sejam visíveis para os usuários. |
| RF024 | Manter tutoriais | Apenas o usuário poderá Criar, editar, salvar e excluir tutoriais que sejam visíveis para os usuários. |
| RF025 | Manter os usuários cadastrados | A administração deverá poder: Criar, editar, excluir, salvar e alterar permissão de acesso. |

<br>

## 9. Requisitos NÃO FUNCIONAIS:

| **Código** | **Nome** | **Descrição** | **Prioridade** |
| :---: | :---: | --- | :---: |
| RNF001 | Tempo de Resposta | A administração deve ser capaz de garantir a  comunicação entre o servidor e o cliente, não podendo ultrapassar o tempo de 5 segundos de resposta na exportação. | Desejável
| RNF002 | Facilidade de uso | A administração deve prover um sistema com uma interface amigável que possibilite a seus usuários uma interação fácil. | Desejável
| RNF003 | Manutenção e suporte da IDE |O administrador irá garantir o funcionamento correto da IDE, assegurando um alto grau de impacto.| Obrigatório
| RNF004 | Monitorar os tutoriais | A administração deverá manter a qualidade dos tutoriais. | Desejável
| RNF005 | Requisitos legais |O administrador deverá adequar a plataforma de acordo com as normas legais(LGPD), garantindo a integridade de dados sensíveis armazenando-os com token de segurança| Obrigatório
| RNF006 | Disponibilidade de armazenamento de arquivos | O sistema deverá realizar o gerenciamento de cache para armazenamento de arquivos locais com espelhamento interno.| Obrigatório
| RNF007 | Exportação de Arquivo | O sistema deve ser capaz de disponibilizar o arquivo exportado pelo usuário em extensão ASM e XML. | Obrigatório
