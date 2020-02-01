# Spotify_plot.py has a function that uses several .csv files to generate a comparison histogram for a given feature between two different countires. The function automatically sets bins with np.linspace to generate frequencies, and makes line plots based on frequencies using matplotlib. 

# Titles and axes titles are set automatically. Axes limits are set automatically based on maximum values for the given audio feature between the two countries. Colors are set automatically so that the country with the higher mean value for the given audio feature is always blue for visual consistency in a presentation. 


# Spotify_plot.py also has an unused function make_scatter that makes a population scatter plot comparison between two countries. This function is useful for visualizing very different populations but less useful when the mean values for a given audio feature does not greatly differ between two countries. This function uses random.random to pair random x values to each audio feature value. Over 50 audio features this generates a general population.
