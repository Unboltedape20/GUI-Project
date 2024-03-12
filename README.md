# GUI-Project
# Hotel Reservation System

Our hotel reservation system is designed to efficiently manage hotel operations, including room assignments, reservations, guest services, and billing. To achieve this, we will be implementing several classes, enums, and data structures that will work together.

Firstly, we have the Room class, which represents individual rooms within the hotel. Each room has attributes such as a unique room number, type (e.g., single, double, suite), availability status, and price. By using an enum RoomType, we can easily categorize rooms hence will ensure consistency throughout the system.

The Guest class represents guests staying at the hotel. It contains attributes such as the guest's name, contact information, and a list of reservations associated with the guest. This allows us to track each guest's booking history and provide personalized services.

Reservations are managed using the Reservation class, which captures details such as the reservation ID, guest making the reservation, room booked, and check-in/check-out dates. This class facilitates the booking process and ensures that rooms are properly assigned to guests for their stay.

The Bill class handles billing for guest stays, including charges for room accommodation, services, and any additional fees. It links each bill to its corresponding reservation, enabling accurate invoicing and payment tracking.

To encourage guest loyalty and reward frequent visitors, we have implemented a LoyaltyProgram class. This class maintains a mapping of guests to points earned and points to rewards. Guests accumulate points based on their stay and can redeem them for various perks offered by the hotel.

Finally, the Hotel class serves as the central hub for managing hotel operations. It contains lists of rooms, reservations, and implements the hotel's loyalty program. This class will interactions between different entities and provides interfaces for performing various tasks such as making reservations, processing check-ins/check-outs, and generating bills.

By utilizing enums, lists, maps, and classes, our hotel reservation system offers flexibility, scalability.Enums ensure consistency in room types, while lists and maps facilitate efficient storage and retrieval of data. Design of our system will promotes code reusability and extensibility, allowing for easy integration of additional features and enhancements in the future.


