# macOS Security Compliance Project - Extension Attributes
The following are Extension Attributes (EAs) for use in Jamf Pro when deploying the [macOS Security Compliance Project (mSCP)](https://github.com/usnistgov/macos_security).
![https://github.com/jordanburnette/mSCP_EAs/blob/readmeupdate/mSCP_EA_Sample.png?raw=true](https://github.com/jordanburnette/mSCP_EAs/blob/main/mSCP_EA_Sample.png?raw=true)
## How to use
Clone this repo to your machine or click **Code** > **Download ZIP** to obtain the XML files. 

Within Jamf Pro, navigate to Settings, Computer Management - Management Framework, Extension Attributes, and click **Upload**.

### Contents Include:
- **mSCP-BaselineVersion.xml** : Lists the name of the baseline that is being run on the computer object (ie. org.cislvl1.audit.plist)
- **mSCP-FailedResultsCount.xml** : Displays a numerical value showing the number of failed compliance controls on computer object
- **mSCP-FailedResultsList.xml** : Lists out the rules that were flagged as being non-compliant
- **mSCP-BaselineExemptions.xml** : Lists out any exemptions configured for the computer object

#### Want to contribute, report issues, or talk macOS compliance?
Join the [MacAdmins Slack](https://www.macadmins.org/) and hop into the *#macos_security_compliance* channel.
