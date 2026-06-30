XNP Linux
A POSIX-compliant meta-distribution for x86_64.
Install    Wiki    GitHub
Overview
XNP Linux is an independent, lightweight meta-distribution built for absolute control. It is designed to run seamlessly inside any host environment via chroot hosting.

Package System
The system utilizes xnp, a package manager written entirely in POSIX sh. It isolates build environments and maintains system cleanliness through a straightforward two-step workflow:

xnp -b [package] # Build package from source
xnp -i [package] # Install package into system
More documentation, core repositories, and deployment guidelines can be found in the official installation section.
