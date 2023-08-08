# Cloudflare-Proxy-Bing
Proxy service with Cloudflare Workers for BingAI

If you see an error message like 200, message='Invalid response status', url=URL('wss://sydney.bing.com/sydney/ChatHub'), you need to set up a proxy service with Cloudflare Workers. Here are the steps to do that:


1.  Go to [this link](https://dash.cloudflare.com/) and sign in or sign up for a Cloudflare account.
2.  In the sidebar, select `Workers & Pages`.
3.  On the page that opens, click `Create application`.
4.  Choose `Create Worker`.
5.  Give your worker a name and click `Deploy`.
6.  On the worker detail page, click `Quick edit`.
7.  Copy all the code from `worker.js` and paste it over the existing code in `worker.js`. Then click `Save and deploy`.
8.  Copy the worker domain that looks like `xxxx-xxxx-xxxx.xxxx.workers.dev` (not a URL like `https://xxxx-xxxx-xxxx.xxxx.workers.dev/`, please remove the prefixes and suffixes) and paste it as `Wss Domain` in the code for BingAI. Then click `Save`.

