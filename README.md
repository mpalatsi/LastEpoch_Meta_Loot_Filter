# LastEpoch_Meta_Loot_Filter
Loot filter to identify high value items in the Merchant's Guild for Last Epoch

### Instructions on creating a Loot Filter to add to the master loot filter:

- Create an account on [LastEpochTools](https://www.lastepochtools.com/forum/)
- Click `Loot Filters` on the top menu bar
- Select `+ Create Loot Filter`
- Select `Create From Scratch`
- Fill out the form that appears, most of this is irrelevant as it's going to be added to a master loot filter. Just make sure you designate the filter as `Private`
- Create a rule by selecting `Add Rule`
- The naming convention of your Rule should adhere to the following format [Item Type][Tier] (ie. Helmet T7)
- Select `Add Condition`
- Use the drop-down menu and pick `Rarity` first, then add `Exalted`
- Add another condition for `Item Type`
- This select will be based on what Item Type you'd like to contribute to the master list
- Add another condition for `Affix`
- Select neon green and check the box `Emphasize`

  At this point your rule should look something like this:
  ![image](https://github.com/mpalatsi/LastEpoch_Meta_Loot_Filter/assets/2904198/9d8ead8c-8d1c-4f35-804c-7469e7d3e1f8)

----------------------

Now the fun starts, navigate to [Maxroll Corruption Tier List](https://maxroll.gg/last-epoch/tierlists/corruption-tier-list)

Starting at the top and working your way down select each build, find the item type you're building your rule for and review the exalted affix like so:
  
![image](https://github.com/mpalatsi/LastEpoch_Meta_Loot_Filter/assets/2904198/8d473719-b238-4c04-97cd-396d78315120)

> [!TIP]
> If the item is a legendary, hold `CTRL+ALT` to find the Tier 7 affix like so:

![image](https://github.com/mpalatsi/LastEpoch_Meta_Loot_Filter/assets/2904198/7a071da6-6777-47be-beea-cd7ce68e15f9)

----------------------

Now head over to the Merchant's Guild in-game and define your affix:

![image](https://github.com/mpalatsi/LastEpoch_Meta_Loot_Filter/assets/2904198/7e53a2e9-a195-4de2-a2bb-7a857cd09113)

Sort the list by `Gold: Low to High`, if the top 3 items are 50k+. You should proceed with creating a rule, otherwise, this affix can be ignored:

![image](https://github.com/mpalatsi/LastEpoch_Meta_Loot_Filter/assets/2904198/97481f4d-854c-4f88-9b5b-a4df9f3a4f6c)

-----------------------

Back in your filter builder on LastEpochTools, add the affix like so:

 > [!TIP]
 > You will need to checkmark `Advanced Options` to assign the desired Tier

![image](https://github.com/mpalatsi/LastEpoch_Meta_Loot_Filter/assets/2904198/540d82cb-3140-47df-9a83-67529c16adf0)

If you're doing Tier 6, go back to the Merchant's Guild and determine if that tier remains valuable. If so, create another rule labeled `HELMET T6` with the other values being the same as the first rule.

------------------------

This process will be repeated for all the builds listed on [Maxroll Corruption Tier List](https://maxroll.gg/last-epoch/tierlists/corruption-tier-list)
(or at the very least S Tier and A Tier)

> [!IMPORTANT]
> DO NOT create a new rule for each affix, you should be adding these to your existing rules labeled [Item Type][T6] or [Item Type][T7]

Once you've completed every build, you can select the `Export` button in the Loot Builder, then `Copy To Clipboard`. Submit this on my discord in the channel [#loot-filter-contributions](https://discord.gg/Tp79F3vwM6) *OR* request to contribute to the GitHub repo and I will provide further instruction on how to edit the master loot filter.

-----------------------

I understand this is a very manual process, but unfortunately it's the best I've come up with while not having an API endpoint to query Merchant's Guild prices. If that every becomes an option, I will work on scripting an automation to build out the XML based on desired criteria at any given point in time.





