### VI.	Stateless Processes

Execute the app as one or more stateless processes – All the processes in a Twelve-factor app are stateless and share-nothing. Any data that needs to be persisted, must be stored in a stateful backing service (such as a Datastore). For instance, by making applications aligned with the stateless behavior of REST, the services can be horizontally scaled as per the requirements without any impact.

