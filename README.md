
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet:  https://padlet.com/mateusdejesusg11/unishare-335t022zpks4cmlk

## 1. Introdução

***1.1.  Nome do Grupo***

[Sabrina Cavalcante de Queiroz](https://github.com/Sabrinascq)  
[Mateus de Jesus](https://github.com/IG-jeebas)  
[Janderson Silva](https://github.com/JandersonLSilva)  
[Nelson Meirelles](https://github.com/Nelsonjr-74)  
[Thiago Henrique](https://github.com/thiagohenrique06)  

***1.2.  Nome do Sistema***

*UNISHARE: Plataforma Colaborativa Acadêmica*

Missão: Otimizar o ecossistema educacional da UTFPR através de compartilhamento estruturado de conhecimento e avaliação docente colaborativa.

***1.3.  Propósito do Sistema***

O principal propósito do sistema é criar um aplicativo colaborativo voltado para estudantes da UTFPR, que funcione como um repositório de materiais de apoio acadêmico. A ideia é permitir o compartilhamento de conteúdos, além das informações do curso entre os alunos, organizando esses *materiais por professores e por assunto, promovendo assim a troca de recomendações sobre docentes e suas matérias.

***1.2.  Público Alvo***

Este documento se destina a Alunos Estudantes de graduação e pós-graduação da UTFPR, com ênfase em:

- **Calouros** necessitando de orientação acadêmica
- **Alunos de períodos avançados** compartilhando materiais a fim de serem apoiados.
  
***1.3. Descrição dos usuários***

Estudantes da UTFPR, cuja dificuldade está na organização e manipulação de arquivos diretamente relacionados às aulas, no armazenamento prático e intuitivo de documentos voltados para fins didáticos e na troca concreta e segura de recomendações sobre docentes e suas disciplinas.

__________________________________________________________________________________________________________________
***Personas:***

[Persona 1](Personas/Persona.pdf)

**Persona 1: Júlia Martins**

**Motivação:**
"Cansada de perder tempo com materiais desorganizados que prejudicam seu rendimento nas provas"

**Uso:**
"Acessa o UNISHARE toda segunda-feira para planejar estudos da semana"

**Requisitos atendidos:**

- RF4 (Busca por matéria)
- RF7 (Organização intuitiva

[Persona 2](Personas/Persona2.pdf)

**Persona 2: Lucas Andrade**

**Comportamento:**

"Prioriza eficiência: precisa conciliar trabalho e estudos"

**Expectativa:**
"Exige carregamento instantâneo mesmo com internet limitada" (RNF5)

**Requisitos atendidos:**

- RF1 (Busca de professores)
- RF15 (Feedback detalhado)
- RNF3 (Latência)

__________________________________________________________________________________________________________________

***Análise da situação atual: antes da introdução de sua solução***

1. O que as pessoas fazem?
   - Estudantes buscam materiais acadêmicos em diversos canais, como grupos de redes sociais, sites e e-mails compartilhados.  
   - Dependem de recomendações informais para obter informações sobre professores e disciplinas.  
   - Armazenam documentos de maneira desorganizada, muitas vezes dispersos entre dispositivos ou plataformas.  

2. Quais os artefatos envolvidos?
   - Arquivos digitais (PDFs, apresentações, apostilas, anotações).  
   - Plataformas de compartilhamento não estruturadas (WhatsApp, Telegram, Google Drive).  
   - Métodos informais de avaliação de docentes (conversas entre alunos, enquetes).  

3. O que elas precisam saber? 
   - Onde encontrar materiais confiáveis e organizados.  
   - Como trocar informações sobre professores e disciplinas.  
   - Métodos eficazes para armazenar e acessar documentos sem risco de perda ou desorganização.  

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***
1. O que as pessoas fazem?
   - Utilizam o aplicativo para armazenar, organizar e compartilhar arquivos de maneira intuitiva.  
   - Têm acesso direto a avaliações e recomendações sobre professores e disciplinas.  
   - Encontram materiais categorizados por assunto e docente sem depender de redes informais.  

2. Quais os artefatos envolvidos?
   - Interface do aplicativo UNISHARE.  
   - Banco de dados estruturado com categorias de arquivos e docentes.  
   - Sistema de avaliações e troca de recomendações.  

3. O que elas precisam saber?
   - Como utilizar o aplicativo para upload e download de materiais.  
   - Métodos de classificação e recomendação de docentes.  
   - Como garantir a segurança e privacidade dos arquivos compartilhados.
__________________________________________________________________________________________________________________

***Cenário: Antes***

Antes da introdução da solução, os alunos estavam com dificuldades para se situar tanto dentro quanto fora das salas de aula. Devido ao difícil acesso a informações rápidas, simples e objetivas, os alunos ficavam confusos e perdidos em relação à fonte de informações e aos meios de obtê-las. Na maioria das vezes, recorriam a informações desatualizadas ou incoerentes repassadas por outros alunos.

***Cenário: Depois***

Em seguida, em consequência da implantação do nosso sistema, o público-alvo (os alunos) ainda não tinha conhecimento de tal ferramenta. Porém, após um período de divulgações e indicações por professores e pela instituição, os estudantes se familiarizaram com êxito, utilizando e usufruindo do sistema. Isso fez com que suas dúvidas fossem sanadas, a dificuldade para encontrar suas salas fosse praticamente eliminada e, por fim, as respectivas informações fossem recebidas de maneira correta e objetiva.

__________________________________________________________________________________________________________________

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

| Identificador | Descrição | Dependente | Prioridade |
| :-: | :- | :- | :-: |
| RF1 | O sistema deve permitir os usuários a busca pelo nome de professor para poder acessar os feedbacks | RF13, RF15, RFN13, RF17 | M |
| RF2 | O sistema deve permitir os usuários inserir materiais de apoio | RF3, RF8 | M |
| RF3 | O sistema deve permitir que os usuários efetuem o login com RA, depois que se cadastrarem no site | RF8, RNF1, RNF10 | M |
| RF4 | O sistema deve permitir aos usuários realizar uma pesquisa de material por matéria | RF2, RF7, RF14, RF17 | M |
| RF5 | O sistema deve permitir os usuários avaliar os professores | RF13, RF3, RF16 | M |
| RF6 | O sistema deve enviar para os usuários notificações personalizadas | RF3, RF7, RNF7, RNF10 | C |
| RF7 | O sistema deve permitir os usuários organizar por disciplinas e professores | RF13, RF14, RF17 | M |
| RF8 | O sistema deve exigir a criação de um perfil para que os usuários possam enviar os materiais | RF3, RNF10 | S |
| RF9 | O sistema deve permitir que os usuários acessem um mapa interativo da UTFPR | RNF1, RNF5 | C |
| RF10 | O sistema deve permitir a acessibilidade para usuários cegos ou analfabetos | RNF1 | S |
| RF11 | O sistema deve permitir a interação e troca de comentários entre os usuários | RF3, RF8, RNF7, RNF10, RF16 | S |
| RF12 | O sistema deve permitir aos usuários acessar a área de notícias | RF3, RNF1 | C |
| RF13 | O sistema deve permitir o cadastro de professores na base de dados |  | M |
| RF14 | O sistema deve permitir filtrar professores, disciplinas e materiais | RF2, RF7, RF13, RF17 | M |
| RF15 | O sistema deve permitir criar feedbacks de professores | RF3, RF13, RF8, RF16 | M |
| RF16 | O sistema deve impedir mensagens e avaliações indevidas e ofensivas, por meio de validações do campo de avaliação |  | M |
| RF17 | O sistema deve permitir ordenação de forma crescente ou decrescente para campos alfanuméricos |  | M |
| RF18 | O sistema deve permitir que pessoas autorizadas verifique o upload de conteúdo não permitido, impróprio, etc., podendo tomar medidas cabíveis em cada situação |  | M |

***2.2. Requisitos Não Funcionais***

| Identificador | Descrição | Dependente | Prioridade | 
| :-: | :- | :- | :-: |
| RNF1 | O sistema deve ser compatível com os sistemas operacionais Android 10 ou superior e com os navegadores Chrome, Firefox e Edge, nas últimas três versões |  | M |
| RNF2 | Em caso de falha crítica, o sistema deve ser capaz de restaurar seu funcionamento completo em até 1 hora | RNF9, RNF11 | S |
| RNF3 | A navegação entre páginas do sistema deve ter latência inferior a 100ms em redes locais (LAN) e inferior a 300ms em redes móveis (4G ou superior) | RNF1, RNF5 | S |
| RNF4 | O sistema deve manter uma identidade visual próxima (tipografia, cores,) com base nas da UTFPR, para reforçar a familiaridade institucional |  | S |
| RNF5 | O aplicativo móvel deve otimizar o carregamento de imagens e arquivos, priorizando versões compactadas sempre que possível, visando reduzir o consumo de dados móveis | RNF1 | S |
| RNF6 | O sistema deve suportar no mínimo 1 TB de arquivos acadêmicos no ambiente de produção, com possibilidade de expansão conforme a demanda | RF2 | S |
| RNF7 | O sistema deve garantir que informações pessoais de alunos (como nome completo, e-mail e curso) só sejam visíveis a outros usuários com consentimento explícito | RF3, RF8 | M |
| RNF8 | A plataforma deve suportar pelo menos 5.000 usuários ativos simultaneamente sem impacto crítico no desempenho | RNF9 | S |
| RNF9 | Uma falha em um módulo (por exemplo, upload de arquivos) não deve comprometer o funcionamento de outros módulos (como busca ou autenticação) |  | M |
| RNF10 | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD), garantindo consentimento explícito para uso de dados pessoais e possibilidade de exclusão mediante solicitação | RF3, RF8, RNF7 | M |
| RNF11 | O sistema deve ser estruturado de forma que alterações em funcionalidades específicas (ex: sistema de recomendações) possam ser feitas sem impacto nos demais módulos | RNF9 | S |
| RNF12 | Dados em cache ou arquivos temporários devem ser removidos automaticamente após 7 dias ou após logout do usuário, garantindo economia de armazenamento | RNF1, RNF5 | C |
| RNF13 | O sistema deve conter um campo de upload de arquivos que aceite somentes documentos em formato PDF ou DOCX |  | C |

__________________________________________________________________________________________________________________
***2.3. Perguntas***
- Como você costuma acessar materiais acadêmicos? Existe alguma dificuldade em encontrá-los?
- Os professores costumam disponibilizar os materias? Gostaria que houvesse melhorias nesse aspecto?
- Como você avalia sua experiência ao interagir com outros alunos e professores na plataforma da instituição?(Tem retorno no quesito de resposta)?
- Você já teve problemas ao utilizar a plataforma da instituição no seu celular ou computador?
- O que poderia ser melhorado?
- Quando precisa acessar conteúdos  ou realizar buscas, você sente que o sistema responde rapidamente?
- O desempenho é satisfatório entre o Wifi e os dados móveis?
- O que poderia ser melhorado no sistema Unishare, e Qual seria a diferença que você sente entre nosso sistema e o Moodle?
- Quanto disponibilizar alguns materiais de outras instituições, você acha que facilitaria o seu acesso aos materiais dessas matérias?
- Você conhece alguém que tenha mais dificuldade em usar a plataforma do Moodle, por exemplo?
- Você acha que no Moodle existe esse apoio? (acessibilidade)
- Sobre a nossa plataforma e o Moodle, você acha que o designer da nossa plataforma, ele acaba facilitando a sua navegação?
- E se pudesse melhorar alguma coisa da interface da plataforma, o que você mudaria pra tornar mais intuitiva?
- E as Dificuldades para acessar plataformas de ensino, como que isso afetou a sua vida acadêmica?
- A nossa plataforma (UNISHARE)conseguiria concentrar um número maior de alunos e de professores interagindo entre si?

***2.4. Entrevista***
[Link para a gravação/documento de transcrição completo](https://drive.google.com/drive/folders/1I61nn2Ky0gpvgulWSAB93tj2LtrBtIbO)  

#### Resumo das descobertas:  
- **Problemas atuais:**  
  • Dificuldade para encontrar materiais (RF4, RF7)  
  • Comunicação falha com professores (RF11)  
  • Instabilidade técnica (RNF2, RNF3)  

- **Sugestão do usuário:**  
  • Organização padronizada por disciplina (RF14)  
  • Design minimalista (RNF4)  
  • Suporte a alta demanda (RNF8)  

__________________________________________________________________________________________________________________

***2.5. Histórias do Usuário***

RF1 - Buscar nome de professor para acessar feedbacks
Como um usuário, eu quero buscar pelo nome de um professor, para que eu possa acessar os feedbacks relacionados a ele.

RF2 - Inserir materiais de apoio
Como um usuário, eu quero inserir materiais de apoio, para que eu possa compartilhar conteúdos úteis com outros usuários.

RF3 - Login com RA após cadastro
Como um usuário, eu quero efetuar o login utilizando meu RA após o cadastro, para que eu possa acessar minhas informações e funcionalidades do sistema.

RF4 - Pesquisa de material por matéria
Como um usuário, eu quero pesquisar materiais por matéria, para que eu encontre conteúdos relevantes para minha disciplina de interesse.

RF5 - Avaliar professores
Como um usuário, eu quero avaliar professores, para que outras pessoas tenham acesso às opiniões sobre a qualidade do ensino.

RF6 - Notificações personalizadas
Como um usuário, eu quero receber notificações personalizadas, para que eu fique informado sobre atualizações e conteúdos relevantes para mim.

RF7 - Organização por disciplinas e professores
Como um usuário, eu quero organizar os materiais e informações por disciplinas e professores, para que eu encontre facilmente o que preciso.

RF8 - Criar perfil para enviar materiais
Como um usuário, eu quero criar um perfil, para que eu possa enviar materiais para a plataforma.

RF9 - Acessar mapa interativo da UTFPR
Como um usuário, eu quero acessar um mapa interativo da UTFPR, para que eu possa me localizar facilmente dentro do campus.

RF10 - Acessibilidade para cegos ou analfabetos
Como um usuário com necessidades específicas, eu quero que o sistema tenha recursos de acessibilidade, para que eu possa utilizá-lo sem dificuldades.

RF11 - Interação e troca de comentários
Como um usuário, eu quero interagir e trocar comentários com outros usuários, para que eu possa discutir e compartilhar ideias sobre os conteúdos disponíveis.

RF12 - Acessar área de notícias
Como um usuário, eu quero acessar a área de notícias, para que eu fique informado sobre novidades e comunicados importantes.

RF13 - Cadastro de professores na base de dados
Como um administrador, eu quero cadastrar professores na base de dados, para que eles possam ser associados a disciplinas e avaliações dos usuários

RF14 - Filtrar professores, disciplinas e materiais
Como um usuário, eu quero filtrar professores, disciplinas e materiais, para que eu possa encontrar facilmente informações relevantes.

RF15 - Criar feedbacks de professores
Como um usuário, eu quero criar feedbacks de professores, para que outras pessoas tenham acesso às minhas opiniões sobre as aulas.

RF16 - Impedir mensagens e avaliações ofensivas
Como um usuário, eu quero que mensagens e avaliações indevidas sejam impedidas, para que o ambiente do sistema se mantenha respeitoso e adequado.

RF17 - Ordenação crescente ou decrescente para campos alfanuméricos
Como um usuário, eu quero ordenar os dados de forma crescente ou decrescente, para que eu possa visualizar as informações de maneira mais organizada.

RF18 - Verificação de uploads impróprios
Como um administrador, eu quero verificar os uploads de conteúdo, para que eu possa tomar medidas cabíveis em relação a materiais inadequados.

__________________________________________________________________________________________________________________
***2.6. Diagramas de Caso de Uso e Especificações***

[Diagrama de Caso de Uso imagem](Diagramas-caso-de-uso/CasodeUso.png)

[Caso de Uso PDF](Diagramas-caso-de-uso/CasodeUso.pdf)

***2.7. Diagramas de Atividades***

[Diagrama de Atividades - Realizar Avaliação](Diagrama-de-Atividades/Realizar-Avaliação.png)

[Diagrama de Atividades - Autenticar Usuário](Diagrama-de-Atividades/Autenticar-Usuario.png)

***2.8. Diagrama de Classes***

[Diagrama de Classes](Diagrama-de-Classes/Diagrama-de-Classes.png)

***2.9. Matrizes de Rastreabilidade***
Aqui está sua tabela organizada no formato desejado:

| **ID Requisito** | **Descrição** | **História de Usuário Associada** | **Casos de Uso Relacionados** | **Prioridade** |
|-----------------|--------------|--------------------------------|---------------------------|-------------|
| RF1 | Buscar professor por nome para feedbacks | Como usuário, quero buscar pelo nome de um professor para acessar feedbacks relacionados | Visualizar avaliações de professores | M |
| RF2 | Inserir materiais de apoio | Como usuário, quero inserir materiais de apoio para compartilhar conteúdos úteis | Inserir materiais acadêmicos | M |
| RF3 | Login com RA após cadastro | Como usuário, quero efetuar login com meu RA após cadastro para acessar minhas informações | - | M |
| RF4 | Pesquisar material por matéria | Como usuário, quero pesquisar materiais por matéria para encontrar conteúdos relevantes | Acessar materiais acadêmicos | M |
| RF5 | Avaliar professores | Como usuário, quero avaliar professores para compartilhar opiniões sobre qualidade de ensino | Avaliar professores | M |
| RF6 | Notificações personalizadas | Como usuário, quero receber notificações personalizadas para ficar informado | - | C |
| RF7 | Organizar por disciplinas/professores | Como usuário, quero organizar materiais por disciplinas e professores para fácil acesso | Acessar materiais acadêmicos, Visualizar avaliações | M |
| RF8 | Exigir perfil para enviar materiais | Como usuário, quero criar um perfil para poder enviar materiais para a plataforma | - | S |
| RF9 | Acessar mapa interativo da UTFPR | Como usuário, quero acessar um mapa interativo da UTFPR para me localizar no campus | Visualizar mapa da UTFPR | C |
| RF11 | Interação e comentários entre usuários | Como usuário, quero interagir e trocar comentários para discutir conteúdos | Conversar no chat com outros usuários | S |
| RF12 | Acessar área de notícias | Como usuário, quero acessar área de notícias para ficar informado sobre novidades | Visualizar notícias da UTFPR | C |
| RF13 | Cadastrar professores na base | Como administrador, quero cadastrar professores na base para associar a avaliações | Inserir professores no banco de dados | M |
| RF15 | Criar feedbacks de professores | Como usuário, quero criar feedbacks de professores para compartilhar minhas opiniões | Avaliar professores | M |
| RNF1 | Compatibilidade com Android/navegadores | - | Todos os casos de uso | M |
| RNF4 | Identidade visual próxima da UTFPR | - | Todos os casos de uso | S |
| RNF7 | Privacidade de dados pessoais | - | Criar perfil, Interação entre usuários | M |
| RNF10 | Conformidade com LGPD | - | Todos os casos de uso com dados pessoais | M |


***2.9. Protótipos***

[Prototipação](https://ninjamock.com/s/BFQW7Lx)

