# qT3: An app for the algorithmic deduction of Arabic verbs. 

## Summary

We implemented an iOS app where a user can enter an
Arabic verb in the state in which they found it: with no
short vowels and with any prefixes and suffixes attached. In turn, they will recieve a page of information, including the root, form, and linguistic features such as tense, mood, person, and number.

See the final report PDF for a full description of how our app works, including introductory explanations into the patterns of Arabic verbs.

### The name comes from ق ط ع (q T 3 in Arabizi), the Arabic root related to cutting. This root might be found in more complex declensions and conjugations to become different words, also related to our app: 
- **piece**
- **division**
- **syllable**
- **section**
- **to deduce**
- **to separate**
- **to slice**
- **many more!**

### Taking any of these conjugations in Arabic and inputting them into our app will return the root ق ط ع (q T 3) with accompanying information.

This app is a project created by Mercy Smith and Sabrina Templeton for CS 701. The back-end was created by Mercy Smith; the front-end was created by Sabrina Templeton; the team collaborated to produce the graphics and documentation. 

## Motivation
We were inspired by the fact that Arabic has predictable
patterns that lend itself to algorithmic deduction. As Arabic
students ourselves, we know that many resources require a
pre existing knowledge of Arabic to use. To look up a word
in an Arabic dictionary, a user must parse a given word into
a more basic form, ignore prefixes and suffixes, and identify
the root, a three letter combination that is associated with
a general core meaning. This can be difficult, especially for
beginning Arabic learners, and this difficulty only increases
with complex conjugations. Other existing technologies,
such as Google Translate, provide no information other than
a rough and oft inaccurate translation. Our app fills this gap in exisiting resources, offering an application for students to be able to input a word and get the information that is most helpful to their learning and understanding of the word, and providing them the root which allows them to properly look up the word if they choose. 

## Methods

Below is a diagram walking through the methods of our algorithm. 


![A flowchart](./images/qt3_flowchart.png)

## Technologies

Our algorithm was implemented in Python, hosted to an API with Flask which was then deployed to Heroku, which was then accessed by our iOS application, built in Swift. 

Note that the API currently does not function due to being deployed on Heroku, which removed the ability to deploy for free after the completion of this project.

## Screenshots

![An app screenshot of the input screen](./images/input_qt3.PNG)

![An app screenshot](./images/qT3_screenshot.PNG)


![Another app screenshot](./images/qT3_screenshot1.PNG)

## Tests

We tested our algorithm's correctness by implementing a test suite which includes 30 individual tests, each running multiple tests within them. 

## Status

Currently this project is in a development phase, and not ready for release on the App Store. Future work includes doing a more in-depth search for corner cases where our algorithm may fail, and improving the front-end.

#### References:

http://www.wseas.us/e-library/conferences/2011/Paris/ECC/ECC-66.pdf

https://www.naun.org/main/NAUN/ijmmas/20-805.pdf

http://www.iaeng.org/publication/WCE2013/WCE2013_pp1577-1582.pdf
