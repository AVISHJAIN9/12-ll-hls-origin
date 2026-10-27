# Systems Engineering Glossary: Low-Latency HLS Origin Packager

### LL-HLS
Low-Latency HTTP Live Streaming protocol reducing video playback delay to under 3 seconds using partial chunks.

### Partial Segment
Sub-division of a video media segment transmitted via chunked transfer encoding before full segment finalization.

### Delta Playlist
Optimized HLS manifest omitting unchanged media segments to minimize manifest polling bandwidth.

### Blocking Playlist Reload
HTTP request waiting on the origin until a new segment or partial chunk is generated.
