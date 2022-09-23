<template>
  <div class="info">
    <div class="container">
      <div class="row text-white">
        <div class="col-md-7">
          <h4>Empresa: Ha la mexicana..!!</h4>
        </div>
        <div class="col-md-5">
          <h4>Francisco Javier Tapia Rivera 10A DGS</h4>
        </div>
      </div>
    </div>
  </div>
  <br />
  <header>
    <div class="container">
      <div class="col-md-12">
        <nav class="menu">
          <ul>
            <div class="col-md-4">
              <li>
                <img
                  src="https://images.vexels.com/media/users/3/173821/raw/f2a5fa5ef1ef0dbf2461da78740d5ebf-diseno-de-logotipo-de-empresa-de-comida-mexicana.jpg"
                  alt="Logo VUE"
                  width="250"
                  height="100"
                />
              </li>
            </div>
            <li><a class="text-white btn btn-info" href="">Tacos</a></li>
            <li><a class="text-white btn btn-info" href="">Gizados</a></li>
            <li><a class="text-white btn btn-info" href="">Desayunos</a></li>
            <li><a class="text-white btn btn-info" href="">Postres</a></li>
            <li><a class="text-white btn btn-info" href="">vevisas</a></li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="container gris">
      <h5>Nuestros platos</h5>
      <p><a class="btn">inicio</a> / <a class="btn">Nuestros platos</a></p>
    </div>
  </header>

  <div class="tel">
    <div class="container">
      <div class="row text-white">
        <div class="col-md-12">
          <h4>Teléfono para Pedidos: 952 03 99 50 - Whatsapp:622 51 51 13</h4>
        </div>
      </div>
    </div>
  </div>

  <div>
    <div class="container">
      <div class="row">
        <div class="col-md-12 center azul text-white">
          Télefono para pedidos: 952 03 99 50 - Whatsapp: 622 51 51 13
        </div>
      </div>
    </div>
  </div>
  <div class="container center">
    <h1>Ensalada y entrantes</h1>
    <card
      url="https://img.chilango.com/2018/11/Caldos-en-CDMX-biwon1.jpg"
      nombre="Pansita"
      descripcion="Incluye un vaso de agua y tortillas"
      costo="100"
    />
    <card
      url="https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/BE035512-0E75-41ED-B1C2-EA9A8C6062E8/Derivates/FBEEFA5F-A1B5-47B2-B632-BFD0506D00AA.jpg"
      nombre="Pozole"
      descripcion="Incluye tostadas y un vaso de agua"
      costo="190"
    />
    <card
      url="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQscVyC0rRJUZjczJieY6aMpiWipQst1d7y4sFBF-EwD_ABWqUUlvlTVI7sCw3QtrRgZmo&usqp=CAU"
      nombre="Clayudas"
      descripcion="Incluye salsas agua y una vevida a escoger"
      costo="200"
    />

    <card
      url="https://aluminiomonarca.mx/uploads/2021/02/Tamales.jpg"
      nombre="Tamales"
      descripcion="Incluye chapurrado o atole de granillo"
      costo="101"
    />
    <card
      url="https://foodandtravel.mx/wp-content/uploads/2017/02/tacos.jpg"
      nombre="Tacos al pastor y arabes"
      descripcion="Incluye refresco"
      costo="290"
    />
    <card
      url="https://www.cocinavital.mx/wp-content/uploads/2019/05/chiles-rellenos-queso-capeados-caldillo-jitomate.jpg"
      nombre="Chiles rellenos"
      descripcion="Vaso de agua y tortillas"
      costo="199"
    />
  </div>
  <footer>
    <h4>© 2022 BlackSoft Company - Todos los Derechos Reservados.</h4>
  </footer>
</template>

<script>
import Card from "./components/Card.vue";
export default {
  components: { Card },
};
</script>

<style scoped>
h1 {
  text-align: center;
}
h4 {
  margin-top: 10px;
}
footer {
  background-color: red;
}
.center {
  align-content: center;
  text-align: center;
  align-items: center;
}
.der {
  text-align: left;
}
.gris {
  background-color: #e8eae9;
  margin-top: 15px;
}
.info {
  background-color: #035ce2;
}
.tel {
  background-color: #035ce2;
  text-align: center;
}

.menu ul {
  display: flex;
  padding: 0;
  margin: 0;
  list-style: none;
}

.menu a {
  display: block;
  padding: 0.5em;
  background-color: #ffeaab;
  text-decoration: none;
  color: #191c26;
}

.menu a:hover {
  background-color: #cc673b;
}

.menu ul li ul {
  display: none;
}

.menu ul li a:hover + ul,
.menu ul li ul:hover {
  display: block;
}

li a {
  margin: 5px;
}


footer{
    text-align: center;
    color: #fff;
    background-color: black;
}
</style>
