---
lab:
  title: 'Laboratório 5.2: gerenciar uma oportunidade baseada em projeto'
  module: 'Module 5: Learn the Fundamentals of Dynamics 365 Project Operations'
---

<a name="module-5-learn-the-fundamentals-of-dynamics-365-project-operations"></a>Módulo 5: Aprender os princípios básicos do Dynamics 365 Project Operations
========================

## <a name="practice-lab-52---manage-a-project-based-opportunity"></a>Laboratório de Prática 5.2 - Gerenciar uma oportunidade baseada em projeto

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

- Qualificar e converter um cliente potencial em oportunidade de projeto.

## <a name="lab-setup"></a>Configuração do Laboratório

  - **Tempo estimado**: 20 minutos
  
## <a name="exercise-1-manage-a-project-based-opportunity"></a>Exercício 1: gerenciar uma oportunidade baseada em projeto 

Agora que criou com sucesso uma oportunidade de projeto baseada em um cliente potencial project0based, você usará a oportunidade para definir detalhes de alto nível relacionados ao projeto. Isso inclui a definição de produtos e itens de trabalho, bem como a definição de estimativas relacionadas a vendas. 

### <a name="task-1-manage-a-sales-opportunity"></a>Tarefa 1: gerenciar uma oportunidade de venda 

1. Usando a navegação no lado esquerdo da tela, selecione **Oportunidades**. 

2. Na lista de Minhas Oportunidades de Serviço do Projeto em Aberto, abra a oportunidade **Implementação de Segurança Global Completa – Suas Iniciais** criada quando você qualificou o cliente potencial anteriormente. Observe que o registro já está na fase **Desenvolver**, já que foi criado a partir de um Cliente Potencial qualificado anteriormente.  

3. No cabeçalho da oportunidade **Implementação de Segurança Global Completa – Suas Iniciais** na parte superior do registro, selecione a seta para baixo próxima ao campo de proprietário. 

4. Preencha o seguinte:

    - **Data de fechamento estimada:** amanhã

    - **Receita estimada:** 250.000.00

5. No fluxo de processo comercial de Cliente Potencial para Oportunidade, selecione o estágio **Desenvolver**. Observe que é necessário Identificar Interessados e Concorrentes.

6. Selecione o **X** na janela de estágios para fechá-la e continuar trabalhando. 

7. Na subgrade **Interessados**, observe que **Jean** já está definido como interessado. 

8. Na subgrade Equipe de Vendas, selecione **Nova Conexão**. (Se você não vir o botão **Nova Conexão**, selecione **Reticências Verticais** e selecione **Nova Conexão** no menu que é exibido.) 

9. No campo **Pesquisar**, insira o texto **Sistema** e selecione **Administrador do Sistema**. Depois de concluído, selecione o botão **Adicionar**. O Administrador do Sistema deve aparecer na equipe de vendas. Caso contrário, selecione o botão **Atualizar** na barra de comandos. 

10. Na subgrade Concorrentes, selecione as **Reticências Verticais**. No menu exibido, selecione **Adicionar Concorrente Existente**. 

11. Pesquise e selecione **Segurança Coho**. (Se esta opção não existir, selecione **Novo Registro** e, em seguida, selecione **Concorrentes**. Caso contrário, passe para a etapa 15 **.** )  

12. Na tela Criação Rápida: tela **Concorrente**, defina o campo **Nome** como **Segurança Coho – “Suas Iniciais”** .

13. Selecione o botão **Salvar e Fechar (Save and Close)** .

14. Se o registro Segurança Coho que você acabou de criar em um exercício anterior estiver selecionado, selecione o botão **Adicionar**. 

15. Selecione o estágio **Desenvolver** no fluxo de processo corporativo **Cliente Potencial para Oportunidade** e defina as etapas **Identificar Interessados** e **Identificar Concorrentes** como **Concluído**. 

16. Selecione o botão **Próximo Estágio** para passar para o estágio **Propor**.

17. No estágio **Propor**, marque a opção **Identificar Equipe de Vendas** como **Concluído**.

18. Selecione o **X** na janela do estágio Propor para fechá-la. 

19. No registro de oportunidade, selecione a guia **Linhas de Oportunidade**.

20. Na subgrade Linhas Baseadas em Projeto, selecione o botão Adicionar Nova Linha de Oportunidade. Configure o novo item Linha de Oportunidade da seguinte maneira:

    - **Tipo de Produto:** Serviço Baseado em Projeto

    - **Oportunidade:** Implementação de Segurança Global Completa - Suas iniciais

    - **Nome:** Desenvolvimento do Sistema

    - **Orçamento do Cliente:** 25.000

    - **Método de cobrança:** Preço Fixo

21. Selecione **Salvar e Fechar**

22. Na subgrade **Linhas Baseadas em Projeto**, selecione o botão **Adicionar Nova Linha de Oportunidade** novamente para adicionar outro item de linha.   
‎Configure o novo item Linha de Oportunidade da seguinte maneira:

    - **Tipo de Produto:** Serviço Baseado em Projeto

    - **Oportunidade:** Implementação de Segurança Global Completa - Suas Iniciais

    - **Nome:** Implementação do Sistema 

    - **Orçamento do Cliente:** 100000 

    - **Método de cobrança:** Tempo e Material

23. Selecione **Salvar e Fechar**
