<template>
  <a class="a-link">
    <div class="product-card">
      <div class="img-box">
        <img
          src="https://tbh-production.s3.ap-southeast-1.amazonaws.com/Product/1342274309/Images/16369625921803871654.jpg"
        />
      </div>
      <div class="detail-box">
        <p class="detail-name">Name</p>
        <div class="detail-price">Price</div>
        <div class="hidden-button">
          <button>Add to Cart</button> 
        </div>
      </div>
    </div>
  </a>
</template>
<script>
export default {
  data() {
    return {};
  },
};
</script>
<style scoped>
.a-link {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  box-sizing: border-box;
  border-style: solid;
  background-color: transparent;
  color: inherit;
  text-decoration: inherit;
  display: block;
  border-width: 1px;
  border-color: rgb(224, 223, 223);
  border-radius: 0.25rem;
  cursor: pointer;
  
}

.a-link:hover{
  box-shadow: 0 0 11px  rgba(33,33,33,.2);
  display: block;
  
 
}
.a-link:hover+.hidden-button{
display: block;
}

.product-card {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: inherit;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  height: 100%;
}
.img-box {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: inherit;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  position: relative;
  height: 10rem;
  padding-top: 0.5rem;
  padding-bottom: 1.5rem;
}
img {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: inherit;
  box-sizing: border-box;
  border-width: 0;
  border-color: #e2e8f0;
  border-style: solid;
  display: block;
  vertical-align: middle;
  max-width: 100%;
  margin-left: auto;
  margin-right: auto;
  height: auto;
  width: auto;
  max-height: 100%;
}
.detail-box {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: inherit;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  padding-top: 0.5rem;
}
.detail-name {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: inherit;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  margin: 0;
  white-space: nowrap;
  text-transform: capitalize;
  padding-bottom: 0.25rem;
  overflow: hidden;
  width: 100%;
  text-overflow: ellipsis;
}
.detail-price {
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  font-family: Avenir LT Pro, sans-serif;
  -webkit-font-smoothing: antialiased;
  --text-opacity: 1;
  color: inherit;
  box-sizing: border-box;
  border-width: 0;
  border-style: solid;
  border-color: #e2e8f0;
  white-space: nowrap;
  padding-top: 0.25rem;
  letter-spacing: -0.05em;
  font-size: 1.125rem;
  font-weight: 600;
  overflow: hidden;
  width: 100%;
  text-overflow: ellipsis;
}
button{
  -webkit-text-size-adjust: 100%;
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
    border-width: 0;
    border-style: solid;
    border-color: #e2e8f0;
    font-family: inherit;
    font-size: 100%;
    margin: 0;
    overflow: visible;
    text-transform: none;
    -webkit-appearance: button;
    background-image: none;
    cursor: pointer;
    padding: 0;
    line-height: inherit;
    --bg-opacity: 1;
    background-color: rgba(0,178,201,var(--bg-opacity));
    border-radius: .5rem;
    padding-top: .25rem;
    padding-bottom: .25rem;
    --text-opacity: 1;
    color: rgba(255,255,255,var(--text-opacity));
    width: 100%;
}
.hidden-button{
  -webkit-text-size-adjust: 100%;
    line-height: 1.5;
    font-family: Avenir LT Pro,sans-serif;
    -webkit-font-smoothing: antialiased;
    --text-opacity: 1;
    color: inherit;
    box-sizing: border-box;
    border-width: 0;
    border-style: solid;
    border-color: #e2e8f0;
    height: 3rem;
    padding-top: 1rem;
    display: none;
}

</style>
