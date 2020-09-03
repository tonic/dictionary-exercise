# iOS Dictionary Exercise

Please create an iOS application that can parse the provided dictionary files. This exercise should take approximately 1&ndash;2 hours, and is not expected to be perfect. Most importantly, it should demonstrate your skill set, and give us a better idea of how you approach problems and construct solutions.

Feel free to use any resources that you would normally have at your disposal (Google, Stack Overflow, etc.), and do not hesitate to [contact us](mailto:developer@hellotonic.com) if you have any questions.

## The Dataset
* `just_a_dictionary.json` - a sorted JSON array of just the words in the dictionary starting with the letter **A**
* `dictionary.json`  a JSON array of objects representing all the words in the dictionary

Only a final app using the full `dictionary.json` file is necessary. The `just_a_dictionary.json` file is useful to prototype with.

## Minimum Requirements

##### Technical

There are no specific requirements about how you build the app. At a minimum, however, your application should fulfill the following:

- [ ] Include some relevant unit tests

##### Functional

At a minimum, your application should fulfill the following requirements:

- [ ] Show a list of words alphabetically sorted, and broken into sections by first letter
- [ ] Clicking on a word should show a detailed view containing:
  - [ ] The word in `20pt` system bold font
  - [ ] The definition in `16pt` system font
  - [ ] A section that contains the related words
  - [ ] A section that contains the anagrams in the dictionary of the selected word. An anagram is another word in the dictionary formed by rearranging the letters of another. For instance, CINEMA and ICEMAN are anagrams.
  - [ ] Each word in the related/anagram sections should be selectable and go to that word's detail screen

## Submission Guidelines

Please create a new repository on GitHub and send us a link. Do not fork this repository. Alternatively, you may send us an archive by [email](mailto:developer@hellotonic.com).