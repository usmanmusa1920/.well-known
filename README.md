# Linking a Github Pages Domain to Discord Connections

You can add your domain to your Discord connections to showcase it on your profile.

In the case of a GitHub Pages domain, DNS verification sounds unable to do already. therefore, we will verify it using the https (file method).

1. Open Discord and navigate to your user settings by clicking on the gear icon next to your username.

2. In the settings menu, select "Connections."

3. Choose the domain, a pop-up will appear. Enter your GitHub Pages domain name.

4. Click on "Next," then select "Verify using https."

5. Copy the content provided there, something like `dh=123456abc`.

6. [Fork this repository](https://github.com/usmanmusa1920/.well-known/fork) or [Create your own](https://github.com/new) with thesame content of this repo

> [!IMPORTANT]  
> Do not change the repository name; keep it as `.well-known`.

7. Edit the `discord` file in the root of the repository and replace the content that you've copied in step 5 and Commit the changes.

8. Go to repository settings and enable GitHub Pages for your forked repository.

9. Click on the verify button, and the domain will be added to your Discord profile.

--- 

Thank you!
