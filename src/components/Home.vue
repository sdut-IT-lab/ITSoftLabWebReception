<template>
  <div class="customers container">
    <div>
      <!-- Main component for a primary marketing message or call to action -->
      <div class="jumbotron">
        <h1>信息技术实验室报名系统</h1>
        <br />
        <p>在信息时代，作为理工科高校的学生，应该掌握一些能够体现自己价值的技术，为自己的未来生活或国家的科研增光添彩。
          在这里，你可以学习web前后端开发技术，开发出属于自己的网站或者app。
          在这里，你可以和搞学术研究的老师，一起参与数据挖掘，机器学习等科研项目，作为参与者发表论文。
          在这里，你可以和小伙伴组建局域网模拟网络攻防，学习机房的维护和网络安全知识。
        </p>
        <p>又或者你还不了解一些语言框架、技术。</p>
        <p>我们只要求你热忠于新技术，学习能力强，能快速适应新环境，能和志同道合的小伙伴每天提升自己，我们在这里等你！</p>
        <br>
          <router-link class="btn btn-lg btn-primary" to="/about">
          了解实验室 »
          </router-link>
        
      </div>
    </div>
    <div id="req" class="other">
      <!-- Example row of columns -->
      <div class="row">
        <div class="col-md-4">
          <h2>要求一</h2>
          <p>面向东校区的大一、大二的学生进行纳新。信管系技术能力突出者优先考虑。其他专业有基础者也优先考虑。</p>
        </div>
        <div class="col-md-4">
          <h2>要求二</h2>
          <p>性格开朗，善于交流。可承受一定压力，积极主动，自学较强。有一定技术基础优先，参与过信息学竞赛获算法比赛优先。</p>
        </div>
        <div class="col-md-4">
          <h2>要求三</h2>
          <p>对技术有一定热情。有责任心和团队合作精神优先，有科研意向者优先，能经常来实验室学习者优先。</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "customers",
  components: {
  },
  data() {
    return {
      alertMsg: "",
      customers: []
    };
  },
  methods: {
  
  },
  created() {
  },
  updated() {
    // this.fetchCustomers();
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.customers {
  margin-top: 100px;
}
th,
td {
  text-align: center;
  vertical-align: middle !important;
}
.other {
  margin-top: 70px;
}
.jumbotron p {
    font-size: 17px;
}
</style>
