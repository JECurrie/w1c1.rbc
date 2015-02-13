# w1c1.rbc
#Convert seconds to years and months.
def seconds_to_years(seconds)
#Assume months are 30 days long.
##seconds2_in_standard_year = ( 60.0 * 60 * 24 * 365 ) + ( 60.0 * 60 * 24 * 31 )
seconds_in_standard_year = ( 60.0 * 60 * 24 * 365 )
age_in_years = ( seconds ) / seconds_in_standard_year
print format "I'm %d years and " % age_in_years 
months = 12 * ( age_in_years - age_in_years.to_i ) 
puts format "%d months old," % months.to_i
end

seconds_to_years(979000000)
seconds_to_years(2158493738)
seconds_to_years(246144023)
seconds_to_years(1270166272)
seconds_to_years(1025600095)
