# Django 프로젝트 시작하기
 
> 참고자료  
> https://tutorial.djangogirls.org/ko/ 

virtualenv 시작하기  
source myvenv/bin/activate  

웹서버 시작하기  
python manage.py runserver 

프로젝트 내부에 별도의 어플리케이션 만들기  
python manage.py startapp blog  

모델 만들기  
python manage.py makemigrations blog 

실제 데이터베이스에 모델 추가하기  
python manage.py migrate blog  


