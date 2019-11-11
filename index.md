<img src="doc/landing.PNG">

## Installation

First, [install Meteor](https://www.meteor.com/install).

Second, go to the [github repository](https://github.com/isaiahstarkey/digits), and click the "clone or download" button. Click on Download ZIP.

Third, after the file is finished downloading, unzip the file.

Fourth, open a Command Promt and cd into the app/ directory of the newly unzipped file. Install meteor:


```
$ meteor npm install
```

Fifth, start the digits application:

```
$ meteor npm run start
```

#### Landing page

When you retrieve the app at http://localhost:3000, this is what should be displayed:

<img src="doc/landing.PNG">

The next step is to use the Login menu to either Login to an existing account or register a new account.

#### Login page

Clicking on the Login link, then on the Sign In menu item displays this page:

<img src="doc/signin.PNG">

#### Register page

Alternatively, clicking on the Login link, then on the Sign Up menu item displays this page:

<img src="doc/register.PNG">

#### Landing (after Login) page, non-Admin user

Once you log in (either to an existing account or by creating a new one), the navbar changes as follows:

<img src="doc/postsignin.PNG">

You can now add new Contacts, and list Contacts you have added. 

#### Add Contact page

After logging in, here is the page that allows you to add new Contacts:

<img src="doc/add.PNG">

#### List Contacts page

After logging in, here is the page that allows you to list all the Contacts you have added.

<img src="doc/list.PNG">

You click the "Edit" link to go to the Edit Stuff page, shown next.

#### Edit Contact page

After clicking on the "Edit" link associated with a Contact, this page displays that allows you to change and save it:

<img src="doc/edit.PNG">

#### Landing (after Login), Admin user

You can define an "admin" user in the settings.json file. This user, after logging in, gets a special entry in the navbar that lists all Contacts added in the database:

<img src="doc/admin.PNG">
