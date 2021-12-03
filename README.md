# Accept Subscriptions/Recurring payments with PayPal in ASP.NET &amp; C#

![PayPal Subscriptions in ASP.NET](https://techtolia.com/PayPalSubscriptions/assets/images/PayPalNET.PNG)

With the PayPal Catalog Products API and PayPal Subscriptions API, you can create and manage subscriptions/recurring payments.

You can now model your business and product offerings in one place. Products define what you sell and Prices track how much and how often to charge.

Once you sign up and confirm your account, PayPal provides you with a set of API keys. Basically you get a “Client Id” key and a “Client Secret” key. 

Logging into the Developer Dashboard to get credentials and create sandbox accounts requires a developer, personal, or business account. Each account provides different levels of access to PayPal functionality. Developer Account: access sandbox, Personal Account: access sandbox+send and receive money, Business Account: access sandbox+send and receive money+go live

If you are looking a solution to integrate PayPal’s subscriptions to your website (ASP.NET Web Forms or ASP.NET Core MVC) that is builded with .Net & C#, look at that demo → https://techtolia.com/PayPalSubscriptions/

Elements are completely customizable. You can style Elements to match the look and feel of your site, providing a seamless subscription experience for your customers.

Create plans that charge users a fixed amount at regular intervals.

Offer your subscribers free or discounted trials to get more subscription signups.

Accept currencies for over 250 countries.

### How a Subscriptions integration works?
![PayPal How a Subscriptions integration works?](https://techtolia.com/PayPalSubscriptions/assets/images/subscriptions-how-to.svg)
1. Create a one-time subscription product and the plan(s) to offer to your consumers.
2. Present the PayPal button to create a subscription using either the Subscriptions API or the PayPal JavaScript SDK.
3. The button launches the PayPal Subscription experience.
4. The buyer agrees and subscribes.
5. The button calls PayPal Subscription API to create a subscription.
6. You show subscription confirmation to the buyer.

### Buyer consent flow with a PayPal account
![Buyer consent flow with a PayPal account](https://techtolia.com/PayPalSubscriptions/assets/images/subscriptions-paypal-account.svg)
1. Buyer clicks PayPal Subscribe.
2. Buyer logs in to PayPal.
3. Buyer agrees to the subscription terms and subscribes.
4. Buyer is redirected to the merchant page.

### Buyer consent flow with no PayPal account

![Buyer consent flow with no PayPal account](https://techtolia.com/PayPalSubscriptions/assets/images/subscriptions-no-paypal-account.svg)
1. Buyer clicks Debit or Credit Card.
2. Buyer enters card details, agrees to the subscription terms and subscribes either as a guest or by creating a PayPal account.
3. Buyer is redirected to the merchant page.
