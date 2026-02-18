## Strategy

- Cross-source validation
- Confidence scoring
- Reject low similarity outputs
- Enforce citation presence

Confidence Formula:

confidence = (semantic_similarity × 0.5) +
             (source_overlap × 0.3) +
             (alignment_score × 0.2)

Reject if confidence < 0.7

====================================================================
