<template>
  <div class="device-map">
    <div class="page-header">
      <h2>设备地图</h2>
      <p>在地图上查看设备分布和状态</p>
    </div>
    
    <el-row :gutter="20">
      <el-col :span="18">
        <el-card class="map-card">
          <template #header>
            <div class="card-header">
              <span>设备分布地图</span>
              <div class="map-controls">
                <el-button type="primary" size="small">定位</el-button>
                <el-button type="success" size="small">刷新</el-button>
              </div>
            </div>
          </template>
          
          <div class="map-container">
            <el-empty description="地图功能开发中..." />
          </div>
        </el-card>
      </el-col>
      
      <el-col :span="6">
        <el-card class="device-list-card">
          <template #header>
            <span>设备列表</span>
          </template>
          
          <div class="device-list">
            <el-empty description="暂无设备数据" />
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script setup lang="ts">
defineOptions({
  name: "DeviceMap"
})

// 页面逻辑将在后续开发中完善
</script>

<style scoped lang="scss">
.device-map {
  padding: 20px;
  
  .page-header {
    margin-bottom: 20px;
    
    h2 {
      margin: 0 0 8px 0;
      color: var(--el-text-color-primary);
    }
    
    p {
      margin: 0;
      color: var(--el-text-color-regular);
    }
  }
  
  .map-card {
    .card-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      
      .map-controls {
        display: flex;
        gap: 8px;
      }
    }
    
    .map-container {
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: var(--el-fill-color-lighter);
      border-radius: 4px;
    }
  }
  
  .device-list-card {
    .device-list {
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
}
</style>