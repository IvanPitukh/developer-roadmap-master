# Automate Everything

This is more of general operations advice than AWS specific, but everything needs to be automated. Recovery, deployment, failover, etc. Package and OS updates should be managed by something, whether it's just a bash script, or Chef/Puppet, etc. You shouldn't have to care about this stuff. As mentioned in a different tip, you should also make sure to disable SSH access, as this will pretty quickly highlight any part of your process that isn't automated. Remember the key phrase from the earlier tip, if you have to SSH into your servers, then your automation has failed.
