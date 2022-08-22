# Red Hat Open Security Content Automation Protocol (SCAP)

### Security Content Automation Protocol (SCAP) links
[NIST SCAP Overview](https://csrc.nist.gov/projects/security-content-automation-protocol "NIST SCAP Overview")

[OpenSCAP Website](https://www.open-scap.org "OpenSCAP Website")

[Getting started with Red Hat Insights and OpenSCAP](https://www.redhat.com/en/blog/getting-started-red-hat-insights-and-openscap-compliance-reporting "Getting started with Red Hat Insights and OpenSCAP")

[Red Hat Compliance service and the Red Hat Insights API](https://www.redhat.com/en/blog/red-hat-compliance-service-and-red-hat-insights-api "Red Hat Compliance service and the Red Hat Insights API")

### Prepare your machines for SCAP policy
[SCAP install ansible playbook](https://github.com/ericcames/RHOpenSCAP/blob/main/scapinstall.yml "SCAP Install Playbook")

### Setup Red Hat Insights Compliance SCAP policy
1. Login in to:

    [Red Hat Insights](https://console.redhat.com "Red Hat Hybrid Cloud Console")
    
2. Click on Red Hat Enterprise Linux
    
    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/RHEL.png "Logo Title Text 1")
    
3. Click on Red Hat Insights

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/Red%20Hat%20Insights.png "Logo Title Text 1")
    
4. Click on Compliance

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/Compliance.png "Logo Title Text 1")
    
5. Click on SCAP Policies -> Create new policy

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/CreateSCAP.png "Logo Title Text 1")

6. Pick your Operating System and add a filter to find your policy

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/PickOS.png "Logo Title Text 1")

7. Pick your Policy name -> Click next

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/Pickyourpolicy.png "Logo Title Text 1")

8. Make any updates -> Click next

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/adjustments.png "Logo Title Text 1")

9. Select your systems -> Click next

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/addyoursystems.png "Logo Title Text 1")

10. Select the rules that you want to apply -> Click next

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/Rulereview.png "Logo Title Text 1")
    
11. Finish!!

    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/Finish.png "Logo Title Text 1")
    
### Remediate your machines using Insights and Ansible
[Example of Insights created ansible playbook](https://github.com/ericcames/RHOpenSCAP/blob/main/example-rhel7cisremediation.yml "SCAP Install Playbook")

Click on systems and the system you would like to look at.  Some of the remediations will have manual steps to be followed for remediation and some will have ansible playbooks that can be generated.
    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/Remediations.png "Logo Title Text 1")
    
Integrate your Ansible Automation Platform with Red Hat Insights.  This will give you access to the remediation playbooks you create.  After you create your playbooks; sync your insights project and you will be able to create templates using the Insights generated playbooks.
    ![alt text](https://github.com/ericcames/RHOpenSCAP/blob/main/images/insightsandansible.png "Logo Title Text 1")



