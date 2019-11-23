<template>
  <q-page>
    <div id="noticias" class="column q-pa-md">
    <q-card class="my-card">
      <q-img src="https://cdn.quasar.dev/img/parallax2.jpg">
      <q-badge class="q-mt-sm float-right" color="orange">
        Categoria
      </q-badge>
      </q-img>
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://cdn.quasar.dev/img/avatar2.jpg">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label>Title</q-item-label>
          <q-item-label caption>Subhead</q-item-label>
        </q-item-section>
      </q-item>
    </q-card>
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
