# **Hong Kong Hourly Link-Level Traffic Volume and Emission Dataset**
### **Hourly traffic volume and emission estimates for eight vehicle classes across the Hong Kong road network**

## **Overview**

This repository provides documentation and access information for a dataset of **hourly road link-level traffic volume and emission estimates for eight vehicle classes in Hong Kong**. The dataset is intended to support research on **traffic dynamics**, **vehicle emissions**, **near-road air pollution**, **spatiotemporal transport analysis**, and **environmental justice**.

This repository serves as the **data portal** for the project. It includes the dataset description, access links, metadata, citation information, and related documentation.

---

## **Access to the Full Dataset**

Because the full data files are too large to store on GitHub, the complete dataset is hosted externally on Zenodo.

### **Dataset Access Link**
**https://zenodo.org/records/19127840**

### **Related Publication**
**Niu, C., Chen, Q., Wang, A., & Xu, J. (2026). _Disentangling Near-Road Emission Inequities in Hong Kong through Data-Driven Spatiotemporal Traffic Dynamics_. Environmental Science & Technology. https://doi.org/10.1021/acs.est.5c14619**

### **Paper Access Link**
**https://doi.org/10.1021/acs.est.5c14619**

---

## **Dataset Description**

This dataset contains **hourly traffic volume and emission estimates at the road-link level across the Hong Kong road network**. Each record corresponds to a specific **road link** and a specific **hour**, allowing users to analyze both the **spatial distribution** and **temporal variation** of traffic activity and associated emissions.

A **link** refers to a road segment in the digital road network representation of Hong Kong. By structuring the dataset at the link level, the data can be directly connected to the road network for **GIS mapping**, **network analysis**, **hotspot identification**, and **integration with demographic or land-use data**.

The dataset includes estimates for **eight vehicle classes**, enabling users to distinguish the contributions of different vehicle types rather than relying on aggregated traffic totals. This high spatiotemporal resolution is especially valuable for examining how different vehicle categories contribute to urban emission burdens across locations and times of day.

This dataset is closely related to the published study on **traffic-emission inequities in Hong Kong** and is intended to facilitate **data reuse**, **methodological transparency**, and **future comparative research**.

The hourly traffic volume data were estimated using an **AI-based approach**. As a result, some estimated traffic volumes are **not integers**. The volume unit should therefore be interpreted as **number of vehicles**, and users may transform these values to integers if needed for their own applications.

---

## **What the Dataset Includes**

### **1. Hourly Link-Level Traffic Volume Data**
For each road link and hour, the dataset reports estimated traffic volumes for **eight vehicle classes**.

- **Unit:** **number**
- Because the traffic volumes are estimated using an AI-based method, some values are **non-integer estimates** rather than observed integer counts.
- Users may round or transform these values into integers if required by their own analysis.

### **2. Hourly Link-Level Emission Data**
For each road link and hour, the dataset reports estimated emissions associated with traffic activity.

The dataset currently includes:

- **NOx emissions**
- **PM2.5 emissions**

**Emission units:**
- **NOx:** grams/km  
- **PM2.5:** grams/km  

These emissions are reported at the **link-hour** level for each vehicle class.

### **3. Spatial Reference Information**
The dataset is structured around the Hong Kong road network, where each observation corresponds to a unique **link-hour** combination. This structure allows the tabular traffic and emission data to be joined back to the road network for mapping and spatial analysis.

### **4. Metadata and Documentation**
Supporting files describe the **variables**, **units**, **vehicle classes**, **spatial structure**, and **recommended usage** of the dataset.

---

## **Spatial and Temporal Resolution**

- **Study area:** Hong Kong  
- **Spatial unit:** Road link  
- **Temporal unit:** Hourly  
- **Data structure:** One record per **link-hour** combination  

This fine spatiotemporal resolution allows users to move beyond daily averages and examine **when** and **where** different vehicle classes contribute to traffic emissions.

---

## **Vehicle Classes**

The dataset includes hourly traffic volume and emission estimates for the following **eight vehicle classes**:

- **MC**: motorcycle  
- **PC**: private car  
- **TX**: taxi  
- **FBDD**: franchised double-deck bus  
- **LDB**: light-duty bus  
- **HDB**: heavy-duty bus  
- **LGV**: light-duty goods vehicle  
- **HGV**: heavy-duty goods vehicle  

The vehicle classification standards are based on the **Transport Department (TD) classification system in Hong Kong**.

---

## **Potential Applications**

This dataset can support research and practice in the following areas:

- **Traffic emission modeling**
- **Urban air pollution analysis**
- **Near-road exposure assessment**
- **Transport equity and environmental justice**
- **GIS and spatial data science**
- **Road-network-based spatial analysis**
- **Vehicle-class contribution analysis**
- **Data-driven transport policy evaluation**

---

## **How to Use the Data**

Users can download the full dataset from Zenodo and use this repository as the main source of:

- **Dataset description**
- **Metadata**
- **Variable definitions**
- **Citation information**
- **Example scripts or workflows**

If a spatial road network file is provided separately, users can join the tabular traffic and emission data to the road network using the **link identifier**.

Because the traffic volumes were estimated using an AI-based method, some link-level hourly traffic volumes are fractional values. Users should interpret these as estimated traffic quantities and may round them if an integer form is preferred.

---

## **Citation**

If you use this dataset, please cite both the **dataset** and the **related publication** describing the methodology and application.

### **Related Article Citation**
**Niu, C., Chen, Q., Wang, A., & Xu, J. (2026). _Disentangling Near-Road Emission Inequities in Hong Kong through Data-Driven Spatiotemporal Traffic Dynamics_. Environmental Science & Technology. https://doi.org/10.1021/acs.est.5c14619**

### **Article Link**
**https://doi.org/10.1021/acs.est.5c14619**

### **Dataset Link**
**https://zenodo.org/records/19127840**

---

## **Repository Structure**
