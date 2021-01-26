<template>
  <v-app>
    <v-card width="400">
      <v-card-title> <h1 class="display-1">Hello</h1></v-card-title>
      <v-card-text>
        <v-form
          ><v-text-field
            label="Username"
            prepend-icon="mdi-account-circle"
          ></v-text-field>
          <v-text-field
            label="Password"
            type="password"
            prepend-icon="mdi-lock"
            append-icon="mdi-eye-off"
          ></v-text-field>
        </v-form>
      </v-card-text>
      <v-card-actions>
        <v-btn color="success">Register</v-btn>
        <v-btn color="info">Login</v-btn>
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
