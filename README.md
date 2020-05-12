# free-gift-with-purchase
Add multiple free gifts to the cart automatically when purchasing a qualifying item
TO USE

Change the handles of your free gifts  (freezer-bag and free-bacon)
{% assign product = all_products['freezer-bag'] %}
{% assign product2 = all_products['free-bacon'] %}

Change the handle of your qualifying product from membership to your product handle

if ( cartItems[i].handle === 'membership' ) {
