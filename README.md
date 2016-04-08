
# <img src="https://raw.githubusercontent.com/Charles-Wang-uni/UMTG/master/images/logo.png" width="200">

UMTG is a toolset for automatically generating executable and traceable system test cases from use case specifications and domain model. In order to extract behavioral information from use case specifications and enable test automation, UMTG employs Natural Language Processing (NLP), a restricted form of use case specifications, and constraint solving.

UMTG is integrated with two tools, IBM Doors and IBM Rational Rhapsody that are widely adopted in industry to manage requirements and design systems. 

### UMTG plug-ins for IBM DOORS

UMTG plug-ins for IBM DOORS is aimed at helping engineer to write high quality Use Case Specifications by following a Restricted Use Case Modeling (RUCM) Methodology.

RUCM relies on a use case template and a set of restriction rules for textual Use Case Specifications (UCSs) to reduce the imprecision and incompleteness inherent to UCSs. Controlled experiment evaluation of RUCM is easy to apply, has enough expressive power, helps improve the understandability and the quality of use cases and facilitates automated analysis.

UMTG extends the original RUCM for test generation purpose and provides facilities help engineer to write high quality UCSs that follow the template and obey all the rules.

UMTG employs Natural Language Processing (NLP) to process the UCSs :

1) Find violations of the template or restriction rules that may course ambiguity.
2) Extract the behavioral information of the system which is used for test generation.
