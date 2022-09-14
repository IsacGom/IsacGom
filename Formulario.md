<html>
    <head>
    </head>


    <body>
        <h1>Preencha o formulário</h1>
        <form action="#" method="get">
            <table>
                <tr>
                <td><label id="lbnome">Nome:</label></td>
                <td><input type="text" size="40" name="nome" value="Digite seu nome"></td>
            </tr>
            <br>
            <input type="radio" name="sexo" value="M">Masculino<br>
            <input type="radio" name="sexo" value="F">Feminino<br>
            <input type="radio" name="sexo" value="N">Não quero informar<br>
            <br>
            <br>
            <p>Escolha as disciplinas</p>
            <input type="checkbox" name="html" value="html">HTML<br>
            <input type="checkbox" name="php" value="php">PHP<br>
            <input type="checkbox" name="bd" value="bd">Banco de dados<br>
            <input type="checkbox" name="math" value="math">Matemática<br>
            <br>
            País:
            <select name="pais">
                
                <option value="Brasil">Brasil</option>
                <option value="Argentina">Argentina</option>
                <option value="Paraguai">Paraguai</option>
                <option value="CoreiaNorte">CoreiaNorte</option>
            </select>
            <input type="submit" value="Enviar">
            <br>
            </table>
        </form>

    </body>
</html>
