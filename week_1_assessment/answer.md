var = "arun" # string
num1= 12 # integer
num2 = 12.0 # float
result = True

arun@arun-OMEN-Laptop-15-ek0xxx:~/tech_interview/week_1_assessment$ irb
irb(main):001:0> cars= ["car1","car2"]
=> ["car1", "car2"]
=> {:wheels=>4, :Max=>"2ookm/hour", :coloe=>"whitw"}
=> {:wheels=>4, :Max=>"21okm/hour", :coloe=>"Black"}
Traceback (most recent call last):
        3: from /home/arun/.rbenv/versions/3.0.0/bin/irb:23:in `load'
.3.0/exe/irb:11:in `<top (required)>'
NoMethodError (private method `Array' called for {:wheels=>4, :Max=>"2ookm/hour", :coloe=>"whitw"}:Hash)
irb(main):005:0> cars.Array[1]
Traceback (most recent call last):
        5: from /home/arun/.rbenv/versions/3.0.0/bin/irb:23:in `<main>'
        4: from /home/arun/.rbenv/versions/3.0.0/bin/irb:23:in `load'
        3: from /home/arun/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/irb-1
        2: from (irb):4:in `<main>'
        1: from (irb):5:in `rescue in <main>'
NoMethodError (private method `Array' called for ["car1", "car2"]:Array)
irb(main):006:0> cars[1]
=> "car2"
irb(main):007:0> cars= [car1,car2]
=> [{:wheels=>4, :Max=>"2ookm/hour", :coloe=>"whitw"}, {:wheels=>4, :Max=>...
irb(main):008:0> cars[1]
# thank you emmma for your support this interview was very helpful
# soon i will give answers of yours other quetions
