# NoSQL Engine

The NoSQL engine is a highly efficient and flexible data storage system designed for quick and easy access to large volumes of unstructured data. By pairing unique keys with corresponding values, it ensures rapid data retrieval and manipulation. This engine excels in various applications, such as enhancing web performance through caching and supporting scalable distributed databases.

## Data Structures:
- WAL (Write Ahead Log)
- SSTable (Data, Index, and Summary)
- LSM Tree (Log-Structured Merge Tree)
- Merkle Tree
- Bloom Filter
- B-Tree
- Cache
- Skip List
- SimHash
- HyperLogLog
- Memtable
- Token Bucket
- Count-Min Sketch

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/conamiflo/NoSQL-Storage-Engine.git
    ```

2. Navigate to the project directory:
    ```sh
    cd NoSQL-Storage-Engine
    ```

### Usage

1. Start the engine:
    ```sh
    go build
    ```

2. Perform operations using the provided API:
    - **PUT**: Inserts a bit array value associated with a string key, returning a boolean indicating success.
    - **GET**: Fetches the bit array value linked to a given string key.
    - **DELETE**: Eliminates a record identified by a string key, returning a boolean to signify success.
    - **LIST**: Retrieves a list of values whose keys begin with a specified string prefix.
    - **RANGE SCAN**: Obtains values within a key range, defined by minimum and maximum string keys.

