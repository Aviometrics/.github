# Aviometrics

We make **ParaBaro**: instruments that measure the pressure inside a paraglider's wing during flight, and record it
with barometric pressure and GPS in a flight log. We're a small team in Northern Ireland.

Most of our work is private. This page is for developers, weather services and research partners who want to work
with the data our devices produce.

## ParaBaro Bridge SDK

The **Bridge** is a small flight recorder that a pilot carries on the riser. The SDK describes what protocol-1.0
firmware sends over Bluetooth and records to its IGC files, with a Python reference library, command-line tools and a
simulator, so you can start without hardware.

- Open specifications (CC BY 4.0) and code (Apache 2.0), free to use in commercial products
- Covers air pressure, sensor temperature, battery, GPS, standard NMEA sentences and IGC files
- Public release is coming soon. Partners can ask for early access now (see below).

The Bridge is a flight recorder, not a primary flight instrument. Its pressure is measured at the sensor port and
not corrected for airflow. Its IGC files are not signed: check your competition's rules before submitting one. No
released firmware implements the protocol the SDK describes yet.

## Working with us

| Level | What you get | What it takes |
|---|---|---|
| Open | The SDK: specifications, code, tools, example data | Nothing. Use it under its licences |
| Partner | Material beyond the SDK, scoped to a joint project | An NDA and an agreed scope |
| Data collaboration | Flight data from real pilots | A data-sharing agreement, and each pilot's written consent to that specific use |

Flight tracks are personal data. We share pilot data only once that consent is recorded.

## Contact

- **Partnerships, early access and data collaboration:** the contact form on [aviometrics.com](https://aviometrics.com)
- **Questions and bugs about a public repository:** open an issue there
- **Security:** please report vulnerabilities privately, never in a public issue. See our
  [security policy](https://github.com/Aviometrics/.github/blob/main/SECURITY.md).

Aviometrics Ltd, registered in Northern Ireland.
