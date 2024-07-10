<nav
  class="navbar navbar-expand-lg mb-2"
  style="background: #adb5bd;box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);background: #adb5bd;"
>
  <div class="container-fluid">
    <a class="navbar-brand" href="principal">VENEMOTOS</a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="register"
            >Crear cuenta</a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link" href="login">Ingresar</a>
        </li>
      </ul>

      <button
        type="button"
        class="btn btn-outline-success nav-item"
        style="margin-right: 350px;"
      >
        <a class="nav-link active" aria-current="page" href="/"
          >Publica tu moto</a
        >
      </button>

      <form class="d-flex my-2" role="search">
        <input
          class="form-control me-2"
          type="search"
          placeholder="¿Qué moto buscas?"
          aria-label="Search"
          style="width: 200px;border:solid 2px ;border-color: black;"
        />
        <button class="btn btn-outline-success"  type="submit">Buscar</button>
      </form>
    </div>
  </div>
</nav>

<div
  id="carouselExampleSlidesOnly"
  class="carousel slide"
  data-bs-ride="carousel"
>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img
        src="src/public/img/1.png"
        class="d-block"
        alt="..."
        style="height: 400px;width:1450px;"
      />
    </div>
    <div class="carousel-item">
      <img
        src="src/public/img/2.png"
        class="d-block"
        alt="..."
        style="height: 400px;width:1450px;"
      />
    </div>
    <div class="carousel-item">
      <img
        src="src/public/img/3.png"
        class="d-block"
        alt="..."
        style="height: 400px;width:1450px;"
      />
    </div>
  </div>
</div>

<div class="row d-flex justify-content-center position-relative" >
  <div class="card m-2" style="width: 10rem; z-index: 100;top:-50px;left:0px;">
    <p class="card-text text-center mt-2 text-warning">Ingresa</p>
    <a href="login" class="d-flex justify-content-center mt-2">
      <i class="fa-solid fa-users-rectangle" style="font-size: 80px;color:#ffc519;"></i></a
    >
    <div class="card-body">
      <p class="card-text text-center text-warning" style="font-size: 15px;">
        Ingresa <br />publica <br /> cumple tus metas
      </p>
    </div>
  </div>
  <div class="card m-2" style="width: 10rem; z-index: 100;top:-50px;left:0px;">
    <p class="card-text text-center mt-2 text-warning">Crea tu cuenta</p>
    <a href="login" class="d-flex justify-content-center mt-2" style="text-decoration: none;">
      <i class="fa-solid fa-gear" style="font-size: 80px;color:#ffc519;" ></i></a
    >
    <div class="card-body">
      <p class="card-text text-center text-warning" style="font-size: 15px;">
        comienza <br />publica <br /> compara
      </p>
    </div>
  </div>
  <div class="card m-2" style="width: 10rem; z-index: 100;top:-50px;left:0px;">
    <p class="card-text text-center text-primary mt-2">Publica</p>
    <a href="login" class="d-flex justify-content-center mt-2" style="text-decoration: none;">
      <i class="fa-solid fa-motorcycle" style="font-size: 80px;"></i></a
    >
    <div class="card-body">
      <p class="card-text text-center text-primary" style="font-size: 15px;">
        Vende Intercambia
      </p>
    </div>
  </div>
  <div class="card m-2" style="width: 10rem; z-index: 100;top:-50px;left:0px;">
    <p class="card-text text-center text-primary mt-2">Motos 150cc</p>
    <a href="login" class="d-flex justify-content-center mt-2">
      <i class="fa-solid fa-person-biking" style="font-size: 80px;"></i></a
    >
    <div class="card-body">
      <p class="card-text text-center text-primary" style="font-size: 15px;">
        Automaticas <br /> Sincronica <br />Semi-auto
      </p>
    </div>
  </div>
  <div class="card m-2" style="width: 10rem; z-index: 100;top:-50px;left:0px;">
    <p class="card-text text-center text-danger mt-2">Motos 200cc</p>
    <a href="login" class="d-flex justify-content-center mt-2" style="text-decoration: none;">
      <i class="fa-solid fa-gauge-high" style="font-size: 80px;color:red"></i></a
    >
    <div class="card-body">
      <p class="card-text text-center text-danger" style="font-size: 15px;">
        Automaticas <br /> Sincronica <br />Semi-auto
      </p>
    </div>
  </div>
  <div class="card m-2" style="width: 10rem; z-index: 100;top:-50px;left:0px;">
    <p class="card-text text-center mt-2 text-danger">Otros cilindrajes</p>
    <a href="login" class="d-flex justify-content-center mt-2" style="text-decoration: none;">
      <i class="fa-solid fa-gas-pump" style="font-size: 80px;color:red"></i></a
    >
    <div class="card-body">
      <p class="card-text text-center text-danger" style="font-size: 15px;">
        Automaticas <br /> Sincronica <br />Semi-auto
      </p>
    </div>
  </div>
</div>

<footer class="text-center text-lg-start text-muted" style="background: #adb5bd;box-shadow: 8px -8px 5px 0px rgba(0,0,0,0.75);">
  <section class="pt-5">
    <div class="container text-center text-md-start">
      <div class="row">
        <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
          <h6 class="text-uppercase fw-bold mb-4">
            <i class="fa-solid fa-road me-3"></i>VENEMOTOS
          </h6>
          <p>
            Empresa dedicada a la venta y adquision de motocicletas.
            Adaptandonos al presupuesto de cada persona .
          </p>
        </div>
        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
          <h6 class="text-uppercase fw-bold mb-4">Motos</h6>
          <p>
            <a href="#!" class="text-reset"  style="text-decoration: none;">Bera - Ava</a>
          </p>
          <p>
            <a href="#!" class="text-reset" style="text-decoration: none;">Empire - Yamaha</a>
          </p>
        </div>
        <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
          <h6 class="text-uppercase fw-bold mb-4">Cilindraje</h6>
          <p>
            <a href="#!" class="text-reset text-center" style="text-decoration: none;">125cc - 150cc</a>
          </p>
          <p>
            <a href="#!" class="text-reset"  style="text-decoration: none;">200cc - 250cc</a>
          </p>
        </div>
        <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
          <h6 class="text-uppercase fw-bold mb-4">Contactanos</h6>
          <p><i class="fas fa-home me-3"></i> Venezuela, Táchira</p>
          <p>
            <i class="fas fa-envelope me-3"></i>
            ayos007@gmail.com
          </p>
        </div>
      </div>
    </div>
  </section>
  <section
  class="d-flex justify-content-center justify-content-lg-between p-2 border-bottom"
>
  <div class="me-5 d-none d-lg-block">
    <span>Conéctate con nosotros en las redes sociales:</span>
  </div>
  <div>
    <a href="#!" class="me-4 text-reset">
      <i class="fab fa-facebook-f"></i>
    </a>
    <a href="#!" class="me-4 text-reset">
      <i class="fab fa-twitter"></i>
    </a>
    <a href="#!" class="me-4 text-reset">
      <i class="fab fa-google"></i>
    </a>
    <a href="#!" class="me-4 text-reset">
      <i class="fab fa-instagram"></i>
    </a>
    <a href="#!" class="me-4 text-reset">
      <i class="fab fa-linkedin"></i>
    </a>
    <a href="#!" class="me-4 text-reset">
      <i class="fab fa-github"></i>
    </a>
  </div>
</section>
  
</footer>
