# labrigart GTM Data Layer for Shopify
Join the WhatsApp Group for Support, Suggestions, and Bug Reports:

<a href="https://wa.me/8801749827904" target="_blank"><img src="images/whatsapp.png" width="150"/></a>

## How to use: 
1. Go to theme edit and paste GTM tracking code right after `<head>` tag in `theme.liquid` file
2. Inside the `snippets` folder create a new file as `labrigart-datalayer`. Copy all of the code from `labrigart-datalayer.liquid` of this repository to sinppet file `labrigart-datalayer.liquid`.
3. In the `theme.liquid` file after your GTM tracking code include `labrigart-datalayer.liquid` file as `{% render 'labrigart-datalayer' %}`
4. From shopify admin dashboard go to **Settings >> Checkout (Scroll Down) >> Additional scripts**. Copy all code from `checkout.liquid` from this repository to the  `Additional scripts` field. Change the example GTM example tracking ID **000-00000** to the real GTM ID
5. Depending on your Shopify theme, you might have to make some adjustments. For more information, please refer to the video below.

<a href="https://youtube.com/@trackingbygtm" target="_blank"><img src="images/play-png.png" width="100"/></a>
### 


## Events Included! ##
1. **view_item**
2. **view_item_list**
3. **add_to_cart**
4. **remove_from_cart**
5. **view_cart**
6. **begin_checkout**
7. **add_to_wishlist**
8. **purchase**
9. **newsletter_signup**
10. **search**
11. **phone_number_click**
12. **email_click**
13. Logged customer and on the checkout page customer details included as **customer** object with dataLayer
14. **Event Parameters:** currency, value, transaction_id, coupon, shipping, vat, items, item_list_name, item_list_id
15. **Items Parameters** item_id, item_name, quantity, price, discount, item_brand, item_category, item_variant, sku, item_list_name, item_list_id

## Features ##
With all general event tracking it also tracks following special events 
1. DataLayer event prefix
2. Quick View Event Tracking (as **view_item**)
3. Mini Cart and Dropdown Cart, Cart Drawer Tracking (as **view_cart**)
4. Shopify Direct Checkout Tracking ( as **add_to_cart** & **begin_checkout**)
5. Sticky Cart, Sidebar Cart, etc Tracking ( as **add_to_cart**)
6. Shopify Ajax Search Tracking ( as **search** )
7. Events was tacked by **Ajax Response** so no data discrepancy for edge cases
8. No **jQuery**, no **3rd Party Scripet** was included, all code was written ES6 Object Oriented Way. Added proper error handling so that there is no JS error


For more information, please watch the video below.

<a href="https://youtube.com/@trackingbygtm" target="_blank"><img src="images/play-png.png" width="100"/></a>
