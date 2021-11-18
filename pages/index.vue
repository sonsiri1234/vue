<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div
        class="pa-7 white rounded-circle d-inline-block"
      >
        <v-icon large color="blue">
          mdi-cloud-upload
        </v-icon>
      </div>
    </v-col>
    <div>
      <h1>KNN BANK</h1>
      <h3>MOBILE APP</h3>
      <v-form>
        <v-container>
          <v-row>
            <v-col
              cols="12"
              sm="6"
              md="4"
            >
              <v-text-field
                label="PLEASE ENTER YOUR PASSWORD"
                placeholder="PASSWORD"
                filled
                rounded
                dense
              />
              <v-btn class="btn1">
                <span class="txt1">LOG IN</span>
              </v-btn>
              <p>Forgot password?</p>
              <p>New to Bank App? Sign Up</p>
            </v-col>
          </v-row>
        </v-container>
      </v-form>
    </div>
  </v-row>
</template>

<style>
.pa-7 {
  margin-top:310px;

}
h3{
  margin-bottom: 40px;
  }
.txt1{
  color: #4E342E;
}
.btn1{
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-bottom: 60px;
}
</style>
