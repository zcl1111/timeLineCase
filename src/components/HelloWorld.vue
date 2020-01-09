<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div style="display:flex; width:900px;margin:100px auto;">
      <div style="flex:1">日志时间：</div>
      <timeLine :timeLineList = "timeLineList"></timeLine>
    </div>
  </div>
</template>

<script>
import timeLine from '../components/timeLine.vue'
export default {
  name: 'HelloWorld',
  components: { timeLine },
  data () {
    return {
      msg: 'Welcome to my channel',
      timeLineList: [{
      //             timestamp: '2008-10-6',
      //             info: '工作室更名为：西安拓美网络科技有限公司1'
      //           },{
      //             timestamp: '2009-10-6',
      //             info: '工作室更名为：西安拓美网络科技有限公司2'
      //           },{
      //             timestamp: '2010-10-6',
      //             info: '工作室更名为：西安拓美网络科技有限公司3'
      //           },{
      //             timestamp: '2011-10-6',
      //             info: '工作室更名为：西安拓美网络科技有限公司4'
      //           },{
      //             timestamp: '2012-10-6',
      //             info: '工作室更名为：西安拓美网络科技有限公司5'
      //           },{
                  timestamp: '2013-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司6'
                },{
                  timestamp: '2014-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司03'
                },{
                  timestamp: '2015-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司02'
                },{
                  timestamp: '2016-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司01'
                },{
                  timestamp: '2017-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司11'
                },{
                  timestamp: '2018-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司12'
                },{
                  timestamp: '2019-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司13'
                },{
                  timestamp: '2020-10-6',
                  info: '工作室更名为：西安拓美网络科技有限公司14'
                }],
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
