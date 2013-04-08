my_jenkins -- command line utility for jenkins
=============================================

## SYNOPSIS

`my_jenkins` --job= --user= --password= [--build] [--get_last_buildnumber]


## DEPENDENCIES

* `python-jenkins` for building
* `jenkinsapi` for extra build insformation


## USAGE

* Add new job to queue:

  `my_jenkins --job=job-name --user=user_name --password=your_password --build`

* Get extra information about last build number and last successfull build:

  `my_jenkins --job=job-name --user=user_name --password=your_password --get_last_buildnumber`
  
  Output:
  
  `'MSP-arsp'=277 is Ready, LastGood=277 @ 2013-04-05 17:52:16`
