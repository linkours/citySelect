<template>
  <div>
    <el-cascader
      :options="options"
      v-model="selectedOptions"
      :separator="'/'">
    </el-cascader>
  </div>
</template>

<script>
import options from '../../../static/test'
export default {
  data() {
    return {
      selectedOptions: [],
      options: options
    }
  }
}
</script>


