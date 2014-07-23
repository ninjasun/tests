””# QA Test

## Intro
You will get access to two thrills.com accounts.
You will login to those accounts using a special link. This version of thrills.com will be almost identical to the production version, except that its broken in very specific ways.

One of the accounts is a swedish user using `SEK` as currency, and the other is a norwegian user with `EUR` as currency.

## Preparation

1. Go to: [http://broken.staging.thrills.com/](http://broken.staging.thrills.com/).

    ![.htaccess](images/qa-htaccess.png)

2. Enter the following details to get access to the site:

    ```
    username: thrills
    password: flappybird
    ```

3. Login with either the swedish or norwegian user.

    ![login](images/qa-login.png)
    
    Use the following details:

    *Swedish user:*
    ```
    username: findthebugs-se
    password: l3tm31n
    ```

    *Norwegian user:*

    ```
    username: findthebugs-no
    password: l3tm31n
    ```
