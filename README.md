This is code from a Data Analytics bootcamp project that pulls track information from the top 50 songs by country from Spotify's API, does some automated analysis, and produces several matplotlib figures. OAuth 2.0 is handled by the spotipy library in the spotify_top_50 script, which is responsible for calling the api and writing the results to a pandas df. 

p_value_matrix creates a df of 2-tailed t-test results comparing each country to each other country for a given top 50 audio feature. This function gives a high level overview of statistically significant comparisons between countries for a selected feature.

make_plot creates both cluster plots and histograms from top 50 song csv data given a feature and two countries to compare. Formatting for the histogram is automatically, with the country having a higher mean value for the audio feature being shaded in blue.
