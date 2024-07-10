<nav class="navbar navbar-expand-lg " style="box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);background: #adb5bd;">
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


<section>
  <div class="mask d-flex align-items-center gradient-custom-3 m-5 ">
    <div class="container ">
      <div class="row d-flex justify-content-center align-items-center h-100">
        <div class="col-12 col-md-9 col-lg-7 col-xl-6">
          <div class="card" style="border-radius: 15px;box-shadow: 0px 38px 64px 30px rgba(0,0,0,0.75);">
            <div class="card-body p-5 bg-body-tertiary">
              <h2 class="text-uppercase text-center mb-5">Crear una cuenta</h2>

              <form >

                <div data-mdb-input-init class="form-outline mb-4">
                  <input type="text" id="nombre" placeholder="Tu nombre" class="form-control form-control-lg" />
                  <label class="form-label" for="nombre"></label>
                </div>

                <div data-mdb-input-init class="form-outline mb-4">
                  <input type="email" id="correo" placeholder="Correo electronico" class="form-control form-control-lg" />
                  <label class="form-label" for="correo"></label>
                </div>

                <div data-mdb-input-init class="form-outline mb-4">
                  <input type="password" id="contraseña" placeholder="contraseña" class="form-control form-control-lg" />
                  <label class="form-label" for="contraseña"></label>
                </div>

                <div data-mdb-input-init class="form-outline mb-4">
                  <input type="password" id="repetircontraseña" placeholder="Repetir contraseña" class="form-control form-control-lg" />
                  <label class="form-label" for="repetircontraseña"></label>
                </div>

                <div class="form-check d-flex justify-content-center mb-5">
                  <input class="form-check-input me-2" type="checkbox" value="" id="form2Example3cg" />
                  <label class="form-check-label" for="form2Example3g">
                    Acepto todas las declaraciones en términos de servicio. <a href="#!" class="text-body"><u>Términos de servicio</u></a>
                  </label>
                </div>

                <div class="d-flex justify-content-center">
                  <button  type="button" data-mdb-button-init
                    data-mdb-ripple-init class="btn btn-success btn-block btn-lg gradient-custom-4 text-body">Registrarme</button>
                </div>

                <p class="text-center text-muted mt-5 mb-0">¿Ya tienes una cuenta? <a href="login"
                    class="fw-bold text-body"><u>Entre aquí</u></a></p>

              </form>

            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
