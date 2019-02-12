<html>
    <head>
        <title>TDB</title>
        <script>
            var queryString = window.location.search.slice(1);
            if(queryString){
                qString = queryString.split('q=')[1].split('&')[0];
                alert(qString);
            }
        </script>
    </head>
    <body>
        
    </body>
</html>
