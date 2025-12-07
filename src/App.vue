<style>
body {
  /* CHANGE BACKGROUND IMAGE FILE NAME AND PATH */
  background-image: url('@/assets/bby-background.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 120px;
}

footer {
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  /* UPDATED TO BEST BUY BLUE */
  background-color: #004694; 
  color: #fff;
  padding: 1rem;
  margin: 0;
}
/* ... (nav, ul, li, a styles remain the same) ... */

button {
  padding: 10px;
  /* UPDATED TO BEST BUY YELLOW */
  background-color: #FFC600; 
  color: #000; /* Use black text for yellow button */
  border: none;
  border-radius: 5px;
  cursor: pointer;
  height: 42px;
}

.product-card {
/* ... (styles remain the same) ... */
}

/* ... (other product-card styles remain the same) ... */

.product-controls button:hover {
  /* UPDATED TO BEST BUY BLUE */
  background-color: #004694;
}

/* ... (shopping-cart styles remain the same) ... */

.checkout-button {
  margin-top: 20px;
  padding: 10px 20px;
  /* UPDATED TO BEST BUY YELLOW */
  background-color: #FFC600;
  color: #000; /* Use black text for yellow button */
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.checkout-button:hover {
  /* UPDATED TO BEST BUY BLUE */
  background-color: #004694;
}
</style>