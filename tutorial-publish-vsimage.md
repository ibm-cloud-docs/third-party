---

copyright:
  years: 2021
lastupdated: "2021-06-01"

keywords: onboard software, third-party software, sell on IBM Cloud, partner center, virtual server image, virtual machine image, image, vm, vsi, publish, Terraform, tutorial, sample

subcollection: third-party

content-type: tutorial
account-plan: paid
completion-time: 30m 

---

{:shortdesc: .shortdesc}
{:screen: .screen}  
{:codeblock: .codeblock}  
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:beta: .beta}
{:external: target="_blank" .external}
{:step: data-tutorial-type='step'} 


# Publishing a virtual server image to the {{site.data.keyword.cloud_notm}} catalog
{: #vsimage-publish}
{: toc-content-type="tutorial"} 
{: toc-completion-time="30m"} 

This tutorial walks you through how to publish a virtual server image with Terraform to {{site.data.keyword.cloud}}. By completing this tutorial, you submit a request to publish the virtual server image, respond to any review feedback, and then publish the virtual server image to the {{site.data.keyword.cloud_notm}} catalog.
{: shortdesc}

The process to sell third-party software is available solely for providers that understand that the onboarding process is still under development. With the current release, you can bring your own licenses or offer your third-party software for free. If you’re interested in trying it out, contact us at kdmeyer@ibm.com.
{: beta}

This tutorial is one of four in a series that demonstrates how to onboard and publish a [sample virtual server image with Terraform](https://github.com/IBM-Cloud/isv-vsi-product-deploy-sample/tree/v1.0){: external}. As you complete the tutorial, adapt each step to fit your product's needs.

## Before you begin
{: #vsimage-publish-prereqs}

1. [Register a virtual server image in Partner Center](/docs/third-party?topic=third-party-vsimage-register).
1. [Define the product details of a virtual server image](/docs/third-party?topic=third-party-vsimage-define).
1. [Onboard a virtual server image to a private catalog](/docs/third-party?topic=third-party-vsimage-onboard).
1. [Update the visibility of a virtual server image](https://github.com/IBM-Cloud/isv-vsi-product-deploy-sample#update-the-visibility-of-your-image-patch-api){: external}.

## Request to publish the virtual server image
{: #vsimage-request-publish}
{: step}

The details of any third-party software must be reviewed by {{site.data.keyword.cloud_notm}} before it can be published to the catalog. Complete the following steps to submit a request to publish your virtual server image:

1. Go to the [Partner Center](https://cloud.ibm.com/partner-center/sell){: external} in the {{site.data.keyword.cloud_notm}} console, and click **My Products**.
1. Select your virtual server image.  
1. From the Onboarding checklist, click **Request Approval**. 
1. Select the version > **I affirm that my company is authorized to use all materials**. 
1. Click **Request Approval**.

At this point, your publishing request is reviewed by {{site.data.keyword.cloud_notm}} to ensure the required details, such as the product name, catalog entry, pricing model, and support experience, are complete and accurate. When your request is approved, you receive an email notifiying you that you can publish the virtual server image to the catalog. 

If updates are required, you'll receive a separate email with details about the required updates. After you address all review feedback, you can submit another publishing request.
{: note} 

## Publish the virtual server image
{: #vsimage-publish-submit}
{: step}

1. Navigate to the Partner Center in the {{site.data.keyword.cloud_notm}} console by clicking the link in the email that you received notifiying you that your publishing request was approved.
1. Click **Publish to catalog**.

## Next steps
{: #vsimage-publish-next}

Verify that the virtual server image is offically live in the catalog for all users. Go to the [catalog](https://cloud.ibm.com/catalog){: external}, select **Software**, and search for the name of your virtual server image. 




