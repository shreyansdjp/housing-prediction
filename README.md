# Housing Price Prediction

A learning project exploring how to predict house sale prices using Perth, Western Australia property data.

## Dataset

Perth residential property sales sourced from [Kaggle](https://www.kaggle.com/datasets/syuzai/perth-house-prices?resource=download).

### Columns

| Column | Description |
|--------|-------------|
| `ADDRESS` | Street address of the property |
| `SUBURB` | Perth suburb where the property is located |
| `PRICE` | Sale price of the property in AUD (target variable) |
| `BEDROOMS` | Number of bedrooms |
| `BATHROOMS` | Number of bathrooms |
| `GARAGE` | Number of garage/car spaces |
| `LAND_AREA` | Total land area in square metres |
| `FLOOR_AREA` | Floor (building) area in square metres |
| `BUILD_YEAR` | Year the property was built |
| `CBD_DIST` | Distance from the property to Perth CBD in metres |
| `NEAREST_STN` | Name of the nearest train station |
| `NEAREST_STN_DIST` | Distance to the nearest train station in metres |
| `DATE_SOLD` | Month and year the property was sold (MM-YYYY) |
| `POSTCODE` | Australia Post postcode of the property |
| `LATITUDE` | Geographic latitude coordinate (sourced from data.gov.au) |
| `LONGITUDE` | Geographic longitude coordinate (sourced from data.gov.au) |
| `NEAREST_SCH` | Name of the nearest ATAR-applicable school |
| `NEAREST_SCH_DIST` | Distance to the nearest ATAR-applicable school in kilometres |
| `NEAREST_SCH_RANK` | Ranking of the nearest ATAR-applicable school (lower number = higher rank; missing if school is unranked) |

## Setup

Requires Python 3.11+ and [uv](https://github.com/astral-sh/uv).

```bash
uv sync
uv run jupyter notebook
```
