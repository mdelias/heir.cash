---
title: Store
layout: layouts/base.njk
subtitle: Purchase a word-list, starter kit, or WY SF today.
---

## <u> $2 - Physical BIP-39 Word-List</u>

+ GPG Signed BIP-39 wordlist

+ 5 pgs laminated card stock

+ Cut-out and pull 24+ words from hat
<br>
<style type="text/css"> .btcpay-form { display: inline-flex; align-items: center; justify-content: center; } .btcpay-form--inline { flex-direction: row; } .btcpay-form--block { flex-direction: column; } .btcpay-form--inline .submit { margin-left: 15px; } .btcpay-form--block select { margin-bottom: 10px; } .btcpay-form .btcpay-custom-container{ text-align: center; }.btcpay-custom { display: flex; align-items: center; justify-content: center; } .btcpay-form .plus-minus { cursor:pointer; font-size:25px; line-height: 25px; background: #DFE0E1; height: 30px; width: 45px; border:none; border-radius: 60px; margin: auto 5px; display: inline-flex; justify-content: center; } .btcpay-form select { -moz-appearance: none; -webkit-appearance: none; appearance: none; color: currentColor; background: transparent; border:1px solid transparent; display: block; padding: 1px; margin-left: auto; margin-right: auto; font-size: 11px; cursor: pointer; } .btcpay-form select:hover { border-color: #ccc; } #btcpay-input-price { -moz-appearance: none; -webkit-appearance: none; border: none; box-shadow: none; text-align: center; font-size: 25px; margin: auto; border-radius: 5px; line-height: 35px; background: #fff; } #btcpay-input-price::-webkit-outer-spin-button, #btcpay-input-price::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; } </style>
<style type="text/css"> input[type=range].btcpay-input-range { -webkit-appearance:none; width:100%; background: transparent; } input[type=range].btcpay-input-range:focus { outline:0; } input[type=range].btcpay-input-range::-webkit-slider-runnable-track { width:100%; height:3.1px; cursor:pointer; box-shadow:0 0 1.7px #020,0 0 0 #003c00; background:#f3f3f3; border-radius:1px; border:0; } input[type=range].btcpay-input-range::-webkit-slider-thumb { box-shadow:none; border:2.5px solid #cedc21; height:22px; width:22px; border-radius:50%; background:#0f3723; cursor:pointer; -webkit-appearance:none; margin-top:-9.45px } input[type=range].btcpay-input-range:focus::-webkit-slider-runnable-track { background:#fff; } input[type=range].btcpay-input-range::-moz-range-track { width:100%; height:3.1px; cursor:pointer; box-shadow:0 0 1.7px #020,0 0 0 #003c00; background:#f3f3f3; border-radius:1px; border:0; } input[type=range].btcpay-input-range::-moz-range-thumb { box-shadow:none; border:2.5px solid #cedc21; height:22px; width:22px; border-radius:50%; background:#0f3723; cursor:pointer; } input[type=range].btcpay-input-range::-ms-track { width:100%; height:3.1px; cursor:pointer; background:0 0; border-color:transparent; color:transparent; } input[type=range].btcpay-input-range::-ms-fill-lower { background:#e6e6e6; border:0; border-radius:2px; box-shadow:0 0 1.7px #020,0 0 0 #003c00; } input[type=range].btcpay-input-range::-ms-fill-upper { background:#f3f3f3; border:0; border-radius:2px; box-shadow:0 0 1.7px #020,0 0 0 #003c00; } input[type=range].btcpay-input-range::-ms-thumb { box-shadow:none; border:2.5px solid #cedc21; height:22px; width:22px; border-radius:50%; background:#0f3723; cursor:pointer; height:3.1px; } input[type=range].btcpay-input-range:focus::-ms-fill-lower { background:#f3f3f3; } input[type=range].btcpay-input-range:focus::-ms-fill-upper { background:#fff; } </style>
<form method="POST"  action="https://btcpay.wyo.llc/api/v1/invoices" class="btcpay-form btcpay-form--block">
  <input type="hidden" name="storeId" value="2bXg8ZDU4CNJEpKjNyXy7ztShh2gjs6tN1DWn9KjGpLr" />
  <input type="hidden" name="notifyEmail" value="safu@xbt.llc" />
  <div class="btcpay-custom-container">
    <input id="btcpay-input-price" name="price" type="text" min="0" max="none" step="any" value="null" style="width: 146px;" oninput="event.preventDefault();isNaN(event.target.value)? document.querySelector('#btcpay-input-price').value = null : event.target.value; if (this.value < undefined) {this.value = undefined; } else if(this.value > undefined){  this.value = undefined;}" onchange= "var el=document.querySelector('#btcpay-input-price'); var price = parseInt(el.value);  if(price< 5) { el.value = 5} else if(price> 100) { el.value = 100} document.querySelector('#btcpay-input-range').value = el.value" />
    <select name="currency">
      <option value="USD" selected>USD</option>
    </select>
    <input class="btcpay-input-range" id="btcpay-input-range" value="2" type="range" min="2" max="20" step="2" style="width:146px;margin-bottom:15px;" oninput="document.querySelector('#btcpay-input-price').value = document.querySelector('#btcpay-input-range').value" />
  </div>
<button type="submit" class="submit" name="submit" style="min-width:146px; min-height:40px; border-radius: 4px;border-style: none;background-color: #F59E0C;" alt="Pay with BtcPay, Self-Hosted Bitcoin Payment Processor"><span style="color:#fff">Buy now $2 ea.</span>
</button></form>

## <u>$35 - SAFU Self-Custody Kit</u>

+ Signed BIP-39 wordlist

+ 1pc. 18-8 stainless steel 1/4"-20 x 2", and cap nut

+ 30pc. 18-8 stainless steel washers 

+ 36pc. 1/8" steel alphanumeric stamping set

+ 3d printed Blockmit washer jig
<br>
<style type="text/css"> .btcpay-form { display: inline-flex; align-items: center; justify-content: center; } .btcpay-form--inline { flex-direction: row; } .btcpay-form--block { flex-direction: column; } .btcpay-form--inline .submit { margin-left: 15px; } .btcpay-form--block select { margin-bottom: 10px; } .btcpay-form .btcpay-custom-container{ text-align: center; }.btcpay-custom { display: flex; align-items: center; justify-content: center; } .btcpay-form .plus-minus { cursor:pointer; font-size:25px; line-height: 25px; background: #DFE0E1; height: 30px; width: 45px; border:none; border-radius: 60px; margin: auto 5px; display: inline-flex; justify-content: center; } .btcpay-form select { -moz-appearance: none; -webkit-appearance: none; appearance: none; color: currentColor; background: transparent; border:1px solid transparent; display: block; padding: 1px; margin-left: auto; margin-right: auto; font-size: 11px; cursor: pointer; } .btcpay-form select:hover { border-color: #ccc; } #btcpay-input-price { -moz-appearance: none; -webkit-appearance: none; border: none; box-shadow: none; text-align: center; font-size: 25px; margin: auto; border-radius: 5px; line-height: 35px; background: #fff; } #btcpay-input-price::-webkit-outer-spin-button, #btcpay-input-price::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; } </style>
<form method="POST"  action="https://btcpay.wyo.llc/api/v1/invoices" class="btcpay-form btcpay-form--block">
  <input type="hidden" name="storeId" value="2bXg8ZDU4CNJEpKjNyXy7ztShh2gjs6tN1DWn9KjGpLr" />
  <input type="hidden" name="notifyEmail" value="heir@xbt.llc" />
  <input type="hidden" name="price" value="35" />
  <input type="hidden" name="currency" value="USD" />
<button type="submit" class="submit" name="submit" style="min-width:146px; min-height:40px; border-radius: 4px;border-style: none;background-color: #F59E0C;" alt="Pay with BtcPay, Self-Hosted Bitcoin Payment Processor"><span style="color:#fff">Buy now $35</span>
</form>


## <u>$5 - Add-on Safu</u>

+ 1pc. 18-8 stainless steel 1/4"-20 x 2", and cap nut

+ 30pc. 18-8 stainless steel washers  
<br>
<style type="text/css"> .btcpay-form { display: inline-flex; align-items: center; justify-content: center; } .btcpay-form--inline { flex-direction: row; } .btcpay-form--block { flex-direction: column; } .btcpay-form--inline .submit { margin-left: 15px; } .btcpay-form--block select { margin-bottom: 10px; } .btcpay-form .btcpay-custom-container{ text-align: center; }.btcpay-custom { display: flex; align-items: center; justify-content: center; } .btcpay-form .plus-minus { cursor:pointer; font-size:25px; line-height: 25px; background: #DFE0E1; height: 30px; width: 45px; border:none; border-radius: 60px; margin: auto 5px; display: inline-flex; justify-content: center; } .btcpay-form select { -moz-appearance: none; -webkit-appearance: none; appearance: none; color: currentColor; background: transparent; border:1px solid transparent; display: block; padding: 1px; margin-left: auto; margin-right: auto; font-size: 11px; cursor: pointer; } .btcpay-form select:hover { border-color: #ccc; } #btcpay-input-price { -moz-appearance: none; -webkit-appearance: none; border: none; box-shadow: none; text-align: center; font-size: 25px; margin: auto; border-radius: 5px; line-height: 35px; background: #fff; } #btcpay-input-price::-webkit-outer-spin-button, #btcpay-input-price::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; } </style>
<form method="POST"  action="https://btcpay.wyo.llc/api/v1/invoices" class="btcpay-form btcpay-form--block">
  <input type="hidden" name="storeId" value="2bXg8ZDU4CNJEpKjNyXy7ztShh2gjs6tN1DWn9KjGpLr" />
  <input type="hidden" name="notifyEmail" value="safu2@xbt.llc" />
  <input type="hidden" name="price" value="5" />
  <input type="hidden" name="currency" value="USD" />
<button type="submit" class="submit" name="submit" style="min-width:146px; min-height:40px; border-radius: 4px;border-style: none;background-color: #F59E0C;" alt="Pay with BtcPay, Self-Hosted Bitcoin Payment Processor"><span style="color:#fff">Buy Now $5 ea.</span>
</button></form>

## <u>$399 - WY Statutory Foundation</u>

+ The Wyoming Statutory Foundation, combines elements of well- established trust and corporate law in Wyoming with classical elements of foundation legislation found in civil law jurisdictions, while also providing access to Wyoming’s privacy and asset preservation laws.
<br>
<style type="text/css"> .btcpay-form { display: inline-flex; align-items: center; justify-content: center; } .btcpay-form--inline { flex-direction: row; } .btcpay-form--block { flex-direction: column; } .btcpay-form--inline .submit { margin-left: 15px; } .btcpay-form--block select { margin-bottom: 10px; } .btcpay-form .btcpay-custom-container{ text-align: center; }.btcpay-custom { display: flex; align-items: center; justify-content: center; } .btcpay-form .plus-minus { cursor:pointer; font-size:25px; line-height: 25px; background: #DFE0E1; height: 30px; width: 45px; border:none; border-radius: 60px; margin: auto 5px; display: inline-flex; justify-content: center; } .btcpay-form select { -moz-appearance: none; -webkit-appearance: none; appearance: none; color: currentColor; background: transparent; border:1px solid transparent; display: block; padding: 1px; margin-left: auto; margin-right: auto; font-size: 11px; cursor: pointer; } .btcpay-form select:hover { border-color: #ccc; } #btcpay-input-price { -moz-appearance: none; -webkit-appearance: none; border: none; box-shadow: none; text-align: center; font-size: 25px; margin: auto; border-radius: 5px; line-height: 35px; background: #fff; } #btcpay-input-price::-webkit-outer-spin-button, #btcpay-input-price::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; } </style>
<form method="POST"  action="https://btcpay.wyo.llc/api/v1/invoices" class="btcpay-form btcpay-form--block">
  <input type="hidden" name="storeId" value="2bXg8ZDU4CNJEpKjNyXy7ztShh2gjs6tN1DWn9KjGpLr" />
  <input type="hidden" name="notifyEmail" value="heir@xbt.llc" />
  <input type="hidden" name="price" value="399" />
  <input type="hidden" name="currency" value="USD" />
<button type="submit" class="submit" name="submit" style="min-width:146px; min-height:40px; border-radius: 4px;border-style: none;background-color: #F59E0C;" alt="Pay with BtcPay, Self-Hosted Bitcoin Payments"><span style="color:#fff">Buy now $399</span>
</form>


## <u>$X - Custom Order</u>

+ Combination of the above items

+ Add together prices and pay invoice

<script>if(!window.btcpay){    var head = document.getElementsByTagName('head')[0];   var script = document.createElement('script');   script.src='https://btcpay.wyo.llc/modal/btcpay.js';   script.type = 'text/javascript';   head.append(script);}function onBTCPayFormSubmit(event){    var xhttp = new XMLHttpRequest();    xhttp.onreadystatechange = function() {        if (this.readyState == 4 && this.status == 200) {            if(this.status == 200 && this.responseText){                var response = JSON.parse(this.responseText);                window.btcpay.showInvoice(response.invoiceId);            }        }    };    xhttp.open("POST", event.target.getAttribute('action'), true);    xhttp.send(new FormData( event.target ));}</script><style type="text/css"> .btcpay-form { display: inline-flex; align-items: center; justify-content: center; } .btcpay-form--inline { flex-direction: row; } .btcpay-form--block { flex-direction: column; } .btcpay-form--inline .submit { margin-left: 15px; } .btcpay-form--block select { margin-bottom: 10px; } .btcpay-form .btcpay-custom-container{ text-align: center; }.btcpay-custom { display: flex; align-items: center; justify-content: center; } .btcpay-form .plus-minus { cursor:pointer; font-size:25px; line-height: 25px; background: #DFE0E1; height: 30px; width: 45px; border:none; border-radius: 60px; margin: auto 5px; display: inline-flex; justify-content: center; } .btcpay-form select { -moz-appearance: none; -webkit-appearance: none; appearance: none; color: currentColor; background: transparent; border:1px solid transparent; display: block; padding: 1px; margin-left: auto; margin-right: auto; font-size: 11px; cursor: pointer; } .btcpay-form select:hover { border-color: #ccc; } #btcpay-input-price { -moz-appearance: none; -webkit-appearance: none; border: none; box-shadow: none; text-align: center; font-size: 25px; margin: auto; border-radius: 5px; line-height: 35px; background: #fff; } #btcpay-input-price::-webkit-outer-spin-button, #btcpay-input-price::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; } </style>
<form method="POST"  onsubmit="onBTCPayFormSubmit(event);return false"  action="https://btcpay.wyo.llc/api/v1/invoices" class="btcpay-form btcpay-form--inline">
  <input type="hidden" name="storeId" value="2bXg8ZDU4CNJEpKjNyXy7ztShh2gjs6tN1DWn9KjGpLr" />
  <input type="hidden" name="jsonResponse" value="true" />
  <div class="btcpay-custom-container">
    <div class="btcpay-custom">
      <input id="btcpay-input-price" name="price" type="number" min="1" max="2100" step="1" value="1" style="width: 5em;" oninput="event.preventDefault();isNaN(event.target.value)? document.querySelector('#btcpay-input-price').value = 2 : event.target.value; if (this.value < 2) {this.value = 2; } else if(this.value > 1000){  this.value = 1000;}"  />
    </div>
    <select name="currency">
      <option value="USD" selected>USD</option>
    </select>
  </div>
<button type="submit" class="submit" name="submit" style="min-width:146px; min-height:40px; border-radius: 4px;border-style: none;background-color: #F59E0C;" alt="Pay with BtcPay, Self-Hosted Bitcoin Payment Processor"><span style="color:#fff">Custom Amount</span>
</button></form>
