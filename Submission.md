
## Which Categories Best Fit Your Submission and Why?

Best Portability (or Best contribution to operational tools, availability, management or Best new feature)

We ported the end to end middleware focused aspects of the NetflixOSS platform from a system that was highly tied to Amazon EC2 to IBM SoftLayer and RightScale demonstrating cloud portability as well as multi-cloud capabilities.

## Describe your Submission

This project included porting the following:

* Oracle/Open Java to IBM Java
** Asgard Sever, Archaius, Karyon/Governator, Eureka Client, Hystrix, Ribbon, Astyanax
* Tomcat to WebSphere Liberty Profile
** Archaius, Karyon/Governator, Eureka Client, Hystrix, Ribbon, Astyanax
* Amazon EC2 to IBM SoftLayer
** Eureka Server, Simian Army/Chaos Monkey
* Amazon Auto Scaling Groups to RightScale Server Templates, Monitoring, RightScripts, and Server Arrays
** Auto Scaling and Auto Recovery

## Provide Links to Github Repo's for your Submission

Wiki that talks to architectural findings, discussions of how to configure IBM and RightScale technologies, and future possible work:

https://github.com/EmergingTechnologyInstitute/SoftLayer-NetflixOSS/wiki

Projects forked with code changes:

* https://github.com/EmergingTechnologyInstitute/asgard
* https://github.com/EmergingTechnologyInstitute/eureka
* https://github.com/EmergingTechnologyInstitute/governator
* https://github.com/EmergingTechnologyInstitute/SimianArmy
