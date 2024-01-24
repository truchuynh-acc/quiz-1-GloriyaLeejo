[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Gloriya Leejo
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {
private:
    std::string model;
    int year;
    std::string color;

public:
    string getmodel(){
    return model;
    }

    string getyear(){
    return year;
    }
   
    string getcolor(){
    return color;
    }
void displayDetails() const {
        std::cout << "Model: " << getModel() << ", Year: " << getYear() << ", Color: " << getColor() << std::endl;
    }
};

int main() {
    Car myCar;


    myCar.displayDetails();

    return 0;
}


