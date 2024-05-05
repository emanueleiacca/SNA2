# Football Team Performance Analysis Using SNA
## Project Overview
This project applies Social Network Analysis (SNA) to study the interactions and performance dynamics of a football team across two halves of a match. By examining how players connect and influence the game through passing, we gain insights into the team's tactical execution and player significance.

### Data
The analysis is based on pass data collected during a professional football match. The data includes:

- Player IDs
- Matrix of the pass to understand who pass to who and how often

### Notebooks and .Html file
FirstHalf: Analyzes the team's network structure and player roles in the first half of the match.

SecondHalf: Continues the analysis into the second half, discussing the effects of tactical changes and player substitutions.

### Analysis Highlights
Centrality Measures: Explore how different players contribute to the team's strategy using degree, closeness, and betweenness centrality.

Network Dynamics: Visualize the team's passing network to understand the flow of the game and identify key players.

Comparative Insights: Assess how the team's performance evolves from the first to the second half, with a focus on strategic adjustments.

### Tools Used
NetworkX: For constructing and analyzing networks.

Matplotlib: For creating visualizations to display network and centrality metrics.

Pandas: For data manipulation and analysis.
## First Half Overview: 
The metrics and visuals provided a clear depiction of the game's dynamics. The most engaged players identified were numbers 2, 5, 8, and 10. Without specific position details, we can surmise that these players likely served as two fullbacks, a central midfielder, and an attacking midfielder, given their significant involvement. The dominance of these players was corroborated by both the Degree Centrality (DG) and EigenVector (EG) analysis, which highlight the frequency of their ball interactions and connections within the team. The PageRank analysis, which measures influence based on the quality of passes received, suggests that player number 8 played a pivotal role in linking up play among key players. 

## Second Half Adjustments:
The game's momentum shifted notably in the second half, possibly influenced by undisclosed substitutions. The flow of play seemed to oscillate more, potentially due to these changes. Notably, player number 10 was replaced by player number 20, who struggled to integrate into the game's rhythm. Conversely, player number 18, who substituted player number 9, appeared to revitalize the team's dynamics. The Degree Centrality (DG) data now highlighted player number 2 as the most connected, indicating their critical role in the match's network. EigenVector analysis confirmed player number 18's increasing involvement, while the PageRank scores indicated player number 5 as central to the team’s interactions. 

## Tactical Shifts and Game Impact:
The metrics indicate a reduction in overall team connections, likely due to the opposing team's increased possession and our strategic focus on defense and counter-attacks. Player number 18, likely a fast player, became central to our counterattacking efforts. Fullbacks number 2 and 5, who were not substituted, played key roles in linking defense with attack, maintaining stability and flow in the team's play despite the pressure. 
