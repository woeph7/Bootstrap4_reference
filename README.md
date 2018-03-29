<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">
  <title>Bootstrap4 reference</title>
</head>
<body>
  <header>
    <h1 class="display-3 text-center my-4">Basic Typography</h1>
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <div class="dropdown">
              <button class="btn btn-primary btn-block dropdown-toggle" type="button" data-toggle="dropdown">
                  2: Utilities
              </button>
              <div class="dropdown-menu">
                  <a class="dropdown-item" href="2_2_basic_typography.html">2.2 Basic Typography</a>
                  <a class="dropdown-item" href="2_3_text_alignment_display.html">2.3 Text Alignment & Display</a>
                  <a class="dropdown-item" href="2_4_floats_position.html">2.4 Floats & Position</a>
                  <a class="dropdown-item" href="2_5_colors_background.html">2.5: Colors & Background</a>
                  <a class="dropdown-item" href="2_6_spacing.html">2.6 Spacing</a>
                  <a class="dropdown-item" href="2_7_sizing.html">2.7 Sizing</a>
                  <a class="dropdown-item" href="2_8_breakpoints.html">2.8 Breakpoints</a>
              </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="dropdown">
              <button class="btn btn-success btn-block dropdown-toggle" type="button" data-toggle="dropdown">
                  3: CSS Components
              </button>
              <div class="dropdown-menu">
                  <a class="dropdown-item" href="3_2_buttons.html">3.2 Buttons</a>
                  <a class="dropdown-item" href="3_3_navbar.html">3.3 Navbar</a>
                  <a class="dropdown-item" href="3_4_list_groups_badges.html">3.4 List Groups & Badges</a>
                  <a class="dropdown-item" href="3_5_forms.html">3.5 Forms</a>
                  <a class="dropdown-item" href="3_6_input_groups.html">3.6 Input Groups</a>
                  <a class="dropdown-item" href="3_7_alerts_progress.html">3.7 Alerts & Progress</a>
                  <a class="dropdown-item" href="3_8_tables_pagination.html">3.8 Tables & Pagination</a>
                  <a class="dropdown-item" href="3_9_cards.html">3.9 Cards</a>
                  <a class="dropdown-item" href="3_10_media_object.html">3.10 Media Objects</a>
              </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="dropdown">
              <button class="btn btn-warning btn-block dropdown-toggle" type="button" data-toggle="dropdown">
                  4: Grid & Flexbox
              </button>
              <div class="dropdown-menu">
                  <a class="dropdown-item" href="4_2_grid_system.html">4.2 Grid System</a>
                  <a class="dropdown-item" href="4_3_grid_alignment.html">4.3 Grid Alignment</a>
                  <a class="dropdown-item" href="4_4_flexbox.html">4.4 Flexbox</a>
                  <a class="dropdown-item" href="4_5_auto_margins_wrapping_order.html">4.5 Auto Margins & Wrap</a>
              </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="dropdown">
              <button class="btn btn-danger btn-block dropdown-toggle" type="button" data-toggle="dropdown">
                  5: JavaScript Widgets
              </button>
              <div class="dropdown-menu">
                  <a class="dropdown-item" href="5_2_carousel.html">5.2 Carousel</a>
                  <a class="dropdown-item" href="5_3_collapse.html">5.3 Collapse</a>
                  <a class="dropdown-item" href="5_4_tooltips.html">5.4 Tooltips</a>
                  <a class="dropdown-item" href="5_5_popovers.html">5.5 Popovers</a>
                  <a class="dropdown-item" href="5_6_modals.html">5.6 Modals</a>
              </div>
          </div>
        </div>
      </div>
    </div>
    <hr>
  </header>

  <div class="container">
    <!--########################START HERE#########################-->

    <!-- HEADINGS -->
    <h1>Heading One <small class="text-muted">Something</small></h1>
    <h2>Heading Two</h2>
    <h3 class="h1">Heading Three</h3>
    <h4>Heading Four</h4>
    <h5>Heading Five</h5>
    <h6 class="h2">Heading Six</h6>

    <!-- DISPLAY CLASSES -->
    <h1 class="display-1">My Heading</h1>
    <h1 class="display-2">My Heading</h1>
    <h1 class="display-3">My Heading</h1>
    <h1 class="display-4">My Heading</h1>

    <!-- PARAGRAPHS -->
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam dolore repellendus veniam consequatur vero numquam voluptatem quam ab expedita eum, ipsam? Necessitatibus dicta quaerat, vitae dolorum, dolor autem reiciendis sapiente.</p>

    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam dolore repellendus veniam consequatur vero numquam voluptatem quam ab expedita eum, ipsam? Necessitatibus dicta quaerat, vitae dolorum, dolor autem reiciendis sapiente.</p>

    <!-- STYLE CLASSES -->
    <p class="font-weight-bold">Bold Text</p>
    <p class="font-weight-normal">Normal Text</p>
    <p class="font-italic">Italic Text</p>

    <!-- TEXT TRANSFORMS -->
    <p class="text-lowercase">HELLO WORLD</p>
    <p class="text-uppercase">hello world</p>
    <p class="text-capitalize">hello world</p>

    <!-- BLOCKQUOTES -->
    <blockquote class="blockquote">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nobis, rerum!</p>
    </blockquote>

    <blockquote class="blockquote blockquote-reverse">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nobis, rerum!</p>
    </blockquote>

    <!-- LISTS -->
    <ul class="list-unstyled">
      <li>Lorem ipsum dolor sit amet.</li>
      <li>Lorem ipsum dolor sit amet.</li>
      <li>Lorem ipsum dolor sit amet.</li>
      <li>Lorem ipsum dolor sit amet.</li>
    </ul>

    <ul class="list-inline">
      <li class="list-inline-item">Lorem ipsum</li>
      <li class="list-inline-item">Lorem ipsum </li>
      <li class="list-inline-item">Lorem ipsum </li>
    </ul>
  </div>

  <div style="margin-top:500px;"></div>

  <script src="https://code.jquery.com/jquery-3.2.1.min.js"
    integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4="
    crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>
</body>
</html>
