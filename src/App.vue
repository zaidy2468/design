<template>
  <div class="text-dark">
    <div class="e-main">
      <div class="main">
        <div class="side-container">
          <div class="categories">
            <div class="categories-box">
              <div class="price-container">
                <categoriesBoxVue></categoriesBoxVue>
              </div>
            </div>
          </div>
        </div>
        <div class="primary-product-section">
          <div class="product-container">
            <div class="product-box">
              <HelloWorld />
              <HelloWorld />
              <HelloWorld />
              <HelloWorld />
              <HelloWorld />
              <HelloWorld />
              <HelloWorld />
              <HelloWorld />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import categoriesBoxVue from "./components/categoriesBox.vue";


export default {
  name: "App",
  components: {
    HelloWorld,
    categoriesBoxVue,
    
    
  },
};
</script>

<style scoped>
.text-dark{
  -webkit-text-size-adjust: 100%;
    line-height: 1.5;
    font-family: Avenir LT Pro,sans-serif;
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
    border-width: 0;
    border-style: solid;
    border-color: #e2e8f0;
    --text-opacity: 1;
    color: rgba(35,31,32,var(--text-opacity));
}
.side-container {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
}
.categories {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  position: relative;
}
.categories-box {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  font-size: 0.875rem;
  display: block;
  padding-right: 2.5rem;
  width: auto;
}
.price-container {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-style: solid;
  border-color: #e2e8f0;
  border-radius: 0.25rem;
  border-width: 1px;
  padding: 1.25rem;
  box-shadow: none;
  width: 20rem;
}
.e-main {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  margin-left: auto;
  margin-right: auto;
  max-width: 1400px;
  padding-left: 0;
  padding-right: 0;
  width: 90%;
}
.main {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  padding-bottom: 1.5rem;
  display: flex;
}
.product-box {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #ecf1f7;
  display: grid;
  grid-gap: 1rem;
  gap: 1rem;
  grid-template-columns: repeat(4, minmax(0, 1fr));
}
.product-container {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  padding-top: 3rem;
}
.primary-product-section {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  position: relative;
  margin-top: 0;
  width: calc(100% - 22.5rem);
}
</style>
