<template>
  <div class="layout">
    <div class="header">
      <q-card flat bordered>
        <q-card-section horizontal>
          <q-img src="me.png" height="240px" width="240px">
            <div class="absolute-bottom text-h6">
              Julius Krahn
            </div>
          </q-img>
          <q-separator vertical/>
          <q-card-section class="text-body1">
            I'm one of the cool kids: I like programming.<br/> Currently dipping my toes into Machine Learning.
            <br/><br/>
            Otherwise I enjoy:<br/>
              - running/hiking<br/>
              - skiing<br/>
          </q-card-section>
        </q-card-section>
      </q-card>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss" scoped>
.layout {
  margin: 0 auto;
  width: 96%;
  min-width: 320px;
  max-width: 800px;
}

.header {
  padding: 32px 0 64px 0;
}
</style>
