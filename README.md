<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>História de Neymar Jr</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Neymar da Silva Santos Júnior</h1>
        <p>A trajetória de um dos maiores camisas 10 do futebol brasileiro.</p>
    </header>

    <main class="container">
        <section class="card">
            <h2>O Início e o Santos FC</h2>
            <p>Nascido em Mogi das Cruzes em 1992, Neymar despertou a atenção do mundo muito jovem. Na Vila Belmiro, conquistou a Copa do Brasil e a Copa Libertadores da América, encantando a todos com seus dribles e irreverência.</p>
        <section class="card">
            <h2>A Conquista da Europa: Barcelona</h2>
          
            <p>Em 2013, transferiu-se para o Barcelona. Ao lado de Messi e Suárez, formou o lendário trio MSN, conquistando a Champions League e o Mundial de Clubes em 2015.</p>
        </section>

        <section class="card">
            <h2>Paris Saint-Germain e Novos Desafios</h2>
            <p>Tornou-se a transferência mais cara da história do futebol ao ir para o PSG em 2017. Na França, empilhou títulos nacionais e levou o clube à sua primeira final de Champions League.</p>
      
        </section>
      <section class="card">
            <h2>Sua passagen na arabia pelo Hal-Hilal</h2>
            <p>A passagem de Neymar pelo Al-Hilal foi curta e marcada por graves problemas físicos. Em 17 meses no clube, o brasileiro disputou apenas sete jogos, marcou um gol e encerrou sua trajetória antecipadamente para retornar ao Santos no início de 2025. .</p>
        </section>
         <section class="card">
           
            <h2>Seleção Brasileira</h2>
            <p>Protagonista absoluto da Amarelinha, liderou o Brasil na conquista do inédito Ouro Olímpico no Rio em 2016 e superou marcas históricas de gols oficiais pela seleção.</p>
    <footer>
       <section class="card">
         <footer>
            <h2>A volta ao Santos FC</h2>
            <p>Após retornar ao Santos em 2025, Neymar rescindiu com o Al-Hilal e assinou com o clube que o revelou. Em meio a desafios físicos, ele atingiu a marca de 156 gols, tornando-se o décimo maior artilheiro da história santista. Disputou a Copa do Mundo de 2026, onde o Brasil foi eliminado nas oitavas de final. Atualmente, seu contrato com o Peixe se encerra em dezembro de 2026, e o jogador avalia seu futuro.</p>
         
           
        <p>Desenvolvido pelo aluno PAULO R.</p>
    

</body>
</html>
</footer>
/* Configurações Globais */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f4f7f6;
    color: #333;
    line-height: 1.6;
}

/* Cabeçalho */
header {
    background: linear-gradient(135deg, #009c3b, #ffdf00);
    color: #fff;
    text-align: center;
    padding: 40px 20px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
}

header p {
    font-size: 1.1rem;
    font-weight: 500;
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
}

/* Conteúdo Principal */
.container {
    max-width: 800px;
    margin: 30px auto;
    padding: 0 20px;
}

.card {
    background: #fff;
    padding: 25px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    border-left: 5px solid #002776;
    transition: transform 0.2s;
}

.card:hover {
    transform: translateY(-3px);
}

.card h2 {
    color: #002776;
    margin-bottom: 12px;
    font-size: 1.4rem;
}

/* Rodapé */
footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: #fff;
    font-size: 0.9rem;
    margin-top: 40px;
}
