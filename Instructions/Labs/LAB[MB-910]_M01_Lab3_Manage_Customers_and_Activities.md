---
lab:
  title: 'Laboratório 1.3: Gerenciar clientes e atividades'
  module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
---

<a name="module-1-learn-the-fundamentals-of-dynamics-365-marketing"></a>Módulo 1: conheça os conceitos básicos do Dynamics 365 Commerce
========================

## <a name="practice-lab-13---manage-customers-and-activities"></a>Laboratório de prática 1.3 – Gerenciar clientes e atividades

## <a name="objectives"></a>Objetivos

Definir e trabalhar com registros de conta e contato em aplicativos do Dynamics 365 é uma das atividades mais comuns que você fará. Depois de criar contas e contatos, atividades como chamadas telefônicas, tarefas e compromissos representarão as interações que você terá com os clientes.

## <a name="lab-setup"></a>Configuração do Laboratório

  - **Tempo estimado**: 15 minutos

## <a name="instructions"></a>Instruções

Neste exercício, vamos trabalhar com registros comuns usados por todos os aplicativos de envolvimento com o cliente do Dynamics 365. 

1. Se ainda não estiver aberto, abra o aplicativo **Hub de Vendas do Dynamics 365**. 

2. Usando a navegação do lado esquerdo da tela, selecione **Contas (Accounts)** . 

3. Na Barra de Comandos, na parte superior da tela, selecione o botão **Novo (New)** .

4. Preencha o registro da conta da seguinte forma:

    - **Nome da Conta:** Contoso Corporate – Suas iniciais

    - **Telefone:** 888-555-1234

    - **Endereço 1 Rua 1:** 191 181st Ave N

    - **Endereço 1 Cidade:** Seattle

    - **Endereço 1 Estado/Província:** WA

    - **Endereço 1 CEP:** 98101

5. Na barra de comandos, selecione o botão **Salvar e Fechar (Save and Close)** para salvar e sair do registro da conta.

6. Na barra de comandos, para a lista de contas, selecione o botão **Novo (New)** mais uma vez

7. Preencha o registro da conta da seguinte forma:

    - **Nome da Conta:** Contoso North America – Suas iniciais

    - **Telefone:** 888-555-4321

    - **Endereço 1 – Rua 1**: 187 11th ST N

    - **Endereço 1 Cidade:** Chicago

    - **Endereço 1 Estado/Província:** IL

    - **Endereço 1 CEP:** 60176

8. Defina o campo **Conta Primária (Parent Account)** para a conta **Contoso Corporate** que você criou anteriormente. 

9. Selecione o botão **Salvar (Save)** para salvar a conta e deixá-la aberta. 

10. Localize a **Subgrade Contatos (Contacts Sub-grid)** à direita da tela. 

11. Selecione as **Reticências verticais (Vertical Ellipsis)** e selecione **Novo Contato (New Contact)** no menu exibido. 

12. Usando o formulário **Criar Contato Rápido (Quick Create Contact)** , crie o contato da seguinte forma:

    - **Nome:** Jackson

    - **Sobrenome:** Anderson – Suas iniciais

    - **Cargo:** CEO

    - **Email:** Jackson@contososample.com

13. Selecione o botão **Salvar e Fechar (Save and Close)** .

14. Acima da subgrade Contatos, selecione o campo **Contato Principal (Primary contact)** e o defina para o contato **Jackson Anderson** que você criou. 

15. Na **Linha do Tempo do Registro (Record Timeline)** , localizada no meio da tela, selecione o ícone **+** para adicionar uma nova atividade. 

16. No menu exibido, selecione **Compromisso (Appointment)** .

17. Preencha o Compromisso assim:

    - **Assunto:** Reunião com Jackson

    - **Start Time:** Hoje às 15:00

    - **Hora de término:** Hoje às 16:00

18. Selecione o botão **Salvar e Fechar (Save and Close)** . 

19. Espere alguns instantes até a atualização automática da linha do tempo. 

20. Observe que agora a **Linha do Tempo (Timeline)** mostra informações sobre o compromisso. 

21. **Salve e feche** a conta. 

22. Na seção **Meu Trabalho (My Work)** do painel de navegação, selecione **Atividades (Activities)** .

23. Selecione o link **Reunião com Jackson** para abrir a linha de compromissos e exibir o formulário. 

24. Com o registro do compromisso aberto, na **Barra de Comandos (Command Bar)** , selecione o botão **Marcar como Concluído (Mark Complete)** para finalizar o compromisso. 

25. Observe que o compromisso não aparece mais na lista **Minhas Atividades (My Activities)** . 

26. Selecione **Minhas Atividades (My Activities)** para alterar a exibição para **Atividades Encerradas (Closed Activities)** . O compromisso concluído **Reunião com Jackson** será exibido.
