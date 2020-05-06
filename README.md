# IMPORTANT .LST INFO

The .LST file format has no concept of nested records. One line is one record, and everything to do with that record must be on that one line.

USE TABS spaces cause errors

workaround see: https://www.penwatch.net/cms/pcgen_lst_1/

## Tips and Tricks

### Change a stat example

Injured Leg CATEGORY:Injuries KEY:Injuries ~ Injured Leg TYPE:Special VISIBLE:YES DESC: -1 to initiative BONUS:COMBAT|INITIATIVE|-1|TYPE=Trait BENEFIT:You have an injured leg and suffer -1 to your initiative

There may be a more elegant solution, but for now this is working.
