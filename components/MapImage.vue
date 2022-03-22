<template>
  <div>
    <h1>Map Image</h1>
    <img
      src="https://maps.geoapify.com/v1/staticmap?style=osm-bright-grey&width=600&height=400&center=lonlat:3.394179,6.455057&zoom=6.8713&marker=lonlat:3.394179,6.455057;type:material;color:%231f63e6;size:x-large;icon:cloud;icontype:awesome;whitecircle:no&apiKey=d548c5ed24604be6a9dd0d989631f783"
    />
  </div>
</template>


<script>
export default {
  name: "MapImage",
  data() {
    return {};
  },
};
</script>