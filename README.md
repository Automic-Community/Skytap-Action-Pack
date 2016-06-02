*Skytap Action Pack*
=============


Incorporate Skytap IaaS into Your Release Workflows
http://github.com/Automic-Community/Skytap-Action-Pack

<!-- List of attached files -->
Contents of Solution Package:

						
								*PCK.TK_SKYTAP_1.0.0.zip
								
								*skytap-logo1.png
								
								*Untitled.png
								
						


Documenation and Instructions
---

<p style="box-sizing: border-box; margin: 0px 0px 10px; max-height: 99999px; word-wrap: break-word;"><span><span><img src="https://448bb31d92917ba3390f-4a8f48d20b0d8c78b979208d38d37653.ssl.cf1.rackcdn.com/696/screenshots/skytap-logo1.png" alt="" width="200" height="55" /></span></span></p>
<p style="box-sizing: border-box; margin: 0px 0px 10px; max-height: 99999px; word-wrap: break-word;"><span><span>Skytap is a cloud provider that moves beyond Infrastructure-as-a-Service (IaaS) by allowing enterprises to package compute, networking, and storage together with their complete operational stack into environments that can be deployed and cloned in seconds. Rather than a jumble of tagged AMIs, AKIs, and VPCs, Skytap organizes your networks and VMs into self-contained environments that support on-premises architectures, networks, and operating systems.</span></span></p>
<p style="box-sizing: border-box; margin: 0px 0px 10px; max-height: 99999px; word-wrap: break-word;"><span><span>&nbsp;</span></span></p>
<p style="box-sizing: border-box; margin: 0px 0px 10px; max-height: 99999px; word-wrap: break-word;"><span><span>The Skytap Action Pack allows you to build visual workflows to fully automate common Skytap related activities.</span></span></p>
<h2>Pre-Requisites</h2>
<ul>
<li>Automic 11.2 or above</li>
<li>Automic Web Services Agent 3.x</li>
<li><a href="https://marketplace.automic.com/details/plugin-manager" target="_blank">Plugin Manager</a></li>
<li>Skytap account. (Tested against Skytap Trial Account)</li>
</ul>
<h2>Installation</h2>
<ol>
<li>Download the Skytap Action pack GitHub project archive from Automic marketplace</li>
<li>Extract the archive to get the&nbsp;PCK.TK_SKYTAP_1.X.X.zip file, this is the actual action pack.</li>
<li>Log onto the Automation Web Interface (ECC).</li>
<li>Navigate to Administation tab</li>
<li>Click&nbsp;<strong>Packs</strong>&nbsp;then click&nbsp;<strong>Install Pack</strong></li>
<li>Select the action pack that you downloaded. Upon installation, the pack PCK.TK_SKYTAP should appear</li>
</ol>
<h3>Configuration</h3>
<p>The integration uses the Automic web services agent. You must create a web service connection object which includes your Skytap username and password, or username and API token. Please refer to the Skytap documentation for further details.</p>
<p>The connection object PCK.TK_SKYTAP.PRV.CONN is provided as a template.</p>
<h3>Workflows</h3>
<p>A sample workflow PCK.TK_SKYTAP.DEMO_WORKFLOW is provided to show how the actions can be combined. The workflow performs the following tasks:</p>
<ol>
<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Create an environment from a VM</li>
<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Rename the VM</li>
<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Power on the VM</li>
</ol>

Copyright and License
---

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (https://marketplace.automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (https://marketplace.automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).