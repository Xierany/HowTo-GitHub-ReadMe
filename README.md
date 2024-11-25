<picture>
  <img src="https://github.com/user-attachments/assets/1cabdd78-7551-4cfe-a172-e4f2fd94b448" width="70%" />
</picture>

### [Table of Contents](#table-of-contents)    
[Readme](#-readme)    
[Images](#-images)    
[Text](#-text)    
[Stats](#-stats)    
[Contact](#-contact)    

<br> Ever wanted to fancy up your GitHub profile but have no idea how? Don't wanna bother figuring it out? <br>
In this I'll give you guides and resources to get started, with instructions and examples. <br> <br>

If you want to check out how my GitHub profile looks, you can check it out <a href="https://github.com/HEE082024KH"> 
  <img src="https://img.shields.io/badge/here-121b6e" alt="My GitHub Profile"> 
</a> <br> <br>

Just want the premade templates and be done? Try these: <br>
[![GPRM](https://img.shields.io/badge/GPRM-blue)](https://gprm.itsvg.in/) &nbsp;
[![Readme Generator](https://img.shields.io/badge/Rahuldkjain-c72828)](https://rahuldkjain.github.io/gh-profile-readme-generator/) &nbsp;
[![Readme Gen Vercel](https://img.shields.io/badge/Vercel-green)](https://readme-gen.vercel.app/app) &nbsp;
[![Profilinator](https://img.shields.io/badge/Profilinator-yellow)](https://profilinator.rishav.dev/) &nbsp;
[![ReadMe Generator](https://img.shields.io/badge/MauroDeSouza-purple)](https://profile-readme-generator.com/) &nbsp;

---

### 📁 Readme
To start you need to create a Readme file.
1. In the upper-right corner of any GitHub page, select ```+``` , then click New repository.
2. Make the Repository name the same as your profile name, this makes the Readme file display on your profile.
3. Select Public.
4. Select "Add a README file" under "Initialize this repository with".
5. Click Create repository. <br> <br>

- Then go to either your front page or your repositories page, to edit the Readme file. <br> <br>

##### Wonder how I get this line across the screen? Just type ```---``` and it will fill the whole width. You can also use ```***``` and ```_ _ _```. 

---

### 🖼 Images
To start you might want to have a header or an image. You can get a customized header image like I used above <a href="https://reheader.glitch.me/"> 
  <img src="https://img.shields.io/badge/here-168037" alt="Header template"> 
</a> <br>
If you want more info you can also check out the full GitHub repo <a href="https://github.com/khalby786/REHeader?tab=readme-ov-file"> 
  <img src="https://img.shields.io/badge/here-f2b527" alt="Khalby786 Header Guide"> 
</a> <br> <br>

You can use any image you please, as long as you have the <ins>URL-link</ins>. Just put the link inside the ```""``` in this element ```<img src=""/>```.
I use this structure to add icons for my tools and languages. <br> <br>

[![Devicon](https://img.shields.io/badge/Devicons-558d6c)](https://github.com/devicons/devicon/tree/master/icons) has a repo full of icons you can use. Use the URL with the element mentioned above, and you'll have a sleek tech stack in no time. If you have local images you want to use, you need to upload them to GitHub or any other file hosting website, and link to them. <br> <br>

If you want to make the image unclickable, ie not redirect to the image when clicked, just surround the picture element with ```<picture>``` tags,
like this 
```<picture> <img src="URL-link"> </picture>```. 
This works on any picture, badge, gif and similar.

---

### 📑 Text
Notice how my headlines are bigger and bolder than the other text? You accomplish this by using ```#``` to ```######```, with ```#``` being the biggest. <br> <br>

A great way to make the text fresh and excicing is by adding icons, like these 💻 🤹. They are easy to get by just typing ```:``` and you will get a dropdown menu with options.
Some like to sort this section with bullet points, but it's up to you what you prefer. However, if you want to write a long summary it might just be best to put it on your LinkedIn,
as long as you remember to link it. *(more about that further down)*

Know how you can do ```---``` for a horisontal line? If you want a thinner line you can instead use the headlines ```##``` or ```#``` without adding text and it will look like below.

#

### 📊 Stats
Now on to the fun stuff. Anuraghazra has a massive guide with several different type of stats <a href="https://github.com/anuraghazra/github-readme-stats"> 
  <img src="https://img.shields.io/badge/here-brown" alt="Anuraghazra"> 
</a> <br>
This includes the stats card, language card and streak card, that I have on my profile. Most of these give you a <ins>URL-link</ins> for the API, and all you need to do is change the username to your own. Put this link in a ```<img src=""/>``` like mentioned above, and you're all set. <br>

<img src="https://github-readme-stats.vercel.app/api?username=hee082024kh&show_icons=true&border_color=787878&icon_color=d12e2e&title_color=d12e2e&text_color=8c8c8c&border_radius=10&bg_color=242424"  width="45%"/> <img src="https://github-readme-streak-stats.herokuapp.com?user=HEE082024KH&theme=dark&border_radius=10&exclude_days=Sun%2CSat&card_width=467&background=242424&ring=D12E2E&fire=D12E2E&stroke=D12E2E&border=787878&currStreakNum=8C8C8C&currStreakLabel=D12E2E&sideNums=8C8C8C&sideLabels=D12E2E&dates=8C8C8C&excludeDaysLabel=D12E2E"  width="45%"/>

##### Many stats cards use markdown to display, using a format that looks like this ```[![Name](Image-link)](Redirect-link)```. This works well most of the time, but offers less customizability than HTML. By using the tags I mentioned above you are able to add HTML parameters like this ```<img src="" width="50px"/>```. <br> <br>

It is possible to have different stats cards for light and dark mode, that automatically changes based on the users color scheme.
This is twice the work, and is mostly for those that want to make the design look how you want it to for every user.
Use the structure below and just fill in the ```""``` with the URL to your stats card.

```
  <source
    srcset=""
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset=""
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
    <img src="" />
```
<br>

The link for the trophy card, that I have on my profile, can be found <a href="https://github.com/ryo-ma/github-profile-trophy"> 
  <img src="https://img.shields.io/badge/here-gold" alt="Trophies card"> 
</a> <br>
**Do note that if you choose to exclude certain trophies from the image, it still maintains the full size as if all trophies were still there.* <br> <br>
<img src="https://github-profile-trophy.vercel.app/?username=hee082024kh&theme=chalk&no-frame=true" /> <br> <br>
The jokes card, that continuously generates new jokes, can be found <a href="https://github.com/ABSphreak/readme-jokes?tab=readme-ov-file"> 
  <img src="https://img.shields.io/badge/here-silver" alt="Jokes Card"> 
</a> <br> <br>
<img src="https://readme-jokes.vercel.app/api?&qColor=%23d12e2e&aColor=%238c8c8c&borderColor=%23787878&textColor=%23ffecd9&codeColor=2e41d1&bgColor=#7D2323" /> <br>
And the simple view counter I've used can be found <a href="https://github.com/antonkomarev/github-profile-views-counter"> 
  <img src="https://img.shields.io/badge/here-red" alt="Jokes Card"> 
</a> <br> <br>
<img src="https://komarev.com/ghpvc/?username=your-github-HEE082024KH&color=7D2323" />

---

### 📫 Contact
To add your contact links is as simple as using the the ```href``` element like this 
```
<a href="link-to-your-social-media-URL"> 
  <img src="link-to-image/button"> 
</a>
```
You can use this with any image, but if you want to use simple badges like <picture>![Shield.io](https://img.shields.io/badge/this-pink)</picture> you can just copy this link
```
https://img.shields.io/badge/text-color
```

Just replace the two elements at the end, where "text" is what the button says and "color" is the color of the button. <br> You can also have a double badge <picture>![Shield.io](https://img.shields.io/badge/like-this-red)</picture> by just adding another text field. <br> <br> <br>
Check out [![Shield.io](https://img.shields.io/badge/Shields.io-93cb04)](https://shields.io/) for more information, if you want more options or want different types of badges. <br> <br>

To get a badge that redirects to an email, however, you need to add an ```href``` tag in addition to the ```img src```.
```
<a href="mailto:your-email">
<img src="https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white"></a>
```
Just replace ```your-email``` with your email and it should work. Notice the ```logo=gmail``` parameter? <br> You can replace it with many popular social media logos, by just typing the name. Try it out! <br>
**Make sure to check that the Gmail link redirects like it should, no point having a fancy badge that doesn't work.*

<a href="mailto:hee082024@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?&logo=gmail&logoColor=white" height="28px" alt="Gmail"></a> &nbsp;
<a href="https://www.linkedin.com/in/eirik-hellesen-035695305"><img src="https://img.shields.io/badge/LinkedIn-blue?&logo=linkedin&logoColor=white" height="28px"><a/> &nbsp;
<a href="https://discordapp.com/users/1274996964089528396"><img src="https://img.shields.io/badge/discord-5865F2?logo=discord&logoColor=white" height="28px"></a> <br>

To redirect your badge to your Discord user profile, just add this URL to the ```href``` element like this: <br>
```<a href="https://discordapp.com/users/Your-User-ID">```.
If you do not know how to find your user-ID, check out <a href="https://www.socialspyro.com/how-to-share-discord-profile-link/"> 
  <img src="https://img.shields.io/badge/this-5865F2" alt="Socialspyro"> 
