# speed-of-light# Speed of light in a vacuum (in meters per second)
SPEED_OF_LIGHT = 299_792_458  # meters per second

def time_to_travel(distance):
    """
    Calculate the time it takes for light to travel a given distance.
    
    :param distance: Distance in meters
    :return: Time in seconds
    """
    time = distance / SPEED_OF_LIGHT
    return time

# Example usage:
distance_meters = 1_000_000  # 1 million meters
time_seconds = time_to_travel(distance_meters)

print(f"Time taken for light to travel {distance_meters} meters: {time_seconds} seconds")
