<!DOCTYPE html>
<html lang="en">
<head>
    <!--bootstrap CSS-->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <!--my CSS-->
    <link rel="stylesheet" href="mystyle.css">

    <!--bootstrap JS-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    
    <title>Title</title>

    <style>
        p {
            background-color:antiquewhite;
        }
    </style>

    <script>
        function hello()
        {
            console.log("Hello, world");
        }
    </script>
</head>
<body>
    <h1 style="background-color:blue">This is a heading</h1>
    <p>This is a paragraph. </p>
    <p>Click <a href="http://google.com">here</a> to visit Google.</p>
    <button type="button" class="btn btn-primary">This is a bootstrap button</button>
    <a href="https://getbootstrap.com/" class="btn btn-primary">This is a link that looks like a button.</a>
    
</body>
<button id="changeList" type="button">
    Type 3 things
  </button>
  <script>
  var item1;
var item2;
var item3;
document.getElementById("changeList").onclick = newList;
function newList() {
    item1 = prompt("Enter a new first thing: ");
    item2 = prompt("Enter a new second thing: ");
    item3 = prompt("Enter a new third thing: ");
    updateList();
}
function updateList() {
    document.getElementById("firstThing").innerHTML = item1;
    document.getElementById("secondThing").innerHTML = item2;
    document.getElementById("thirdThing").innerHTML = item3;
}
</script>
</html>
