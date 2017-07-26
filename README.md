# Adaptive App

The goal of this project is to create a basic but highly modifiable communication tool for people who have some barrier to communicating verbally. 
A common tool in communicating with patients who cannot verbally communicate but can indicate either with their own technique or with the help of a caregiver is a **word board**. Word boards have conventionally been created and used from a prefabricated paper pad with tear off sheets or by one of the rehabilitation team members writing a patient-focused list of vocabulary words onto a paper that the patient can see and interact with. Understandably, the paper word boards have a number of limitations. Most importantly, they are not particularly durable, they can not be easily modified, and they are not customizable to the patient's experiences.

The main sections of the app address making a word board by pulling from a pre-loaded dictionary, communicating a medical need summary, and a 'free type' section for general communication. In the next section below, you will find notes and sketches for each functional section of the application.

---
## 'Home' Screen
![Home Screen](https://github/pickwickian/orange-banana/HomeScreen.png)
This screen displays all sub-action items the application offers. Each sub-action item is discussed below. In short:
- Converse has the functionality of generating a message onto the screen by selecting words from the dictionary or selecting saved person icons. The message stays on the screen until the screen is cleared by the user or aide. 
- People: in this section, users can connect a picture to a saved name. The picture is saved with the name underneath and the icon is then usable much like an emoji in the converse section.
- Dictionary: this is a standard dictionary application using a pre-loaded dictionary. There are a few special additions to this section outside of a standard dictionary app. These modifications are addressed in the dictionary specific section.
- Saved boards: this section is simply a set of saved digital word boards.
- Medical: This is a series of survey type screens that then summarizes the selected options into a concise 1 page medical complaint and detail list for acute medical issues.

## 1. Converse
![Converse](orange-banana/Converse.png)
There are three options in the converse section to add a word or concept to the message:
1. People: This option accesses the People sub-action menu and allows the user to select a person-icon block. The selected icon block is placed in the next open/available block space (denoted in the drawing with the underscore height lines).
1. Dictionary: This option accesses the Dictionary sub-action menu and allows the user to select a word. The word is then placed in the next open block space.
1. Type: This option pulls up a letter board (users can select QWERTY arrangement or ABC arrangement) and allows them to select a series of letters in sequence and then select 'ENTER.' Once enter is selected, the entire letter sequence is treated as a block and entered into the next open block space in the converse board interface.

## 2. People
![People](https://github/pickwickian/orange-banana/People.png)
The concept for this section is that users can access the built-in camera of the tablet or the tablet's photo directory and link a picture to a name. This picture+name combo then becomes an icon that can be used in other sections of the application.

Special features for this section:
- a built in camera interface so that users can connect new people they interact with immediately with a name and save the icon
- option to a tag an icon and use the tag in searches for other app functions (namely, the converse section and the word board section)

## 3. Dictionary
![Dictionary](https://github/pickwickian/orange-banana/Dictionary.png)
The overall idea for this is just access to a pre-loaded dictionary with predictive search. The first tab will give the user a screen with the most used words.

Special features for this section:
- ability to tag words

## 4. Basic Boards
![Basic Boards](https://github/pickwickian/orange-banana/BasicBoards.png)
This section is composed of two related resources:

1. Users can use the camera interface and take a picture of word boards their aides, rehabilitation specialists, family members, teachers, etc. create for them. The image is then saved in the slot marked <<Board 1>>. Essentially, this is simply a way to digitally store word boards. These boards are not interactive and cannot be changed. Users use them by selecting the preview from the page seen in the image (ie., the preview would be a smaller image of whatever image the user saved for <<Board 1>>). When a preview is selected, that word board image fills the screen and users indicate words in their usual manner.

2. The other option is to 'Build a dictionary board.' To create a dictionary board, the user does the following:
- Selects one of the 'Build a dictionary board' slots.
- This opens up a build option page that has 3 options: add people, add words, or add from tags.
- The add people and the add words options are essentially the same: these options open up the People and Dictionary sub-action menus respectively and allow the user to select icons or words respectively. The selected icons and words then populate the in progress word board.
- To add from tags, the user can search the tag and select any and/or all of the items associated with that tag to add to the in progress board.
- When the word board is full, or if the user is finished adding before the word board is full, the user selects 'save.'
- The word board is then saved as an image format and is saved in one of the 'Dictionary Board' slots under the 'Basic Boards' menu.

## 5. Medical
![Medical](https://github/pickwickian/orange-banana/Medical.png)
The Medical sub-menu has 4 sub-sections.
1. Issue: survey style screen to allow a patient to more quickly summarize their acute medical complaint and communicate it to a healthcare team member
1. Medical words: a basic board with medical-centered vocabulary
1. Facility words: a basic board for in-facility vocabulary about needs and treatment
1. Medical history: saved pertinent patient data

### Issue
This is a series of 3 screens. The user or their aide selects options on each screen (the options are either multiple check select or radio button-1 option). At the end of the 3 screens, the user selects 'done.' At this point, the app will display 1 summary page with only the information the user selected. This single summary screen stays saved until the user clears it, even if the user navigates to another section of the app and then navigates back to this section.

The three screens are in sequence as follows:
1. An anatomy diagram where the patient can touch or indicate the area that they want to communicate about and mark the diagram with an 'X'. Next to the diagram, there is a radio button style survey so the user can select the type of issue they are having.
2. There are survey sections on this screen for duration and a validated pain scale.
3. This screen has a list of associated symptom descriptors and the user can select the words that describe their current complaint.

If the user clears the summary screen, this section resets to show issue screen #1 without any selections yet made.

### Medical Words
When the medical words sub-section is selected, the app opens a screen that is a built in digital copy of the standard medical word board used in the hospital and acute care settings. 

### Facility Words
When the facility words sub-section is selected, the app opens a screen that is a built in digital copy of a word board used to communicate with nursing and facility aides about the environment, bed positioning, and bodily needs.

### Health History
![Health History](https://github/pickwickian/orange-banana/History.png)
This screen is filled in by the user or the aide using a free type box or interacting with the survey options.
