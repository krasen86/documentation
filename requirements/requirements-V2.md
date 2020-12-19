# Requirements

## EPIC 1: The system shall be able to provide information about the dentist
US1.1. As an end-user I want to see the clinic’s name so that I know with whom I make the booking with.  
US1.2. As an end-user I want to be able to see the clinic’s availability so that I can select a time that suits me.  
US1.3. As an end-user I want to be able to see the clinic’s address so that I know where to go for my appointment.  
US1.4. As an end-user I want to be able to see the name of the owner of each clinic, so that I can contact the supervisor in any possible complication occurrences.  
US1.5. As an end-user I want the system to be able to update the clinics opening when changes occur, so that I can make bookings according to the correct opening hours. [Update 1]

## EPIC 2: The system shall be able to display dentists in the Gothenburg area on a map.
US2.1. As a developer, I want to introduce a map feature, so that end-users have a graphical way of finding dentists.  
US2.2. As an end-user I want the location of the dentist displayed on the map so that I can decide on a location that is convenient for me.  
US2.3. As an end-user I want to be able to navigate the map so that I can find a dentist in Gothenburg.  
US2.4. As an end-user I want to be able to change the focus (zoom) of the map so that I can get an overview of the clinics in the area.  
US2.5. As an end-user I want to be able to select a clinic so that I can get more information about the clinic.  
US2.6. As an end-user I want the system to be able to update the map of dentists with new clinics in the area, so that I can book appointments to clinics most relevant to me  [update 1]
US2.7. As an end-user I want to be able to see clinics that have available time slots for a date of my liking so that I don’t have to browse all clinics. [update 2]

## EPIC 3: The system shall be able to update the time slots availability for the clinics in the Gothenburg area.
US3.1. As an end-user I want the system to be able to update the clinic's availability when changes occur so that I receive the latest information.  
US3.2. As an end-user I want the system to be able to increase the number of dentists in a clinic when changes occur, so that there’s more timeslots to make bookings from. [update 1]

## EPIC 4: The end-user shall be able to request an appointment for a specific clinic and time-slot.
US4.1. As an end-user I want to be able to see the available time slots whilst making an appointment.  
US4.2. As an end-user I want to receive a confirmation with a unique reference number when my appointment request is successful so that I can save my booking number and time.  
US4.3. As an end-user I want to be able to receive an error message when the appointment request is unsuccessful so that I can choose a different time slot.  
US4.4. As an end-user I want to be able to make an appointment by providing my name, email and phone number so that I can complete a booking fast.  
US4.5. As an end-user I want to be able to see the booking form and availability of the clinics by selecting the clinics on the map so that I don’t need to navigate multiple pages to make an appointment.  
US4.6. As an end-user I want to be able to make a booking for a specific time-slot and date, so that I can make the booking fit my own schedule. [update 1]  
US4.7. As a product owner I want the system bookings to include a timestamp in the specified format (update1) so that the availability time slots are updated accordingly. [update 1]

## EPIC 5: The system shall be able to process multiple request by the end-user and update the system accordingly.
US5.1. As a developer I want the system to be able to process multiple requests so that first come, first served.<br>
US5.2. As a product owner I want to introduce a request generator so that I can stress-test the system. [update 1]<br>
US5.2.1. See detailed specifications in the update document. [update 1]<br>
US5.3. As a developer I want the system to have fault-tolerance mechanisms so that the components can handle high request loads. [update 2]<br>
US5.3.1 As a PO I want the system to have logging mechanisms so that I can trace the overload, reaction and effect on the system. [update 2]<br>