# web
web homework1 repo
<!doctype html>
<html lang="en">

  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1,
      shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous">
    <script src="myscripts.js"></script>
    <style>
    th,
    td {
      padding: 10px;
    }
    body{
      margin: 0;
      padding: 0;
      height: 100%;
    }
  </style>
    <title>Hello, world!</title>
  </head>

  <body>
    <div class="container-fluid" style="height: 100vh; background: palevioletred" >
      <div class="row">
        <a class="col-2" href="https://sergeydus.github.io/web-hw1/hw1.html" style="height: 100vh;background: cadetblue; display: flex;flex-direction: column;justify-content: center">
            <img src="leftarrow.png" style="width: 30%"/>
        </a>
        <div class="col-8">
          <h2 style="display: flex;justify-content: center">Hello! my name is:</h2>
          <h1 style="display: flex;justify-content: center"><i><b>Green Blob</b></i></h1>
          
          <div style="display: flex;justify-content: center">
            <img
              src="https://i.kym-cdn.com/entries/icons/original/000/006/907/ugly.jpg"
              />

          </div>
          <table style="width:100%; display: flex;justify-content: center;">
            <tr>
              <th>Firstname</th>
              <th>Lastname</th>
              <th>Age</th>
              <th>likes</th>
            </tr>
            <tr>
              <td>Green</td>
              <td>Blob</td>
              <td>16</td>
              <td id="likes">3</td>
            </tr>
          </table>
          <div style="display: flex;justify-content: center">
            <img
              src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Love_Heart_symbol.svg"
              onclick="like();" width="10%"
              height="10%" />

          </div>
          <h2 style="display: flex;justify-content: center">Like if you want to go out with me ;)</h2>
        </div>
        <a class="col-2" href="https://sergeydus.github.io/web-hw1/alex1.html" style="direction: rtl; background: cadetblue; height: 100vh; display: flex;flex-direction: column;justify-content: center">
          <img src="rightarrow.png" style="width: 30%"/>
      </a>
        <script>
      var likes = 3;
      function like() {
        likes++;
        document.getElementById("likes").innerText = likes;
      }
      
    </script>
        <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
          integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
          crossorigin="anonymous">
    </script>
        <script
          src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
          integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
          crossorigin="anonymous">
    </script>
        <script
          src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
          integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
          crossorigin="anonymous">
    </script>
      </div>
    </div>
  </body>

</html>
