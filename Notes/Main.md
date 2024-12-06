# Intro:

Main Database

- Workload:

    - Write-heavy and read-heavy depending on the application's needs.
    - Random writes and reads for general key-value storage.

- Priority:

    - Balance read/write performance.
    - Durability and efficient compaction.

# Recomendations:

Optimize for a mix of read and write operations.

# Config:

1. Configure `block_cache` for random reads and optimize for general-purpose
   access.
