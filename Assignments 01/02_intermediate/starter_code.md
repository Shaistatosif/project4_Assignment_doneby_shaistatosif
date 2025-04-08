def main():
    # Prompt for Earth weight
    earth_weight = float(input("Enter a weight on Earth: "))
    
    # Prompt for planet name
    planet = input("Enter a planet: ")
    
    # Dictionary of planet gravity multipliers relative to Earth
    planet_gravity = {
        "Mercury": 0.378,
        "Venus": 0.907,
        "Mars": 0.377,
        "Jupiter": 2.36,
        "Saturn": 0.916,
        "Uranus": 0.889,
        "Neptune": 1.12,
        "Pluto": 0.071
    }
    
    # Calculate weight on the selected planet
    planet_weight = earth_weight * planet_gravity[planet]
    
    # Print the result
    print(f"The equivalent weight on {planet}: {planet_weight}")

if __name__ == "__main__":
    main()