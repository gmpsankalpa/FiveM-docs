---
title: Monetizing your server
weight: 461
---

Monetize your in-game content, sell resources and support FiveM through our official server monetization partner, Tebex. With Tebex you can set up your own unique and secure webstore within minutes. They are our _exclusive_ provider for server monetization.

Getting started
---------------

### 1. Register an account

In order to use Tebex, you must set up an account on [their website][tebex].

### 2. Set up your first store

Create your first webstore after registering.

- Select FiveM as your game server and confirm.
- Name your webstore and select a currency.
- Accept the terms and rules.

### 3. Configure Tebex on your server

To activate Tebex on your server, you must add your Tebex key to your `server.cfg`.

- After completing the previous step, you will see a few options to link your store with.
- Select `Game Server` and continue.
- Copy and add the presented `sv_tebexSecret` to your `server.cfg`.
- When you restart your server, you should see the `Authenticated with Tebex: <your store>` message in your server console.

### 4. Create content!

Now your store is linked and running, it's your turn to create something great. Start [adding packages][tebex-docs-packages] to your store, [reward your players][commands] in-game and be creative.


Profit and "ToS" Compliance
---------------------------

Using Tebex counts as "built-in commerce functionality" as described in the FiveM Platform Service Agreement, commonly known in our community as the [Terms of Service][terms]. So yes, **profit is allowed**.

> Despite being our monetization partner, we might instill additional terms to disallow selling of Rockstar game content (built-in DLC vehicles, etc.) and mandate tracking of earned vs. purchased virtual currency in order to prevent purchased virtual currency from being used to violate any party's copyright, including Rockstar's.

Frequently Asked Questions
--------------------------

### Is it allowed to sell resources?
Yes! With Tebex you are allowed to sell resources, as long as they abide by the FiveM [Terms of Service][terms]. Violation or malicious intent will result in blacklisting of the resource.

### What authentication methods can be used?
Purchases must be done using a [FiveM account][forums].

Support
-------

- [Forums][forums]
- [Tebex Documentation][tebex-docs]

What's next?
------------

- [Create an in-game callback after a purchase][commands]
- [Check for previously bought player purchases][functions]

[forums]: https://forum.cfx.re/
[tebex]: https://www.tebex.io/fivem
[tebex-docs]: https://docs.tebex.io/store/
[tebex-docs-packages]: https://docs.tebex.io/store/key-features/how-to-create-packages
[commands]: ./commands
[functions]: ./functions
[terms]: https://fivem.net/terms
