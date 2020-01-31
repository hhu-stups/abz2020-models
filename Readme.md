# ABZ'2020 Case Study Models

Classical B and Event-B models accompanying the submission

- Modelling and Validating an Automotive System in Classical B and Event-B
- Michael Leuschel, Mareike Mutz, Michelle Werth

## Contents

Classical B model along with VisB visualisation, saved trace for Test 7 and images created using VisB

Event-B model as Rodin archive and ProB export along with VisB visualisation files (slightly adapted for event names)



## Abstract of Submission
We have modelled parts of the ABZ automotive case study using the B-method.
For the early phases of modelling we have used the classical B for software, while
for proof we have used Event-B and Rodin.
It is maybe surprising that classical B's machine inclusion mechanism along with
operation calls can be used for modular system modelling.
Moreover, for one particular style of modelling, the result can then be translated
 to superposition refinement with event extension in Event-B.
Before conducting the proof, we have validated our models using model checking and animation with visualizations.
The graphical visualizations were constructed using a new plugin (VisB) which
  helped uncover errors and transforms our model into an executable, interactive reference specification which
  can be examined by users without formal background.