<template>
    <section id="sobremi">
        <div class="contenedor-foto">
            <img :src="require('@/assets/foto.jpg')" alt="">
        </div>
        <div class="sobremi">
            <p class="titulo-seccion">About Me</p>
            <h2>Hi, I am <span>Javier Argoty</span> </h2>
            <h3>Web Developer</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur reprehenderit voluptatibus blanditiis nulla adipisci iste fuga expedita, ea exercitationem dicta, similique rem, atque soluta recusandae ipsam autem. Sapiente, quo ducimus?</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro nam a beatae natus.</p>
            <a href="#">Download CV</a>
        </div>
    </section>
</template>

<script>
export default {};
</script>

<style>
#sobremi {
  max-width: 1100px;
  margin: auto;
  padding: 100px 15px;
  color: #111135;
  display: flex;
}

#sobremi .contenedor-foto {
  max-width: 400px;
  margin-right: 80px;
}

#sobremi .contenedor-foto img {
  padding: 20px;
  width: 100%;
  border-radius: 20px;
  background-color: #f3f3f3;
}

#sobremi .sobremi {
  margin: 0 40px;
}

#sobremi .sobremi .titulo-seccion {
  font-size: 22px;
  text-transform: uppercase;
  color: #111135;
  text-decoration: underline;
  text-decoration-color: #d3d3d3;
  text-decoration-thickness: 5px;
}

#sobremi .sobremi h2 {
  font-size: 34px;
  font-weight: bold;
  margin: 20px 0;
  letter-spacing: 2px;
}

#sobremi .sobremi h2 span {
  color: var(--color);
}

#sobremi .sobremi h3 {
  font-size: 18px;
  font-weight: 500;
  text-transform: uppercase;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

#sobremi .sobremi p {
  font-size: 14px;
  line-height: 25px;
  color: #565656;
  margin-bottom: 12px;
}

#sobremi .sobremi a {
  display: inline-block;
  text-decoration: none;
  color: #000;
  border-radius: 30px;
  border: 1px solid #000;
  padding: 10px 20px;
  margin-top: 30px;
  transition: 0.5s;
}

#sobremi .sobremi a:hover {
  background-color: var(--color);
  color: #fff;
}
</style>