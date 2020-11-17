<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
  *{
    margin: 0px;
    padding: 0px;
  }
  .el-table .cell {
    text-align: center
  }
  .el-table td, .el-table th.is-leaf {
  border-left: 1px solid rgba(211,217,223);
}
.el-table th.is-leaf {
  border-top: 1px solid rgba(211,217,223);
 }
.el-table:last-child{
  border-right: 1px solid rgba(211,217,223)!important;
} 
</style>
