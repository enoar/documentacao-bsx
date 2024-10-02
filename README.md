# documentacao-bsx


## Campanha


A funcionalidade de campanhas de contratação em massa da BSX RH é uma ferramenta poderosa para empresas que buscam otimizar seu processo de recrutamento. Com essa funcionalidade, ela permite criar campanhas de forma prática e eficiente, preenchendo informações essenciais como salário, local de atuação e o perfil desejado do profissional.

Uma das grandes vantagens dessa ferramenta é a capacidade de enviar mensagens automáticas para os candidatos, facilitando o contato inicial e mantendo um fluxo de comunicação constante ao longo do processo seletivo. Além disso, é possível definir testes de pré-seleção, com notas de corte, para garantir que apenas os candidatos mais adequados avancem no processo.

Após a criação da campanha, a BSX RH utiliza sua base de dados interna para identificar potenciais candidatos que já participaram de outros processos seletivos, além de buscar novos talentos em outros portais de emprego através de robôs de integração. Essa abordagem abrangente não apenas aumenta as chances de encontrar o profissional ideal, mas também economiza tempo e recursos, permitindo que as equipes de RH se concentrem em outras atividades estratégicas.

Com a BSX RH, as campanhas de contratação se tornam uma solução eficiente e eficaz, potencializando os resultados do recrutamento e garantindo que as empresas consigam atrair os melhores talentos disponíveis no mercado
## Ambiente Local

É necessário utilizar o Postgres, Java, Node, RabbitMQ.

Após a instalação dos pre-requisitos acima é necessário criar os seguintes bancos:

agendamento_db
cadastro_db
campanha_db
leads_db
licensa_db
linkedin_db
prova_db
teste_integracao_db
usuario_db

Todas as tabelas e registros iniciais já são criados automaticamente na primeira vez que o projeto é rodado.


Front

https://github.com/belchiorSX/admin

BackEnd

https://github.com/belchiorSX/gateway

https://github.com/belchiorSX/notificacao

https://github.com/belchiorSX/usuario

https://github.com/belchiorSX/report

https://github.com/belchiorSX/teste-integracao

https://github.com/belchiorSX/leads

https://github.com/belchiorSX/cadastro

https://github.com/belchiorSX/campanha

https://github.com/belchiorSX/agendamento

https://github.com/belchiorSX/licensa

https://github.com/belchiorSX/prova

https://github.com/belchiorSX/bsx-driver

https://github.com/belchiorSX/bsx-media

Robôs

https://github.com/belchiorSX/robo-bne

https://github.com/belchiorSX/linkedin-web-scrapper

## Painel de Vagas

A funcionalidade do painel de vagas da BSX RH proporciona uma maneira eficiente e transparente de gerenciar oportunidades de emprego. Todas as vagas criadas pelo cliente ficam expostas nesse painel, permitindo que qualquer candidato que acessar a página de recrutamento e seleção do cliente possa se candidatar de forma simples e direta.

Essa visibilidade não só amplia o alcance das oportunidades, mas também facilita a interação entre os candidatos e as empresas. Ao acessar o painel, os candidatos podem visualizar todas as vagas disponíveis, incluindo detalhes relevantes como descrição da função, requisitos, salário e local de atuação. Isso ajuda a garantir que apenas os profissionais mais alinhados se inscrevam para as posições.

Além disso, o painel de vagas é uma ferramenta dinâmica que permite ao cliente atualizar constantemente as informações, garantindo que os candidatos tenham acesso às oportunidades mais recentes e relevantes. Com essa funcionalidade, a BSX RH torna o processo de recrutamento mais acessível e eficiente, promovendo uma experiência positiva tanto para os candidatos quanto para as empresas em busca de talentos.
## Recrutador

A BSX RH oferece uma funcionalidade robusta para recrutadores, permitindo que eles gerenciem todo o processo de recrutamento de maneira integrada e eficiente. Com essa plataforma, os recrutadores podem criar e gerenciar campanhas, realizar processos seletivos, e avaliar as entrevistas dos candidatos, garantindo um acompanhamento detalhado de cada etapa.

Uma das características importantes é a possibilidade de realizar contratações ou declinações, sempre com a opção de fornecer feedback sobre os processos. Isso não apenas melhora a comunicação com os candidatos, mas também enriquece a experiência do recrutador, que pode ajustar suas estratégias com base nas informações coletadas.

Além disso, a BSX RH permite que os recrutadores exportem currículos e apliquem provas para os candidatos, facilitando a análise de habilidades e qualificações. No entanto, a plataforma garante a privacidade e a segurança dos dados. Os recrutadores não têm acesso ao nome completo dos candidatos; apenas o primeiro nome e a inicial do sobrenome são exibidos. Da mesma forma, as informações de contato dos candidatos não ficam disponíveis, e toda a comunicação é realizada exclusivamente por meio do software.

Essa abordagem protege a empresa contra vazamentos de informações sensíveis e promove um ambiente de recrutamento mais seguro e ético. Com a BSX RH, os recrutadores têm as ferramentas necessárias para conduzir processos seletivos de forma eficiente, mantendo a confidencialidade e a integridade dos dados dos candidatos.
## Avaliador


Dentro da plataforma BSX RH, os avaliadores técnicos desempenham um papel fundamental no processo de seleção de talentos. Eles recebem todas as informações necessárias para conduzir as entrevistas, incluindo o link de acesso e o horário previamente agendado, que são enviados por e-mail e WhatsApp. Além disso, os avaliadores podem acessar esses detalhes diretamente pelo sistema, garantindo que tenham sempre à mão as informações necessárias para a entrevista.

Após a conclusão da entrevista, os avaliadores têm a opção de entrar na plataforma para avaliar o candidato. Eles podem atribuir uma nota, que reflete sua percepção sobre o desempenho do candidato, e adicionar um descritivo detalhado da avaliação. Essa funcionalidade permite que os avaliadores compartilhem suas impressões de forma clara e objetiva, contribuindo para uma tomada de decisão mais informada no processo seletivo.

Com essa estrutura, a BSX RH não apenas facilita a comunicação e o gerenciamento de entrevistas, mas também assegura que as avaliações sejam registradas de maneira organizada, promovendo uma análise mais completa e colaborativa entre todos os envolvidos no recrutamento. Os avaliadores técnicos, portanto, desempenham um papel essencial na identificação dos melhores talentos, garantindo que a empresa encontre o profissional ideal para cada vaga.
## Leads

A API de leads da BSX RH é uma ferramenta poderosa que potencializa o recrutamento ao conectar empresas a uma vasta rede de candidatos. Com mais de 100 mil leads disponíveis na plataforma, as empresas podem divulgar suas vagas de forma direcionada, alcançando profissionais qualificados que estão em busca de novas oportunidades.

Além da divulgação de vagas, a BSX RH permite que cada empresa crie sua própria base de leads, onde apenas ela poderá realizar a comunicação. Isso proporciona um controle total sobre o relacionamento com os candidatos, permitindo que as empresas desenvolvam estratégias personalizadas de engajamento e recrutamento.

A busca ativa por prospectos é facilitada, seja utilizando leads próprios ou aqueles fornecidos pela BSX RH. Além disso, as empresas têm a opção de contratar candidatos de terceiros que já foram selecionados e avaliados por parceiros confiáveis. Isso expande ainda mais as oportunidades de encontrar talentos adequados para as vagas disponíveis.

Outra funcionalidade interessante é a possibilidade de as empresas venderem candidatos que não foram aproveitados, mas que passaram por todo o processo seletivo. Essa abordagem não só maximiza a utilização dos recursos de recrutamento, mas também gera uma nova oportunidade de receita para as empresas.

Com a API de leads da BSX RH, as empresas têm acesso a uma solução abrangente e flexível para otimizar seu processo de recrutamento, garantindo que possam encontrar e gerenciar talentos de forma eficaz no mercado competitivo atual.
## Acesso Demonstração

Empresa teste A
https://rh-web-2.firebaseapp.com/#/

Empresa teste b
https://bsx-rh.web.app/

login: admin@bsx.com
senha: 1mM@teste

Vídeo:
https://vimeo.com/813381517

## Arquitetura


![Imagem](https://firebasestorage.googleapis.com/v0/b/betsure-36cd0.appspot.com/o/rh.drawio%20(3).png?alt=media&token=adbbf779-4b0b-4b83-a816-6566192c4705)




## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


# BSX RH

Sistema BSX RH - Recursos Humanos White Label
Descrição do Produto:
O BSX RH é uma solução de Recursos Humanos white label que permite a personalização da plataforma com a identidade visual de cada empresa. Desenvolvido para otimizar os processos de recrutamento e seleção, o sistema oferece uma ampla gama de funcionalidades que facilitam a gestão de candidatos.

Principais Funcionalidades:

Entrevistas Gravadas:



Gravação e armazenamento de entrevistas, proporcionando uma análise detalhada e um registro completo de todo o processo seletivo.



Banco de Dados de Candidatos:



O banco de dados é de propriedade do cliente, garantindo total controle e privacidade sobre as informações dos candidatos.



Integração com HackerRank:



Integra-se à plataforma HackerRank para a aplicação de testes técnicos especializados na área de TI, permitindo uma avaliação precisa das habilidades dos candidatos.



Integrações Personalizadas:



Possibilidade de integrar outras soluções de testes técnicos já utilizadas pela empresa, assegurando flexibilidade e personalização no processo de seleção.



Campanhas de Recrutamento:



Gerencia a contratação em massa, seguindo todos os ritos definidos na criação da campanha, incluindo triagem, entrevistas, testes e feedback, garantindo que cada etapa seja cumprida conforme as diretrizes estabelecidas.



Mercado de Negociação de Leads:



Um ambiente que permite a compra e venda de candidatos, facilitando a negociação e ampliando as opções de recrutamento.



Comunicação Integrada:



Comunicação eficiente com candidatos via WhatsApp e e-mail, assegurando interações rápidas e fluidas durante todo o processo de seleção.



Controle de Agendamento:

Calendário de Disponibilidade:



Integra um calendário onde os recrutadores podem marcar sua disponibilidade para entrevistas, sincronizando com ferramentas como Google Calendar ou Outlook.



Agendamento de Entrevistas:



Permite que os candidatos escolham horários disponíveis para entrevistas através de um link, facilitando o processo de agendamento.



Notificações:



Envia lembretes automáticos por e-mail ou SMS para candidatos e recrutadores antes das entrevistas.



Feedback do Processo Seletivo:

Sistema de Avaliação:



Após cada etapa, os recrutadores podem registrar feedback sobre o desempenho dos candidatos em um sistema de avaliação.



Relatório de Feedback:



Cria um modelo de relatório que sintetiza as avaliações, permitindo que os recrutadores compartilhem feedbacks com os candidatos, tanto positivos quanto negativos.



Follow-up:



Automatiza o envio de e-mails de feedback aos candidatos, informando sobre o status do processo e agradecendo pela participação.



Benefícios:

Mantém a identidade visual e a marca da empresa.

Aumenta a eficiência no recrutamento em massa.

Melhora a qualidade dos candidatos selecionados.

Reduz o tempo e os recursos investidos no processo de seleção.

Proporciona maior controle sobre os dados dos candidatos.

Conclusão:
O BSX RH é uma solução flexível e personalizável que atende às necessidades específicas de cada empresa, oferecendo uma experiência de recrutamento ágil e eficaz. Com a capacidade de gerenciar contratações em massa e seguir ritos de contratação definidos, sua organização pode otimizar o processo de seleção, assegurando que todas as etapas sejam seguidas de forma organizada e eficiente. Transforme seu processo de seleção com o BSX RH e aproveite uma experiência inovadora e eficaz.
## Cadastro

O cadastro de candidatos na plataforma BSX RH é um passo fundamental para facilitar o processo de contratação e conectar talentos às oportunidades disponíveis. A seguir, explicamos como funciona esse processo e quais são os principais passos para se cadastrar.


Acesso à Plataforma: O primeiro passo consiste em acessar a plataforma BSX RH através de um navegador da web.



Criação de Conta: Após acessar a plataforma, o candidato deve criar uma conta. Para isso, será necessário fornecer informações básicas, como nome completo, e-mail e criar uma senha. A plataforma BSX RH solicitará a confirmação do e-mail para ativar a conta.



Preenchimento do Perfil: Com a conta criada, o próximo passo é preencher o perfil do candidato. Isso inclui informações sobre formação acadêmica, experiência profissional, habilidades e competências. É importante ser detalhado e honesto, pois essas informações ajudam os recrutadores a encontrar o candidato mais adequado para as vagas.



Configuração de Preferências: O candidato pode configurar preferências, como áreas de interesse, tipo de emprego (tempo integral, meio período, estágio, etc.) e localização desejada. Isso ajuda a plataforma a sugerir oportunidades que estejam alinhadas com as expectativas do candidato.



Busca por Vagas: Após completar o cadastro, o candidato pode começar a buscar vagas disponíveis. A plataforma geralmente oferece filtros de pesquisa para facilitar a busca, permitindo que o candidato encontre oportunidades que correspondam ao seu perfil.



Aplicação para Vagas: Quando o candidato encontrar uma vaga interessante, ele pode se candidatar diretamente pela plataforma. Isso geralmente envolve o envio do currículo e, em alguns casos, a resposta a perguntas específicas relacionadas à vaga.



Acompanhamento do Processo: Após a aplicação, o candidato pode acompanhar o status da sua candidatura através da plataforma. Muitas vezes, as plataformas oferecem atualizações sobre o andamento do processo seletivo.



Interação com Recrutadores: As entrevistas ocorrem diretamente na plataforma BSX RH. Após a candidatura, o candidato receberá opções de horários para a entrevista e poderá escolher aquele que melhor se adequa à sua disponibilidade.



Privacidade e Segurança: É importante que o candidato esteja ciente das políticas de privacidade da plataforma, garantindo que suas informações pessoais e profissionais estejam protegidas.



O cadastro na plataforma BSX RH é uma oportunidade valiosa para os candidatos se destacarem no mercado de trabalho. Ao seguir esses passos e manter um perfil atualizado, os candidatos aumentam suas chances de serem notados por empregadores e, consequentemente, de conseguirem uma colocação profissional que se alinhe às suas aspirações.
## Agendamentos

Na BSX RH, o agendamento de entrevistas foi otimizado para proporcionar uma experiência fluida tanto para recrutadores quanto para candidatos. O processo é simples e eficiente: o recrutador inicia selecionando uma variedade de horários disponíveis que se encaixam em sua agenda. Essas sugestões são então enviadas aos candidatos, permitindo que cada um escolha o horário que melhor se adapta à sua disponibilidade.

Após o candidato selecionar o horário desejado e confirmar sua participação, todos os envolvidos — recrutador, avaliador e candidato — recebem automaticamente um link para a sala virtual, onde a entrevista ocorrerá. Essa abordagem não apenas facilita a coordenação entre as partes, mas também assegura que todos estejam alinhados e preparados para o processo seletivo.

Com a BSX RH, o agendamento de entrevistas se torna uma tarefa descomplicada, promovendo uma comunicação clara e eficiente, e contribuindo para uma experiência positiva para todos os participantes.
## Provas

A integração com parceiros na plataforma BSX RH ocorre por meio de uma API robusta e bem documentada, que facilita a conexão entre a plataforma da BSX e sistemas externos. Essa flexibilidade permite que os parceiros implementem suas próprias plataformas de avaliação ou utilizem soluções de terceiros, como a HackerRank, sem complicações.

A API da BSX RH foi projetada para ser intuitiva, proporcionando aos desenvolvedores a capacidade de integrar funcionalidades de forma rápida e eficiente. Com essa integração, as empresas podem personalizar suas avaliações, adaptar processos de recrutamento às suas necessidades específicas e garantir que os testes sejam realizados de maneira fluida e integrada.

Além disso, a API permite o compartilhamento de dados em tempo real, facilitando a análise de resultados e a geração de relatórios. Isso significa que os gestores de RH têm acesso imediato a informações cruciais sobre o desempenho dos candidatos, permitindo uma tomada de decisão mais ágil e fundamentada.

Em resumo, a API da BSX RH é um elemento central na estratégia de integração da plataforma, proporcionando aos parceiros a flexibilidade necessária para otimizar seus processos de avaliação e recrutamento, ao mesmo tempo em que mantém a eficiência e a precisão na gestão das informações.
## Perfil - Vaga


O cadastro de perfil na plataforma BSX RH é uma etapa fundamental para quem deseja aprimorar sua visibilidade no mercado de trabalho e se destacar em processos seletivos. Ao criar um perfil, o usuário tem a oportunidade de definir suas habilidades, tanto as soft skills quanto as hard skills, que são essenciais para o sucesso profissional.

As soft skills referem-se a competências interpessoais, como comunicação, trabalho em equipe, empatia e resolução de conflitos. Estas habilidades são cada vez mais valorizadas pelas empresas, pois influenciam diretamente a dinâmica de trabalho e a cultura organizacional. Ao cadastrar essas habilidades na BSX RH, o usuário permite que os recrutadores identifiquem seu potencial para se adaptar a diferentes ambientes e colaborar efetivamente com colegas.

Por outro lado, as hard skills são as competências técnicas específicas que podem ser mensuradas e frequentemente adquiridas por meio de educação formal ou treinamento. Isso inclui conhecimentos em programação, idiomas, análise de dados, entre outros. A plataforma BSX RH possibilita que os usuários listem suas hard skills, facilitando a correspondência com as exigências dos empregadores.

Ao integrar essas informações no cadastro de perfil, a BSX RH não apenas ajuda os candidatos a se apresentarem de maneira mais completa, mas também otimiza os processos seletivos, tornando-os mais precisos e eficientes. Os recrutadores podem buscar candidatos que não apenas possuem a formação técnica necessária, mas que também se encaixam na cultura e nas dinâmicas da equipe.

Em resumo, o cadastro de perfil na BSX RH é uma ferramenta poderosa para o desenvolvimento profissional. Ao definir suas habilidades de soft e hard skills, os usuários aumentam suas chances de serem notados por empresas que valorizam tanto o conhecimento técnico quanto as competências interpessoais, abrindo portas para novas oportunidades de carreira.
## Arquitetura


![Imagem](https://firebasestorage.googleapis.com/v0/b/betsure-36cd0.appspot.com/o/rh.drawio%20(3).png?alt=media&token=adbbf779-4b0b-4b83-a816-6566192c4705)



