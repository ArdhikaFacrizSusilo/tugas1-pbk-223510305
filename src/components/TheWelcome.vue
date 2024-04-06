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
    <template #heading>PROFIL</template>

    Perkenalkan saya adalah seorang Web Development, disini saya memiliki semangat juang yang tinggi dalam bekerja secara mandiri maupun team. Jika Anda mencari seseorang yang siap menghadapi tantangan dengan senyum di wajahnya, maka Anda telah menemukannya! wkwk : )
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>DATA PRIBADI</template>

    NAMA  : ARDHIKA FACRIZ SUSILO 
    <br>
    Tempat,Tgl lahir : Pekanbaru,12-12-2002
    <br>
    Jenis Kelamin : Laki-Laki
    <br>
    Agama : ISLAM
    <br>
    Status  : Belum menikah

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>PENDIDIKAN</template>

    saat ini saya kuliah di salah satu kampus swasta di Riau yaitu
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>. Sebelumnya saya bersekolah di SMA Negri <a href="" target="" rel="noopener">SMA 5 TUALANG</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>DATA KEMAMPUAN</template>

    Bahasa Pemograman : HTML/CSS, JavaScript, C++
    <br>
    Database  : SQL Server and MySQL
    <br>
    Desain  : Adobe Photoshop
    <br>
    Bahasa Percakapan : Bahasa Indonesia (Aktif) dan Bahasa Inggris (Pasif)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>SOSIAL MEDIA</template>

    <i class="bi bi-instagram"> Instagram : ardhikafacriz</i>
    <br>
    <i class="bi bi-facebook"> Facebook  : Ardhika Facriz</i>
  </WelcomeItem>
</template>
