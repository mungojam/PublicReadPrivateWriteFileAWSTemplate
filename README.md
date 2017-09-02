# PublicReadPrivateWriteFileAWSTemplate
A cloud formation template for creating a publicly viewable S3 file and an associated user that can write to it.

[Get it here](https://raw.githubusercontent.com/mungojam/PublicReadPrivateWriteFileAWSTemplate/master/PublicReadPrivateWriteFileAWSTemplate/PublicReadPrivateWriteFileAWS.template)

This could have a number of uses. I created it for a reasonably non-sensitive settings file that needed to be publicly accessible through a URL. Originally I simply used dropbox for this, but I wanted the file to be updateable through pull requests without being part of a public GitHub or BitBucket profile. I use this template, combined with a BitBucket pipeline to update the file in question on S3.
