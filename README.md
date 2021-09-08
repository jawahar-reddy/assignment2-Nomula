# assignment2-Nomula
# Jawahar Reddy Nomula

###### Ladakh is one of my favourite place.

As a travel **enthusiast**, I can say that Ladakh is one of the beautiful place to visit in India.<br> Here we can go on some of the adventurous bike rides in the country.<br> Moreover, Ladakh is famous for **camping** and **trekking**. A lot of tourists from many countries come and visit this place.

---

## How to travel from Maryville to Ladakh?
1. Go to Kansas Airport.
2. Take a flight from kansas to New Delhi.
3. From Delhi there are two best ways to reach ladakh
    1. it's better to take a rental bikeor from delhi
    2. we can also catchup a flight from delhi to Ladakh.
4. If we are moving on bike we can see a lot of places in between delhi to ladakh.

## List of items that are suggested to be carried for the trip
* Enough water bottles must be carried.
* Instant food items.
* if you go by bike enough fuel cans must be carried out.
* jackets or sweaters must be taken.

link of [AboutMe](https://github.com/jawahar-reddy/assignment2-Nomula/blob/main/AboutMe.md)

---

## List of food/drinks i recommend yoy to try
The table below describes my favourite drinks and food items that i would recommend you to try
| food/drink | location    | amount |
| :---       | :---        | :---   |
| Coffee     |  Starbucks  | $5     |
| Tea        | Indian mart | $4     |
| biryani    |  Mehfil     | $12    |
| coke       | any location| $2     |

---

## Quotes
> "Life is like riding a bicycle. To keep your balance, you must keep moving" .<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; - *Albert Einstein*

> "Life is a song - sing it. Life is a game - play it. Life is a challenge - meet it. Life is a dream - realize it. Life is a sacrifice - offer it. Life is love - enjoy it".<br> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; - *Sai Baba*

---

> The idea behind DFS is to go as deep into the graph as possible, and backtrack once you are at a vertex without any unvisited adjacent vertices.<br>
It is very easy to describe / implement the algorithm recursively: We start the search at one vertex. After visiting a vertex, we further perform a DFS for each adjacent vertex that we haven't visited before. This way we visit all vertices that are reachable from the starting vertex.

Here is the link:- <br>
<https://cp-algorithms.com/graph/depth-first-search.html>

Example code for `DFS`: 

```
vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices

vector<int> color;

vector<int> time_in, time_out;
int dfs_timer = 0;

void dfs(int v) {
    time_in[v] = dfs_timer++;
    color[v] = 1;
    for (int u : adj[v])
        if (color[u] == 0)
            dfs(u);
    color[v] = 2;
    time_out[v] = dfs_timer++;
}

```
Here is the link for code: <br>
<https://cp-algorithms.com/graph/depth-first-search.html>


