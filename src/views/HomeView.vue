<template>
  <div class="home">
    <HeaderEcom />
    <HeroEcom />
    <WomanBannerEcom />
    <InstaEcom />
    <PartnerEcom />
    <FooterEcom />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderEcom from '@/components/HeaderEcom.vue';
import HeroEcom from '@/components/HeroEcom.vue';
import WomanBannerEcom from '@/components/WomanBannerEcom.vue';
import InstaEcom from '@/components/InstaEcom.vue';
import PartnerEcom from '@/components/PartnerEcom.vue';
import FooterEcom from '@/components/FooterEcom.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderEcom,
    HeroEcom,
    WomanBannerEcom,
    InstaEcom,
    PartnerEcom,
    FooterEcom
  }
}
</script>
