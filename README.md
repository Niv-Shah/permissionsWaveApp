## Wave App for Comparing Salesforce User Permissions

Comparing user's permissions within the Salesforce platform has been a long standing request and non-trival task for administrators. I wrote a blog post on [Comparing Profiles and Permission Sets](http://www.salesforcehacker.com/2013/01/comparing-profiles-and-permission-sets.html) previously about this very topic, outlining some of the challenges with reporting on user's access. 

Since then, it's come up on social media a couple of times, most recently with a [twitter post](https://twitter.com/brentdowney/status/678258476322131968). While apps like the [Perm-Comparator](https://perm-comparator.herokuapp.com/) from [John Brock](https://twitter.com/_johnbrock) are still the goto solution for comparing users, permission sets, and profiles, a thought occured to me that you could also solve this BigData problem with the Salesforce Wave platform. 

So I set out to use the tooling available via the Wave platform for creating a simple app that compares permission assignments and their containers. Just a proof of concept but it can be a good starting point for admins who have access to Wave already and want to compare user's permissions.


![alt tag] (https://raw.github.com/atorman/asyncSOQL/master/img/LoginForensics.png)


## Installation

This JSON will only work with the Spring '16 release

1. Download a ZIP of the repository. 
2. Uncompress the files. 
3. Upload and run the ProfilesPermissionSetsUsersDataflow.json
4. Copy-paste the JSON from ProfilesPermissionSetsUsersDashboard.json into a new dashboard
5. Modify any ids such as report and dataset Ids

## Credit

Contributors include:

* Adam Torman created and orchestrated the majority of the repository

This repo is As-Is. All pull requests are welcome.