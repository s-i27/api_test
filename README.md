# api_test

SELECT SUBSTRING_INDEX(USER(), '@', -1) AS ip,  @@hostname as hostname, @@port as port, DATABASE() as current_database;
