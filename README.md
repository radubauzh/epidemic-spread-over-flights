# Epidemic spread over the flights network
## Abstract
Pandemics are known to spread rapidly over the world if no measures are taken to control the spreading. In this final report, we analyze the flight network through centrality measures to detect nodes of interest. With the help of a spreading simulator, we then analyze the behavior of said nodes in a pandemic setting. To assess the behavior of the network without the node of interest, we ran the simulation without these nodes. Overall, our results show that the removal of nodes of interest is an effective strategy to reduce the spread of a pandemic. By targeting the most connected parts of the network, we can significantly reduce the reproduction rate of the disease and limit its spread.

\begin{figure}[h!]
  \includegraphics[width=\linewidth]{epidemic-spread-over-flights/Pictures/heatmap.png}
  \caption{Heatmap of the world picturing all airports with their degree as a bubble. Edges between airports displaying the routes of airlines.}
  \label{img:map}
\end{figure}

![Alt text](epidemic-spread-over-flights/Pictures/heatmap.png "Title")

## Conclusion
This final report studies the importance of nodes (airports) in controlling the spreading of a pandemic. The in-/out-degree distribution, several centrality measures and the page rank were calculated and used to identify the relevant nodes in the aviation network. As discussed in Chapter 4, four airports were identified as vital for the flight network in a pandemic setting. As stated in Chapter 4, the results need to be enjoyed with care, since numerous variables come into play, when pinpointing nodes of interest in a pandemic (Chapter 2). Nevertheless, the results convey an emphasis on airports that are highly interconnected (i.e. hubs). With the spreading simulator, we were also able to test what effect the removal of the identified nodes has on the rapidity the disease propagates through the network. The fact, it takes most of the iterations (i.e. starting from one node and spreading through the whole network) one iteration longer, is also an identification of the significance of the extracted nodes. Overall we can conclude that it is possible to identify the most relevant nodes of the air travel network on a high level (i.e. measurements through routes) and analyze their significance in a pandemic.


