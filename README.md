# PBIS-AD

Use PBIS to pre-configure the user environment for all domain users that log into the newly added system.

sudo /opt/pbis/bin/config AssumeDefaultDomain true
sudo /opt/pbis/bin/config LoginShellTemplate /bin/bash
sudo /opt/pbis/bin/config HomeDirTemplate %H/%U
sudo /opt/pbis/bin/config UserDomainPrefix SHORT_DOMAIN_NAME