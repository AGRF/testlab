Welcome to the Galaxy {{ site_name }} {{ lab_name }}! 



<!-- example grid system with links, 

note that many of the sections here are not yet actual sections as yml files, just here for examples

to link to a section, see what it is called in the yml file (it's id, on the first line)
then add Section, so data becomes dataSection

-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bootstrap Grid</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body {
      background-color: white;
    }

    .grid-item {
      background-color: #cce5ff;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      font-size: 1em;
      font-weight: bold;
      transition: 0.3s;
      height: 100%;
      width: 100%;
    }

    .grid-item a {
      text-decoration: none;
      color: #0056b3;
      display: block;
      height: 100%;
    }

    .grid-item:hover {
      background-color: #99c2ff;
    }
  </style>
</head>
<body>

<div class="container mt-3">
  <div class="row g-2">
    <!-- Row 1 -->
    <div class="col-md-4 d-flex">
      <div class="grid-item flex-fill"><a href="#importSetion">Import Data</a></div>
    </div>
    <div class="col-md-4 d-flex">
      <div class="grid-item flex-fill"><a href="#dataSection">Quality Control</a></div>
    </div>
    <div class="col-md-4 d-flex">
      <div class="grid-item flex-fill"><a href="microbialSection">Microbial Profiling</a></div>
    </div>

    <!-- Row 2 -->
    <div class="col-md-4 d-flex">
      <div class="grid-item flex-fill"><a href="#learnGalaxy">Learn Galaxy</a></div>
    </div>
    <div class="col-md-4 d-flex">
      <div class="grid-item flex-fill"><a href="#galaxyHelp">Galaxy Help</a></div>
    </div>
    <div class="col-md-4 d-flex">
      <div class="grid-item flex-fill"><a href="#contactAgrf">Contact AGRF</a></div>
    </div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

