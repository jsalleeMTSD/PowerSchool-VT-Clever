# PowerSchool-VT-Clever

A Vermont varient. Everything else in README is from the original. —Jon Sallée, 20 SEP 2024

I've parked all files in the folder: Clever PowerQuery Support in order for a direct .zip download to be usable as a plugin as directly as possible.

***These files use: Students.DCID for students, and Users.DCID for Teachers and Staff. This is not 'default' for Clever.***

I'll update these files if they're not passing Clever's upload muster.

-- Greg Matyola
August 5, 2022

# Update ( September 16, 2022 )

I've updated my files a little bit, and there's one more minor tweak I think I need to do to the "Teachers" export...

Also note the caveat that my files are pulling for New Jersey, so your state implementation will differ!

-- Greg Matyola

# Available on PowerSource (October 5, 2022):
(a.k.a. the Self-Promotion section)

I've also got a "plugin" for PowerSchool that might be useful if you're using PowerSchool, allowing you to upload the Clever badges into PowerSchool, and reveal (or not) the badges to Administration, Teachers or Parents.

* Clever QR Import and Portal Display Plugin:
  https://support.powerschool.com/exchange/view.action?download.id=1096

# Update ( October 10, 2022 ) 
I've fixed both the Teachers Export (Teachers now will only export for their "home school"), and Sections (Sections will not extract if students have not ever been enrolled in the sections).

# Update ( November 15, 2022 )
I've been working on geting my Students query cleaned up for "public consumption", and found the probable genesis of my queries:
* https://github.com/sriehl/Clever-PowerQueries

# Updated Student Queries to "Full Code" version (v2)
* Added CHECK_ME points (in students_csv.named_queries.xml) where adaptations / choices will need to be made.
* This version WILL EXPORT 'Data Access Accounts' as 'family' to Clever. Please alter that part of the query if you needs differ!

# Updated ( November 3, 2023 )
* Fixed a bug where two co-teachers in a section would both have an equal priority order. Should be fixed now.
