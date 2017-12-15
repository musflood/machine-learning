# machine-learning
Practice using Jupyter Notebook and other analysis packages to analyze data.

## Boston Housing

Analysis of the Boston Housing data, compiling data on home values in suburbs in Boston from 1993, from [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html).

Consists of 506 samples with the following categories:

|Field | Description |
|-------|-------------|
|CRIM   |  per capita crime rate by town |
|ZN     |  proportion of residential land zoned for lots over 25,000 sq.ft. |
|INDUS  |  proportion of non-retail business acres per town |
|CHAS   |  Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) |
|NOX    |  nitric oxides concentration (parts per 10 million) |
|RM     |  average number of rooms per dwelling |
|AGE    |  proportion of owner-occupied units built prior to 1940 |
|DIS    |  weighted distances to five Boston employment centres |
|RAD    |  index of accessibility to radial highways |
|TAX    |  full-value property-tax rate per $10,000 |
|PTRATIO|  pupil-teacher ratio by town |
|B      |  1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town |
|LSTAT  |  % lower status of the population |
|MEDV   |  Median value of owner-occupied homes in $1000's |

For analysis, fields were isolated and then compared using [Matplotlib](http://matplotlib.org/) for visualization.

## Seattle Trees

Analysis of the Washington DC Tree data, compiling current data on Urban Forestry Administration (UFA) managed trees and tree locations in DC, from [Open Data DC](http://opendata.dc.gov/datasets/urban-forestry-street-trees).

Consists of 170,975 samples with the following categories:

| Field | Description |
|-------|-------------|
|X|Latitude of location|
|Y|Longitude of location|
|OBJECTID|Internal feature number|
|FACILITYID|Unique Tree Identifier|
|VICINITY|address in immediate vicinity of the tree|
|WARD|Ward|
|TBOX_L|Tree box length|
|TBOX_W|Tree box width|
|WIRES|Overhead eletrical wires|
|CURB|Curb Type|
|SIDEWALK|Sidewalk Type|
|TBOX_STAT|Plantable status of location|
|RETIREDDT|Date of location retirement|
|SCI_NM|Scientific Name|
|CMMN_NM|Common Name|
|DATE_PLANT|most recent planting date of location|
|DBH|diameter at breast height (This tree girth is commonly measured at 4.5 feet from the soil surface.)|
|DISEASE|Observation of tree disease incidence|
|PESTS|Observation of tree pest incidence|
|CONDITION|Generalized tree health via visual inspection|
|CONDITIODT|Most recent date of condition inspection|
|OWNERSHIP|Ownership of tree|
|TREE_NOTES|Comments|
|ONEYEARPHOTO||
|SPECIALPHOTO||
|PHOTOREMARKS||
|ELEVATION|Level of soil at base of tree or in tree box|
|SIGN|Type of sign in close proximity to tree|
|TRRS||
|WARRANTY|Planting season when plant warranty began|
|FAM_NAME|Scientific family name|
|CREATED_USER||
|CREATED_DATE||
|EDITEDBY||
|LAST_EDITED_USER||
|LAST_EDITED_DATE||
|GENUS_NAME|Scientific genus name|