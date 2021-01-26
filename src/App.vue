<template>
  <v-app>
    <v-card>
      <v-card-title> <h1 class="display-1">Hello</h1></v-card-title>
      <v-card-text>
        <v-form
          ><v-text-field label="Username"></v-text-field>
          <v-text-field label="Password" type="password"></v-text-field>
        </v-form>
      </v-card-text>
      <v-card-actions>
        <v-btn>Register</v-btn>
        <v-btn>Login</v-btn>
      </v-card-actions>
    </v-card>
  </v-app>
</template>

<script>
export default {
  name: "App",

  components: {},

  data: () => ({
    //
  }),
}
</script>
