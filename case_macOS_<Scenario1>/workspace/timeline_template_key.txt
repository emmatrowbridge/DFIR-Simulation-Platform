event_id: A simple numeric identifier for ordering rows. This makes the file easier to read and reference.
timestamp: The timestamp of the event, ideally in a standardized format such as YYYY-MM-DD HH:MM:SS.
event_description: A plain-language description of what happened (e.g., "User executed suspicious installer")
artifact_source: The artifact that supports the event (e.g., Safari History, Unified Logs, Windows Security Event Log, Prefetch, LaunchAgent plist, etc.)
artifact_path: The exact path or file name where the evidence came from (e.g., /Users/research_eng/Library/Safari/History.db or C:\Windows\System32\winevt\Logs\Security.evtx)
notes: Optional explanation, ambiguity, or supporting detail.
