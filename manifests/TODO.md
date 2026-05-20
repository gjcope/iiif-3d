# TODO: Missing Placeholder Manifests

The following manifest files were removed because they were empty and caused the IIIF Presentation API 4.0 validator to report errors. It should be considered whether they should be implemented and added back in the future.

## Removed Files

### `8_scenes_with_duration/`

- **`zz_comment_at_t_pointselector.json`** — A scene with duration demonstrating
  a commenting annotation targeted at a specific time point using a PointSelector
  with a temporal component.

- **`zz_compact_frag_syntax.json`** — A scene with duration demonstrating the
  compact fragment syntax for targeting temporal segments of a timed scene.

- **`zz_video_on_iiif_canvas_in_scene_refinedby_t_mediafrag.json`** — A scene
  containing a video on a IIIF Canvas, with a media fragment selector used to
  refine the target by time (`t=`).

### `11_special/`

- **`zz_infinite_canvas.json`** — A manifest demonstrating an infinite canvas
  use case (details TBD).
