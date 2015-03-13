## Basic structure and the functionality of iPhone Application ##

**Leave the Patient Side as just a Senor for now**

**Doctor - Patient Communication**

  * - doctorToPatient() : establish the communication
  * - patientToDoctor() : to provide the patient id to the doctor. (data type to be specified.)

**Doctor - Database Communication**

`"For the code that deal with the communication, mark with comments so that the code may be changed in the future. Specifically that a layer of encryption may be added to the communication."`


  * doctorToDB( id, … ):  to query the relevant medical records and information
  * getExpert(): To return the data from the expert system.
> > (Temporary expert system in the doctor's app)
  * getData(): Get the data from the DB
  * forwardDoctor(): Give the risk and decision making the doctor

**The privacy and security on Database**

  * rivacy and Integrity
  * ecurity on data retrieval