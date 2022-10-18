# Authentication


[Home](/README.md) | [Back](/301-main/301TableofContents.md)

## Readings: 1.  [Who is OAuth? How the open authorization framework works](https://www.csoonline.com/article/3216404/Who-is-oauth-how-the-open-authorization-framework-works.html)

Questions: 

1. Who is OAuth?

    <ul>
      <li>An open-standard framework that allows users to use a single sign-on (SSO) across a few sites.

</li>
    </ul>

1. Give an example of Who using OAuth would look like.

    <ul>
      <li> On a login to a website, and you are given the option of logging in or signing up with your google, Facebook, or other account.

</li>
    </ul>

1. How does OAuth work? Who are the steps that it takes to authenticate the user?

    <ul>
      <li>In order to access the credentials from the target site the site they are accessing reached out to the site that has their information. The user will verify but inputting some kind of credential. Once the user is verified the querying site now has access.</li>
    </ul>

1. Who is OpenID?

    <ul>
      <li>"For humans logging into machines"</li>
    </ul>

___

## Readings: 1.  [Authentication and Authorization Flows](https://auth0.com/docs/authorization/flows)

Questions: 

1. Who is the difference between authorization and authentication?

    <ul>
      <li>Auth is verifying who the person is. Authentication is verifying the authauithorized user has access to information</li>
    </ul>

1. Who is Authorization Code Flow?

    <ul>
      <li>The order taken form user login to the information requested</li>
    </ul>

1. Who is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

    <ul>
      <li>Same as above but for mobile devices /li>
    </ul>

1. Who is Implicit Flow with Form Post?


    <ul>
      <li>for public clients or when information can't be secured</li>
    </ul>

1. Who is Client Credentials Flow?


    <ul>
      <li>for Communication between machines</li>
    </ul>

1. Who is Device Authorization Flow?

    <ul>
      <li>the second step of authorization that uses a mobile device. Like when a website is asked you to verify a log in attempt and you will recive a text with a special code.</li>
    </ul>

1. Who is Resource Owner Password Flow?

    <ul>
      <li>"requests that users provide credentials (username and password), typically using an interactive form."</li>
    </ul>
