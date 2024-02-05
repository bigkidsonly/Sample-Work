This folder contains original queries to monitor and uplift anomolies in our quality control pipeline. There are two projects: an automated weekly email to a Program Manager, informing them of the topline issues emerging from their state, and a National Dashboard for a small team of National data staff to pick up on emerging to-do's across all 10 states.


[Email: Count of Forms by QC Visual Review Response](https://github.com/bigkidsonly/SampleQueries/blob/main/QCAnalysis/CountFormsbyQCResponse.sql)


[Quality Control Dashboard Scripts](https://platform.civisanalytics.com/users/sign_in/#/exports/154571384)

- [FlagsbyType.sql](https://github.com/bigkidsonly/SampleQueries/blob/main/QCAnalysis/FlagsbyType.sql) populates the `flags` table

- [Ready for Delivery by Turf](https://github.com/bigkidsonly/SampleQueries/blob/main/QCAnalysis/ReadyforDeliverybyTurf.sql) populates `delivery_auto` table

- [Ready for Coversheet](https://github.com/bigkidsonly/SampleQueries/blob/main/QCAnalysis/ReadyforCoversheet.sql) populates `weird_statuses` table

- [Forms Over Turnaround](https://github.com/bigkidsonly/SampleQueries/blob/main/QCAnalysis/FormsOverTurnaround.sql) populates `turnaround` table

- [Flags by Type](https://github.com/bigkidsonly/SampleQueries/blob/main/QCAnalysis/FlagsbyType.sql) populates `flags` page
