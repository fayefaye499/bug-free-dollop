# bug-free-dollop

SELECT
track_id,
track_name,
composer,
milliseconds,
milliseconds * 1000 AS secs
FROM
track
WHERE
composer = "Johann Sebastian Bach"
