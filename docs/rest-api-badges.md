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

Since reported much abusive activity on this Lavalink List, we have identified lots of unauthorized request, spams.. Was caused by those unstable lavalink list scrapers, likely they using invalid Regex. So to resolve this please use this valid Rest API instead scraping lavalink causing spams, this api contains All Lavalink from this Lavalink Lists!

### Lists REST API Docs

You can simply making request to these apis and get ```host```, ```port```, ```password```, ```secure```, and ```identifier```, there also ```version``` string which you want to pick for your supported clients, the API separated to SSL, NonSSL, even all of them...


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

### Badges Docs

After Lavalink Added here, you also can get an Stats Badges!!, here the breakdown:

```
https://lavalink-list-api.ajieblogs.eu.org/<unique-id>/badge/<type>
```
- `<unique-id>` - you can get unique-id at [**Lists REST API Docs**](https://lavalink.darrennathanael.com/rest-api-badges/#lists-rest-api-docs)<br />
- `<type>` - Badge type, supported badge type are: `Players`, `Status`, `Load`

Example: `https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Players` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Players) <br />

Example: `https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Status` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Status) <br />

Example: `https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Load` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/lava-v3-ajieblogs-eu-org-443/badge/Load)


If need any support or question you can join our Discord!
