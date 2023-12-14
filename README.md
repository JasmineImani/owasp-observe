<p align="center">
<img src="https://imgur.com/5ULuhtJ.png" height="90%" width="90%" alt="owasp logo"/>
</p>

<h1>OWASP ZAP - Observe Results</h1>
This tutorial outlines the observation of OWASP ZAP test results on a Windows OS.<br />


<h2>Environments and Technologies Used</h2>

- OWASP ZAP
- Java 8 or later

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Steps</h2>

<p>
<img src="https://imgur.com/y1fSBlM.png" height="60%" width="60%" alt="owasp-install Steps"/>
</p>
<p>
Once testing is complete, you can view the results. The report includes a detailed mapping of all the Gruyere instance's pages and subpages and any hidden, potentially forgotten, or unsecured pages. It also lists any resources used to manage these pages.

1. In the Tree window, expand Sites.
2. Expand other sites to see more URLs discovered and explored.
3. As ZAP searches and indexes a site, it sends various test requests to pages that it discovers. ZAP creates an alert for any page with a potential vulnerability. In the Information window, click the Alerts tab to view a list of all vulnerabilities detected.    

</p>
<br />

<p>
<img src="https://imgur.com/clJJoRt.png" height="80%" width="80%" alt="open-owasp Box Steps"/>
</p>
<p>
ZAP assigns a risk type to each vulnerability, and the color of the flag for each vulnerability indicates the vulnerability's risk type. Red means high, orange means medium, yellow means low, blue means informational, and green means false positive.

1.  Click an alert to view additional information about it, and expand the alert to display the URL or URLs that triggered it.    
2. To view alerts by node, first, in the Tree window, right-click a node (on Mac, press Ctrl and click the node). Lastly, click Alerts for This Node from the pop-up menu.  

</p>
<br />
