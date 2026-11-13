Questões 1 a 7

Questão 1)

a) A linha 2 guarda que o valor do id que está sendo usado é 3 quando usa essa url, o window.location.search contém detalhes.html, get("id") devolve id=3, sendo o valor 3 para o id e o tipo é um dado numérico, o Number( ) foi usado porque ele vai pegar dessa url que é dada somente o valor numérico dela, que vai ser o valor o id para colocar na constante id, porque o valor de id tem que ser um número.

b) O método find recebe o id que foi pego na linha de cima e define ele como o id o item e define qual item tem aquele id, ele devolve o item que foi encontrado para herói, que seria qual heroi está usando a url, descobrindo qual foi pelo id, quando não encontra devolve um alerta escrito Item não encontrado.

c) Ao abrir a pagina iria mostrar  `${heroi.nome} - Galeria de Heróis` e   `<h3>${heroi.nome}</h3><p>${heroi.descricao}</p>`, porque mesmo existindo o heroi se não tivesse o Number() a parte de encontrar o heroi não iria funcionar porque iria procurar o id pela url e não pelo valor da id, ai não iria encontrar, porque o valor e tipo de id é numerico e o valor dele tem que ser lido em numeros, portanto o find n iria achar o heroi que tem um id como url e não numero.

d) O papel do return é encaminhar a mensagem na tela e fechar/sair do if sem ocorrer erros, se ele fosse apagado e o id do heroi fosse 99 e não existisse esse heroi, para entrar no if, ai a mensagem apareceria e travaria a pagina, nao deixando as outras mensagens aparecerem nela porque ficaria pra sempre dentro do if.

Questão 2)

a) Essa função é do tipo que pega o valor de sel e define o $ como esse valor, ela recebe o valor de sel lido do documento, quando encontra devolve oq está definido das linhas das linhas 14 a 20 e a pagina de detalhes e se não encontrar devolve a pagina da obra só que sem os detalhe dela e a parte das linhas 14 a 20 também não aparecem. 

b) Eles permitem que o mesmo arquivo sirva pra duas linhas por causa do $ e da primeira linha, porque assim que entra no if ele usa a mesma função da primeira linha que pega as informações de um documento, então ele só pega informações diferentes da mesma pagina. Porque só entra no if se achar a informação no documento, como $ é uma função ela pode ser utilizada.

c) Elas filtram o catalogo por mangás e mostram somente os mangás que tem na pagina. Quando abre só index.html ai mostra todo o catálogo disponível. 

d) ele iria para a função render detalhes mesmo sem ter nenhuma certeza que existe os detalhes ou não, então a funcao render detalhes iria rodar ate a linha do alvo onde iria trava e mostrar a mensagem de erro se caso não existir detalhe.

Questão 3)

a) O objetivo essas linhas é mostrar os cards e os slides com os filmes. São criados 12 slides e ficam 2 cards em cada um. 

b) matchMedia significa que as fotos que forem adicionadas todas tem que seguir o mesmo paramêtro do matchMedia para ficar todas com o mesmo tamanho.

c) Se o númeo 1 for excluido o forech não vai permitir que entre na função e não vai aparecer nenhum livro, porque vai sair da condição do if e vai travar, o erro vai aparecer na linha 7, porque ai o if vai fzr que cada id de filme menos um dividido pela quantidade tem q da resto 0, ai como a quantidade vai ser 11, vai dar erro.

d) 6    dados.filmes.forEach(f =>
   7    f.id) { 
        ...
   10   item.classList.add("active");
        ...}

Questão 4)

a) O trim separa a pagina de catálogos onde tem virgula e coloca cada um separado em uma string do array, entao devide id de titulo e de tipo, o toLowerCase() faz a funcção rodar e pegar todos os livros até o último. O !lista.length servia pra mostrar todos os filmes, até acabar a lista defilmes, quando não tier mais acaba. 

b) Essas linhas server para poder mostrar todos os livros e poder filtrar eles. O papel de includes, de && 
|| e dos parênteses é garantir que todas as condições são verdadeiras ou falsas e onde e quando o codigo deve entrar ou não, nos if, etc. RenderLivros é executada quando encontra os livros e as informações nas linhas 17 e 18.

c) (1) 3
   (2) 1,4
   (3) 4,6

d) O resultado mudaria se fosse procurar por tipo, porque ai ele não acharia porqu não entraria n if, ja q tem q ser um ou outro, a nao funcionaria.

Questão 5)

a) O tipo do valor é um dado númerico e e o tipo de f.id é seria númerico também. Ela continua encontrando o filme porque memso se o id fosse um url ele pegaria somente o numero que esta nela, q seria o id, ai viraria uma comaração para ver se o filme é igual ao id dele, ai a constatnte filme n funcionaria no resto do codigo. 

b) o valor de filme seria 99, a linha que seria o erro é na linha 3, apareceria item não encontrado como erro, e as lihas seguintes não seriam executadas.

c) 

Questão 6)

a) O filter serve para filtrar e mostrar apenas os herois que estão nos destaques, o operador ternário serve para verifica se a condição é verdadeira ou falsa e realizar a ação dependendo da resposta, foi usado o indice i para poder percorrer todo os itens e verificar todas as informações de cada um.

b)

c)

d)

Questão 7)

a) 

b)

c)

d)
