# Moving from Section 508 to WCAG 2.0 AA
Comparing Section 508 to WCAG 2.0 AA


|Proposed (WCAG 2.0 Success Criteria|Existing 508 Corresponding Provision|Summary|What would Change|Comment|
|--- |--- |--- |--- |--- |
|[1.1.1 Non-text Content](https://www.w3.org/TR/UNDERSTANDING-WCAG20/text-equiv-all.html) [A]|[1194.22a](https://section508.gov/content/quick-reference-guide#1194.22a)|Provides for text alternatives of images and other non-text content, including user interface components|Substantially Equivalent|WCAG 2.0 provides additional detail for categories of non-text content (Controls/Input, Time-Based Media, Test, Sensory, CAPTCHA, Decoration/Formatting/Invisible).|
|[1.2.1 Prerecorded Audio-only and Video-only](https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-av-only-alt.html) [A]|[1194.22a](https://section508.gov/content/quick-reference-guide#1194.22a)|Provides that prerecorded audio is available in a visible format and that silent animations are available in an audible format. |Substantially Equivalent| [WCAG 2.0 1.2.1](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-av-only-alt).|
|1.2.2 Captions (Prerecorded) [A]|[1194.22b](https://section508.gov/content/quick-reference-guide#1194.22b) & [.24c](https://section508.gov/content/quick-reference-guide#1194.24c)|Provides for synchronized captioning of prerecorded video and multimedia.|Substantially Equivalent|Proposed standard distinguishes between live and prerecorded media. [WCAG 2.0 1.2.2](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-captions).|
|1.2.3 Audio Description or Media Alternative (Prerecorded) [A]|[1194.22b](https://section508.gov/content/quick-reference-guide#1194.22b) & [.24d](https://section508.gov/content/quick-reference-guide#1194.24d)|Provides for audio description of prerecorded video and multimedia |Substantially Equivalent| [WCAG 2.0 1.2.3](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-audio-desc)|
|1.2.4 Captions (Live) [AA]|[1194.22b](https://section508.gov/content/quick-reference-guide#1194.22b) & [.24c](https://section508.gov/content/quick-reference-guide#1194.24c)|Provides for captioning of live video and multimedia |Substantially Equivalent| [WCAG 2.0 1.2.4](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-real-time-captions)|
|1.2.5 Audio Description (Prerecorded) [AA]|[1194.22b](https://section508.gov/content/quick-reference-guide#1194.22b) & [.24d](https://section508.gov/content/quick-reference-guide#1194.24d)|Provides for audio description of live video and multimedia |Substantially Equivalent| [WCAG 2.0 1.2.5](https://www.w3.org/WAI/WCAG20/quickref/#qr-media-equiv-audio-desc-only)|
|1.2.6 Sign Language (Prerecorded) [AAA]|  |  |*New*||
|1.2.7 Extended Audio Description (Prerecorded) [AAA]|  |  |*New*||
|1.2.8 Media Alternative (Prerecorded) [AAA]|  |  |*New*||
|1.2.9 Audio-only (Live) [AAA]|  |  |*New*||
|[1.3.1 Information and Relationships](http://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-programmatic.html) [A]|[1194.22e](https://section508.gov/content/quick-reference-guide#1194.22e) through (h)|Provides that information, structure, and relationships conveyed visually are available to users of assistive technology. <br> Provides that semantic markup be used for headings, lists, emphasized or special text, and tabular data, including the association of data cells with their headers|Substantially Equivalent|Proposed standard is written broadly and is technology neutral, whereas existing standard is specific to HTML image maps and data tables.|
|1.3.2 Meaningful Sequence [A]||Provides for a reasonable and logical reading order  when using assistive technology|**New**||
|1.3.3 Sensory Characteristics [A]||Provides that instructions are not conveyed only through sound, shape, size, or visual orientation|**New**||
|[1.4.1 Use of Color](http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html) [A]|[1194.21i](https://section508.gov/content/quick-reference-guide#1194.21i) & [.22(c)](https://section508.gov/content/quick-reference-guide#1194.22c)|Provides that information and prompts are not conveyed only through color|Substantially Equivalent|No technical difference.|
|1.4.2 Audio Control [A]||Provides that there is a way to stop, pause, mute, or adjust volume with audio that plays automatically|**New**||
|1.4.3 Contrast (Minimum) [AA]||Provides for specified contrast between foreground and background of text and images of text|**New**||
|1.4.4 Resize Text [AA]||Provides tor content that remains readable and functional when the font size is doubled|**New**||
|1.4.5 Images of Text [AA]|[1194.21f](https://section508.gov/content/quick-reference-guide#1194.21f)|Provides for the use of text, as opposed to images of text|Substantially Equivalent|Proposed standard provides detail for two situations where images of text are permissible.|
|1.4.6 Contrast (Enhanced) [AAA]|  |  |*New*||
|1.4.7 Low or No Background Audio [AAA]|  |  |*New*||
|1.4.8 Visual Presentation [AAA]|  |  |*New*||
|1.4.9 Images of Text (No Exception) [AAA]|  |  |*New*||
|[2.1.1 Keyboard](http://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-keyboard-operable.html) [A]|[1194.21a](https://section508.gov/content/quick-reference-guide#1194.21a)|Provides for functionality when using only the keyboard interface|Substantially Equivalent|Proposed standard clarifies the requirement by emphasizing the method of input, rather than the nature of the output.|
|2.1.2 No Keyboard Trap [A]||Provides that the keyboard focus is not trapped when the keyboard is used for navigation|**New**||
|2.1.3 Keyboard (No Exception) [AAA]|  |  |*New*||
|[2.2.1 Timing Adjustable](http://www.w3.org/TR/UNDERSTANDING-WCAG20/time-limits-required-behaviors.html) [A]|[1194.22p](https://section508.gov/content/quick-reference-guide#1194.22p)|Provides for flexible time limits|Substantially Equivalent|Proposed standard provides additional options to the single approach specified in the existing provision (that the user “be alerted and given sufficient time to indicate more time is required”).|
|2.2.2 Pause, Stop, Hide [A]|[1194.21h](https://section508.gov/content/quick-reference-guide#1194.21h)|Provides for user control over moving, blinking, scrolling, and information that updates automatically|Substantially Equivalent|Proposed standard specifies options (pause, stop, hide, or control the frequency) instead of “displayable in at least one non-animated presentation mode”, and allows for when animation “is part of an activity where it is essential” (for example, data that is being updated in real time).|
|2.2.3 No Timing [AAA]|  |  |*New*||
|2.2.4 Interruptions [AAA]|  |  |*New*||
|2.2.5 Re-authenticating [AAA]|  |  |*New*||
|[2.3.1 Three Flashes or Below Threshold](http://www.w3.org/TR/UNDERSTANDING-WCAG20/seizure-does-not-violate.html) [A]|[1194.21k](https://section508.gov/content/quick-reference-guide#1194.21k) & [.22j](https://section508.gov/content/quick-reference-guide#1194.22j)|Provides that nothing flashes more than three times per second, unless the flash is very small and does not contain too much red|Substantially Equivalent|Proposed standard takes into consideration the size and hue of the flash.|
|2.3.2 Three Flashes [AAA]|  |  |*New*||
|[2.4.1 Bypass Blocks](http://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-skip.html) [A]|[1194.22o](https://section508.gov/content/quick-reference-guide#1194.22o)|Provides for a skip navigation link or other means to bypass repetitive content|Substantially Equivalent|Proposed standard uses the phrase “blocks of content that are repeated” instead of just “repetitive navigation links”.|
|2.4.2 Page Title [A]|[1194.22i](https://section508.gov/content/quick-reference-guide#1194.22i)|Provides for descriptive and informative page titles|Substantially Equivalent|Proposed standard is for all types of content instead of just HTML frames.|
|2.4.3 Focus Order [A]||Provides for a keyboard-oriented navigation order that is reasonable and logical Provides that links, form elements, and other user interface controls and components have a reasonable and logical navigation order|**New**||
|2.4.4 Link Purpose (In Context) [A]||Provides that the purpose of any link is understandable from its text or context|**New**||
|2.4.5 Multiple Ways  [AA]||Provides for two or more means to locate content|**New**||
|2.4.6 Headings and Labels [AA]||Provides that headings and labels are descriptive|**New**||
|2.4.7 Focus Visible [AA]|[1194.21c](https://section508.gov/content/quick-reference-guide#1194.21c)|Provides that the keyboard focus is visually apparent when using the keyboard to navigate|Substantially Equivalent|Proposed standard uses the phrase “indicator is visible” instead of “well-defined on-screen indication”.|
|2.4.8 Location [AAA]|  |  |*New*||
|2.4.9 Link Purpose (Link Only) [AAA]|  |  |*New*||
|2.4.10 Section Headings [AAA]|  |  |*New*||
|[3.1.1 Language of Page](http://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-doc-lang-id.html) [A]||Provides that the default language of content is exposed  to assistive technology|**New**||
|3.1.2 Language of Parts [AA]||Provides that changes in language are exposed to assistive technology|**New**||
|3.1.3 Unusual Words [AAA]|  |  |*New*||
|3.1.4 Abbreviations [AAA]|  |  |*New*||
|3.1.5 Reading Level [AAA]|  |  |*New*||
|3.1.6 Pronunciation [AAA]|  |  |*New*||
|[3.2.1 On Focus](https://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-receive-focus.html) [A]|[1194.21l](https://section508.gov/content/quick-reference-guide#1194.21l) & [.22n](https://section508.gov/content/quick-reference-guide#1194.22n)|Provides that user interface components do not initiate a change of context when receiving focus|Substantially Equivalent|Proposed standard is explicit instead of having the requirement implicit in that “the form shall allow people using assistive technology to access the information, field elements, and functionality required for completion and submission of the form, including all directions and cues.”|
|3.2.2 On Input [A]|[1194.21l](https://section508.gov/content/quick-reference-guide#1194.21l) & [.22n](https://section508.gov/content/quick-reference-guide#1194.22n)|Provides that changing the setting of user interface components does not automatically cause a change of context|Substantially Equivalent||
|3.2.3 Consistent Navigation [AA]||Provides that repeated navigational components occur in the same relative order each time they are encountered|**New**||
|3.2.4 Consistent Identification [AA]|[1194.21e](https://section508.gov/content/quick-reference-guide#1194.21e)|Provides that components having the same functionality are identified consistently|Substantially Equivalent|Proposed standard is for all types of content instead of just “bitmap images”.|
|3.2.5 Change on Request [AAA]|  |  |*New*||
|[3.3.1 Error Identification](http://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-identified.html) [A]|[1194.21l](https://section508.gov/content/quick-reference-guide#1194.21l) & [.22n](https://section508.gov/content/quick-reference-guide#1194.22n)|Provides that automatically detected input errors are identified and described in text to the user|Substantially Equivalent|Proposed standard is explicit instead of having the requirement implicit in that “the form shall allow people using assistive technology to access the information, field elements, and functionality required for completion and submission of the form, including all directions and cues.”|
|3.3.2 Labels or Instructions [A]|[1194.21l](https://section508.gov/content/quick-reference-guide#1194.21l) & [.22n](https://section508.gov/content/quick-reference-guide#1194.22n)|Provides for labels or instructions when content requires user input|
|3.3.3 Error Suggestion [AA]||Provides that the system makes suggestions for correction when input errors are automatically detected and suggestions are available|**New**||
|3.3.4 Error Prevention (Legal, Financial, Data) [AA]||Provides that when legal, financial, or test data can be changed or deleted the changes or deletions can be reversed, verified, or confirmed|**New**||
|3.3.5 Help [AAA]|  |  |*New*||
|3.3.6 Error Prevention (All) [AAA]|  |  |*New*||
|[4.1.1 Parsing](http://www.w3.org/TR/UNDERSTANDING-WCAG20/ensure-compat-parses.html) [A]||Provides that significant HTML/XHTML validation and parsing errors in source code are avoided|**New**||
|4.1.2 Name, Role, Value [A]|[1194.21d](https://section508.gov/content/quick-reference-guide#1194.21d)|Provides that sufficient information (including identity, operation, and state) about user interface components is available to assistive technology|Substantially Equivalent|Proposed standard uses the phrase “programmatically determined” instead of “available to assistive technology”.|
