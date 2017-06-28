# things-profile-dialog

## This is a dialog showing user profile information.

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

## This is an Icon Button that you use to display the user profile dialog.

Example
```html
  <things-profile system="Hassed"
    role-list-url ="roles"
    role-request-url="request_auths/account/auth/request">
  </things-profile>
```
<br><br>

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/things-profile/`, where `things-profile` is the name of the directory containing it.
