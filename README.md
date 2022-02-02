# assignment2-reddy
# vamsidhar reddy
###### HyderabadHouse. 
Near by the HyderabadHouse, many **Indians** reside, and many other **Indian restaurants** too.</br> 
This restaurant is owned by an Indian and is located in **Chicago, IL**.

*** 

### Airport to HyderabadHouse
O'Hare is the international airport that is near to HyderabadHouse
1. from airport take a cab to rosephalt
2. from rosephalt take pace bus to schaumburg pace station 
3. take a walk for 350 meters W to reach HyderabadHouse

***
The food that must try by others:</br>
*Chicken Tikka Masala

*Chicken Butter Masala  

*chicken Lollipos</br>
[About me](AboutMe.md)

***

## Sports Activities

#### The below table shows the sports which are located at various locations and the amount to be charged for participation.

| Name | Location | Amount |
| --- | --- | --- |
| Badminton | Recreation center | 10 |
| Cricket | Indore | 11 |
| TableTennis | Colden Hall | 14 |
| BasketBall | Valk Center | 15 |

***

## Quotes
> "I slept and dreamt that life was joy. I awoke and saw that life was service. I acted and behold, service was joy".</br>
 >>  -*Rabindranath Tagore*</br>
 
> To succeed in your mission, you must have single-minded devotion to your goal.</br>
>>   -*A. P. J. Abdul Kalam*</br>

***

### Code fencing

> Depth-first search is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node  and explores as far as possible along each branch before backtracking. So the basic idea is to start from the root or any arbitrary node and mark the node and move to the adjacent unmarked node and continue this loop until there is no unmarked adjacent node. Then backtrack and check for other unmarked nodes and traverse them. Finally, print the nodes in the path. 
[follow link for more details]<https://www.geeksforgeeks.org/depth-first-search-or-dfs-for-a-graph/>

```
vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices

vector<bool> visited;

void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}</br>

``` 
[follow link for more details]<https://cp-algorithms.com/graph/depth-first-search>
