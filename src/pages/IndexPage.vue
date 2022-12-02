<template>
  <q-page class="column flex-center">
    <q-input
      outlined
      style="min-width: 360px"
      class="q-my-md q-mx-lg"
      label="senha"
    >
      <template v-slot:append>
        <q-icon name="visibility" />
      </template>
    </q-input>
    <div outlined class="q-my-md justify-between">
      <q-btn
        unelevated
        class="q-mx-md"
        rounded
        color="blue"
        label="0 ou 3 "
      ></q-btn>
      <q-btn
        unelevated
        class="q-mx-md"
        rounded
        color="blue"
        label="6 ou 4 "
      ></q-btn>
      <q-btn
        unelevated
        class="q-mx-md"
        rounded
        color="blue"
        label="1 ou 5 "
      ></q-btn>
    </div>
    <div class="q-ma-md justify-between">
      <q-btn
        unelevated
        class="q-mx-md"
        rounded
        color="blue"
        label="9 ou 7 "
      ></q-btn>
      <q-btn
        unelevated
        class="q-mx-md"
        rounded
        color="blue"
        label="2 ou 8 "
      ></q-btn>
      <q-btn
        unelevated
        class="q-mx-md q-px-lg q-py-sm"
        rounded
        color="blue"
        icon="backspace"
      ></q-btn>
    </div>
    <q-btn
      unelevated
      class="q-mx-md"
      rounded
      color="blue"
      label="Acessar "
      style="min-width: 360px"
    ></q-btn>
    <q-btn
      unelevated
      class="q-ma-md"
      rounded
      color="blue-2"
      text-color="blue-9"
      label="esqueci minha senha "
      style="min-width: 360px"
    ></q-btn>
    <template v-slot:append>
      <q-icon name="favorite" />
    </template>
  </q-page>
</template>

<script></script>
