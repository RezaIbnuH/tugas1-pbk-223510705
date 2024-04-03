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
    <template #heading>Tentang saya</template>

   Nama saya Muflif Fadhlurrochman biasa dipanggil akrab patur. Dan saya anak tunggal. Saya sedang menempuh pendidikan S1 di Universitas Islam Riau (UIR).
   Dan saya asli orang Pekanbaru dan lahir di Pekanbaru.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi Saya</template>

   Saya sangat senang Berolahraga dan semua olahraga adalah hobi saya. Tetapi yang paling sering dimainkan adalah
   Bermain futsal,bola,berenang,bulu tangkis dan masih banyak lagi.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Cita-Cita</template>

    Cita-cita saya waktu TK adalah menjadi tentara, sewaktu sd ingin menjadi pemain sepak bola profesional, sewaktu smp ingin menjadi pengusaha kaya, 
    sedangkan sekarang saya ingin menjadi orang yg kaya dan menjadi orang yg berguna bagi banyak orang. 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>

     <ul>
     <li>TK AZZUHRA ISLAMIC SCHOOL PEKANBARU</li>
     <li>SDIT AZZUHRA ISLAMIC SCHOOL PEKANBARU</li>
     <li>SMPIT AZZUHRA ISLAMIC SCHOOL PEKANBARU</li>
     <li>SMK MUHAMMADIYAH 2 PEKANBARU</li>
     
     </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Sosial Media</template>

    Instagram me: 
    <a href=" https://www.instagram.com/fathurmufliff?igsh=OHc5dTVpbzdtN2Vk&utm_source=qr" target="_blank" rel="noopener">Fathurmufliff</a>
  </WelcomeItem>
</template>
