def celsius_to_fahrenheit(celsius):
    """Converts Celsius to Fahrenheit."""
    return (celsius * 9/5) + 32

# Test the conversion
temp_c = 25
temp_f = celsius_to_fahrenheit(temp_c)

print(f"Temperature in Celsius: {temp_c}°C")
print(f"Converted to Fahrenheit: {temp_f}°F")
