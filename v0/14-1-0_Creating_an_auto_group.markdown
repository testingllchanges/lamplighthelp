# 14.1.0    Creating an {{auto group}}

> On the main menu go to {{Group}}s -> Add {{auto group}}. Give the {{group}} a name and description; enter your search criteria, and click 'Save'. 

On the main menu go to {{Group}}s -> Add {{auto group}} and you will see the following screen:

![Creating an {{auto group}}]({{imgpath}}103a.png)

This screen is where you set up the criteria for your {{group}}. As you go through you can add different aspects: {{Lamplight}} will include people that meet ALL the criteria you enter. Note too that all numeric and date comparisons in {{Lamplight}} are inclusive (for example >=, not > ).

When you have added all criteria, click the 'save' button in the bottom-right.

**{{Group}} name tab**: the name and description of the {{group}} are to help you and other users of the system remember what this {{group}} is for. Both are required fields.

**{{People}} tab:** do you want a {{group}} of individuals, or organisations? What types of {{people}} do you want?

![{{Auto group}}s - choosing what types of {{people}} to add]({{imgpath}}103b.png)

You cannot create a {{group}} of both {{people}}. The search for the type of {{person}} ({{user}}, {{staff}}) etc. is an 'OR' search: it will include those that meet any of the criteria selected, not just those that meet all of them.

**Address:** search by address. You can search particular lines of the address, or more reliably search any part of it, or by postcode. When searching by postcode, you can enter multiple postcodes (or partial postcodes) separated by a semi-colon (;). Whenever you search for text, you can select how the search should be carried out: 

  * Exact match - the phrases should be identical, but case-insensitive (so 'hello' matches 'HeLLo')
  * Match anywhere - will match the entire string wherever it occurs (so 'stone lane' matches '15 Stone Lane', and matches '15 Brightstone Lane', but does not match '15 Stonecroft Lane'.
  * Starts like - will match any strings that start with the search string

Spaces at the beginning and end of address lines is excluded from searches.

**Relationship:** searches by relationship created between {{people}}. This allows you to create {{group}}s of, say, 'parents' or 'trustees'. 

**{{User}} fields, {{staff}} fields, {{funder}} fields etc:** are fields set up for {{user}}s, {{staff}}, and {{funder}}s respectively, so the choices will depend on how your system has been set up (and may not be visible at all if there are no fields set up).

The comparisons vary depending on the type of field. Date and number fields may be matched as either: 

  * Greater than or equal to, meaning that people with a value greater (or later) than or equal to the value you specify will be included.
  * Less than or equal to
  * Equal to

Where there are multi-select options, only those that match all of your selections will be included in the {{group}}.

**{{Work}}** tab lets you filter for {{people}} based on {{work}} records. If you want to find {{people}} that have attended based on dates, you first need to set the dates, you need to specify what {{work}} has happened around those dates. You can also specify if you want to be sure that you find people that have not attended at certain periods. So, for example:

To identify people attending after 1st April 2009 and before 31st March 2010:

![Automatic groups - {{work}} records tab example 1]({{imgpath}}103c.png)

To identify people attending between 1st April 2009 and 30th September 2009 (equivalent to people attending between Q1 2009 and Q2 2009)

![Automatic groups - {{work}} records tab example 2]({{imgpath}}103d.png)

To identify new users - people attending after 1st April 2009 that had never attended before then:

![Automatic groups - {{work}} records tab example 3]({{imgpath}}103e.png)

To identify 'April only' attendees - new users in April 2009 who have not returned since:

![Automatic groups - {{work}} records tab example 4]({{imgpath}}103f.png)

Finally, you can add filters by {{workarea}}, attendance type and role, and any custom {{work}} fields you have added to your system.

The **{{Outcome}}s** tab lets you search for {{people}} that have {{outcome}} scores above or below a certain level, between certain dates, and even whether that score has been maintained for a certain period of time. This will let you set up {{group}}s like '{{people}} that have gained a job and have sustained it for 6 months'. Bear in mind here that {{Lamplight}} treats yes-no {{outcome}}s as 1 - 0 (ie a 'yes' is stored as 1, and a 'no' as a 0, so to find {{people}} that have answered 'yes' to a particular {{outcome}} you'll need to enter 'Outcome score' as 'Equal to' '1'. 

[View the video](/help/video/id/18)
###### core module

