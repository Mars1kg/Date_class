Instructions


1. Define the Date Class
Create a Date class with attributes:

day (int)

month (int)

year (int)

Provide appropriate constructors for these attributes.





2. Implement the Following Methods
isValidDate()

Validates if the date is within reasonable ranges.

Considers leap years while checking February 29.

updateDate(int d, int m, int y)

Updates the day, month, and year attributes after checking validity.

getDayOfWeek()

Returns the day of the week for a given date (e.g., "Monday").

calculateDifference(Date otherDate)

Computes the difference in days between two Date objects.

Considers leap years.

printDate()

Displays the date in a readable format, such as "January 1, 2023".

compareTo Method (Sorting Support)

Implements Comparable<Date>.

Sort the date list in ascending order, first by year, then by month, and finally by day.
Allows sorting Date objects using Collections.sort().




3. Write a Program
Create a Main class to demonstrate the Date class by:

Creating valid and invalid Date objects.

Updating a Date object.

Printing the day of the week.

Computing the difference between two dates.

Sorting an ArrayList<Date> using Collections.sort().

Sort the date list in ascending order, first by year, then by month, and finally by day.

Handling invalid inputs with appropriate error messages.
