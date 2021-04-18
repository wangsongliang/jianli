<template>
  <div>
    <div class="zhuye">
        <h2>基本信息</h2>
        <div class="xinxi">
            <div class="zuoa">
                <div class="wenben">姓名：王松亮</div>
                <div class="wenben">性别：男</div>
                <div class="wenben">联系电话：18676717460</div>
                <div class="wenben">紧急联系人：江淑芬</div>
            </div>
            <div class="youa">
                <div class="wenben">全拼：wangsongliang</div>
                <div class="wenben">出生年月：1998/06/07</div>
                <div class="wenben">邮箱：1498750532@qq.com</div>
                <div class="wenben">联系电话：15907031877</div>
            </div>
		</div>
    </div>
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style>
    .zhuye{
		height: 600px;
		border-left: #b4cffe 2px solid;
		cursor: default;
	}
    .xinxi{
        overflow: hidden;
        font-size: 19px;
    }
    .zuoa{
        float: left;
    }
    .youa{
        float: right;
     }
     .wenben{
         margin-top: 30px;
      }
     .wenben:hover{
         font-size: 20px;
     }
</style>
