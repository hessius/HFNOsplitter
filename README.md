# Welcome to the HFNOsplitter project

This project is dedicated to doubling the capacity for High Flow Nasal Oxygen (HFNO) treatment by treating two COVID-19 patients simultaneously using one HFNO-device.
This project is currently only aimed at the Airvo 2 Optiflow system.

**N.B. 1 This is an ongoing project and is not yet ready for use in patients.
We hope that the project will be validated and ready for use around the 7th of April.**

**N.B. 2 Even when ready this solution will be provided as is with no express or implied warranty.
In no event will the authors be held liable for any damages arising from the use of this solution.**

**N.B. 3 This project is not done in conjuction, collaboration or influence of the original manufacturer of any equipment, medical or otherwise**

### Progress

- [x] Develop Solution
- [x] Risk Assesment
- [x] Medical instructions (Swedish)
- [ ] Medical instructions (English) (_zOngoing_)
- [ ] Validation of prototypes (_Ongoing_)
- [ ] First clinically aimed production (Aimed at April 5th)
- [ ] Roll out (Aimed at April 7th)

Treating two patients simultaneously is possible due to

1. Treatment guidelines that stipulate a maximum flow of 30 litres/minute
2. The Airvo 2 system being capable of outputting 60 litres/minute

Treating two patients simultaneously is feasible due to

1. Unidirectional high flow makes cross contamination unlikely
2. Using this only for cohort care with patients with the same disease makes cross contamination less significant
3. HFNO being a completely open system / circuit makes patient factors basically irrelevant for air flow dynamics
4. In the authors' limited experience the COVID-19 patients are often titrated to very similar treatments

This project provides both the 3D-models of parts needed for split HFNO treatment as well as **suggested** instructions for use and manufacture. We also aim to continuously provide the validation from both simulations / calculations as well as real world usage (when ready).

![Render of T-Shaped Connector](Meta/T-Front.png 'Render of T-Shaped Connector')

## Summary

HFNO is a valuable treatment in the ongoing COVID-19 pandemic. It's importance has risen as many healthcare systems now recommend against using more readily available Non Invasive Ventilation (e.g. BiPAP). The access to HFNO is severely limited. The standard HFNO device Airvo 2 uses only proprietary connectors and cannot be connected to other devices.
**The basic premise of this project is to provide 3D-printable parts to be able to split the HFNO treatment between to patients, thus doubling the treatment capacity.** This should not be used if any other method of providing HFNO exists!

## Overview / Introduction

High Flow Nasal oxygen (HFNO) / High Flow Nasal Cannula (HFNC) is a staple of treatment in COVID-19, especially as many countries/regions/hospitals/health care providers are now recommending against regularly using CPAP and Non Invasive Ventilation / BiPAP in these patients. This is the case in Sweden (where this project was initiated), where the Infectious Diseases Association of Sweden (**IDAS**, Sw: "Svenska Infektionsläkarföreningen") has recommended not using CPAP or NIV as well as limited upper maximums for HFNO (See below).

Used timely and correctly in the context of COVID-19 a patient can in the best case scenario avoid intubation and invasive ventilation. Access to these systems are however severely limited and the machines are markedly more scarce than e.g. BiPAP-systems.

The main system in use outside of the ICU is the Fischer & Paykel Airvo 2, often called "**Optiflow**", which to be precis is the special nasal cannula used with the system. The Airvo is capable of outputting 2-60 litres / minute of airflow with 21-100% FiO2 and uses wholly proprietary connectors which are not readily available and cannot be used with standardised respiratory equipment.

IDAS recommends limiting the HFNO air flow in COVID-19 patients to 30 litres / minute due to risk of aeorosolisation and the FiO2 to 50 % due to the risk of alveolar collapse. **Thus the Airvo 2 is capable of providing two patients without impeding the maximum levels of treatment.**

HFNO systems are well suited for split airflow, substantially more so than ventilators, CPAP, or BiPAP. This is due to the open nature of the system which causes patient factors (e.g. airway resistance) to have minimal impact on the air flow. The unidirectionality of the air flow means that no air is shared between patients, even without added filtration. Even so, the only patients eligible for treatment with Split HFNO (Hereon "**SHFNO**") are suffering from the same disease, which also means that potential cross contamination across patients is less significant.

While every health care provider utilising SHFNO will need to ensure that they have medical instructions for use in place, we provide an example based on the medical instructions for use from Västmanland Hospital Västerås, in Sweden. In these instructions it is recommended to avoid SHFNO for patients with _confirmed_ secondary bacterial infections as well as for carriers of drug resistant bacteria.

To enable SHFNO we provide 3D models of

1. A **T-shaped connector** used to connect the distal end of the Airvo connected tube (AirSpiral) with two standard 22mm CPAP/BiPAP tubes as well as two bottles used to collect condensate.
2. An **Adapter** between the distal end of a standard 22mm CPAP/BiPAP tube and the proximal end of the Optiflow nasal cannula.

**A standard SHFNO setup requires one T-shaped connector as well as two adapters.**

_Aside from the main set provided are also models of other adapters as well as an alternate T-shaped connector enabling the proprietary connectors to connect to other standardised connectors as setup might differ across hospitals._

In the setup of SHFNO both patients receive identical treatment, in the (hitherto limited) clinical experience of the authors, COVID-19 patients treated under the recommendations above are invariably using HFNO titrated to very similar flows and FiO2. For suggestions on how to start treatment with HFNO / SHFNO please see the provided documentation.

## Images

![Render of T-Shaped Connector Front](Meta/T-Front.png 'Render of T-Shaped Connector Front')
![Render of T-Shaped Connector Back](Meta/T-Back.png 'Render of T-Shaped Connector Back')
![Photo of T-Shaped Connector](Meta/T-Connected.png 'Photo of T-Shaped Connector')

## [AR-Demo](https://github.com/hessius/HFNOsplitter/blob/master/Meta/Complete%20Set%20-%20Orientation.usdz?raw=true)

(iOS only)

## Working group

- Erik Cederberg, 3Dverkstan
- Erik Ekbom, Region Skåne
- Petter Frieberg. Region Skåne
- Einar Heiberg, Region Skåne
- Jesper Hessius (MD), Region Västmanland
- Per Nordqvist, Region Skåne
- Göran Peterson, Region Skåne
- Philip Bernborg, Region Skåne
- Sebastian Strunk-Möller, Region Skåne
- Muris Imsirovic, Region Skåne

## Thanks to

### [3Dverkstan](http://3dverkstan.se) for provididng their time, effort, expertise and printers for this project. Without them none of this would have happened.

All the online communities, doctors, nurses and medical technicians who have provided their input and knowledge into every step of this process.
