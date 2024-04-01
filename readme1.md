# Microsoft Learn Student Ambassador Certificate Automation

This repo simply use a template certificate docx file and generates certificates
both docx and pdf.

## Setup

- Working on Windows only.
- Required Microsoft Doc

Use the below commands in cmd

git clone https://github.com/Rtarun3606k/MLSA-CERTI-CREATE--1.git

cd MLSA-Certificate-Automate

pip install -r requirements.txt

python main_certificate.py

## Customization

In, `main_certificate.py` folder. Change your participants and your name with path and name.
In case, you have to deal with your own participate file due to your needs, you should update `list_participants` data.

Change line 33 in main_certificate.py [enter your event name]

Change line 55 in main_certificate.py [enter Ambassador Name]

in Data Template > Event Participate Template.csv [enter the participants name]

the outputs will be created in output folder in PDF and Doc formmat

Also, functions are very simple. You can implement your own versions as well.

after this u can use this link to create mail templates in csv form 
https://github.com/Rtarun3606k/CSV-data-and-mail-template.git


credits 
git clone https://github.com/muhammedogz/MLSA-Certificate-Automate.git
the code is used from above repository
