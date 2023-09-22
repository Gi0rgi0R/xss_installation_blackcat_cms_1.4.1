# XSS in BlackCat CMS install page

Software link: BlacCat CMS [(https://blackcat-cms.org/)]

Version: 1.4.1

@author: Jorge Riopedre

Description: BlackCat CMS 1.4.1 is affected by a Cross-site scripting (XSS) vulnerability in upload/install/index.php that allows remote attackers to inject arbitrary web script or HTML via the 'Website Title' parameter.

# POC

When performing the installation and entering the site settings to install the appliance, the 'Website title' field is affected by the injection of arbitrary code:

![imagen](https://github.com/Gi0rgi0R/xss_installation_blackcat_cms_1.4.1/assets/145793179/dccd86dd-8fa8-4db3-a47e-20994b1c18a1)


![imagen](https://github.com/Gi0rgi0R/xss_installation_blackcat_cms_1.4.1/assets/145793179/bf8c4a17-e240-4e3c-8b83-9ee71b111b1f)

