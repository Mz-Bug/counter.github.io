<template>
  <q-page>
    <!-- <div class="q-pa-md">
      <q-card class="my-card">
        <div class="row">
          <q-btn color="white" text-color="black" label="Standard" />
          <q-icon
            class="bg-dark"
            color="white"
            name="arrow_left"
            v-for="size in ['xl']"
            :key="size"
            :size="size"
          />

          <q-btn color="white" text-color="black" label="Standard" />
          <q-btn color="white" text-color="black" label="Standard" />
        </div>
      </q-card>
    </div> -->

    <!-- <ul id="vert_menu">
      <a href="#" class="current">Campany</a>
    </ul>

    <div>
      <ul id="vert_menu">
        <a href="#" class="current">Person</a>
        <br />
        <a href="#" class="current">welfkwegfkwh</a>
      </ul>
    </div> -->
    
    <Basetimer></Basetimer>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import Basetimer from "components/BaseTimer.vue";
export default defineComponent({
  name: "IndexPage",
  components: {
    Basetimer,
  },
});
</script>
<style>
/* #vert_menu {
  overflow: hidden;
  width: 100%;
}
#vert_menu li {
  float: left;
}
#vert_menu a {
  padding: 8px 20px 8px 40px;
  float: left;
  text-align: center;
  text-decoration: none;
  font: normal 16px Myriad Pro, Helvetica, Arial, sans-serif;
  text-shadow: 0px 1px 0px #000;
  color: #e6e2cf;
  position: relative;
  text-shadow: 1px 0 0 #000;
  background: #525252;
  min-width: 181px;
  width: auto;
}

#vert_menu a::after,
#vert_menu a::before {
  content: "";
  position: absolute;
  top: 50%;
  margin-top: -19px;
  border-top: 19px solid transparent;
  border-bottom: 19px solid transparent;
  border-left: 1em solid;
  right: -1em;
}
#vert_menu a::after {
  z-index: 2;
  border-left-color: #525252;
} */
</style>
