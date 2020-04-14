# Class 2 Example Object

* Instance: `sally_s`
* Attributes:
  1. `employee_name = "Sally Smith"`
  2. `employee_wage = 16.50`
  3. `role = "server"`
  4. `weekly_hours_available = 35`
  5. `hours_worked_this_week = 0`
* Methods:
  1. `give_raise(raise_amount)`:
      ```
      employee_wage = employee_wage + raise_amount

      give_raise(1.50)
      =>
      employee_wage = 18.00
      ```
  2. `transfer_role(new_role)`:
      ```
      role = new_role

      transfer_role("bar tender")
      role = "bar tender"
      ```
  3. `update_availability(new_hours)`:
      ```
      weekly_hours_available = new_hours

      update_availability(40)
      =>
      weekly_hours_available = 40
      ```
  4. `hours_remaining`:
      ```
      hours_remaining = weekly_hours_available - hours_worked_this_week
      ```
        After Sally has worked 15 hours (assuming her hours have already been update to reflect the `update_availability(40)` method called above):
      ```
      hours_remaining = 40 - 15
      hours_remaining = 25
      ```
