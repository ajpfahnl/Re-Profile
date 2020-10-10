# Re-Profile
This application is based on Cloudfare's Wrangler tool and the [Router](https://github.com/cloudflare/worker-template-router) starter. 

You can check out the results [here](https://cloudfare-general.ajpfahnl.workers.dev). 

There are two main routes in this application: `/links` and anything else. Accessing `/links` returns a JSON list with three URLs and some basic metadata that I chose. Accessing the application from any other route will return an `HTMLRewriter`'ed webpage that depicts a dynamically rewritten version of [this](https://static-links-page.signalnerve.workers.dev) webpage.