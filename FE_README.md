




# New England Getaway
### Concept
New England Getaway is an online app geared towards people who are visiting, or thinking of visiting New England. App will generate an activity from a stored database listing a wide range of activities.

### Frontend Technologies Used

* VueJS
* JavaScript
* Python
* Django
* PostGres SQL
* Bootstrap/Tailwind
* HTML


### Routes and CRUD functions
|Path|Action| Description
|----|----|----|
|'/'| Main | Homepage will have a simple display that will include a button to generate a random activity.
|'/:id' | Show | Show page will display a specific restaurant and reviews along with it.
|'/create'| | Create page will allow user to create a random activity which will be added to the site's database.
|'/activity/update/:id' | Update | Will update the activity.
|'/activity/delete/:id' | Delete | Will delete the activity.


### Mockups

##### Landing Page
https://docs.google.com/drawings/d/1khwyKTqfENMvGWRwunA3XVD44G8cJCMfpFby8JP-nac/edit 

##### Show Page

https://docs.google.com/drawings/d/1UI8zHoe8xlvk6AF9HCp2iovDAu2wYAyLzh4bUhGavvI/edit


#### Backend Schema

{
  * name: String
  * img: String
  * state: String
  * activityType: String
  * description : String
  * address: String
  
  }