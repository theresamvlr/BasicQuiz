<template>
  <div class="question-box-container">
    <b-jumbotron>
      <template v-slot:lead>
        Some questions here
      </template>

      <hr class="my-4" />

      <p>
        Some answers here
      </p>

      <b-button variant="primary" href="#">Submit</b-button>
      <b-button variant="success" href="#">Next</b-button>
    </b-jumbotron>
  </div>
</template>
