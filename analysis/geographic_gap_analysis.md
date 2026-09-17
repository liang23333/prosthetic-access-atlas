# Geospatial Gap Analysis: Identifying Prosthetic Care Deserts in Rural America

## 1. Context & Methodology

While technological innovations in bionics and neural interfaces advance at leading urban academic medical centers, access to basic certified orthotic and prosthetic (O&P) services in rural America remains in severe crisis. A lower-limb prosthesis is not an "off-the-shelf" device; it requires continuous clinical attention:
* Diagnostic socket evaluation and definitive fabrication.
* Volume fluctuation management (diurnal residual limb fluid changes).
* Component alignment adjustments, gait retraining, and mechanical maintenance.
* Treatment of skin abrasions, shear blistering, and dermatological breakdown.

A typical new amputee requires **5 to 10+ clinical visits within their first year** post-amputation. When a patient lives 1.5 to 2.5 hours away from the nearest provider, this transit burden triggers catastrophic health failure modes: delayed socket modification, chronic residual limb ulceration, infection, secondary proximal amputation, and permanent device abandonment.

To quantify these coverage gaps, geospatial routing and distance analyses were conducted across three designated rural regions:
1. **Rural West Virginia** (Central/Southern Appalachia)
2. **Eastern Kentucky** (Cumberland Plateau Coalfields)
3. **The Mississippi Delta** (Northwestern Mississippi)

---

## 2. Regional Analysis 1: Rural West Virginia (Appalachian Mountain Basin)

### Demographic & Clinical Vulnerability:
* **Focal Coordinates:** Beckley, Raleigh County (37.7782° N, 81.1882° W).
* **Context:** Southern West Virginia exhibits some of the nation's highest rates of cardiopulmonary disease, type 2 diabetes, peripheral vascular disease (PVD), and occupational trauma (coal mining, timber, heavy manufacturing).
* **Provider Deserts:** Entire counties—such as McDowell, Wyoming, Webster, and Nicholas—possess **zero full-time certified prosthetists (CPs)**. Patients must travel to regional tertiary centers in Charleston or Morgantown.

### Quantitative Route Analysis (OpenStreetMap Engine):
* **Route:** Beckley, WV to Charleston Area Medical Center (CAMC / Dickinson St Medical District).
* **Distance:** **94,535 meters (94.5 km / 58.7 miles)**
* **Transit Duration:** **4,491 seconds (74.8 minutes / 1.25 hours)** one-way under optimal free-flow conditions.
* **Route Profile:** Traverse via I-77 / I-64 along the West Virginia Turnpike through severe mountain grades, bridges, and toll plazas.
* **Extreme Sub-regional Burden:** For amputees residing in deep hollows of McDowell County (e.g., Welch, WV), transit to Charleston exceeds **160 km (100 miles) and 2 hours 20 minutes each way**.

```
[Deep Rural Counties: McDowell / Wyoming]
       │ (1.0 hr winding secondary mountain roads)
       ▼
[Beckley Hub] ──(94.5 km / 75 min via WV Turnpike)──▶ [Charleston Tertiary O&P Hub]
Total Round-Trip Commitment: 4.0 - 5.0 hours | Cost: High fuel + toll fees
```

### Coverage Gap Failure Mode:
In winter months, heavy snowfall and treacherous mountain road conditions cut off access entirely. Amputees wearing ill-fitting sockets experience pressure necrosis over bony prominences, requiring hospital admission for debridement rather than routine outpatient adjustment.

---

## 3. Regional Analysis 2: Eastern Kentucky (Cumberland Plateau)

### Demographic & Clinical Vulnerability:
* **Focal Coordinates:** Hazard, Perry County (37.2490° N, 83.1934° W).
* **Context:** Eastern Kentucky faces systemic intergenerational poverty, high uninsured/Medicaid rates, and high amputation incidence compounded by the closure of community hospitals.
* **Provider Deserts:** While limited visiting satellite clinics occasionally operate in Perry or Pike counties, patients requiring specialized care, custom component fabrication, pediatric prosthetics, or revision fittings must travel to Lexington (University of Kentucky HealthCare / Shriners Children's).

### Quantitative Route Analysis (OpenStreetMap Engine):
* **Route:** Hazard, KY to UK HealthCare / Chandler Medical Center, Lexington, KY.
* **Distance:** **185,617 meters (185.6 km / 115.3 miles)**
* **Transit Duration:** **8,296 seconds (138.3 minutes / 2.3 hours)** one-way.
* **Route Profile:** Navigates North Main St, onto the Hal Rogers Parkway / KY-15 North, through Mountain Parkway Spur, across Mountain Parkway (KY-9002), onto I-64 West and Winchester Road into Lexington.

```
[Hazard, KY / Perry County]
       │
       ▼ (KY-15 & Mountain Parkway Spur)
[Mountain Parkway: 68.7 km]
       │
       ▼ (I-64 Corridor: 25 km)
[Lexington Tertiary Medical Center (UK HealthCare)]
───────────────────────────────────────────────────────────
Total One-Way: 185.6 km (115.3 mi) | Driving Time: 2h 18m
Total Round-Trip Commitment: 371 km (230 mi) | Driving Time: > 4.6 hours
```

### Coverage Gap Failure Mode:
A 4.6-hour round-trip driving requirement for a 30-minute socket alignment check creates an insurmountable barrier for elderly amputees who do not drive or cannot afford gas. Family caregivers must miss entire workdays. As a result, appointments are skipped until catastrophic residual limb ulcers or infections develop.

---

## 4. Regional Analysis 3: The Mississippi Delta (Alluvial Floodplain)

### Demographic & Clinical Vulnerability:
* **Focal Coordinates:** Clarksdale, Coahoma County (34.2006° N, 90.5702° W).
* **Context:** The Mississippi Delta has the highest prevalence of non-traumatic lower-extremity amputations (LEA) per capita in the entire United States, driven by epidemic levels of diabetic neuropathy and peripheral artery disease (PAD) combined with stark racial disparities in limb salvage revascularization.
* **Provider Deserts:** The vast majority of counties in the Delta (Coahoma, Bolivar, Sunflower, Leflore, Quitman, Tunica) have no standalone, full-service O&P fabrication facilities. Patients must journey either north to Memphis, TN, or south to Jackson, MS.

### Quantitative Route Analysis (OpenStreetMap Engine):
* **Route:** Clarksdale, MS to Regional O&P Centers in Memphis, TN (Poplar Ave / Medical District).
* **Distance:** **121,305 meters (121.3 km / 75.4 miles)**
* **Transit Duration:** **5,865 seconds (97.8 minutes / 1.63 hours)** one-way.
* **Route Profile:** Direct transit north along US-61 through rural Tunica and DeSoto counties, crossing state lines into Shelby County, Tennessee via South B.B. King Boulevard.

```
[Clarksdale, MS / Coahoma County]
       │
       ▼ (US-61 North: 51.2 km rural highway)
[Tunica / Northern Delta Corridor]
       │
       ▼ (US-61 Interstate Link: 62.6 km)
[Memphis, TN Regional Orthopedic & O&P Hub]
───────────────────────────────────────────────────────────
Total One-Way: 121.3 km (75.4 mi) | Driving Time: 1h 38m
Total Round-Trip Commitment: 242.6 km (150.8 mi) | Driving Time: > 3.3 hours
```

### Coverage Gap Failure Mode:
* **Public Transit Absence:** Unlike urban centers, there is zero scheduled public transit connecting Delta communities to Memphis medical facilities.
* **Interstate Medicaid Incompatibilities:** Mississippi Medicaid recipients often face bureaucratic prior-authorization denials when seeking care across state lines in Tennessee, forcing patients instead to travel south to Jackson (over **170 km / 2+ hours one-way**).

---

## 5. Comparative Regional Metrics Matrix

| Metric | Rural West Virginia (Beckley ➔ Charleston) | Eastern Kentucky (Hazard ➔ Lexington) | Mississippi Delta (Clarksdale ➔ Memphis) |
| :--- | :--- | :--- | :--- |
| **One-Way Distance** | 94.5 km (58.7 mi) | 185.6 km (115.3 mi) | 121.3 km (75.4 mi) |
| **One-Way Drive Time** | 74.8 minutes (1.25 hrs) | 138.3 minutes (2.30 hrs) | 97.8 minutes (1.63 hrs) |
| **Round-Trip Drive Time** | 2.5 hours | 4.6 hours | 3.3 hours |
| **Terrain / Infrastructure** | Mountainous; turnpike toll roads; severe winter freezing | Mountain parkway corridors; elevation changes; winding valleys | Flat alluvial plain; long rural two-lane highways |
| **Primary Disease Etiology** | Trauma, coal-related injuries, diabetes, PVD | Diabetes, vascular disease, occupational trauma | Diabetic ulcers, PVD/PAD, severe health disparities |
| **Local O&P Density** | Extreme deficit; zero in peripheral counties | Dependent on sporadic visiting regional satellites | Near complete absence of certified fabrication labs |
| **Key Barrier to Regular Care**| Mountain weather, vehicle maintenance costs, tolls | Distance (>230 mi round-trip), lost caregiver wages | Poverty, lack of personal transport, interstate Medicaid barriers |

---

## 6. Synthesis: The Rural Amputee Trap

The combination of data from ClinicalTrials.gov and our geospatial routing proves that:
1. **Clinical Innovation is Centered in Urban Elite Academic Centers:** High-tech research trials (AMI, osseointegration, AI pattern recognition) are clustered in cities like Boston, Chicago, Seattle, and Cleveland.
2. **Rural Populations Bear the Disproportionate Disease Burden:** The highest concentrations of amputees live in Appalachian and Delta counties where access to even basic socket modifications requires a half-day or full-day travel odyssey.
3. **The Urgent Solution is Decentralization:** Bridging this divide requires shifting away from centralized brick-and-mortar clinics toward decentralized delivery models: mobile prosthetic units, digital 3D scanning, and remote sensor-based telehealth monitoring.
