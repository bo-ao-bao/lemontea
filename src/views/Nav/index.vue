<template>
  <div id="nav">
    <strong class="nav_logo">柠檬茶号</strong>
    <div class="nav_link">
      <ul>
        <li>
          <router-link to="">甲板</router-link>
        </li>
        <li>
          <router-link to="">货舱</router-link>
        </li>
        <li>
          <router-link to="">档案室</router-link>
        </li>
        <li>
          <router-link to="">传达室</router-link>
        </li>
        <li>
          <router-link to="">船长室</router-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Nav',
};
</script>

<style scoped lang="less">
#nav {
  width: 100%;
  height: 100px;

  border: 4px solid #00a1d6;
  border-radius: 18px;

  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-around;
  align-items: center;

}
.nav_logo{
  font-size: 3rem;
  font-weight:bold;
}
.nav_link{
  width: 50%;

  font-size: 20px;

  &>ul{
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-around;
    align-items: center;

  }
}
</style>
