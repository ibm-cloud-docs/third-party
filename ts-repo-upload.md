---

copyright:
  years: 2020, 2021
lastupdated: "2021-04-01"

keywords: troubleshoot software, HTTPS protocol, repo, github, tgz

subcollection: third-party

content-type: troubleshoot

---

{:tsSymptoms: .tsSymptoms}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:external: target="_blank" .external}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:beta: .beta}
{:troubleshoot: data-hd-content-type='troubleshoot'}

# Why can't I upload my source details from my GitHub repository?
{: #repo-upload-error}
{: troubleshoot}

The process to sell third-party software is available solely for providers that understand that the onboarding process is still under development. With the current release, you can bring your own licenses or deliver your third-party software for free. If you’re interested in trying it out, contact us at kdmeyer@ibm.com. 
{: beta}

You receive the following error message when you try to upload your source details from a GitHub repository:
{: tsSymptoms}

`There was an error while contacting this URL.`

This error typically occurs because the repository doesn't support HTTPS protocol or your Helm chart repository does not include an `index.yaml` file. 
{: tsCauses}

Make sure that your repository supports HTTPS protocol and your repository includes an `index.yaml` file. Alternatively, you can also point directly to a `.tgz` release file, which you can generate in your public GitHub repository. For more information, see [Managing releases in a repository](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/managing-releases-in-a-repository){: external}.
{: tsResolve}
