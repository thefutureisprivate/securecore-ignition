# securecore-ignition

> [!WARNING]  
> This Ignition configuration is tailored for my own systems. If you want to use it, you **must** at least change the password and SSH key of the admin user!

## What it does

- Installs Fedora CoreOS and rebases it to the default `securecore-main-hardened` image
- Configures gVisor as the default Podman runtime and enables automatic updates for gVisor and container images
- Enables Unbound with local DNSSEC validation
- Enables Secureblue Bash environment lockdown for all users
- Installs `qemu-guest-agent`
- Enrolls the Secureblue Secure Boot certificate
