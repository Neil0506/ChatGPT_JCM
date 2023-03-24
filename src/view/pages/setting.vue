<template>
  <div class="setting">
    <el-container>
      <el-header>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <h3>L V S H I H A O</h3>
          </div>
        </transition>
      </el-header>
      <el-main>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <span>
              基于开源项目修改，如有问题请联系小倪
            </span>
            <div>
              <a href="https://space.bilibili.com/326625155?spm_id_from=333.337.0.0">BliBili</a>---<a href="https://github.com/202252197/ChatGPT_JCM">GitHub</a>
            </div>
          </div>
        </transition>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      show: false,
    };
  },
  mounted() {
    this.show = true;
  },
};
</script>

<style>
  .transition-box {
    text-align: center;
    margin-top: 5%;
    color: #F2F6FC;
    font-size: 30px;
  }
  h1 {
    color: aliceblue;
    font-size: 80px;
  }
  a {
    text-decoration: none;
    color: #67C23A;
  }
</style>
