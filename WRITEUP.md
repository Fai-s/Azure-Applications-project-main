# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Answer:
 - VM:
    - The CMS app does not have a heavy load of content that requires maintaining the whole operating system or to scale up the processing power and it's expensive.

 - App Service:
    - It's based to host web applications like CMS app and has high availability and auto-scaling but its charges depends on the plan we choose so, it's likely to be cheaper than VM. 

 finally, my choice will be the App Service.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Answer:
 I might change to VM if there was a massive increase of users for the CMS app and there was a need for new development with tools not supported by the App service.
