<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="pa-7 white rounded-circle d-inline-block">
        <!-- <v-icon large color="blue">
          mdi-arrow-up-bold-box-outline
        </v-icon> -->
        <i class="fas fa-school" style="color: #0989ff; font-size: 30px;" />
      </div>
      <h1>KNN BANK</h1>
      <h3>MOBILE APP</h3>
      <v-form>
        <v-container>
          <v-col cols="12" sm="8" md="6">
            <v-menu transition="slide-x-transition">
              <template #activator="{ on, attrs }">
                <v-text-field
                  label="PLEATE ENTER YOUR PASSWORD"
                  placeholder="PASSWORD"
                  filled
                  rounded
                  dense
                  v-bind="attrs"
                  v-on="on"
                />
              </template>
              <div class="box">
                <v-row>
                  <v-col cols="4" class="text-right">
                    <v-btn fab light elevation="0">
                      1
                    </v-btn>
                    <v-btn fab light elevation="0">
                      4
                    </v-btn>
                    <v-btn fab light elevation="0">
                      7
                    </v-btn>
                  </v-col>
                  <v-col cols="4" class="text-center">
                    <v-btn fab light elevation="0">
                      2
                    </v-btn>
                    <v-btn fab light elevation="0">
                      5
                    </v-btn>
                    <v-btn fab light elevation="0">
                      8
                    </v-btn>
                    <v-btn fab light elevation="0">
                      0
                    </v-btn>
                  </v-col>
                  <v-col cols="4">
                    <v-btn fab light elevation="0">
                      3
                    </v-btn>
                    <v-btn fab light elevation="0">
                      6
                    </v-btn>
                    <v-btn fab light elevation="0">
                      9
                    </v-btn>
                  </v-col>
                </v-row>
              </div>
            </v-menu>
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
  .box{
    background-color: #fff;
    padding: 5px;
    border-radius: 10px;
    font-size: 18px;
  }
</style>
