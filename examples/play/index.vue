<template>
  <div style="margin: 20px;">
    <el-table
            style="width: 100%">
      <el-table-column
              prop="date"
              label="日期"
              width="150">
      </el-table-column>
      <el-table-column label="价值标签" :row-span="2">
        <el-table-column label="价值1">
        </el-table-column>
        <el-table-column label="价值2">
        </el-table-column>
      </el-table-column>
      <el-table-column label="价值标签1">
        <el-table-column label="价值3">
          <el-table-column label="价值4">
          </el-table-column>
          <el-table-column label="价值5">
          </el-table-column>
        </el-table-column>
        <el-table-column label="价值6">
          <el-table-column label="价值7">
          </el-table-column>
        </el-table-column>
      </el-table-column>
    </el-table>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        input: 'Hello Element UI!'
      };
    }
  };
</script>
