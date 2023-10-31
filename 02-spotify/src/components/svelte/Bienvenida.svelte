<script lang="ts">
  const now = new Date();
  const nowHour = now.getHours();

  let greeting = "Buenas noches";
  if (nowHour < 12) greeting = "Buenos días";
  else if (nowHour < 18) greeting = "Buenas tardes";
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>
