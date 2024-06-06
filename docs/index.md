<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+14"><center>
*Sistema de Presença - Escola Infinito*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Aluno 1: Eduardo Honorio Friaça                 (RA: 10408959)
* Aluno 2: Gabriel Fuentes de Freitas Yamashita   (RA: 10408876)
* Aluno 3: Felipe Jiao                            (RA: 10408852)
* Aluno 4: Matheus Marçal Ramos de Oliveira       (RA: 10409001)
* Aluno 5: Pedro Akira Cardoso Toma               (RA: 10390171)


# Descrição do Projeto

A Escola Infinito deseja alterar a forma de validação de presença dos alunos do Fundamental I, para que a mesma seja feita de forma mais eficiente e consistente, buscando praticidade, pois ainda utilizam a chamada em papel até os dias de hoje. Nossa equipe foi contatada para realizar a operação desejada, priorizando as exigências feitas pela Escola após coletarmos as informações necessárias para projetar uma solução, implementá-la e disponibilizá-la para os envolvidos.

A equipe decidiu priorizar e atender de imediato os pontos levantados durante a reunião com a escola. Dessa forma, definimos os requisitos funcionais a partir desses pontos, que serão o foco principal nesse primeiro momento. Os requisitos não-funcionais serão definidos de acordo com as bases de como um bom software deve se portar e serão implementados ao decorrer do processo de criação do projeto em si.

A ideia de fazer um sistema de chamada veio com alguns desafios, principalmente o de definir quem serão os atores que utilizarão o sistema. No nosso ponto de vista, haverá três atores principais: os responsáveis pela criança, que utilizarão o sistema para verificar a presença da mesma; a secretaria, que terá o papel de alterar a base de dados (sobre quais alunos estão matriculados, que professores ministram quais aulas, etc.) e também de reprovar o aluno em si; e, por fim, os professores, que irão fazer a chamada e registrar presença/falta do aluno no dia em determinada aula. Dessa forma, o sistema gira em torno do aluno, porém sem nenhum contato direto do mesmo, visto que serão crianças e não haveria necessidade para elas acessarem o sistema.

O sistema será dividido em módulos específicos para cada ator. Os responsáveis terão acesso a um portal onde poderão visualizar a presença de seus filhos em tempo real. A secretaria terá um painel administrativo para gerenciar os dados dos alunos e professores, além de funções de supervisão e auditoria. Os professores contarão com uma interface simples para registrar a presença ou falta dos alunos de forma rápida e eficiente durante as aulas. Então, desde o cadastro inicial dos alunos até a geração de relatórios de presença e a comunicação automática com os responsáveis, o sistema buscará automatizar ao máximo as tarefas repetitivas e garantir a segurança e confidencialidade dos dados dos alunos.

Portanto, o sistema de chamadas que desenvolveremos terá como base esses pontos mencionados acima. Ele permitirá um controle mais rigoroso e eficiente da presença dos alunos, substituindo o processo manual atual por um sistema digital integrado. O sistema será projetado para ser intuitivo e acessível para todos os atores envolvidos, garantindo que as informações estejam sempre atualizadas e facilmente acessíveis. Dessa forma, a Escola Infinito estará preparada para oferecer um serviço mais moderno e eficaz, melhorando a experiência de todos os envolvidos no processo educacional.

# Análise de Requisitos Funcionais e Não-Funcionais
  ## Requisitos Funcionais
  * Registro: base de controle de presença, para coletar os dados necessários, ou seja, as faltas;
  * Cadastro: para ser realizado tal registro, professores e alunos serão os atores do sistema, turma e matéria, serão fundamentais para cadastrá-los;
  * Acessibilidade: como a Escola pontuou na coleta de informações, será umas das prioridades que todas as pessoas envolvidas possam utilizar o sistema;
  * Acesso em todo navegador/dispositivo: necessário para garantir que todos os usuários tenham acesso independente de onde acessam;
  * Relatório de Faltas: a organização de todos os dados em si foi requisitada pelo cliente;
  * Notificação: importante para alertar os usuários sobre as faltas.

  ## Requisitos não Funcionais
  São os requisitos base para um bom software, porém não serão a prioridade para o primeiro momento do projeto. Sendo eles:
  * Segurança: garantir medidas de prevenção para possíveis ameaças e vulnerabilidades;
  * Confiabilidade: garantir a sincronização dos dados presentes na base de dados e disponibilizados para alteração;
  * Responsividade: garantir um tempo de resposta adequado após a inserção de informações pelo usuário;
  * Desempenho: o sistema deve ser ágil para alterar e buscar informações de alunos na base de dados, facilitando o seu uso;
  * Backup/Preservação de dados: garantir a preservação dos dados (núvem/disco) para restauração, caso necessário;
  * Interface de usuários: garantir uma interface intuitiva e de fácil utilização.

# Diagrama de Atividades

![sdasdasdadsdas](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/e4f5b520-74d4-4f48-8be2-186a58a47575)

 > _Figura 1: Diagrama de atividades elaborado pelos alunos_

# Diagrama de Casos de Uso

![diagramadeuso](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/59d57d07-6f15-4aef-83ba-59f7b757576e)

 > _Figura 2: Diagrama de casos de uso elaborado pelos alunos_

# Descrição dos Casos de Uso
Após a elaboração dos diagramas e discussões com o grupo, foram definidos quatro casos de uso fundamentais para o projeto. Estes casos foram concebidos para abordar as necessidades essenciais do sistema de validação de presença: realizar a chamada, visualizar a presença do aluno, atualizar a base de dados e reprovar o aluno. Cada um desses casos desempenha um papel crucial na implementação de um sistema completo e funcional, garantindo que todas as etapas do processo sejam contempladas de maneira eficiente.


Caso de uso 1: Fazer a chamada

![Captura_de_tela_2024-04-02_174025-transformed (1) (1)](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/b4373e8d-43cd-43b4-8eec-66f48e3c64f4)

> _Figura 3: Caso de uso - Fazer a chamada_
>     


Caso de uso 2: Vizualizar a presença do aluno

![2](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/cad5d7fa-e607-49be-8724-eb5c4c6d3117)

> _Figura 4: Caso de uso - Vizualizar a presença do aluno_


Caso de uso 3: Alterar a base de dados

![image](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/9c8ef910-d292-45b8-9a9e-2cdb14e90073)

> _Figura 5: Caso de uso - Alterar a base de dados_


Caso de uso 4: Reprovar aluno

![image](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/2ea20588-db5f-43f0-b6f2-88454a1577e2)

> _Figura 6: Caso de uso - Reprovar aluno_



# Diagrama de Sequência

Ordem e interação dos objetos relacionados ao professor:

![image](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/1fd523e4-50b1-40d3-ad7b-f57484bc47e7)

> _Figura 7: Diagrama de sequência - Professor_


Ordem e interação dos objetos relacionados ao responsável:

![image](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/1b59e8cd-c142-46de-ad7c-c8bdf2e3e813)

> _Figura 8: Diagrama de sequência - Responsável_


Ordem e interação dos objetos relacionados a secretaria:

![image](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/96ae2e5c-76c1-4ac1-89c9-d6750505c4f4)

> _Figura 9: Diagrama de sequência - Secretaria_



# Diagrama de Classes

![Diagrama_de_Classes1 drawio](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/34073d89-5918-4de9-b941-2140b41d5341)

> _Figura 10: Diagrama de relacionamento entre classes para os seus atributos e operações_



# Diagrama de Estados

Comportamento interno relacionado ao professor:

![Diagrama_de_Estado_Professor drawio](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/ebb3c2f1-0904-4746-b702-e92f8b5dcf6a)

> _Figura 11: Diagrama de estado - Professor_

Comportamento interno relacionado ao responsavel:

![Diagrama_de_Estado_Responsavel drawio](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/ce83a665-7d82-47d9-9706-ae8fefa5ed55)

> _Figura 12: Diagrama de estado - Responsável_

Comportamento interno relacionado a secretaria:

![Diagrama_de_Estado_Secretaria drawio](https://github.com/EFGMP/UML-Classroom-FCI/assets/161724871/f746ca53-8232-4261-bd93-e0aede91b8e2)

> _Figura 13: Diagrama de estado - Secretaria_



# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

Engenharia de software
Roger S. Pressman; Bruce R. Maxim
