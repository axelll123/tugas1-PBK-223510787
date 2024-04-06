<script setup lang="ts">
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
    <template #heading>Tentang</template>
    Nama lengkap saya adalah Reza Ibnu Hidayah, saya tinggal di Jalan Karya Bersama Kecamata Bukit Raya Kota Pekanbaru,Riau Indonesia. Saat ini, saya tengah meniti perjalanan pendidikan sebagai seorang mahasiswa di Universitas Islam Riau, yang terletak di Jalan Kaharuddin Nst, Pekanbaru. Saya telah menjalani perjalanan pendidikan ini selama beberapa waktu dan saat ini berada di semester keempat. Di universitas ini, saya mengambil jurusan Teknik Informatika, yang telah menarik minat dan perhatian saya sejak awal. Berada di lingkungan akademik ini memberikan saya kesempatan untuk belajar dan berkembang di bidang yang saya minati, serta bertemu dengan berbagai orang yang berbagi minat dan aspirasi yang sama.
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
Riwayat pendidikan saya :

      <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/400ADAC7-2FF5-E011-AC8F-0177FFB6A670" target="_blank" rel="noopener">SDN 77 Pekanbaru</a></li>
      <li><a href="http://www.smpbabussalampekanbaru.sch.id/" target="_blank" rel="noopener">SMP Babussalam</a></li>
      <li><a href="https://sman14pekanbaru.sch.id/" target="_blank" rel="noopener">SMA Negeri 14 Pekanbaru</a></li>
      <li>Saat ini<a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a></li>

  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>
    Kemampuan merupakan kunci keberhasilan dalam berkomunikasi, bekerja sama, dan menyesuaikan diri di lingkungan profesional.    <ul>
      <li>Komunikasi</li>
      <li>Personal Branding</li>
      <li>Manajemen Waktu</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobi</template>
    Saya menyalurkan waktu luang saya dengan hobi saya:    <ul>
    <li>Badminton</li>
      <li>Musik</li>
      <li>Futsal</li>
</ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sosial Media</template>
Saya lumayan aktif di sosial media seperti Instagram, berikut adalah Instagram saya
   :<a href="https://www.instagram.com/reza_ibnu345" target="_blank">reza_ibnu345</a>
  </WelcomeItem>
</template>