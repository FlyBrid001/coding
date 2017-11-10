So go ahead, #UnboxYourself, think different and you should have the solution to the Buggy Code Challenge!

letters = []
printers = []
"Unbox Yourself".split('').each { |letter|
letters << letter
printers << Proc.new { puts letters.join }
} printers.map{|printer| printer.call } 
printers.each{|printer| printer.call }

put your solution in Solution~~~~~