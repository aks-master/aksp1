## Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

APP SERVICE:
prebuild and readymade platfrom for fast deployments hence more prefferd in this scenario.
As this is a small scale project choosing app service saves time and developer effort as we get readymade stack for deployement and we just have to push code.

VM:
The VM allows for more customization of the app's capability. It also would really benefit developers who have already built a CMS app but it might not be supported
through App Service but could work through the VM workflow.

My Choice:
I chose App Service because the CMS app is lightweight, does not require robust compute power, and is easy to deploy through Azure. The CMS
App is straightforward and runs on a Python codebase, which is supported by App Service. Overall, a simple choice.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

APP Service:
If the CMS app needed to be updated to allow for more compute capability, hardware limitations of app serivce will be challenging. Also, being unable to control the underlying software on the
server could also cause significant issues that could break your app.

VM:
If this CMS became more popular, it could become more expensive due to requiring more hardware/compute power. A new developer
coming onboard needs to know how the VM has been customized, so the on-boarding for new devs would take a bit longer. Also,
if the CMS needed more compute capability, it could also become significantly more expensive.
