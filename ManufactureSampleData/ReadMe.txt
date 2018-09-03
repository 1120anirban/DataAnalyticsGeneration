####################################################################################################
	Generating Train and Test Data -- How likely is a person to register in SSY Scheme
####################################################################################################
   ||    FluxionBits    |    SSY Analytics    |    14-Aug-2018    |    Anirban Chakrabarty    ||
####################################################################################################

Description: This program will be generating simulation of Train and Test Data on how likely a person from a given occupation, of a specific age group, from a specific location etc. (we can increase / change these parameters later as and when required) is to register in SSY Scheme. This will work on existing data and give the probbilities of registering in the scheme.

The machine learning code that will be written next, is supposed to learn the inherent pattern of this probability of registration depending on the attributes occupation, age group and specific location etc.

Further analytics and choropleth BI reporting can be generated from this dataset.

Input File: SubdivisionList.csv
Input Fields: DistCode, District, Subdivision
Output File: SubdivisionPersons.csv
Output Fields: Index, DistCode, District, Subdivision, PersonName, Gender, Age, RegisteredYesNo
Output Rows: 5106 (Can be extended programatically to as much required)

####################################################################################################

Processing: GeneratingData.ipynb
1. Make sure the SubdivisionList.csv and the GeneratingData.ipynb are in the same folder.
2. Run the sections of GeneratingData.ipynb one by one.
2. Some sections may take few minutes depending on how many rows we want to generate.
3. Once each row is successfully run we get the output in SubdivisionPersons.csv file.

####################################################################################################

Support: anirbanchakrabarty@fluxionbits.com | +61 470 142229

####################################################################################################

Disclaimer: This computer program is proprietary and confidential to FluxionBits.com. This is being used for marketing purposes to the Dept. of Planning, West Bengal Govt. only. Any illegal usage of this data or program in any form is punishable under the Indian Information Technology Act, 2000 and Copyright Act, 1957.

This uses computer simulation and public domain data and is completely free from any data infringement.

####################################################################################################
