---
lab:
  title: 'Roteiro de aprendizagem 2 – Laboratório 2.1: Criar uma jornada do cliente simples'
  learning path: Explore the fundamentals of Dynamics 365 Marketing
  module: Explore Dynamics 365 Marketing
---

Roteiro de aprendizagem 2 – Módulo 1: Explorar o Dynamics 365 Marketing
========================

## Roteiro de aprendizagem 2.1 – Criar uma jornada do cliente simples

## Objetivos

Durante este exercício, você verá que as Jornadas do cliente são um componente essencial no Dynamics 365 Marketing. Você criará as jornadas do cliente como base para qualquer esforço de marketing a fim de guiar o caminho que um cliente segue enquanto interage com o processo de marketing da organização. O objetivo de uma jornada, quando for concluída, é transformá-la em receita.

## Configuração do Laboratório

  - **Tempo estimado**: 20 minutos

## Instruções

1. Abra o **Aplicativo do Dynamics 365 Marketing**.

2. Alterne a área para **Marketing de saída**. 

3. Na navegação esquerda, selecione **Contatos** no grupo **Clientes**

4. Na barra de comandos, selecione **Novo**.

5. Preencha a página **Novo Contato (New Contact)** assim:

    - **Nome**: Jenny

    - **Sobrenome**: Jones (suas iniciais)

    - **Email**: Insira um endereço de email ativo.

    - **Endereço 1 Rua 1:** 101 Sample Ave

    - **Endereço 1 Cidade**: Fargo

    - **Endereço 1 Estado:** ND

    - **Endereço 1 CEP (código postal):** 58103

6. Depois de preencher o contato, selecione **Salvar e Fechar**.

7. Na barra de comandos, selecione novamente “Novo” para criar outro contato.

8. Preencha o segundo contato assim:

    - **Nome**: Marco

    - **Sobrenome**: Gomez (suas iniciais)

    - **Email**: Insira um endereço de email ativo.

    - **Endereço 1 Rua 1:** 101 Sample Ave

    - **Endereço 1 Cidade**: Fargo

    - **Endereço 1 Estado:** ND

    - **Endereço 1 CEP (código postal):** 58103

**Observação:** Estamos usando as mesmas informações de endereço para facilitar o reconhecimento dos contatos como dados de amostra. 

9. Depois de preencher o contato, selecione **Salvar e Fechar**.

**IMPORTANTE:** devido ao endereço, pode ocorrer o disparo das configurações de detecção de duplicatas do sistema. Se a tela de registro duplicado for exibida, pressione o botão **Ignorar e salvar**. 

**Tarefa 2: Criar segmento de Fargo** 

Em seguida, você criará um segmento e adicionará os contatos criados na tarefa anterior. 

1. Na navegação esquerda, selecione **Segmentos** em **Marketing**. 

    2. Na barra de comandos, selecione **Novo**.

    3. No menu suspenso exibido, selecione **Novo Segmento Dinâmico (New Dynamic Segment)** .

    4. Na caixa de diálogo **Modelos de Segmento (Segment Templates)** aberta, selecione **Ignorar (Skip)** para fechá-la e seguir para a tela **Novo Segmento (New Segment)** .

    5. Selecione **Adicionar bloco de consulta** para criar uma consulta na entidade de contato. 

    6. Clique no texto duplicado **Selecionar atributo**. 

    7. Em seguida, digite "cidade" para filtrar a lista e escolha **Endereço 1: Cidade**.

    8. Deixe a lista suspensa definida como **Is**. 

    9. Selecione a terceira lista suspensa, que contém o texto duplicado **Digitar para pesquisar** e digite **Fargo**.

    10. Clique para selecionar o campo **Nome** na parte superior da consulta e insira **Contatos de Fargo (suas iniciais)** . (Talvez seja necessário selecionar a seta para baixo ao lado de “Motivo do status”).

    11. Selecione **Salvar (Save)** na barra de comandos para salvar o segmento.

    12. Selecione **Ativar (Go Live)** para publicar o segmento.

    13. Aguarde cerca de um minuto e selecione **Atualizar (Refresh)** na barra de comandos para atualizar a página. 

    14. Você verá que a guia **Membros (Members)** foi adicionada. 

 

**Tarefa 3: Criar um email simples.** 

Em seguida, você criará um email simples com base em um modelo existente que poderá ser usado na jornada do cliente. 

1. Na navegação esquerda, selecione **Emails de marketing** no grupo **Execução de marketing**.

2. Usando a barra de comandos, selecione **+ Novo**.

3. Na tela **Modelos de email de marketing**, selecione **Coluna 1** e clique no botão **Selecionar**. 

4. No canto superior esquerdo do email, selecione o campo “Nome”. (Terá um texto semelhante ao Email ypl da coluna 1)

5. Altere o nome para “**Exemplo de mensagem de email (suas iniciais)** ”.

6. No campo **Assunto**, insira o texto "**Veja o que temos a oferecer**”. 

7. Selecione o botão **Salvar**. 

8. Pressione o botão **Publicar** para publicar o email. 

 

**Tarefa 4: Criar uma jornada do cliente.** 

Agora que você tem o público-alvo e a atividade de email a ser usada, criará uma jornada do cliente. 

1. Na navegação esquerda, selecione **Jornadas do cliente** no grupo **Execução de marketing**.

    2. Usando a barra de comandos, selecione **+ Novo**.

    3. No pop-up **Modelos de jornada do cliente**, selecione **Ignorar** para começar a criar uma jornada.

    4. Selecione **Definir público-alvo** (ou, como opção, selecione **+** ). Verifique se **Tipo de origem** está definido como **Segmento** e selecione o segmento **Contatos de Fargo** (suas iniciais) criado no exercício anterior. O primeiro bloco é preenchido com o nome do segmento, e o painel **Público-alvo (Audience)** exibe as propriedades do segmento.

    5. Selecione **+** na tela e clique em **Enviar um email** no menu contextual.

    6. Na seção “Enviar um email”, selecione a **Mensagem de email de amostra** (suas iniciais) criada anteriormente.

    7. Selecione a guia Geral (General) localizada acima do registro da jornada do cliente. Insira as seguintes informações na guia **Geral (General)** :

        - **Nome**: Jornada do cliente de Fargo (suas iniciais)

        - **Data e hora inicial (Start date and time)** : Insira a data de hoje

        - **Data e hora de término**: Um mês a partir de hoje

        - **Fuso horário**: Selecione o fuso horário local.

8. Na barra de comandos, selecione **Salvar (Save)** para salvar o trabalho realizado até agora.

9. Sua jornada está pronta. Para começar a jornada, você deve publicá-la selecionando **Ativar (Go live)** na barra de comandos.

 
