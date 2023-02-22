# inmotion-app-translation
A repository for INMOTION APP translation.

## How to contribute
There are translations files for each language that you can edit. You can find the appropriate language by looking at the country identifier in the file name. So if you want to translate to German, you would look for the file de_DE.dart. In order to edit the file, either fork the repository and make the changes, or simply go to the file and click on the pencil icon to edit it directly (top right corner).

Make sure to add your translation between the two empty quotations marks. You can see an example of this by looking at the initial English translations.

When you're happy with your changes, open a pull request so they can be added. Please open pull requests often, so other people can see what has been done already! Don't forget to include your name / username that you want to have added to the contributors.md file. The people in this file will be added to the list of contributors that will be available in the app!

## Comments
Throughout the translations file, you will see some comments (preceded with //). These are there to give you an indication where the translation is used. That way, if you aren't sure about a translation, you can check if it would fit by going to the right part in the app. These comments should not be translated, as they are only used to give context to the rest of the words.

## Variables
Sometimes you will run into constructs such as %s or %d. These are variables and should be included in your translation! Later on, the app will substitute these constructs by the appropriate words. An example would be this: "%dmin ago" would become "3min ago" in the app.

## Additional info

### Unsure about translation?
If you are unsure about a translation, it is better to leave it blank and open an issue to discuss about it with other people. Just list the word(s) you are uncertain of (and in the require language) and other people might be able to help you out with it!

### Missing your language?
If your language isn't added yet, you can just copy the en_US.dart file, then modify the file name to lang_region.dart, and then translate it. So if you want to translate to German, you would copy the en_US.dart file and then rename to de_DE.dart, then you could begain your translation.

### Better translation for already translated part?
If you come across part of the app that you would translate different: you're free to edit existing translations. This also holds for the original English translations: if you believe you have a better way to word something, go ahead!
