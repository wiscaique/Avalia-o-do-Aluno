# Avalia-o-do-Aluno
Estruturada de Programação 80
<!DOCTYPE html>
<html>
  <meta charset="UTF-8">
  <title>Programa 80</title>
  <body>
    <h1>JavaScript</h1>
    <h2>Exercicio 03</h2>
    <h3>Estrutura Sequencial</h3>
    <p>RA</p>
    <p id="ra"></p>
    <p>Nome</p>
    <p id="nome"></p>
 <p>Notas</p>
    <p id="notas"></p>
    <p>Média</p>
    <p id="media"></p>
    <script>
      // programa ES080
      // declarar e inicializar as variáveis
        var RA = 0; var nomeAluno = "";
        var nota1 = 0.0; var nota2 = 0.0;
        var media = 0.0; var strNotas = "";
      //// ler dados
        RA = prompt("Informar o Valor de a:", "RA");
        nomeAluno = prompt("Informar o Nome:", "Nome de Aluno");
        nota1 = prompt("Informar a Nota1:", 0.0);
        nota2 = prompt("Informar a Nota2:", 0.0);
      // exibir o RA
        alert("RA: " + RA);
        document.getElementById('ra').innerHTML = RA;
      // exibir o nome
        alert("Nome do Aluno: " + nomeAluno);
        document.getElementById('nome').innerHTML = nomeAluno;
        strNotas = "Nota1 = " + nota1 + ", Nota2 = " + nota2
      // exibir as notas
        alert("Notas: " + strNotas);
        document.getElementById('notas').innerHTML = strNotas;
      // converter as string numéricas para números
        nota1 = parseFloat(nota1);
        nota2 = parseFloat(nota2);
      // calcular e exibir a média
        media = (nota1 + nota2) / 2.0;
        alert("media = " + media);
        document.getElementById('media').innerHTML = media;
    </script>
  </body>
</html>
