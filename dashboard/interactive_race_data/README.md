# Dashboard data directory

Production data is intentionally not committed to this repository.

The live dashboard expects JavaScript data modules in this directory. In production these files contain reconstructed monthly channel/video series, channel avatars, video event indexes, and Rain-mode indexes.

Expected file families:

- channel metric datasets, for example `channel_views.js`, `channel_subscribers.js`, and related channel metrics;
- video compact datasets, for example `videos_normal_compact.js`;
- Rain-mode video indexes, for example `rain_video_events.js`;
- per-channel Rain indexes under the production `rain_channel_events` structure;
- channel avatar lookup data, for example `channel_avatars.js`.

To run the dashboard with real data, copy the generated production `interactive_race_data` folder next to `dashboard/index.html`.

The public GitHub repository keeps the application shell and documentation only, so the repository stays lightweight and does not publish the full production dataset.
