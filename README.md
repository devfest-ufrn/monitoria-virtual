# Sistema de Monitoria Virtual
-----------------
## Descrição Geral do Sistema

### Desafio
-----------------
Atualmente os alunos do BTI não costumam procurar os monitores das disciplinas para tirar suas dúvidas. Seja porque muitos estudantes já trabalham, ou porque os horários de monitoria conflitam com os horários das aulas de outras disciplinas, ou mesmo por falta de interesse de alguns alunos. Pensando nisso, vamos abordar como poderemos centralizar a comunicação entre alunos, monitores e até mesmo professores, em um canal rápido, prático e simples de ser usado.
O nosso principal desafio é fazer com que a monitoria no geral se torne algo mais simples e direto, para que seja mais utilizada. Nosso propósito é elencar as causas do problema para criar um produto baseado nas necessidades do usuário, que nesse caso são principalmente os alunos e monitores do BTI.

### Limites do Problema
-----------------
Após elencar os principais fatores que geram o problema que queremos resolver, faremos um planejamento cruzando os principais fatores com a dificuldade de se resolver cada um deles. Com isso, esperamos ter uma lista dos problemas POSSÍVEIS de se resolver dentro do escopo da disciplina, mas que ao mesmo tempo sejam impactantes para o nosso propósito maior.
Baseado nas nossas pesquisas, chegamos a conclusão que a funcionalidade principal a ser desenvolvida são as threads de dúvidas (como o StackOverflow), que contará com as seguintes funcionalidades:

1. O aluno pode publicar uma pergunta. Para permitir que o aluno descreva melhor sua dúvida, serão disponibilizados vários formatos de mídia: texto puro, trecho de código, link, citação, imagem, vídeo, áudio ou arquivo (qualquer formato) em anexo.
2. O aluno pode responder uma pergunta, também se utilizando de vários formatos de mídia. Para garantir a confiabilidade das respostas, o monitor deve avaliar todas as respostas, que recebem o status “aguardando avaliação”, “aprovada” ou “reprovada”.
3. Os alunos também podem comentar as respostas, além de votar na melhor resposta. O próprio monitor pode comentar, votar e responder quando achar conveniente. Quando o aluno achar que sua pergunta foi satisfatoriamente respondida, ele fecha a pergunta. 
4. O aluno poderá seguir uma pergunta para indicar que também possui uma dúvida semelhante e que também é de seu interesse que tal pergunta seja respondida.

Adicionalmente, precisamos de um mecanismo para organizar essas threads de forma que os usuários vejam threads que possívelmente o interessa, e também que seja fácil achar threads sobre os assuntos que o usuário precisa.

## Indicadores de sucesso
-----------------
Consideramos que esse trabalho será bem sucedido se, no final, tenhamos um protótipo funcionando que obtenha aprovação  dos nossos usuários. Ou seja, esperamos PELO MENOS trilhar o caminho certo da implementação deste produto, e, mesmo que no final da disciplina ele não esteja 100% concretizado, alcançar indícios de que estamos desenvolvendo algo que faz sentido para os usuários e que os agrada será o indicador de sucesso mais importante para a equipe.

### Objetivos finais
-----------------
Complementando o que foi dito anteriormente, nosso objetivo final é um produto que consiga atacar os principais problemas geradores do problema maior que queremos resolver, de forma que no mínimo nossos usuários sintam que estamos desenvolvendo a coisa certa, que estamos no caminho certo.
Esperamos também desenvolver uma aplicação que sirva como canal de comunicação para aproximar alunos e monitores do IMD. Incentivando os alunos a cooperar entre si para sanar suas dúvidas, entrar em contato com o monitor e frequentar a monitoria, além de manter o interesse pelo conteúdo da disciplina. A ferramenta poderá auxiliar os monitores a gerenciar os encontros e entender as principais fontes de dúvidas dos alunos para tomar as devidas providências.
