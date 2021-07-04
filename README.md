# UFOs
Create a dynamic table on a webpage to explore UFO data using CSS, HTML, JavaScript, and Bootstrap

# Project Overview
In this assignment, we are helping Dana present data on UFO sightings to others via a dynamic table on a website. She would like us to help her improve her dynamic table so that users can perform a more in-depth search.

# Project Results:
## Using the Website:

When first visiting the page, the user is met with the Jumbotron header featuring the phrase 'The Truth Is Out There'. This phrase has become linked to the show The X-Files in reference for UFO sightings and other unexplained phenomenon.

Users are then presented with a short article by a ufologist.

![Main Page](https://github.com/ssheggrud/UFOs/blob/58721fb10058c53eeb98b67ad96713297c3fea3a/static/images/main_pg.jpg)

Scrolling down, the users will find the heart of the page. The search box that will allow them to look up data on UFO sightings.

The default setting shows all of the sightings currently available.

![Default Search](https://github.com/ssheggrud/UFOs/blob/3f07071c215b96ee974fba770ed65d2c37ee782b/static/images/default_search.jpg)

The end user can enter as much or as little information as they'd like in the search boxes, and the table will dynamically adjust. Below is an example filtering on Buffalo, NY.

![Buffalo UFOs](https://github.com/ssheggrud/UFOs/blob/3f07071c215b96ee974fba770ed65d2c37ee782b/static/images/specific_search.jpg)

# Summary
## Pros of the site:
The page is fairly crisp and uncluttered, making it easy for users to find the sections they're looking for. The overall visual of the site lends itself well to the theme.

## Cons of the site:
The biggest con is that in order to search, you need to know how the data is formatted. The data is case sensitive, NY is not the same as ny. This could lead to false negative results because unless the end user looked at the default results before entering their search terms, they might not realize the limitations. There's nothing to guide the end user on the best way to get results, aside from the placeholder text.

## Recommendations for further developement:
*Instructions should be added:
    - "Press Tab or Enter to filter"
    - Alternately, add a filter button
*Change the text search buttons into drop-down boxes. The lists in the boxes would show values for that criteria.
*Include the date range for the data so that the end user knows the overall time frame they're looking at.
*Change the date from a single box to a range option. This would allow the end user to look at several dates at once for a location.
*Adding validation to the fields might help as well. Something that would alert the end user that they didn't enter data in a way the search box recognizes. Entering "1/2010" returns no results when it might be better if it gave an error that it wasn't a valid entry. It's another case of a false negative.
