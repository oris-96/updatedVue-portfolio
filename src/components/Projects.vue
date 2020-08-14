<template>
  <div id="project" class="container">
    <b-container class="bv-example-row h-100 mt-5">
      <b-row class="h-100 justify-content-center align-items-center flex">
        <b-col cols="12">
          <h3 class="header">Projects</h3>
          <b-container
            fluid="sm md lg xl"
            class="d-flex flex-column h-100 justify-content-between p-3 paint"
          >
            <div>
              <b-row class="mb-5">
                <b-card-group deck>
                  <b-card header="Dice Game">
                    <blockquote class="blockquote mb-0">
                      <p>Roll a dice and hold your value, the first player to a minimum of 100 points wins the game. Great app for deciding who should go first in games amongst friends</p>

                      <div class="d-flex justify-content-between p-2">
                        <a href="http://uttermost-brake.surge.sh/">
                          <i class="fas fa-external-link-alt fa-2x"></i>
                        </a>
                        <br />
                        <a href="https://github.com/oris-96/pig-game">
                          <i class="fa fa-github fa-2x" aria-hidden="true"></i>
                        </a>
                      </div>
                    </blockquote>
                  </b-card>

                  <b-card header="Ecommerce app">
                    <blockquote class="blockquote mb-0">
                      <p>A beautiful Ecommerce interface made with React for a Scarf Business, creates a great user experience which improves sales.</p>

                      <div class="d-flex justify-content-between p-2">
                        <a href="http://foolish-month.surge.sh/">
                          <i class="fas fa-external-link-alt fa-2x"></i>
                        </a>
                        <br />
                        <a href="https://github.com/oris-96/ecommerce">
                          <i class="fa fa-github fa-2x" aria-hidden="true"></i>
                        </a>
                      </div>
                    </blockquote>
                  </b-card>

                  <b-card header="Video Rental Rest API">
                    <blockquote class="blockquote mb-0">
                      <p>A Video Rental API using Node, express and mongoDB that performs CRUD operations. This API also features a User Authentication system using JWT, Each endpoint was tested using Postman</p>

                      <div class="d-flex justify-content-between p-2">
                        <a href="https://github.com/oris-96/rentals-api">
                          <i class="fas fa-external-link-alt fa-2x"></i>
                        </a>
                        <br />
                        <a href="https://github.com/oris-96/rentals-api">
                          <i class="fa fa-github fa-2x" aria-hidden="true"></i>
                        </a>
                      </div>
                    </blockquote>
                  </b-card>
                </b-card-group>
              </b-row>
            </div>
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

.paint {
  color: #485563;
}
</style>
