# Django with mongoDB project
django-mongodb-engine을 사용한 프로젝트
* 기본 django에서 mongodb 드라이버를 지원하지 않아 오픈소스 engine을 사용
* engine자체가 오래되서 python3을 지원하지 않는다.
* django-nonrel을 사용 (django 1.5.11 버전)

사전셋팅
```

pip install git+https://github.com/django-nonrel/django@nonrel-1.5  // nonrel버전을 설치
pip install git+https://github.com/django-nonrel/djangotoolbox      // toolbox 설치
pip install git+https://github.com/django-nonrel/mongodb-engine     // db engine 설치

```
