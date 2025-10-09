# 1931-census-pl
⚠️Project development currently suspended in the inital phase.

This repository serves the reconstruction of occupation data in the 1931 census in Poland.

The 1931 census occupation data is the richest dataset on the occupation in industry and services sectors in interwar Poland. It contains data on the level of ~300 categories, but only ~60 are indicated for each district. For each district, only those 60 categories and some additional most numerous occupation categories were explicitly indicated. In case of a detailed occupation category `c_1` missing in district `d` there is always information on the number of people in a more detailed category `C`, there is frequently information on the number of employed in other subcategories `c_2`, `c_3`, etc. of the category `C` and the total number of employed in `c_1` in the whole voivodeship. I use this abundant information to reconstruct the information on all the categories in districts where they are missing.
