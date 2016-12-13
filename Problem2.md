<!doctype html>
  <html>
  <head>
  <meta charset="UTF-8">
  <title>Unit 9 Assignment</title>
  </head>
  <body>
<p id="redBlack"><strong>We</strong> have just started <strong>this</strong> section for the users (<strong>beginner</strong> to intermediate) who <strong>want</strong> to work with <strong>various</strong> JavaScript <strong>problems</strong> and write scripts online to <strong>test</strong> their JavaScript <strong>skill</strong>.</p>

<script>
document.getElementById("redBlack").onmouseover = function() {mouseOver()};
document.getElementById("redBlack").onmouseout = function() {mouseOut()};

function mouseOver()
{
	var x = document.getElementById("redBlack");
    var y = x.getElementsByTagName("strong");
    var i;
    for (i = 0; i < y.length; i++)
    {
        y[i].style.color = "red";
	}
}

function mouseOut()
{
    var x = document.getElementById("redBlack");
    var y = x.getElementsByTagName("strong");
    var i;
    for (i = 0; i < y.length; i++)
    {
        y[i].style.color = "black";
    }
}
</script>
  </body>
  </html>
