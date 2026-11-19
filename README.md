# pgvector AI Agent Persistent Memory

This example demonstrates how to use PostgreSQL with the `pgvector` extension to provide persistent, semantic memory for AI agents. It shows how to store vector embeddings representing agent experiences and then perform similarity searches to retrieve relevant past "memories" based on new input. This allows AI agents to learn from and leverage their history, much like Sherlock Holmes recalling critical clues.

## Language

`python`

## How to Run

1. Ensure PostgreSQL is running with the `pgvector` extension enabled (`CREATE EXTENSION vector;` in your database).
2. Install dependencies: `pip install psycopg2-binary pgvector`.
3. Set environment variables for your PostgreSQL connection (e.g., `PG_DB`, `PG_USER`, `PG_PASSWORD`, `PG_HOST`, `PG_PORT`) or modify the script directly.
4. Run the script: `python main.py`.

## Original Article

This example accompanies the Turkish article: [Yapay Zeka Ajanlarının Kalıcı Hafızası: pgvector ve Sherlock Vuruşları](https://fatihsoysal.com/blog/yapay-zeka-ajanlarinin-kalici-hafizasi-pgvector-ve-sherlock-vuruslari/).

## License

MIT — see [LICENSE](LICENSE).
