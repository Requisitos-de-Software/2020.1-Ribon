# Cenários

## Introdução

Um cenário é um ambiente criado pela equipe de projeto para representar situações que ajude a compreender as interações entre os sistemas e também elicitar a parte comportamental do software. Essa técnica tem se provado muito eficiente para levantamento de requisitos apesar de informal.

## Metodologia 

A técnica funciona com a criação de narrativas que descrevem um episódio específico que necessitam do uso da tecnologia do nosso projeto. Assim criamos uma breve história de uma cena bem detalhada com atores para simular a situação.<br/><br/>
**Na criação dos nossos cenários utilizamos o seguinte modelo base:**  
<br/>

Tópico | Descrição 
:----: | :--------
**Título**   | Nome breve para o cenário
**Objetivo** | Finalidade da história 
**Contexto** | Local, tempo e pré-condição da história
**Atores**   | Personagens que participarão da história
**Recurso**  | Recursos envolvidos
**Restrição** | Critérios favoráveis, caso tenha
**Exceção**  | Critérios desfavoráveis, caso tenha
**Episódio** | Descrição da narrativa 
<br/>

## Nossos cenários

### C1 - Primeiro pedido de ajuda

|      | Descrição 
:----- | :--------
**Objetivo** | Adicionar seu primeiro pedido de ajuda no aplicativo 
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: precisar de algo urgente
**Ator(es)** | Nova usuária
**Recurso**  | Telefone com o aplicativo<br/> Telefone com internet
**Restrição** | Pedido possível de ser feito pelo aplicativo
**Exceção**  | Falta de sinal de internet
**Episódio** | Usuária conhece o Mia Ajuda e se cadastra.<br/> Usuária necessitou de remédios para seu filho.<br/> Usuária anuncia sobre sua necessidade.<br/>Usuária aguarda que seu pedido seja atendido.
<br/>

### C2 - Cadastro no aplicativo

|      | Descrição 
:----- | :--------
**Objetivo** | Criar uma conta no Mia Ajuda
**Contexto** | Local: página inicial do aplicativo<br/>Tempo: de manhã<br/>Pré-condição: ainda não possuir cadastro
**Ator(es)** | Usuário não cadastrado
**Recurso**  | Telefone com o aplicativo<br/>Acesso a internet<br/>Conta de e-mail<br/>
**Restrição** | Possuir telefone com câmera<br/>Conta de e-mail ativa<br/>Serviço de localização do telefone ativado
**Exceção**  | CPF já cadastrado<br/>E-mail já cadastrado
**Episódio** | Usuário não cadastrado abre o aplicativo.<br>Usuário seleciona criar conta.<br> Usuário seleciona uma localização próxima a sua residência.<br> Usuário preenche e-mail, senha e confirmar senha.<br> Usuário recebe e-mail de confirmação e recebe acesso a página do aplicativo.
<br/>

### C3 - Primeira ajuda realizada

|      | Descrição
:----- | :--------
**Objetivo** | Executar um pedido de ajuda no aplicativo 
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: ter a agenda livre
**Ator(es)** | Nova usuária
**Recurso**  | Telefone com o aplicativo<br/> Telefone com internet<br/> 
**Restrição** | Encontrar pedido em uma localidade próxima<br/>Condição de contribuir com a ajuda
**Episódio** | Usuária conhece o Mia Ajuda e se cadastra.<br/> Usuária pretende contribuir com sua primeira ação solidária.<br/> Usuária encontra no mapa uma solicitação próxima a sua residência.<br/>Usuária aceita pedido.
<br/>

### C4 - Ajudando pessoas do grupo de risco

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer ajuda para alguém no isolamento social
**Contexto** | Local: trabalho<br/>Tempo: horário de almoço<br/>Pré-condição: poder sair do escritório
**Ator(es)** | Ajudante e idoso
**Recurso**  | Telefone com o aplicativo<br/> Acesso à internet<br/> Automóvel
**Restrição** | Não possuir outro compromisso na hora do almoço
**Exceção**  | Pouco tempo disponível<br/>Possuir algum sintoma de COVID-19
**Episódio** | Ajudante entra no aplicativo.<br/> Ajudante busca por pedidos de ajuda em localidades próximas.<br/> Ajudante encontra um idoso que precisa de fazer compra suprimentos básicos para casa.<br/> Ajudante contacta o idoso para mais informações.<br/> Ajudante vai ao mercado às compras.<br/>Ajudante e idoso se encontram com todo cuidado necessário e finalizam o pedido.
<br/>

### C5 - Mão de obra amiga

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer pequenos serviços
**Contexto** | Local: bairro próximo<br/>Tempo: sábado de manhã<br/>Pré-condição: não possuir outro compromisso
**Ator(es)** | Usuário ajudante, usuário ajudado
**Recurso**  | Carro<br/>Telefone com aplicativo<br/>Telefone com acesso à internet<br/>Ferramentas de construção
**Restrição** | Ter o dia livre<br/>Familiaridade com as ferramentas<br/>
**Exceção**  | Problemas com carregamento de peso ou esforço físico<br/>Usuário ajudante com alguma deficiência
**Episódio** | Ajudante pode contribuir no aplicativo com pedidos apoio físico.<br/>Ajudado solicita voluntário para demolição das paredes de um cômodo em sua casa.<br/>Ajudante aceita o pedido e marca um horário.<br/>Ao final do dia as paredes estavam derrubadas.<br/>
<br/>

### C6 - Logar no aplicativo

|      | Descrição 
:----- | :--------
**Objetivo** | Entrar no seu perfil
**Contexto** | Local: página inicial do aplicativo<br/>Tempo: de manhã<br/>Pré-condição: ter saído da conta
**Ator(es)** | Usuário já cadastrado
**Recurso**  | Telefone com o aplicativo<br/>Acesso a internet<br/>Conta de e-mail<br/>Senha
**Restrição** | E-mail cadastrado<br/>
**Exceção**  | E-mail incorreto<br/>Senha incorreta
**Episódio** | Usuário já cadastrado abre o aplicativo.<br> Usuário preenche e-mail e senha e selecionar entrar.<br> Usuário é redirecionado para página inicial logada.
<br/>

### C7 - Colaboração psicológica

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer ajuda psicológica 
**Contexto** | Local: clínica de terapia<br/>Tempo: sexta a tarde<br/>Pré-condição: agenda de atendimentos vazia
**Ator(es)** | Psicóloga, usuário ajudado
**Recurso**  | Telefone com aplicativo<br/>Telefone com acesso à internet<br/>
**Exceção**  | Não ser profissional da área de psicologia.
**Episódio** | Psicóloga entra no aplicativo.<br/>Psicóloga encontra pedido de apoio psicológico.<br/>Usuário e psicóloga combinam um horário para a sessão.<br/>Em uma chamada pelo telefone ocorre o diálogo.<br/>Primeira sessão de conversa finalizada.
<br/>

### C8 - Auxílio com transporte de emergência

|      | Descrição 
:----- | :--------
**Objetivo** | Levar o usuário em uma consulta médica 
**Contexto** | Local: hospital regional<br/>Tempo: à tarde<br/>Pré-condição: possuir um automóvel.
**Ator(es)** | Usuário voluntário, usuário ajudado
**Recurso**  | Telefone com aplicativo<br/>Telefone com acesso à internet<br/>Carro<br/>
**Restrição** | Veículo com gasolina<br/>Tempo para esperar<br/>Não ser do grupo de risco
**Exceção**  | Hospital muito distante.<br/>
**Episódio** | Usuário voluntário entra no aplicativo em busca de solicitações de ajuda.<br/>Usuário voluntário encontra próximo à sua casa um pedido.<br/>Usuário voluntário vê descrição breve sobre o pedido.<br/>Usuário ajudado precisa de alguém que o leve em uma consulta no dia seguinte.<br/>Usuário voluntário está disponível no horário descrito.<br/>Pedido de ajuda aceito.
<br/>

### C9 - Apoio social

|      | Descrição 
:----- | :--------
**Objetivo** | Promover uma ajuda de apoio social
**Contexto** | Local: centro de ajudas sociais<br/>Tempo: a tarde<br/>Pré-condição: um grupo de pessoas dispostas a ajudar
**Ator(es)** | Usuários ajudantes, usuário cadastrado, criança carente
**Recurso**  | Acesso ao aplicativo<br/>
**Restrição** | Disponibilidade de tempo<br/>Conhecimento sobre ajudas sociais
**Episódio** | Usuários ajudantes entram no aplicativo em busca de pedidos.<br/> Usuário cadastrado conhece uma criança desamparada.<br/>Usuário cadastrado no Mia Ajuda cria um pedido de apoio social para a criança carente.<br/>Usuarios ajudantes aceitam o pedido e assumem a responsabilidade do caso.
<br/>

### C10 - Emergência com itens de proteção

|      | Descrição 
:----- | :--------
**Objetivo** | Doação de itens de proteção contra COVID-19
**Contexto** | Local: em casa<br/>Tempo: horário do almoço<br/>Pré-condição: 
**Ator(es)** | Usuário
**Recurso**  | Acesso ao aplicativo<br/>Máscaras<br/>Embalagem de álcool<br/>Luvas<br/>Avental
**Restrição** | Equipamentos esterilizados
**Exceção**  | Ajudantes com mais de 60 anos<br/>Ajudantes com algum sintoma de COVID-19
**Episódio** | Usuário participa de um trabalho voluntário durante a pandemia.<br/> Usuário não possui recursos para comprar seus materiais de proteção frequentemente.<br/>Usuário solicita no Mia Ajuda um pedido dos seguintes itens de proteção (máscaras, álcool, luvas e avental).
<br/>

### C11 - Pedido de ajuda confirmado

|      | Descrição 
:----- | :--------
**Objetivo** | Notificar o usuário que seu pedido de ajuda será atendido
**Contexto** | Local: na página de confirmação do Mia Ajuda<br/>Tempo: horas depois do pedido de ajuda<br/>Pré-condição: alguem aceitar ajudar
**Ator(es)** | Usuário ajudante e usuário ajudado
**Recurso**  | Acesso ao aplicativo<br/> acesso à internet
**Episódio** | Usuário ajudante procurar alguem para ajudar<br/> Usuário ajudante achar e aceitar um pedido de ajuda<br/> Chegar a notificação no aplicativo de quem pediu a ajuda

### C12 - Procurar pedido de ajuda

|      | Descrição 
:----- | :--------
**Objetivo** | O usuário achar uma ajuda pendente
**Contexto** | Local: em casa<br/>Tempo: de manhã<br/>Pré-condição: estar com a internet e GPS ligados
**Ator(es)** | Usuário
**Recurso**  | Acesso ao aplicativo
**Exceção**  | Não ter nenhuma ajuda pendente ao redor
**Episódio** | O usuário vai abrir o aplicativo e colocar sua localização e o raio de distância<br/> O aplicativo vai mostrar todas as ajudas disponiveis dentro do raio de distância ao redor da localização do usuário

### C13 - Sair do aplicativo

|      | Descrição 
:----- | :--------
**Objetivo** | Sair de uma conta logada
**Contexto** | Local: em casa<br/>Tempo: qualquer hora<br/>Pré-condição: estar logado no aplicativo
**Ator(es)** | Usuário logado
**Recurso**  | Acesso ao aplicativo<br/> Acesso à internet<br/> 
**Restrição** | Estar logado no aplicativo
**Exceção**  | Cair a internet antes de completar a saida<br/> O aplicativo ser encerrado antes de sair
**Episódio** | Usuário abre o aplicativo<br/> Vai na seção de perfil<br/> Procura a opção de sair<br/> Confirma que quer sair


---

## Versionamento

|Data|Versão|Descrição|Autor|
|:--:|:----:|:-------:|:---:|
|3/10/2020| 0.1| Criação do escopo do documento| Ailamar Alves Guimarães|
|5/10/2020| 0.2| Adição dos cenários C1 a C10 | Ailamar Alves Guimarães|
|7/10/2020| 0.3| Adição dos cenários C11 a C13 | Matheus Amaral Moreira|

### Referências 

- Requisitos - Aula 10. Milene Serrano e Maurício Serrano. Disponívem em: <https://aprender3.unb.br/pluginfile.php/426741/mod_resource/content/1/Aula%2010.pdf>. Acesso em out. 2020.

- Modelagem - Cenários. GORETTI, André; ROCHA, Ian; ANTUNES, João Gabriel; COSTA, Marco Antônio; DANTAS, Murilo; BRAZ, Thallys. Disponível em: <https://requisitos-de-software.github.io/2019.2-Audible/cenarios/>. Acesso em out. 2020.
