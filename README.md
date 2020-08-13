<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 30%;
  height: 150px;
  padding: 5px;
  margin-left: 5px;
  margin-right: 5px; 
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2 style="text-align:center">Our Menu</h2>
<div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2 style="text-align:right">Chicken</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2 style="text-align:right">Beef</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#ccc;">
    <h2 style="text-align:right">Sushi</h2>
    <p>Some text..</p>
  </div>
</div>
</body>
</html>