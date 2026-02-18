## Incremental Strategy

- Maintain watermark timestamp
- Fetch only new records
- Compute embedding
- Compare similarity with 30-day corpus
- Drop if similarity > 0.92

Pseudo Logic:
`
FOR document IN new_batch:
    embed(document)
    similarity = max_cosine_similarity(corpus)
    IF similarity < threshold:
        insert_to_silver
`
