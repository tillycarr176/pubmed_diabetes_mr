This code searches pubmed for various search terms
eg for gestational diabetes AND mendelian randomisation
'(("mendelian randomisation"[tiab] OR "mendelian randomization"[tiab]) AND ("gestational diabetes"[tiab])'
multiple spellings are captured
[tiab] means it is restricted to searching in the title and abstract
number of search results will increase with time as more papers are added

i - searches pubmed for all papers on MR and each type of diabetes listed.
Makes a bar chart of these absolute totals (fig 1A)

ii - searches for total number of papers on each type of diabetes. 
Makes a table of MR and diabetes papers (i results) and total papers (ii results)

iii - searches for MR, diabetes and "gene"[tiab] papers. 
Searches for total diabetes and "gene"[tiab] papers. 
Makes a table of these. 

iv - combines this MR/total table and the MR-gene/total-gene table together.
Calculates their percentages.
Makes a bar chart (fig 1B)

v - searches using a yearly restriction using example dates, extrapolated to make fig 1C

yearly_totals - searches total number of papers published each year between 2000-2025. 
Makes a line chart of the cumulative total (fig 1D)
