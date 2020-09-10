# ML-Project-4-Exoplanets


#### Project Goal

The goal of this project was to predict potential exoplanets that are earth-size and smaller within the habitable zone of their respective sun using a variety of classification models.

#### Conclusion

Under normal circumstances I would only report one model, whether it be an ensemble of models or one classification model but I was curious on what my best two models would predict and how differnet they were when it comes to predicting unseen candidate data.

After extracting 2418 candidates, I used my best two models to classify them.
* SVC predicted there would be 994 potential earth-sized and smaller exoplanets within the habitable zone
* Random Forest predicted there would be 829 potential earth-sized and smaller exoplanets within the habitable zone

![](Pictures/countcan.JPG)

If I was part of NASA's team that is involved in the Kepler's mission, I would attempt to validate the candidates my models predicted. 

# Final thoughts 

The models and their final **recall** performance was;
* Logistic Regression (87%)
* KNN (86%)
* Decision Tree (84%)
* Random Forest (89%)
* SVM (90%)


#### Data Source

This dataset was obtained by [California Institute of Technology (Caltech)](https://exoplanetarchive.ipac.caltech.edu/index.html) which hosted NASA's exoplant archive. 
This dataset has the most accurate and updated dispositions, stellar, and planetary information. 

#### Data Description

Please visit the [Caltech documentation](https://exoplanetarchive.ipac.caltech.edu/applications/DocSet/index.html?doctree=/docs/docmenu.xml&startdoc=1) to understand what each column/feature entails. 

