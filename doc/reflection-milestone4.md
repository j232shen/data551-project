## Reflection on Our Dashboard

 In this reflection, we explain what we have built so far, what still needs work, and how we have used feedback to improve the app.

### What We Have Implemented

- **Header and Layout:**
We added a clear header displaying the dashboard’s title and purpose, giving users an immediate understanding of its focus. Titles and descriptions were also added to each tab and plot, helping users navigate the dashboard smoothly and find key insights more easily.

- **Visual Enhancements:**
We improved the affordability index cards by adding a feature that shows the change compared to the previous year. This helps users see trends over time more clearly. Additionally, we added a legend on the map, which now helps users understand what the colors and symbols represent.

- **Detailed Explanations:**
Each graph now has a subtitle to explain what the data means. For example, we clarified the difference between "All Commodities" and "Staple Commodities" in our food price trend plots. This extra detail makes it easier for users to understand the context behind the numbers. Additionally, we added an info tooltip to help users interpret the Affordability Index, clarifying its relationship to the Affordability Ratio and addressing potential confusion between the two.

- **Dynamic Sizing:**
Graphs and containers now adjust relative to the viewport and their parent elements, ensuring a consistent layout across different screen sizes.

- **Default Data Displays:**
To maintain visual clarity, plots on the global tab now default to showing data from the last selected country and year when all selections are cleared, preventing empty plots. On the country tab, the Affordability Index card displays "No data available before 2021" instead of appearing empty, as selections from 2021 to 2024 still influence the map and other plots within the tab.

### Feedback and Improvements
Feedback from peers and TAs played an important role in our development process. Here are some key points we addressed:

- Positive Feedback:
Users liked the overall clean design and found the interactive features (like the cursor for comparisons) very helpful. They felt that the dashboard was easy to navigate and the graphs were informative.

- 


### What Is Still Under Development

If we were to continue working on this, we would want to address the following areas of improvement:
- A suggestion was made to include a chart ranking countries by certain metrics (e.g., highest or lowest values). While this could be a valuable addition, we prioritized optimizing existing dashboard components due to time constraints.
- Another suggestion was to switch to horizontal bar charts on the country tab for better label readability. While this would likely improve readability, the benefit was too small to justify the significant HTML reorganization required. However, this could be worth exploring in the future.
- Some users suggested shortening variable names to improve readability. Although we made some effort to do this, the variable names have their own meaning that is important to the users. Trying to shorten them too much sometimes led to technical issues, like overlapping text. So, we chose to keep the variable names as they are to avoid confusion.
- Finally, we would also want to enhance the dashboard’s visual design by applying a stronger theme (e.g., a cohesive color palette for the background and other elements). Additionally, we could improve the layout of the bottom half of the global tab by reorganizing the filters to better indicate their connection to the bottom two graphs. 

### Conclusion

Overall, our dashboard now has a strong design with clear titles, descriptions, and visual aids that make the data easier to understand. While we have made significant progress, we recognize there are still improvements to be made. By focusing on the areas that need work and considering user feedback, we are confident that our dashboard will continue to evolve and become even more user-friendly in the future.
