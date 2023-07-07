[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/isPhTOcA)

# Documentation for Development and Depoloyment Process and Workflow with Custom Domain (https://aldinotaher.site/)

This week (week-4), author has a task to develop and to deploy a site with custom domain and the author should explain about their process and workflow in more detail in this documentation.
## Site Development

Site that is used for deployment is the previous wweek (week-3) assignment as instructed. Hence, there will be no any signficant changes in topics or theme for the site. However, there will be some slight changes for update, pull request, merge and branch on git that is done github. The difference from previous week (week-3) task is that this week author should deploy the site using a custom domain.

Before the deployment process start, author should make a netlify account and github account. Then author should develop the codes first. Nevertheless, those early stages of work before deployment have already done since the first week of work (week-1). Hence, for the one who seeks previous work could see through links provided below:

[Links for The Previous Assignments]
1. (https://github.com/RevoU-FSSE-2/week-1-andalanaldi)
2. (https://github.com/RevoU-FSSE-2/week-2-andalanaldi)
3. (https://github.com/RevoU-FSSE-2/week-3-andalanaldi)

## Deployment Process and Workflow

### Version Control System

Then for those who seeks to see the deployment process and worflow with custom domain in this part, here after will be focused on those things. The process started from Version Control System (VCS) that ended with git push into the main branch in github. These are the steps for VCS with html, css and javascript files from previous week (week-3) works:

1. The process could be done from git bash because the author use windows operating system (OS) or could be done from integrated terminal on Visual Studio Code (VS Code). In this case, author choose to **use interated terminal from VS code**. Hence the author could imagine how deployment process is done and to make sure whther there is any error or not.

2. On integrated terminal in VS Code, Author could choose between git init, git remote or git clone. Author decide to choose **git clone** to clone the folder and readme.md file form github repository to get easier and faster steps completed in deployment process and workflow. The link for git clone is:

    **Repository URL**
    (https://github.com/RevoU-FSSE-2/week-4-andalanaldi.git)

    **Git Clone Repository URL**
    ![Git Clone Repository URL](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/gi-clone.JPG?raw=true)

_Remember : Do not forget to login or use token first to connect github account with integrated terminal in VS Code._

3. Then, **copy HTML, CSS, Javascript and other needed files** from week-3 and paste those files into week-4 local folder that had beed cloned into local repository. 

    _Remember : Do not forget to set repository into **week-4 folder in intergated terminal using "cd folder/"** location name._

    ![Locate to cloned folder](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/cd-folder.JPG?raw=true)

4. After that, check which files that have not been committed in week-4 folder by using **git status**. if there is untracked files, please use **git add .** to add all files or **git add filename.html** for instance to add single untracked files.

5. Do not forget to use **git commit -m "message that contain action"** to give information about what files and what treatment that author used. The information will be displayed on github.

    **Git status**
    ![Git status](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/git-status.JPG?raw=true)  

    **Git status result**
    ![Git status result](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/git-status-result.JPG?raw=true)    

    **Git add and git commit**
    ![Git add and git commit](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/git-add-dot-git-commit-result.JPG?raw=true)

6. After all those steps are done then use **git push** to push codes files into main branch at week-4 repository on github. If there is no error then githup repsitory could be checked whether the files already stored in that repository. 

    Git Push Origin Main
    ![Git Push Origin Main](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/git-push-origin-main.JPG?raw=true)

    Refresh main
    ![Refresh main](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/refresh-mainbranch.JPG?raw=true)  

### Comparison, Pull Request and Merge

After author pushed codes into github. Author needs to update his codes because Author has local fonts from google fonts that needs to be used, nevertheless, those local fonts is not placed in special folder on week-3 folder and those are looked so messy. Hence, author needs to  make separate folder first inside wwek-4 local folder to contain those fonts then copy and paste those local fonts into new sub folder from week-4 local folder. After that step is done, repeat 5 steps from before with exception in the sixth steps as described by new steps below :

**Add fonts and Git Status**
![Add Fonts](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/addfont-editcss-gitstatus.JPG?raw=true)

**Git Status results**
![Git status results](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/gitstatus-result-merge.JPG?raw=true)

**Git add and git commit**
![Add Fonts](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/gitadd-oneoone-gitcommit.JPG?raw=true)

1. Before **git push**. Remember that updates should be in new branch to make it easier to create a pull request and merge on github (at least for author, git pull and git merge is easier to be done directly from github compare to integrated terminal in VS code, it easier to compare which codes that have changed). To create branch, use **git branch -b "New Branch Name"**.

    Git checkout branch
        ![Git checkout branch](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/gitcheckout-gitpush-branch.JPG?raw=true)

    Git push origin branch
        ![Git checkout branch](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/gitcheckout-gitpush-branch.JPG?raw=true)

2. After branch is created, the use **git push** to main branch. then if there is no error please visit or reload week-4 repository on github. **Compare & pull request** button should be appeared automatically on codes menu in week-4 repository then just click on that button to create pull request and merge new codes and add fonts folder into repository.

    ![Pull Request for css-update branch to main](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/css-update-pull-request.JPG?raw=true)

3. **Please checked**, whether there is any **conflict between 2 files** for example previous "style.css" file with new "style.css file. If there is conflict **please choose 1 part of codes that will be preserved and eliminate other codes that will not be used**. If there is no conflict anymore then add comments and click on **Create pull request** button.

    Compare Two CSS files
    ![Compare Two CSS files](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/compare%20css.JPG?raw=true)

    Comment for Pull Request
    ![Comment for Pull Request](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/comment-pullrequest.JPG?raw=true)

4. After github automatically checked the codes and if there is no conflict, the author outside from a collaborator could check the codes and give comments. If he agree to merge the updated css file and add fonts the author could give comment and then click **Merge pull request** then github will merge css codes and add font files from branch to main.

    ![Author comments on merge](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/author-mergecomment.JPG?raw=true)

    ![Confirm Megre](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/confirm-merge.JPG?raw=true)

![](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/.JPG?raw=true)

5. After it is done sucessfully, then, **the branch could be deleted safely**. 

    ![Delete Branch](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/safely-delete.JPG?raw=true)

_Remember : **Do not delete** the branch before one **sprint cycle or process is done**._

### Deployment into Netlify

Before going further with custom domain, codes from github should be deployed to netlify to get host that stored codes for the site. Here is the steps to do so :

1. **Log in** to netlify.app and head into **overview dashboard**.

2. On team overview, **add new site** and then **import an existing project**.

    ![Import from GitHub](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/netlifyimport-github.JPG?raw=true)

3. Then choose **Deploy with GitHub**. Wait until netlify authorized it.

    Choose github to be deployed
    ![Choose github to be deployed](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/choose-github-deploy.JPG?raw=true)

    Wait for authorization
    ![Wait for authorization](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/authorized.JPG?raw=true)

4. Choose **RevoU-FSSE-2** Repository then please choose **week-4-**_author's email name_. After that, please choose correct author or owner name and choose main branch to be deployed. Then scroll down, **click on  Deploy week-4-**_author's email name_ button that has light blue color. wait for netlfy in deploying process.

    Choose Week 4
        ![Choose Week 4](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/revou-week4.JPG?raw=true)

    Deploy from main
        ![Deploy from main](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/branchmain-netlify.JPG?raw=true)

    Deploy Week 4
        ![Deploy Week 4](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/deploy-week4.JPG?raw=true)

5. **Check the netlify** link whether its already deployed the site or not. if yes then continue to the custom domain stage.

    Check it from netlify

    ![Check it from netlify](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/check-netlifydeploy.JPG?raw=true)

    Check it directly on the browser
        
    ![Check it directly on the browser](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/check-netlifydeploy2.JPG?raw=true)

### Buy Custom Domain via Niagahoster

The company which is PT. Revolusi Cita Edukasi instructed to buy *.site domain from niagahoster. Then here is the steps to buy it:

1. Visit (https://niagahoster.co.id/) then, **sign up** or user can directly **sign in via google mail account**. Author choose to use gmail directly to reduce the steps needed.

    ![Sign in into Niagahoster](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/signin-niagahoster.JPG?raw=true)

2. **Find domain name** that author needs then check the **availability**.

    Check domain availibility
        ![Check domain availibility](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/check-site.JPG?raw=true)

    Site is available
        ![Check domain availibility](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/site-available.JPG?raw=true)

    _Remember : **Please use .site** because the maximum amount of payment that can be reimbursed by PT Revolusi Cita Edukasi is  **17K IDR**._

    Notes : please choose domain name that is **not create suspicion for niagahoster for example domain name with tendency of scams**. _(Expereince of a partner in oaur Team 4)_

3. If the domain available, click choose button then wait for it. After that, **continue to the payment**. Please choose payment whether it is virtual account, electronic wallet, et cetera. Then click checkout now.

    Result of Domain Choice
        ![Choose OVO e-wallet](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/result-choosepackage.JPG?raw=true)

    Choose OVO e-wallet
        ![Choose OVO e-wallet](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/choose-ovo-checkout.JPG?raw=true)

    _Remember : **Please read terem and conditions** eventhorugh the author have not read it yet however please make time to do that, make bookmark for that page._

4. Please complete the author identity to continue the payment process. The, pay now and continue the payment through your mobile banking or e-wallet. After it finished **please download the invoice in PDF** with official stamp and signature in it for reimbursment purpose with PT. Revolusi Cita Edukasi. **The deadline is on Sunday, July 9th 2023 23.59 GMT +7 / UTC +7 JKT BKK**.

    Fill domain buyer's data
        ![Fill domain buyer's data](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/fill-data.JPG?raw=true)

    Download Invoice
        ![Download Invoice](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/invoice-pdf.JPG?raw=true)

5. **Do not forget to verfy email** first to niagahoster otherwise **the domain could not be used**.

    E-mail Verification
        ![](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/verify-email.JPG?raw=true)

6. If there is any problem with niagahoster, author could choose alternatives such as hostinger, domainesia, godaddy or directly buy a domain on cloudflare.

_Intermezzo :  When will PT. Revolusi Cita Edukasi listed on Indonesia's Stock Exchange and make its Initial Public Offering ?is it already profitable from bootcamp activities as its core business? or is it still burn money? or is this PT does not want to share devidend to Indonesian public and keep it for itself or its owner and investors if it is profitable?_ 

### Connect it with Netlify and Cloudflare

After successfuly purchase the domain.site. Then, it should be connected to cloudflare then netlify. First, it should go through cloudflare first and make connection with it.

1. **Visit** (https://www.cloudflare.com/) then **Sign up**. Wait for its loading. Please fill up email and password then sign up and follow the isntructions.

    **Sign up on Cloudflare**
    ![Sign up on Cloudflare](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/cloudflare-signup.JPG?raw=true)

    **Fill Data Sign Up**
    ![Fill data for sign up](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/filldata-signup.JPG?raw=true)

    _Reminder :  Please read **Cloudflare's term, privacy policy and cookie policy first** please try to make the time for it even after finsihing this task_ 

2. After sign up, you or author could choose between **add a website directly** after sign up or **login through email verfication** in the email used for sign up (author used gmail). Add website directly display promotion and tutorial and if that is too distrubing then just choose verification through email.

    ![Insert domain site](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/insert-site.JPG?raw=true)

    _Reminder :  Please if **verifcation link is not valid** send the verification link again through cloudflare_ 

3. **Insert the author's domain.site** to the add site input area after that clicl **Add site** button. Wait for it to load

    ![Add Domain Site](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/add-domainn.JPG?raw=true)

4. Step 1, **choose annual plan** for domain.site. **Please choose free plan** beacuse it would not be reimbursed by our company (PT Revolusi Cita Edukasi). Then press continue button, scroll in the below free annual plan and then wait for quick scan.

    ![Choose Free Package Annual Plan](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/free-package.JPG?raw=true)

5. Step 2, Cloudflare ask to **add record for DNS management**. Author could add it or just continue then fill it later on. 

    ![DNS Record](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/dns-record.JPG?raw=true)

6. Please copy **Cloudflare's nameservers which have 2 item**. Then **paste and replace the nameserver on Niagahoster**.

    Copy Cloudflare Nameserver
    ![Copy Cloudflare Nameserver](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/cloudflare-nameserver.JPG?raw=true)

    Replace namserver
    ![Replace namserver](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/replace-namserver.JPG?raw=true)   

7. Please wait for oeverview page on dashboard **turned into green checklist** which shows **active status for domain.site**. While waiting for it, Author could manage DNS on **DNS menu** on dashboard then choose **record** and **add record**.

    Domain still Not Active
        ![Domain still Not Active](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/notactive.JPG?raw=true)

    Add netlify domain to DNS record
        ![Add netlify domain to DNS record](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/dns-records.JPG?raw=true)

    _Reminder : it takes arround 10 till 30 minutes for the domain.site to be activated and notified via email_

8. Author may **need to go back and forth between cloudflare and netlify**. Please **copy netlify domain** link and paste it to cloudflare DNS record on **target input then choose CNAME type the insert @ to Name, then save the record**.

    ![](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/.JPG?raw=true)

9. After the domain.site is active on Cloudflare, then **please set up custom domain** on **site overview or site configuration** on netlify dashboard. Insert domain.site to input area then **add domain**.

    Custom domain option on Netlify
        ![Custom Domain option on Netlify](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/custom-domain.JPG?raw=true)

    Verify site in Netlify
        ![Verify site in Netlify](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/verifysite-netlify.JPG?raw=true)

    Domain management menu
        ![Domain management menu](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/domain-mgmt.JPG?raw=true)

10. On Domain management, especially the Domains part, there will be a world wide web (**www**) link, please configure it too on Cloudflare again via DNS record and add new record to make it redirected to "https://domain.site".

    Add www to DNS record
        ![Add www to DNS record](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/dns-www.JPG?raw=true)

    Www has been added
        ![www has been added](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/www-site.JPG?raw=true)

    No awaiting external DNS anymore
        ![No awaiting external DNS anymore](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/no-awaiting.JPG?raw=true)

    Site is secured
        ![Site is secured](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/secured.JPG?raw=true)

    _Reminder : it takes arround 10 till 30 minutes for the connection between netlify, domain and cloudflare to be connected and could be checked by visiting ter domain.site_

11. If the process is done then visit domain.site. It will automatically display the site and there will be a **padlock symbol** on the left side of domain.site which indicates that the site is secure. Then, **Voila !! you ot the author has sucessfully deploy a custom domain with secure connection, Congratulations**.

![](https://github.com/RevoU-FSSE-2/week-4-andalanaldi/blob/main/screenshots/.JPG?raw=true)

Note : If there is enough time, author will add complementary screenshot to show the whole process and workflow of deployment with custom domain and also with new updates if it is necessary.

Documatation created by Aldi Andalan (andalanaldi@gmail.com) on last day of assignment as instructed step by step brief from the instructor.

**If you have any further question and feedback on (https://aldinotaher.site/) then please do not hesitate to reach out to him.**




