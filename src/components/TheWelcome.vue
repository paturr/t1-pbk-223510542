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
    <template #heading>PENDIDIKAN</template>
    PENDIDIKAN YANG DITEMPUH<br> SD (004 Salo)<br> SMP (SMP-IT Al- Utsaimin Ridan Permai, Bangkinang)<br> SMA (SMAN 1 Bangkinang Kota)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>OLahraga</template>
    Ketertarikan dengan dunia Olahraga<br> Sepakbola
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>GAMES</template>
    Games Favorite untuk saat ini,<br> 1.eFootbal 2024<br> 2.Ball 8 Pool<br> 3.PUBG
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>MEDIA SOSIAL</template>
    -Instagram : @fathur.azrahman<br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>DATA DIRI</template>
    1.NAMA : Fathur Azrahman<br> 2.UMUR : 20<br> 3.MAHASISWA : Universitas Islam Riau<br> 4.JENIS KELAMIN : LAKI-LAKI
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
