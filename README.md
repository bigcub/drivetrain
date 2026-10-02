# Inside the Drivetrain

An interactive Three.js teaching assembly showing how a piston, gudgeon pin, connecting rod and crankshaft transmit motion to a clutch and gearbox input shaft.

Live site: https://drivetrain.dej.app

## Run locally

Requires Node.js 22.13 or newer.

```sh
npm ci
npm run dev:pages
```

## GitHub Pages

The Pages workflow builds the static application with `npm run build:pages` and deploys `dist-pages` on each push to `main`. Choose GitHub Actions as the Pages source and set the custom domain to `drivetrain.dej.app`.

DNS: create a CNAME record for `drivetrain` pointing to `bigcub.github.io`. Enable HTTPS in Pages once the certificate is issued.

## Teaching model

Geometry is generated procedurally. This is a simplified single-cylinder teaching model, not a production CAD assembly or service specification. Release travel, oil-film thickness and worn-bearing movement are exaggerated for teaching.
