---
title: Lavalink List REST API & Badges
description: REST API of Lavalink Lists.
hide:
  - navigation
---

<h1 style="font-family:Gotham SSm A;font-size: 2.0em;font-weight: 800;line-height:1.1;color: white;">Lavalink List REST API & Badges</h1>

<!-- inject image ad -->
<div data-ea-style="stickybox" class="dark horizontal" data-ea-publisher="darrennathanaelcom" data-ea-type="image"></div>

---

### Introductions

Since we have received reports of abusive activity on this Lavalink List, we have identified many unauthorized requests and spam. These issues were caused by unstable Lavalink list scrapers likely using invalid regex. To resolve this, please use the valid REST API instead of scraping the Lavalink list, as it contains all the Lavalink entries from this list!

### Lists REST API Docs

You can simply make requests to these APIs to obtain the ```host```, ```port```, ```password```, ```secure```, and ```identifier``` information. There is also a ```version``` string that you can select for your supported clients. The API is separated into SSL, NonSSL, and a combined list.

#### SSL List API
```bash
https://lavalink-list.ajieblogs.eu.org/SSL
```
#### NonSSL List API
```bash
https://lavalink-list.ajieblogs.eu.org/NonSSL
```
#### All List API
```bash
https://lavalink-list.ajieblogs.eu.org/All
```


Response example

```json
[
  {
    "unique-id": "lavalinkv3-id-serenetia-com-80",
    "identifier": "lavalinkv3-id-serenetia-com-80",
    "host": "lavalinkv3-id.serenetia.com",
    "port": 80,
    "password": "https://dsc.gg/ajidevserver",
    "secure": false,
    "version": "v3"
  },
  {
    "unique-id": "lava-v4-ajieblogs-eu-org-80",
    "identifier": "lava-v4-ajieblogs-eu-org-80",
    "host": "lava-v4.ajieblogs.eu.org",
    "port": 80,
    "password": "https://dsc.gg/ajidevserver",
    "secure": false,
    "version": "v4"
  },
{
    "unique-id": "And more...."
}
]
```
Additional Notes: The API list will be updated every 10 minutes to ensure that only online/active nodes are listed.

### Badges Docs

After adding Lavalink, you can also get Stats Badges! Below is the breakdown:

```
https://lavalink-list-api.ajieblogs.eu.org/<unique-id>/badge/<type>
```
- `<unique-id>` - You can get the unique-id from the [**Lists REST API Docs**](https://lavalink.darrennathanael.com/rest-api-badges/#lists-rest-api-docs)<br />
- `<type>` - Badge type. Supported badge types are: `Players`, `Status`, `Load`

Example: `https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Players` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Players) <br />

Example: `https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Status` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Status) <br />

Example: `https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Load` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Load)


If need any support or question you can join our [Discord](https://discord.gg/CFbwj7YCPb)!
