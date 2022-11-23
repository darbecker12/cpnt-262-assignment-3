<script>
export default {
  data() {
    return {
      teams: {
        team1: 'Calgary Flames',
        team2: 'Edmonton Oilers',
        team3: 'Vancouver Canucks',
        team4: 'Winnepeg Jets',
        }
      }
    }
  }
</script>

<template>

  <ul>
    <li v-for="value in teams">
      {{ value }}
    </li>
  </ul>

</template>

<style>
ul{
  margin-top: 1rem;
  border: 1px solid blue;
  background: lightcyan;
}
li{
  font-size: 15px;
  gap: 5px;
  color: black;

}
</style>