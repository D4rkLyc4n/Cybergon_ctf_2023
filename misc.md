### Write Up for Cybergon Misc by  *N00b_ScRiptKidS*

## Discord
**it say "Do not break the rules and forget to join discord."**
>I click that link mentioned in question and i read some texts and i found the flag.

## Move Move
**it say "Well known file transfer software product is attacked by a ransomware group. 
Do you know RAT name that used by this group for C2 ?"**
>So i start research like which RAT is used by Clop when attacking moveit and i found flag in cisa.gov site

## Storm Zero Five Five Eight
**The strom hit Exchange Online and got unauthorized email access using OWA. What key did the strom use for the access ?**
>I research about strom(storm 0558) hit and i found the clue for flag bcz i saw MSA key in every blog or news site about this storm. here ref: (https://www.wiz.io/blog/storm-0558-compromised-microsoft-key-enables-authentication-of-countless-micr)

## writeup "BMW For Sale"
>Question:
Do you heard any threat actor group luring viticims by attracting with BMW car advertisement as part of their campaign ? If you realised the campaign, I believed you can find the associated malicious url.
Answer:
Ok....First, from the question i use this line and search it on google "threat actor group luring viticims by attracting with BMW car advertisement as part of their campaign", then i found this group is APT29 but we don't see any malicious link.
So... i used "APT29" group name for searching like this "apt29 BMW car advertisement malicious link"
then we got the link from linkedin blog 
link : hxxp://tinyurl.com/ysvxa66c

## Operation Ghost
>Question: 
What MITRE techinques used to make data obfuscation in the Operation Ghost ?
Answer:
I used to search all of the words from Question on google.
As a result, i got flag on "https://attack.mitre.org/techniques/T1001/002/" this website
There from right hand side ... Technique ID :T1001.002
we got flag id number.

## Backdoor
>Question:
Do you know the cyber espionage campaign used chinoxy backdoor ? In that campaign, threat actor used vbs to run remote commands.
Answer:
I used "Question" like this "what is the cyber espionage campaign used chinoxy backdoor"to search the campaign name.
the result we got the name of the campaign "Funnydream".
Then i used "Funnydream" to got the flag ,like this "In funnydream campaign threat actor used which vbs to run remote commands"
then we know the vbs file name "wmiexec. vbs"

## Find Me
>I downloaded given file.Then,I viewed this excel file with my default software.I got nothing.So,I searched online viewer and viewd with this file.
I saw flag in sheet 2 in right side.It is flag.
>used link : https://extendsclass.com/excel-viewer.html
>
>![Find me.](/img/photo_2023-08-24_19-30-42.jpg)

## Captured
**it say "Our intels captured some conversation between Mr.Yit and his friend. Do you find some useful information ?"**
>I downloaded a mp4 file and  decoded the DTMF tones and found a numbers.That is a Flag.
>i decoded DTMF in Here https://unframework.github.io/dtmf-detect/

## Help me
**How many languages can you speak ?**
>I downloaded given mp4 and i watch it and notify that is look like morse code.So i go to audio to morse website adnd paste it and got
>a morse code and translate to text
>used site :
>https://morsecode.world/international/decoder/audio-decoder-expert.

>https://databorder.com/transfer/morse-sound-receiver/
>![help me](/img/photo_2023-08-24_21-42-11.jpg)


## Wallet Address
>APT group used Whipser Gate to perfrom destructive operation. 
From this line, we need to know which group
perform?? So, a I search for this line on google like this "Which APT group used whisper gate to perform destructive operation".
Then i found DEV-0586 apt group.
One of the strategies is overwritting MBR to create fake ransom note. Can you find wallet address that used in that note ?
From this line, i search like this using their group name "Dev-0586 is overwriting MBR to create fake ramsom note" 
then i found this fake letter from microsoft.com
You should pay us $10k via bitcoin wallet 1AVNM68gj6PGPFcJuftKATa4WLnzg8fpfv 
....Tang Tang !!!! We found their wallet address.

## Feedback
**it say "Please give us some feedback for CYBERGON Capture The Flag 2023 !!!"**
>Click the link and submit the feedback and boom got the flag
