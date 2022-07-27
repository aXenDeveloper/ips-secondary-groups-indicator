# (aXen) Secondary Groups Indicator

The plugin show secondary groups on website in:

- Topics
- Hovercard
- Profile
- Search

Include with **Secondary Groups Icon** in 3.0.0 version.

## 🏷️ Requirements

- [IPS Community Suite: 4.5, 4.6, 4.7 version](https://invisioncommunity.com/)

## 🧰 Install

1. Go to: AdminCP -> System -> SITE FEATURES -> **Plugins**,  
   ![Select Plugin](https://files.axendev.net/github/plugins/admincp_select.png)
2. Click on the link **manual upload**,  
   ![Manual Upload](https://files.axendev.net/github/plugins/manual_upload.png)
3. Select file **.xml** from packet and click install button

## 🛠️ Update

1. Go to: AdminCP -> System -> SITE FEATURES -> **Plugins**,  
   ![Select Plugin](https://files.axendev.net/github/plugins/admincp_select.png)
2. Search plugin and click **Upload a new version**,  
   ![Upload a new version](https://files.axendev.net/github/plugins/new_version_upload.png)
3. Select file **.xml** from packet and click install button.

# 🔧 Templates for pHTML files

From version **4.0.0**, special templates have been made available for developers of custom themes.

### Profile

- @param $member - \IPS\Member
- @param $showTitle - Show title widget? _(Default: true)_

```
{template="aXenProfileSecondaryGroups" group="plugins" location="global" app="core" params="$member, true"}
```

### Hovercard

- @param $member - \IPS\Member

```
{template="aXenHovercardSecondaryGroups" group="plugins" location="global" app="core" params="$member"}
```

### Search

- @param $member - \IPS\Member

```
{template="aXenSearchSecondaryGroups" group="plugins" location="global" app="core" params="$member"}
```

### Topics

- @param $comment - \IPS\Member author

```
{template="aXenTopicsSecondaryGroups" group="plugins" location="global" app="core" params="$comment"}
```

## 📷 Graphics

![1](https://github.com/aXenDeveloper/ips-secondary-groups-indicator/blob/master/1.png?raw=true)
![2](https://github.com/aXenDeveloper/ips-secondary-groups-indicator/blob/master/2.png?raw=true)
![3](https://github.com/aXenDeveloper/ips-secondary-groups-indicator/blob/master/3.png?raw=true)
![4](https://github.com/aXenDeveloper/ips-secondary-groups-indicator/blob/master/4.png?raw=true)
![5](https://github.com/aXenDeveloper/ips-secondary-groups-indicator/blob/master/5.png?raw=true)
![6](https://github.com/aXenDeveloper/ips-secondary-groups-indicator/blob/master/6.png?raw=true)
![7](https://github.com/aXenDeveloper/ips-secondary-groups-indicator/blob/master/7.png?raw=true)

## 🔌 Download from other sources

- [invisioncommunity.com](https://invisioncommunity.com/files/file/8760-axen-secondary-groups-indicator/),
- [invisionize.pl](https://forum.invisionize.pl/files/file/772-axen-secondary-groups-indicator/)

_The resources from the links above are updated on an ongoing basis if the administration approves the file._
