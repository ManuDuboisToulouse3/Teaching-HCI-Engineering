---
layout: page
title: Howto
permalink: /guide/
---

# How to propose a case study.

The [IFIP WG 2.7/13.4](http://ui-engineering.org) is maintaining a list of case studies for teaching Human-Computer Interaction (HCI) Engineering. 
You can propose to add your own through a pull request to the case study repository. You can also request some changes to the existing content following the same procedure. 

For completing the guide, you will be needing a [GitHub account](https://github.com).


## Step 1: Fork the Teaching HCI Engineering repository
* Log-in using your [GitHub account](https://github.com)
* Fork the [Teaching HCI Engineering](https://github.com/IFIP-WG-2-7/Teaching-HCI-Engineering). This will create your personal copy of the repository. If you already sent content in the past, you can reuse the existing one and skip this point. 

![fork]({{site.baseurl}}/images/guide/imagefork.png)

## Step 2: Create a new branch for the request

Create a new branch in your copy of the repository, as shown in the following image.

![branch]({{site.baseurl}}/images/guide/imagebranch.png)

 1. Click on *main* (red box)
 2. Enter a *branch name* (green box). In order to help us with the management, please name the branch using the case study title. For instance `fantasy-soccer`.
 3. Finally, click on `Create Branch` (blue box).  

In this way, you have created a new branch in your copy of the project.

## Step 3: Create or Edit the content
Before proceeding, please double-check that you are modifying the branch created at Step 2. 

### Propose new content
If you are proposing a new case study, please complete the following steps: 

1. Go to the `_case_studies` folder.
   
2. Click on `Add file`, then `Create new file`. 

![newfile]({{site.baseurl}}/images/guide/newfile.png)

3. Create a file named `[case-study-title]/description.md`, where `[case-study-title]` is the title of your case study.
    

![insert]({{site.baseurl}}/images/guide/insert.png)


4. Copy & Paste the following template and fill it with your content and metadata. Elements inside angular brackets (e.g., `<this one>`) must be changed with a proper value.

```
---
layout: case-study
title: <Your case study title>
authors:
    - author: 
        name: <Your name>
        surname: <Your surname>
        url: "<URL to your website (for contact)"
    - author:
        name: <Optional co-author, you can add more than one>
        surname: <...>
        url: "<...>"
type: <Project or Exercise>
application-domains: 
  - <first application domain (e.g., Healt)>
  - <second application domain (if any)
  - <...>
interaction-techniques:
    - <first interaction technique (e.g., WIMP)>
    - <second interaction technique (if any>
    - <...>
brief-description: "<a few lines of description>"
---
## Targeted students and prerequisites
<content in markdown format>

## Objectives
<content in markdown format>

## Pedagogical steps/monitoring, initial materials and tools
<content in markdown format>

## Expected outputs and Evaluation
<content in markdown format>
```

5. The resulting file must contain a structured data section (between the two `---`), and the content written in [Markdown syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

6. (Optional) Upload assets files (e.g., logos, member pictures) inside the `[case-study-title]` folder. You can refer them using relative URLs inside the Markdown content. 

### Modify existing content
In this case the procedure is simpler. Change the existing content through the GitHub editor and proceed to the next step. 

## Step 4: Commit the changes in your repository copy
1. (Optional, but recommended) Add a small summary of the new or changed content you are proposing. 
2. Commit to your repository by clicking the `Commit new file` button. If you are requesting changes to existing content, press the `Commit` button.

![commit]({{site.baseurl}}/images/guide/commit.png)

## Step 5: Send the pull request to the original project.

1. Click on `Pull Requests`;
![pull1]({{site.baseurl}}/images/guide/pullStep1.png)

2. Then, click the `Compare & pull request` button;
![pull2]({{site.baseurl}}/images/guide/pullStep2.png)

3. Finally, click the `Create pull request` button.
![pull3]({{site.baseurl}}/images/guide/pullStep3.png)


## That's all, folks!
Congratulations, you completed the pull request process!  Once accepted, the new content or the updates will published in the website. In case you will need to change it, you can send another pull request. 


