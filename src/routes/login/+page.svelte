<nav class="navbar navbar-expand-lg" style="box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);background: #adb5bd;">
  <div class="container-fluid">
    <a class="navbar-brand" href="principal">VENEMOTOS</a>
  </div>

  <form class="d-flex my-2" role="search">
    <input
      class="form-control me-2"
      type="search"
      placeholder="¿Qué moto buscas?"
      aria-label="Search"
      style="width: 200px;"
    />
    <button class="btn btn-outline-success" type="submit">Buscar</button>
  </form>
</nav>

<section style="background: #adb5bd;">
  <div class="container-fluid h-custom">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col-md-9 col-lg-6 col-xl-5">
        <img src="src\public\img\V.png" class="img-fluid" alt="login" />
      </div>
      <div class="col-md-8 col-lg-6 col-xl-4 offset-xl-1" >
        <form>
          <div
            class="d-flex flex-row align-items-center justify-content-center justify-content-lg-start"
          >
            <p class="lead fw-normal mb-0 me-3">Inicia sesión con</p>
            <button
              type="button"
              data-mdb-button-init
              data-mdb-ripple-init
              class="btn btn-primary btn-floating mx-1"
            >
              <i class="fab fa-facebook-f"></i>
            </button>

            <button
              type="button"
              data-mdb-button-init
              data-mdb-ripple-init
              class="btn btn-primary btn-floating mx-1"
            >
              <i class="fab fa-twitter"></i>
            </button>

            <button
              type="button"
              data-mdb-button-init
              data-mdb-ripple-init
              class="btn btn-primary btn-floating mx-1"
            >
              <i class="fab fa-linkedin-in"></i>
            </button>
          </div>

          <div class="divider d-flex align-items-center my-4">
            <p class="text-center fw-bold mx-3 mb-0">Ó</p>
          </div>

          <!-- Email input -->
          <div data-mdb-input-init class="form-outline mb-4">
            <input
              type="email"
              id="form3Example3"
              class="form-control form-control-lg"
              placeholder="Ingresa tu correo"
            />
            <label class="form-label" for="form3Example3"></label>
          </div>

          <!-- Password input -->
          <div data-mdb-input-init class="form-outline mb-3">
            <input
              type="password"
              id="form3Example4"
              class="form-control form-control-lg"
              placeholder="Ingresa tu contraseña"
            />
            <label class="form-label" for="form3Example4"></label>
          </div>

          <div class="d-flex justify-content-between align-items-center">
            <!-- Checkbox -->
            <div class="form-check mb-0">
              <input
                class="form-check-input me-2"
                type="checkbox"
                value=""
                id="form2Example3"
              />
              <label class="form-check-label" for="form2Example3">
                Recordar
              </label>
            </div>
            <a href="#!" class="text-body">Has olvidado tu contraseña?</a>
          </div>

          <div class="text-center text-lg-start mt-4 pt-2">
            <button
              type="button"
              data-mdb-button-init
              data-mdb-ripple-init
              class="btn btn-primary btn-lg"
              style="padding-left: 2.5rem; padding-right: 2.5rem;">Login</button
            >
            <p class="small fw-bold mt-2 pt-1 mb-0">
              No tienes una cuenta? <a href="register" class="link-danger"
                >Registrate</a
              >
            </p>
          </div>
        </form>
      </div>
    </div>
  </div>
  <div
    class="d-flex flex-column flex-md-row text-center text-md-start justify-content-between py-4 px-4 px-xl-5" style="background: #adb5bd;"
  >
    <div class="text-white mb-3 mb-md-0"></div>
    
    <div>
      <a href="#!" class="text-white me-4">
        <i class="fab fa-facebook-f" style="color:blue"></i>
      </a>
      <a href="#!" class="text-white me-4">
        <i class="fab fa-twitter" style="color: blue;"></i>
      </a>
      <a href="#!" class="text-white me-4">
        <i class="fab fa-google" style="color: blue;"></i>
      </a>
      <a href="#!" class="text-white">
        <i class="fab fa-linkedin-in" style="color: blue;"></i>
      </a>
    </div>
  </div>
</section>
