# stage_medecine_front
Back : https://github.com/guilloulouis/stage_medecine_api

Web Application to be able to handle medecine traineeship there are 2 types of users : 
- Student
- Admin

## Student 
The student has his account created by the admin, he will be able to : 
- Manage his account :
  - Password
  - E-mail
- Check the traineeship he has done 
- Check how many points he has and his ranking in his promotion
- Get access to a procedure when there is one for his promotion and participate to this procedure (5 steps form)
- Check the differents simulations for the procedures (the traineeship he has gotten and the points that it will cost)

## Admin
The admin can manage all the Students and the procedures, he is able to : 
- Create students throught a file (csv) or manually (their username and password are directly sent to them via Email)
- Create a procedure for a promotion, sending a mail to the whole promotion
- Process the procedure to get simulations, sending a mail to the whole promotion
- Manage auto-simulations
- Apply a simulation to the traineeships so the students are assigned definitely to a traineeship
- Manage his account

## Both
They will both be allowed to : 
- Check the history of traineeship for each promotions and how many points each traineeship were valued 
