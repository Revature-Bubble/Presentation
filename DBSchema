Profile
 - profile_id (pk) - int
 - first name - varchar
 - last name - varchar
 - email - varchar
 - username - varchar
 - password - varchar

Post
 - post_id (pk)
 - profile_id reference Profile
 - body
 - date_posted - timestamp
 - image_url

Comments
 - comment_id (pk)
 - body
 - date_commented - timestamp
 - previous_comment references Comments
 - post_id references Post
 - profile_id references Profile
 
**Many-to-Many**
Followers
 - profile_id references Profile
 - follower_id references Profile

**One-to-Many**
Likes
 - post_id references Post
 - profile_id references Profile


<--OPTIONAL-->

Profile_Specs (optional)
 - school
 - bio
 - location
 - birthday
 - gender
 - pronouns
 - id references Profile (fk)
