<template>
  <div class="row">
      <div class="col-md-12">
      <h3>Quotes Added</h3>
      <div class="progress">
          <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemax="100"
          :style="{width: (quoteCounts / maxQuotes ) * 100 + '%'}"
          >
              {{quoteCounts}} / {{maxQuotes}}
          </div>
      </div>
      </div>
  </div>
</template>

<script>
export default {
    props: ['quoteCounts', 'maxQuotes']
}
</script>

<style>

</style>