<template>
  <div style="">
    <div class="header-wrapper">
      <div class="nav-bar">
        <b-nav pills>
          <b-nav-item exact exact-active-class="active" to="/hello">נעים להכיר</b-nav-item>
          <b-nav-item exact exact-active-class="active" to="/irox-exercise">התרגיל באירוקס</b-nav-item>
          <b-nav-item exact exact-active-class="active" to="/more-projects">ועוד פרויקטים</b-nav-item>
          <b-nav-item exact exact-active-class="active" to="/my-resume">קורות החיים שלי</b-nav-item>
        </b-nav>

      </div>
    </div>

  </div>
</template>

<script>


// import {library} from '@fortawesome/fontawesome-svg-core'
// import {
//   faEllipsisV,
// } from '@fortawesome/free-solid-svg-icons'

// library.add(
    // faEllipsisV,
// );
export default {
  name: "Header",
  components: {},

  data() {
    return {}
  },
  props: {},


};
</script>

<style lang="scss" scoped>
.header-wrapper {

  .nav-bar {
    height: 70px;
    display: flex;
    align-items: center;
    font-size: 16px;
  }

  a {
    color: #1c2745;
  }

  .nav-pills .nav-link.active {
    background: transparent;
    color: #1c2745;
    font-weight: bold;
  }

}
</style>