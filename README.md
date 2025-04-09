Updated README with full documentation

# DailyPivotZonesPro

A TradeStation strategy for intraday traders that automates the plotting of daily pivot points, Fibonacci extensions, and dynamically generated support/resistance zones.

## Features

- **Daily Pivot Points**: Classic pivot, R1/R2, S1/S2, calculated after market open (default 9:30 AM ET)
- **Customizable Alerts**: Visual, sound, and optional text/email alerts for each level
- **Fibonacci Extensions**: Auto-calculated based on previous day's high/low range
- **Shaded Support/Resistance Zones**: Filled bands using stacked lines for visual clarity
- **Time Zone Control**: Choose your local time zone to sync pivot calculations
- **Clean Chart**: Auto-clears previous drawings daily to prevent clutter
- **Fully Customizable**: Toggle plot visibility, alert levels, and zone settings
- **Built for Strategy Use**: Works as both an indicator and a foundation for automated strategies

## Installation

1. Open TradeStation Development Environment (TDE).
2. Create a new **Indicator** or **Strategy** and paste in the EasyLanguage code from this repository.
3. Save and compile.
4. Apply to your chart via `Insert > Strategy` or `Insert > Indicator`.

## Inputs

| Input | Description | Default |
|-------|-------------|---------|
| `ShowToday` | Toggle display of pivot levels | `true` |
| `EnableAlerts` | Enable alerts for level breaks | `true` |
| `ShowZones` | Show shaded zones (support/resistance) | `true` |
| `ZoneThickness` | Number of lines used to build each zone | `5` |
| `TimeZoneOffset` | Adjust for your local time zone vs EST | `0` |
| `Alert_Pivot`, `Alert_R1`, ... | Enable/disable alerts per level | `true/false` |

## Example Chart

*(Insert image here once uploaded)*

## License

Licensed under the MIT License. Feel free to modify, adapt, or contribute.

---

**Developed by:** `AI Mentor - Integrity With Purpose`  
**GitHub:** [https://github.com/dhughes91706/DailyPivotZonesPro](https://github.com/dhughes91706/DailyPivotZonesPro)
