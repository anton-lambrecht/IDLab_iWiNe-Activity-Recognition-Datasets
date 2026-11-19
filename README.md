# Synchronized RF Human Activity Recognition Dataset

This dataset contains synchronized FMCW radar, impulse-radio ultra-wideband (IR-UWB), and Wi-Fi measurements for human activity recognition. All three modalities recorded the same activity executions against a common time reference.

## Collection setup

Measurements were collected in a bedroom at the HomeLab in Zwijnaarde, Belgium. The sensing hardware was mounted on the ceiling above the bed and remained fixed throughout the campaign.

| Modality | Hardware | Configuration |
| --- | --- | --- |
| FMCW radar | Texas Instruments IWR6843AOP | 60-64 GHz; 3 transmit and 4 receive antennas; 50 ms frame interval |
| IR-UWB | Qorvo QM33120WDK1 (DW3000) with Nordic nRF52840 development boards | 6.49 GHz; separate transmitter and receiver nodes approximately 30 cm apart; one measurement every 6.67 ms |
| Wi-Fi CSI | ZedBoard FPGA with AD-FMCOMMS2-EBZ, running openwifi | 2.4 GHz; monostatic setup; approximately 500 packets per second |

## Participants and room layouts

Twenty participants (14 male and 6 female), aged 21-67 years, took part. Heights ranged from 159 to 189 cm and weights from 50 to 92 kg. Participants provided written informed consent, and the study was approved by the relevant ethics committees of KU Leuven and Ghent University.

Six room layouts were created by changing the bed and chair positions while keeping the sensors fixed. Participants followed spoken instructions for realistic actions and were free to move at their own pace. The campaign yielded up to 120 participant-layout recordings.

The fine-grained labels cover no activity, walking, standing up, sitting down, lying on the bed, getting up from bed, anxious movement, eating, waving hands, and clapping hands. A separate four-class label set for sleep-monitoring analysis is also described in the accompanying study.

## Contact

For questions, clarifications, or permissions to use this dataset, please contact:

**Eli De Poorter**: [eli.depoorter@ugent.be](mailto:eli.depoorter@ugent.be)