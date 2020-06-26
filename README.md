# Padrões de interoperabilidade para repositórios de dados de pesquisa

## Apresentação

A Parceria para Governo Aberto (do inglês, Open Government Partnership - OGP) é uma iniciativa internacional composta, atualmente, por mais de 79 nações. O Brasil é co-fundador dessa parceria que foi criada, em setembro de 2011, com o objetivo de difundir e incentivar globalmente práticas governamentais relacionadas à transparência dos governos, ao acesso à informação pública e à participação social.

As ações relativas à OGP são operacionalizadas, em cada país, por meio de um Plano de Ação Nacional, onde são especificados os compromissos em Governo Aberto assumidos pelo país e as estratégias e atividades para concretizá-los. Os planos de ação possuem duração de até dois anos e, ao longo desse período, os Governos precisam publicar, anualmente, um relatório de autoavaliação sobre a execução dos compromissos assumidos.

O Brasil publicou, em 29 de outubro de 2018, o seu 4º Plano de Ação Nacional composto por 11 compromissos, os quais foram co-criados com o envolvimento de 105 pessoas, representantes de 88 instituições, sendo 39 organizações da sociedade civil, 39 órgãos da Administração Pública Federal e 10 órgãos das Administrações Públicas Estaduais e Municipais. 

O Compromisso 3 do 4º Plano de Ação Nacional do Brasil tem o objetivo de “Estabelecer mecanismos de governança de dados científicos para o avanço da Ciência Aberta no Brasil”. Esse compromisso, conhecido como Compromisso pela Ciência Aberta, é coordenado pela Empresa Brasileira de Pesquisa Agropecuária (Embrapa) e conta com a parceria dos seguintes órgãos governamentais e da sociedade civil: Ministério da Ciência, Tecnologia, Inovações e Comunicações (MCTIC), Instituto Brasileiro de Informação em Ciência e Tecnologia (Ibict), Fundação Oswaldo Cruz (Fiocruz), Coordenação de Aperfeiçoamento de Pessoal de Nível Superior (Capes), Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq), Rede Nacional de Ensino e Pesquisa (RNP), Open Knowledge Brasil (OKBR), Comissão Nacional de Energia Nuclear (CNEN), Arquivo Nacional, Instituto de Pesquisa do Jardim Botânico do Rio de Janeiro (JBRJ).

A execução desse compromisso conta com ações desenvolvidas em nove marcos, sendo que o Marco 8 teve o objetivo de “definir padrões de interoperabilidade para repositórios de dados de pesquisa”, o qual esteve sob a responsabilidade do Ibict em parceria com o CNEN e a RNP,  também vale destacar a colaboração com a Universidade de Twente e cujo resultado é este documento.

As recomendações aqui propostas aplicam-se a todas as instituições de pesquisa que desenvolvem pesquisas financiadas com recursos públicos e tem o objetivo de orientar e promover a abertura e interoperabilidade dos dados científicos em apoio ao movimento da Ciência Aberta no Brasil. Os padrões de interoperabilidade aqui definidos visam guiar as instituições de pesquisa a construir ou aprimorar seus repositórios de dados científicos. 


## Introdução

A partir movimento Acesso Aberto surgiram novas necessidades e perspectivas que demandam a abertura de todo o processo científico para a sociedade de forma geral, surgindo então a Ciência Aberta (um termo guarda-chuva que abrange as práticas de abertura seguindo os princípios da transparência e colaboração). Um dos temas tratados na Ciência Aberta são os dados de pesquisa.

Porém ao tratar dados surgem novas dificuldades, a começar com sua própria definição, para isso surgiu a diferenciação de dados DE pesquisa e dados PARA a pesquisa, com dados DE sendo dados que surgiram com o método científico em mente e dados PARA, todos os outros que não surgiram neste contexto porém podem ser utilizados em uma pesquisa. 
Os repositórios, juntamente dos periódicos de dados são apontados como a ferramenta para  tratar destes dados. Como qualquer outro repositório é uma base de dados digital voltada para suprir a necessidade de armazenar, organizar e disponibilizar seus objetos digitais, o que no caso são os dados de pesquisa.

Porém com a diversidade de instituições, cada uma com diferentes realidades e necessidades, os mais distintos modelos e padrões de descrição surgiram. O que resulta em dificuldades de interoperabilidade e comunicação. Para tratar tais problemas iniciativas internacionais estabeleceram padrões garantindo assim a homogeneidade ou ao menos a compatibilidade.

### Objetivos

Entre as dificuldades encontradas uma das mais proeminentes é não adoção de padrões de metadados já conhecidos e bem estabelecidos ou de ao menos padrões compatíveis entre si. Esse documento tem o objetivo então de desenvolver e aplicar uma metodologia que estabeleça um padrão de metadados para dados de pesquisa que podem ser usados para descrever dados multitemáticos.

### Metodologia	

O estudo a seguir é então classificado como qualitativo que de acordo com Creswell (2007) “usa estratégias de investigação como narrativas, fenomenologias, etnografias, estudos baseados em teoria ou estudos de teoria embasada na realidade. O pesquisador coleta dados emergentes abertos com o objetivo principal de desenvolver temas a partir dos dados.“.
Para construção da proposta, foi realizada uma pesquisa exploratória (objetivando elaborar um levantamento) e análise descritiva que segundo Gil (2011, p. 28) “têm como objetivo primordial a descrição das características de determinada população ou fenômeno ou o estabelecimento de relações entre variáveis. ” acerca dos repositórios de dados no Brasil, registrados no re3data.org (Registry of Research Data Repositories). O levantamento dos dados ocorreu entre os anos 2019 e 2020.
A metodologia proposta foi desenvolvida em 2 etapas, uma para o estabelecimento de um padrão de metadados para dados de pesquisa gerais multitemáticos que os consiga descrever de forma minimamente satisfatória, e uma segunda etapa para o desenvolvimento de extensões por área do conhecimento para esse padrão.

- Padrão de metadados para dados de pesquisa gerais multitemáticos:

O primeiro passo no desenvolvimento deste padrão foi o estudo das diretrizes internacionais propostas pela OpenAIRE, ou seja as OpenAIRE Guidelines V3 e V4 e por fim as diretrizes DRIVE 2.0, apenas as diretrizes propostas se mostraram insuficientes para descrever a nova geração de necessidades dos dados então foram acrescentados os metadados da funcionalidade Fair Data Point (FDP).

- Extensões por área do conhecimento

Para o desenvolvimento das extensões por áreas do conhecimento, primeiro foi necessário definir como seriam definidas e divididas as áreas do conhecimento, para tanto foram realizada uma busca por árvores do conhecimento, sendo levantadas então a tabela do conhecimento CNPq, árvore do conhecimento do manual Frascati para pesquisa e desenvolvimento experimental e por fim a divisão utilizada pelo Data Curation Centre (DCC)/Research Data Alliance (RDA).

A partir da definição das árvore do conhecimento foram utilizados: uma ferramenta publicada pelo RDA e mantida pela comunidade o [Diretório de metadados](http://rd-alliance.github.io/metadata-directory/), que basicamente é uma lista de padrões de metadados divididos por área do conhecimento; e a lista de padrões de metadados do DCC baseado no diretório. Essas listas foram então desduplicadas e adaptadas para atender áreas específicas do conhecimento. Após essa seleção inicial uma verificação na plataforma re3data foi realizada visando conferir quais padrões estão realmente sendo utilizados.

Após o levantamento dos padrões foi realizada uma filtragem a fim de selecionar os padrões de metadados a partir da conferência da utilização ou não desses padrões pela comunidade. Essa verificação de utilização  foi realizada a partir da plataforma RE3DATA (re3data.org), um registro global de repositórios de dados de pesquisa para só então se iniciar a análise dos padrões.

Por fim é realizada uma análise dos padrões buscando quais campos seriam de maior importância para a descrição de dados da área em questão a partir da comparação dos padrões encontrados seguida da adequação às diretrizes OpenAIRE 4V e FDP.

Devido a extensão da proposta desenvolvida foram selecionadas 4 áreas para se testar a metodologia, Biologia (devido ao seu comportamento nas árvores do conhecimento levantadas), Agricultura (devido à importância da área nacionalmente), Ciências Sociais (devido ao caráter temático do âmbito institucional onde a pesquisa foi desenvolvida) e por fim Saúde (pela importante e pioneira atuação no movimento Acesso Aberto e outros aspectos relacionados à pesquisa científica). Vale destacar que durante o desenrolar da proposta especialistas das áreas foram consultados, em especial a Fiocruz (Saúde) e Embrapa (Agricultura).

## Desenvolvimento

O projeto Digital Repository Infrastructure Vision for European Research  (DRIVER) em 2007 publicou as Guidelines for content providers: Exposing textual resources with OAI-PMH, que contêm recomendações que permitem interoperabilidade entre repositórios. E desde então essas recomendações foram evoluindo e estão atualmente em sua versão 4.0 sendo chamadas de OpenAIRE Guidelines for Literature Repository Managers v4. A partir de 2013 a Comissão Européia (CE) com a publicação do Guidelines on Open Access to Scientific Publications and Research Data está de acordo com os requerimentos do Horizon 2020 abrangendo desde repositórios de literatura à repositórios de dados e sistemas CRIS.

Vale destacar ainda, outras iniciativas da CE como: a European Open Science Cloud (EOSC) de 2015 que visa implementar uma infraestrutura de práticas de ciência aberta; a promoção do princípios FAIR desde 2014 com a publicação de diversos guias e o relatório Turning FAIR into reality: Final Report and Action Plan on FAIR Data em 2018; as diretrizes PSI (Public Sector Information) de 2003, que em 2019 se transformaram nas Diretrizes para dados abertos e reuso de informações do setor público (Directive on open data and the re-use of public sector information); o programa e publicação Open Innovation, Open Science and Open to the World: a vision for Europe de 2016; por último reconhece-se a atuação da CE no Research Data Alliance (RDA) que em 2018 lançou a quarta fase de seu programa na plataforma, garantindo a participação de stakeholders a partir de projetos e financiamentos.

As diferentes versões das diretrizes estão apresentadas [aqui](https://guidelines.openaire.eu/en/latest/) (incluindo as diretrizes para arquivos de dados da versão 3.0) e versão mais recente [aqui](https://openaire-guidelines-for-literature-repository-managers.readthedocs.io/en/v4.0.0/index.html). A diretriz é dividida em três partes: Uma introdução onde ela é apresentada; Uso do OAI-PMH (Open Archives Initiative Protocol for Metadata Harvesting), onde são apresentadas algumas explicações sobre o uso do protocolo OAI-PMH e; por fim uma visão de um perfil de aplicação, que pode ser encontrado [aqui](https://openaire-guidelines-for-literature-repository-managers.readthedocs.io/en/v4.0.0/application_profile.html). A aplicação é baseada em quatro padrões de metadados: Dublin Core, Dublin Core qualificado, Datacite e Oaire (um padrão de metadados próprio desenvolvido pela OpenAIRE), além de serem utilizados diversos vocabulários controlados.

Ressalta-se que mesmo com o extensivo papel do protocolo OAI-PMH na interoperabilidade sintática o paradigma atual tecnológico está se desenvolvendo para cobrar mais. Assim outras iniciativas se destacam como os W3C: PROV-O (que baseiam o Fair Data Point) e DCAT 2.0, que incorpora classes para descrever os serviços de dados visando a implementação FAIR.

Nas diretrizes OpenAIRE V4. foram definidos quatro níveis de obrigatoriedade para metadados: Mandatório (M); Mandatório se aplicável (MA); Recomendado (R) e; Opcional (O). Seguem as explicações de cada um deles.

- Mandatório (M): Qualquer campo com esse nível de obrigatoriedade deve ser preenchido independentemente da situação, caso isso não ocorra estará em não conformidade com as diretrizes. (ex: Título)

- Mandatório se aplicável (MA): Quando o campo apresenta esse nível de obrigatoriedade ele deve ser preenchido caso a informação em questão esteja disponível. (ex: Contribuidor)

- Recomendado (R): O campo que apresentar esse nível de obrigatoriedade não necessita ser preenchido porém é beneficial que o faça. (ex: Identificador Alternativo)

- Opcional (O): Este nível de obrigatoriedade significa que seu preenchimento é de caráter completamente discricionário, caso se julgue que seu preenchimento enriquecerá o registro pode-se preenchê-lo ou não. (ex: Tamanho)

É apresentado no perfil de aplicação uma tabela  com os campos, elementos e vocabulários utilizados. São 32 campos no total, com seis mandatórios, oito mandatórios se aplicáveis, quinze recomendados e três opcionais. Para melhor visualização essa tabela foi reformulada e dividida de acordo com os níveis de obrigatoriedade a seguir. 

Os primeiros campos apresentados serão os **mandatórios (M)**:

**Tabela 1**- Campos Mandatórios


Campo | Metadado | Definição | Exemplo | Exemplo de aplicação | Vocabulário controlado
------|----------|-----------|---------|----------------------|-----------------------
Title (Título)datacite:title | Nome ou título pelo qual o recurso é conhecido | National Institute for ... | <datacite:title xml:lang="en-US"> |National Institute for ...




```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/lnpaganine/testeteste/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
