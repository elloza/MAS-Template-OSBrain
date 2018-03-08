# MAS-Template-OSBrain
Template for MAS developed with OSBrain

This is a simple example of MAS using OSBrain:

* **Persistence Agent**: which is responsible of the data access.
* **Prediction Agent**: which is in charge of request the data to the persistence agente and
 build the predictions for WebAPI agent given a user id and GPS coordinates.
* **WebAPI Agent**: which is responsible to mount a simple end-point with Flask to serve predictions to third party applications.


The communication is performed in a scheme of synchronous communication. For other types of communication
read the documentation [OSBrainDOC](http://osbrain.readthedocs.io/en/stable/). 