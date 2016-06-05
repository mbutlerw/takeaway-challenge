#Takeaway Challenge
==================
```
                            _________
              r==           |       |
           _  //            |  M.A. |   ))))
          |_)//(''''':      |       |
            //  \_____:_____.-------D     )))))
           //   | ===  |   /        \
       .:'//.   \ \=|   \ /  .:'':./    )))))
      :' // ':   \ \ ''..'--:'-.. ':
      '. '' .'    \:.....:--'.-'' .'
       ':..:'                ':..:'

 ```

#Features that need implementing

Create fake SMS client to test full functionality
https://robots.thoughtbot.com/testing-sms-interactions


#User Interface
```sh
2.3.1 :001 > require './lib/takeaway.rb'
 => true
2.3.1 :002 > takeaway = Takeaway.new <
 => ####
2.3.1 :003 > takeaway.add_menu_items({chips: 1.99, fish: 3.99})
 => {:chips=>1.99, :fish=>3.99}
2.3.1 :004 > takeaway.order("chips")
 => "1x chips added to basket, current total: 1.99"
2.3.1 :005 > takeaway.order("fish", 2)
 => "2x fish added to basket, current total: 9.97"
2.3.1 :006 > takeaway.order("chips", 3)
 => "3x chips added to basket, current total: 15.940000000000001"
2.3.1 :007 > takeaway.basket
 => "3x chips (@1.99 each), 2x fish (@3.99 each), current total: 15.940000000000001"
2.3.1 :008 > takeaway.checkout
 => "Thank you! Your order was placed and will be delivered before 21:56." </p>
```
