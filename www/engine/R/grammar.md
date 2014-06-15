<!-- DEFAULT HEADER- DO NOT TOUCH-->

<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="data.table, an R package for faster subset, grouping, assign, ordered joins and list columns in short and flexible syntax, for faster development.">
<meta name="keywords" content="R, data.table, dplyr, benchmark, big-data">
<meta name="author" content="Matt Dowle, Arun Srinivasan, other authors and contributors">
<title>data.table &middot; Grammar</title>
<link href="../css/bootstrap.css" rel="stylesheet" media="screen">
</head>

<body>

<!-- Master nav - DO NOT TOUCH-->
<header>
<div class="navbar-default">
<button class="navbar-toggle" type="button" data-toggle="collapse" data-target=".bs-navbar-collapse">
<span class="sr-only">Toggle navigation</span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
</button>
<nav class="collapse navbar-collapse bs-navbar-collapse" role="navigation">
<ul class="nav navbar-nav">
<li><a href="../"><span class="glyphicon glyphicon-home"></span> data.table</a>
<li class="dropdown">
<a class="dropdown-toggle" data-toggle="dropdown" href="#" id="docs"><span class="glyphicon glyphicon-pencil"></span> Getting started <span class="caret"></span></a>
<ul class="dropdown-menu" aria-labelledby="docs">
<li><a href="../about"><span class="glyphicon glyphicon-bookmark"></span> data.table project</a></li>
<li><a href="../intro"><span class="glyphicon glyphicon-file"></span> Quick Introduction</a></li>
<li><a href="../faq"><span class="glyphicon glyphicon-question-sign"></span> FAQs</a></li>
</ul>
</li>
<li><a href="../benchmarks/"><span class="glyphicon glyphicon-wrench"></span> Benchmarks</a></li>
<li class="active"><a href="./"><span class="glyphicon glyphicon-book"></span> Grammar</a></li>
<li><a href="../new/"><span class="glyphicon glyphicon-cog"></span> What's new</a></li>
</ul>
<ul class="nav navbar-nav navbar-right">
<li><a href="../notes/">Release Notes</a></li>
</ul>
</nav>
</div>
</header>

<!-- ACTUAL TEXT STARTS HERE -->
.div{.container .bs-docs-container}
.div{.row}
.div{.col-md-9 __main}

<!-- Grammar -->
.div{.bs-docs-section}

<!-- Introduction -->
# Introduction {#introduction .page-header}

There are quite a few philosophical differences towards data manipulation between %>% dplyr !!{.text-info} %>% and %>% data.table !!{.text-info} %>%. Most of these differences are *by design* and are in alignment with the priorities with which these packages are developed. .p{.lead}

</body>