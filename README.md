# esp-uart-server
A UART-serving application for the ESP32 PICO.

## Instructions followed

### Prerequisites

1. Run `cargo install cargo-binstall`.
2. Run `cargo binstall espflash`.
3. Run `cargo install esp-generate`.

### Project generation

1. Run `esp-generate --chip esp32 <proj_name_here>`.
2. Select below options:
    1. `Enable unstable HAL features.`
    2. `Enable allocations via the esp-alloc crate.`
    3. `Enable Wi-Fi via the esp-wifi crate.`
    4. `Add embassy framework support.`
    5. `Flashing, logging and debugging (espflash)`
        1. `Use defmt to print messages.`
    6. `Options`
        1. `Add support for Wokwi simulation using VS Code Wokwi extension.`
        2. `Add GitHub Actions support with some basic checks.`
    7. `Optional editor config files for rust-analyzer`
        1. `Add rust-analyzer settings for Visual Studio Code`

