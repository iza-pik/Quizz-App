<template>
  <div class="question">
    <b-nav>
      <b-nav-item disabled>
        <strong>Quizz</strong>
      </b-nav-item>
      <b-nav-item disabled>Counter: {{numCorrect}}/{{numTotal}}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"]
};
</script>