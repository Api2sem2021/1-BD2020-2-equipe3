# Easy Way

O **Link** para acesso ao Vídeo de Informações sobre o Projeto Integrador:

_https://youtu.be/UjivxozPW4o_


____________________________________________________________________________


**Integrantes**

**Scrum Master:**


Ana Amorim

Pedro Minicz

**Time:**

Adriano Ribeiro Martins

Fernando Daniel S.A.de Araujo

Isaque Costa Beirao

Junio Luiz Sendreto dos Santos

Paulo Vitor Lima Domingues

Pedro Lucas dos Santos Rodrigues

__________________________________________________________________________________________________________________________________________________

**Sumário**

1.	Estória do Usuário  3

2.	Requisitos Funcionais	3

2.1 Motorista	3

2.2 Passageiro	3

2.3 Aplicação	3

3.	Requisitos não funcionais	3

4.	Sprints	4

__________________________________________________________________________________________________________________________________________________
1.  **Estória do Usuário**

O motorista está tendo problemas com as rotas e tempo, em casos de usuários que não avisam que irão utilizar a van, perdendo tempo e gerando gastos, ou em casos que os usuários avisam existe perda de tempo com mapeamento de novas rotas. Assim o motorista deseja um aplicativo que solucione esses problemas.

2.  **Requisitos Funcionais**

2.1 Motorista

Gerenciamento de Destino:
•	O motorista pode adicionar um destino;
•	O motorista pode alterar o destino; e
•	O motorista pode excluir um destino.
Gerenciamento de Passageiro:
•	O motorista pode excluir o passageiro;
•	O motorista pode adicionar destinos ao passageiro;
•	O motorista pode alterar o destino do passageiro; e
•	O motorista pode alterar o horário de chegada para cada passageiro.

2.2 Passageiro

•	O passageiro pode criar apenas um usuário;
•	O passageiro pode alterar alguns dados cadastrais; e
•	O passageiro deve enviar sua presença na ida e volta todos os dias; e
•	O passageiro pode mudar de ideia e enviar alteração sobre a utilização da van.

2.3 Aplicação

Rota:

•	O aplicativo deve sugerir as rotas a partir do ponto de saída;
•	O aplicativo deve organizar a ordem de busca de passageiros; e
•	O motorista pode alterar o horário de chegada para cada passageiro.

Hora Prevista:

•	O aplicativo deve informar para o passageiro a hora prevista de chegada na ida; e
•	O aplicativo deve informar para o passageiro a hora prevista de chegada na volta.

3.	**Requisitos não funcionais**

•	O Aplicativo deve ser feito com APP INVENTOR.


4.	**Sprints**

Sprint 0 - 27/09
•	Protótipo de login e Cadastro

Sprint 1 - 17/10
•	Gerenciamento de Usuário

Sprint 2 - 08/11
•	Gerenciamento de Destino 
•	Gerenciamento de Rota 

Sprint 3 - 29/11
•	Gerenciamento de Hora Prevista


•   Tela de cadastro:
A tela de cadastro é onde o usuario insere seus dados pessoais que é armazenado no firebase para um resgate futuro.
![cadastro](https://gitlab.com/adrianormFatec/easyway2/-/blob/master/WhatsApp_Image_2020-10-18_at_17.02.01.jpeg)

•   Tela de login:
Nesta tela o usuario insere dados que foram usados no seu cadastro, ou seja, armazenados no firebase para a verificação da sua conta, 
tanto do tipo passageiro quanto motorista.

•   Tela inicial Motorista:
A tela inicial motorista possui um botão escrito "Listar Passageiros", que quando pressionado exibe uma lista onde há os passageiros já cadastrados.

•   Tela inicial Passageiro:
A tela inicial passageiro possui um botão escrito "Alterar Dados", que quando pressionado o redireciona para uma 
outra tela de cadastro (Tela Cadastro 02).

•   Informacões do passageiro:
Essa tela é acessada a partir da tela inicial, que ao clicar no nome de um passageiro, o usuario é redirecionado para a tela informações Passageiro.
Esta tela contem informações pessoais do passageiro em questão, também a opção de exclui-lo e voltar para a tela inicial.

•   Tela de Cadastro 02:
Essa tela é identica a (Cadastro), porém nela existe informações especificas disponiveis para alteração.