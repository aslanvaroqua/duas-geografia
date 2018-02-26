# duas-geo
duas-geo

spark crime analysis example. released to all members of the public. 
not complete but thought I can share a bit of it. 
The rest is complete but contains our clients proprietary methods.  

Crime data is publicly available on Chicago's website... Export to csv and make sure this statement
points to the correct comma delimited table

    val communityCodesData = sc.textFile("data/CommunityCodes.csv").
                                map(rec => (rec.split(",")(0), rec.split(",")(1)))
                                
                                
See the license document!

![alt text](http://duasamericasgroup.com/css/2016_style/img/logos/aslan-varoqua-greenblue-duas-logo-orig.png)

Steal this project!
