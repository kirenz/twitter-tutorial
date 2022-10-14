# Twitter setup

In this tutorial, we'll cover the setup to get started with the Twitter API v2.


## Signing up with Twitter

In order to get started with the Twitter API, you need a Twitter account. 

If you do not have one yet, you can sign up for one: [Twitter account](https://help.twitter.com/en/using-twitter/create-twitter-account)


---

## Developer account

Sign up for a developer account: [Twitter developer account](https://developer.twitter.com/en/portal/petition/essential/basic-info). 

---

## Create a Project and connect an App

### Create a new project

Next, in the [developer portal](https://developer.twitter.com/en/portal/dashboard), create a new Project.


![](https://cdn.cms-twdigitalassets.com/content/dam/developer-twitter/docs/new-project.png.twimg.1920.png)


Give it a name, select the appropriate use-case, provide a project description. 


### Create an App


Click `‘create a new App instead’`.

![](https://cdn.cms-twdigitalassets.com/content/dam/developer-twitter/docs/add-your-app-project.png.twimg.1920.png)


Give your App a name in order to create a new App.


![](https://cdn.cms-twdigitalassets.com/content/dam/developer-twitter/docs/last-step-name-your-app.png.twimg.1920.png)

click on complete.


### API Keys and Bearer Token

Once you click complete, you will get your API Keys and the Bearer Token that you can then use to connect to the new endpoints in the Twitter API v2.


![](https://cdn.cms-twdigitalassets.com/content/dam/developer-twitter/docs/here-are-your-keys.png.twimg.1920.png)


Click the (+) next to *API Key*, *API Secret Key* and *Bearer Token* and copy it in a safe place on your local machine.

You will need these to make the API calls in the next tutorial.

:::{note}
Please note: The keys in the screenshot above are hidden, but in your own developer portal, you will be able to see the actual values for the API Key, API Secret Key and Bearer Token.
:::

- *API Key and API secret key: Essentially the username and password for your App.*

- *Bearer token*: allows developers to have a more secure point of entry for using the Twitter APIs*

### Access token and access token secret

Obtain the *access token* and *access token secret*: These can be generated in your [developer portal](https://developer.twitter.com/en/portal/projects-and-apps), under the `“Keys and tokens”` tab for your developer App.

Add them to the file with your *API Key*, *API Secret Key* and *Bearer Token*.


- *Access Token and access token secret: In general, Access Tokens represent the user that you are making the request on behalf of. The ones that you can generate via the developer portal represent the user that owns the App.* 