<template>
  <v-flex xs6 sm1 md1>
    <div class="caption grey--text">
      {{ $t('ratio') }}
    </div>
    <div>{{ torrent.ratio }}</div>
  </v-flex>
</template>
<script>
export default {
  name: 'Ratio',
  props: ['torrent']
}
</script>
