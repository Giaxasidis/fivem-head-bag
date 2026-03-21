## FiveM Head Bag Interaction System

**Head Bag Interaction System** is a professional, lightweight script for FiveM that allows players to apply or remove head bags on other players via a clean and intuitive menu. Perfect for roleplay servers, it provides realistic interactions, visual overlays, and full client-server management for a smooth and safe gameplay experience.
This script is built using the **ESX framework**, is modular, easy to configure, and fully extendable for future features.

## Features

* [x] Apply a head bag to nearby players using an in-game menu.
* [x] Remove head bags from players who already have one applied.
* [x] Clean and professional NUI overlay for visual indication.
* [x] Triggered via a usable item (e.g., `headbag`) for easy activation.
* [x] Client-server architecture for secure, synchronized application.
* [x] In-game notifications for professional player feedback.
* [x] Fully modular design for easy extension and maintenance.

## How It Works

1. **Detect Nearby Players:**
   The script detects players within a 2-meter radius and allows applying or removing a head bag.

2. **Apply Head Bag:**
   A head bag object (`prop_money_bag_01`) is created and attached to the target player’s head with proper coordinates and rotation for a realistic appearance.

3. **Overlay Display:**
   The NUI overlay automatically displays when a head bag is applied, providing a clean visual indicator.

4. **Remove Head Bag:**
   Head bags can be safely removed either by the player themselves or by another player, ensuring smooth interactions.

5. **Persistent Handling:**
   The head bag is automatically removed on player respawn (`playerSpawned`) to prevent glitches or ghost objects.

## Installation & Setup

### Prerequisites

* A FiveM server running the ESX framework.
* Basic knowledge of installing resources on GTA V servers.

### Installation Steps

1. Clone or download this repository.
2. Place the resource folder into your server’s `resources` directory.
3. Add the following line to your `server.cfg`:

```cfg
start headbag_system
```

4. Restart the server or the resource to apply changes.

## Usage

* Use the item `headbag` to open the interaction menu.
* Select whether to apply or remove the head bag from nearby players.
* The NUI overlay appears automatically when a head bag is applied.
* Fully client-server synchronized for reliable gameplay.

## Permissions & Compatibility

* No special permissions required.
* Compatible with any FiveM server using ESX framework.
* Works perfectly in multiplayer roleplay environments.

## Contributing

Contributions, bug reports, and feature requests are welcome! Please:

* Fork the repository and create a feature branch.
* Commit your changes with clear, descriptive messages.
* Submit pull requests with detailed explanations.
* Report issues via GitHub Issues.

## License

This project is licensed under the **Apache-2.0 License**.   
It allows full usage, modification, and distribution with minimal restrictions.
See [LICENSE](./LICENSE) for full details.

##  Author

Created and maintained by **KaloudasDev**.  
If you find this project useful, a star star on the repository would be greatly appreciated!
