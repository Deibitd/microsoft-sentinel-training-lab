## Bug Fixes / Troubleshooting

### Issue 1
**Problem:**
- Had an error saying my workspace wasn't onboarded even though I had just finished onboarding it.

**Cause:**  
- Cause unknown, though probably of my own doing.

**Resolution:**  
- Simply redeployed as it hadn't gone through and spit an error back when trying to deploy Sentinel.

**Notes:**  
- Take extra time making sure everything in deployments go smoothly as rushing through can cause to further problems down the line.


---

### Issue 2
**Problem:**  
- Due to my last error, the deployment was seen as in progress, though I had cancelled it a few minutes prior.

**Cause:**  
- Cancelled deployment and hadn't made sure it was complete.

**Resolution:**  
- I had to go into my resource group "sentinel-lab-deibit" and delete the deployment from the deployments section. Once this was done, the deployment of the training program ran smoothly.

**Notes:**  
- Double check my resource groups after troubleshooting, as lingering issues may lie dormant and prevent further creations.

---

### Lessons Learned
- Stop rushing through, can lead to further mistakes and unnecessary troubleshooting
- Double check all deployments in resource groups after cancellations/errors.
  
