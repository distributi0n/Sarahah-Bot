# Sarahah-Bot
Heard of that Social Media site / app that allows you to receive anonymous "constructive" criticism? I made a bot for it. It's pretty simple to use and it has a fair amount of features. 

Many people will probably ask why I made this, I was really bored and it seemed so easy to do, I also got asked by some people on snapchat if it was possible and after viewing their source code its shocking how weak their security is.

## Question Shortcuts
* [account_name] => Username of your account (X.sarahah.com)
* [your_name] => Used if you just want to refer to yourself.
* [config_configkey] => This basically means you can get any config element, just name it after [config_ and end with ]
* [random_name]<br> => A random name, male or female doesn't matter.
* [random_name_girl]<br> => A random name, but strictly only a female name.
* [random_name_guy]<br> => A random name, but strictly only a male name.
* [random_name_opposite]<br> => A random name, for the gender opposite to yours.
* [random_surname]<br> => A random surname, with no strict gender filters.
* [random_surname_girl]<br> => A random surname, only female ones.
* [random_surname_guy]<br> => A random surname, only male ones.
* [random_surname_opposite]<br> => A random surname, opposite gender to yours.
* [random_number_min_max]<br> => Gives you a random number (min = minimum number, max = maximum number)
* [random_emoji_times]<br> => Used to release a random emoji, you can even add _times before ], example: [random_emoji_3]

## Emojis?
Hell yeah! I've added a file that KeyValuePair's certain words with emojis which can be found below. You can paste the emoji raw but that's just hard work keeping up with changing the emojis in 1 spot. I've added probably about 100 emojis, feel free to add more it really is super easy. Just visit the site and copy+paste into the KeyMapping file. http://getemoji.com/

## Emoji Key Mapping 
* [heart]
* [heart_black]
* [heart_yellow]
* [love_eyes]
* [kiss]
* [wink]
* [crying]
* [laughing]
* [thumbs]
* [thumbs_down]
* [devil]
* [devil_frowning]
* [angel]
* [ghost]
* [sick]
* [straight_face]
* [smile]
* [frown]
* [grin]
* [tounge_waggle]
<br>
Application comes with around 1,000 pre-made questions that I just read off other peoples posts. You can adapt it to suit your needs, just edit the questions file which is located in the "assets" directory of the exe location.<br><br>

I could of just sent a http POST request but they use token so I would rather take the quick option and just run an internal browser embedded into the application. This application isn't an app that you need to worry about speed anyway. If your questions are sent too fast it'll obviously look fake.<br>

Oh yeah, I've also added a setting for delay in the amount of time it takes to send a question and how long it waits between questions. That can also be modified and edited in the configuration file.
