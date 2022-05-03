---
lab:
  title: 'Laboratório 1.2: Gerenciar clientes e atividades'
  module: 'Module 1: Examine the core capabilities of Dynamics 365 (CRM)'
ms.openlocfilehash: 886e0800f6747542fcd83ade072fb312ad922de4
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/29/2022
ms.locfileid: "144404911"
---
<a name="module-1-examine-the-core-capabilities-of-dynamics-365-crm"></a>Módulo 1: Examinar as funcionalidades principais do Dynamics 365 (CRM)
========================

## <a name="practice-lab-12---manage-customers-and-activities"></a>Laboratório prático 1.2 – Gerenciar clientes e atividades

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

15. Na **Linha do Tempo do Registro** localizada no meio da tela, clique no **ícone do sinal de mais** para adicionar um item novo. 

16. No menu exibido, selecione **Compromisso (Appointment)** .

17. Preencha o Compromisso assim:

    - **Assunto:** Reunião com Jackson

    - **Start Time:** Amanhã às 10h 

    - **Hora de término:** Amanhã às 11h 

18. Selecione o botão **Salvar e Fechar (Save and Close)** . 

19. No seu teclado, pressione a tecla **F5** para atualizar a tela.     

20. Na linha do tempo do registro, selecione o **Compromisso** para exibir os detalhes sobre ele.   

21. Clique no link **Abrir Compromisso (Open Appointment)** . 

22. Com o registro do compromisso aberto, na **Barra de Comandos (Command Bar)** , selecione o botão **Marcar como Concluído (Mark Complete)** para finalizar o compromisso. 

23. Clique no botão **Salvar e Fechar (Save and Close)** para voltar ao registro da conta.   

24. Selecione **Salvar e Fechar (Save and Close)** no registro da conta para sair.   
