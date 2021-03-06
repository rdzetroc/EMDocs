<properties pageTitle="File names and locations for EMS technical articles" description="Explains the file structure for articles and the naming conventions you should follow when you create a new article." metaKeywords="" services="" solutions="" documentationCenter="" authors="tysonn" videoId="" scriptId="" manager="required" />

<tags ms.service="contributor-guide" ms.devlang="" ms.topic="article" ms.tgt_pltfrm=""  ms.workload="" ms.date="02/25/2016" ms.author="v-jocgar" />

# File names and locations for EMS technical articles
To Do: 
- [ ] #7 Pull in the services slugs for examples
- [ ] #8 Confirm the file naming pattern
- [ ] #9 Provide replacement examples of file naming patterns
- [ ] #10 Make sure all links (especially anchors) work properly

In our technical content repository, we use a single folder (the **articles** folder) for all articles. There's no folder hierarchy - all articles live in the flat file structure. If you create folders with articles in them, your articles can't be published.

Instead of using a file structure as an organizing principle, we use a strict file naming convention that clearly identifies topics and that contributes towards discoverability on the web.

Here's what you need to know:

+ [Rules for naming files]
+ [File name patterns]
+ [Examples]
+ [File name approval]

## Rules for naming files

- No spaces or punctuation characters. Use hyphens to separate the words in the file name.
- Use all lowercase letters
- No more than 80 characters - this is a publishing system limit
- Use action verbs that are specific such as develop, buy, build, troubleshoot. No -ing words (gerunds).
- No small words - don't include a, and, the, in, or, etc.
- All files must be in markdown and use the .md file extension.

## File name patterns

Here's the general naming pattern:

<span style="color:red;">Need confirmation on this file naming pattern.</span>
 **service-platform-language-content-product-version.md**

Use the parts of the pattern that apply, and review the list of articles in the repository to get an idea of existing names. 

## Examples
<span style="color:red;"> **Need replacement examples for this section from docs.microsoft.com/ems**  </span>

Here are a few examples of valid names that follow the pattern:

- cloud-services-dotnet-continuous-delivery.md
- mobile-services-ios-get-started.md
- documentdb-manage-account.md
- mobile-services-dotnet-backend-get-started-settings-sync.md
- active-directory-java-authenticate-users-access-control-eclipse.md
- virtual-machines-install-windows-server-2008r2.md

## File name approval

It's the job of our group of pull request reviewers to review file names when a new file is submitted to the repository for the first time. Pull request reviewers should review the file name and provide feedback if changes are needed. The file name needs to be corrected before the pull request is accepted. Contributors can easily push the update to the pending pull request.

## Back to Home

- [Overview article](./../README.md)
- [Index of guidance articles](./contributor-guide-index.md)


<!--Anchors-->
[Rules for naming files]: #rules
[File name patterns]: #pattern
[Examples]: #standard-examples
[File name approval]: #file-name-approval
