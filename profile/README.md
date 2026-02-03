# DWIS Repository Navigator

This index lists each repository in this folder with its README headline (or a note if none). Click a link to jump into that repo.

## DWIS Workstreams

```mermaid
flowchart TD
    A[DWIS Advisory Committee] -->|Workstream| B(High Level Architecture)
    A -->|Workstream| C(Semantic of Realtime Signals)
    A -->|Workstream| D(Drilling Process Protection)
    A -->|Workstream| E(ADCS Standard Interfaces)
    A -->|Workstream| F(Contextual Data)
    A -->|Workstream| G(Use Cases)
    A -->|Workstream| I(Rig Action Pland/Detailed Operational Plan)
```

- [Overall](https://github.com/D-WIS/Overall/) - An overall repo for general DWIS project documents
- [AdvisoryCommittee](https://github.com/D-WIS/AdvisoryCommittee/) - DWIS repo for the Advisory Committee
- [HighLevelArchitecture](https://github.com/D-WIS/HighLevelArchitecture/) - DWIS project repo for the workstream "High Level Architecture"
- [ContextualData](https://github.com/D-WIS/ContextualData/) - The DWIS Project repo for the Workstream "Contextual Data"
- [SemanticDrillingRTSignals](https://github.com/D-WIS/SemanticDrillingRTSignals/) - The DWIS Project repo for the Workstream "Semantic of RT Signals"
- [RigOS-DrillingProcessProtection](https://github.com/D-WIS/RigOS-DrillingProcessProtection/) - The DWIS project repo for the workstream "Drilling Process Protection"
- [RigOSAPI](https://github.com/D-WIS/RigOSAPI/) - The DWIS Project repo for the workstream ADCS Interfaces
- [UseCases](https://github.com/D-WIS/UseCases/) - The DWIS Project repo for the workstream "Use Cases"
- [Downlinking](https://github.com/D-WIS/Downlinking/) - The DWIS Project report for the specification of Downlinking commands
- [ProjectSTUPID](https://github.com/D-WIS/ProjectSTUPID/) - A repo for working on Rig Action Plan or Detailed Operational Plan

## Main Code
![DWIS Architecture](Architecture.svg)

### Common Code
- [Common](https://github.com/D-WIS/Common/) - Common classes for DWIS

### Blackboard
- [DDHub-Semantic-Interoperability](https://github.com/D-WIS/DDHub-Semantic-Interoperability/) - DWIS Semantic vocubulary
- [DWIS-Blackboard-Base](https://github.com/D-WIS/DWIS-Blackboard-Base/) - Base code for the DWIS Blackboard
- [DWIS-Blackboard-Clients](https://github.com/D-WIS/DWIS-Blackboard-Clients/) - Clients for DWIS Blackboard
- [DWIS-Blackboard-Samples](https://github.com/D-WIS/DWIS-Blackboard-Samples/) - Samples for the DWIS Blackboard
- [DWIS-Blackboard-Server](https://github.com/D-WIS/DWIS-Blackboard-Server/) - DWIS Blackboard server
- [Semantic-Server-Deploy](https://github.com/D-WIS/Semantic-Server-Deploy/) - Blackboard deployment

### Microstate Engine
- [MicroStateEngine](https://github.com/D-WIS/MicroStateEngine/) - DWIS Microstates Engine

### Scheduler
- [Scheduler](https://github.com/D-WIS/Scheduler/) - The original DWIS Scheduler
- [Scheduler](https://github.com/D-WIS/DWIS.HSM.Scheduler/) - The new version of the DWIS Scheduler compatible with autonomy

### Composer
- [AdviceComposer](https://github.com/D-WIS/AdviceComposer/) - DWIS Advice Composer

### ADCS Capability Descriptions
- [RigOS-Capabilities](https://github.com/D-WIS/RigOS-Capabilities/) - Classes used to define the ADCS function capabilities
- [RigOS-Controller-Capabilities](https://github.com/D-WIS/RigOS-Controller-Capabilities/) - Classes used to define the specific ADCS capabilities for Controller functions
- [RigOS-FDIR-Capabilities](https://github.com/D-WIS/RigOS-FDIR-Capabilities/) - Classes used to define the specific ADCS capabilities for Fault Detection Isolation and Recovery
- [RigOS-Procedure-Capabilities](https://github.com/D-WIS/RigOS-Procedure-Capabilities/) - Classes used to define the specific ADCS Capabilities for standard drilling procedures
- [RigOS-SOE-Capabilities](https://github.com/D-WIS/RigOS-SOE-Capabilities/) - Classes used to define the specific ADCS capabilities for safe operating envelopes

### ADCS Bridges
- [ADCSBridgeGeneric](https://github.com/D-WIS/ADCSBridgeGeneric/) - Generic ADCS Bridge (used for BTWN)
- [ADCSBridgeDEAL](https://github.com/D-WIS/ADCSBridgeDEAL) - ADCS Bridge  for DEAL from HMH (Private)
- [ADCSBridgeNOVOS](https://github.com/D-WIS/ADCSBridgeNOVOS/) - ADCS Bridge  for NOVOS from NOV (Private)

### DAQ Bridges
- [DAQBridgeCleanSight](https://github.com/D-WIS/DAQBridgeCleanSight/) - an example bridge between the CleanSight system from DrillDocs and DWIS
- [DAQBridgeRheoSense](https://github.com/D-WIS/DAQBridgeRheoSense) - an example bridge between RheoSense from IMS and DWIS
- [DAQBridgeBaraLogix](https://github.com/D-WIS/DAQBridgeBaraLogix) - an example bridge between BaraLogix from Halliburton and DWIS
- [DAQBridgeOmniView](https://github.com/D-WIS/DAQBridgeOmniView) - an example bridge between OmniView from Petromar/Nabors/WellID and DWIS
- [DAQBridgeBlackStream](https://github.com/D-WIS/DAQBridgeBlackStream) - an example bridge between BlackStream from NOV and DWIS
- [DAQBridgeBaseStar](https://github.com/D-WIS/DAQBridgeBaseStar) - an example bridge between the BaseStar mechanical sub from Halliburton and DWIS
- [DAQBridgeUDPTopSideData](https://github.com/D-WIS/DAQBridgeUDPTopSideData) - an example bridge between a top-side logging system using UDP datagrams and DWIS

### Contextual Data
- [ContextualDataWellBoreSelector](https://github.com/D-WIS/ContextualDataWellBoreSelector) - a web application to select an active wellbore from the list of wellbores available in the OSDC microservice framework.
- [ContextualDataBridgeBHADrillString](https://github.com/D-WIS/ContextualDataBridgeBHADrillString) - a bridge between the OSDC BHA/Drill-string microservice the D-WIS Blackboard
- [ContextualDataBridgeWellBoreArchitecture](https://github.com/D-WIS/ContextualDataBridgeWellBoreArchitecture) - a bridge between the OSDC Wellbore Architecture microservice the D-WIS Blackboard
- [ContextualDataBridgeTrajectory](https://github.com/D-WIS/ContextualDataBridgeTrajectory) - a bridge between the OSDC Trajectory microservice the D-WIS Blackboard

### Example Services
- [ServiceDownholeECD](https://github.com/D-WIS/ServiceDownholeECD) - a service that reads downhole annulus pressures, trajectory data and wellbore architecture information to produce Downhole ECD (and ESD).
- [ServiceActiveVolume](https://github.com/D-WIS/ServiceActiveVolume) - a service that reads drilling fluid and cuttings flowrate from observations at the shale shaker lever and active pit volume and produces a consolidated active pit volume.
- [ServiceAdjustedWOB](https://github.com/D-WIS/ServiceAdjustedWOB) - a service that reads the surface and downhole WOB and that provides a consolidated WOB. The service also performs the opposite operation for recommended WOB limits, i.e., it converts into the ADCS SWOB context, WOB limits accounting for initial biases on zero WOB, effects of the block position and changes in flowrates.

## Additional Code for Demo Preparation
- [DWIS-demo-2024-deploy](https://github.com/D-WIS/DWIS-demo-2024-deploy/) - Repository used for the deployment of the apps involved in the 2024 D-WIS demonstration
- [DWIS-demo-2024-openlab](https://github.com/D-WIS/DWIS-demo-2024-openlab/) - The applications used during the preparation of the 2024 DWIS demonstration
- [DWIS-demo-2024-openlab-adcs](https://github.com/D-WIS/DWIS-demo-2024-openlab-adcs/) - The DWIS to OpenLab drilling access used during the preparation of the 2024 DWIS demonstration
- [DWIS-demo-2024-openlab-replay](https://github.com/D-WIS/DWIS-demo-2024-openlab-replay/) - A repository used to perform replays
- [DWIS-demo-2024-web](https://github.com/D-WIS/DWIS-demo-2024-web/) - The DWIS web interface used during the 2024 DWIS demonstration 
- [DWIS-demo-mockup](https://github.com/D-WIS/DWIS-demo-mockup/) - Repository to perform mockup tests in connection to preparation of DWIS Demos
- [DWIS-Docker](https://github.com/D-WIS/DWIS-Docker/) - Facilities for D-WIS containers management 
- [DWIS-NOVOS-Clients](https://github.com/D-WIS/DWIS-NOVOS-Clients/) - Clients for the DWIS NOVOS bridge
- [eRAPAdvisor](https://github.com/D-WIS/eRAPAdvisor/) - an eRAP Advisor

## Additional Code for Side and Obsolete Projects
- [ADCSSoftwareInterface](https://github.com/D-WIS/ADCSSoftwareInterface/) - OpenRDM
- [RigOS-Viewer-Capabilities](https://github.com/D-WIS/RigOS-Viewer-Capabilities/) - A viewer for ADCS Capabilities
- [WP2_CSI](https://github.com/D-WIS/WP2_CSI/) - Repo for the CSI application. Part of the work package 2 of the DSID project
- [WP2_MUMA](https://github.com/D-WIS/WP2_MUMA/) - Repo for the mud management activity. Work package 2 of the DSID project
- [D-WIS.github.io](https://github.com/D-WIS/D-WIS.github.io/) - The first web page for the DWIS project. Now replaced by [D-WIS.org](https://d-wis.org/)

## Archived and Deprecated
- [SemanticAndLogicalStatement](https://github.com/D-WIS/SemanticAndLogicalStatement/) - Classes used to define semantically logical statements
- [SemanticAndStateAutomata](https://github.com/D-WIS/SemanticAndStateAutomata/) - Classes used to define semantically finite State Automata
- [DDHub-DSID-WP2-Common](https://github.com/D-WIS/DDHub-DSID-WP2-Common/) - Many test projects used during development

# Publications
- Cayeux, Eric, Macpherson, John, Laing, Moray, Pirovolou, Dimitrios, and Fred Florence. "Drilling Systems Automation: Fault Detection, Isolation and Recovery Functions for Situational Awareness." Paper presented at the SPE/IADC International Drilling Conference and Exhibition, Stavanger, Norway, March 2023. [SPE-212565-MS](https://doi.org/10.2118/212565-MS)
- Cayeux, Eric, Macpherson, John, Pirovolou, Dimitrios, Laing, Moray, and Fred Florence. "A General Framework to Describe Drilling Process States." Paper presented at the SPE/IADC International Drilling Conference and Exhibition, Stavanger, Norway, March 2023. [SPE-212537-MS](https://doi.org/10.2118/212537-MS)
- Cayeux, Eric, Daireaux, Benoît, Macpherson, John, Florence, Fred, and Espen Solbu. "Interoperability of Real-Time Drilling Signals at the Rig Site: An Example Based on Mechanical Specific Energy." Paper presented at the SPE/IADC International Drilling Conference and Exhibition, Stavanger, Norway, March 2023. [SPE-212472-MS](https://doi.org/10.2118/212472-MS)
- Annaiyappa, P., Macpherson, J., and E. Cayeux. "Clock Synchronization and Timestamping of Data on Acquisition at the Wellsite: Guidelines and Recommendations." SPE Drill & Compl (2023;): [SPE-208732-PA](https://doi.org/10.2118/208732-PA)
- Kuilenburg, R. Van, Isbell, M., Behounek, M., Macpherson, J., Schaefer, S., Fox, T., and D. Pirovolou. "Interoperability for Drilling Process Automation." Paper presented at the IADC/SPE International Drilling Conference and Exhibition, Galveston, Texas, USA, March 2024. [SPE-217748-MS](https://doi.org/10.2118/217748-MS)
- Cayeux, Eric, Macpherson, John, Pirovolou, Dimitrios, Laing, Moray, and Fred Florence. "A General Framework to Describe Drilling Process States." SPE Journal (2024;): [SPE-212537-PA](https://doi.org/10.2118/212537-PA)
- Cayeux, E., Daireaux, B., Olsen, K. K., Antosz, K., Johansen, M. Dahle, Næsgaard, H. S., and L. Hoarau. "Demonstration of Seamless Interoperability for Automatic Drilling Management in a Multi-Vendor Context." Paper presented at the SPE Annual Technical Conference and Exhibition, New Orleans, Louisiana, USA, September 2024. [SPE-220987-MS](https://doi.org/10.2118/220987-MS) 
- Cayeux, E., Macpherson, J., Brackel, H. U., Igland, J. K., and S. Schaefer. "Automatic Online Classification of Drilling Activities." Paper presented at the SPE/IADC International Drilling Conference and Exhibition, Stavanger, Norway, March 2025. [SPE-223782-MS](https://doi.org/10.2118/223782-MS) 
- Cayeux, E., Mihai, R., Herikstad, R. V., Olsen, K. K., Antosz, K., and M. Pham. "Code Generation of Automatic Drilling Control System Functions with Embedded Verification and Validation Functionalities." Paper presented at the SPE/IADC International Drilling Conference and Exhibition, Stavanger, Norway, March 2025. [SPE-223716-MS](https://doi.org/10.2118/223716-MS) 
- E. Cayeux, B. Daireaux, E. Dvergsnes, I. Villanueva, M. Pham, K.K. Olsen, S. Gåseland, K. Antosz, D. Dashevskiy, R. Tobisawa, F. da Silva, R. Herikstad, K. Birgisson, E. Nyjordet, and J. Cao. “Demonstration of the Drilling and Wells Interoperability Standard Framework in a Multi-Company Context”, SPE/IADC Drilling Conference, Galveston, TX, USA, Mar 2026

