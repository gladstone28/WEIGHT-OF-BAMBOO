# Constants
density_kg_per_m3 = 600  # Average density of bamboo in kg/m^3, as an approximation.
length_m = 0.3048  # Length of bamboo in meters (1 foot).
pi = 3.141592653589793

# Assuming an average diameter for Bambusa vulgaris, let's say about 4 inches (0.1016 meters),
# to calculate the volume and then the weight.
diameter_m = 0.1016  # Average diameter in meters.

# Calculate the radius from the diameter
radius_m = diameter_m / 2

# Volume formula for a cylinder V = πr^2h
volume_m3 = pi * (radius_m ** 2) * length_m

# Weight calculation (mass = density * volume)
weight_kg = density_kg_per_m3 * volume_m3

# Convert weight to grams for a more intuitive measure in this context
weight_g = weight_kg * 1000  # 1 kg = 1000 g

weight_g
