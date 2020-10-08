<template>
  <div>
      <div class="container-header">
      <Header>
        </Header>
          </div>
          <BoxDownload>

          </BoxDownload>
      
  </div>
</template>

<script>

import Header from "./components/Header"
import BoxDownload from "./components/BoxDownload"

export default {
  name: 'App',
  components: { Header, BoxDownload }
}
</script>



<style>
.container-header {
  display: flex;
  justify-content: flex-end;
  flex-wrap: wrap;
}
</style>
