---
title: Donate
date: 2017-01-01T00:00:00.000Z
permalink: /donate/index.html
eleventyNavigation:
  key: Donate
  order: 1
---
<style>
#priceLabelError,
#invoiceidError,
#descriptionError {margin: 0;}
</style>
Making dope shit takes a lot of time. Drop a couple bucks to keep me going.

<div id="smart-button-container">
  <div style="text-align: center"><label for="amount">How much money do you want to give me: </label><input name="amountInput" type="number" id="amount" value="" ></div>
    <p id="priceLabelError" style="display: none; color:red; text-align: center;">Please enter a price</p>
  <div id="invoiceidDiv" style="text-align: center; display: none;"><label for="invoiceid"> </label><input name="invoiceid" maxlength="127" type="text" id="invoiceid" value="" ></div>
    <p id="invoiceidError" style="display: none; color:red; text-align: center;">Please enter an Invoice ID</p>
  <div style="text-align: center"><label for="description">Oh shit, really? Why? </label><input type="text" name="descriptionInput" id="description" maxlength="127" value=""></div>
    <p id="descriptionError" style="display: none; color:red; text-align: center;">Please enter a description</p>
  <div style="text-align: center; margin-top: 0.625rem;" id="paypal-button-container"></div>
</div>

Donations are also accepted through the following platforms:
- Paypal: circadianriff@gmail.com
- Venmo: @circadianriff