# Data processing and visualization of the PABP binding assay raw data

The raw data contained in the csv files exported from the Agilent Bioanalyzer 2100 Expert Software can be processed and plotted in Python. Here we show how to normalize the Bioanalyzer peaks in two ways:
- To the reference peak
- To the highest peak of each sample

You will need the following files:
- One csv file containing the Ladder information. When you export the "Result Table" csv file, make sure to check the tab "Include Ladder". You can then just copy the Ladder peak table in a new csv file (for an example see the file 'Ladder_peaks.csv' in the folder T100).
- A separate csv file for each sample, which can be obtained by exporting the Aligned Sample Data tables from the Agilent Bioanalyzer 2100 Expert Software.

  
