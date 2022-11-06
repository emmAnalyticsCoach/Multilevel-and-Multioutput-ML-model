# Multilevel-and-Multioutput-ML-model

The aim of this project is to apply the knowledge that has been acquired in the BI & Big data
program within a hospital tumor registry (RTH). Specifically, we will work on the development of
2 products:
- The first is focus on the building and optimization of an application with shiny that it is used as
a dashboard to represent and analyze the data that is collected in the registry.
- And the second focuses on the development of a model which uses machine learning that will
be used to extract molecular information from text.
This text consists of a series of classifications and protocols that are in the ESPOQ data source
when a chemotherapy treatment is administered to the patient.
Finally it has been possible to create and optimize the dashboard with shiny and a proof of that
it has been uploaded to production on website of company.
Regarding the second project, it has been possible to develop a multilevel and multioutput
model with crossvalidation to extract information from molecular markers with a good precision
of around 94%. The SGDClassifier technique has been chosen as the best model.
