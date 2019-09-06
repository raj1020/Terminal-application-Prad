# Terminal-application-Prad
Holiday recommendation using ruby


places={
            place1: ["activity1", "activity2", "activity3"],
            place2: ["activity2", "activity5", "activity4"],
            place3: ["activity4", "activity1", "activity5"],
            place4: ["activity3", "activity4", "activity5"]


}
i=0
input1=gets.chomp
input2=gets.chomp


places.each do |key, value|
    
    


    if input1==value[i] or input1==value[i+1] or input1==value[i+2]
        if input2==value[i] or input2==value[i+1] or input2==value[i+2]

            puts"your recommended holiday is in #{key}"

        end

    end
end

