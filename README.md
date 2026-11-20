# Django digital marketplace

A marketplace prototype where sellers list digital products and buyers browse listings and start Stripe Checkout. Sellers can review sales by product and period, and buyers can revisit their purchases.

## Follow a purchase

1. Inspect the [product and order models](mysite/myapp/models.py).
2. Follow `create_checkout_session` and `payment_success_view` in the [checkout views](mysite/myapp/views.py).
3. Open the [seller dashboard](mysite/myapp/templates/myapp/dashboard.html) to see how sales are presented.

Built with Django, Stripe, Tailwind CSS and Chart.js.
