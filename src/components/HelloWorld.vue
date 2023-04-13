<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Actualmente Banco Unión S.A. cuenta con cuatro filiales (Valores Unión,
      SAFI Unión, Univida y Unibienes),<br />
      y se compone de una extensa red de oficinas y cajeros automáticos en todo
      el país. El objetivo rector de Banco Unión S.A. se enfoca en crecer y
      consolidar su posición en los primeros lugares<br />
      del Sistema Financiero Nacional, generando los mejores ratios de
      rentabilidad al Banco y manteniendo un permanente<br />
      compromiso con el desarrollo del país a través de servicios financieros
      integrales, eficientes y modernos, ofreciendo<br />
      soluciones ágiles y sobre todo calidad y atención de excelencia.
    </p>
    <img
      alt="Vue logo"
      src="https://cd1.eju.tv/wp-content/uploads/2018/10/5bd300fd89555.jpg"
      height="80"
    />
    <img
      alt="Vue logo"
      src="https://cd1.eju.tv/wp-content/uploads/2017/10/59d7a68e58fd0.jpg"
      height="80"
    />
    <img
      alt="Vue logo"
      src="https://4.bp.blogspot.com/-gGLBIXTlmtU/WwRVkRrgDMI/AAAAAAAAIDY/-0Co20uAL7kOXCX8TzoVVYw_oro6Td28ACLcBGAs/s1600/banco_union_desfalco.jpg"
      height="80"
    />
    <h3>Redes sociales</h3>
    <ul>
      <li>
        <a href="facebook.com" target="_blank" rel="noopener">Facebook</a>
      </li>
      <li><a href="instagram.com" rel="noopener">Instagram</a></li>
      <li><a href="tiktok.com" target="_blank" rel="noopener">Tiktok</a></li>
      <li><a href="youtube.com" target="_blank" rel="noopener">Youtube</a></li>
      <li>
        <a href="whatsapp.com" target="_blank" rel="noopener"
          >Chat en whatsapp</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
