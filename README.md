![Header](./Assets/Image/head%20web.png)

<h1 align="center">Welcome to My Company !</h1>
Hi, I'm Rizqi Akbar. This is what my company can help u!. This company not big for now but we can guarante our service will make u statisfied. Our company's work ethic prioritizes quality and speed in completing work.

## STRUCTURE 📰

- Header
  - Dark mode
  - Navbar
- Main
  - Photo AI
  - R34 information
  - The whistle of domination
- Footer
  - Form

## INGREDIENTS I USE 📜

- HTML
- CSS
- Internal Source
  - Icon
  - Image

## HOW TO SET UP 📰

You will need a github account to clone this repository, make sure you're connected to github.

1. Clone this repository

```
git clone https://github.com/revou-fsse-3/milestone-1-LOOL18.git
```

2. Create a new branch named "develop", in this repository we would like to develop the website with personal information.

```
git branch -b "develop"
```

3. Once it's created, checkout to a new branch

```
git checkout -b "develop"
```

4. Develop & modify the website with your personal information, once it's done you will need to push it.

```
git add .
git commit -m "update message" // make sure to give details commit message to get better logs
git push origin develop
```

5. Once you're done, you can merge into main/master branch for production build.

```
git checkout main
git pull origin main // pull the latest version before commit merge
git merge develop // if there are any conflicts, you should resolve them manually
git commit -m "Merge develop into main"
git push origin main
```

## DEPLOYMENT ⚙️

The project has been successfully deployed using Netlify. You can access the production version of the website by following this link: [https://alrickindo.dartvader.cloud/](https://alrickindo.dartvader.cloud/) or [this link](https://alrickindo.dartvader.cloud/).

### Deployment status :

[![Netlify Status](https://api.netlify.com/api/v1/badges/4f459b63-ef8d-4352-99a4-9efe96466988/deploy-status)](https://app.netlify.com/sites/glittery-horse-3be537/deploys)

---

## **1. Connect your account to Netlify !**

he first step to deploy in Netlify is creating a new account or use existing account. As a beginner progammer, I would prefer using GitHub account instead.

After you successfully login, you will be redirected to dashboard of Netlify app. In this scenario, you will need to import your existing project from github to netlify. Add new site -> Import existing project -> Connect via GitHub.

## **2. Auto Deploy with Netlify !**

One of the benefit using your GitHub account connected to Netlify is that you don't have to worry about re-deploying your project manually, once there are changes that have been pushed in your repository, it will automatically re-deployed by Netlify within second.

## **3. Domain Registrar with NiagaHoster & Cloudfire !**

Go to [https://niagahoster.co.id](https://niagahoster.co.id) and log in or create a new account. Check available domain that you wanted and make it yours.

After that, go to [https://dash.cloudflare.com/](https://dash.cloudflare.com/) and log in or create a new account. You will be redirected to dashboard, add the domain that you have bought previously.

## **4. Modify your project with favorite customize domain !**

You're on the final step to bringing live your project with custom domain. Go to dashboard Cloudfire -> DNS Records -> CloudFire NameServer. You will see the information of Nameserver that is given to you.

Copy these nameserver and jump into dashboard overview of NiagaHoster. You should replace it with NameServer of CloudFire. After that, go to Netlify Dashboard -> open your project -> Custom domain -> Add domain that you have set previously. In thise case, you will see they're awaiting for external DNS. You will get some information such as IPv4 and domain name that you should input it to CloudFire.

Final step, go to Dashboard Cloudfire -> DNS Records -> Add record domain -> set them accordingly.

## **5. Congratulations, You're done !**

_You should wait within 1x24 hours to let the NiagaHoster and Cloudfire setting up the DNS, it could be faster or slower depending on the provider internet that you're using.
Feel free to explore the website and try out the different features. I appreciate any feedback and suggestions to further improve the user experience.
Happy browsing!_
