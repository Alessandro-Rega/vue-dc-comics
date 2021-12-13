<template>
  <div>
      <main>
          <span>→ Content goes here ←</span>
      </main>
  </div>
</template>

<script>
export default {
    name: 'Main'
}
</script>

<style scoped>

div{
    background-color: #212121;
}

main{
    width: 70%;
    height: 180px;
    margin: 0 auto;
    background-color: #212121;
    display: flex;
    align-items: center;
}

span{
    color: white;
    font-weight: 800;
    font-size: 30px;
}

</style>