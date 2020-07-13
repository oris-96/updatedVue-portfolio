<template>
  <div id="about" class="container">
    <b-container class="bv-example-row h-100 mt-5 ">
      <b-row class=" h-100 justify-content-center align-items-center flex">
        <b-col cols="8">
          <h3 class="header ">
            About Me
          </h3>
          <b-container
            fluid="sm md lg xl"
            class="d-flex flex-column justify-content-between p-3"
          >
            <p>
              i'm Ibrahim, a software Engineer with a passion for problem
              solving, i studied Electrical /Electronics Engineering during my
              undergraduate bachelor's, i was always fascinated by software and
              how they were put together the curiosity made me start the journey
              of teaching myself how to code whilst i was pursuing my
              bachelor's, currently i am pursuing a masters in computer science
              and quantitative methods and i totally love it.
            </p>
            <p>
              I enjoy building performant applications with clean and dynamic
              user interface and an efficient backend architecture, i strive to
              grow and improve myself daily , i solve problems that help save my
              clients money
            </p>
            <p>Here are some of the technologies i'm proficient in:</p>
            <!-- <b-container class="bv-example-row"> -->
            <b-row cols-sm="1" cols-md="2" cols-lg="3">
              <b-col sm="auto" md="auto" lg="auto">
                <ul>
                  <li class="about-tech">Python</li>
                  <li class="about-tech">Javascript/ES5/ES2015</li>
                  <li class="about-tech">HTML5</li>
                  <li class="about-tech">CSS</li>
                </ul>
              </b-col>
              <b-col sm="auto" md="auto" lg="auto">
                <ul>
                  <li class="about-tech">VUEjs</li>
                  <li class="about-tech">NODEjs</li>
                  <li class="about-tech">EXPRESS</li>
                  <li class="about-tech">MongoDB</li>
                </ul>
              </b-col>
              <b-col sm="auto" md="auto" lg="auto">
                <ul>
                  <li class="about-tech">NPM</li>
                  <li class="about-tech">GIT</li>
                  <li class="about-tech">SASS/SCSS</li>
                  <li class="about-tech">Hyper</li>
                </ul>
              </b-col>
            </b-row>
            <!-- </b-container> -->
          </b-container>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<style lang="scss" scoped>
.header {
  display: flex;
  align-items: center;
  &::after {
    content: " ";
    height: 1px;
    width: 50%;
    display: inline-block;
    background-color: #e4e3e3;
    margin-left: 15px;
  }
}

.container {
  margin-top: 15%;
}

.about-tech {
  //position: relative;
  margin-bottom: 10px;
  padding-left: 20px;
  font-size: 14px;
  color: #63beff;
}
</style>
