TABLE status, platform, related_project
FROM "07-content"
WHERE status != "published"
SORT created DESC