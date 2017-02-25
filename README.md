# Moving from Section 508 to WCAG 2.0 AA
Comparing Section 508 to WCAG 2.0 AA


|Proposed (WCAG 2.0 Success Criteria|Existing 508 Corresponding Provision|Summary|What would Change|Comment|
|--- |--- |--- |--- |--- |
|1.1.1 Non-text Content [A]|1194.22(a)|Provides for text alternatives of images and other non-text content, including user interface components|Substantially Equivalent|WCAG 2.0 provides additional detail for categories of non-text content [WCAG 2.0 1.1.1](https://www.w3.org/WAI/WCAG20/quickref/#qr-text-equiv-all).|
|1.2.1 Prerecorded Audio-only and Video-only [A]|1194.22(a)|Provides that prerecorded audio is available in a visible format and that silent animations are available in an audible format. || [WCAG 2.0 1.2.1](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-av-only-alt).|
|1.2.2 Captions (Prerecorded) [A]|1194.22(b) and .24(c)|Provides for synchronized captioning of prerecorded video and multimedia.|Substantially Equivalent|Proposed standard distinguishes between live and prerecorded media. [WCAG 2.0 1.2.2](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-captions).|
|1.2.3 Audio Description or Media Alternative (Prerecorded) [A]|1194.22(b) and .24(d)|Provides for audio description of prerecorded video and multimedia || [WCAG 2.0 1.2.3](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-audio-desc)|
|1.2.4 Captions (Live) [AA]|1194.22(b) and .24(c)|Provides for captioning of live video and multimedia || [WCAG 2.0 1.2.4](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-real-time-captions)|
|1.2.5 Audio Description (Prerecorded) [AA]|1194.22(b) and .24(d)|Provides for audio description of live video and multimedia || [WCAG 2.0 1.2.5](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-audio-desc-only)|
|1.2.6 Sign Language (Prerecorded) [AAA]|  |  |  |  |
|1.2.7 Extended Audio Description (Prerecorded) [AAA]|  |  |  |  |
|1.2.8 Media Alternative (Prerecorded) [AAA]|  |  |  |  |
|1.2.9 Audio-only (Live) [AAA]|  |  |  |  |
|1.3.1 Information and Relationships [A]|1194.22(e) through (h)|Provides that information, structure, and relationships conveyed visually are available to users of assistive technology
Provides that semantic markup be used for headings, lists, emphasized or special text, and tabular data, including the association of data cells with their headers|Substantially Equivalent|Proposed standard is written broadly and is technology neutral, whereas existing standard is specific to HTML image maps and data tables.|
|1.3.2 Meaningful Sequence [A]|None|Provides for a reasonable and logical reading order  when using assistive technology|New||
|1.3.3 Sensory Characteristics [A]|None|Provides that instructions are not conveyed only through sound, shape, size, or visual orientation|New||
|1.4.1 Use of Color [A]|1194.21(i) and .22(c)|Provides that information and prompts are not conveyed only through color|Substantially Equivalent|No technical difference.|
|1.4.2 Audio Control [A]|None|Provides that there is a way to stop, pause, mute, or adjust volume with audio that plays automatically|New||
|1.4.3 Contrast (Minimum) [AA]|None|Provides for specified contrast between foreground and background of text and images of text|New||
|1.4.4 Resize Text [AA]|None|Provides tor content that remains readable and functional when the font size is doubled|New||
|1.4.5 Images of Text [AA]|1194.21(f)|Provides for the use of text, as opposed to images of text|Substantially Equivalent|Proposed standard provides detail for two situations where images of text are permissible.|
|1.4.6 Contrast (Enhanced) [AAA]|  |  |  |  |
|1.4.7 Low or No Background Audio [AAA]|  |  |  |  |
|1.4.8 Visual Presentation [AAA]|  |  |  |  |
|1.4.9 Images of Text (No Exception) [AAA]|  |  |  |  |
|2.1.1 Keyboard [A]|1194.21(a)|Provides for functionality when using only the keyboard interface|Substantially Equivalent|Proposed standard clarifies the requirement by emphasizing the method of input, rather than the nature of the output.|
|2.1.2 No Keyboard Trap [A]|None|Provides that the keyboard focus is not trapped when the keyboard is used for navigation|New||
|2.1.3 Keyboard (No Exception) [AAA]|  |  |  |  |
|2.2.1 Timing Adjustable [A]|1194.22(p)|Provides for flexible time limits|Substantially Equivalent|Proposed standard provides additional options to the single approach specified in the existing provision (that the user “be alerted and given sufficient time to indicate more time is required”).|
|2.2.2 Pause, Stop, Hide [A]|1194.21(h)|Provides for user control over moving, blinking, scrolling, and information that updates automatically|Substantially Equivalent|Proposed standard specifies options (pause, stop, hide, or control the frequency) instead of “displayable in at least one non-animated presentation mode”, and allows for when animation “is part of an activity where it is essential” (for example, data that is being updated in real time).|
|2.2.3 No Timing [AAA]|  |  |  |  |
|2.2.4 Interruptions [AAA]|  |  |  |  |
|2.2.5 Re-authenticating [AAA]|  |  |  |  |
|2.3.1 Three Flashes or Below Threshold [A]|1194.21(k) and .22(j)|Provides that nothing flashes more than three times per second, unless the flash is very small and does not contain too much red|Substantially Equivalent|Proposed standard takes into consideration the size and hue of the flash.|
|2.3.2 Three Flashes [AAA]|  |  |  |  |
|2.4.1 Bypass Blocks [A]|1194.22(o)|Provides for a skip navigation link or other means to bypass repetitive content|Substantially Equivalent|Proposed standard uses the phrase “blocks of content that are repeated” instead of just “repetitive navigation links”.|
|2.4.2 Page Title [A]|1194.22(i)|Provides for descriptive and informative page titles|Substantially Equivalent|Proposed standard is for all types of content instead of just HTML frames.|
|2.4.3 Focus Order [A]|None|Provides for a keyboard-oriented navigation order that is reasonable and logical Provides that links, form elements, and other user interface controls and components have a reasonable and logical navigation order|New||
|2.4.4 Link Purpose (In Context) [A]|None|Provides that the purpose of any link is understandable from its text or context|New||
|2.4.5 Multiple Ways  [AA]|None|Provides for two or more means to locate content|New||
|2.4.6 Headings and Labels [AA]|None|Provides that headings and labels are descriptive|New||
|2.4.7 Focus Visible [AA]|1194.21(c)|Provides that the keyboard focus is visually apparent when using the keyboard to navigate|Substantially Equivalent|Proposed standard uses the phrase “indicator is visible” instead of “well-defined on-screen indication”.|
|2.4.8 Location [AAA]|  |  |  |  |
|2.4.9 Link Purpose (Link Only) [AAA]|  |  |  |  |
|2.4.10 Section Headings [AAA]|  |  |  |  |
|3.1.1 Language of Page [A]|None|Provides that the default language of content is exposed  to assistive technology|New||
|3.1.2 Language of Parts [AA]|None|Provides that changes in language are exposed to assistive technology|New||
|3.1.3 Unusual Words [AAA]|  |  |  |  |
|3.1.4 Abbreviations [AAA]|  |  |  |  |
|3.1.5 Reading Level [AAA]|  |  |  |  |
|3.1.6 Pronunciation [AAA]|  |  |  |  |
|3.2.1 On Focus [A]|1194.21(l) and .22(n)|Provides that user interface components do not initiate a change of context when receiving focus|Substantially Equivalent|Proposed standard is explicit instead of having the requirement implicit in that “the form shall allow people using assistive technology to access the information, field elements, and functionality required for completion and submission of the form, including all directions and cues.”|
|3.2.2 On Input [A]|1194.21(l) and .22(n)|Provides that changing the setting of user interface components does not automatically cause a change of context|
|3.2.3 Consistent Navigation [AA]|None|Provides that repeated navigational components occur in the same relative order each time they are encountered|New||
|3.2.4 Consistent Identification [AA]|1194.21(e)|Provides that components having the same functionality are identified consistently|Substantially Equivalent|Proposed standard is for all types of content instead of just “bitmap images”.|
|3.2.5 Change on Request [AAA]|  |  |  |  |
|3.3.1 Error Identification [A]|1194.21(l) and .22(n)|Provides that automatically detected input errors are identified and described in text to the user|Substantially Equivalent|Proposed standard is explicit instead of having the requirement implicit in that “the form shall allow people using assistive technology to access the information, field elements, and functionality required for completion and submission of the form, including all directions and cues.”|
|3.3.2 Labels or Instructions [A]|1194.21(l) and .22(n)|Provides for labels or instructions when content requires user input|
|3.3.3 Error Suggestion [AA]|None|Provides that the system makes suggestions for correction when input errors are automatically detected and suggestions are available|New||
|3.3.4 Error Prevention (Legal, Financial, Data) [AA]|None|Provides that when legal, financial, or test data can be changed or deleted the changes or deletions can be reversed, verified, or confirmed|New||
|3.3.5 Help [AAA]|  |  |  |  |
|3.3.6 Error Prevention (All) [AAA]|  |  |  |  |
|4.1.1 Parsing [A]|None|Provides that significant HTML/XHTML validation and parsing errors in source code are avoided|New||
|4.1.2 Name, Role, Value [A]|1194.21(d)|Provides that sufficient information (including identity, operation, and state) about user interface components is available to assistive technology|Substantially Equivalent|Proposed standard uses the phrase “programmatically determined” instead of “available to assistive technology”.|
