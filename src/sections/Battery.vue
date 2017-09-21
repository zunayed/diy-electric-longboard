<template>
  <div class="col-12">
    <div class="section-title">
      <div class="timberframing">Battery
      <img class=""
        src="https://png.icons8.com/car-battery/ios7/75"
        height="35">
      </div>
    </div>
    <p>
      Entire books can be written about batteries! One of the most complex parts of the build there is quite a bit of information to digest. Please read up on battery safety as incorrect usage can be catastrophic! There are a few type of rechargeable batteries you can choose from. Lets go through some -

      Lipo

      Li-Ion
      I'm going with LIPO for my first build to get a better understanding of the tech, how to balance cells, maintenance. Li-Ion are more work to assemble and significantly more expensive. I definitely don't want to be out hundreds of dollars due to improper usage.

      I think everyone should consider using LIPO for their first build, Its a great way to learn about battery technology & balancing cells & battery handling/maintenance & wiring etc.
      A LiPo cell has a nominal voltage of 3.7V. So when you see "2S" it means there are 2 cells in series making it 7.4Vk
    </p>

    <div class="row">
      <div class="col-4 widget-large">
        <span class="line1"><i class="fa fa-check" aria-hidden="true"></i>LIPO</span>
        <hr/>
        <p>
          <ul class="pro-con-list">
            <li><i class="fa fa-plus"></i> Low cost</li>
            <li><i class="fa fa-plus"></i> No need for battery management system</li>
            <li><i class="fa fa-minus"></i> Needs a special balance charger to make full use of batteries</li>
            <li><i class="fa fa-minus"></i> Can come in different sizes</li>
          </ul>
        </p>
      </div>

      <div class="col-4 widget-large">
        <span class="line1">Li-Ion</span>
        <hr/>
        <p>
          <ul class="pro-con-list">
            <li><i class="fa fa-plus"></i> Comes in standard sizes</li>
            <li><i class="fa fa-plus"></i> Large companies invest heavily in battery research and you can reap those beefits</li>
            <li><i class="fa fa-plus"></i> More physically robust</li>
            <li><i class="fa fa-plus"></i> Can come in different sizes</li>
            <li><i class="fa fa-plus"></i> Less prone to thermal runaway and fire</li>
            <li><i class="fa fa-minus"></i> Much higher cost $$</li>
            <li><i class="fa fa-minus"></i> If you want to diy the battery pack you will need special tooling
            </li>
            <!--+ higher voltages? allow for less heat?-->
          </ul>
        </p>
      </div>

    </div>
  </div> <!-- end of battery-->
</template>

<script>
export default {};
</script>

