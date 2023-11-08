<template lang="kor">
    <div>
        <h5>{{blogContents.title}}</h5>
        <p>{{blogContents.content}}</p>
        <p>{{blogContents.date}}</p>
        <p>{{blogContents.number}}</p>
    </div>
</template>
<script>
export default {
  name: "ListVue",
  props: {
    blogContents: Array,
  },
};
</script>
<style lang="kor"></style>
