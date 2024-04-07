<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Data Diri</template>
    Nama:Joner Okto Sanjogi Damanik<br>
    Tempat, Tanggal lahir: Sei Berlian 10-10-2003<br>
    Agama:kristen protestan
    <br>Gmail:yogiphone566@gmail.com
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
    SD: SDN 021 Senama Nenek<br>
    SMP: SMPN 3 Merek Raya<br>
    SMA: SMAN 1 Tapung Hulu<br>
    Perguruan Tinggi: UNIVERSITAS ISLAM RIAU
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skills</template>
    -HTML<br>
    -CSS<br>
    -PHP<br>
    -Java Script<br>
    -SQL
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontak</template>

    Ingin menghubungi saya? silahkan kontak dibawah ini<br>
    <a href="https://github.com/bangdamanik" target="_blank" rel="noopener"> Github</a><br>
    <a href="https://www.instagram.com/gii.damanik?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" rel="noopener"> Instagram</a><br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobi</template>
    -Bermain musik<br>
    -otomotif<br>
    -memancing
  </WelcomeItem>
</template>
