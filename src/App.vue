<template>
  <div id="app">
    <Header></Header>
    <NavBar></NavBar>
    <BannerImage1></BannerImage1>
    <ImageGallery></ImageGallery>
    <FeaturedSection></FeaturedSection>
    <TextComponent title='Trending Tshirts'></TextComponent>
    <ProductComponent></ProductComponent>
    <ProductComponent></ProductComponent>
    <TextComponent title='Featured Products'></TextComponent>
    <ProductComponent></ProductComponent>
    <BannerImage2></BannerImage2>
    <TextComponent title='New Products'></TextComponent>
    <ProductComponent></ProductComponent>
    <TextComponent title='Best Selling'></TextComponent>
    <ProductComponent></ProductComponent>
    <CollectionGallery></CollectionGallery>
    <BannerImage3></BannerImage3>
    <DiscountBanner></DiscountBanner>
    <FeaturesRow></FeaturesRow>
    <SubscribeComponent></SubscribeComponent>
    <FooterComponent></FooterComponent>
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/> -->
  </div>
</template>

<script>
import FeaturedSection from './components/FeaturedSection.vue';
import Header from './components/Header.vue';
import ImageGallery from './components/ImageGallery.vue';
import NavBar from './components/NavBar.vue';
import ProductComponent from './components/ProductComponent.vue';
import CollectionGallery from './components/CollectionGallery.vue';
import DiscountBanner from './components/DiscountBanner.vue'
import FeaturesRow from './components/FeaturesRow.vue'
import SubscribeComponent from './components/SubscribeComponent.vue';
import FooterComponent from './components/FooterComponent.vue'
import BannerImage1 from './components/BannerImage/BannerImage1.vue';
import BannerImage2 from './components/BannerImage/BannerImage2.vue'
import BannerImage3 from './components/BannerImage/BannerImage3.vue'
import TextComponent from './components/HeaderText/TextComponent.vue'

export default {
  components: {
    Header,
    NavBar,
    ImageGallery,
    FeaturedSection,
    ProductComponent,
    CollectionGallery,
    DiscountBanner,
    FeaturesRow,
    SubscribeComponent,
    FooterComponent,
    BannerImage1,
    TextComponent,
    BannerImage2,
    BannerImage3
  }
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
