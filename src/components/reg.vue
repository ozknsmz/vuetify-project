<template>
  <v-app id="inspire">
    <v-content>
      <v-container class="fill-height" fluid>
        <v-row align="center" justify="center">
          <v-col cols="4" sm="4" md="4">
            <v-card class="elevation-12 mx-auto mt-5">
              <v-window v-model="step">
                <v-window-item :value="1">
                  <v-row align="center" justify="center" class="fill-height">
                    <v-col cols="6" md="10">
                      <v-card-text class="mt-4">
                        <h1
                          class="
                            text-center
                            display-1
                            teal--text
                            text--accent-3
                          "
                        >
                          Create Account
                        </h1>
                        <v-form @submit.prevent="createUser">
                          <v-text-field
                            label="Name"
                            name="Name"
                            prepend-icon="person"
                            type="text"
                            color="teal accent-3"
                          />
                          <v-text-field
                            label="Email"
                            name="Email"
                            prepend-icon="email"
                            type="text"
                            color="teal accent-3"
                          />

                          <v-text-field
                            id="password"
                            label="Password"
                            name="password"
                            prepend-icon="lock"
                            type="password"
                            color="teal accent-3"
                          />
                        </v-form>
                      </v-card-text>
                      <div class="text-center mb-4">
                        <v-btn rounded color="teal accent-3" dark
                          >Register</v-btn
                        >
                      </div>
                    </v-col>
                  </v-row>
                </v-window-item>
              </v-window>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  data: () => ({
  }),

  methods:{
    createUser(){

    }
  },
};
</script>
