![Mad Noodle + QMK + Via](https://i.imgur.com/aeldbRH.png)

# Mad Noodle VIA Support

Welcome to the Mad Noodle VIA Support repository! This repository is your go-to resource for VIA firmware and definitions for all Mad Noodle keypads. Follow the instructions below to ensure your keypad is up-to-date and ready for customization through VIA.

## Getting Started

Before you begin, make sure you have:
- A Mad Noodle keypad
- A USB cable to connect your keypad to your computer
- The files downloaded from this repository

## Firmware Update

> [!NOTE]
> **If you purchased your keypad in 2024 or later, it should already come with the latest VIA firmware. For older models, please update your firmware:**

1. Locate the 'Firmware' folder that corresponds to your specific keypad model in this repository.
2. Find the Via firmware .hex or .uf2 file associated with your keypad.
3. Install the firmware as usual, following the flashing instructions provided on [The Mad Noodle Flashing Guide](https://github.com/The-Mad-Noodle/QMK-Mad-Noodle-KeyPads/blob/main/README.md#flashing-firmware-to-your-mad-noodle-keypad) or our website for your keypad model.

## Setting Up VIA

You can configure your keypad using the VIA application, which is available as a Web App or as a standalone desktop application.

- Web App: [VIA Web App](https://usevia.app/)
- Desktop App: [VIA Releases](https://github.com/the-via/releases/releases)

## Configuring Your Keypad with VIA

Once you have VIA open:

1. Go to 'Settings' and enable the "Show Design tab" option.
2. Select the 'Design' tab, indicated by a paintbrush icon.
3. Under 'Load Draft Definitions', upload your `{keypad}.json` file from the 'Via Definitions' folder in this repository that corresponds to your specific keypad model.

Your keypad should now be fully functional with VIA. If you encounter any issues, try changing the 'Render Mode' to `3D` in the settings menu.

## Troubleshooting

In case of any difficulties, please refer to our troubleshooting guide or send an email to Jesse@themadnoodle.com.

## Support and Contact

For further assistance, please reach out through our [GitHub Issues](https://github.com/The-Mad-Noodle/Mad-Noodle-Via-Support/issues) or contact support directly at our website https://www.themadnoodle.com/.

Hope you love this new support we added for your Mad Noodle KeyPad!


