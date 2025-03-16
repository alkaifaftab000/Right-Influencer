# Choosing the Right Influencer 🎯

## Project Overview 📜
This project leverages the Twitch dataset to identify the top five influencers within the Twitch network. By applying advanced graph metrics on Twitch nodes and edges, the analysis aims to determine the most influential individuals.

---

## Workflows ⚙️
The following metrics were applied to the Twitch graph dataset (nodes and edges):
1. **Betweenness Centrality** 🛤️: To measure the control over the information flow in the network.
2. **Degree Centrality** 🔗: To analyze direct connections of each node.
3. **Closeness Centrality** 🚀: To determine the efficiency of reaching other nodes from a specific node.
4. **Clustering Coefficient** 🤝: To evaluate the tendency of nodes to form tightly-knit groups.
5. **Eigenvector Centrality** ⭐: To determine the influence of nodes based on their connection to other influential nodes.

### Strategy 🧠
1. Individually applied **Betweenness**, **Eigenvector Centrality**, and **Degree Centrality** to the graph data.
2. For each metric, extracted the **top 10 nodes** based on their scores.
3. Merged the three top-10 datasets and conducted an intersection to find the **top 3 influencers** present across all three metrics.

---

## Learning Outcomes 🎓
1. Enhanced understanding of applying graph-theoretic metrics in social network analysis.
2. Gained insights into designing strategies for influencer identification by combining multiple centrality measures.

---
## Our Top Twitch Influencer 2023

1. Sacriel  
[Click here](https://www.twitch.tv/sacriel)  
Channel Id - 23735582  
Id - 4949
![{5A227D9B-6776-43A9-AE58-A45B4FA429D2}](https://github.com/user-attachments/assets/7647db0c-38a6-498c-a2e9-0787475c5915)
---
2. Yogscast  
[Click here](https://www.twitch.tv/yogsca)  
Channel Id - 20786541  
Id - 1773  
![{0AB9A7A2-D254-4629-B6AD-59A2B16A1DCA}](https://github.com/user-attachments/assets/0aa77c46-076c-4c4e-b443-ad3a558a7d8a)
---
3. FACEIT  
[Click here](https://www.twitch.tv/faceittv)  
Channel Id - 27942990  
Id - 6136
![{B86559EE-1FBC-40D4-AB43-F2D755B08EFF}](https://github.com/user-attachments/assets/2daea960-5cad-4bf0-982d-6033c9ed3157)

----


## Plugins and Libraries Used 🛠️
- **Pandas**
- **NetworkX**
- **Matplotlib**
- **Seaborn**
- **NumPy**
