<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
        
    <script>
       let media;

    media = prompt ("Digite a média", "aqui a média");

       if (media === 5){
           document.write ("<p style = 'color: #F00' > Passou raspando... </p>")
       } else if (media > 5 && media <8) {
           document.write ("<p style = 'color: #F00' > Bom rapaz! </p>")
       } else if (media < 5) {
           document.write ("<p style = 'color: #F00' > Reprovado!!! </p>")
       } else if (media > 8) {
           document.write ("<p style = 'color: #F00' > Você é o cara!! </p>")
       }


    </script>
    
</body>
</html>
