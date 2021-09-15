<template>
  <div class="home">
    <stdpage :title="titlee" :contente="info" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import stdpage from "@/components/page.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    stdpage,
  },
  data() {
    return {
      titlee: "科协",
      info: "南京信息工程大学大学生科学技术协会（Students’ Association for Science and Technology),简称SAST，中文简称南信大校科协，成立于1992年。它是在校团委指导下，依照国家法规和大学生规章制度，独立开展活动的学生科技文化及学术研究的组织，也是校团委直属的组织中唯一一个技术类的学生组织。",
    };
  },
});
</script>
