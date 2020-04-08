## Validation

Basic validation has now been finished. This has consisted of multiple flow simulations of both air and water flows as well as practical setup.

### Practical testing

Printed models, printed on different printers at different printing sites have been tested with a wide variety of adapters and tubes conforming to either ISO standards or the proprietary Airvo connectors. With air leakage testing performed by submerging connections in water and running at full speed, no leakage could be identified.

### Air flow

Air flow simulations show that no clinically relevant resistance is added to the system by this project. Air flow is split evenly and the collection bottles are to be considered dead space.
Condensation can however affect air flow, see below.

| Air flow                                                                                                                                                              | Air flow with condensation                                                                                                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Air flow](<../../Validation/Air%20Flow/Air%20Flow%20(OLD%20design).png> 'Air flow simulation')                                                                      | ![Air flow + condensation simulation](../../Validation/Air%20Flow/Air%20Flow%20Condensation.png 'Air flow + condensation simulation')                                       |
| This simulation uses an older version of the design with a higher introduced resistance, even with an artifially high resistance the clinical effect is non-existent. | This simulation shows that with the extra unilateral condensation the resistance in one side of the setup is increased causing an uneven airflow that stabilises over time. |

### Condensation

While several steps have been taken to address condensation it is notable that high levels of condensation can affect air flow (see simulation above).

**Slosh Simulations**
|Slosh at 0 lpm| Slosh at 60 lpm|
|---|---|
|[**View simulation video**](https://github.com/hessius/HFNOsplitter/blob/master/Validation/Slosh/1x%20slosh%200lps-1.mp4?raw=true)|[**View Simulation Video**](https://github.com/hessius/HFNOsplitter/blob/master/Validation/Slosh/2x%20slosh%2060lps-1.mp4?raw=true)
|When removing excess build up of condensation toward the collection bottles at 0 lpm our simulations show that a tiny amount of fluid is able to pass the separator between the bottles. This is only possible at 0 lpm, with large amounts of fluid and if fluid is returned at high speed.|During use at full flow, excess condensation might not be able to flow freely back to the collection bottles. This is normal and expected at high flows. If excess fluid cannot easily be returned it is recommended to temporarily reduce flow.

### Continued validation

While basic validation has been sufficient to bring this into use as a standby solution at the hospital of origin we are performing continued validation focused on measuring the air flow within the circuit. We are now close to a functioning setup with results expected mid-april. When results are available this document will be updated accordingly.

<br /><br /><br /><br />

---

### [**Hygiene**](06%20Hygiene.md)&emsp;← Prev&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Next →&emsp;[**FAQ**](07%20FAQ.md)
