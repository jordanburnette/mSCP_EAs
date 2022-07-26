# macOS Security Compliance Extension Attributes
The following are Extension Attributes (EAs) for use in Jamf Pro when deploying the macOS Security Compliance Project (mSCP).
![mSCP Jamf EAs](https://github.com/jordanburnette/mSCP_EAs/blob/readmeupdate/mSCP_EA_Sample.png?raw=true)

## Contents Include:
- **mSCP-BaselineVersion.xml** : Lists the name of the baseline that is being run on the computer object (ie. org.cislvl1.audit.plist)
- **mSCP-FailedResultsCount.xml** : Displays a numerical value showing the number of failed audit items on computer object
- **mSCP-FailedResultsList.xml** : Lists out the rules that were flagged as being non-compliant
- **mSCP-BaselineExemptions.xml** : Lists out any exemptions configured for the computer object

These are in XML format to allow easy uploading into Jamf Pro. Any feedback? Let me know!
