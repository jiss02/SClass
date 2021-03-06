<br />

<p align="center">
    <img src="https://user-images.githubusercontent.com/42693808/70762593-6f6cfb80-1d94-11ea-90a6-2f955df468f5.png" alt="Logo">
  </a>

  <h3 align="center">SClass</h3>
  <p align="center">
    지역 상인들의 숨겨진 이야기, SClass <br/>
  WIC 해커톤 프로젝트
    <br />
   </p>

&nbsp;
<!-- TABLE OF CONTENTS -->

## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Requirements](#requirements)
  * [Installation](#installation)
* [Details](#details) 
  * [Deploy](#deploy)
  * [Links](#links)
  * [Demo](#demo)
 * [Contanct](#contact)

&nbsp;
<!-- ABOUT THE PROJECT -->

## About The Project

<div align="center">
    <br/>
    <img src="https://user-images.githubusercontent.com/42693808/70762550-3fbdf380-1d94-11ea-8309-a1d110c7cc69.png" />
    <br /><br/>
    숙명여자대학교 AWS WIC 해커톤 프로젝트
    <br/>
    <b>지역 상인들의 숨겨진 이야기, SClass</b>
</div>

&nbsp;

우리의 주변에는 많은 지역 시장들이 존재합니다. 그러나 이런 지역 시장들은 점점 우리의 기억 속에서 잊혀져 가고 있습니다. SClass는 지역 시장을 활성화시켜 해당 문제를 해결하기 위해 만들어졌습니다.

꽃꽂이, 다도, 반찬 만들기와 같은 지역 시장에서만 만나볼 수 있는 특별한 클래스를 즐기며 지역 시장 상인들의 숨겨진 이야기를 찾아낼 수 있습니다. 지역 시장 클래스의 혜택은 여기서 그치지 않습니다. 클래스를 수강한 사람에게는 클래스를 진행한 가게에 재방문 할 시 할인 혜택을 제공합니다. 

주변 지역 시장의 매력에 빠져보세요.

### Built With

* Python Django
* HTML5 + CSS3 + Javascript
* SQLite3

&nbsp;
<!-- GETTING STARTED -->

## Getting Started



### Prerequisites

Setup project environment with [venv](https://docs.python.org/3/library/venv.html) and [pip](https://pip.pypa.io).

* setting venv

```sh
$ python -m venv venv
$ . venv/Scripts/activate
```

* Django

```sh
$ pip install django
```


&nbsp;

### Requirements

```
beautifulsoup4==4.8.1
botocore==1.12.253
cement==2.8.2
certifi==2019.9.11
chardet==3.0.4
colorama==0.3.9
Django==2.1.1
django-bootstrap4==1.0.1
docutils==0.15.2
future==0.16.0
idna==2.7
jmespath==0.9.4
pathspec==0.5.9
Pillow==6.2.1
python-dateutil==2.8.1
pytz==2019.3
PyYAML==3.13
requests==2.20.1
semantic-version==2.5.0
six==1.11.0
soupsieve==1.9.5
sqlparse==0.3.0
termcolor==1.1.0
urllib3==1.24.3
wcwidth==0.1.7
```

&nbsp;

### Installation

1. Clone the repo

```sh
$ git clone https://github.com/jiss02/SClass.git
```

2. Migrate Database

```sh
$ python manage.py migrate
```

3. Create config folder and key.json

```sh
$ mkdir config
$ cd config
$ vim key.json
```

4. Run server

```
$ python manage.py runserver
```

&nbsp;

## Details 

### Deploy

* Heroku (현재 중단 상태)
  &nbsp;

### Links

* Project Link: https://github.com/jiss02/SClass.git
* Website Link: (현재 중단 상태)
  &nbsp;

### Demo

* superuser ID(for test) : admin
* superuser PW : 1234

<div align="center">

| main 1|
| :---: |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887518-870ce400-2021-11ea-8e23-335bc65db5cd.png"> |
| main 2 |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887519-870ce400-2021-11ea-87be-23fe7bd107f6.png"> |
| class list 1 |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887529-88d6a780-2021-11ea-942b-ac6810d29934.png"> |
| class list 2 |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887531-896f3e00-2021-11ea-9008-ce085b14bfb3.png"> |
| class detail 1 |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887527-88d6a780-2021-11ea-96a9-70692e742f1f.png"> |
| 클래스가 열리는 상점을 지도에 표시해주며, 클래스 수강신청과 스크랩이 가능합니다. |
| class detail 2 |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887528-88d6a780-2021-11ea-8ea0-58067f26d967.png"> |
| myclass |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887522-87a57a80-2021-11ea-84a6-c8568543ef02.png"> |
| mypage |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887523-883e1100-2021-11ea-8e83-5e58fbcd0f08.png"> |
| store 1 |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887525-883e1100-2021-11ea-8554-44b7bc7869e7.png"> |
| store 2 |
| <img width="800" alt="" src="https://user-images.githubusercontent.com/42693808/70887526-883e1100-2021-11ea-9c24-eae82b853dde.png"> |
| 지역 상인들의 스토리를 카드 뉴스 형식으로 보여줍니다. |

</div>

