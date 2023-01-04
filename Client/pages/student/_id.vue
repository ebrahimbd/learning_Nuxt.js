<template>
  <div>
    <div v-if="product" class="card" style="width: 18rem;">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
        <p class="card-text">
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
          <button id="counter" @click="increment">{{ count }}</button>
          ================={{ title }}
        </p>
        <a href="#" class="card-link">Card link</a>
        <a href="#" class="card-link">Another link</a>
      </div>
    <Make   v-bind:ebrahim="`errrrrrrrrrrrrrrrrrr 56666666666666`"/>
    </div>
  </div>
</template>

<script>
import { nextTick } from "vue";
import index   from "./index.vue";
export default {
  data() {
    return {
      count: 0,
      title: "this._props"
    };
  },
  computed: {
    product() {
      console.log(this);
      return true;
    }
  },
  methods: {
    async increment() {
      this.count++;
    }
  },
  
};
</script>

<style scoped></style>
