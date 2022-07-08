{% section title="Create pricing model" %}

    {% step title="Create pricing model" %}
    	Build the pricing model with Products and Prices. Read the docs to learn more about pricing models.
    {% /step %}

{% /section %}

{% section title="Build your subscription page" %}

    {% step title="Add a pricing preview page" %}
    	Add a page to your site to display your product and offer your customers an option to subscribe to it. When they click the checkout button, they’re redirected to a Stripe-hosted Checkout page. The order is finalised when your customer is sent to the Checkout page – they can’t modify it after that point.
    {% /step %}

    {% step title="Add a checkout button" %}
        Add a button to your order preview page. Clicking this button redirects your customer to the Stripe-hosted Checkout page. The lookup_key was added when you created the product and price in the first step. When the form is submitted, it is used to retrieve the price_id on the server.
    {% /step %}

    {% step title="Add a success page" %}
        Create a success page for the URL you provided as the Checkout Session success_url to display order confirmation messaging or order details to your customer. Stripe redirects to this page after the customer successfully completes the checkout.
    {% /step %}

    {% step title="Add a customer portal button" %}
        Add a button to redirect to the customer portal to allow customers to manage their subscription. Clicking this button redirects your customer to the Stripe-hosted customer portal page.
    {% /step %}

{% /section %}
