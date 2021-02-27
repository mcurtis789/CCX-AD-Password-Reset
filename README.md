This is a demo script for resetting a user password from Cisco UCCX. It will look for the caller’s number then create a random password and read it off to the user. The following fields would have to be set to valid values for your test environment in distinguished name format
sDomainSearchScope
sServiceAccountDN 
sServiceAccountPassword
sserverIP

Also this script makes no attempt to confirm the user identity, add on logic is required for this.  
