<template>
  <div class="row g-5 g-xl-8">
    <div class="col-xl-4">
      <StatisticsWidget5
        widget-classes="card-xl-stretch mb-xl-8"
        icon-name="basket"
        color="danger"
        icon-color="white"
        title="Shopping Cart"
        description="Lands, Houses, Ranchos, Farms"
      />
    </div>

    <div class="col-xl-4">
      <StatisticsWidget5
        widget-classes="card-xl-stretch mb-xl-8"
        icon-name="cheque"
        color="primary"
        icon-color="white"
        title="Appartments"
        description="Flats, Shared Rooms, Duplex"
      />
    </div>

    <div class="col-xl-4">
      <StatisticsWidget5
        widget-classes="card-xl-stretch mb-5 mb-xl-8"
        icon-name="chart-simple-3"
        color="success"
        icon-color="white"
        title="Sales Stats"
        description="50% Increased for FY20"
      />
    </div>
  </div>

  <div class="g-5 gx-xxl-8">
    <TablesWidget10 />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import StatisticsWidget5 from "@/components/widgets/statsistics/Widget5.vue";
import TablesWidget10 from "@/components/widgets/tables/Widget10.vue";

export default defineComponent({
  name: "dashboard-main",
  components: {
    StatisticsWidget5,
    TablesWidget10,
  },
});
</script>
