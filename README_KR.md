# things-profile-dialog

## 이는 사용자 프로파일 정보를 보여주는 다이얼로그이다.

Example
```html
  <things-profile-dialog
    name="elidom"
    email="elidom@example.com"
    role-list-url ="roles"
    role-request-url ="request_role"
    img="../../images/profile.png">
  </things-profile-dialog>
```

# things-profile

## 이는 사용자 프로파일 다이얼로그를 보여주고 싶을 때 사용하는 Icon Button이다.
Example
```html
  <things-profile system="Hassed"
    role-list-url ="roles"
    role-request-url="request_auths/account/auth/request">
  </things-profile>
```
<br><br>

## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install


## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polyserve

그리고, 아래의 방법을 통해 실행할 수 있다.

    polyserve

element를 실행한 경우, `things-profile`이 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-profile/`을 통해 이를 미리 확인할 수 있다. 
