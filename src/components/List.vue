<template lang="kor">
    <div>
        <h5 @click="$router.push('/detail/0')">{{blogContents[0].title}}</h5>
        <p>{{blogContents[0].content}}</p>
        <p>{{blogContents[0].date}}</p>
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
