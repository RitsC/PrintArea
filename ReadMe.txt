This software is licensed under the MIT agreement. Please see license.txt for any additional requests.

Update 2.3.1

    - Important Changes:
        * In this version, the document standard is no longer set by the option 'strict'.
            To accomodate different standards, you can specify one of [strict, loose, html5] as the new 'standard' option.
        * HTML5 is the default standard for the doc type.

    - Notes:
        * For <link> elements, you MUST include the 'rel' attribute with a value of 'stylesheet'. Otherwise the stylesheet will not be included in the printed element.
        * New option : 'extraHead' this is a comma delimited string of additional elements that is added to the head of the printed document.
            An example of this might be: '<meta charset="utf-8" />,<meta http-equiv="X-UA-Compatible" content="IE=edge"/>'
