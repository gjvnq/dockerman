# dockerman

A simpleish app for managing docker and a homepage for the hosted services.

Basically a simpler and easier to use version portainer.

Planned features:
- [ ] Homepage with links and a few stats
- [ ] OAuth login
- [ ] Webauthn login
- [ ] Manage containers, images, volumes, and networks
- [ ] Read container logs
- [ ] Run stuff on containers
- [ ] Docker compose via git repos
- [ ] Auto update images
- [ ] Secrets storage - via obfuscation
- [ ] Secrets storage - via TPM

Possible features if I ever decide this project should usurp traefik's features:
- [ ] Green blue deployments
- [ ] DNS server for subdomains per service
- [ ] Automatic SSL certificate management
- [ ] Way to access services before they are fully live (useful for debugging)
