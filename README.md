# \<login-signup\>

Component to display Login / Sign up forms, this component can be only Login if configure the option

## Installation

```sh
npm i -g polymer-cli
npm i -g bower
git clone https://github.com/igoodbad/login-signup.git
cd login-signup/
polymer serve --open
```

## Usage

1. Login, simple view show two inputs:
    + username
    + password
  The default language is 'Español (es)'
2. Sign up, simple view show six inputs:
    + first name
    + last name
    + age
    + username
    + password
    + confirm password
- 
This form check password and confirm equals, check the length minimun is five characteres  

### Action Efects
+ Toogle between Login / Sign up
+ Validations includes
+ Login
    + Username and Password required
    + Validation username/password incorrect
+ Register
    + Password minimun length 5 characteres
    + Password confirm


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

Apache License 2004
