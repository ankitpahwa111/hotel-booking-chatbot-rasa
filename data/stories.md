<!-- Booking stories -->
## Book Room 1
* greet
  - utter_greet
* booking
  - utter_enquiry_room_no
* room_no
  - utter_enquiry_room_type
* choose{"room_type": "Simple"}
  - utter_confirmation
* affirm
  - utter_done
## Book Room 2
* greet
  - utter_greet
* booking
  - utter_enquiry_room_no
* room_no
  - utter_enquiry_room_type
* choose{"room_type": "Deluxe"}
  - utter_confirmation
## Book Room 3
* greet
  - utter_greet
* book+room_no
  - utter_enquiry_room_type
* choose{"room_type": "Simple"}
  - utter_confirmation
* affirm
  - utter_done
## Book Room 4
* greet
  - utter_greet
* book+room_no
  - utter_enquiry_room_type
* choose{"room_type": "Simple"}
  - utter_confirmation
* affirm
  - utter_done
<!-- Cleaning Stories -->

## Clean 1
* greet
  - utter_greet
* cleaning
  - utter_ask_time
* clean+time
  - action_relative
* affirm
  - utter_done
  
## Clean 2
* greet
  - utter_greet
* cleaning
  - utter_ask_time
* immediate
  - utter_cleaning_confirm
* affirm
  - utter_done
  <!-- FAQ -->
  ## Faq 1
* checkin
  - utter_checkin
 ## Faq 2
* checkout
  - utter_checkout
   ## Faq 3
* cancelreservation
  - utter_cancelreservation
   ## Faq 4
* cancellationpolicy
  - utter_cancellationpolicy
   ## Faq 5
* restaurant
  - utter_restaurant
   ## Faq 6
* breakfast
  - utter_breakfast
   ## Faq 7
* breakfasttimings
  - utter_breakfasttimings
   ## Faq 8
* restauranttimings
  - utter_restauranttimings
  <!-- GOODBYE -->
   ## Bye
* goodbye
  - utter_bye
