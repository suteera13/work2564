<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="pa-7 white rounded-circle d-inline-block">
        <v-icon large color="blue">
          mdi-arrow-up-bold-box-outline
        </v-icon>
      </div>
      <h1>KNN BANK</h1>
      <h3>MOBILE APP</h3>
      <v-form>
        <v-container>
          <v-col cols="12" sm="8" md="6">
            <v-text-field
              label="PLEATE ENTER YOUR PASSWORD"
              placeholder="PASSWORD"
              filled
              rounded
              dense
            />
            <v-btn class="btn1">
              <span class="txt1">LOG IN</span>
            </v-btn>
            <p>Forgot password?</p>
            <p>New to Bank App?Sign Up</p>
          </v-col>
        </v-container>
      </v-form>
    </v-col>
  </v-row>
</template>

<style>
  .pa-7{
    margin-top: 100px;
    margin-bottom: 20px;
  }
  .h3{
    margin-top: 50px;
  }
  .txt1{
    color: brown;
  }
  .btn1{
    background: linear-gradient(to bottom,#ffeb3b,#ffc107);
    margin-bottom: 90px;
  }
</style>
