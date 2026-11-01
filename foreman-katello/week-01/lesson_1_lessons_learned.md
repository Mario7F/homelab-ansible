## What is Hammer?

#### - Hammer is the command-line interface for Foreman and Katello.

#### - Instead of doing everything in the web GUI, Hammer communicates with the Foreman API.

#### - It asks Foreman to perform operations through Foreman's application/API layer.



## What is Pulp?

#### - Pulp is the content engine underneath Katello.

#### - Katello does not personally store every RPM.

#### - In a way Katello is the content manager and Pulp is the warehouse.


## PostgreSQL

#### - Foreman/Katello needs a database to remember configuration and application state.


## What is Smart Proxy?

#### - The Smart Proxy is how Foreman reaches out and performs infrastructure-related functions.

#### - The Smart Proxy can act as the execution/interface layer.


## foreman-maintain

#### - foreman-maintain is an administrative/maintenance utility for Foreman/Katello environments.

#### - It knows about the platform as a whole rather than just one Linux service.
