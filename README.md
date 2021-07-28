# Author
sharon kemboi


# description 
school management system is besically an application that ensures that there is ease in running the school activies.Its has diffrent user and each has its own funcionalities.Take a look below 

## Functions
### Teacher
First the teacher will apply for job,if he/she gets selected there accounts will be made and approved by the admin, after approval only teacher can access their dashboard.
After account approval by admin, teacher can take attendance of any class and view their attendance later.
Teacher can also publish/announce notice to student like submission of assignments.

## Student
First student will take admission/signup.
When their account is approved by admin, only then the student can access their dashboard.
After account approval by admin the student can view their details like attendance.
Student can't view attendance of other student.
Student can't announce, they can only view.

### Admin
First admin will signup for a account.
After login they can see how many student/teacher wants to get job/admission in their school.
They can approve or delete/cancel the request.
They can update any student/teacher details.
Admin can announce notice also.


## HOW TO RUN THIS PROJECT
- Install Python(3.8.5) 
- Open Terminal and Execute Following Commands :

``` python -m pip install -r requirements. txt ```


- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
python manage.py makemigrations
python manage.py migrate
python  manage.py runserver

- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```


EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```

#  Technology
Python
Django 
HTML
CSS
## Feedback
Any suggestion and feedback is welcome. 
