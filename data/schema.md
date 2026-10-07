### Players
player_id        INT
signup_date      DATE
region           TEXT (NA / EU / ASIA)
platform         TEXT (PC / Console)


### Sessions
session_id       INT
player_id        INT
login_date       DATE
session_duration FLOAT


### Missions
mission_id       INT
player_id        INT
mission_type     TEXT   (Defense / Survival / Exterminate / Capture / Interception)
mission_duration FLOAT
success          INT  --  1 = Sucess, 0 = Failure
reward           INT