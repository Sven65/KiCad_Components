# KiCad Components

Custom KiCad symbols and footprints for various electronic components.

Each component includes accurate footprints based on real measurements and datasheets, along with corresponding schematic symbols.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/kicad-components.git
   ```

2. In KiCad, add libraries:
   - **Symbols:** `Preferences → Manage Symbol Libraries`
   - **Footprints:** `Preferences → Manage Footprint Libraries`
   
3. Browse to the component folder you need under `Components/`

## Structure

```
Components/
└── Component_Name/
    ├── footprint/
    │   └── component.kicad_mod
    ├── symbol/
    │   └── component.kicad_sym
    ├── images/
    └── README.md
```

## Components

Browse the `Components/` folder to see all available parts. Each component has its own README with specifications and pinout information.

## License

Licensed under the [MIT License](LICENSE)