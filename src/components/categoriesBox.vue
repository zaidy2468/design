<template>
  <div class="price">
    <h3 class="text-price">Price</h3>
    <div class="price-box">
      <div class="price-enter">
        <input type="number" placeholder="0" class="price-input" />
        <span>$</span>
      </div>
      <span class="space"></span>
      <div class="price-enter">
        <input type="number" placeholder="200000" class="price-input" />
        <span>$</span>
      </div>
    </div>
  </div>
  <div data-v-d1f5d26e="" class="pt-8">
    <h3 class="text-lg">Categories</h3>

    <div class="pt-5">
      <div class="max-h-44 overflow-auto">
        <div class="flex-items-center-py-1-checkbox-wrapper">
          <input type="checkbox" class="w-5-h-5" value="true" />
          <span class="checkmark"></span>
          <span class="pl-4">DUNS</span>
        </div>
        <div class="flex-items-center-py-1-checkbox-wrapper">
          <input type="checkbox" class="w-5-h-5" value="true" />
          <span class="checkmark"></span>
          <span class="pl-4">DRS</span>
        </div>
        <div class="flex-items-center-py-1-checkbox-wrapper">
          <input type="checkbox" class="w-5-h-5" value="GMP" />
          <span class="checkmark"></span>
          <span class="pl-4">GMP</span>
        </div>
        <div class="flex-items-center-py-1-checkbox-wrapper">
          <input type="checkbox" class="w-5-h-5" value="ISO 13485" />
          <span class="checkmark"></span>
          <span class="pl-4">ISO 13485</span>
        </div>
        <div class="flex-items-center-py-1-checkbox-wrapper">
          <input type="checkbox" class="w-5-h-5" value="ISO 9001" />
          <span class="checkmark"></span>
          <span class="pl-4">ISO 9001</span>
        </div>
        <div class="flex-items-center-py-1-checkbox-wrapper">
          <input type="checkbox" class="w-5-h-5" value="ISO 9001:2015" />
          <span class="checkmark"></span>
          <span class="pl-4">ISO 9001:2015</span>
        </div>
      </div>
    </div>
    <!---->
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
};
</script>
<style scoped>
.price {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  padding-top: 2rem;
}

.text-price {
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
  margin: 0;
  font-weight: inherit;
  font-size: 1.125rem;
}
.price-box {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  display: flex;
  align-items: center;
  padding-top: 0.75rem;
}
.price-enter {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-style: solid;
  --bg-opacity: 1;
  background-color: rgba(242, 242, 242, var(--bg-opacity));
  border-color: rgba(35, 31, 32, 0.15);
  border-radius: 9999px;
  border-width: 1px;
  display: flex;
  align-items: center;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
  -webkit-appearance: none;
  margin: 0;
}
.price-input {
  -webkit-text-size-adjust: 100%;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  outline: none;
  border-color: #e2e8f0;
  font-family: inherit;
  font-size: 100%;
  margin: 0;
  overflow: visible;
  padding: 0;
  line-height: inherit;
  color: inherit;
  --bg-opacity: 1;
  background-color: rgba(242, 242, 242, var(--bg-opacity));
  text-align: center;
  width: 80%;
  border-radius: 9999px;
  padding-left: 0.75rem;
  padding-right: 0.75rem;
  padding-top: 2px;
}
span {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  --bg-opacity: 1;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
}
.space {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  --border-opacity: 1;
  border-color: rgba(200, 199, 199, var(--border-opacity));
  border-top-width: 1px;
  margin-left: 0.25rem;
  margin-right: 0.25rem;
  width: 1.25rem;
}
.pt-8 {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  padding-top: 2rem;
}
.text-lg {
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
  margin: 0;
  font-weight: inherit;
  font-size: 1.125rem;
}
.pt-5 {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  padding-top: 1.25rem;
}
.max-h-44 overflow-auto {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  max-height: 11rem;
  overflow: auto;
}
.flex-items-center-py-1-checkbox-wrapper {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  display: flex;
  align-items: center;
  padding-top: 0.25rem;
  padding-bottom: 0.25rem;
  position: relative;
  user-select: none;
  cursor: pointer;
}

.pl-4 {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: rgba(35, 31, 32, var(--text-opacity));
  font-size: 0.875rem;
  user-select: none;
  cursor: pointer;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  padding-left: 1rem;
}
</style>
