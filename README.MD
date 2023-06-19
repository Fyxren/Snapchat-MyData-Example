<h1 align="center">👻 Snapchat MyData Example</h1> 
<p align="center">An example of the json files you will receive when you request your data from <a href="https://accounts.snapchat.com/accounts/downloadmydata">Snapchat</a>.</p>

<br/>

I couldn't really find anything which documented the files Snapchat gives, so I created this repo. While it isn't quite a documentation, I feel like it does give a general idea of what everything could be. Unfortunately, there is still quite a bit unknown. These parts have been marked with `// UNKNOWN` in the files. All contributions to add & update data will be appriciated.

## 📃 The data files
All the files are in `/data` and are `.md` files. These are structured as followed:
### Info
**Description:** A short description of what the file contains\
**Status:** The status of the example (_self-explanatory, but see [`#Status Legend`](https://github.com/Fyxren/Snapchat-MyData-Example#-status-legend) for more info_)\
**Last Updated:** The date when the file was last updated, to know how up-to-date (_or outdated_) the example is.

### Data
```json
{
    // The actual data
}
```

## ❤️ Contributing
If you want to contribute, thank you! There is still quite a bit of data missing. If you've requested your data from Snapchat ([link ↗](https://accounts.snapchat.com/accounts/downloadmydata)) and noticed that you have something in your file which isn't in this repo, or has changed, feel free to add/update it.

Please keep these in mind:
- **Description:** Check if the description is still applicable, please update it when needed.
- **Status:** When needed, update the status (_see [#Status Legend](https://github.com/Fyxren/Snapchat-MyData-Example#-status-legend)_).
- **Last Updated:** Update the date to the date of the commit in this format: `January 1st, 2022`.

## 📞 Contact
If you need to contact me, just shoot me a message on Discord: [fyxren](https://discord.com/users/462914535351779328).\
Feel free to star the repo if you like it ⭐

<a href="https://discord.com/users/462914535351779328">
    <img src="https://lanyard.cnrad.dev/api/462914535351779328">
</a>

---

## ❔ Status Legend
| **Status**    | **Description**                                                                                   |
|---------------|---------------------------------------------------------------------------------------------------|
| Complete      | The file is finished.                                                                             |
| Semi Complete | The file is finished, but it feels like something could appear if Snapchat knows a certain thing. |
| Incomplete    | There is some data missing.                                                                       |
| Unknown       | There is basically no info.                                                                       |
