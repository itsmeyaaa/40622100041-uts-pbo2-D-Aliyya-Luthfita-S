<template>
  <v-navigation-drawer expand-on-hover rail>
    <v-list>
      <v-list-item
        prepend-avatar="https://p16-va.lemon8cdn.com/tos-maliva-v-ac5634-us/oovPZ0BuAEOIiKiV8QbinaATTNMA5AyvB9Uir~tplv-tej9nj120t-origin.webp"
        subtitle="aliyya.luthifta@widyatama.ac.id"
        title="Aliyya Luthfita S"
      ></v-list-item>
    </v-list>

    <v-divider></v-divider>

    <v-list density="compact" nav>
      <v-list-item prepend-icon="mdi-folder" title="Home" :to="'/home'"></v-list-item>
      <v-list-item
        prepend-icon="mdi-account-multiple"
        title="Dosen"
        :to="'/dosen-entry'"
      ></v-list-item>
      <v-list-item prepend-icon="mdi-star" title="Mahasiswa" :to="'/mahasiswa-entry'"></v-list-item>
      <v-list-item prepend-icon="mdi-star" title="Ruangan" :to="'/ruangan-entry'"></v-list-item>
    </v-list>
  </v-navigation-drawer>

  <v-main style="height: 250px"></v-main>
</template>
