---
title: "Frequently Asked Questions"
layout: page-sidebar
permalink: "/faq"
comments: true
---

<div class="alert alert-success" role="alert">
  If you have any questions that are not listed below, please ask in comments.
</div>


#### Q: Can I join this organization?

A: Yes, joining this organization is open, even if you are not a student of IUST. Use the [contact form](http://iust-projects.ir/contact.html) to let us know you want to join, or send an email to either:

- [Aryan Ebrahimpour](mailto:Oxaryan@outlook.com)
- [Nikan Doosti](mailto:nikan.doosti@outlook.com)

#### Q: I am a member of organization, however I am not in the website's members page. Why?

A: Because website does not automatically create a profile for you after joining the organization. If you want to have an special page
that is displayed in the [members](/members) page, simply:

1. Fork the [iust-projects/iust-projects.github.io](https://github.com/iust-projects/iust-projects.github.io) project.

2. Add your info to [Members File](https://github.com/iust-projects/iust-projects.github.io/blob/master/_data/members.yml). Make sure to use a unique id, and the yaml file key matches your `id`. like:
   ```yaml
   myusername:
       id: myusername
       ...
   ```

3. Add "{your username}.md" file in the [members folder](https://github.com/iust-projects/iust-projects.github.io/tree/master/member) and write about yourself. like *`aryan.md`* or *`nikan.md`*.
   
4. Send a pull request.