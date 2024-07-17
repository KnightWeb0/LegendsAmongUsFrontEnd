<script setup lang="ts"></script>

<template>
  <!-- <RouterView /> -->
  <VRow justify="center">
    <VCol cols="3" class="mt-2">
      <VCard width="250" height="350" flat variant="outlined" rounded="xl">
        <VRow>
          <VCol class="text-center">
            <VCardTitle class="text-h5"> Oli Sykes</VCardTitle>
            <VImg
              rounded="lg"
              class="mt-1 ml-6"
              cover
              width="200px"
              src="https://upload.wikimedia.org/wikipedia/commons/b/b3/2016_RiP_Bring_Me_the_Horizon_-_Oliver_Sykes_-_by_2eight_-_8SC6713.jpg"
            />
            <VCardText class="pa-0 mt-1"> Role: Artist</VCardText>
            <VCardText class="pa-0 mt-1"> Band:<strong> Bring Me The Horizon </strong> </VCardText>
            <VCardText class="pa-0 mt-1">
              Record label: <strong> Epitaph Records </strong>
            </VCardText>
          </VCol>
        </VRow>
      </VCard>
    </VCol>
  </VRow>
</template>
