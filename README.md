# Food Recommendation System Using Java

Topic Introduction:\
	Based on the user interests this system will narrows down the food menu for the user. The finalized list highlights the food items which are recommended for the user.\

Query Format:\
	Food Recommendation system requires three csv input files, Food Catagories, food types, restaurant types and food items with ids.\

Query Processing Method:\
	For each of the combination of the user interests(input requires atleast one input value among three inputs, such as, restaurant type, food type and food category). Food recommendation system generates a food menu. The input data is completely based on the csv data (RestaurantType.csv, FoodType.csv, FoodCategory.csv and FoodItemIdNames.csv) provided to the system and on the user inputs.\
\
Optimization Explanation:\
	Food recommendation system uses a very simple optimization technique. Based on the user input values for food type, food category and restaurant type, this system filters the concerned results. Here the filtration happens based on the user selection of the input values by using if condition and results are generated and stored in FoodRecommend.csv file.
\
# Sample Execution Screenshots:

1. Goto project source file directory (cd ~/Desktop/Restaurant/src/)\
2. Check for the input csv files and java files. (ls *.csv and ls *.java)\
3. Compile java files (javac -d . FoodCategory.java) to create package directory which contains the compiled class files.\
4. Run the program using the command java restaurants.FoodRecommend\
5. Enter input values.\
6. Press 4 to see your recommended food\
7. Press 5 to exit from the program.\
8. The final results get appended to the FoodRecommend.csv file.\


# Project Summary:\
	Food Recommendation is a basic project which deals with the set of user specific interests to recommend food. Based on the selected restaurant type, food type and food category, this system generates the menu for the user that satisfies the user inputs.\
  
# Required csv files
FoodType.csv\
FoodCategory.csv\
RestaurantType.csv\
FoodItemIdNames.csv\

# Compile program
cd /path/to/src/\

javac -d . FoodType.java\
javac -d . FoodCategory.java\
javac -d . RestaurantType.java\
javac -d . FoodItemIdNames.java\
javac -d . FoodRecommend.java\

# Run program
java restaurants.FoodRecommend\

# Every time you ask for recommendation, the recommended food for the given options gets appended to FoodRecommend.csv file.


