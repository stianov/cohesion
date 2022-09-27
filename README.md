# cohesion
An experimental project for creating a shared environment for several devices. Consists of three separate parts:

- cohesiond

Runs as a user-level daemon on your system, and synchronizes your system as you've configured it to. Runs a D-Bus service.
- cohesion-gnome

A libadwaita user interface for cohesiond. Communicates through D-Bus.
- cohesion-proxy

Coordinates the streams between your systems, and facilitates persistent information storage.
