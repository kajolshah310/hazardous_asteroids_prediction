# hazardous_asteroids_prediction
**Prediction whether asteroids are potentially hazardous or not**

Motivation:-
Though I don't have much knowledge about Astrophysics fields, I really am interested in this field. So, when I came across this interesting problem statement, I decided to work on it. The model for this problem statement is created using machine learning algorithms in R.\

Dataset:- https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset \
This dataset is officially maintained by Jet Propulsion Laboratory of California Institute of Technology which is an organization under NASA.

Basic column definitions(referred from Kaggle):-\
Basic Column Definition\
SPK-ID: Object primary SPK-ID\
Object ID: Object internal database ID\
Object fullname: Object full name/designation\
pdes: Object primary designation\
name: Object IAU name\
NEO: Near-Earth Object (NEO) flag\
PHA: Potentially Hazardous Asteroid (PHA) flag\
H: Absolute magnitude parameter\
Diameter: object diameter (from equivalent sphere) km Unit\
Albedo: Geometric albedo\
Diameter_sigma: 1-sigma uncertainty in object diameter km Unit\
Orbit_id: Orbit solution ID\
Epoch: Epoch of osculation in modified Julian day form\
Equinox: Equinox of reference frame\
e: Eccentricity\
a: Semi-major axis au Unit\
q: perihelion distance au Unit\
i: inclination; angle with respect to x-y ecliptic plane\
tp: Time of perihelion passage TDB Unit\
moid_ld: Earth Minimum Orbit Intersection Distance au Unit\

As this dataset is pretty huge with around 10 lakh rows and also has missinng values, I followed 2 approaches to create the model for this problem statement:-\
1) Replacing the missing values with mean of the column\
2) Removing the rows with missing values\
