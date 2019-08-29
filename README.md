Usage: oslogs \[-f] NAME \[SYSLOG_IDENTIFIER \[SYSLOG_IDENTIFIER ...]]

Shows system journal with given identifiers, then shows container journals under /openstack/log/\*NAME\*/jornal with same identifiers.

If no identifiers are given then the entire journal is shown for all containers matching \*NAME\*.

Examples:

Show cinder scheduler logs:

./oslogs cinder cinder-scheduler
