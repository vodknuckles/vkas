# VKAS - Vod K'nuckles Archival System
---
## Introduction
The Vod K'nuckles Archival System (VKAS) is a set of archival, organizational, and preservative guidelines that spans many different subjects and media types. In this instance, the focus will be on modifications (mods) to video games. These will mostly be tailored to Bethesda games as they are very mod friendly.

These guidelines will cover a range of topics from mod storage to preservation, porting, and more.

---
## Getting Started
Firstly and foremostly, you'll need to meet a few prerequisites in order to start backing up your mods.

1. A copy of the game(s) you'll be modding
	1. Legit or not, it shouldn't matter as long as it's playable
2. An account for the websites that require one for downloading mods
	1. [Nexus Mods](https://www.nexusmods.com/) (Nexus, NM) will be the site for the vast majority of your mods
	2. Nexus accounts are free and easy to create
3. Somewhere to store the mod archives and their folder structure
	1. I like to use a NAS, but you can use any storage solution

Once these conditions are met, continue reading and you'll learn how your folders should be structured.

---
## Basic Outline
The basic steps to archiving a mod are as follows:

1. Create and name a mod folder in an appropriate category folder
	1. See the section titled **Folder Structures**
2. Download the mod page
	1. See the section titled **Storing Mods (Part 1)**
3. Download the mod file(s)
	1. See the section titled **Storing Mods (Part 2)**
4. Create an index of requirements
	1. See the section titled **Requirements, Notes, and Instructions**
5. Move all those files into the mod folder from Step 1

---
## Folder Structures
As with all of my media, it is stored in a parent directory which then contains different child directories. An example of how I would organize a mod folder would be as follows:

`X:\games\mods\Game Title\Category\[1] Mod`

Let's break this down a bit.

Firstly, you'll want to centralize your mod files into one location. For my example, I put the `\mods` folder directly into my `\games` folder. You don't need them this close, feel free to store the either folder wherever.

> I do not store my mods in the same drive as my installed games. They are on an SSD while my mods are on my NAS.

Next, you'll want individual folders for each separate game you plan to store mods for. `\Game Title` would of course be replaced with a folder called `\Skyrim SE`, `\Fallout NV`, or `\Far Cry 3` just to name some of my favorites.

Inside of these game folders will nest your `\Category` folders. There is no unified, agreed upon category set. Nexus Mods has their own (it's also different for each game), [Mod Organizer](https://github.com/ModOrganizer2/modorganizer) uses their own, and of course I have my own as well.

Lastly, inside the `\Category` folders will be your mod folders, `\[1] Mod` in the example. These folders will *generally* have an ID in brackets, followed by a title. If the mod is often abbreviated or referenced to as an acronym, you can add it to the name after the brackets:

`\[21497] Mod Configuration Menu`

becomes

`\[21497] MCM - Mod Configuration Menu`

I recommend not including useless indicators such as what game the mod is for, author names[^1], or version numbers. Naming mod folders this way puts the mods in sequential, release order as Nexus Mods' ID system is iterative. Below are some examples of mod folders with the extraneous info removed:

`\[133] The Eyes Of Beauty Fallout Edition`

becomes

`\[133] The Eyes Of Beauty`

`\[8126] Ponytail Hairstyles by Azar v2.5a`

becomes

`\[8126] Ponytail Hairstyles`

[^1]: This might be desired in some circumstances. I'll usually reserve author names for large groups of similar mods. EX:  "`- Mihail Monsters and Animals`"  goes on the end of creature mods by Mihail since they all belong to a single theme and there are *dozens* of them. Another method for large mod collections is to create another folder inside of a given `\Category` for a given mod author. I only recommend this for groups of three or more similar mods.

---
## Storing Mods (Part 1)
As technology improves and modding communities mature, more detailed, intensive, and technical mods begin to pop up. Some of these have very complex and / or involved installation processes and requirements. Usually, this information is present solely on the mod page on the Nexus.

This can be problematic for long term support as Nexus has a tendency to remove mods it doesn't like, not to mention when mod authors hide or delete their mods for any number of reasons. Archiving the mod page as well as the mod files can be the difference between having a fully functional mod that's been blacklisted and having a bunch of mixed up archives that you can't make heads or tails of.

### Saving Mod Pages
If you've ever tried to save a website using the *Right-Click > Save As*, you may remember that upon opening the .HTML file, the page was all messed up or it had some elements displayed incorrectly (or missing). Well a solution I have discovered is a simple Chromium extension that allows you to save a webpage as a single .HTML file. This in turn, allows you to see the mod page exactly how it was when it was saved.

This method is fast, easy, and quick (large pages may take up to 15 seconds or so, the vast majority are near instant). As a backup option, taking a full-page screenshot using a different browser extension will suffice, at the expense of selectable text and navigable links.

The extension I primarily use is (at the time of writing):

![Save Page WE](https://addons.mozilla.org/user-media/addon_icons/724/724283-64.png)

[Save Page WE](https://chrome.google.com/webstore/detail/save-page-we/dhhpefjklgkmgeafimnjhojgjamoafof) - Chrome, Brave, and other browsers that support Chrome extensions

[Save Page WE](https://addons.mozilla.org/en-US/firefox/addon/save-page-we/) - Firefox version

[GoFullPage](https://chrome.google.com/webstore/detail/gofullpage-full-page-scre/fdpohaocaechififmbbbbbknoalclacl) - Full Page Screen Capture, use as a last resort

#### For full .HTML extensions:
1. Install the extension
2. Visit a mod page and wait for it to fully load
	1. ex: https://www.nexusmods.com/fallout4/mods/4598
3. Click the extension icon **before doing anything else**
	1. this includes scrolling, clicking, etc.
	2. *Alt+A* is the keyboard shortcut for Save Page WE
4. Wait for the .HTML file to finish downloading

> Sometimes a mod will have a large number of parts or patches. In these cases I may also elect to save the *Files* tab of the page as well. I append "` - files`" at the end of the .HTML filename for these Files tab pages. So in the mod folder, there would be two pages.
> 
> For example:
> `Mod Page - Nexus Mods.html`
> `Mod Page - Nexus Mods - files.html`

#### For full page screenshots
The naming convention I've adopted (out of laziness) is the default name generated when I save an .HTML file. I would recommend following the same naming convention for full page screenshots as well.

The naming convention for Nexus looks like this, but without the brackets:

`[Mod Name] at [Game] Nexus - Mods and community.html`

Your screenshot could be named something like:

`Mod Configuration Menu at Fallout 4 Nexus - Mods and community.png`

### Missing Mod Pages
For the few mods that do get taken down before you have a chance to save a copy of the webpage, what are your options?

Well, my favorite is to check the [Internet Archive's Wayback Machine](https://web.archive.org/), this massive archive has snapshots of a lot of the more popular mod pages, but the integrity of the page layout, images, etc. may not have been properly stored. Most of the time the text is the most important part anyway, but it is nice to see the original page's images (if they're present).

*"Well what do I do if I don't know the original mod page URL?"*, I hear you ask.

Basically, if you know the mod ID and what game it belongs to, you can recreate this URL using this template:

`nexusmods.com/game/mods/modID`

`/game` - This should be replaced with the actual game of the mod you're searching for
	*FalloutNV*, *SkyrimSpecialEdition*, *Oblivion*, etc.
`/modID` - This will be the ID of the mod you're searching for
	*123*, *1234*, *12345*, etc.

Once you have the URL, bring it to the Wayback Machine, paste it in, and wait for it to finish searching.

If it found a snapshot:
	Great! Click a snapshot, when it finishes loading, save it as an .HTML file or screenshot it

If it didn't find a snapshot:
	Crap! Better luck next time. You're on your own.

---
## Storing Mods (Part 2)
After creating a mod folder and saving the mod page, you'll want to save the mod itself. Mods are incredibly diverse and are not a one-method-fits-all kind of deal. Mods tend to be single, self-contained archives, but not always. Some can be in many different parts with separate updates, patches, etc.

On the *Files* tab of a given Nexus mod page, there may be as many as four sections that files can be located in:

1. **Main Files** - The required, core mod files
	1. These are the files that add the functionality or fulfill the listed purpose of the mod
2. **Optional Files** - Not strictly necessary for mod functionality
	1. These files may add more functionality or enhance the mod in some way.
	2. These files could also be additional tools, tutorials, variants, etc.
3. **Miscellaneous Files** - Any other files uploaded by the author
	2. These files could also be additional tools, tutorials, variants, etc.
4. **Old Files** - Old mod versions
	1. Generally, these are older versions of the Main or Optional files and are best left alone.

It is very hard for me to give any advice regarding what files you should or shouldn't archive. I usually just download the files I need or think I could use in the future and move on. I'll go through an example mod to give you some idea of how I would do this.

I'll be using [CBBE - Caliente's Beautiful Bodies Enhancer](https://www.nexusmods.com/fallout4/mods/15) as it is popular and uses all four file categories. On the CBBE *Files* tab, the files (at the time of writing) are as follows:

1. **Main Files**
	1. *Caliente's Beautiful Bodies Enhancer - v2.6.3
2. **Optional Files**
	1. *CBBE Reduced (with dismemberment)*
3. **Miscellaneous Files**
	1. *Modder's Resource*
	2. *NeverNude Underwear Resource*
	3. *Texture Source and Options - v1.0*
4. **Old Files**
	1. *Old mod versions* 

**Main Files**
	1.1 Main mod file, I will download this
**Optional Files**
	2.1 Reduced complexity version of main mod compatible with dismemberment. Useful, but I'm not using any dismemberment mods, so I'll skip this file
**Miscellaneous Files**
	3.1 I don't plan to modify CBBE, pass
	3.2 I don't use NeverNude and don't need to modify it, pass
	3.3 ibid, 3.1
**Old Files**
	4.1 I don't need old versions of CBBE, pass

> Hopefully, that short demonstration showed how even though there may be a dozen files, you may only really need one. If you aren't sure where to start, read through the mod page's installation section if one is available. Else, check the *Posts* tab, Reddit, or YouTube for a tutorial.

---
## Requirements, Notes, and Instructions (New Method)
> The *Old Method* (detailed below) is now deprecated and I won't be expanding on it.
> 
> The *New Method* is being worked out now, I'll update this ReadMe when I have a good plan in place. More than likely, I will move to a large spreadsheet with all Bethesda games in one place.

---
## Requirements, Notes, and Instructions (Old Method)
> If you didn't read above, this section is deprecated and uses a method that is time consuming and tedious. Refer to the previous section for a better method... or continue reading.
> 
> I'm an author's note, not a cop.

```
Alright, you've made your folder structure, saved a few webpages, and downloaded some mods. I'm glad you've made it this far!

Lastly, some mods have dependencies that are required for the mod to function. These mods won't be a retexture or small fix, they'll generally have some scripting or they might base part of their functionality on a separately developed mod. This can be great and lead to some awesome projects, but more often it's a juggling act of trying to keep everything updated and playing nice.

For this problem, I've developed a template .txt file that I include inside of each mod folder where some required materials or other information is needed for smooth functionality. These requirements (req.) files (in their current implementation, I may move to a centralized or Markdown solution in the future) are simple .txt file that specifies any hard or soft requirements as well as any optional files, notes, or special instructions.

Below is a short summary of the sections of a req. file:

[Hard Requirements]	; Strictly required, mod may crash or be unstable without these	

[Soft Requirements]	; Not strictly necessary, may be required for some features	

[Notes]	; Any comments, notes, or special instructions should go here

In a given req. file, I've decided to only include the populated sections. For example, if a mod had a hard requirement and some notes, I would omit the soft requirements section.

(The author abandoned this section without giving any examples)
```
