## Memory Limits and Maximum Storable Elements in STL Containers

| Container + Type                       | `sizeof(T)` (bytes) | Max N (256 MB)         | Max N (512 MB)         |
| -------------------------------------- | ------------------- | ---------------------- | ---------------------- |
| `vector<char>` / `string`              | 1                   | **2.68 × 10^8**        | **5.36 × 10^8**        |
| `vector<bool>` (bit-packed)            | \~0.125             | **2.15 × 10^9**        | **4.29 × 10^9**        |
| `vector<int>`                          | 4                   | **6.71 × 10^7**        | **1.34 × 10^8**        |
| `vector<long long>`                    | 8                   | **3.35 × 10^7**        | **6.71 × 10^7**        |
| `vector<double>`                       | 8                   | **3.35 × 10^7**        | **6.71 × 10^7**        |
| `vector<pair<int,int>>`                | 8                   | **3.35 × 10^7**        | **6.71 × 10^7**        |
| `vector<pair<long long,long long>>`    | 16                  | **1.68 × 10^7**        | **3.35 × 10^7**        |
| `set<int>` / `unordered_set<int>`      | \~24–32             | **(0.84–1.12) × 10^7** | **(1.68–2.24) × 10^7** |
| `map<int,int>` (red-black tree node)   | \~32–40             | **(0.67–0.84) × 10^7** | **(1.34–1.68) × 10^7** |
| `unordered_map<int,int>`               | \~32–48             | **(0.56–0.84) × 10^7** | **(1.12–1.68) × 10^7** |
| `deque<int>`                           | \~4                 | **6.71 × 10^7**        | **1.34 × 10^8**        |
| `priority_queue<int>` (heap in vector) | \~4                 | **6.71 × 10^7**        | **1.34 × 10^8**        |

---


