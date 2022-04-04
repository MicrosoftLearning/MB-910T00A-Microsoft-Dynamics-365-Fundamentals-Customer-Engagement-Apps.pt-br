---
lab:
  title: 'Laboratório 3.3: Laboratório Capstone do Dynamics 365 for Customer Service'
  module: 'Module 3: Learn the Fundamentals of Dynamics 365 Customer Service'
---

<a name="module-3-learn-the-fundamentals-of-dynamics-365-customer-service"></a>Módulo 3: conheça os conceitos básicos do Dynamics 365 Customer Service
========================

## <a name="practice-lab-33---dynamics-365-customer-service-capstone-lab"></a>Laboratório de prática 3.3 - Laboratório Capstone do Dynamics 365 for Customer Service

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

Muitas vezes, os clientes podem encontrar problemas com seus equipamentos. Quando forem encontrados problemas, eles são informados ao help desk da empresa ABC. Os problemas podem ser informados de várias maneiras. Em alguns casos, o equipamento pode informar problemas de modo proativo. À medida que os problemas são informados, os agentes tentam resolvê-los remotamente. Se isso não funcionar, um técnico de campo será enviado para resolver o problema. Você tem corrigido muitos sensores que pararam de funcionar recentemente. Você percebeu que isso se deve a um bug de software. Você deseja criar um artigo de conhecimento que outros agentes possam usar como referência quando encontrarem o mesmo problema. 

Como agente de help desk, você é responsável por trabalhar em problemas informados por clientes. Você recentemente atendeu um telefonema de Piper Smith. Piper está informando que um dos sensores em seu sistema não está funcionando. Você precisa registrar a chamada e tentar localizar uma resolução para o problema. 

Após a conclusão do laboratório, teremos concluído o seguinte:

- Criado um artigo de conhecimento 

- Gerenciado casos usando o hub de atendimento ao cliente.

- Criado e registrado um caso. 

- Gerenciar um registro de caso ao longo do ciclo de vida. 

## <a name="lab-setup"></a>Configuração do Laboratório

  - **Tempo estimado**: 45 minutos

## <a name="instructions"></a>Instruções

## <a name="exercise-1-create-and-publish-a-knowledge-article"></a>Exercício 1: Criar e publicar um artigo de conhecimento

### <a name="task-1-create-a-knowledge-article"></a>Tarefa 1: Criar um artigo de conhecimento

1. Se ainda não estiver aberto, abra o aplicativo **Dynamics 365 for Customer Service Hub**. 

2. Usando a navegação no lado esquerdo da tela, selecione **Artigos de conhecimento**. 

3. Para ver facilmente quais artigos estão em diferentes estágios, selecione a seta suspensa ao lado de **Meus artigos ativos**. 

4. Selecione **Artigos de rascunho**. 

5. Use o seletor de exibição para selecionar **Artigos aprovados**.  

6. Use o seletor de exibição para alternar de volta para **Meus artigos ativos**

7. Na **Barra de comandos**, selecione o botão **Novo**. Depois que o novo registro abrir, selecione a seta suspensa ao lado do campo **Razão do status (Status reason)** no cabeçalho do registro, na parte superior. Defina o **Idioma (Language)** para **English - United States**.

8. Conclua o artigo como se segue:

    - **Título:** O sensor não está funcionando - Suas iniciais

    - **Palavras-chave:** Sensor, danificado, não funcionando

    - **Descrição:** Ajuda a trabalhar em cenários onde um sensor não está funcionando. 

9. Insira o seguinte texto na caixa **Designer de Conteúdo**.   

    O sensor não está funcionando atualmente

    Quando o sensor não está funcionando como deveria, faça o seguinte:

    1. Localize e substitua as baterias no dispositivo. 

    2. Pressione e mantenha pressionado o botão liga/desliga por 3 segundos. 

    3. O dispositivo abrirá em modo de administrador. 

    4. Pressione e mantenha pressionado o botão do par até que a luz mude de vermelha para azul. 

    5. Pressione o botão de redefinição. 

    Assim que o dispositivo reiniciar, ele estará on-line novamente. 

10. No editor de contexto, selecione o texto “O sensor não está funcionando atualmente”

11. Altere o tamanho da fonte para **22** e selecione o botão **Negrito**. 

12. Na **Barra de comando**, selecione o botão **Salvar** para salvar o artigo de conhecimento e deixá-lo aberto. 

13. No **Novo processo**, selecione o estágio do **Autor**, defina o campo **Assunto do artigo** para **Serviço**. 

14. Defina o campo **Marcar para revisão** como **Concluído**.

15. Selecione o botão **Próximo estágio** para avançar ao estágio de **Revisão**.

16. Na **Barra de comando**, selecione o botão **Salvar e fechar** para salvar suas alterações e fechar o artigo.

 

### <a name="task-2-manage-an-article-through-the-approval-process"></a>Tarefa 2: Gerenciar um artigo ao longo do processo de aprovação

Na maioria das organizações, depois que o autor do artigo cria o registro, ele passa por um processo de aprovação antes que fique disponível. Na maior parte do tempo isso é feito por um indivíduo diferente. Neste exemplo, agiremos como um aprovador. 

1. Nos Artigos de conhecimento, alterne a exibição para **Artigos propostos** para ver quais artigos precisam de aprovação. 

2. Abra o artigo **Sensor não está funcionando - suas iniciais** que acabou de criar.

3. Em **Novo processo**, selecione o estágio de **Revisão**. Defina o campo **Revisão** como **Rejeitado**.

4. Na tela de Artigo de conhecimento rejeitado, insira o texto **Essas etapas não funcionam quando tento replicá-las.**

5. Selecione o botão **Rejeitar**

6. Selecione **Salvar e Fechar** para fechar o registro do artigo.

7. Usando o **seletor de exibição**, altere a visualização para **Meus artigos ativos**. 

8. Abra o registro **Sensor não está funcionando - suas iniciais**.

9. Assim que o registro for aberto, selecione a guia **Resumo**. 

10. Na **Linha do tempo** do registro, observe uma nota que indicou que o artigo foi rejeitado e o motivo da rejeição. 

11. Selecione a guia **Conteúdo**

12. No campo **Conteúdo**, posicione o cursor antes da palavra **Pressionar** na etapa 5. 

13. Pressione a tecla **Enter**. 

14. Insira o texto “Pressionar botão de confirmar.” 

15. Na **Barra de Comando**, selecione o botão **Salvar e Fechar**.

16. Use o **Seletor de exibição** e alterne a exibição para **Artigos propostos**.

17. Abra o artigo **Sensor não está funcionando - suas iniciais**. 

18. No fluxo de processo empresarial **Novo processo**, selecione o estágio de **Revisão**.

19. Alterne o Status para **Aprovado**. 

20. Você será solicitado a confirmar a aprovação do artigo; selecione **OK**. 


### <a name="task-3-approve-the-knowledge-article"></a>Tarefa 3: Aprovar o artigo de conhecimento

Agora que o artigo foi aprovado, vamos publicá-lo para que ele fique disponível para pessoas trabalhando em casos. 

1. Selecione o botão **Próximo Estágio** para passar para o estágio **Publicar**. 

2. Marque **Definir associações de produto** como **Concluído**. 

3. Defina a **Data de validade** para **um ano a partir de hoje às 0:00**. 

4. Selecione o botão **Concluir** para completar o processo. 

5. Na **Barra de comando** para o artigo, selecione o botão **Publicar**. 

6. Confirme os itens a seguir:

    - **Publicar:** Agora

    - **Status de publicação:** Publicado

    - **Data de validade:** Um ano a partir de hoje às 0:00

    - **Estado da validade:** Expirado

    - **Status da validade:** Expirado

7. Selecione o botão **Publicar** para publicar o artigo.


## <a name="exercise-2-manage-a-support-case-through-its-lifecycle"></a>Exercício 2: Gerenciar um caso de suporte ao longo do ciclo de vida


### <a name="task-1-create-and-manage-a-case"></a>Tarefa 1: Criar e gerenciar um caso

1. Se ainda não estiver aberto, abra o aplicativo **Dynamics 365 for Customer Service Hub**. 

2. Usando a navegação no lado esquerdo da tela, selecione **Painéis de controle**. Isso abrirá o painel de **Nível 1**. 

3. Na **Barra de comando**, selecione o botão **Exibir filtros de visual**.


4. Painéis de controle adicionais oferecem mais detalhes sobre a carga de casos atual. Você pode trabalhar com outros painéis de controle usando o seletor de painéis. Troque o painel de **Painel de nível 1** para **Painel de nível 2**. 

 

Agora que você está familiarizado com algumas das diferentes visualizações e painéis, vamos criar um registro de caso para auxiliar Piper com o problema dela.

 

10. Usando a navegação no lado esquerdo da tela, selecione **Casos**. 

11. Na **Barra de comando**, selecione o botão **Novo** para criar um registro de caso.

12. Preencha o novo registro de caso como se segue:

    - **Título da Ocorrência:** O sensor não está funcionando - Suas iniciais

    - **Cliente:** Piper Smith

    - **Origin:** Telefone

    - **Descrição:** Piper está informando que um dos sensores que ela recebeu não está funcionando adequadamente. 

13. Selecione o botão **Salvar** para salvar o registro e deixe-o aberto. 

14. Usando a **Linha do tempo do registro**, selecione o **Ícone de sinal de mais** para criar uma atividade. 

15. No menu exibido, selecione **Telefonema**.

16. No formulário **Criação Rápida: Chamada telefônica**, complete a atividade como se segue:

    - **Assunto:** Retornar chamada para Piper

    - **Direção:** saída

    - **Número de telefone:**  888 555-1762

    - **Duração:** 15 minutos.

17. Selecione o botão **Salvar e Fechar (Save and Close)** . 

18. Em **Telefone para Processo do caso**, selecione o estágio **Identificar**.

19. Selecione o botão **Próximo Estágio** para passar para o estágio **Pesquisar**. 

20. Selecione o **X** na janela flutuante do estágio **Pesquisar** para fechar a janela e poder continuar trabalhando. 

21. Usando a **Linha do tempo do registro**, selecione o **Ícone de sinal de mais** para criar uma atividade. 

22. No menu exibido, clique em **Tarefa (Task)** .

23. No formulário **Criação Rápida: Chamada telefônica**, complete a atividade como se segue:

    - **Assunto:** Pesquisar o problema da Piper

    - **Descrição:** Aproveitar a base de conhecimentos para pesquisar o problema da Piper. 

    - **Duração:** 30 minutos.

24. Selecione o botão **Salvar e Fechar (Save and Close)** . 

25. No lado direito da tela de caso, localize e selecione o ícone de livro **Conhecimento**. (Ele estará diretamente abaixo do ícone de chave inglesa).

26. Observe que o título do caso está sendo usado automaticamente como texto da pesquisa. Localize e selecione o artigo **Sensor não está funcionando - suas iniciais** que você criou anteriormente. 

27. O conteúdo completo do artigo será exibido; selecione o ícone de **Polegar para cima** na parte inferior do artigo para indicar que o artigo foi útil. 

28. Selecione o ícone **Vincular este artigo ao registro atual**. Verifique se o texto **Vinculado ao caso** aparece. 

 

### <a name="task-2-close-the-case"></a>Tarefa 2: Fechar o caso

Agora que identificamos uma resolução para o problema da cliente, vamos nos preparar para resolver o caso. A primeira etapa para fechar o caso é encerrar quaisquer atividades abertas que foram associadas a ele. 

1. Na **Linha do tempo** do registro, passe o mouse sobre a **tarefa Pesquisar o problema da Piper** que você criou anteriormente **.** Selecione a marca cheia **Ícone de marca de verificação** para concluir a atividade. 

2. Na tela **Fechar tarefa**, verifique se o status está Concluído e selecione o botão **Fechar**. O status da tarefa deve dizer **Fechada**. 

3. Passe o mouse sobre a **Chamada telefônica — Retornar chamada para Piper** que você criou anteriormente **.** Selecione a marca cheia **Ícone de marca de verificação** para concluir a atividade. 

4. Na tela **Fechar chamada telefônica**, verifique se o **Estado** está **Concluído** e se o **Status** está **Feito**. Selecione o botão **Fechar**. Verifique se a atividade aparece como fechada na Linha do tempo. 

5. No **Telefone para processar caso**, selecione o estágio **Pesquisar** e selecione **Próximo estágio** para avançar ao estágio **Resolver**. 

6. No estágio **Resolver**, selecione o botão **Finalizar** para concluir o fluxo do processo. 

7. Na **Barra de comando** para o registro do caso, selecione o botão **Resolver caso**.

8. Na janela **Resolver caso**, defina o campo **Resolução** para **Artigo de conhecimento**. 

9. Verifique se os campos **Tempo total** e **Tempo faturável** estão definidos para **45 minutos** (isso representa o tempo total gasto nas atividades Chamada telefônica e Tarefa adicionadas ao registro.) 

10. Selecione o botão **Resolver** para completar o processo. 

