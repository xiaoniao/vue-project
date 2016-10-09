<template>
  <div class="firstTable">
    <el-table
      :data="tableData"
      border
      style="width: 100%">
      <el-table-column
        property="date"
        label="日期"
        width="180">
      </el-table-column>
      <el-table-column
        property="name"
        label="姓名"
        width="180">
      </el-table-column>
      <el-table-column
        property="address"
        label="地址">
      </el-table-column>
    </el-table>
  </div>

</template>

<script>
export default {
  data () {
    return {
      tableData: [
        {
          date: '1',
          name: '1',
          address: '1'
        },
        {
          date: '2',
          name: '2',
          address: '2'
        },
        {
          date: '3',
          name: '3',
          address: '3'
        },
        {
          date: '4',
          name: '4',
          address: '4'
        }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.firstTable {

}

</style>
