A. Clear instructions for how to REQUEST data from the microservice you implemented. Include an example call.
        
        I will be open my partner's text file, and write the zipcode for his to read, so that he can provide me the weather of this location
        f = open('partner_file.txt', 'w')
               f.write(zipcode)
               f.close()

B. Clear instructions for how to RECEIVE data from the microservice you implemented:

       I will be receiving data from my partner's text file and read it. Eventually, I will render zipcode  and temperature in the user interface

        f = open('partner_file.txt','r')
                    line = f.readline(Zipcode, Weather)
                    f.close()

        print(Zipcode, Weather)            


C. UML sequence diagram showing how requesting and receiving data work. Make it detailed enough that your partner (and your grader) will understand
