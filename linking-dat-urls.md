---

layout: home
title: "Linking everyone's dat urls"
permalink: "network-setup"

---


# [Home](/)<br>Network Interfacing

Linking Everyone&rsquo;s dat url to their profile.

<hr>


Please update the [sheet](https://docs.google.com/spreadsheets/d/1VTTNBRftvCj-_L-M8hwBZuwXps4wBGrrRB6rER0Kqzc/edit#gid=0) with the dat url you worked on the first week (add it to the *dat home url* column). You should view this url as your "index" or "home" url and continue developing it throughout the semester. 

This is the url that you&rsquo;ll use to post with throughout the semester, and it will be the url that people use to search for your posts as we build other interface variations. 

The main use for this is the `posts/` folder, as this is what others will be calling. if you want to expand/use multiple interfaces throughout the semester, feel free to make variations with different `html` pages.

## Instructions
- update the *dat home url* column on the class [spreadsheet](https://docs.google.com/spreadsheets/d/1VTTNBRftvCj-_L-M8hwBZuwXps4wBGrrRB6rER0Kqzc/edit#gid=0) with your most current dat url. 
- once everyone has updated their sheet, copy the urls into your `profile.json` file's `"user"` key.
- Find your `loadProfile()` function and update your javascript to load the user list `usersProfiles(userCounter, userList, centralListContainer)` inside the `loadProfile()` promise. 
- If you&rsquo;re able to load your list of profiles, begin to try loading their posts with `userAndTheirPosts(userCounter, userList, watchingContainer)`.


## Links
- class [spreadsheet](https://docs.google.com/spreadsheets/d/1VTTNBRftvCj-_L-M8hwBZuwXps4wBGrrRB6rER0Kqzc/edit#gid=0)
- [boilerplate](https://github.com/leigler/ni-boilerplate)
- [datArchive API Docs](https://beakerbrowser.com/docs/apis/dat)

