<template>
  <main>
    <h5>{{ fullName }}</h5>
    <div>
      <h4>El numero actual es...</h4>
      <h1>{{ count }}</h1>
      <button @click="count--">-</button>
      <button @click="count++">+</button>
    </div>
  </main>
</template>

<script>
export default {
  name: "CounterItem",
  data() {
    return {
      count: 0,
      fullName: "Sebas Puruguay",
    };
  },
};
</script>