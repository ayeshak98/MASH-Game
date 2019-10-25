# MASH-Game
MASH Game for Web Design 1 at Northwest Vista College

<!DOCTYPE html>
<html>

  <!-- HEAD SECTION STARTS -->
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=0.5, maximum-scale=0.5, minimal-ui">
    <title>MASH</title>
    <link href="" rel="stylesheet">
    <link href="" rel="stylesheet">
  </head>
  <!-- HEAD SECTION ENDS -->

  <!-- BODY SECTION STARTS -->
  <body>
    <h1>MASH</h1>
    <p class="description">Fill in the blanks if you wish to know your future.</p>
    <form action="" method="post" id="mash">
      <div id="answers" class="hide">
        <p>Your home is in <span id="answer_1"></span> with a <span id="answer_3"></span> as you are a <span id="answer_2"></span> who owns a <span id="home"></span>.
      </div>
      <div class="bucket">
        <div class="choice-bucket">
          <h4 class="highlight">Where will you live?</h4>
          <input name="answer_1[]" type="text">
          <input name="answer_1[]" type="text">
          <input name="answer_1[]" type="text">
          <input name="answer_1[]" type="text">
        </div>
        <div class="choice-bucket">
          <h4 class="highlight">What will your future profession be?</h4>
          <input name="answer_2[]" type="text">
          <input name="answer_2[]" type="text">
          <input name="answer_2[]" type="text">
          <input name="answer_2[]" type="text">
        </div>
        <div class="choice-bucket">
          <h4 class="highlight">What pet will you own?</h4>
          <input name="answer_3[]" type"text">
          <input name="answer_3[]" type"text">
          <input name="answer_3[]" type"text">
          <input name="answer_3[]" type"text">
        </div>
      </div>
      <button type="submit" class="button-submit">Tell my fortune</button>
    </form>  
    <script src=""></script>
  </body>
  <!-- BODY SECTION ENDS -->

</html>
