---
lab:
  title: 'Laboratório 2.3: Laboratório de conclusão do Dynamics 365 Sales'
  module: 'Module 2: Learn the Fundamentals of Dynamics 365 Sales'
---

<a name="module-2-learn-the-fundamentals-of-dynamics-365-sales"></a>Módulo 2: conheça os conceitos básicos do Dynamics 365 Sales
========================

## <a name="practice-lab-23---dynamics-365-sales-capstone-lab"></a>Laboratório prático 2.3 - Laboratório Capstone do Dynamics 365 for Sales

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

Você trabalha como representante de vendas residenciais na ABC Company. Embora muitos de seus clientes potenciais provenham de eventos patrocinados pela empresa, campanhas de marketing e listas adquiridas, você ainda recebe consultas diretamente de clientes. Quando recebe essas consultas, você precisa registrar manualmente o cliente potencial e gerenciá-lo pelo ciclo de vida de vendas. 

Recentemente, você atendeu uma pessoa chamada Piper Smith. Tem ocorrido uma série de roubos em seu bairro, e ela gostaria de adquirir alguns equipamentos de segurança residencial. Você fará o registro do cliente potencial em nome de Piper no sistema, tentará qualificá-la e fará seu avanço pelo ciclo de vendas. 

Após a conclusão do laboratório, teremos concluído o seguinte:

- Registrar um cliente potencial no Dynamics 365 for Sales

- Qualificar e converter um cliente potencial em oportunidade de vendas.

- Gerenciar atividades diárias associadas a uma oportunidade. 

- Adicionar uma cotação a uma oportunidade. 

- Fechar uma oportunidade de vendas. 

- Gerar uma fatura. 

## <a name="lab-setup"></a>Configuração do Laboratório

  - **Tempo estimado**: 30 minutos

## <a name="instructions"></a>Instruções
  
## <a name="exercise-1-create-and-qualify-a-lead-in-dynamics-365-sales"></a>Exercício 1: Crie e qualifique um cliente potencial no Dynamics 365 for Sales


### <a name="task-1-create-a-new-lead"></a>Tarefa 1: Crie um novo Cliente Potencial

1. Se necessário, abra um navegador InPrivate e navegue até [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. Quando solicitado, faça login com as credenciais do usuário fornecidas a você pelo instrutor. 

3. Na lista de aplicações exibidas, selecione **Hub de Vendas.**

4. Use a área de navegação à esquerda da tela e selecione **Clientes Potenciais**. 

5. Para exibir todos os clientes potenciais de vendas atuais no sistema, selecione a seta para baixo próxima a **Meus clientes potenciais em aberto**; no menu exibido, selecione **Clientes Potenciais Ativos**. 

6. Para voltar à lista de clientes potenciais, selecione a seta para baixo próxima a Clientes Potenciais Ativos e, no menu exibido, selecione **Meus Clientes Potenciais em Aberto**. 

7. Em seguida, crie um novo cliente potencial em nome de Piper Smith. Na exibição **Meus Clientes Potenciais em Aberto**, selecione o botão **Novo** na barra de comandos.

8. Preencha o novo registro de clientes potenciais da seguinte maneira:

    - **Tópico:** Procurando equipamentos de segurança - "Seu Nome"

    - **Nome:** Piper

    - **Sobrenome:** Smith - "Suas iniciais"

    - **Telefone celular:** 888 555-1762

    - **Email:** piper@sample.com


9. Selecione o botão **Salvar** na barra de comandos para salvar o novo cliente potencial e deixá-lo em aberto.

10. Observe o Fluxo do Processo Comercial do **Lead da Oportunidade** na parte superior do registro. Selecione o **Estágio Qualificar**. Conclua o estágio da seguinte maneira:

    - **Cronograma de Compras:** este trimestre

    - **Orçamento estimado:** 10000 

    - **Processo de compra:** Individual

    - **Identificar o Tomador de Decisões:** Concluído

11. Selecione o **X** na janela do estágio para fechá-la. 

12. Acesse a **Linha do tempo** de registro no meio da tela e selecione o **Ícone do Sinal de Mais** para incluir uma nova atividade. 

13. No menu exibido, selecione **Telefonema**.

14. Na tela Criação Rápida da Ligação Telefônica, complete a ligação telefônica da seguinte maneira:

    - **Assunto:** Procurando equipamentos de segurança residencial

    - **Número de telefone:** 888 555-1762

    - **Direção:** Recebida

    - **Descrição:** Após alguns incidentes em seu bairro, ela resolveu adquirir um sistema de segurança. 

15. Selecione o botão **Salvar e Fechar (Save and Close)** .

16. Observe que a atividade **Procurando equipamentos de segurança residencial** agora está exibida na **Linha do Tempo** de registro. Posicione o mouse sobre a atividade e selecione a atividade de fechamento **Ícone de Marcação** para marcar a ligação telefônica como concluída. 

17. Na janela **Fechar Chamada Telefônica**, verifique se o status definido é **Concluído** e selecione o botão **Fechar**.

 

**IMPORTANTE:** Não feche o registro de cliente potencial. Deixe-o aberto para ser usado na próxima tarefa. 

 

### <a name="task-2-qualify-the-lead-as-an-opportunity"></a>Tarefa 2: Qualifique o cliente potencial como oportunidade

Após visitar Piper, você identificou que há interesse suficiente da parte dela para justificar o avanço no processo e que temos produtos e serviços que a beneficiariam. Em seguida, você qualifica o registro de cliente potencial. Isso cria um registro de Oportunidade relacionado e avança para o próximo estágio do processo de vendas Cliente Potencial para Oportunidade. 

1. Na **Barra de Comandos**, selecione o botão **Qualificar**. 

2. Depois que o sistema qualificar o cliente potencial, um novo registro de Oportunidade será criado e o processo comercial passará para o estágio **Desenvolver**. Selecione o estágio **Qualificar** para exibir o registro de lead original. 

3. Selecione o estágio **Qualificar** para voltar à oportunidade.

4. Selecione o botão **Salvar e Fechar** para fechar o registro de Cliente Potencial que foi criado. 

 

 

## <a name="exercise-2-manage-a-sales-opportunity-in-dynamics-365-sales"></a>Exercício 2: Gerencie uma oportunidade de vendas no Dynamics 365 for Sales

Agora que qualificamos com êxito o cliente potencial como uma oportunidade, é hora de gerenciar a oportunidade pelo ciclo de vida.

### <a name="task-1-manage-a-sales-opportunity--create-a-quote"></a>Tarefa 1: Gerencie uma oportunidade de vendas e crie uma cotação 

1. Usando a navegação no lado esquerdo da tela, selecione **Oportunidades**. 

2. Selecione a seta de lista suspensa ao lado da exibição **Minhas Oportunidades em Aberto**. No menu exibido, selecione **Todas as Oportunidades**.

3. Na Barra de Comandos, selecione Mostrar Gráfico. Observe que o gráfico **Principais Clientes** é exibido com base na tabela Oportunidade. 

4. Selecione a seta de lista suspensa ao lado de **Principais Clientes**. No menu exibido, selecione **Pipeline de Vendas**.

5. Selecione a parte Qualificar do Funil. Observe que a lista de Oportunidades muda para exibir aquelas que estão no estágio de qualificação. 

6. Selecione qualquer lugar do espaço em branco do gráfico para exibir todas as oportunidades em aberto de novo. 

7. Selecione a seta de lista suspensa ao lado da exibição **Oportunidades em Aberto**. No menu exibido, selecione **Minhas Oportunidades em Aberto**. O item **Procurando Equipamentos de Segurança - Suas Iniciais** provavelmente será a única ocorrência, e o gráfico deve refletir isso. 

8. Na **Barra de Comandos**, selecione o botão **Ocultar Gráfico**. 

9. Abra o item **Procurando Equipamentos de Segurança - Suas Iniciais** que você criou anteriormente ao qualificar o cliente potencial. Observe que o registro já está na fase **Desenvolver**, já que foi criado a partir de um Cliente Potencial qualificado anteriormente.  

10. No cabeçalho da oportunidade **Procurando Equipamentos de Segurança - Suas Iniciais** na parte superior do registro, selecione a seta para baixo ao lado do campo de proprietário. 

11. Preencha o seguinte:

    - **Data de fechamento estimada:** amanhã

    - **Receita estimada:** 12.500,00

12. Acesse a **Linha do tempo** de registro no meio da tela e selecione o **Ícone do Sinal de Mais** para incluir uma nova atividade. 

13. No menu exibido, selecione **Compromisso**.

14. No formulário **Criação Rápida: Compromisso**, preencha da seguinte maneira:

    - **Assunto:** Reunião Rápida - “Suas Iniciais”

    - **Localização:** Online

    - **Hora de início**: Amanhã, às 10h

    - **Hora de término:** Amanhã, às 10h30

15. Na barra de comandos, selecione **Salvar e Fechar**

16. No fluxo de processo comercial de Cliente Potencial para Oportunidade, selecione o estágio **Desenvolver**. Observe que é necessário Identificar Interessados e Concorrentes.

17. Selecione o **X** na janela de estágios para fechá-la e continuar trabalhando. 

18. Na subgrade **Partes Interessadas**, observe que **Piper** já está definida como parte interessada. 

19. Na subgrade Equipe de Vendas, selecione a **Elipse Vertical**. No menu exibido, selecione **Nova Conexão**. 

20. No campo **Pesquisar**, insira o texto **Sistema** e selecione o registro **Administrador do Sistema**. Depois de concluído, selecione o botão **Adicionar**. O Administrador do Sistema deve aparecer na equipe de vendas. Caso contrário, selecione o botão **Atualizar** na barra de comandos. 

21. Na subgrade Concorrentes, selecione as **Reticências Verticais**. No menu exibido, selecione **Adicionar Concorrente Existente**. 

22. Na tela **Registro de Busca**, selecione **Novo** e depois **Concorrentes**.

23. Na tela Criação Rápida: tela **Concorrente**, defina o campo **Nome** como **Segurança Coho – “Suas Iniciais”** .

24. Selecione o botão **Salvar e Fechar (Save and Close)** .

25. Confirme se o registro Coho Security recém-criado está selecionado e selecione o botão **Adicionar**. 

26. Selecione o estágio **Desenvolver** no fluxo de processo corporativo **Cliente Potencial para Oportunidade** e defina as etapas **Identificar Interessados** e **Identificar Concorrentes** como **Concluído**. 

27. Selecione o botão **Próximo Estágio** para passar para o estágio **Propor**.

28. No estágio **Propor**, marque a opção **Identificar Equipe de Vendas** como **Concluído**.

29. Selecione o **X** na janela do estágio Propor para fechá-la. 

30. No registro de oportunidade, selecione a guia **Cotações**. 

31. Na subgrade Cotações, selecione **Nova Cotação**.

 

**IMPORTANTE:** Como esses ambientes têm vários apps próprios instalados, é possível que o formulário de cotação exibido no momento não seja o correto para a função de vendas. Se o texto abaixo do nome da cotação **Procurando Equipamentos de Segurança - Suas Iniciais** for: **Cotação . Cotação**, o formulário correto será carregado. Se for, **Cotação . Informações de Serviço de Campo**, será necessário trocá-lo. Se isso for necessário, selecione a seta de lista suspensa ao lado de **Cotação . Informações de Serviço de Campo**. No menu exibido, selecione **Cotação**. 

 

### <a name="task-2-manage-a-quote"></a>Tarefa 2: Gerencie uma cotação

Agora que já tem uma cotação relacionada, você a prepara para apresentar a um cliente. Em situações normais, provavelmente incluiríamos produtos no registro de cotação antes de enviar a um cliente. Como estamos trabalhando em ambientes compartilhados, vamos pular a inclusão de linhas na cotação e passaremos para seu envio. 


1. É necessário selecionar uma Lista de Preços para anexar à Oportunidade.  Em **Lista de Preços**, no painel esquerdo, selecione o ícone Procurar e depois **Office 365 USA (sample)** na lista de resultados. Na **Barra de Comandos**, selecione o botão **Ativar Cotação** para ativá-la. 

2. Agora que criamos a cotação, vamos atualizar o registro de oportunidade para refletir os novos dados. No registro de Cotação, selecione **Procurando Equipamentos de Segurança** – **“Seu Nome”** no campo **Oportunidade** na seção **Informações de Vendas**. O registro de oportunidade deve abrir na tela. 

3. No registro de oportunidade, selecione o estágio **Propor**. 

4. Marque **Desenvolver Proposta**, **Concluir Revisão Interna** e **Apresentar Proposta** como **Concluído** e selecione o botão **Próximo Estágio** para avançar ao estágio **Fechar**. 

5. No estágio **Fechar**, marque **Concluir Proposta Final**, **Apresentar Proposta Final**, **Enviar Agradecimento** e **Arquivar Avaliação** como **Concluído**. 

6. Defina **Confirmar Data de Decisão** para **Data de hoje**. 

7. Selecione o botão **Concluir**. 

8. Selecione o **X** na janela do estágio Fechar para fechá-la. 

9. Selecione a guia **Cotações**. 

10. Abra a cotação **Procurando Equipamentos de Segurança - Suas Iniciais**. 

11. Na **Barra de Comandos**, selecione o botão **Criar Pedido**.

12. Na janela Criar Pedido, preencha da seguinte maneira:

    - **Motivo do Status:** Ganho

    - **Data de Ganho:** Data de hoje

    - **Fechar Oportunidade:** Sim

    - **Calcular Receita Real das Cotações:** Não

    - **Receita Atual:** $12.500

13. Selecione o botão **OK** 

O sistema cria um novo pedido de vendas relacionado ao item. E fecha o registro de cotação e o registro de oportunidade relacionado. Depois de tudo concluído, o pedido será aberto na tela. Deixe o pedido aberto. 

###  

### <a name="task-3-manage-the-order-and-invoice"></a>Tarefa 3: Gerencie o pedido e a fatura

Agora que criamos um pedido de vendas, vamos fechar o pedido e gerar a fatura. Em situações normais, incluiríamos produtos do registro de cotação no pedido de vendas. Como estamos trabalhando em ambientes compartilhados, vamos continuar como se já houvesse produtos anexos. 

 

1. Na **Barra de Comandos**, selecione o botão **Preencher Pedido**. 

2. Na tela Preencher Pedido, preencha da seguinte maneira:

    - **Motivo do Status:** Concluir

    - **Data de Preenchimento:** Data de hoje

3. Selecione o botão **Preencher**. 

4. Na **Barra de Comandos** do pedido, selecione o botão **Criar Fatura**. 

5. Na **Barra de Comandos**, selecione o botão **Fatura Paga**. Selecione OK.
