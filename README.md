# car-key

Hosts the **public** key for the Tesla Fleet API integration in Home Assistant.

Served via GitHub Pages at `https://car.zsurzsan.com/.well-known/appspecific/com.tesla.3p.public-key.pem`.

- Only the public key lives here. The matching private key stays in Home Assistant (`config/tesla_fleet.key`) and must never be committed.
- `.nojekyll` lets GitHub Pages serve the `.well-known` folder.
- Vehicles pair with this key via `https://tesla.com/_ak/car.zsurzsan.com`.
