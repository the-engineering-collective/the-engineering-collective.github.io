# The Engineering Collective

The Engineering Collective is a GitBook created by the community containing a breadth of learning materials. Read the [book](https://gwolverson.github.io/engineering-collective/) to learn more. 

## Mission Statement

The idea behind this book is to gather a wide range of learning materials and experience together to form 'Quests', the idea of which comes from a learning 'journey'. 

This book is open source. It _should_ be driven through the community. As a collective of engineers with a huge variety of skills and experience, we can use those skills and experience to help up-skill the engineers of the future. I feel we have a responsibility as engineers to share our knowledge as much as possible and to help pave the way for future generations.

## Contributing

There are several ways you can contribute to this book; 
- Adding new content via Quests or Skills
- Updating content as things change and go out of date
- Suggesting new content areas to be added to the book
- Reviewing and critiquing existing content

However you decide to contribute, and please do, if you end up adding any new content, or updating existing content, please run the following command to run some basic spelling checks;

`npm run lint`

The outcome of which will either be; no issues or a set of errors from the markdown-spelling checker. Please address any issues before raising a pull request, as any issues will be found during the build anyway.

**NOTE**: If the spell check raises an error, but the word(s) in question are correct (code be a coding language word etc) then feel free to add the word to the `.spelling` file. This ensures the word won't be picked up as part of future spelling checks.

### New Content

The content of this book _should_ be community driven. To that end, here's how you can contribute to the material contained inside.

* Decide what content you want to contribute, it can be a whole new 'Quest', or an individual 'Skill'.
* Fork this repository

#### Creating a Quest

   1. Create a new 'Quest' folder beneath `./docs/quests/` - naming conventions: lower case, hyphenated, e.g. `kotlin-engineer`
   2. Add a `index.md` file to the root of this folder (e.g. `kotlin-engineer/index.md`) outlining the Quest and the list of skills to learn (see another Quest README file for an example)

#### Creating a Skill

   1. Decide whether the Skill is [technical](./docs/skills/technical/index.md) or [non-technical](./docs/skills/non-technical/index.md)
   2. Choose the _category_ the Skill should sit within, if no category exists, create one:
      1. Add a new folder for the category beneath the relevant technical/non-technical folder, and a `index.md` file at the root, explaining what type of skills the category encapsulates
   3. If the category already exists or after creating a new category:
      1. Create a new Skill markdown file under the relevant category - naming conventions: lower case, hyphenated, e.g. `gradle.md` - when creating the new 'Skill' document, please refer to the [Skill Template](skill-template.md) markdown file.
    4. When you're happy with your new content, please issue a pull request back into this repository

## Suggestive Changes

If you've spotted any spelling or grammatical errors in the book, or accompanying markdown files, please feel free to fix and raise a pull request. Again, ensuring you run the linter to check for spelling and grammar first:

`npm run lint`
