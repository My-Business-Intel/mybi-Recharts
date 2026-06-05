# MyBI Recharts — a MyBI chart plugin

An interactive chart pack for **MyBI**, built on
[Recharts](https://recharts.org). It adds a **Recharts** panel to the dashboard
that binds to your selected dataset and draws **bar / line / area / pie** charts —
with hover tooltips, a toggleable legend, and a brush on line/area charts.

Each chart library is its own MyBI plugin; this is the Recharts one.

> **First-party MyBI plugin.** It reads your data **read-only**, only when allowed
> in the project's plugin settings. It never modifies your data.

## What it does

- **Chart types:** Bar, Line, Area, Pie.
- **Binding:** pick an X (category) column and one or more Y (measure) columns from
  the selected dataset.
- **Interactive:** hover tooltips, legend toggle, and a brush on line/area charts.
- Clicking a category highlights related visuals on the dashboard.

## Install in MyBI

Install **Recharts Charts** from the in-app marketplace, or download
`charts-recharts.mybiplugin` from the [latest release](../../releases/latest) and
import it in MyBI (**Extensions → Import plugin**).

## License

Apache-2.0
