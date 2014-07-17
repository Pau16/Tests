Tests
=====
<html lang="en">
    <head>
        <title>Jose test2 page</title>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" type="text/css" href="stylesheet.css"/>
        <!--<link href="//maxcdn.bootstrapcdn.com/bootswatch/3.2.0/cosmo/bootstrap.min.css" rel="stylesheet"> -->
    </head>
    <body>
        
        <div class="form">
            <form action="demo_form.asp" method="get">
                <div>
                    <label for="inputemail" class="section">First name: </label>
                    <input type="text" id="fname" autofocus="" >
                </div>
                <div>
                    <label for="inputemail" class="section">Last name: </label>
                    <input type="text" id="ltname">
                </div>
                <div>
                    <div class="inline"><label for="inputsex" class="section">Sex:</label></div>
                    <div class="inline">
                        <input type="radio" id="mysex" value="Man"> Man
                        <input type="radio" id="mysex" value="Woman"> Woman
                    </div>
                                        
                </div>
                <div>
                    <label for="inputemail" class="section">E-mail adress: </label>
                    <input type="email" id="e-mail" pattern="[a-zA-Z0-9_]+([.][a-zA-Z0-9_]+)*@[a-zA-Z0-9_]+([.][a-zA-Z0-9_]+)*[.][a-zA-Z]{1,5}">                
                </div>
                <div>
                    <label for="inputsubject" class="section">Subject: </label>
                    <input type="text" id="subject">
                </div>
                <div>
                    <label for="inputemail" class="section">Body:</label>
                    <textarea id="body"></textarea>
                </div>
                <div>
                    <button>Contact us</button>
                </div>
            </form>
        </div>
    </body>
</html>
