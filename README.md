<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Museu do Ceará - Terra do Sol</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background: linear-gradient(90deg,#ff8c00,#c7b100);
color:#333;
}

/* HEADER */

header{
background:#222;
color:white;
text-align:center;
padding:20px;
}

header img{
width:120px;
margin:10px 0;
}

nav{
margin-top:10px;
}

nav a{
color:white;
text-decoration:none;
margin:0 15px;
font-weight:bold;
}

nav a:hover{
color:orange;
}

/* BANNER */

.banner{
text-align:center;
padding:50px 20px;
background:white;
}

.banner h2{
font-size:32px;
margin-bottom:20px;
}

.banner p{
max-width:900px;
margin:auto;
line-height:1.6;
}

.banner button{
margin-top:20px;
padding:12px 25px;
border:none;
background:orange;
color:white;
font-size:16px;
cursor:pointer;
border-radius:5px;
}

.banner button:hover{
background:#ff6a00;
}

/* DESTINOS */

#destinos{
padding:50px 20px;
text-align:center;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:30px;
margin-top:30px;
}

.card{
background:white;
width:350px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,0.2);
overflow:hidden;
}

.card img{
width:100%;
height:200px;
object-fit:cover;
}

.card h3{
padding:15px;
color:#ff6600;
}

.card p{
padding:0 15px 20px;
font-size:14px;
line-height:1.5;
}

/* GALERIA */

#galeria{
background:white;
padding:50px 20px;
text-align:center;
}

.galeria{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
margin-top:30px;
}

.galeria img{
width:100%;
border-radius:10px;
transition:0.3s;
}

.galeria img:hover{
transform:scale(1.05);
}

/* TEXTO HISTÓRICO */

.historia{
max-width:900px;
margin:40px auto;
line-height:1.6;
}

/* CONTATO */

#contato{
padding:50px 20px;
text-align:center;
}

form{
max-width:500px;
margin:auto;
display:flex;
flex-direction:column;
gap:15px;
}

input,textarea{
padding:10px;
border-radius:5px;
border:1px solid #ccc;
}

button{
background:#ff6600;
color:white;
border:none;
padding:12px;
cursor:pointer;
border-radius:5px;
}

button:hover{
background:#e65c00;
}

/* FOOTER */

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>
</head>

<body>

<header>

<h1>🌴 MUSEU DO CEARÁ</h1>

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Logo_arquitet%C3%B4nica_do_Museu_do_Cear%C3%A1.png/250px-Logo_arquitet%C3%B4nica_do_Museu_do_Cear%C3%A1.png">

<nav>
<a href="#">Início</a>
<a href="#destinos">Destinos</a>
<a href="#galeria">Galeria</a>
<a href="#contato">Contato</a>
</nav>

</header>

<section class="banner">

<h2>Descubra a História do Ceará</h2>

<p>
A história do Ceará iniciou-se com povos indígenas Tupis e Cariris, passando por uma difícil colonização portuguesa no século XVII, marcada pela pecuária e resistência nativa. Inicialmente ligado a Pernambuco, o Ceará emancipou-se em 1799, tornando-se uma capitania independente, com forte economia baseada no charque e no algodão. 
Principais Marcos Históricos:
Colonização e Resistência: O território foi inicialmente ignorado pelos portugueses, sendo alvo de tentativas de ocupação no século XVII, incluindo o forte de Pero Coelho de Sousa (1603) e a chegada de Martim Soares Moreno, considerado o "fundador" do Ceará. Os povos nativos (Cariris e Tremembés) resistiram bravamente à ocupação.
Influência Holandesa: No século XVII, o Ceará foi cenário de conflitos entre portugueses e holandeses, que também ocuparam a região.
Pecuária e "Civilização do Couro": A ocupação do interior cearense ocorreu principalmente através da pecuária extensiva, que se espalhou pelos sertões, criando uma sociedade baseada no latifúndio e na produção de carne seca.
Emancipação (1799): O Ceará separou-se da Capitania de Pernambuco em 17 de janeiro de 1799, obtendo autonomia administrativa.
Independência do Brasil: O Ceará teve papel atuante na consolidação da Independência no Norte do Brasil, com destaque para a atuação de figuras como Tristão Gonçalves e a luta contra o comandante português Fidié.
Ciclos Econômicos: Após a pecuária, o estado viveu ciclos econômicos baseados no algodão e, posteriormente, na produção de cera de carnaúba e atividades de comércio.
Secas e Migração: A história cearense é fortemente marcada pelas secas cíclicas, que moldaram a paisagem, a economia e a migração de sertanejos para a capital, Fortaleza, ou para a Amazônia, como no Ciclo da Borracha.
</p>

<button>Conheça o Ceará</button>

</section>

<section id="destinos">

<h2>Lugares Históricos</h2>

<div class="cards">

<div class="card">

<img src="https://jcce.com.br/wp-content/uploads/2020/04/pra%C3%A7a-do-ferreira-2-1.jpg">

<h3>Litoral do Ceará</h3>

<p>
O litoral do Ceará foi fundamental para a formação histórica do estado.
A colonização portuguesa começou no século XVII com a construção de
fortificações e vilas. A pesca, o comércio e o turismo transformaram
a região em uma das mais importantes do estado.
</p>

</div>

<div class="card">

<img src="https://i.pinimg.com/originals/f6/f4/7e/f6f47ee17339f107badd28ebfe589ae1.png">

<h3>Beira-Mar de Fortaleza</h3>

<p>
A Avenida Beira-Mar começou a ser construída em 1961 e transformou
uma antiga área de pescadores em um dos principais cartões-postais
de Fortaleza. Hoje é um dos pontos turísticos mais visitados do Ceará.
</p>

</div>

</div>

</section>

<section id="galeria">

<h2>Fotos Antigas</h2>

<div class="galeria">

<img src="https://i.pinimg.com/736x/b3/d8/6d/b3d86d929f2def9fccffc874d1175c3c.jpg">

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjPMnIvbATjb-DcdpKhtuXJ7admqiTd01CeqlRYYcBHp8N31HTWeusNEd5rSN8aYSEynSzGF5lvh-9LSiVniJIXQmfe2kJrklWXfjygJW3qB1c5vgqwx3TWY2laJV6i7CZH_59jwBXNUKI/w640-h418/001.jpg">

<img src="https://www.researchgate.net/publication/345816819/figure/fig7/AS:957504934641668@1605298374782/Figura-7-Avenida-Beira-Mar-na-decada-de-1970.png">

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjfmE8dsb0F7yYAgkRT6TflKWOnb30k6aeeoRSYNi13RWZW6XO3FduSubWa2ljhaGttQPR5S6skm3eTkIhVWCva0UrUfG4UDxstjmHIdkUoqDP6ZEox5f-h6hXoFiajtSIYEgvfgqiOdlY/s1600/Praia+Di%25C3%25A1rios+final+anos+60.jpg">

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhhxpBtd_RPirXc16sMHpl1JG6pCbV94azdM2cbvT6hG5EsI42VUbCvdvRRgxGNLgP8ucZj7S96qpVOnr0qDSAgNeKeHTY6ecU-d50a4p2ZVtLhjHc_rtbEXtdjg3RuoN2Xfr_jbpRzvn0/s1600/00.jpg">

</div>

<div class="historia">

<p>
O Museu do Ceará atual tem suas coleções originadas no primeiro museu do Ceará, pertencente ao médico Joaquim Antônio Alves, que, em 1873, organizou uma coleção de objetos e fragmentos da natureza. Essa coleção compôs o Museu Provincial, que funcionou entre 1875 e 1885 como uma das dependência do Gabinete Cearense de Leitura. A partir de 1894, Francisco Dias da Rocha formou uma coleção para o Museu Rocha, que funcionou até 1950.

O Museu Histórico do Ceará só foi criado em 1932, pelo então governador Roberto Carlos Vasco Carneiro de Mendonça. Foi criado conjuntamente com o Arquivo Público do Estado. Em 1951, o Arquivo Público foi transferido para o Palácio Senador Alencar, ficando o museu no edifício da Praça da Sé até 1957, passando para a tutela do Instituto do Ceará. Em 1955, houve a incorporação de novas peças ao acervo, as coleções indígenas do antigo Museu do Instituto e do Museu Rocha, e este último passou à denominação de Museu Histórico e Antropológico do Ceará. 

Em 1967, o museu voltou para a tutela do estado vinculado à Secretaria de Cultura do Estado do Ceará (Secult). Em 1973, o Palacete Senador Alencar foi tombado como Monumento Nacional pelo IPHAN. Em 1990, na gestão do governador Tasso Jereissati, foi restaurado e passou a ser sede do atual Museu do Ceará. Foi reinaugurado em 25 de março de 1998, na comemoração dos 144 anos da abolição da escravatura no Ceará. O majestoso edifício foi, então, adaptado para o funcionamento do museu e, desde 1998, abriga exposições de longa e curta duração. Em 2001, foi criada a Sala Paulo Freire, que sedia palestras, cursos e seminários. No ano seguinte, foi aberto o Memorial Frei Tito, uma homenagem ao religioso que viveu durante o regime militar instaurado no país em 1964. O Museu do Ceará possui, ainda, Reserva Técnica, sala do Núcleo Educativo, sala da administração e biblioteca. Tem ainda em sua coleção um acervo plumário que também foi tombado pelo IPHAN. 
</p>

<h3>Fortaleza Atual</h3>
<a>A formação de Fortaleza remonta à presença indígena e ao contato com colonizadores europeus no início do século XVI. A ocupação efetiva ocorreu no século XVII, com a construção de fortificações. Em 1649, os holandeses ergueram o Forte Schoonenborch, retomado pelos portugueses em 1654 e rebatizado como Fortaleza de Nossa Senhora da Assunção, origem do nome da cidade.

No final do século XVII e ao longo do XVIII, Fortaleza consolidou-se como núcleo político. Em 13 de abril de 1726, foi elevada à categoria de vila, data que marca o aniversário da cidade. Em 1799, após a separação do Ceará da Capitania de Pernambuco, firmou-se como capital, sendo elevada à categoria de cidade em 1823.

A partir do século XX, vivenciou rápido crescimento demográfico e urbanístico, impulsionado por reformas de infraestrutura, industrialização e fortalecimento do turismo. As décadas de 1950 e 1960 marcaram expressiva expansão econômica e, a partir dos anos 1970, a instalação de polos industriais consolidou sua posição como centro econômico regional.

Com a redemocratização, a cidade passou por transformações políticas e, nas décadas seguintes, consolidou-se como uma metrópole de referência no Nordeste, com atuação destacada nos setores administrativo, cultural, turístico e industrial.

Fortaleza em Números
Fortaleza está situada no litoral Atlântico, com 34 km de praias. O município possui área de 312,353 km² e população de 2.428.678 habitantes, de acordo com Censo de 2022, sendo a maior cidade do Nordeste em número de habitantes e a quarta do Brasil.

Sua economia é alicerçada nos setores de serviços e comércio, o que a coloca como a cidade de maior Produto Interno Bruto (PIB) da região Nordeste, com aproximadamente R$ 73 bilhões. No turismo, destaca-se como um dos destinos mais procurados do país.

Desde 1997, a gestão administrativa da Prefeitura de Fortaleza está descentralizada em Regionais, que atualmente abrangem 121 bairros.

A localização estratégica confere à cidade papel de destaque como um dos principais centros de conexões do Brasil com o mundo. Fortaleza abriga hubs tecnológicos, marítimos e aéreos. A capital também possui voos internacionais diretos e diários para destinos como Lisboa, Paris, Miami e Buenos Aires.</a>

<img src="https://t3.ftcdn.net/jpg/01/29/24/58/360_F_129245850_v7jtAAJHtYvhh7tNd9pxVoDMuoNyt3Se.jpg" alt="">

<a href="https://pt.wikipedia.org/wiki/Museu_do_Cear%C3%A1" target="_blank">
Entre Conheça Nossa História
</a>

</div>

</section>

<section id="contato">

<h2>Contato</h2>

<form>

<input type="text" placeholder="Seu nome" required>

<input type="email" placeholder="Seu email" required>

<textarea placeholder="Digite sua mensagem" required></textarea>

<button type="submit">Enviar Mensagem</button>

</form>

</section>

<footer>

<p>© 2026 CEARÁ MUSEU DO CEARÁ</p>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Contador de Visitantes</title>
</head>
<body>

<h2>Visitantes:</h2>
<p id="contador">0</p>

<script>
let visitas = localStorage.getItem("visitas");

if (visitas === null) {
  visitas = 1;
} else {
  visitas = parseInt(visitas) + 1;
}

localStorage.setItem("visitas", visitas);
document.getElementById("contador").innerText = visitas;
</script>

</body>
</html>
<style>
body{
background: linear-gradient(90deg, orange, rgb(107, 107, 18));
}
</style>
