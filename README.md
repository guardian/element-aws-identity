aws-identity
============

Element exporting AWS credentials using Web Identity Federation.

[Documentation](http://guardian.github.io/element-aws-identity/)

## Example

``` html
<aws-identity accountId="AWS_ACCOUNT_ID"
              roleName="AWS_ROLE_NAME"
              sink="{{config}}">
    <google-signin clientId="GOOGLE_APP_ID.apps.googleusercontent.com"
                   scopes="https://www.googleapis.com/auth/userinfo.email">
    </google-signin>
</aws-identity>
```
