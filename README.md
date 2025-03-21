# **Altair Interactive Visualization Project**
This project explores **interactive data visualization** using **Altair**, a declarative statistical visualization library in Python. It showcases various **interactive elements**, including filtering, selection, and zooming, to enhance **data exploration**.

## **📊 Overview**
- **Built an interactive visualization** using **Altair** to enable dynamic filtering and user-driven insights.
- **Implemented linked charts**, enabling selection-based interactivity across multiple visual elements.
- **Exported the visualization as an interactive HTML file**, allowing easy sharing and embedding.

---

## **🖼️ Example Interactive Visualization**

- **1️⃣ Visualization 1: Goals of World Cup Winners Since 1950**
  * Description: A line chart visualizing the goals scored by World Cup-winning teams since 1950.
  * Interactivity:
    - Hovering over bars displays the average score as tooltips.
    - Brushing (dragging over bars) changes the opacity of unselected bars.
    - Brushing also updates the average score line, dynamically adjusting to the selected range.
    - 
## ⚽ Interactive World Cup Visualization  

[Click here to view the interactive Altair chart! 🎉](https://oscar10408.github.io/WorldCup-Interactive_Visualization/chart1.html)

Or click the preview image below:

[![World Cup Interactive Chart](output/chart1_preview.png)](https://github.com/oscar10408/WorldCup-Interactive_Visualization/blob/main/chart1.html)

- **2️⃣ Visualization 2: Matchups Between World Cup Winners**
  * Description: A heatmap showing historical matchups between past World Cup winners.
  * Interactivity:
    - Hovering over a cell highlights the number of times two winning teams played against each other.
    - The color intensity indicates the frequency of matchups.
    - Users can filter by specific World Cup tournaments.

- **3️⃣ Visualization 3: Goal Timing Distribution**
  * Description: A bar chart displaying the distribution of goals scored across different minutes of a match.
  * Interactivity:
    - Hovering over a bar shows the exact number of goals scored in that minute.
    - Brushing over a time range filters the goal distribution to only show specific periods of the game (e.g., first half vs. second half).
    - A dynamic average goal line updates based on the brushed selection.

- **4️⃣ Visualization 4: Goal Distribution by Teams**
  * Description: A stacked bar chart comparing goal-scoring patterns for different World Cup-winning teams.
  * Interactivity:
    - Clicking on a team filters the visualization to show only that team's goals.
    - Hovering over a segment displays goal counts in tooltips.
    - Users can toggle between total goals and percentage-based views for comparison.


---

## **🛠️ Technologies Used**
- Altair – Declarative visualization library
- Pandas – Data handling and processing
- Jupyter Notebook – Interactive coding environment
- Python – Core programming language

---
