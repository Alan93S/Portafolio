<template>
  <div id="About">
    <div class="fondo2">
      <div class="container text-center pt-5">
 
          <!--Contenido-->
          <div class="row justify-content-center">
        <div class="imagenes col-10 col-sm-9 m-3 p-4 shadow-lg ">
          <h1 class="titulo1 pt-5">Acerca de mi</h1>
          <img class="circular--square img-fluid" src="img/alan.jpeg" />
          <ul>
            <li>Frontend Developer, Awakelab, (2022)</li>
            
          </ul>
          <p class="parrafo1 pt-3">
           Hola, soy Alan San Martín. Finalicé mis estudios en la modalidad bootcamp  "frontend trainee" impartido por AWAKELAB y espero con entusiasmo poner en práctica lo aprendido y ser un aporte en el equipo que me reciba, para así poder despegar y crecer en esta área. Mi última experiencia laboral fue como procurador de cobranza judicial, es en el área que tengo mayor experiencia hasta el momento y de la cual estoy agradecido, ya que, me brindó herramientas y conocimientos sobre distintos ámbitos del mundo laboral. Siempre he tenido un alto interés por la tecnologia en sí, he sido testigo del gran aporte que ha sido para la humanidad, es por esto que hoy definitivamente he decidido reinventarme y salir de mi zona de confort laboral, para afrontar el desafío de trabajar en algo que realmente me apasiona.
          </p>
<!--Iconos Tecnologias-->
          <div class="iconos mt-5">
            <div class="circulos">
              <img class="imagen img-fluid" src="iconos/html-5.png" alt="Html"/>
            </div>
            <div class="circulos">
              <img class="imagen img-fluid" src="iconos/css-3.png" alt="CSS" />
            </div>
            <div class="circulos">
              <img class="imagen img-fluid" src="iconos/sass.png" alt="SASS" />
            </div>
            <div class="circulos">
              <img class="imagen img-fluid" src="iconos/bootstrap.png" alt="Bootstrap"/>
            </div>
            <br />
            <div class="circulos">
              <img class="imagen img-fluid" src="iconos/js.png" alt="Javascript"/>
            </div>
            <div class="circulos">
              <img class="imagen img-fluid" src="iconos/vue.png" alt="Vue" />
            </div>
        
          </div>
          <p class="parrafo2 pt-5">
            Profesional con habilidades de trabajo, prolija y autodidacta.
            Siempre con actitudes de superación y con intereses de formación
            continua.
          </p>
        </div>
      </div>
    </div>
  </div>
  
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Quicksand&display=swap");

* {

  font-family: "Quicksand", sans-serif;
}
.fondo2 {
  color: rgb(36, 35, 35);
  background: #f2f2f5;

}
.titulo1 {
  font-size: 25pt;
  font-weight: bold;
}
.parrafo1 {
  font-size: 16pt;
  color: rgb(68, 65, 65);

}
.imagen {
  height: 80px;
  width: 80px;
  margin-top: 25px;
}
.circulos {
  width: 130px;
  height: 130px;
  display: inline-block;
  margin-left: 20px;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  background-color: #f0f0f0;
  border: 3px solid rgb(0, 0, 0);
  box-shadow: 4px 4px 5px rgb(22, 21, 21);
}
.circulos:hover {
  -webkit-transform: scale(1.3);
  transform: scale(1.3);
}
.circular--square {
  height: 180px;
  width: 180px;
  border-radius: 50%;
  border: 3px solid rgb(0, 0, 0);
  box-shadow: 4px 4px 5px rgb(22, 21, 21);
  margin: 20px;
}
ul {
  list-style: none;
  color: rgb(129, 129, 129);
}
.parrafo2 {
  font-weight: bold;

}
</style>
