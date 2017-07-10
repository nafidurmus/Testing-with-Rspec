#Nasıl başlatılır.

gem install rspec yazdıktan sonra 

rspec --init yaparak dosyamıza eklenti olarak spec/spec_helper.rb oluşturulur.

Ayrıca lib dosyasının içindeki ......_spec.rb dosyasının içine 
    
    require "spec_helper.rb"
    describe "   " do
       # örnekler
       # buraya -- it "örnek isim" -- şeklinde yazılmalı.
    end
    
    #spec/lib/...._spec.rb dosyasının içine yukarıdaki kodlar kendi kodlarına uygın şekilde yazılmalı.


spec/lib/......_spec.rb                     

require "spec_helper"
require " zombie "          		          
  describe Zombie do
    it "örnek isim"				               
  end
  
   lib/zombie.rb
   
   class Zombie
   end
