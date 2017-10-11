# test_calculator

Ruby exercise 11

## Instructions

1. Copy the below code into `test_calculator.rb`

```
require 'minitest/autorun'
require_relative 'calculator'

class TestCalculator < Minitest::Test

  def setup
    puts "set up"
    @calc = Calculator.new
  end

  def test_add
    assert_equal 4, @calc.add(2,2)
  end
  
  # Write test methods for subtract, multiply, and divide
  
  
  
  

  def teardown
    puts "tear down"
  end

  

end
```

2. Copy the below code into `calculator.rb`

```
class Calculator

    def add(a, b) 
      a + b
    end
    
end
```

## Running the test class

```
ruby test_calculator.rb
```