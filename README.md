# Angular Cursos - Alura

Repositório para salvar e compartilhar meus códigos desenvlvidos durante a formação "Explore o Framework Angular" da Alura.

## Angular 14: aplique os conceitos e desenvolva seu primeiro CRUD

Neste curso irei aprender o básico do Angular enquanto desenvolvo um projetinho com um CRUD completo.

O projeto é a Memoteca, uma biblioteca online onde podemos salvar pensamentos, frases, ideias e qualquer coisa interessante que quisermos salvar e deixar exposto no nosso mural.

### Aula 1

#### Entendendo a estrutura

Nesta aula aprendi o geral de como é a estrutura de um projeto Angular e como utilizar o CLI para criar um novo projeto, criar novos componentes e etc.

Também aprendi como os componentes da nossa aplicação podem ser utilizados no template HTML do "app", entendendo um pouco mais de como funciona o Decorator "@Component()".

### Aula 2

#### Aplicando Data Bindings

Nesta aula aprendi a aplicar os Data Bindings na aplicação, tornando dinâmico o que aparece no template, assim como o que fica salvo no componente.

Além disso, aprendi um pouco mais cobre o ngModel e como ele funciona, aplicando o Data Binding de via dupla.

### Aula 3

#### Aplicando rotas

Nesta aula aprendi a como utilizar rotas no Angular, utilizando o "router-outler" e o "RouterModule", assim tendo apenas uma parte da página que atualiza ao acessar outra rota, enquanto o resto da página principal continua a mesma coisa.

Também aprendi a criar links para outras rotas da nossa aplicação utilizando o "routerLink".

### Aula 4

#### Entendendo diretivas

Nesta aula pude aprender mais sobre as diretivas do Angular e aprender algumas diretivas novas, como ngFor, ngIf e NgClass.

Também aprendi as diferenças entre diretivas de componentes, estruturais e de atributos, aplicando os três tipos de diretivas no projeto Memoteca.

### Aula 5

#### Ajeitando projeto para utilizar Services

Nesta aula aprendi como configurar uma "Mock API" para utilizarmos na nossa aplicação, simulando uma comunicação real entre a nossa aplicação front-end com uma API do back-end.

Além disso, aprendi para que servem as classes Service no Angular, além de ter aprendido sobre como funciona a injeção de dependências no Angular, injetando o HttpClient na classe service do pensamento.

Também vi que é possível criar interfaces e utilizá-las normalmente no Angular, assim como no TypeScript, o que facilita muito na comunicação entre cliente e servidor.

### Aula 6

#### Fazendo requisições à API

Nessa aula aprendi a utilizar o HttpClient para fazer requisições à uma API do backend, vendo alguns detalhes de como esse recurso e o Observable funcionam, implementando todas as funcionalidades de um CRUD no projeto.

Também aprendi a criar uma API para o desenvolvimento do frontend utilizando o json-server, assim não tendo a necessidade de ter um backend pronto para dispararmos as requisições, assim tornando o desenvolvimento mais rápido e simples.

Além disso, aprendi mais sobre o Router e o ActivatedRoute, que ajudam muito para trabalhar com as rotas e extrair informações delas.

### Conclusão

Neste curso pude entender o básico do Angular e criar o meu primeiro CRUD usando o framework.

Foi muito legal desenvolver o projeto do curso e estou muito satisfeito com o resultado.

Me sinto mais confiante para desenvolver o frontend dos meus projetos utilizando o Angular e estou muito animado para continuar os meus estudos.

## Angular 14: evoluindo a aplicação

Neste curso irei melhorar o projeto "Memoteca", adicionando funcionalidades como pesquisa de pensamentos por autoria, curtidas em pensamentos, validações no formulário de criação de pensamento, entre outras.

### Aula 1

#### Aplicando fomulário reativo

Nesta aula aprendi a utilizar o módulo "ReactiveFormsModule" e algumas de suas classes para transformar o formulário de criação de pensamentos em um formulário reativo, o que ajudará muito quando for fazer as validações dos campos e etc.

Aprendi também a utilizar o "FormGroup" e os "FormControls" no template HTML do componente, assim conseguindo ter o "Two Way Data Binding", assim como conseguindo ler os valores dos "FormControls" com a interpolação em tags HTML.

### Aula 2

#### Fazendo validações no formulário

Nesta aula aprendi a utilizar a classe "Validators" do Angular para fazer validações nos campos do nosso formulário, assim podendo impedir a submissão do mesmo e mostrar mensagens personalizadas conforme o erro que for causado e apenas quando o usuário já tiver interagido com o campo em questão.

Também aprendi a desabilitar botões, mudar classes CSS de elementos e etc com base nos erros de validação, o que é muito útil.

Gostei bastante dessa aula e sinto que os formulários do site estão ficando muito mais robustos.

### Aula 3

#### Aplicando paginação no pensamentos

Nessa aula aprendi a aplicar paginação nos itens retornados pela API com o intuito de melhorar a performance da página, fazendo com que o usuário tenha que clicar em um botão para carregar mais pensamentos após os que já aparecem na tela, que foram limitados para o total de 6 pensamentos por página.

Para fazer isso, aprendi a utilizar a classe HttpParams, uma classe que facilita muito a utilizarmos parâmetros na URL em que iremos mandar a nossa requisição, fazendo com que não precisemos escrever os parâmetros na própria URL, e sim atribuí-los à uma instância da classe e passá-la junto com o corpo da requisição nos métodos do HttpClient.

### Aula 4

#### Adicionando funcionalidade de pesquisa

Nesta aula aprendi a implementar uma funcionalidade de pesquisa no projeto, modificando a lógica da requisição feita no service de pensamentos e adicionando um Event Binding ao input de pesquisa criado, para que a cada letra que o usuário digite seja disparada uma requisição ao backend onde o filtro será aplicado e serão retornados apenas os pensamentos que contém a string passada no input.

Também tive que lidar com a paginação ao mesmo tempo que essa pesquisa é feita, resetando todos os valores de página atual e afins, pois se isso não fosse feito, iria quebrar a página e a pesquisa não iria funcionar corretamente.

### Aula 5

#### Adicionando favorito

Nesta aula implementei a funcionalidade de favoritar e desfavoritar pensamentos, tendo um novo botão que muda a imagem conforme o valor de "favorito" do pensamento e muda esse valor quando é clicado.

Achei muito legal essa funcionalidade e, apesar de não terem sido aplicados conceitos novos, pude praticar as coisas já vistas até agora.

Agora falta implementar um filtro que só mostre os pensamentos favoritos para que o usuário possa aplicá-lo.

### Aula 6

#### Adicionando filtro de favoritos

Nesta aula implementei o filtro de pensamentos favoritos, que mostra apenas os pensamentos marcados como favoritos e continua funcionando normalmente com a paginação e a pesquisa, fazendo com que essas outras funcionalidades também só procurem entre os pensamentos favoritos.

Também implementei a funcionalidade de remover da lista de pensamentos favoritos um pensamento que o usuário desmarque dos favoritos enquanto vê a lista, o que não ocorria normalmente, utilizando o "subscribe()" do Observable, coisa que preciso estudar um pouco mais, pois vi que é muito poderoso implementando esta funcionalidade.

Além disso, aprendi um pouco mais sobre o Router e vi que é possível recarregar um componente completamente sem ter que recarregar a página em si, e sim usando algumas configurações e métodos dele.

### Conclusão

Neste curso me apronfundei um pouco mais nos meus conhecimentos de Angular desenvolvendo mais funcionalidades para o projeto desenvolvido no curso anterior.

Implementei formulários reativos, validações nos campos, paginação dos dados, funcionalidade de pesquisa e funcionalidade de favoritar e pude praticar muito meus conhecimentos e aprender muita coisa nova ao decorrer do curso.

Gostei muito de implementar essas novas funcionalidades e o projeto ficou bem mais completo, me sinto muito mais confiante para aplicar todo este conhecimento que adquiri nos meus projetos pessoais e fazer aplicações mais completas no front-end.

Muito animado para continuar me aprofundando no Angular!
