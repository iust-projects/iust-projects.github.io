---
title: "Frequently Asked Questions"
layout: page-sidebar
permalink: "/faq"
comments: true
---

<div class="question">
<a href="#q-what-is-iust-projects">What is 'IUST Projects'?</a>
<a href="#q-who-created-this-organization">Who created this organization?</a>
<a href="#q-is-this-an-official-iust-website">Is this an official IUST website?</a>
<a href="#q-can-i-join-this-organization">Can I join this organization?</a>
<a href="#q-i-am-a-member-of-organization-however-i-am-not-in-the-websites-members-page-why">I am a member of organization, however I am not in the website's members page. Why?</a>
</div>

<div class="alert alert-success" role="alert">
  If you have any questions that are not listed below, please ask in comments.
</div>

#### Q: What is 'IUST Projects'?

A: IUST Projects is an open GitHub organization with a focus on showcasing and maintaining projects created at Iran University of Science and Technology.

#### Q: Who created this organization?

A: This website and its GitHub account was initially created by [Aryan Ebrahimpour](/member/aryan) and [Nikan Doosti](/member/nikan).

#### Q: Is this an official IUST website?

A: No. This website and its organization is maintained by its true owners, the students and the contributors outside of the university.

#### Q: Can I join this organization?

A: Of course, joining this organization is open, even if you are not a student of IUST. Use the [contact form](http://iust-projects.ir/contact.html) to let us know you want to join, or send an email to either:

- [Aryan Ebrahimpour](mailto:Oxaryan@outlook.com)
- [Nikan Doosti](mailto:nikan.doosti@outlook.com)

We'll send you an invitation mail as soon as we can.

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