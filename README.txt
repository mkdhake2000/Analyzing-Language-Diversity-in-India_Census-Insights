Plugins-
Software: python3 jupyter notebook (.sh files run python3 jupyter notebooks)

Environments: python 3.7.3


Python Libraries: pandas v1.3.2, numpy v1.20.2, openpyxl(for reading excel files), scipy 1.7.2

Programs-

.sh files:

assign2.sh 
top level script that runs the entire assignment 

percent-india.sh
runs Q1.ipynb as
jupyter nbconvert --to notebook --execute Q1.ipynb

gender-india.sh
runs Q2.ipynb as
jupyter nbconvert --to notebook --execute Q2.ipynb

geography-india.sh
runs Q3.ipynb as
jupyter nbconvert --to notebook --execute Q3.ipynb

3-to-2-ratio.sh
runs Q4-1.ipynb as
jupyter nbconvert --to notebook --execute Q4-1.ipynb

2-to-1-ratio.sh
runs Q4-2.ipynb as
jupyter nbconvert --to notebook --execute Q4-2.ipynb

age-india.sh
runs Q5.ipynb as
jupyter nbconvert --to notebook --execute Q5.ipynb

literacy-india.sh
runs Q6.ipynb as
jupyter nbconvert --to notebook --execute Q6.ipynb

region-india.sh
runs Q7.ipynb as
jupyter nbconvert --to notebook --execute Q7.ipynb

age-gender.sh
runs Q8.ipynb as
jupyter nbconvert --to notebook --execute Q8.ipynb

literacy-gender.sh
runs Q9.ipynb as
jupyter nbconvert --to notebook --execute Q9.ipynb

INPUT FILES:
Input files are stored inside INPUT folder

OUTPUT FILES:
Output files are stored inside OUTPUT folder

Jupyter Notebook files:

Q1.ipynb
Input: 'DDW-C18-0000.XLSX', 'DDW_PCA0000_2011_Indiastatedist.xlsx'
Output: percent-india.csv

Q2.ipynb
Input: 'DDW-C18-0000.XLSX', 'DDW_PCA0000_2011_Indiastatedist.xlsx'
Output: gender-india-a.csv, gender-india-b.csv, gender-india-c.csv

Q3.ipynb
Input: 'DDW-C18-0000.XLSX', 'DDW_PCA0000_2011_Indiastatedist.xlsx'
Output: geography-india-a.csv, geography-india-b.csv, geography-india-c.csv

Q4-1.ipynb
Input: 'DDW-C18-0000.XLSX', 'DDW_PCA0000_2011_Indiastatedist.xlsx'
Output: 3-to-2-ratio.csv

Q4-2.ipynb
Input: 'DDW-C18-0000.XLSX', 'DDW_PCA0000_2011_Indiastatedist.xlsx'
Output: 2-to-1-ratio.csv

Q5.ipynb
Input: 'DDW-C18-0000.XLSX', 'DDW-0000C-13A.xlsx'
Output: age-india.csv

Q6.ipynb
Input: 'DDW-C19-0000.XLSX', 'DDW-0000C-08.xlsx'
Output: literacy-india.csv

Q7.ipynb
Input: 'DDW-C18-0000.xlsx', 'DDW-C17-0000.XLSX', (for each state with code 01 to 35)'DDW-C17-state-code00.XLSX'(stored in STATES folder)
Output: region-india-a.csv, region-india-b.csv

Q8.ipynb
Input: 'DDW-C18-0000.XLSX', 'DDW-0000C-13A.xlsx'
Output: age-gender-a.csv,age-gender-b.csv,age-gender-c.csv

Q9.ipynb
Input: 'DDW-C19-0000.XLSX', 'DDW-0000C-08.xlsx'
Output: literacy-gender-a.csv, literacy-gender-b.csv, literacy-gender-c.csv

How to use:
In order to run all programs sequentially, run the following command from the terminal-
bash assign2.sh 