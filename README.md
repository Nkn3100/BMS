# BMS
Book My Show
Requirement gathering
1. User should be able to book tickets
2. Book my show is available in a lot of cities and user can choose a city
3. User can choose movie
4. User can choose theater
5. User can choose Show (time)
6. User can choose seat and make payment to get tickets
7. Each theater may have many sreens (AUDI) and each screen would be showing a different movie at the same time
8. Show is a movie playing at a particular time at a particular audi in a particular theater
9. Users should be able to see all movies in a particular region
10. When user chooses a movie he/she should be able to see all shows of the movie.
11. In one booking user can book upto 10 seats
12. No two people should be able to book the same seat
13. Price will depend on two things -> show and seat type
14. Payment should be handled by 3rd party. We used to store the ref Id , payment gateway and status
15. User can cancell their bookings as well
16. We want to support partial payments as well(for a 400 rs, we can use 200 voucher and 200 payment)
17. Movie details -> poster, name, cast, trailer, language, genre, suration, ratings, certificate
18. Movie features -> DOLBY AUDI, DOLBI VISION, 3D, 3K, 4K ATMOS, IMAX etc
19. Auditorium feature -> DOLBY AUDI, DOLBI VISION, 3D, 3K, 4K ATMOS, IMAX etc
20. Each auditorium will have different types of seats (it will be a class instead of an enum because theater might want to customize their seat names)

