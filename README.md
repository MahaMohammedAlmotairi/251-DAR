# DAR_Group2
void reschedule(String d, String t) {
        if (isBooked) { 
            date = d; 
            time = t;
            System.out.println("Appointment is rescheduled: " + date + " " + time); }
        else System.out.println("No booking found.");
    }
