# _Google Tag Manager_

#### _GTM script tags, 02.14.18_

#### By _**Kaili Nishihira**_

## Description
_This is a collection of custom script tags I wrote for various clients of a digital marketing agency. The GTM custom HTML tags track specific user data triggered by events. Please see comments in the code for specifics._

## Setup/Installation Requirements
* _Create a [Google Analytics](https://analytics.google.com) account._
* _Create a [Google Tag Manager](https://tagmanager.google.com) account._
* _Link your GA account to your GTM account._
* _Copy and paste the GTM Container Code in the head of each page of your site._
* _Set up Custom Event Variables for Action, Category, Label and NonInteraction with the names eventInfo.nameOfVariable._
* _Set up a Custom Event Trigger, with an event named customEvent to fire on Custom Event - Label and does not equal Conversion._
* _Set up a Page View - DOM Ready trigger which fires on all DOM ready events._
* _Set up a Custom Event Universal Analytics GA tag to track events, add the Custom Event Category, Action, Label and NonInteraction variables and fire the tag with a Custom Event Trigger._
* _Create Custom HTML tags for your site and use the code as an example, replace the element's with own your site's elements. Most Custom HTML tags I created used the DOM Ready trigger._

## Technologies Used
* _jQuery_
* _[Google Tag Manager](https://tagmanager.google.com)_
* _[Google Analytics](https://analytics.google.com)_
* _[Omnibug](https://omnibug.io/) for debugging_
* _[Observe Point](https://www.observepoint.com) for debuggin_

## Known Bugs

_None._

## Support and contact details

_Contributions are always welcome! Please contact Kaili Nishihira at kailinishihira@gmail.com_


### License

Copyright (c) 2018 **_Kaili Nishihira_**
*Licensed under the [MIT License](https://opensource.org/licenses/MIT)*
