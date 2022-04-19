## LANGKAH - LANGKAH PRAKTIKUM 6

```
Galang Rintang Widya Pratama
312010299
TI.20.B.2
Universitas Pelita Bangsa
```

## Membuat Layout Web Dengan Menggunakan Twitter Bootsrap

## Langkah 1
Buat folder baru dengan nama lab6_css_framework

![image](https://user-images.githubusercontent.com/101440705/163949037-ef6f9896-3e39-4198-8ab0-1aa6d9d6ddbc.png)
![image](https://user-images.githubusercontent.com/101440705/163949082-aa3ccbcf-750b-47b3-91ff-7a1301a017a2.png)


## Langkah 2
Buat File html didalam dile lab6_css_framework dan masukan kode bootstrapnya, kode tersebut bisa kita ambil dari web bootstrap.

Berikut Kodenya :

```
<!DOCTYPE html>
<html lang="en" >
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>lab6_css_framework</title>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
        <link rel="stylesheet" type="text/css" href="css/style.css">
    </head>
```

## Langkah 3
setelah itu buatlah layout sederhana seperti yang pernah kita buat di praktikum sebelumnya.

dan dibawah ini adalah kode nya :

# HTML

```
<!DOCTYPE html>
<html lang="en" >
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>lab6_css_framework</title>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
        <link rel="stylesheet" type="text/css" href="css/style.css">
    </head>
    <body>
        <div class="container" >
            <!--NAVBAR-->
            <div class="jumbotron jumbotron-fluid bg-light pb-2 mb-1">
              <div class="container">
                <h1 class="display-4">Layout Sederhana</h1>
              </div>
            </div>
            
            <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
              <a class="navbar-brand" href="#"></a>
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Article</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link">contact</a>
                  </li>
                </ul>
              </div>
            </nav>

            <!--JUMBOTRON-->
    <div class="jumbotron">
    <h1 class="display-4">Hello, world!</h1>
    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat.</p>
    <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
    </div>
     <div class="d-flex p-2">
    <div class="p-2">
      <!--CARDS-->
    <div class="row" >
      <div class="col">
      <div class="card pt-3">
        <img src="assets/anon.jpg" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      <div class="col">
      <div class="card pt-3">
        <img src="assets/anon.jpg" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      <div class="col">
      <div class="card pt-3">
        <img src="assets/anon.jpg" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      </div>
  <hr>
  <!--CARDS 2-->
  <div class="mt-3 mb-5">
    <h2>First Featurette Heading</h2>
    <div class="row no-gutters">
      <div class="col-md-3">
        <img src="assets/anon.jpg" class="card-img-top rounded-square" alt="...">
      </div>
      <div class="col-md-8">
        <div class="card-body">
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
        </div>
      </div>
    </div>
  </div>
<hr>
  <div class="mt-5">
    <h2>First Featurette Heading</h2>
    <div class="row">
      <div class="col-md-8">
        <div class="card-body">
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
        </div>
      </div>
      <div class="col-md-3">
        <img src="assets/anon.jpg" class="card-img-top rounded-square" alt="...">
      </div>
    </div>
  </div>

</div>

<div class="p-2">
<!--LIST GROUP-->
  <div class="col">
  <div class="list-group">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Header
    </a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
  </div>
  <div class="list-group mt-3">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Text
    </a>
    <span class="list-group-item list-group-item-action">Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu.
      Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</span>
  </div>
</div>  
</div>
</div>
<footer>
<p>&copy; 2021 - Universitas Pelita Bangsa - Galang Rintang Widya Pratama - 312010299</p>
</footer>
</div>
        <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF" crossorigin="anonymous"></script>
    </body>
</html>
```

# CSS

```
.card-img-top{
	width: 120px;
	align-self: center;
}

footer {
    clear:both;
	background-color:#1d1d1d; 
	padding:20px;
	color:#eee;
}
```

## Dan dibawah ini adalah hasil dari Kode Bootstrap di atas :

![image](https://user-images.githubusercontent.com/101440705/163950935-59ca7287-44ad-4039-a8d2-bb1082cf3477.png)

![image](https://user-images.githubusercontent.com/101440705/163950983-9ed14a9f-bfba-4cc4-9db9-1c4475d0c4a0.png)
