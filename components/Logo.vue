<template>
  <div class="logo">
    <v-btn color="#2775a7" class="menu">
      <v-icon>mdi-flask-outline</v-icon>
    </v-btn>
    <v-btn color="#2775a7" class="menu">
      <v-icon style="left: 1px; top: 5px" size="29px">mdi-format-color-fill</v-icon>
    </v-btn>
    <v-btn color="#4c4c4c" class="menu">
      <v-icon>mdi-radio</v-icon>
    </v-btn>
    <v-btn color="#f0584a" class="menu">
      <v-icon size="23px">mdi-patreon</v-icon>
    </v-btn>
  </div>
</template>

<script>
export default {
  name: "Logo",
  data() {
    return {
    }
  }
}
</script>

<style scoped lang="scss">
.logo {
  width: 115px;
  height: 114px;
  padding: 3px 5px;
  border-radius: 7px;
  user-select: none;
  overflow: hidden;

  .menu {
    box-sizing: border-box;
    width: 48px;
    min-width: auto !important;
    min-height: 48px;
    margin: 3px 1px;
    box-shadow: none;

    .v-icon {
      color: white;
    }
  }
}
</style>