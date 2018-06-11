
# Terminology
Is is important to understand the difference between Service Pack and Update rollup. This is an [extract from Microsoft blog post](https://blogs.msdn.microsoft.com/muaddib/2014/02/03/list-of-rollup-updates-for-windows-88-1-windows-server-2012-2012-r2/):

>**Service pack **\
>_**Definition**_: A tested, cumulative set of all hotfixes, security updates, critical updates, and updates. Additionally, service packs may contain additional fixes for problems that are found internally since the release of the product. Service packs my also contain a limited number of customer-requested design changes or features.

>**Update rollup**\
>_**Definition**_: A tested, cumulative set of hotfixes, security updates, critical updates, and updates that are packaged together for easy deployment. A rollup generally targets a specific area, such as security, or a component of a product, such as Internet Information Services (IIS).

Please keep in mind the lists below may not be exhaustive but were complete as of the time of this writing.  I’ll try to keep this list updated going forward.  You should search TechNet for “<operating system> update rollup” to find the latest update rollup packages.  Another option is to use Microsoft Baseline Security Analyzer (MBSA) or Windows Update to scan for missing updates.


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
