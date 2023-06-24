
# Text to Voıce Converter APP

This code represents a simple application that can output text as speech using the Web Speech API in your browser.

The code works with these steps:

A SpeechSynthesisUtterance object is created. This object contains speech settings and text.
A voices array is created to store the available voices.
VoiceSelect, a select HTML element, is selected.
The window.speechSynthesis.onvoiceschanged event is set. This event is triggered when sounds become available. The function inside assigns the available voices to the voices array and sets the speech.voice property to the first voice. It also populates the voiceSelect's options.
A change event listener is assigned to voiceSelect. This event is triggered when the user-selected voice changes. The function inside sets the speech.voice property to the selected voice.
Button, which is a button HTML element, is selected.
A click event listener is assigned to the button element. This event is triggered when the user clicks the button. The function inside takes the text from the textarea and assigns it to the speech.text property. Then the text is output as speech using the window.speechSynthesis.speak(speech) method.
This application provides a text box where the user can enter text and a list of sounds that can be selected. The user can hear the text with the selected voice by clicking the "Speak" button after entering the text.

Note: This code works with modern browsers that support Web Speech API in your browser.
## Kullanılan Teknolojiler

Javascript


## Live Demo


  
## SS

![1](https://github.com/Halismelih1/text-to-vo-ce-converter/assets/125564176/9923e65c-dec9-4288-a6b4-a4773f3dd0ac)
![2](https://github.com/Halismelih1/text-to-vo-ce-converter/assets/125564176/17fb7112-b85e-48b4-b318-9977c50adbe1)
