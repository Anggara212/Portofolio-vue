<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon/>
    </template>
    <template #heading>Nama</template>
    <li>Anggara Fabiano Putra Sugama</li>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Role</template>
    <li>Software Engineer</li>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Alamat</template>
    <li>Kampung Areman Rt 08 rw 08,<br> cimanggis, depok, jawa barat</li>   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
    <li>08212-480-4356</li>
    <li>0895-6168-888-040</li>
    <li>Anggarafabiano4@gmail.com</li>
  </WelcomeItem>
  
</template>
