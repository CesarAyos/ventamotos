<script>
   import FormVentas from "./Components/FormVentas.svelte"   
   import Ventas from "./Components/Ventas.svelte";
        
        let moto = {
        vendedor: '',
        marca: '',
        modelo: '',
        ano: '',
        ubicacion: '',
        precio: '',
        moneda: '',
        telefono: '',
        telefono2: '',
        imagen: '',
        description: '',
        dueno: '',
        transmision: '',
        cilindraje: '',
        negociable: '',
    };
    
     
      
    let Arraymoto = [];
    
    
    const onSubmitHandlers = () => {
        Arraymoto=[...Arraymoto,{...moto}];
        console.log(Arraymoto)
        Clear();
    };
    
    
    
    const Clear = () => {
        moto = {
        vendedor: '',
        marca: '',
        modelo: '',
        ano: '',
        ubicacion: '',
        precio: '',
        moneda: '',
        telefono: '',
        telefono2: '',
        imagen: '',
        description: '',
        dueno: '',
        transmision: '',
        cilindraje: '',
        negociable: '',
        }
    }
    
    
    </script>
    
    
    <FormVentas {moto} {onSubmitHandlers}/>
    <Ventas {Arraymoto} />
    