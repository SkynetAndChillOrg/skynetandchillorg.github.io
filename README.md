# SkyNet Fleet Telemetry key host

This organization Pages repository serves the public key for a separate Tesla developer application at:

https://skynetandchillorg.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

Pages publishes from the `main` branch root. `.nojekyll` allows the `.well-known` path to be served.
Only the public PEM belongs here. Never commit the Tesla private signing key, OAuth secrets, or vehicle data.
This static site does not handle OAuth callbacks or exchange authorization codes.
