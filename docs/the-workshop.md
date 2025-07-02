# The Workshop

### 4.1 Data Discovery Canvas

The workshop always kicks off with the Data Discovery Canvas. The goal of this canvas is to visualize all data that needs to be classified.

**Process** During the analysis of the process, the different steps are mapped out. This begins with identifying each individual step required to complete the process. These steps are then written on Post-its, so they can be easily moved and rearranged. These Post-its are affixed to a canvas, which provides a visual representation of the process. This helps with the following steps.

**Systems** In these steps, it is examined which systems/applications are needed to execute the process. Often, this is a combination of systems with structured data (databases, etc.) and systems with unstructured data (documents, presentations, emails). For example, a document can be generated in a system with structured data, which is then sent by email to a colleague or an external partner. The goal is not to map all data flows, but to determine where which data is stored. This helps with the next step.

**Document types & Data elements** In this step, all data must be described. These are often documents such as Word, PowerPoint, or Excel files. All this unstructured data is written on Post-its and affixed to the canvas. Subsequently, it must also be examined whether specific information can be identified that may be sensitive. These are called data elements in this methodology. These can be personal data such as Name, Social Security Number, or date of birth. But also other types of data such as quote numbers, customer numbers, customer names, identification numbers for intellectual property, specific columns in a database, etc. All these data elements are also written on Post-its. When a document type can be identified by a data element, the Post-it of the data element is placed on or near the document type. The remaining data elements are placed separately from the data types on the canvas.

### 4.2 Data Classification Canvas

This canvas is used for classifying information based on the Traffic Light Protocol (TLP) and describing measures per classification level.

**Impact of Breach** Classifying data is essential to be able to take the right security measures and ensure the integrity and confidentiality of information. Determine the classification level for each document type or data element according to the Traffic Light Protocol (TLP) Classification Levels:

1. **TLP: White**
   * **Description:** Information that may be publicly shared. There are no restrictions on the dissemination of this data.
   * **Examples:** Press releases, public reports, marketing material.
2. **TLP: Green**
   * **Description:** Information that may be shared within the organization and with partners, but may not be made public.
   * **Examples:** Internal policy documents, operational procedures, non-public research results.
3. **TLP: Amber**
   * **Description:** Information that must be restricted to a specific group within the organization. This data may not be shared outside the organization without permission.
   * **Examples:** Project plans, internal emails, customer data.
4. **TLP: Red**
   * **Description:** Highly sensitive information that may only be shared with specific individuals within the organization. The dissemination of this data must be strictly controlled.
   * **Examples:** Confidential business strategies, financial data, personal information of employees.

Questions that can help determine the classification level are:

* How bad would it be if this data fell into the wrong hands?
* Who is allowed to view this data?
* What are the consequences of leaking this data?
* Are there legal obligations we must comply with in relation to this data?

A detailed damage table that can be used for classification based on TLP is included in the appendix.

**Measures** After the document types and data elements have been classified, the measures must be formulated. Each higher level in the classification adds measures to the preceding level. This means that when a document is classified as Amber, the measures for White and Green classification must also be taken. Examples of such measures include the use of encryption to encrypt sensitive information, the application of access controls to ensure that only authorized persons have access to certain data, the establishment of insider risk management, and the implementation of Data Loss Prevention (DLP) policies to prevent sensitive data from being unintentionally shared or leaked.

Once all these steps have been completed, it is known which data is processed within a process, what the classification of this data is, and how it should be protected.
