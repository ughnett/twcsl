# Store Product Price Zero Remove

### Version 0.1.1

#### SS Versions 7.1, 7.0 ([Brine template family][1], [Five][2], [Montauk template family][3])

#### v7.1 Fluid Engine Compatible : Not Applicable

---

## Install

* Install **[Store Price Change][4]**.
  
* In the store price change code after the searchReplaceText example lines add
  the following code.
  
  ```javascript
          '$0.00' : sppzr, // store product price zero remove
  ```
  
* Add code from **[store product price zero remove.html][5]** to
  Store Settings > Advanced > Page Header Code Injection for the store page
  **before** the **store price change** code. Read the code for any instructions
  within.

## Note

If your currency symbol is not dollar sign then use the one set for your site.

## Make a Donation

Please consider [making a donation][6].

## Changes

* **2022-10-10**

  * check text includes instead of ==
  * bumped version to 0.1.1
  
* **2022-08-23**

  * initial version

[1]: https://support.squarespace.com/hc/en-us/articles/212512738-Brine-template-family
[2]: https://support.squarespace.com/hc/en-us/articles/206544937-Five-template
[3]: https://support.squarespace.com/hc/en-us/articles/205815568-Montauk-template-family
[4]: https://github.com/tomsWebConsulting/twcsl/tree/main/Store%20Price%20Change#store-price-change
[5]: store%20product%20price%20zero%20remove.html#L1
[6]: https://github.com/tomsWebConsulting/twcsl#make-a-donation
