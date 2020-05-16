# Silicon_Labs_FT8_Tranceiver
Copyright (C) 2020, Charles Hill

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

Please use this software at your own risk.

Project Motivation, Attribution and Other Thoughts, May 2020
I have had some success in executing SDR projects using STM32 Discovery Boards which combine a 32 bit processor with a graphic touch screen display. These boards make for a compact stand alone QRP transceiver. My past projects made use of IQ DSP processing to integrate the Discovery boards with popular SDR radios such as the SoftRock RxTx  and UHFSDR transceivers.
Kees Talen  provoked me to do an FT8 project. I tried several times with NIL results. Then I came across the work done by Karlis Goba which you may review on this website: https://github.com/kgoba/ft8_lib . Karlis is a ham, YL3JG.
And, I decided to port my previous FT8 work over to the STM769 Disco board which has a lot more RAM than the STM746 Board. ShaZam  I finally got the FT8 stuff to work! Not only does iit work, it works well due to the great work done by Karlis. I have had several email exchanges with Karlis and he has been most helpful and supportive in my effort to produce another DSP project.
One of my colleagues, Jim Reagan (W0CH)L, shared with me an interesting Silicon Labs chip, the Si4753. Our local QRP Group, Austin QRP Club, are quite experienced with several Silicon Labs products to include the Si570 and Si5351. Silicon Labs headquarters are located in Austin and they have been supportive by allowing several of  their engineers to make technical presentations at our meetings.
I found the Si4753 to be most intriguing and well behaved. I made a crude lash up and fed the audio into one of my STM board projects and found it to really works well. So, I decided to build a transceiver for FT8 which uses the Si4735 for receive and the Si5351 for generating the FT8 signal directly at the chosen operating frequency. Hence the name for my project, Silicon Laboratories FT8 Transceiver.
At, present the operating mode of the application is quite limited. However, as I learn more about FT8 operations and experiment with the code I may add additional operation  features.






