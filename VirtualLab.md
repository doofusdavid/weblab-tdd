Unit Test Virtual Lab
=====================

Ensure you have Brian’s code from here: https://github.com/byelle/module5-review

### Step One
First, run `phpunit` on the 3crud/tests/userTest.class.php and ensure that there are no errors.  Note that this refers to the user.class.php in 3crud/models.

### Step Two
create a new test method in userTest.class.php:

```
    /* Set a valid email address, and check to make sure the property is set */
    testEmailSetAndGet()
```

### Step Three
Re-run the tests, and ensure they all pass.

### Step Four
Our client has created a new requirement that the user class should not accept an invalid email address.  Upon setting the user’s email to an invalid email address, it should instead be set to an empty string.

### Step Five
Create a new method in userTest.class.php:

```
/* Set an invalid email address, and check to make sure the property is blank */
testEmailIsInvalid()
```

### Step Six
Re-run the tests.  That new test should fail.

### Step Seven
Change user.class.php to ensure that an invalid email address results in an empty string for the email.  Hint: google php validate email

### Step Eight
Re-run the tests.  All tests should pass.

### Step Nine
Send me your changes to user.class.php and usertest.class.php
