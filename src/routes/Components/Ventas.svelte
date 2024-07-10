<script>
  export let Arraymoto;
</script>
<div class="row m-2">
{#each Arraymoto as item}
<div class="card m-3" style="max-width: 40rem;box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);">
  <div class="row g-0">
    <div class="col-md-4">
      <img src={item.imagen} class="img-fluid rounded-start" alt="..." style="height:25rem ;width:auto;">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Marca:{item.marca} Modelo: {item.modelo} Año:{item.ano}</h5>
        <p class="card-text">descripció n{item.description}</p>
      </div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">Ubicacion:{item.ubicacion} <br>Precio:{item.precio}{item.moneda} </li>
        <li class="list-group-item">Telefono Principal:{item.telefono} <br> Telefono Alternativo:{item.telefono2} <br> Unico Dueño:{item.dueno}</li>
        <li class="list-group-item">transmision:{item.transmision} <br> Cilindraje:{item.cilindraje} <br> negociable:{item.negociable}</li>
      </ul>
      <h2 class="card-title">vendedor:{item.vendedor}</h2>
    </div>
  </div>
</div>
    
  
{/each}
</div>
