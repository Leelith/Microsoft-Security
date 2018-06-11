
# Terminology
Is is important to understand the difference between Service Pack and Update rollup. This is an [extract from Microsoft blog post](https://blogs.msdn.microsoft.com/muaddib/2014/02/03/list-of-rollup-updates-for-windows-88-1-windows-server-2012-2012-r2/) and [this support note](https://support.microsoft.com/en-za/help/824684/description-of-the-standard-terminology-that-is-used-to-describe-micro):

>**Critical update**\
>_Definition_:\
>A widely released fix for a specific problem that addresses a critical, non-security-related bug.

>**Definition update**\
>_Definition_:\
>A widely released and frequent software update that contains additions to a product’s definition database. Definition databases are often used to detect objects that have specific attributes, such as malicious code, phishing websites, or junk mail.

>**Feature pack**\
>_Definition_:\
>New product functionality that is first distributed outside the context of a product release and that is typically included in the next full product release.

>**Security update**\
>_Definition_:\
>A widely released fix for a product-specific, security-related vulnerability. Security vulnerabilities are rated by their severity. The severity rating is indicated in the Microsoft security bulletin as critical, important, moderate, or low.

>_Additional information_:\
>Microsoft security updates are available for customers to download and are accompanied by two documents: a security bulletin and a Microsoft Knowledge Base article. For more information about the format of Microsoft Knowledge Base articles for Microsoft security updates, click the following article number to view the article in the Microsoft Knowledge Base:
> * 824689 Description of the format of Microsoft Knowledge Base articles for Microsoft Security Updates

>**Service pack**\
>_Definition_:\ 
>A tested, cumulative set of all hotfixes, security updates, critical updates, and updates. Additionally, service packs may contain additional fixes for problems that are found internally since the release of the product. Service packs my also contain a limited number of customer-requested design changes or features.

>**Update**\
>_Definition_:\
>A widely released fix for a specific problem. An update addresses a noncritical, non-security-related bug.
Update rollup

>_Definition_:\
>A tested, cumulative set of hotfixes, security updates, critical updates, and updates that are packaged together for easy deployment. A rollup generally targets a specific area, such as security, or a component of a product, such as Internet Information Services (IIS).

>**Security-only update**\
>_Definition_:\
>An update that collects all the new security updates for a given month and for a given product, addressing security-related vulnerabilities and distributed through Windows Server Update Services (WSUS), System Center Configuration Manager and Microsoft Update Catalog. Security vulnerabilities are rated by their severity. The severity rating is indicated in the Microsoft security bulletin as critical, important, moderate, or low. This Security-only update would be displayed under the title Security Only Quality Update when you download or install the update and will be classified as an "Important" update.

>**Monthly Rollup**\
>_Definition_:\
>A tested, cumulative set of updates. They include both security and reliability updates that are packaged together and distributed over Windows Update, WSUS, System Center Configuration Manager and Microsoft Update Catalog for easy deployment. The Monthly Rollup is product specific, addresses both new security issues and nonsecurity issues in a single update and will proactively include updates that were released in the past. Security vulnerabilities are rated by their severity. The severity rating is indicated in the Microsoft security bulletin as critical, important, moderate, or low. This Monthly Rollup would be displayed under the title Security Monthly Quality Rollup when you download or install. This Monthly Rollup will be classified as an "Important" update on Windows Update and will automatically download and install if your Windows Update settings are configured to automatically download and install Important updates.

>**Preview of Monthly Rollup**\
>_Definition_:\
>A tested, cumulative set of new updates that are packaged together and distributed over Windows Update, WSUS, System Center Configuration Manager and Microsoft Update Catalog ahead of the release of the next Monthly Rollup for customers to proactively download, test and provide feedback. The Preview of Monthly Rollup is product specific and addresses new non-security updates, and includes fixes from the latest Monthly Rollup. This Preview of Monthly Rollup would be displayed under the title Preview of Monthly Quality Rollup when you download or install and will be classified as an "Optional" update.

# Windows server 2008
* Many different updates each months, that are replacing some others

# Windows 7, 8.1, 2008R2 and 2012R2
* Security updates are not cumulative so we need to install each one manually
* Or Monthly Rollup are cumulatives which are sometimes replacing not well documented updates 

# Windows 10
* Updates are cumulatives, but usually it's needed to apply 2-3 per months
* What is usually needed here: 
  * flash updates
  * Servicing stack
  * Latest cumulatives

## Windows 10 release informations
[List of the different Windows 10 releases](https://www.microsoft.com/en-us/itpro/windows-10/release-information)  
 
## List of Windows 10 updates
* [Windows 10 version 1607 update history](https://support.microsoft.com/fr-fr/help/4000825)
* [Windows 10 version 1703 update history](https://support.microsoft.com/fr-fr/help/4018124/windows-10-update-history)
* [Windows 10 version 1709 update history](https://support.microsoft.com/fr-fr/help/4043454)
* [Windows 10 version 1803 update history](https://support.microsoft.com/fr-fr/help/4099479)


# Windows lifecyle
Following link provides usefull information about the Windows support: [Windows lifecyle fact sheet](https://support.microsoft.com/en-au/help/13853/windows-lifecycle-fact-sheet)

# Windows Vista end of support
Windows Vista has support ended in 11th of April 2017: [End of support information](https://support.microsoft.com/en-ca/help/22882/windows-vista-end-of-support)

# [Windows 8 and Windows Server 2012: List of Rollup Updates](https://social.technet.microsoft.com/wiki/contents/articles/23820.windows-8-and-windows-server-2012-list-of-rollup-updates.aspx)

# [Windows 8.1 and Windows Server 2012 R2: List of Rollup Updates](https://social.technet.microsoft.com/wiki/contents/articles/23823.windows-8-1-and-windows-server-2012-r2-list-of-rollup-updates.aspx)
