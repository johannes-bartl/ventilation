# The Resistance of the Endotracheal Tube During Bronchoscopy

This project demonstrates the effects of catheter insertion into an endotracheal tube (ETT) during bronchoscopy in mechanically ventilated patients. It visualizes how airflow resistance increases and how this impacts ventilation under both volume- and pressure-controlled modes.

👉 **[Click here to view the interactive demo](https://johannes-bartl.github.io/ventilation/)**

<a href="https://johannes-bartl.github.io/ventilation/" target="_blank">
  <img src="docs/screenshot.png" alt="View Site" style="max-width: 100%; height: auto; border: 1px solid #ccc; margin-top: 20px;" />
</a>

## 🧪 Abstract

During bronchoscopy in mechanically ventilated patients, the insertion of a catheter into the endotracheal tube (ETT) drastically increases airflow resistance, potentially compromising ventilation. In this study, we quantify the nonlinear, flow-dependent resistance of ETTs with and without inserted bronchoscopy catheters. Pressure–flow relationships are measured across various tube–catheter combinations.

We find that:
- The resistance of unobstructed tubes scales with the inverse fourth power of the inner diameter.
- With catheters inserted, resistance scales more steeply—closer to the inverse sixth power of the effective diameter.

These increases in resistance lead to:
- **Dynamic hyperinflation and intrinsic PEEP** in volume-controlled ventilation
- **Reduced tidal volumes** in pressure-controlled ventilation

Simulations based on measured resistance values closely match experimental data from intensive care ventilators and lung simulators. This provides a practical framework for anticipating ventilation impairments during bronchoscopic procedures.

## 👨‍🔬 Authors

- Ben Fabry<sup>1</sup>, Navid Bonakdar<sup>1</sup>, Christian Kuster<sup>1</sup>
- Saskia Balling<sup>2</sup>, Frederick Krischke<sup>2</sup>, Roland Francis<sup>2</sup>

<sup>1</sup> Department of Physics, Friedrich-Alexander University Erlangen-Nürnberg, Germany  
<sup>2</sup> Clinic for Anesthesiology, University Clinics Erlangen, Germany

## 💻 Usage

To test or modify the simulation locally:
1. Clone the repository  
   `git clone https://github.com/johannes-bartl/ventilation.git`
2. Open `index.html` in your browser.

Or view it live at:  
➡️ **[https://johannes-bartl.github.io/ventilation/](https://johannes-bartl.github.io/ventilation/)**

## 📄 License

[MIT License](LICENSE)
