## Add yourself to the lab's website

> Welcome to Khan Lab! 🎉 To add yourself to the [team page](https://khanlab.bio/team/), please follow the instructions below.



### Step 1: Fork and Clone the Repository

If you haven’t already, fork and clone the lab website repository:

```bash
git clone https://github.com/khan-lab/khan-lab.github.io.git
cd khan-lab.github.io
```

### Step 2: Create Your Profile Markdown File

Navigate to the `_members/` directory and create a new file named with your **first and last name** separated by a dash (`-`):

```
_members/firstname-lastname.md
```

📌 Example:
```
_members/aziz-khan.md
```


### Step 3: Fill in Your Metadata and Bio

Use the following template and customize it with your own details:

```yaml
---
name: Your Full Name
image: /images/team/name.jpg
role: member
description: Your Role Title (e.g., Research Associate, Postdoc, PhD Student)
links:
  google-scholar: scholar_id  # optional
  home-page: https://yourwebsite.com  # optional
  bluesky: bluesky  # optional
  github: yourgithub  # optional
  orcid: 0000-0000-0000-0000  # optional
  twitter: yourtwitter  # optional
  email: email@mbzuai.ac.ae
---

A short bio (2–4 sentences) about your background, interests, and what you’re working on at the lab.
```


### Step 4: Add Your Profile Image

- Image must be square, ideally 400x400 px.
- Save the image as `firstname-lastname.jpg`.
- Place the image in:

```
assets/images/team/
```


### Step 5: Commit and Push Your Changes

```bash
git add _members/firstname-lastname.md assets/images/team/firstname-lastname.jpg
git commit -m "Add [Your Name] to team page"
git push origin main  # or create a Pull Request if using a fork
```


### Step 6: Verify

After the site rebuilds, check your profile on the team page:

👉 https://khanlab.bio/team/


### More Examples

You can check the markdown files for all the members [here](https://github.com/khan-lab/khan-lab.github.io/tree/main/_members) to use as an example or copy one and edit. 

If you run into any issues, feel free to ask a senior lab member or open an issue on the repository.
