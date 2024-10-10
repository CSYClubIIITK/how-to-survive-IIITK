# Contributing to *How to Survive IIITK* 💻🎉

Hey awesome contributor! 👋 We’re thrilled you want to help make life at IIITK easier for everyone. Contributing to this project is super simple, but we’ve laid out some guidelines to make sure everything goes smoothly and looks fabulous in our GitBook.

Here’s how to get started:

---

## 1. Fork and Clone the Repo

First, fork the repository and clone it to your local machine:

```bash
git clone https://github.com/<YOUR-USERNAME>/how-to-survive-IIITK.git
```

Navigate into the project directory:

```bash
cd how-to-survive-iiitk
```

---

## 2. Write Your Article 📝

- **Step 1:** Create a new Markdown file in the required `/<category>` directory. For example `/food`, `/travel`, `/acads`, `/tech`, `/sports`, etc...
  - The file name should be descriptive of your topic (e.g., `best-food-places-in-pala.md` or `how-to-survive-x-professor.md`).
  - Your blog post should be written in Markdown and follow a conversational, helpful, or even humorous tone (just like chatting with your friends!).
  
- **Step 2:** Write your article with as much detail as possible. Here’s a basic template to get you started:

```md
# Title of Your Article

## Introduction
Start with a brief intro to your topic. Hook the reader in!

## Main Content
Break your content into sections with headings, subheadings, and bullet points if needed.

You can use:
- Lists
- Tips
- Examples
- Code snippets (for tech-related topics)
- Images (if relevant, but try to keep things lightweight)

## Conclusion
Wrap it up with a conclusion or takeaway message.

---
*Happy surviving at IIITK!* 🎉
```

---

## 3. Update the `summary.md` 📚

Once you’ve written your article, make sure to link it in the **`summary.md`** file so it appears in our GitBook’s navigation.

1. Open the `summary.md` file located at the root of the repository.
2. Add your blog post as a bullet point under the appropriate section, like so:

```md
* [Title to show in navigation](<category>/<article-name>.md)
```

Make sure the link is correct and pointing to the new Markdown file you just created in the `/<category>` folder.

---

## 4. Create a Pull Request (PR) 🚀

Once your article is written and linked in `summary.md`, it’s time to open a Pull Request!

1. **Stage and commit** your changes:

```bash
git add <category>/<article-name>.md summary.md
git commit -m "Added blog on <artice topic>"
```

2. **Push** your changes to your fork:

```bash
git push origin YOUR-BRANCH-NAME
```

3. Open a Pull Request from your forked repo on GitHub. Make sure to include a brief description of your article in the PR.

---

## 5. PR Review and Feedback 🔍

Once your PR is open, we’ll review it as quickly as possible! 🚀

- If everything looks good, we’ll merge your changes and your blog post will be live on the GitBook.
- If there’s any feedback or requested changes, we’ll let you know what needs to be fixed, so don’t worry!

---

## Pro Tips 💡

- **Be specific and clear:** Try to provide concrete tips, step-by-step guides, or actionable advice for surviving life at IIITK.
- **Keep it fun:** Humor is welcome (but keep it appropriate). Make your article enjoyable to read!
- **Stay organized:** Use headings, lists, and concise paragraphs to keep things structured.
- **Check your spelling/grammar:** Everyone appreciates well-written content.

---

## Need Help? 🤔

If you run into any issues or need help with your contribution, feel free to:
- Open an issue in the GitHub repo
- Ping us on the project’s discussion board

We’re here to make contributing as smooth as possible!

---

Thank you for being part of this project and helping the IIITK community thrive! 🎉🎓

Happy hacking and writing!