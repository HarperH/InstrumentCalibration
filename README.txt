Welcome to the DTCP Final Project.

	#Before you start

For now our program only works with the provided dataset so you'll need to download that in order to run it.


	#What's what

CCMR.txt - sources for code in compiledFinal.ipynb
Interim_report.docx - document describing project methodology
PressureSensorData.csv - the data used for this project
ProjectSpecs.ipynb - project goals/parameters
Project_worksheet.ipynb - models and model analysis of our data
Project_worksheet.pdf - pdf version of Project_worksheet.ipynb
README.txt - you're lookin at it
compiledFinal.ipynb - client-facing program to convert input voltages to true and analogue pressure outputs


	#Program operation

Run all code blocks in order (as long as the import block is first and the tkinter box is last it should work fine) and when
you run the last box you'll get a pop-up window asking for inputs.  Simply input the voltage you want to see a pressure for,
select your confidence interval, and press enter or click the "Calculate" button to see your results.

If you want to add your own data to our dataset you can as well, just make sure that you enter numbers in each field because
it converts each input into a float and won't work if not every box has an entry.  The "Clear Data Entries" button will
remove all user data entries, leaving only the provded default dataset.