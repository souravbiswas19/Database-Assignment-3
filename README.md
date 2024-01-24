1. SELECT name FROM User;
2. SELECT * FROM Tweet WHERE userid = 101 ORDER BY tweettime DESC;
3. SELECT COUNT(*) FROM Like WHERE tweetid = 501;
4. SELECT COUNT(*) FROM Retweet WHERE tweetid = 501;
5. SELECT COUNT(*) FROM Tweet WHERE commentid=501;
6. SELECT U.name FROM User U JOIN Retweet R ON U.userid = R.userid WHERE R.tweetid = 502;
7. SELECT tweettext FROM Tweet WHERE commentid = 501;
8. SELECT T.tweettext, U.name FROM Tweet T JOIN User U ON T.userid = U.userid WHERE T.tweetid = 501;
