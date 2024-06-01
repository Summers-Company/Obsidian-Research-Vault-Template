---
tags:
  - subject
---
> [!success] 
>  🥳 Yay, you installed Obsidian. For a nice exteranal guide, look at the [obsidian documentation](https://help.obsidian.md/Obsidian/Index)

Welcome to this Vault, your dedicated space for leveraging [[Obsidian]] as a powerful second brain to aid your academic research. This vault is designed to demonstrate the effective use of Obsidian and [[Git]]/[[GitHub]] in academia (*Git and GitHub **are in fact different** learn more at [[Git vs. Github]]*). We've integrated essential plugins and custom templates that will assist you in getting the most out of your research.

Continue reading to discover the benefits and functionalities of [[Obsidian]].
# Philosophy

[[Obsidian]] is a note-taking app where you edit simple text files known as [[Markdown]] ( *◀ press ctrl as you hover over the highlighted word 'Markdown' for a surprise!*  ) files which are enhanced with many powerful easy to use features. Unlike cloud-based apps like [[Notion]], [[Obsidian]] stores your data locally on your machine, giving you full control over your notes.

> [!important] 
> If the company behind [[Obsidian]] ever went down then you would still just have all your notes on your computer. They are just markdown files ```.md extension``` so could be imported into a new app

### Why Obsidian?

The core idea behind [[Obsidian]] is to move away from rigid folder structures and instead focus on capturing your ideas freely. By linking these ideas together, a natural structure emerges that aligns with your unique way of thinking. This approach not only enhances your note-taking but also allows you to leverage AI to gain deeper insights from your notes.

>[!Example]
> ### Rigid File Structures vs. Obsidian for a Meme
> 
> #### Rigid File Structures
> 
> Imagine you come across a meme that is funny, features a cat, and involves a piano. In a traditional file structure, you might struggle to decide where to save this meme. Do you put it in:
> 
> - **Humor Folder**: Because it's funny.
> - **Cats Folder**: Because it has a cat.
> - **Music Folder**: Because there's a piano.
> 
> You might end up duplicating the file into multiple folders, which can quickly become a disorganized mess, or you might save it in just one folder and struggle to find it later because it fits multiple categories.
> 
> #### Obsidian
> 
> In Obsidian, you don't have to worry about fitting this meme into a single rigid category. Instead, you can:
> 
> 1. **Create a Note for the Meme**: You can create a note titled "Funny Cat Piano Meme".
> 2. **Tag and Link**: Add relevant tags like `#funny`, `#cat`, `#piano`, and `#meme`.
> 3. **Link to Related Notes**: If you have other notes about memes, cats, or pianos, you can create links to those notes.
> 
> This way, when you want to find this meme, you can search by any tag or keyword, and Obsidian will show you all related notes. The note can exist in multiple contexts without needing to duplicate it. This approach allows you to effortlessly retrieve and connect your notes based on any attribute or context you remember, leveraging the full power of linked ideas and tags.

Using [[Obsidian]] for note-taking and information management in academia offers a flexible and powerful alternative to rigid file structures. By linking these ideas together, _structure can naturally form_ that matches your way of thinking. This dynamic approach not only simplifies your workflow but also enhances your ability to connect ideas and gain deeper insights from your notes.

> [!Note]
> [[Obsidian]] also has many core plugins like "Slides" which allows you to make slide shows within the application itself! Learn how at [[My First Presentation]]
# Concepts

### Obsidian Graph View and "Ghost Topics"

One of the standout features of [[Obsidian]] is the Graph View, which visually represents the connections between your notes. This powerful tool helps you see the relationships between different pieces of information, making it easier to understand and navigate your knowledge base.

#### Graph View

The Graph View displays your notes as nodes connected by lines, representing the links between them (*To see the graph view it should be in the bottom right of your vault if not press the ```open graph view``` button in the left side panel*).

- **Node Size**: The size of each node increases with the number of links it has. This makes it easy to identify your most connected notes at a glance.
- **Clusters**: Notes that are closely related form clusters, helping you see how different topics and ideas group together.
- **Navigation**: Clicking on a node brings you directly to that note, allowing you to explore your connections easily.

> [!About] 
> #### Benefits
> - **Visual Relationships**: See how your ideas and notes are interconnected.
> - **Identify Key Notes**: Larger nodes highlight the most linked and potentially important notes in your vault.

#### "Ghost Topics"

"Ghost Topics" are concepts or ideas that you link to frequently but haven't created a dedicated note for yet. These are placeholders or potential notes that you can flesh out later.

- **Creating Links**: You can create links to these ghost topics using `[[ ]]` even if the note doesn't exist yet. This way, you can link related notes to these topics as they arise. For example, if you link to [[Notion]] and [[Obsidian]], you'll notice that [[Notion]] is a darker link compared to [[Obsidian]] as the note for [[Notion]] doesn't exist yet. This visual cue helps you differentiate between existing and non-existing notes.

- **Identifying Growth**: As you continue to link to these ghost topics, you might notice certain ones becoming more central to your research. When a ghost topic has many links, it indicates that it's a significant concept worth creating a dedicated note for.

- **Easy Visibility**: Another benefit of ghost topics is that when you type `[[` to create a link, [[Obsidian]] will show you all files, including ghost topics. This makes it easy to see and manage your ghost topics as you create new notes.

> [!About] 
> #### Benefits
> 
> - **Flexibility**: Allows you to create connections without needing to have a full note ready.
> - **Scalability**: Helps you identify emerging themes and topics that are becoming important in your research.
> - **Proactive Organization**: Encourages you to stay on top of growing topics and organize your notes effectively.


### Using Graph View and Ghost Topics in Academic Research

The Graph View and the concept of "Ghost Topics" enhance your ability to manage and visualize your research. By using these features, you can:

- **Track the Evolution of Ideas**: See how your understanding and research on a topic develop over time.
- **Identify Key Themes**: Recognize which concepts are central to your work and need further exploration.
- **Optimize Your Notes**: Efficiently manage your notes by identifying when to convert ghost topics into fully fleshed-out notes.

These tools make [[Obsidian]] not just a note-taking app, but a dynamic environment for academic research and knowledge management, helping you uncover connections and insights that might otherwise be missed.
### Front Matter in Obsidian

Obsidian allows you to add metadata to your notes using a feature called front matter. Front matter is written in YAML format and placed at the top of your Markdown files between triple dashes (`---`). This metadata can include information such as the title, author, date, tags, and more. It helps organize your notes and makes it easier to search and filter them within Obsidian.

For example, a note with front matter might look like this:

```yaml
---
title: "Research on AI"
author: "Jane Doe"
date: "2024-05-31"
tags: ["AI", "research", "machine learning"]
---
```

In this example:
- **title**: The title of the note.
- **author**: The author of the note.
- **date**: The creation or last modification date of the note.
- **tags**: Keywords associated with the note for easier searching and categorization.

Using front matter in Obsidian helps you keep your notes organized and enhances the functionality of your second brain by allowing you to add meaningful context to each note.
#### To learn more, click the link: [[Front Matter]]

### Using Tags in Obsidian

Tags in Obsidian are a simple yet powerful way to categorize and organize your notes. They help you quickly find and connect related information, making your note-taking system more efficient and intuitive.

**What are Tags?**

Tags are keywords or labels that you add to your notes using a `#` symbol followed by the tag name, like `#research` or `#meeting`. They can be placed anywhere in your note, and you can use multiple tags in a single note.

#### Why Use Tags?

- **Organization**: Tags help categorize notes by topics, projects, or any criteria you choose.
- **Searchability**: Quickly search and filter notes by tags to access related information.
- **Flexibility**: Unlike folders, tags are not hierarchical, allowing for a more fluid organization.

#### How to Use Tags

1. **Adding Tags**: Type `#` followed by the tag name, e.g., `#research`.
2. **Multiple Tags**: Use multiple tags in a note for broader categorization, e.g., `#research`, `#meeting`.
3. **Tag Pane**: Access the Tag Pane from the sidebar to view and navigate all tags in your vault.

> [!Info]
> For a note about a research meeting on AI, you could use tags like `#research`, `#meeting`, and `#AI`. Later, search for `#AI` to find all related notes.
> > [!Example]
> > I am a #research note that is about #AI being used for solving a problem

#### Advanced Tag Usage

- **Nested Tags**: Create detailed categories with nested tags like `#research/AI`.
- **Tag Combinations**: Search for notes with multiple tags, e.g., `#research` and `#AI`.

#### Benefits

Tags provide a flexible and dynamic way to organize your notes, enhancing your ability to link related ideas and manage information efficiently. They make Obsidian a powerful tool for academic research and personal knowledge management.

### Plugins in Obsidian

[[Obsidian]]'s true power lies in its extensive range of plugins, which allow you to customize and enhance your note-taking experience. These plugins add new features and functionalities to [[Obsidian]], making it a highly flexible and adaptable tool for academic research and personal knowledge management. In this vault, we've integrated several essential [[Obsidian - Plugins|plugins]] to help you get the most out of your research.
#### Installing and Managing Plugins

To install a plugin in [[Obsidian]]:
1. Open the Settings menu.
2. Navigate to the "Community Plugins" section.
3. Click on "Browse" to explore the available plugins.
4. Select the plugin you want to install and click "Install."
5. Once installed, enable the plugin by toggling the switch.

You can manage your installed plugins from the "Plugins" section in the Settings menu. Here, you can enable or disable plugins, configure their settings, and update them to the latest versions.

**Benefits of Using Plugins**

Plugins allow you to tailor Obsidian to fit your specific workflow and needs. They add powerful new features, streamline repetitive tasks, and connect Obsidian with other tools and platforms you use in your research and daily life. By leveraging these key plugins, you can transform Obsidian into a highly personalized and efficient tool for managing your academic research and personal knowledge. These plugins help you stay organized, save time, and enhance your productivity, making your research process smoother and more effective.

To explore more about plugins and how to use them, visit the [Obsidian Community Plugins](https://obsidian.md/plugins) page.

---
# Beware the Rabbit Hole

This setup took quite a while to make, and involved a deep dive into the rabbit hole. [[Obsidian]] is always changing, and there are so many [[Obsidian - Plugins|plugins]] that it's hard to keep up.

While it's tempting to spend a lot of time tweaking and optimizing every little detail, especially with all the plugins and customization options available, it's important to remember the primary goal: **focusing on your notes and research.**

> [!info] 
> Try out this setup and tweak it to suit you. Usually, these changes can be made in the settings for each [[Obsidian - Plugins|plugin]], or by visiting the Obsidian forums.

> [!tip] 
> If you think of a good idea, someone has probably made a plugin for it.

Obsidian is a powerful tool, but don't let the endless customization options distract you from your academic goals. Use the features and plugins that genuinely enhance your productivity and research process, and remember that sometimes simpler is better. Focus on capturing and organizing your ideas, and let Obsidian's flexibility work for you, not against you.

---

# Conclusion

Now that you know about [[Obsidian]], you can see how this vault works. [[Obsidian]] is more than just a note-taking app—it's a versatile tool designed to enhance how you capture, organize, and connect your thoughts and research. The power of [[Obsidian]] lies in its adaptability and the community-driven innovations that continually evolve through plugins and updates.

Use [[Obsidian]] to build a personalized knowledge management system that aligns with your academic needs and personal goals. While it's easy to get drawn into perfecting your setup, focus on the functionality that directly benefits your work. The right balance will not only boost your productivity but also enrich your learning and research experience.

Whether you're jotting down quick notes, drafting detailed research, or collaborating on projects, [[Obsidian]] can be your digital workspace that grows and adapts with you. Dive in, explore its capabilities, and make it your own. And always remember to step back from the rabbit hole of endless customization to ensure that technology serves you, not the other way around.

For further guidance, don't hesitate to utilize resources like the [[Obsidian]] forum and the vast array of tutorials available online. Harness the full potential of [[Obsidian]], and transform the way you think, learn, and create.

To see an overview of how this vault is structured, visit [[Obsidian - Vault Overview|Vault Overview]].