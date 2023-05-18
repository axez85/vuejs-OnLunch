<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="yellow">{{ msg }}</h1>
    <h3>
      Mysig morgon och trevlig kväll 
    </h3>
    
    <h3>OBS! Ojämn fördelning</h3>
  </div>

  <div class="container text-center ">
    <div class="row">
      <div class="col-4 tbl">
        Tider
      </div>
      <div class="col-6 ">
        Tekniker
      </div>
    </div>
    <div class="row">
      <div class="col tbl">
        11:00-12:00
      </div>
      <div class="col">
        David
      </div>
      <div class="col">
        David
      </div>
      <div class="col">
        David
      </div>
      <div class="col">
        David
      </div>
    </div>
    <div class="row">
      <div class="col tbl">
        12:00-13:00
      </div>
      <div class="col">
        David
      </div>
      <div class="col">
        David
      </div>
      <div class="col">
        David
      </div>
    </div>
  </div>

    <div>

    </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.tbl {
text-align: left;
white-space: nowrap;
}
.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
