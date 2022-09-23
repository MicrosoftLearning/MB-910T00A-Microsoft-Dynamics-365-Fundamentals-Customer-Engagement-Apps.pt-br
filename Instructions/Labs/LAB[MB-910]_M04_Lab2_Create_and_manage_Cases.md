---
lab:
  title: 'Laboratório 4.2: Criar e gerenciar ocorrências no Dynamics 365 Customer Service'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Customer Service'
ms.openlocfilehash: 2590c7be81b274a95528c4cd61b32be7db3e3548
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/29/2022
ms.locfileid: "144404940"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-customer-service"></a>Módulo 4: Aprender os princípios básicos do Dynamics 365 Customer Service
========================

## <a name="practice-lab-42---create-and-manage-cases-in-dynamics-365-customer-service"></a>Laboratório prático 4.2 – Criar e gerenciar casos no Dynamics 365 Customer Service

## <a name="lab-setup"></a>Configuração do Laboratório

  - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

1. Se ainda não estiver aberto, abra o aplicativo **Dynamics 365 for Customer Service Hub**. 

2. Usando a navegação no lado esquerdo da tela, selecione **Casos**. 

3. Na **Barra de Comando**, selecione o botão **Novo Caso** para criar um novo registro de caso.

4. Preencha o novo registro de caso como se segue:

    - **Título da ocorrência:** Item chegou danificado - Suas iniciais

    - **Cliente:** Alpine Ski House

    - **Origem:** Telefone

5. Selecione o botão **Salvar** para salvar o registro e deixe-o aberto. 

6. Em **Telefone para Processo do Caso**, selecione a fase **Identificar** e defina o campo **Encontrar Campo de Contato** como **Patrick Sands**. 

7. Selecione o **X** na janela flutuante do estágio **Identificar** para fechar a janela e poder continuar trabalhando. 

8. Usando a **Linha do tempo do registro**, selecione o **Ícone de sinal de mais** para criar uma atividade. 

9. No menu exibido, selecione **Telefonema**.

10. Defina o campo **Assunto** como **Retornar chamada para Patrick - suas iniciais** e deixe o restante dos campos como estão. 

11. Selecione o botão **Salvar e Fechar (Save and Close)** . 

12. Em **Telefone para Processo do caso**, selecione o estágio **Identificar**.

13. Selecione o botão **Próximo Estágio** para passar para o estágio **Pesquisar**. 

14. Selecione o **X** na janela flutuante do estágio **Pesquisar** para fechar a janela e poder continuar trabalhando. 

15. No lado direito da tela de caso, localize e selecione o ícone de livro **Conhecimento**. (Ele estará diretamente abaixo do ícone de **chave inglesa**).

16. Observe que o título do caso que você criou é automaticamente fornecido como texto da pesquisa. Localize e selecione o artigo **Item quebrado na chegada** que você criou anteriormente. 

17. O conteúdo completo do artigo será exibido; selecione o ícone **Vincular este artigo ao registro atual**. Verifique se o texto **Vinculado ao caso** aparece. 

18. Agora, vamos nos preparar para resolver o caso. Na **Linha do tempo do registro**, passe o mouse sobre a atividade de chamada telefônica **Retornar chamada para Patrick** que você criou anteriormente. Selecione a marca cheia **Ícone de marca de verificação** para concluir a atividade. 

19. Na tela **Encerrar chamada telefônica**, selecione o botão **Fechar**. Verifique se a atividade diz **Fechada**. 

20. No **Telefone para processar caso**, selecione o estágio **Pesquisar** e selecione **Próximo estágio** para avançar ao estágio **Resolver**. 

21. No estágio **Resolver**, selecione o botão **Finalizar** para concluir o fluxo do processo. 

22. Na **Barra de comando** para o registro do caso, selecione o botão **Resolver caso**.

23. Na janela **Resolver caso**, defina o campo **Resolução** para **Artigo de conhecimento**. 

24. Selecione o botão **Resolver** para completar o processo. 
