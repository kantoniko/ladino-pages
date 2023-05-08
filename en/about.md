# About Kantoniko, the corner of Ladino

## Goals

* Create a comprehensive dictionary of Ladino with translation to several languages using free and libre materials.
* Include examples and explanations on the use of the words in different locations.
* Provide tools for students of Ladino to make it easier to learn the language.

## How to use

* On the [home page](/) you will be able to see the translation of each word you type in.
* Under **Konfig** you can select which languages to display.
* Feel free to type in words in Ladino or any of the languages you selected.
    - If we recognize it as a word in Ladino we'll display it and its translations.
    - If it is not in our list of Ladino words we'll try to see if it is a word in one of the other languages. If it is we'll show the Ladino translation and its meanings.
* We don't try to understand the context or the full expression. It is still your job to decide which meaning of a word is relevant in the specific context.

## Source of the content

* This site is based on the dictionary created by Güler Orgun, Ricardo Portal, and Antonio Ruiz Tinoco.
* More specifically it is based on the Excel file from the [Ladinokomunita](https://ladinokomunita.groups.io/).
* It is created by the enourmous countribution of the members of the Ladinokomunita and espcially its moderators: Rachel Amado Bortnick (founder), Yehuda Hatsvi, Aldo Sevi, Guler Orgun, and Moshe Gormez.
* The [WhatsApp messages](/whatsapeando) were created by Albert Israel.
* The site was created and is being maintained by [Gabor Szabo](https://szabgab.com/). All errors are mine. Please report them via email or via the Git repositories below so I can fix them.
* Many words and most of the categorizations are based on the posters of dr. Aldo Sevi of [Los Ladinadores](https://www.facebook.com/groups/ladinadores) in Facebook.

## Source and License

* The source code of the web application can be found [here](https://github.com/kantoniko/ladino-diksionaryo-code/).
* The license of the source code is [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.en.html).
* The files containing the dictionary data can be found in the [Ladino diksionaryo data repository](https://github.com/kantoniko/ladino-diksionaryo-data).
* The license of the dictionary data is [CC BY-SA 4.0: Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).
* The sound files of words and examples can be found in the [Ladino diksionaryo sounds repository](https://github.com/kantoniko/ladino-diksionaryo-sounds/).
* The license of the sound files is [Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
* The files containing the WhatsApp messages can be found in the [Ladino estamos Whatsapeando repository](https://github.com/kantoniko/ladino-estamos-whatsapeando/).
* The license of the WhatsApp messages is [CC BY-NC-ND 4.0: Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/).

## How and what to contribute

* Adding more Ladino words and adding the different forms of the words.
* Adding sentences in Ladino that show the usage of the words in context. (Including the translations to one or more of our languages.)
* Adding sentences that explain the meaning of words. (Including translations as well.)
* Correcting the existing translations.
* Providing translations for the words where we are still missing the translations.

* [Contact Gabor Szabo](https://szabgab.com/contact.html) to discuss how could you get involved.
* Both the source code of the application and the source of all the content are in Git repositories listed above. If you know how those work you can contribute there.
* Ladino words and texts should be sent via the [Ladinokomunita](https://ladinokomunita.groups.io/)

## (Learning) Game

There is an experimental learning game that is accessible from the front page by clicking "Djugo" in the menu.
It will show random words in Ladino. Then you can try to guess the word. Pressing the "Reveal" button you will see the translations.
At this point you can confirm that you guessed correctly (OK) or that you failed to guess correctly (Fail). Based on a spaced repetion algorightm
you will see the same word appear again. If at this point you are not interested to learn this word you can click **Later** and it will be put back to the list of random words.

We maintain 2 lists. One for words that were last time marked as "OK" and one for the words marked as "Fail". (And we have the pool of all the words.)
When the user clickes OK or Failure the word is placed at the end of the appropriate queue.
if we have less than 10 words in the two lists, pick from the pool.
If there are 10 or more then: 50% pick the first one from the "failed", 25% pick the first from the "ok" list 25% pick from the general pool (till we have a word that is not in the other two lists).

## Contributors

* [szabgab](https://github.com/szabgab)
* [ms-kanto](https://github.com/ms-kanto[[O)
* [IsaBispoAbacherly](https://github.com/IsaBispoAbacherly)
* [aftahaporti](https://github.com/aftahaporti)
* [Yitzhak22](https://github.com/Yitzhak22)

