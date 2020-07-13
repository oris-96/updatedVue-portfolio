<template>
  <div class="container">
    <b-container class="bv-example-row h-100 mt-5">
      <b-row class=" h-100 justify-content-center align-items-center">
        <b-col cols="8">
          <h4>
            <span class="header__greet">Hello</span>
          </h4>
          <h2>
            <span class="header__name">I'm Ibrahim Abdulkareem.</span>
          </h2>
          <h1>
            <span class="header__work">I'm a Software Engineer.</span>
          </h1>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<style lang="scss" scoped>
.container {
  margin-top: 13%;
}
.header {
  &__greet {
    font-size: 20px;
    color: #da22ff;
  }

  &__name {
    font-size: 40px;
    font-weight: 400;
    color: #e4e3e3;
  }

  &__work {
    font-size: 50px;
    font-weight: 400;
    color: #e4e3e3;
  }
}
</style>
