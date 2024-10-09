# MassMailer Demonstrations, powered by SIGNiX
![SIGNiX (4c) (Custom)](https://github.com/user-attachments/assets/af5bbf18-ee52-41b3-9637-cd28c5537ac4)

[SIGNiX](https://www.signix.com/) digital signature platform has MassMailer feature for distributing documents and forms and collecting data and signatures


## Description
This project contains files for a showcase and tutorial of the SIGNiX MassMailer feature.

There are two demonstrations included. One is for collecting data from lessees of Zoom Jet Packs,
a fictional company that is required to collect insurance details on an annual basis. The other is
for Zoom Jet Packs to distribute an important recall notice, and to track which customers have 
opened and acknowledged it.

## About MassMailer
MassMailer is a feature to create transactions in volume. Capabilities include:
* Distribute documents and forms
* Personalize / prepopulate forms for each transaction (similar to Mail Merge)
* Collect signatures and signed documents / forms
* Collect data via forms (and downloaded in aggregate)
* Track the completion of transactions via a dashboard

MassMailer is a no-code solution. It is driven entirely through the SIGNiX MyDoX UI, with supporting CSV files.
To find out more about SIGNiX, and to request a demo or trial, click [here](https://www.signix.com/).

MassMailer is a user-driven feature with a complete UI. It is CSV-driven, so data is easy to
prepare in Excel or with a database. Results can be processed in Excel, offering all the data
collected via forms. Of course, the collected data could then be uploaded to a database or 
business application.

Documents and forms are in PDF format. SIGNiX provides an interactive editor, for adding
form fields and signature fields to PDFs. The form fields can be prepopulated from the input
CSV, or used to collect data from signers.

## Table of Contents
- Installation
- Usage
- Explanation of files
- Contributing
- License
- Contact

## Installation
MassMailer is a no-code solution, so there is no installation of code required. However, to use
the demo files, they should be downloaded to a local desktop. To get the files in a zip file,
use the Release package, and then extract the files from the zip archive.

## Usage
There are two scenarios covered by the sample files:
1. Data collection in volume
   1. Zoom Jet Packs is required to collect insurance details from their lessees on an annual basis.
   2. A standard form (included in the samples) is used to notify lessees and request data.
   3. The form is tagged to include prepopulated data and fields for collecting data.
   4. The form must be signed by the lessee. The act of signing also submits the user-provided data.
   5. A template can be used, so the same tagged form can be reused multiple times. This allows a test run, followed by a full production run. CSV files for each are included in the samples.
   6. During the notification and collection process, transactions can be tracked, showing who has submitted their forms, and which forms are still outstanding.
   7. Data collected is processed in Excel, making it ready for upload to a business application and preparing it for analysis.
2. Document distribution and tracking of acknowledgements
   1. Zoom Jet Packs must send a recall notice to certain customers, and track acknowledgements.
   2. A recall notice document is included in the sample files, along with a corresponding CSV file for distribution list.
   3. The document can be uploaded to SIGNiX, tagged for requesting acknowledgement, and then sent to the distribution list.
   4. Acknowledgements can be tracked.

In both scenarios, the general process of using MassMailer is as follows:

![MassMailer-Process](https://github.com/user-attachments/assets/8bb3185f-9a48-4763-bf1a-f43e071ae0e7)

When analyzing your document / form, you should identify:
- Personalized / prepopulated fields
- Data collection fields
- Signature and date fields

![MassMailer-Form-Analysis](https://github.com/user-attachments/assets/a262421f-5463-42f2-bcec-77bbb8b807c4)

To prepare the CSV file that will contain the distribution list, prepopulated data and columns for data collection, follow the instructions here:
https://knowledge.signix.com/helpcenter/how-do-i-create-the-mass-mailer-csv-import-file 

And, for more general information on using MassMailer, click here:
https://knowledge.signix.com/helpcenter/how-do-i-use-the-mass-mailer-feature

A screen-by-screen walkthrough of the two scenarios is included in the sample files.
[MassMailer Walkthrough Screens](https://github.com/kmsignix/zoom-massmailer/blob/main/MassMailer%20Walkthrough%20Screens.pdf)

The output of the MassMailer report feature has columns for both tag names and tag values. To transform the MassMailer 
report data into a more general-purpose format, an Excel file containing a Power Query is used and included in the sample files.

To use this Excel file for transforming the report output:
1. Request and download the report data in a zip format.
2. Extract the files.
3. Download the Excel file and put it in the same folder as the extracted files.
4. Open the Report.csv file and copy all the data.
5. Paste the data “as values” at row A1 in the INPUT tab. The table will automatically size to fit the pasted data.
6. Open the OUTPUT tab, and right-click on the green table. Select Refresh. The OUTPUT tab should now show the data in simple named columns.

It may be necessary to format date columns, etc., prior to further processing.

## Explanation of Files
- Documents / Forms / PDFs
  - Example PDFs for the insurance data request and recall notice.
- CSVs
  - Example CSVs that contain distribution lists and details of prepopulated fields and data to be collected.
- Excel file
  - File to transform the output of the Report to a more general-purpose format.
- Walkthrough PDF
  - Screen-by-screen walkthroughs of the scenarios.

## Contributing
Guidelines for contributing coming soon.

## License
This project is distributed under the MIT license. See the LICENSE.txt file for details.

## Contact
Contact information coming soon.
