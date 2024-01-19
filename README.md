## Nashville-Housing
Data Cleanup using SQL

This is to demonstrate data cleaning before using it for analysis 


### Data Source:  https://www.kaggle.com/datasets/tmthyjames/nashville-housing-data


### Issues that needed to be addressed:

- The Date is not in the standard format.
- Some rows in the PropertyAddress is NULL
- The PropertyAddress has the City and House Address in the same column.
- The OwnerAddress has the state, city, and address in the same column.
- A few rows in the SoldAsVacant have Y and N instead of Yes or No.
- Some duplicate rows need to be removed.
- Some Columns would not be useful for the analysis and therefore should be deleted.


### METADATA:
- UniqueID — id number attributed to a buyer.
- ParcelID — code attributed to a land.
- LandUse — shows the different uses of land.
- SalesPrice — cost of land
- LegalReference — citation is the practice of crediting and referring to authoritative documents and sources.
- OwnerName_ name of land owner
- Acreage — the size of an area of land in acres
- LandValue — the worth of the land
- Building Value — worth of a building
- Total Value — landvalue + building value
- YearBuilt — year the building was built
- FullBath — a bathroom that includes a shower, a bathtub, a sink, and a toilet.
- HalfBath — a half bathroom only contains a sink and a toilet
- Sale_Date — date when the land was sold
- SaleAddress — address of land sold
- City — location of land
- Owner_Address — owners house address
- OwnerCity — city where owner lives
- OwnerState — state where owner is located
