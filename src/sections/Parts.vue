<template>
  <div class="section row">
    <div class="col-4">
      <h1 class="timberframing">Parts</h1>
      <p>
        The following are the different components we need to research, buy and use!
        Now you have to look at all the parts holistically. For example your wheels and battery size will dictate your range and top speed. The type of motor you use will have different characteristics for torque
      </p>
    </div>

    <div class="col-8">
      <div class="row">
        <div v-for="part in parts" class="col-md-2">
          <img class="icon" :src="`dist/icons/${part.icon}`" height="75">
          <span class="title">{{ part.title }} </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    parts: [
      {
        title: "Board",
        icon: "board.png"
      },
      {
        title: "Wheels",
        icon: "wheel.png"
      },
      {
        title: "Trucks",
        icon: "trucks.png"
      },
      {
        title: "Mount",
        icon: "mount.png"
      },
      {
        title: "Pulley",
        icon: "pulley.png"
      },
      {
        title: "Belts",
        icon: "belts.png"
      },
      {
        title: "Motor",
        icon: "motor.png"
      },
      {
        title: "Battery",
        icon: "battery.png"
      },
      {
        title: "Charger",
        icon: "charger.png"
      },
      {
        title: "Controller",
        icon: "controller.png"
      },
      {
        title: "Remote",
        icon: "remote.png"
      },
      {
        title: "Spark Protection",
        icon: "spark.png"
      },
      {
        title: "Wiring",
        icon: "wiring.png"
      },
      {
        title: "connectors",
        icon: "connectors.png",
      },
      {
        title: "Tools",
        icon: "tools.png",
      },
    ],
  })
};
</script>

