# Models

These designs have all been made from scratch for this project. They use no prioprietary or 3D-scanned information. They are based on ISO standards when applicable - ISO-5356 for connectors and ISO-19054:2006 for mounts. All CAD work has been performed by Erik Cederberg at 3Dverkstan on behalf of the project.

---

### T-Connector

This connector splits air flow evenly and connects the proprietary connector of the distal end of the AirSpiral tube to the proximal end of two CPAP / BiPAP standard tubes.

It also features two drainage points to collect condensation. Two PET bottles are connected here to collect the fluid build up, and between the drainage point there is a splash guard. These features keep condensation from each patient separate. Thus the risk of cross contamination is kept to a minimum.

The design features clear markings so that the setup can be as easy and reliable as possible (also, each connector can only fit in the correct place).

|                                                 CAD view - Front                                                 | CAD view - Cross section                                                                                              |
| :--------------------------------------------------------------------------------------------------------------: | --------------------------------------------------------------------------------------------------------------------- |
| ![T-Shaped Connector Shell](../../Meta/Schematics%20and%20Renders/Sideview_v3.png 'CAD view T-Shaped Connector') | ![T-Shaped Connector Cross Section](../../Meta/Schematics%20and%20Renders/Cutaway_v3.png 'Cross Section T-connector') |

The T-connector provided has a unified mount conforming the ISO-19054:2006 rail mount standard as well as enabling fastening with cable ties. The previous ziptie-only mount for the Airvo pole is therefore considered deprecated.

|                                                ISO-19054:2006 / Zip tie unified mount (male)                                                 |
| :------------------------------------------------------------------------------------------------------------------------------------------: |
| ![T-Connector back ISO-mount](../../Meta/Schematics%20and%20Renders/T-Coupling-V4/V4-Backside-Combimount.png 'T-Connector back Combi-mount') |

---

### Adapters

We provide adapters for both the distal end of the AirSpiral tube and the proximal end of the Optiflow Nasal Cannula in two sizes / configurations, a male and female version.

For the core set you need two copies of the male Airvo connector with a male 22mm connector ("Airvo-M-22-M.stl")

![All adapters](../../Meta/Schematics%20and%20Renders/Adapters_All.png 'All adapters')

---

## Demo

This AR demo, only available on iOS, shows the 3D printed parts (for a standard setup) in actual size in Augmented Reality. Launch the demo by opening the link using an iPhone or iPad.

## [Launch AR-Demo](https://github.com/hessius/HFNOsplitter/blob/master/Meta/Other/Complete%20Set%20-%20Orientation.usdz?raw=true)

---

## Manufacturing Instructions

These prints are made to be printed using readily available resin 3D-printing methods. We recommend using SLA methods, specifically these instructions are based on the Formlabs Form 2/3 printers.

We recommend against using FDM/FFM printing as the high humidity and temperature is very suitable for bacterial growth and as FDM produces porous prints which cannot easily be sterilised.

All prints intended for medical use within this project are printed using the Formlabs Surgical Guide or Formlabs Dental SG Resin. These resins are approved for dental use and made to be autoclaved. When using one of these resins our risk assessment has been that the associated risks with the printing material are negligible.

[Formlabs Surgical Guide Datasheet](https://dental-media.formlabs.com/datasheets/SugicalGuideTechnicalDataSheet-101.pdf)

[Formlabs Surgical Guide Instructions for use](https://dental-media.formlabs.com/filer_public/56/69/566945b9-11c8-417a-a3e2-e88ec38668f5/surgicalguideifu.pdf)

[Formlabs Dental SG Datasheet](https://formlabs-media.formlabs.com/datasheets/DentalSG-DataSheet.pdf)

[Formlabs Dental SG Instructions for use](https://media.formlabs.com/m/1a0daf305c310d9d/original/-ENUS-Dental-SG-Instructions-for-Use.pdf)

If you attempt to print this on your own, we recommend that you have experience with these types of materials or are able to use the assistance of someone with that type of experience.

After validation is complete, we will provide complete printing instructions in the form of .form projects that others are free to use with the Formlabs standard software.

For all parts, we recommend that you turn off internal supports. For the T-connector, we recommend that you rotate the model so that one end of the long axis (so one of the 22mm connectors) is aiming toward the build plate in a ~50 degree angle, with around 10 degrees of tilt backwards.

For the adapters and plugs, we recommend that you raise them slightly off the print bed. For the adapters, orient the models with the 22mm/15mm coupling facing the build plate straight on. For the plugs, orient the models with th handle facing the build plate straight on. This way, support can be avoided on all critical surfaces, ensuring the best possible tolerance level.

| Complete set on build plate                                                                                                                  | Adapter straight up with support                                                                                                       | T-coupling angled with support                                                                                           |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| ![One complete set on a build plate](../../Meta/Schematics%20and%20Renders/Buildplate-one-set-Form3.png 'One complete set on a build plate') | ![Adapter straight up with support](../../Meta/Schematics%20and%20Renders/adapter-with-support.png 'Adapter straight up with support') | ![T-Coupling angled with support](../../Meta/Schematics%20and%20Renders/T-coupling.png 'T-Coupling angled with support') |

### Changelog

| **Date**   | **Changes**                                                           |
| ---------- | --------------------------------------------------------------------- |
| 2020-04-05 | - Change B and C ports to 22mm male                                   |
| 2020-04-08 | - Rename STL-files (M/F -> Optiflow/AirSpiral)                        |
|            | - Add plugs to set.                                                   |
|            | - Add slight modifications to B, C, D, and E to better fit with plugs |
| 2020-04-10 | - Version bump: V4                                                    |
|            | - Add new ISO-19054:2006 compatible mounting slot                     |
| 2020-04-13 | - Add new "combimount" compatible with ISO-19054:2006 and zip ties    |  |
