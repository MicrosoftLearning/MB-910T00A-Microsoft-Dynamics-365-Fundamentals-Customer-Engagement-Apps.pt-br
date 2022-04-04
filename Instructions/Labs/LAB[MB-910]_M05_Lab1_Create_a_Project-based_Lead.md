---
lab:
  title: 'Laboratório 5.1: criar um cliente potencial baseado em projeto'
  module: 'Module 5: Learn the Fundamentals of Dynamics 365 Project Operations'
---

<a name="module-5-learn-the-fundamentals-of-dynamics-365-project-operations"></a>Módulo 5: Aprender os princípios básicos do Dynamics 365 Project Operations
========================

## <a name="practice-lab-51-create-a-project-based-lead"></a>Laboratório de prática 5.1: criar um cliente potencial baseado em projeto

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

- Inserir um cliente potencial de projeto no Dynamics 365 Sales

## <a name="lab-setup"></a>Configuração do Laboratório

  - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

## <a name="exercise-1-create-a-project-based-lead"></a>Exercício 1: criar um cliente potencial baseado em projeto

### <a name="task-1-create-a-new-lead"></a>Tarefa 1: Crie um novo Cliente Potencial

1. Se necessário, abra um navegador InPrivate e navegue até [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. Quando solicitado, faça login com as credenciais do usuário fornecidas a você pelo instrutor. 

3. Na lista de aplicativos exibida, selecione **Serviço de Projeto**. 

4. Se o Serviço do Processo não aparecer, visite trials.dynamics.com e instale a avaliação do Serviço de Projeto. 

    - Email de trabalho: Email do locatário. 

    - Número de telefone: número do telefone celular

5. Usando a navegação no lado esquerdo da tela, selecione a área **Vendas**. 

6. Usando a navegação, selecione **Clientes Potenciais**. 

7. Para exibir todos os clientes potenciais de vendas atuais no sistema, selecione a seta para baixo próxima a **Meus clientes potenciais em aberto**; no menu exibido, selecione **Clientes Potenciais Ativos**. 

8. Para voltar à lista de clientes potenciais, selecione a seta para baixo próxima a Clientes Potenciais Ativos e, no menu exibido, selecione **Meus Clientes Potenciais em Aberto**. 

9. Em seguida, criaremos um novo cliente potencial para uma empresa chamada Consolidated Sample. Na exibição **Meus Clientes Potenciais em Aberto**, selecione o botão **Novo** na Barra de comandos.

10. Preencha o novo registro de clientes potenciais da seguinte maneira:

    - **Tópico:** implementação global completa – Suas iniciais

    - **Tipo:** baseado no trabalho

    - **Nome:** Jean

    - **Sobrenome:** Anderson - Suas iniciais

    - **Telefone comercial:** 888 555-8855

    - **Email:** jean@sample.com

    - **Empresa:** Consolidated Sample – Suas iniciais

    - **Rua 1:** 219 91<sup data-htmlnode="">st</sup> Ave N

    - **Cidade:** Seattle

    - **Estado:** WA

    - **CEP:** 98001 

11. Selecione o botão **Salvar** na barra de comandos para salvar o novo cliente potencial e deixá-lo em aberto.

12. Observe o Fluxo do Processo Comercial do **Lead da Oportunidade** na parte superior do registro. Selecione o **Estágio Qualificar**. Conclua o estágio da seguinte maneira:

    - **Cronograma de Compras:** este trimestre

    - **Orçamento estimado:** 25.000  

    - **Processo de compra:** comissão

    - **Identificar o Tomador de Decisões:** Concluído

13. Selecione o **X** na janela do estágio para fechá-la. 

14. Acesse a **Linha do tempo** de registro no meio da tela e selecione o **Ícone do Sinal de Mais** para incluir uma nova atividade. 

15. No menu exibido, selecione **Telefonema**.

16. Na tela Criação Rápida da Ligação Telefônica, complete a ligação telefônica da seguinte maneira:

    - **Assunto:** chamada de qualificação inicial – Suas iniciais  

    - **Número de telefone:** 888 555-8855

    - **Direção:** saída

    - **Descrição:** Conversa inicial com Jean para determinar a qualificação inicial. 

17. Selecione o botão **Salvar e Fechar (Save and Close)** .

18. Observe que a atividade **Chamada de Qualificação Inicial** agora é exibida no **Cronograma de Registro**. Posicione o mouse sobre a atividade e selecione a atividade de fechamento **Ícone de Marcação** para marcar a ligação telefônica como concluída. 

19. Na janela **Fechar Chamada Telefônica**, verifique se o status definido é **Concluído** e selecione o botão **Fechar**.

 

### <a name="task-2-qualify-the-lead-and-convert-to-opportunity-for-further-qualification"></a>Tarefa 2: qualificar o Cliente Potencial e converter em Oportunidade para melhor qualificação

1. Na **Barra de Comandos**, selecione o botão **Qualificar**. 

2. Depois que o sistema qualificar o cliente potencial, um novo registro de Oportunidade será criado e o processo comercial passará para o estágio **Desenvolver**. Selecione o estágio **Qualificar** para exibir o registro de lead original. 

3. Selecione o estágio **Desenvolver** para retornar à oportunidade.

4. Selecione o botão **Salvar e Fechar** para fechar o registro de Oportunidade que foi criado. 

