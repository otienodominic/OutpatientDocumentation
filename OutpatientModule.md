# Outpatient Module

Refers to a specific component or segment of a larger health information system that is dedicated to managing and facilitating outpatient care services. The outpatient module is designed to streamline and organize the processes related to patient care provided on an outpatient basis, where individuals receive medical treatment without being admitted to a hospital or staying overnight.

## Key features of an outpatient module

- **Patient Registration:** Captures and maintains essential patient information, including demographics, contact details, and medical history relevant to outpatient care.

- **Appointment Scheduling:** Allows for the scheduling and management of outpatient appointments, ensuring efficient use of healthcare resources and minimizing patient wait times.

- **Visit Documentation/Consultation:** Records and manages information about each outpatient visit, including patient vitals, symptoms, diagnosis, prescribed medications, and treatment plans.

- **Billing and Payment:** Manages financial aspects of outpatient care, including billing for services rendered, processing insurance claims, and handling patient payments.

- **Prescription Management:** Facilitates the ordering, dispensing, and tracking of prescription medications prescribed during outpatient visits.

- **Diagnostic Tests and Results:** Integrates with laboratory and imaging systems to request, record, and retrieve diagnostic test results for outpatient cases.

- **Follow-up and Referral Management:** Supports the scheduling of follow-up appointments and facilitates referrals to specialists or additional healthcare services as needed.

- **Reporting and Analytics:** Provides tools for generating reports and analytics related to outpatient services, aiding in performance assessment and decision-making.

- **Integration with Electronic Health Records (EHR):** Ensures seamless integration with the overall electronic health record system, allowing for a comprehensive view of a patient's medical history.


## OpenMRS Implementation of the Outpatient Module

### Patient Registration: 

I registered a patient by name _James Ayodi Ohon_ born on _4th Feb, 1967_. Below are the registration details.

![Alt text](image.png)

I started a visit for this _James Ayodi Ohon_ as shown below:

![Alt text](image-1.png)

I captured vitals as shown below:

![Alt text](image-2.png)

I added visit note for _James Ayodi Ohon_ as shown below. The diagnosis presumed from laboratory test from lab module allows me to select from ICD-11.

![Alt text](image-3.png)

After selection of the _Primary Diagnosis_ from the list, I added clinical notes relevant to the diagnosis in the text box. After this I added the next appointment date as shown below:


![Alt text](image-4.png)


## Tiberbu HMIS Implementation of the Outpatient Module

Tiberbu is based on the ERP known as Frappe Cloud which is customisable based on the needs of the users. Below is a patient flow diagram 

![Alt text](image-5.png)


## Ministry of health Implementation of the Outpatient Module

The ministry of health of Kenya implements the outpatient using two types of registers:

### MOH 204 A Outpatient Register (under five years)
The register is used for both Male and Female below 5 years (0 – 59 months) who are sick and visit the Health Facility for treatment. The patient/client is registered as an outpatient upon issuance of OPD card. The register also covers the IMCI component and should not have separate register for implementing IMCI. The register has various data elements which need to be captured in it. These include the patient name, age, sex, first visit or revisit, diagnosis, treatment given, danger signs and others. This register is supposed to feed the MOH 701 A Under five (<5) years Daily outpatient morbidity tally sheet before posting the daily summaries to MOH 705 A Under five (< 5) years Daily outpatient morbidity summary sheet.


<object data="Under5yrsRegister.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="Under5yrsRegister.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="Under5yrsRegister.pdf">Download PDF</a>.</p>
    </embed>
</object>

### MOH 204 B Outpatient Register (over 5 years)

Similar to the MOH 204 A Outpatient Register (under five years), this the register is used for both Male and Female above 5 years (60+ months) who are sick and therefore seek treatment in the health facility. The patient/client is registered as an outpatient upon issuance of OPD card. The register has various data elements which need to be captured in it. These include the patient name, age, sex, first visit or revisit, diagnosis, treatment given and others. This register is supposed to feed the MOH 701 B Over five (>5) years Daily outpatient morbidity tally sheet before posting the daily summaries to MOH 705 B Over five (>5) years Daily outpatient morbidity summary sheet. 




<object data="Over5yrsRegister.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="Over5yrsRegister.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="Over5yrsRegister.pdf">Download PDF</a>.</p>
    </embed>
</object>