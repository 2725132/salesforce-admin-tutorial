#**Salesforce Training**

#Lead:
    -A prospect you are targeting for marketing purposes.
    -An individual who has expressed interest in your product or service.
    -Potential Customer.
    
##Lead Object:
    -Capture business card information.(Maybe personal informations)
    -Can be captured via the Web.
    -Is assigned to ownership either manually or via assingment rules.

##How can be created?
    -Manually by users.
    -Imported using the import wizard for leads
    -Imported via API
    -Captured via **web-to-lead**
    
##Lifecyle of a lead
    -Receive by some entry point like web
    -Converted to Opportunity
    -Can be found inside Queues

##Converting Leads
    -Lead qualification depends on your business process
    -Lead information is mapped to business object (**Account**, **Contact** or **Opportunity**)
    -Data validation rules ensure that only properly completed leads are converted.
    
##Who Should handle Leads?
    ###Queue (Collection of Records)
        -A queue can contain public groups, roles, subordinates and users.
            
        -When you create a queue, a view is *automatically* added to the lead home page.
            
        -Members of the queue are free to accept leads from the queue

        -Queue are associated to leads e and accounts ###**ONLY**
        
##Assignment Rules
    -Specify how leads are assigned to **users** and **queues**.
    
    -Each rule can contain multiple entries.
    
    -Only one rule can be in effect at any time.