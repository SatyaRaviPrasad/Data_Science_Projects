create schema RedBus;
create table bus_routes(
id int AUTO_INCREMENT PRIMARY KEY,
route_name text,
route_link text,
busname text,
bustype text,
departing_time time,
duration text,
reaching_time time,
star_rating FLOAT,
price decimal,
seats_available int
)