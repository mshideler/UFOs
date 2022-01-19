# UFOs

## Project Overview

The purpose of this project is to help Dana, a data journalist, by helping her with a webpage related to UFO’s.  In addition to displaying her article, she needs our help to include a searchable table of UFO sightings.

## Results

The unfiltered table of UFO sightings is pictured here.

![Unfiltered Table](https://github.com/mshideler/UFOs/blob/main/Resources/no_results.png)

There is a list of filters to the left of the table that may be used to narrow the list of results.

![Search Filters](https://github.com/mshideler/UFOs/blob/main/Resources/search_filters.png)

Any of these filters may be used and may be used in any combination with each other.  Below are some examples of how to apply the filters:

1. Applying a single filter (Date, in this case)

   ![Single Filter](https://github.com/mshideler/UFOs/blob/main/Resources/single_filter_date.png)

2. Applying two filters (City and Shape, in this case)

   ![Double Filter](https://github.com/mshideler/UFOs/blob/main/Resources/double_filter.png)

3. Applying three filters (Date, Country and Shape, in this case)

   ![Triple Filter](https://github.com/mshideler/UFOs/blob/main/Resources/triple_filter.png)

## Summary

Overall, the page has good search functionality; however, one drawback is the criteria must be exact—no wildcards are allowed to capture more results, and there is case sensitivity.  For example, when looking for sightings in El Cajon, CA, “el cajon” must be entered for the city name, and “ca” must be entered for the state.

Results for “El Cajon” vs. Results for “el cajon”

![El Cajon](https://github.com/mshideler/UFOs/blob/main/Resources/El_Cajon_search.png)

![el cajon](https://github.com/mshideler/UFOs/blob/main/Resources/el_cajon_search2.png)

Therefore, one recommended feature would be to remove case sensitivity and allow partial strings and wildcards in the search criteria.  Another recommended feature would be to add a “Clear Search” button to remove all filters so users don’t have to reload the page every time they want the filters cleared.
