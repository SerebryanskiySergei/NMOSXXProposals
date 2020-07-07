# IS-XX: EDID

Regular **Markdown** here.

## Diagrams

First of all, we need to define use-cases that we are trying to cover with the proposed solution:

![EDID Use_cases](images/EDID_Negotiation_Use_Cases.png)

For each Use Case we have an activity diagram that represents what should happen in order to fullfill the use case.

For get receiver params use-case:

![Get_receiver_params activity model](images/Get_receiver_params_activity.png)

For manual update sender's params use case:

![Update sender's_params activity model](images/Manual_update_Source_params_activity.png)

For EDID Negotiation Use case:

![EDID Negotiation activity model](images/EDID_Negotiation_activity.png)

We are going to add more details with sequence diagram which extends each activity:

For get receiver params use-case:

![Get_receiver_params seq model](images/Get_receiver_params_sequence.png)

For manual update sender's params use case:

![Update sender's_params seq model](images/Manual_update_source_params_sequence.png)

For EDID Negotiation Use case:

![EDID Negotiation seq model](images/EDID_Negotiation_sequence.png)

Also we need to explain the data model that is used in our solution.

![EDID Data model](images/EDID_Data_Model.png)

Some more markdown

ToDo:
1) edid file -> monitor profile
2) think about source capabilities?
    can we add new resource and ask users to manually define source caps
