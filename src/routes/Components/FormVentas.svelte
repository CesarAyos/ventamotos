<script>
    export let moto
    export let onSubmitHandlers
   
  
  </script>

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


<div class="d-flex justify-content-center">
  <div class="card m-5" style="width:35rem;background-color:#adb5bd ;box-shadow: 0px 38px 64px 30px rgba(0,0,0,0.75);">
    <h2 class="text-uppercase text-center mb-3 mt-3">Formulario de Ventas</h2>
    <form on:submit|preventDefault={onSubmitHandlers} class="row p-3">
      <div class="input-group d-flex mb-3 col-md-12">
        <span class="input-group-text" id="basic-addon1"
          ><i class="fa-solid fa-user"></i></span
        >
        <input
        bind:value={moto.vendedor}
          type="text"
          class="form-control"
          id="vendedor"
          placeholder="NOMBRE DEL VENDEDOR"
          required
        />
      </div>
  
      <div class="input-group mb-3 col-md-4">
        <input
        bind:value={moto.marca}
          type="text"
          id="marca"
          class="form-control"
          placeholder="MARCA DE LA MOTO"
          required
        />
        <span class="input-group-text" id="basic-addon2"
          ><i class="fa-solid fa-motorcycle"></i></span
        >
      </div>
  
      <div class="input-group mb-3 col-md-4">
        <input
        bind:value={moto.modelo}
          type="text"
          id="modelo"
          class="form-control"
          placeholder="MODELO DE LA MOTO"
          required
        />
        <span class="input-group-text" id="basic-addon2"
          ><i class="fa-solid fa-group-arrows-rotate"></i></span
        >
      </div>
  
      <div class="input-group mb-3 col-md-4">
        <input
        bind:value={moto.ano}
          type="month"
          id="año"
          class="form-control"
          placeholder="AÑO DE LA MOTO"
          required
        />
        <span class="input-group-text" id="basic-addon2"
          ><i class="fa-solid fa-group-arrows-rotate"></i></span
        >
      </div>
  
      <div class="input-group mb-3 col-md-6">
        <input
        bind:value={moto.ubicacion}
          type="text"
          id="ubicacion"
          class="form-control"
          placeholder="UBICACIÓN DE LA MOTO"
          required
        />
        <span class="input-group-text" id="basic-addon2"
          ><i class="fa-solid fa-group-arrows-rotate"></i></span
        >
      </div>
  
      <div class="input-group mb-3 col-md-6">
        <span class="input-group-text">$</span>
        <input
        bind:value={moto.precio}
          type="number"
          id="moneda"
          class="form-control"
          placeholder="PRECIO DE LA MOTO"
          aria-label="Amount (to the nearest dollar)"
          required
        />
        <select bind:value={moto.moneda} id="precio" required class="btn btn-dark">
          <option value="Bolivares">Bolivares</option>
          <option value="Dolares">Dolares</option>
          <option value="Euros">Euros</option>
        </select>
      </div>
  
      <div class="input-group mb-3 col-md-12">
        <input
          bind:value={moto.telefono}
          type="number"
          id="telefono"
          class="form-control"
          placeholder="TELEFONO PRINCIPAL DEL VENDEDOR"
          aria-label="Username"
          required
        />
        <span class="input-group-text"><i class="fa-solid fa-phone"></i></span>
        <input
        bind:value={moto.telefono2}
          type="number"
          id="telefono2"
          class="form-control"
          placeholder="TELEFONO SECUNDARIO DEL VENDEDOR"
          aria-label="Server"
          required
        />
      </div>
  
      <div class="mb-3 col-md-12">
        <div class="input-group">
          <span class="input-group-text" id="basic-addon3"
            ><i class="fa-solid fa-image"></i></span
          >
          <input bind:value={moto.imagen} required type="url" placeholder="https://images" >
  
        </div>
      </div>
  
      <div class="input-group col-md-12">
        <span class="input-group-text"
          ><i class="fa-solid fa-table-cells"></i></span
        >
        <textarea
        bind:value={moto.description}
          id="textarea"
          class="form-control"
          placeholder="DESCRIPCIÓN DE LA MOTO"
          aria-label="With textarea"
          required
        ></textarea>
      </div>
  
      <div class="d-flex flex-column flex-md-row text-center text-md-start justify-content-between">

      <div class="p-2">
        <p class="p-2">¿Unico Dueño?</p>
        <select id="dueño" bind:value={moto.dueno} required class="btn btn-dark">
          <option value="si">SI</option>
          <option value="no">NO</option>
        </select>
      </div>
  
      <div class="p-2">
        <p class="p-2">TRANSMISIÓN</p>
        <select id="transmison" required bind:value={moto.transmision} class="btn btn-dark">
          <option value="AUTOMATICA">AUTOMATICA</option>
          <option value="SINCRONICA">SINCRONICA</option>
          <option value="SEMI-AUTOMATICA">SEMI-AUTOMATICA</option>
        </select>
      </div>
  
      <div class="p-2">
        <p class="p-2">CILINDRAJE</p>
        <select id="cilindraje" required  bind:value={moto.cilindraje} class="btn btn-dark">
          <option value="100">100cc</option>
          <option value="125">125cc</option>
          <option value="150">150cc</option>
          <option value="200">200cc</option>
          <option value="250">250cc</option>
          <option value="otros">otros</option>
        </select>
      </div>
  
      <div class="p-2">
        <p class="p-2">NEGOCIABLE</p>
        <select id="negociable" required bind:value={moto.negociable} class="btn btn-dark">
          <option value="si">SI</option>
          <option value="no">NO</option>
        </select>
      </div>
    </div>
      <div class="d-flex justify-content-center">
      <button type="submit"  class="btn btn-outline-success m-5 col-md-11">PUBLICAR</button>
    </div>
    </form>
  </div>
</div>