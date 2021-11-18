<template>
  <div>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div
          class="pa-7 white rounded-circle d-inline-block margin-top:100px"
        >
          <v-icon color="black" large>
            mdi-cloud-upload
          </v-icon>
        </div>
      </v-col>
    </v-row>
    <h1>HOME ROOM</h1>
    <h3>mobile app</h3>
    <v-form>
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="6"
            md="4"
          >
            <v-menu transition="scroll-y-transition">
              <template #activator="{ on, attrs }">
                <v-text-field
                  label="Please enter your password"
                  placeholder="password"
                  filled
                  rounded
                  dense
                  v-bind="attrs"
                  v-on="on"
                />
              </template>
              <div class="box">
                <v-row>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      1
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      2
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      3
                    </v-btn>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      4
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      5
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      6
                    </v-btn>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      7
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      8
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      9
                    </v-btn>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      0
                    </v-btn>
                  </v-col>
                </v-row>
              </div>
            </v-menu>
            <v-btn
              class="btn1"
            >
              <span class="txt1"> LOGIN </span>
            </v-btn>
            <p>Forgot password?</p>
            <p>New to bang app? Sign up</p>
          </v-col>
        </v-row>
      </v-container>
    </v-form>
  </div>
</template>

<style>
.pa-7{
  margin-top:100px ;
}
h3{
  margin-bottom: 50px;
}
.txt1{
  color: rgb(255, 255, 255);
}
.btn1{
  background: linear-gradient(to bottom,#FFEB3B,#FFC107);
  margin-bottom: 50px;
}
.box{
  background-color: beige;
  padding: 5px;
  border-radius: 10px;
  font-size: 18px;
}
</style>
