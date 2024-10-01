<script lang="ts">
  const currentTime = new Date();
  const currentHour = currentTime.getHours();

  let greeting = "";
  let name = "Juan";

  if (currentHour < 12) {
    greeting = "Buenos dias";
  } else if (currentHour < 18) {
    greeting = "Buenas tardes";
  } else {
    greeting = "Buenas noches";
  }
</script>

<h1 class="text-3xl font-bold">{greeting + " " + name}</h1>
