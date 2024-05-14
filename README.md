# Font Comparison Power App

This repository contains a Power App for comparing different fonts. The app allows users to preview and compare various fonts side by side, helping them make informed decisions about font choices for their projects.

## Purpose

The primary purpose of this app is to:
- Provide an easy way to compare different fonts.
- Allow users to visualize font differences in real-time.
- Help designers and developers make better font choices.

## Features

- **Font Preview**: Enter text and see how it looks in various fonts.
- **Comparison Mode**: Compare multiple fonts side by side.
- **Customization**: Change text size, color, and other properties to see how fonts perform under different conditions.

## Installation

To install and use the Font Comparison Power App:

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/font-comparison-power-app.git
   cd font-comparison-power-app
   ```

2. **Import the App into Power Apps**
   - Go to [Power Apps](https://make.powerapps.com/).
   - Click on "Apps" and then "Import canvas app".
   - Upload the `.msapp` file from the repository.

3. **Run the App**
   - Once imported, you can run the app directly from Power Apps.

## Usage

1. Open the Font Comparison app.
2. Enter the text you want to compare.
3. Select the fonts you want to compare from the list.
4. Adjust text properties like size and color as needed.
5. View the comparison results.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
   ```sh
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes.
   ```sh
   git commit -m "Add your feature description"
   ```
4. Push to your branch.
   ```sh
   git push origin feature/your-feature-name
   ```
5. Open a pull request with a detailed description of your changes.

## Controls
```
Screen1
└── ScreenContainer1
    ├── HeaderContainer1
    │   └── Label2
    ├── MainContainer1
    │   └── galFont
    │       └── Container1
    │           ├── lblKanji
    │           ├── lblEnglish
    │           ├── lblFont
    │           └── lblHiragana
    └── FooterContainer1
        ├── Slider1
        ├── Toggle1
        ├── Toggle2
        ├── Toggle3
        └── Toggle4
```

```plaintext:Formulas
FontTable = Table(
    {
        Index: 1,
        Font: Font.Arial,
        Label: "Arial"
    },
    {
        Index: 2,
        Font: Font.'Courier New',
        Label: "Courier New"
    },
    {
        Index: 3,
        Font: Font.'Dancing Script',
        Label: "Dancing Script"
    },
    {
        Index: 4,
        Font: Font.Georgia,
        Label: "Georgia"
    },
    {
        Index: 5,
        Font: Font.'Great Vibes',
        Label: "Great Vibes"
    },
    {
        Index: 6,
        Font: Font.Lato,
        Label: "Lato"
    },
    {
        Index: 7,
        Font: Font.'Lato Black',
        Label: "Lato Black"
    },
    {
        Index: 8,
        Font: Font.'Lato Hairline',
        Label: "Lato Hairline"
    },
    {
        Index: 9,
        Font: Font.'Lato Light',
        Label: "Lato Light"
    },
    {
        Index: 10,
        Font: Font.'Open Sans',
        Label: "Open Sans"
    },
    {
        Index: 11,
        Font: Font.'Open Sans Condensed',
        Label: "Open Sans Condensed"
    },
    {
        Index: 12,
        Font: Font.'Patrick Hand',
        Label: "Patrick Hand"
    },
    {
        Index: 13,
        Font: Font.'Segoe UI',
        Label: "Segoe UI"
    },
    {
        Index: 14,
        Font: Font.Verdana,
        Label: "Verdana"
    }
);
```
