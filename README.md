# bootstrap-left-slide-menu
Simple Bootstrap (Left) Slide Menu

USAGE:
                <head>
                <meta charset="utf-8" />
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>TITLE</title>
                
                <!-- Latest compiled and minified CSS -->
                <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
            
                <!-- Optional theme -->
                <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap-theme.min.css">
                
                <!-- bootstrap-left-slide-menu css -->
                <link rel="stylesheet" href="bootstrap-left-slide-menu.css">
                </head>
            <body>
                <div id="wrapper" class="">
                    <div class="overlay" style="display: none;"></div>
                    <nav class="navbar navbar-inverse navbar-fixed-top" id="sidebar-wrapper" role="navigation">
                        <ul class="nav sidebar-nav">
                            <li class="sidebar-brand"> <a href="#"> BLESM </a> </li>
                            <li> <a href="#"><i class="fa fa-fw fa-home"></i> Home</a> </li>
                            <li> <a href="#"><i class="fa fa-fw fa-folder"></i> Page one</a> </li>
                            <li> <a href="#"><i class="fa fa-fw fa-file-o"></i> Second page</a> </li>
                            <li> <a href="#"><i class="fa fa-fw fa-cog"></i> Third page</a> </li>
                        </ul>
                    </nav>
                    <div id="page-content-wrapper">
                        <button type="button" class="hamburger animated fadeInLeft is-closed" data-toggle="offcanvas">
                            <span class="hamb-top"></span>
                            <span class="hamb-middle"></span>
                            <span class="hamb-bottom"></span>
                        </button>
                        <div class="container">
                            ...YOUR CONTENT...
                        </div>
                    </div>
                </div>
                <!-- JQUERY -->
                <script src="//code.jquery.com/jquery-1.11.3.min.js"></script>
                
                <!-- Latest compiled and minified JavaScript -->
                <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
                
                <!-- bootstrap-left-slide-menu js -->
                <link rel="stylesheet" href="bootstrap-left-slide-menu.js">
            </body>
