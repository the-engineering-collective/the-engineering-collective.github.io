# The Engineering Collective

The Engineering Collective is created by the community containing a breadth of learning materials. Browse the [collective](https://gwolverson.github.io/engineering-collective/) to learn more. 

## Mission Statement

The idea behind this collective is to gather a wide range of learning materials and experience together to form 'Quests', the idea of which comes from a learning 'journey'. 

This collective is open source. It _should_ be driven through the community. As a collective of engineers with a huge variety of skills and experience, we can use those skills and experience to help up-skill the engineers of the future. I feel we have a responsibility as engineers to share our knowledge as much as possible and to help pave the way for future generations.

## Contributing

There are several ways you can contribute to this collective; 
- Adding new content via Quests
- Updating content as things change and go out of date
- Suggesting new content areas to be added to the collective
- Reviewing and critiquing existing content

If you want to contribute, and please do, if you end up adding any new content, or updating existing content, please run the following command to run some basic spelling checks;

`npm run lint`

The outcome of which will either be; no issues or a set of errors from the markdown-spelling checker. Please address any issues before raising a pull request, as any issues will be found during the build anyway.

**NOTE**: If the spell check raises an error, but the word(s) in question are correct (code be a coding language word etc) then feel free to add the word to the `.spelling` file. This ensures the word won't be picked up as part of future spelling checks.

### New Content

The content of this collective _should_ be community driven. To that end, here's how you can contribute to the material contained inside.

* Decide what content you want to contribute, it can be a whole new 'Quest', update to an existing 'Quest' or maybe a new content area you feel is missing.
* Fork this repository

#### Creating a Quest

   1. Create a new 'Quest' folder beneath `./docs/quests/` - naming conventions: lower case, hyphenated, e.g. `kotlin-engineer`
   2. Add a `index.md` file to the root of this folder (e.g. `kotlin-engineer/index.md`) outlining the Quest, it's Roadmap (see 'Creating a Roadmap' below), the resources, certifications and engineer suggestions (see another Quest README file for an example).

#### Creating a Roadmap

The Roadmap is crucial to each Quest, it helps outline a visual path through the particular _quest_. Roadmaps in this collective have been created via [draw.io](https://www.draw.io/) which is a free diagram creation software, although feel free to use other software as long as the diagrams look similar for consistency. Each roadmap is pretty straight forward, and follows a simple layout: 
  * Each diagram should have a 'key' defining which parts of the roadmap are; Must Know, Good to Know and Further Knowledge. Which _skills_ fit into these categories is up to you as the Quest creator - remember it can always be updated over time!
    * Colour scheme wise, the following colours have been used for the 3 main categories:
      * Yellow - Must Know
      * Light Blue - Good to Know
      * Light Grey - Further Knowledge
  * Each diagram should follow some semblance of order, think of it as a journey from beginner to master - so it makes sense to place the really important 'core' stuff first, then follow with the more complex, 'mastery' level stuff towards the end. 
  * When you're ready to export your diagram from whichever software you've used to create it, it's best to export _only_ the diagram and not any extra page space. This can be done on draw.io via selecting all (Ctrl+A or command+A) and clicking File -> Export as -> PNG... naming conventions wise: <quest>_path.png, e.g. java_path.png
    * When exporting the .png version of the diagram, it's also useful to export the XML version as well, for ease of import if someone wants to update diagram in the future. 
    * Both the exported png and xml files then go into the following project location; docs/assets/img and docs/assets/xml respectively.

## Suggestive Changes

If you have a good idea for a new Quest, changes to an existing quest, or a new content area, but don't have the time to create the content yourself, please still feel free to raise an 'issue' on the Github repository with a label of 'enhancement' - this allows us to categorise issues properly. 
  * For new quests, please use the issue title: 'New Quest: <Quest Name>' e.g. 'New Quest: Kotlin Engineer'
  * For updates to quests, please use the issue title: 'Update Quest: <Quest Name>' e.g. 'Update Quest: Java Quest'
  * For new/additional content, please use the issue title: 'New Content: <Content Name>' e.g. 'New Content: New Section' 

## Content Errors 

If you've spotted any spelling or grammatical errors in the collective, or accompanying markdown files, please feel free to fix and raise a pull request. Again, ensuring you run the linter to check for spelling and grammar first:

`npm run lint`
