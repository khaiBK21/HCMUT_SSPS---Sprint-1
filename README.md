# HCMUT_SSPS---Sprint-1
HCMUT_SSPS is Student Smart Printing Service. It is used to serve students in HCMUT to print their documents.
## Domain contexts
Throughout the length of a study program at a university, students have a need to use printing utilities elsewhere for a number of purposes, such as printing lecture slides and reading materials, printing form templates or printing personal files. However, different printing locations can charge fees differently depending on the owners’ need for profit. Therefore, a university printing system can provide an opportunity for universities to make revenue from buying printing services whilst enabling students a convenient way to print documents in a safe and controlled environment in the university.
## Stakeholders
Some of the relevant stakeholders are students and HCMUT_SPSO (Student Printing Service Office). First of all, students have the need for a reliable system which they can use to print their documents according to how they want. A simple and concise interface is also what they want for the printing system. Meanwhile, for HCMUT_SPSO, one of the most essential needs is a system which is capable of providing necessary services as well as meeting the students’ needs. The office also wants that system to be designed so that they can monitor students’ interaction and allocate the system’s resources as efficiently as possible.
## Functional requirements
### Students
- Students can use the system to print the documents.
- Students can upload a document file onto the system, choose a printer, and specifying the printing properties such as paper size (A3 or A4 with one A3 is counted as two A4s), pages (of the file) to be printed, one-/double-sided, number of copies, etc.
- Students can view their printing log for a time period together with a summary of number of printed pages for each page size.
- Students can buy some more pages that they are allowed to print using the feature Buy Printing Pages of the system.
- Students can use online payment method to buy more pages.
### SPSO
- SPSO can configure the permitted file types.
- SPSO can view the printing history of all students or a student for a time period (date to date) and for all or some printers.
- SPSO can manage printers manage printers such as add/enable/disable a printer.
- SPSO can manage other configuration of the system such as changing the default number of pages, the dates that the system will give the default number of pages to all students, the permitted file types accepted by the system.
- SPSO can view the monthly or yearly report of the printing system at any time.
## Non-functional requirements
### Performance
- Time for log in should be less than 5 seconds.
- The printing properties verifying process should be less than 2 seconds.
- The system should be able to handle 1000 users’ access at the same time.
- The system should have enough storage to keep at least 10000 printing logs and 26 reports (the number of reports in 2 years)
### Reliability
- The system should be available 24/7 (with at most 5% of their operating time that it is offline)
- The system should be able to recovered quickly if it catches a crash.
### Adaptability
- The system interface should be in Vietnamese with an opportunity to switch to English in the future.
- Each printer has ID, brand/manufacturer name, printer model, short description, and the location (campus name, building name, and room number).
- The system should be connected to HCMUT_SSO authentication service for user verification.
- All the printing properties for the students to specify should be displayed in one view. 
## Use-case description table for the printing properties specification module
|Property|Content|
|---|---|
|'Use-case name'|Specify printing properties|
|'Actor'|Student|
|'Description'|Student change or choose printing properties|
|'Trigger'|Click “Print Options” button|
|'Normal flow'||
|||
