<script setup lang="ts">
defineOptions({
  name: "DeviceMonitoring"
})

// 页面逻辑将在后续开发中完善
</script>

<template>
  <div class="device-monitoring">
    <el-row :gutter="20">
      <el-col :span="24">
        <el-card class="monitoring-card">
          <template #header>
            <div class="card-header">
              <span>设备状态监控</span>
          
            </div>
          </template>

          <div class="device-status">
            <el-empty description="设备监测功能开发中..." />
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<style scoped lang="scss">
.device-monitoring {
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

  .monitoring-card {
    .card-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .device-status {
      min-height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
}
</style>
