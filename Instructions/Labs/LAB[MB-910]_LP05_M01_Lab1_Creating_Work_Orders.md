---
lab:
  title: 'Roteiro de aprendizagem 5 – Laboratório 5.1: Criar ordens de serviço no Dynamics 365 Field Service'
  learning path: Learn the Fundamentals of Dynamics 365 Field Service
  module: Explore Dynamics 365 Field Service
---

Módulo 1: Explorar o Dynamics 365 Field Service
========================

# Laboratório prático 5.1 – Como criar ordens de serviço no Dynamics 365 Field Service

## Configuração do Laboratório

**Observação para instrutores:** *para que este laboratório funcione conforme planejado para os alunos, há algumas etapas de configuração que precisam ser concluídas. É possível encontrar as etapas de configuração no guia de preparação do instrutor MB-910T00A. É possível encontrar os dados de demonstração do Field Service aqui: [https://github.com/MicrosoftLearning/MB-910T00A-Microsoft-Dynamics-365-Fundamentals-Customer-Engagement-Apps/tree/master/Instructions/Labs ]*

  - **Tempo estimado**: 20 minutos

## Instruções

1. Se ainda não estiver aberto, abra o aplicativo **Dynamics 365 Field Service**.

2. Usando a navegação no lado esquerdo da tela, selecione **Casos**.

3. Na **Barra de comando**, selecione o botão **Novo** para criar um registro de caso.

4. Preencha o novo registro de caso como se segue:

    - **Título do caso:** superaquecimento da unidade de controle (suas iniciais)

    - **Cliente:** A. Datum Corporation

    - **Origem:** Telefone

5. Selecione a guia **Serviço de Campo**

6. Defina o campo **Tipo de incidente** como **Superaquecimento de unidade**.

7. Na **Barra de comando**, selecione o botão **Salvar e Fechar** para salvar e fechar o registro do caso.

Voltaremos depois ao seu registro de caso criado. A seguir, vamos examinar como criar manualmente um registro de ordem de serviço.

8. Na navegação à esquerda, selecione **Ordens de Serviço**.

9. Na **Barra de Comandos**, selecione o botão **Novo** para criar uma nova ordem de serviço.

10. Preencha os detalhes da ordem de serviço da seguinte forma:

    - **Conta de serviço:** Adventure Works

    - **Lista de preços:** Taxas da fatura dos EUA

    - **Tipo de incidente primário:** Conexão de linha perdida

11. Selecione a guia **Settings** (Configurações).

12. Defina o campo **Território de Serviço** como **WA**.

13. Em **Preferências**, configure as preferências de tempo conforme mostrado a seguir:

    - **Hora de início prometida:** Hoje às 9:00

    - **Hora de Término Prometida:** Hoje às 11:00

14. Selecione **Salvar e fechar** para salvar as alterações e sair da nova ordem de serviço.

Outra forma de gerar ordens de serviço é escalar registros de casos. Neste exemplo, você fará a escalada do caso de superaquecimento da unidade de controle criado anteriormente.

15. Usando a navegação esquerda, selecione **Casos**.

16. Abra o caso de **Superaquecimento da unidade de controle** **(suas inicias)** criado anteriormente.

17. Na **Barra de Comando**, selecione o botão **Converter em Ordem de Serviço**.

18. Após a criação da ordem de serviço, clique no botão **OK** na tela pop-up para exibir os detalhes dela.

19. Selecione a guia **Serviços** e verifique se os serviços **Inspecionar a integridade do sistema** e **Inspecionar a amplitude de movimento** foram adicionados à ordem de serviço.

**OBSERVAÇÃO:** se eles não forem inicialmente exibidos, pressione F5 para atualizar a tela.

20. Selecione a guia **Tarefa de serviço** e verifique se a tarefa **Inspecionar unidade** foi adicionada.

Suas novas ordens de serviço estão prontas para serem agendadas.

