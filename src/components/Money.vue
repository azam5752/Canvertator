<template>
  <div>
    <h1>Hello</h1>
    <div class="container money">
      <div class="container-row">
        <select name="first-currency" id="first-currency">
          <option value="RUB">RUB</option>
          <option value="EUR">USD</option>
          <option value="UZS">UZS</option>
        </select>
        <input type="number" name="input-one" />
      </div>
      <div class="container-two">
        <button>Switch</button>
        <h4 id="baseValue">1 USD = 12 UZS</h4>
      </div>
      <div class="container-three">
        <select name="second-currency" id="second-currency">
          <option value="RUB">RUB</option>
          <option value="EUR">USD</option>
          <option value="UZS">UZS</option>
        </select>
        <input type="number" id="anount-two" placeholder="0" disabled />
      </div>
      <div class="container-four">
        <h4 id="lastlyUpdated">Lastly Updated 22.09.2023</h4>
      </div>
    </div>
  </div>
</template>

<script setup></script>
