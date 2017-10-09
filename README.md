# OAuth-ing With Trello
=======================

Howdy 👾,

This project is an example application that authenticates a user with Trello's API via OAuth 1.0. Documentation on how Trello manages authorization can be found [here](https://developers.trello.com/authorize).

Trello provides third party developers the ability to allow users to authorize applications to take actions within Trello on their behalf. One way of doing this is via the OAuth 1.0 authorization flow.

To successfully run the project, you'll need to remix it and include your Trello API key and OAuth secret in 🗝.env file ↖️ over there. You can get your key and secret from Trello at: [https://trello.com/app-key](https://trello.com/app-key).

Once you've added your 🔑 and 🕵🏼, when you view the project live and click on the `Login with OAuth!` text the app will open Trello's authorization flow in a Pop-up. After you select the `Allow` ✅ button, the app will receive a token that can be used on your behalf to make requests to [Trello's API](https://developers.trello.com/advanced-reference).


To dive into the code, head on over to [`server.js`](https://glitch.com/edit/#!/trello-oauth?path=server.js)! 🚀