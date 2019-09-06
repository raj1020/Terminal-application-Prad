# Terminal-application-Prad
Holiday recommendation using ruby



places={
            Sydney: ["Adventure", "Art_Music_Culture", "Beaches_and_Islands"],
            Hobart: ["Adventure", "Food_and_Wine", "Festival_and_events"],
            Goldcoast: ["Beaches_and_Islands", "Adventure", "Nature_and_Wildlife"],
            Perth: ["Adventure", "Art_Music_Culture", "Nature_and_Wildlife"],
            Melbourne: ["Art_Music_Culture", "Sports", "Festivals_and_Events"],
            Brisbane: ["Adventure", "Art_Music_Culture", "Food_and_Wine"],
            Adelaide:["Food_and_Wine", "Art_Music_Culture", "Shopping"],
            Darwin: ["Sports", "Festival_and_events", "Adventure"]
}
i=0
puts "Please choose the most important holiday activity for you from the list:\n Adventure \n Art_Music_Culture \n Beaches_and_Islands \n 
Food_and_Wine \n Festival_and_Events \n Nature_and_Wildlife \n Sports \n Shopping"
input1=gets.chomp

puts "Please choose the second most important holiday activity from the list above"
input2=gets.chomp


places.each do |key, value|
    
    


    if input1==value[i] or input1==value[i+1] or input1==value[i+2]
        if input2==value[i] or input2==value[i+1] or input2==value[i+2]

            puts"your recommended holiday is in #{key}"

        end

    end
end

