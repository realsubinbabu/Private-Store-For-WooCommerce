# Private-Store-For-WooCommerce

Make your shop page and all products on your online store private by requiring login or registration for viewing the content, limiting access only to logged-in customers.

This code snippet uses the template_redirect action to redirect unauthenticated users to the "My Account" page, when they try to access the shop page, product category pages, or product tag pages. The function wc_require_registration checks if the user is not logged in and trying to access the shop page, product category pages, or product tag pages. If these conditions are true, the code uses the wp_redirect function to redirect the user to the "My Account" page, using the get_permalink function to get the URL of the "My Account" page and the get_option function to get the page ID of the "My Account" page.

It's important to test the code snippet in a development or staging environment before using it on your live website, and also make sure that the page ID of the "My Account" page is correct.
