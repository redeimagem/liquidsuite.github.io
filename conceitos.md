# Liquid Suite - Introdução


### Conceitos 

De forma geral todos os itens citados acima, Usuário, Armário, Pasta e Ficha são objetos lógicos* dentro do sistema Liquid.  
***lógicos**. É uma entidade que possui atributos e existe apenas dentro do sistema, não sendo físico.  

**Usuário**: É um utilizador do sistema, ele recebe um login (nome) e senha para acesso, além de permissões que determinam o que ele poderá realizar dentro ambiente Liquid.  

**Armário**: É o repositório inicial da estrutura do sistema Liquid, ele armazenará todas as pastas e subpastas que venham a ser criadas pelos usuários com direitos de acesso a esse armário. Basicamente, vê-se o conceito de armário digital, como espelhamento do ambiente físico de um cliente quanto a sua distribuição dos documentos.  

No sistema Liquid um armário não interage com outro, ou seja, pastas e documentos de armários diferentes não contém acesso a pastas e documentos de outro armário. Para um usuário ter acesso a mais de um armário, ele deve receber as regras de acesso e de objeto que contemplam os armários que ele deverá acessar.  

**Pasta**: As pastas formam a estrutura mais básica de armazenamento Liquid, nelas armazenamos os documentos do sistema e também outras pastas, formando assim uma estrutura de pastas ou árvore de pastas.  

**Documento**: Os documentos têm uma estrutura parecida com a estrutura de pasta, pois um documento pode conter vários tipos de extensões, como PDF, PNG, XLS... 

**Ficha**: Fichas de indexação são fichas cadastrais dos documentos, onde um conjunto de campos são preenchidos com os dados do documento para sua localização posterior. As fichas também são conhecidas como modelos de documentos.   

Por exemplo, em uma biblioteca há um arquivo de cadastro de livros. Neste arquivo, há fichas onde são armazenados os dados de identificação de cada livro. Para localizar um determinado livro, o bibliotecário pesquisará nas fichas por algum dado (título, autor, gênero, data de lançamento, etc...) e saberá então em qual prateleira encontrar o livro que está procurando.
Em geral, cada modelo de documento possui uma ficha, com as chaves mais relevantes para determinado tipo de documento. Em uma biblioteca, além da ficha "Livros", podem existir ainda os modelos "Jornais" e "Revistas".  

Exemplo:  
**Livro**: Titulo, Autor, Edição, Editora, Ano de lançamento.  
**Jornais**: Nome, Data, Dia da semana, Manchete, Cidade.  
**Revistas**: Nome, Data, Manchete, País.  

Observe que cada tipo de documento pode possuir campos diferentes, que são escolhidos por sua relevância para cada tipo de documento.  

Em um sistema GED, cada Livro será um "documento" e possuirá uma ficha de indexação. Para localizar um título, utilizaremos a ferramenta de pesquisa para encontrar o documento desejado e acessá-lo.  

Convém, então, realizar um levantamento para definir quais modelos de fichas serão criadas (ou já estão criadas) no sistema GED, bem como qual será os campos de cada uma.