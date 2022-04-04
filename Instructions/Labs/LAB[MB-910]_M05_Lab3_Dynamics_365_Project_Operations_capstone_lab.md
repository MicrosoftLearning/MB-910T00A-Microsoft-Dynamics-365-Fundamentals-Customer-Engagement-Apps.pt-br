---
lab:
  title: 'Laboratório 5.3: Laboratório de conclusão do Dynamics 365 Project Operations'
  module: 'Module 5: Learn the Fundamentals of Dynamics 365 Project Operations'
---

<a name="module-5-learn-the-fundamentals-of-dynamics-365-project-operations"></a>Módulo 5: Aprender os princípios básicos do Dynamics 365 Project Operations
========================

## <a name="practice-lab-53---dynamics-365-project-operations-capstone-lab"></a>Laboratório de Prática 5.3 - Laboratório avançado do Dynamics 365 Project Operations

## <a name="lab-scenario"></a>Cenário do laboratório

A empresa ABC é especializada na fabricação, comercialização, instalação e manutenção de equipamentos de segurança. Os produtos da empresa incluem câmeras de segurança internas e externas, sensores de umidade e incêndio, serviços de monitoramento e muito mais. 

A empresa ABC usa os aplicativos do Dynamics 365 para interagir com todos os clientes em diferentes áreas da organização, das vendas aos serviços. 

**Vendas e Marketing**

A empresa ABC comercializa para seus clientes residenciais diretamente por meio de campanhas de marketing direcionadas. Os clientes são segmentados de acordo com suas cidades e outros fatores. Os materiais de marketing são enviados por email e são baseados na interação com o email direcionado correspondente. 

Embora alguns de seus produtos menores sejam vendidos por varejistas, a maioria é vendida diretamente para os consumidores por meio da equipe interna de vendas.

Internamente, eles se concentram em duas áreas principais: 

- **Clientes residenciais:** Os clientes residenciais geralmente procuram componentes individuais ou uma solução para a casa inteira. Esses ciclos de vendas costumam ser mais curtos e se originam de mídias sociais, sites, referências ou contato direto com o cliente potencial. Como, no geral, os clientes residenciais estão mais focados em produtos específicos ou instalações menores, os ciclos de vendas normalmente duram alguns dias ou semanas. 

- **Clientes empresariais:** Os vendedores empresariais se concentram nos clientes que precisam de soluções de negócios mais especializadas e sob medida. As vendas corporativas geralmente se estendem por várias localizações com comunicação vinculada e, muitas vezes, requerem vários recursos para concluir o projeto. Esses ciclos de vendas costumam ser mais longos e têm muito mais peças móveis. 

É importante que todos os vendedores da empresa ABC tenham as ferramentas, os recursos e a orientação necessários, seja qual for a área de foco ao vender para os clientes. 

**Instalação do sistema:**

O processo de instalação do equipamento de segurança adquirido varia de acordo com o tipo de cliente para quem foi vendido. 

- **Clientes residenciais:** Como as instalações residenciais geralmente levam menos de um dia, elas são feitas por funcionários internos. Após a efetivação da venda, uma ordem de serviço é criada e um técnico qualificado é identificado e agendado para realizar a instalação. 

- **Clientes empresariais:** As implantações corporativas podem levar meses e exigem um gerente de projeto para supervisionar as operações do dia adia. Isso inclui a criação de planos de projeto, a definição de equipes de projeto e o agendamento de recursos. 

**Serviço e suporte:**

Assim que os sistemas são instalados, a empresa ABC fornece suporte pós-venda. Se um cliente tiver um problema, ele pode entrar em contato com o suporte ao cliente. Um agente tentará trabalhar com o cliente remotamente para resolver o problema. Se o problema não puder ser resolvido remotamente, o agente de suporte pode escalonar o problema para uma ordem de serviço que será agendada e realizada por um técnico de campo qualificado. 
## <a name="objectives"></a>Objetivos

Os vendedores da empresa ABC focam mais a atenção em clientes cujas necessidades de segurança exigem soluções comerciais mais especializadas e personalizadas. Por esse motivo, suas vendas corporativas normalmente abrangem vários locais com comunicação vinculada e frequentemente precisam de vários recursos para concluir o projeto. Os ciclos de vendas corporativas das empresas ABC podem levar muitos meses e precisam de várias partes móveis para a execução. 

Depois que um cliente corporativo compra um sistema, pode levar meses para implementar o projeto. Cada projeto é atribuído a um gerente, que supervisiona o planejamento do projeto e as operações diárias. Isso inclui a criação de planos de projeto, a definição de equipes de projeto e o agendamento de recursos. 

Como vendedor corporativo, você é responsável pela venda de soluções de segurança personalizadas de alta qualidade aos clientes. Recentemente, você recebeu uma ligação de uma empresa chamada Consolidated Sample. Ela gostaria de ter uma solução de segurança totalmente integrada que abrangesse todos os seus locais. Vamos inserir o cliente potencial da Consolidated Sample no sistema, incluí-lo por meio do ciclo de vendas do projeto e criar um projeto correspondente. 

Após a conclusão do laboratório, teremos concluído o seguinte:

- Gerenciar atividades diárias associadas a uma oportunidade de projeto. 

- Adicionar a criação e a definição da cotação de um projeto. 

- Gerar um contrato de projeto. 

- Criar um Projeto e definir uma Equipe para ele. 

## <a name="lab-setup"></a>Configuração do Laboratório

  - **Tempo estimado**: 45 minutos

## <a name="instructions"></a>Instruções

## <a name="exercise-1-create-a-project-quote--project-estimate"></a>Exercício 1: Criar a cotação e a estimativa de um projeto

A Oportunidade de Projeto é usada para capturar detalhes de alto nível sobre um possível projeto. À medida que surgem mais detalhes sobre o projeto, é possível criar uma Cotação do Projeto. A cotação do projeto frequentemente inclui detalhes relacionados a diferentes funções, cronogramas e preços. A cotação do projeto é aquilo que é apresentado ao cliente. A cotação do projeto também é onde você pode começar a criar um plano que é associado ao projeto que está sendo vendido. Isso economiza tempo depois que o projeto é vendido, pois muitos dos detalhes relacionados ao projeto já foram capturados.

Neste exercício, você criará um projeto e definirá detalhes relacionados à cotação dele. 

### <a name="task-1-create-a-project-quote"></a>Tarefa 1: Criar uma cotação de projeto.  

1. Com a Oportunidade de Projeto aberta, selecione a guia **Cotações**. 

2. Na subgrade Cotações, selecione **Nova Cotação**.

3. Depois que o registro da nova cotação for aberto, defina o campo **Lista de Preços de Produtos** na cotação para **Taxas de Fatura dos EUA**. 

4. Selecione a guia **Linhas de Cotação**.

5. Selecione e abra o item de linha **Implementação do Sistema**. 

6. No campo **Projeto**, selecione **Novo Projeto**. 

7. Na tela **Criação Rápida de Projeto**, conclua o projeto da seguinte maneira:

    - **Nome:** implementação global completa – Suas iniciais

    - **Gerente de projetos:** Selecione o registro do usuário

    - **Modelo de calendário:** Modelo de trabalho padrão

    - **Unidade contratante:** Fabrikam US

    - **Data de Início Estimada:** Daqui a uma semana

    - **Custo de Mão de Obra Estimado:** $ 175.000

    - **Custo de Despesas Estimado:** $ 50.000

    - **Custo Total Estimado:** $ 225.000

8. Selecione o botão **Salvar e Fechar**.

9. Em seguida, definiremos se podemos cobrar por funções específicas atribuídas ao projeto. Selecione a guia **Funções Cobráveis**.

10. Selecione e abra a função **Engenheiro de Robótica** e defina o tipo de cobrança como Não Cobrável.

11. Na **Barra de Comandos**, selecione o botão **Salvar e Fechar**.

12. Selecione a guia **Detalhes da Linha de Cotação**.

13. Na subgrade, selecione o botão **Detalhes da Linha da Nova Cotação**.

14. Conclua o item **Detalhes da linha de cotação** da seguinte maneira:

    - **Descrição:** Execução da Linha de Comunicação – Suas Iniciais

    - **Classe da Transação:** Hora

    - **Função:** Técnico de rede

    - **Categoria:** Hora

    - **Data de início:** Daqui a um mês

    - **Data de Término:** Daqui a dois meses

    - **Unidade de Recursos:** Fabrikam US

    - **Unidade:** Hora


15. Selecione o botão **Salvar e Fechar** para fechar o item de detalhes da linha. 

16. Na **Barra de Comandos**, selecione o botão **Salvar e Fechar**. 


**Observação:** Deixe a Cotação de Projeto aberta para que possa ser usada na próxima tarefa. 


### <a name="task-2-close-the-project-quote-and-create-a-project-contract"></a>Tarefa 2: Fechar a cotação do projeto e criar um contrato.

Nesta tarefa, você fechará a cotação de projeto criada e a converterá no contrato do projeto. O Contrato do Projeto pode ser usado e aproveitado enquanto o projeto está sendo executado. 


1. Com o registro de Cotação de Projeto **Implementação de Segurança Global Completa – Suas Iniciais** aberto, selecione o botão **Fechar como Ganho** na Barra de Comandos. 

2. Na tela **Tem certeza de que deseja fechar a cotação**, selecione **OK**.

3. Depois que a cotação for fechada, o recém-criado Contato do Projeto **Implementação de Segurança Global Completa – Suas Iniciais** será exibido. 

 

**Observação:** deixe o Contato de Projeto aberto para que possa ser usado na próxima tarefa. 

## <a name="exercise-2-manage-a-project"></a>Exercício 2: Gerenciar um projeto

Uma das vantagens de aproveitar os recursos de venda de projetos de Project Operations é a capacidade de criar um projeto durante o processo de vendas. O projeto criado poderá ser acessado de diferentes registros relacionados a vendas, como Cotações de Projetos e Contratos de Projetos. 

Neste exercício, você gerenciará algumas das tarefas iniciais relacionadas a um projeto, como definir detalhes do projeto, definir a equipe de um projeto e esboçar as tarefas do projeto. 


### <a name="task-1-manage-basic-project-data"></a>Tarefa 1: Gerenciar dados de um projeto básico. 

1. Com o Contrato do Projeto **Implementação de Segurança Global Completa - Suas Iniciais** aberto, selecione a guia **Relacionado**. 

2. No menu exibido, selecione **Projetos**.

3. Abra o Projeto **Implementação de Segurança Global – Suas Iniciais**. 

4. No Fluxo de Processo Corporativo **Serviço do Projeto**, selecione o Estágio **Novo** e selecione o botão **Próximo Estágio** para passar para o estágio **Cotação**. 

5. No estágio **Cotação**, defina o campo **Data de Término Estimada** como **daqui a seis meses**. 

6. Selecione o botão **Próximo Estágio** para passar para o estágio **Plano**. 

 
### <a name="task-2-create-a-project-team"></a>Tarefa 2: Criar a equipe de um projeto.

Cada projeto terá uma equipe de membros que auxiliará na execução do projeto. Nesta tarefa, você definirá os recursos que comporão os membros da equipe do projeto. 

 
1. Com o registro do projeto **Implementação de Segurança Global Completa – Suas Iniciais** aberto, selecione a guia **Equipe**

2. Na subgrade **Todos os Membros da Equipe**, selecione o botão **+ Novo**.

3. Configure o registro de membro da equipe da seguinte maneira:

    - **Nome da Posição:** Engenheiro de Robótica – Suas Iniciais

    - **Recurso Reserva:** Allison Dickson

    - **Função:** Engenheiro de Robótica

4. Selecione a seta próxima ao botão Salvar e Fechar. No menu exibido, selecione **Salvar e Criar Novo**.

5. Configure o próximo registro de membro da equipe da seguinte maneira:

    - **Nome da Posição:** Engenheiro de Software – Suas Iniciais

    - **Recurso Reserva:** Bob Kozak

    - **Função:** Engenheiro de Software

6. Selecione a seta próxima ao botão Salvar e Fechar. No menu exibido, selecione **Salvar e Criar Novo**.

7. Configure o registro de membro da equipe da seguinte maneira:

    - **Nome da Posição:** Técnico de Rede – Suas Iniciais

    - **Recurso Reserva:** Dianna Woodward

    - **Função:** Técnico de rede

8. Selecione o botão **Salvar e Fechar**.


### <a name="task-3-define-a-project-schedule"></a>Tarefa 3: Definir a Programação de um Projeto.

Outra parte importante da definição de um projeto é definir as tarefas do projeto e fazer a programação dele. Nesta tarefa, vamos adicionar algumas tarefas do projeto e associá-las a funções diferentes. 


1. Com o projeto **Implementação de Segurança Global Completa – Suas Iniciais** aberto, selecione a guia **Programação**. 

2. Na barra de ferramentas da subgrade de programação, selecione o botão **+ Adicionar**. 

3. Na linha que é exibida, defina o campo **Nome** como **Desenvolvimento do Sistema**.

4. Na barra de ferramentas da subgrade de programação, selecione o botão **+ Adicionar** novamente para adicionar outro item. 

5. Configure o item da seguinte maneira:

    - **Nome:** Criar layout do sistema

    - **Esforço:** 25

6. Na barra de ferramentas da subgrade de programação, selecione o botão **+ Adicionar** novamente para adicionar outra tarefa. 

7. Configure o item da seguinte maneira:

    - **Nome:** Câmeras de Design

    - **Antecessor:** Criar layout do sistema

    - **Esforço:** 50

8. Na barra de ferramentas da subgrade de programação, selecione o botão **+ Adicionar** novamente para adicionar uma tarefa final. 

9. Configure o item da seguinte maneira:

    - **Nome:** Verificar e aprovar design

    - **Antecessor:** Câmeras de Design

    - Esforço: 8 

 
**Observação:** Fique na guia de programação, pois faremos algumas modificações adicionais na próxima tarefa. 


### <a name="task-4-associate-resources-with-a-project"></a>Tarefa 4: Associar recursos a um projeto.

Como parte da definição da programação de um projeto, é possível especificar os tipos de recursos que serão usados para preencher os requisitos da equipe. Eles podem ser recursos reais nomeados ou recursos genéricos que serão substituídos por recursos nomeados no futuro. Nesta tarefa, você definirá os recursos nomeados e os genéricos para as tarefas do projeto que foram criadas. 

1. Se necessário, abra o projeto **Implementação de Segurança Global Completa – Suas Iniciais** e selecione a guia **Programação**. 

2. Localize a tarefa **Criar Layout do Sistema** adicionada anteriormente e selecione o campo **Recursos**. 

3. No menu exibido, selecione **Criar**. 

4. Configure o membro da equipe do projeto da seguinte maneira

    - **Nome da Posição:** Engenheiro de Robótica Genérico – Suas Iniciais

    - **Recurso Reserva:** Recurso Genérico

    - **Função:** Engenheiro de Robótica

5. Selecione o botão **Salvar e Fechar (Save and Close)** . 

6. Verifique se os recursos **Engenheiro de Robótica Genérico – Suas Iniciais** foram adicionados ao campo Recursos. 

7. Localize a tarefa **Câmeras de Design** e selecione o campo **Recursos**. 

8. No menu exibido, selecione **Criar**. 

9. Configure o membro da equipe do projeto da seguinte maneira:

    - **Nome da Posição:** Engenheiro de Robótica Genérico – Suas Iniciais

    - **Recurso Reserva:** Recurso Genérico

    - **Função:** Engenheiro de Robótica

10. Selecione o botão **Salvar e Fechar (Save and Close)** . 

11. Localize a tarefa **Verificar e Aprovar Design** e selecione o campo **Recursos**. 

12. No menu exibido, selecione **Allison Dickson**. 


Parabéns, você vendeu e criou com sucesso um projeto no Dynamics 365 Project Operations. Aqui, os gerentes de projeto podem gerenciar diferentes aspectos do projeto, como a programação de recursos, o monitoramento da programação do projeto e o gerenciamento de tempo e despesas. 

 

 
