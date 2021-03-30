REST API interaction flows :

SIGN-UP :
$. ajax {(URL: 'signup/api/user', method: 'POST', data: {nickname: nickname, password: password}, success: function(data) {if err: console. Error else: redirect to 'home/api/start'})}
SIGN_UP : User can choose among various options using auth google
Authorized Redirect: http://localhost:8080  
URI: http://localhost:8080/auth/google/callback ( Copy and paste Client ID and Client secret keys into. Env )

Backend (For User Registration): //Check if user exists: User.findOne({name: req. body.name}) if exists : res.status(400) {User exists} else: new User({"name", "password"}) }) // Password hashing for secure pathways.

ONBOARDING PHASE : 
1.	Sleep
2.	Anxiety
3.	Depression

"home/api/choice" with a FORM approach. Minimalistic design.

Events(onClick) will be fired for example:

GET request: Every category asks different set of questions from the user.
if onClick (category == 'SLEEP’) {“home/api/choice/: categoryID”} redirect to "home/api/choice/: categoryID/"

Questions related to different genres:
" Nice goal. Do you want to alter anything related to sleep? " 
" How much did you sleep yesterday? "

POST request: {url:'home/api/choice/: categoryID/', method: 'POST', data = {sleep, time, routine, sleep duration} success: function(data) {
Error check and if not any error then take the user to the specific and ideal routine for them}

DB (DATABASE)
Every user will have a unique name which would be used as the PK.
Database: User Table: {username: luis12667, password: 12345(encrypted), firstName: luis, lastName: emilio, category: ["sleep”, “sports activity"]} Onboarding Plan: {sleep: 'not very happy with sleep cycle’, time: '10:00pm to 7:00am ' ..}
Data formatting will be done accordingly.
In the end the user could be redirected to the dashboard for more details and better plans for them and their family.
